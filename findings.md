# GTA V Decompiled Scripts — FiveM Port Findings

Notes on mining this repo (build 1.73-3889.0, 1156 scripts) for mechanics worth
porting to FiveM. Extracted data is quoted verbatim from the decompiles.

## Repo shape

- `decompiled_scripts/` — 1156 `.c` files, readable output: real native names,
  `joaat("...")` left as literal strings, control flow intact.
- `native_tables/` — per-script native tables.
- `scripts/` — raw `_ysc` disassembly.

Rough buckets by prefix: 142 `am_*`, 125 `fm_*`, 70 `gb_*`, 38 `re_*`, 32
`launcher_*`, 26 `ob_*`.

**Do not start with the big files.** `freemode.c` is 31 MB and
`fm_mission_controller_v3.c` is 27 MB, and much of that bulk is boilerplate
stamped into every script — the shared money/stat plumbing alone is thousands of
lines that reappears in a 1.6 MB vending machine script. Value is concentrated in
the small ones. Always grep first, read narrow slices second.

## The goldmine: `ob_*` and `re_*`

26 object-interaction scripts and 38 random events, each a self-contained worked
example of one mechanic.

`ob_*` scripts run as **object brains**: attached to a prop model and woken by
`IS_OBJECT_WITHIN_BRAIN_ACTIVATION_RANGE` when a player approaches. That maps
cleanly onto a target/interact system in FiveM.

### Extracted anim data

| Script | Dict | Anims / props |
|---|---|---|
| `ob_vend1/2` | `MINI@SPRUNK@FIRST_PERSON` | `PLYR_BUY_DRINK_PT1/PT2/PT3` |
| `ob_mp_bed_*` | `mp_bedmid` | `f_getin_l_bighouse`, `f_sleep_l_loop_bighouse`, `f_getout_l_bighouse` (`_r` variants in bed_high) |
| `ob_mp_shower_med` | `ANIM@MP_YACHT@SHOWER@MALE@` / `@FEMALE@` | `male_shower_enter_into_idle`, `male_shower_idle_a`–`d`, `Male_Shower_Exit_To_Idle`, prop `p_mp_showerdoor_s` |
| `ob_telescope` | `MINI@TELESCOPE` | `ENTER_FRONT`/`IDLE`/`EXIT_FRONT`, plus `UPRIGHT_*` and `PUBLIC_*` variants; props `prop_telescope`, `prop_telescope_01` |
| `ob_jukebox` | `anim@amb@clubhouse@jukebox@` | scaleform track menu |
| `ob_poledancer` | `MISSSTRIP_CLUB` | `Poledance_01` |
| `ob_mp_stripper` | `mini@strip_club@lap_dance_2g@*` | `ld_2g_intro_m/_s1/_s2` + `_face` variants |
| drinking family | `MP_SAFEHOUSEBEER@`, `MP_SAFEHOUSEWINE@`, `MP_SAFEHOUSEWHISKEY@`, `mp_safehousewheatgrass@`, `mp_safehousebong@` | enter/idle/exit **plus drunk-state exits**: `exit_sober_bot`, `exit_slightly_drunk_bot`, `exit_moderately_drunk_bot`, `exit_drunk_bot`, with matching facials and named cameras |
| `ob_tv` / `ob_franklin_tv` | — | channel list `PL_STD_CNT`, `PL_LO_WZL`, `PL_MP_WEAZEL`, `PL_LES1_FAME_OR_SHAME`, … |

Drunk movement clipsets: `MOVE_M@DRUNK@SLIGHTLYDRUNK`,
`MOVE_M@DRUNK@MODERATEDRUNK_HEAD_UP`. A complete sober→drunk progression exists.

Drink/consume props: `prop_cs_beer_bot_01`, `p_wine_glass_s`, `prop_bong_01`,
`p_cs_joint_01`, `prop_cigar_03`, `p_whiskey_bottle_s`, `p_w_grass_gls_s`.

### `ob_cashregister` — smallest useful script (~170 lines)

No animation. Polls `HAS_OBJECT_BEEN_BROKEN` on the register prop, then spawns
cash via `GET_SAFE_PICKUP_COORDS` so it never lands inside geometry.
SP drops 70–120 (`pickup_money_med_bag`), MP 50–100 scaled by a global
multiplier (`prop_cash_pile_01`).

### `ob_poledancer` — ambient performer template (~170 lines)

Freeze prop, spawn ped at its coords, loop anim, and call
`SET_ENTITY_ANIM_CURRENT_TIME` with a random 0–1 float so multiple dancers do
not move in lockstep. Watches for player proximity, shooting or touching, then
bails into `TASK_COWER`.

### `re_*` random events — spawn recipes with exact models

Notable ones and their anim dicts:

- `re_paparazzi` — `random@paparazzi@pap_anims/@peek/@trans/@wait`, plus panic
  passenger `veh@std@ps@idle_panic`. Full pursue-and-flee AI loop.
- `re_drunkdriver` — `random@drunk_driver_1/_2` + the drunk movement clipsets.
- `re_atmrobbery` — `random@atmrobberygen@male` / `@female`.
- `re_shoprobbery` — `random@robbery`, `random@shop_robbery`.
- `re_hitch_lift` — `random@hitch_lift`, facials `facials@gen_female@base`.
- `re_gang_intimidation`, `re_lured`, `re_muggings`, `re_burials`,
  `re_domestic`, `re_prisonvanbreak`, `re_getaway_driver`, `re_securityvan`,
  `re_homeland_security`, `re_stag_do`, `re_cartheft`, `re_bikethief`.

Each carries its ped and vehicle model list, scenario strings
(`WORLD_HUMAN_SMOKING`, `WORLD_HUMAN_STAND_MOBILE`, `WORLD_HUMAN_HANG_OUT_STREET`,
`WORLD_VEHICLE_DRIVE_SOLO`) and branching outcomes.

## Deep dive: vending machine (`ob_vend1.c`) — PORTED

Built as `od_vending` for the odessa server. Full flow as shipped by R*:

1. Stash weapon to unarmed and hide it, clear stealth movement,
   `CLEAR_AREA_OF_PROJECTILES` radius 3.
2. `TASK_LOOK_AT_ENTITY` 2000 ms + `TASK_GO_STRAIGHT_TO_COORD` to offset
   `{0, -0.97, 0.05}` from the machine, **forced to the machine's own heading**,
   0.1 tolerance. This alignment is why the vanilla anim never looks off-centre.
3. Wait for `GET_SCRIPT_TASK_STATUS(script_task_go_straight_to_coord) == 7`.
4. `PLYR_BUY_DRINK_PT1` (flag 1310720) — can created at **0.31** and attached to
   bone **28422**; chains to PT2 at 0.98.
5. `PLYR_BUY_DRINK_PT2` (flag 1048576) → `PLYR_BUY_DRINK_PT3` (flag 1048624).
6. Can released at **0.306 of PT3**: `DETACH_ENTITY`, then
   `APPLY_FORCE_TO_ENTITY(can, 1, {6.0, 10.0, 2.0}, ...)` — the throw — then
   `SET_OBJECT_AS_NO_LONGER_NEEDED`. **It is never deleted on success.**
7. Abort path deletes only if `IS_ENTITY_A_MISSION_ENTITY`, and **always
   detaches first**.

Timeouts: 2500 ms for the walk, 15000 ms per anim. Interrupt check is
damaged-by-any ped/vehicle/object, followed by `CLEAR_ENTITY_LAST_DAMAGE_ENTITY`.
Audio bank `VENDING_MACHINE`. Help labels `VENDHLP` / `VENDCSH`.
Early cancel uses `STOP_ANIM_TASK(..., -1.5)` — a blend-out, not a hard stop.

Machine models: `prop_vend_soda_01/02`, `prop_vend_water_01`,
`prop_vend_coffe_01`, `prop_vend_snak_01`, `prop_vend_fags_01`,
`prop_vend_condom_01`, `sf_prop_sf_vend_drink_01a` (needs a higher offset:
stand `{0,-0.97,1.0}`).

Can props (the complete set — only these exist): `prop_ld_can_01b`,
`prop_ecola_can`, `sf_prop_sf_can_01a`. Also `prop_energy_drink`,
`p_amb_coffeecup_01`, `prop_cs_paper_cup`.

**Gotchas learned the hard way:**
- An attached entity will not delete. Detach first, always.
- The soda machines share models, so which brand a machine is cannot be derived
  from the model — use a menu.
- Only `PLYR_BUY_DRINK_PT1/2/3` exist in the whole game. There is no alternate
  button-press animation; the hand path is authored data, not script-aimed.

Related tunables: `vending_machine_sprunk_can_cost`, `shop_sprunk_can_cost`,
`property_sprunk_can_cost`, `sprunk_health_replenish_multiplier`,
`po_coupon_sprunk` (free-drink coupons).

## Next candidates, ranked by reuse of the vending skeleton

1. **Beds** (`ob_mp_bed_*`) — no cameras, no scaleform. Enter → loop → exit.
2. **Cash register** (`ob_cashregister`) — tiny, reactive rather than
   interactive, different pattern.
3. **Telescope** (`ob_telescope`) — adds camera + FOV zoom + timecycle modifier +
   2 scaleforms. Sound sets `TELESCOPE_COIN_OP` / `_HIGH_END` / `_DOMESTIC`;
   the coin-op is a paid interaction.
4. **Jukebox** (`ob_jukebox`) — scaleform track menu, disabled controls.
5. **Shower** (`ob_mp_shower_med`) — 4 cameras, 13 `SET_CAM_PARAMS`. Most work.

## Minigames & activities

| Script | Size | Anim dicts | Custom scaleforms |
|---|---|---|---|
| `darts.c` | 628K | `mini@dartsoutro` | `darts_scoreboard` |
| `golf.c` | 3.0M | `mini@golfclub_bag`, `mini@golfclubhouse` | `golf`, `golf_floating_ui` |
| `tennis.c` | 2.7M | `facials@gen_male@base`, `facials@gen_female@variations@happy`, … | — |
| `am_armwrestling.c` | 2.7M | `mini@arm_wrestling` | `COUNTDOWN` |
| `range_modern.c` | 2.5M | `mini@shoot_range`, `mini@ears_defenders` | `SC_LEADERBOARD` |
| `pilot_school.c` | 2.6M | `oddjobs@basejump@`, `veh@helicopter@rps@base` | `TV_FRAME`, `MP_MEDAL_FREEMODE`, `mission_quit` |
| `yoga.c` | 1.9M | `mini@yoga`, `missfam5_yoga` | `yoga_buttons`, `yoga_keys` |

`darts_scoreboard`, `golf_floating_ui`, `yoga_keys` and `taxi_display` are
purpose-built scaleforms — usable directly, no NUI needed.

### Reusable scaleform catalogue

Seen across many scripts, safe to lean on:
`instructional_buttons`, `GENERIC_INSTRUCTIONAL_BUTTONS`, `MP_BIG_MESSAGE_FREEMODE`,
`MIDSIZED_MESSAGE`, `SC_LEADERBOARD`, `COUNTDOWN`, `MP_MEDAL_FREEMODE`,
`BREAKING_NEWS`, `SOCIAL_CLUB_TV`, `MP_SPECTATOR_CARD`, `MP_SPECTATOR_OVERLAY`.

## Heist minigames — scaleform names

From `gb_data_hack.c`, `gb_casino_heist.c`, `fm_mission_controller_2020.c`:

- `VAULT_DRILL` — the drilling minigame.
- `VAULT_LASER` — laser cutting.
- `DIGITAL_SAFE_DISPLAY` — keypad / safe entry.
- `HACKING_MESSAGE` — hacking overlay.
- `SECURITY_CAM`, `DRONE_CAM` — camera feeds.
- `digiscanner` — scanner overlay.
- `POWER_PLAY_GENERIC`, `mp_mm_card_freemode`, `mp_matchmaking_card`.

These are the exact movies behind the vanilla heist minigames. Each needs its
`BEGIN_SCALEFORM_MOVIE_METHOD` call sequence traced before use.

## Casino

Scripts: `blackjack.c` (608K), `casinoroulette.c` (7.7M), `casino_slots.c`
(360K), `casino_lucky_wheel.c` (1.5M), `bigwheel.c` (660K), plus
`am_mp_casino.c`, `am_casino_peds.c` (9.5M) and six `casino_*_seating.c`.

- `casino_slots.c` drives a single `SLOT_MACHINE` scaleform — the smallest,
  most self-contained casino game and the obvious first port.
- `blackjack.c` and `casinoroulette.c` use only `instructional_buttons` /
  `GENERIC_INSTRUCTIONAL_BUTTONS`; table state is data-driven and the dealer
  animation lives in `am_casino_peds.c`.
- `am_casino_peds.c` holds the ambient casino population under
  `ANIM@AMB@CASINO@…`: `HANGOUT@PED_FEMALE@STAND@01A@BASE` / `@IDLES` /
  `@IDLES_CONVO` (numbered variants), `BAR@SPECIAL_PEDS@LAUREN@01A@BASE@`,
  `BAR@SPECIAL_PEDS@TAYLOR@01A@BASE@`, and brawl reactions
  `BRAWL@REACTS@BAR@` / `@SLOTS@` / `@STANDING@`.

## Nightclub (`am_mp_nightclub.c`, 14M)

Scaleforms `DANCER`, `SECURITY_CAM`. Anim dicts:

- Crowd: `anim@amb@nightclub@dancers@crowddance_groups@low_intensity`
- Player bartender: `anim@amb@nightclub@mini@drinking@bar@player_bartender@base`
  with `@one` `@two` `@three` `@four` `@idle_a` — a full serving sequence.
- Drinking at the bar: `…@bar@drink@base` / `@beer` / `@one`–`@four`, plus a
  `drink_v2` variant.
- Shots with drunk states: `anim@amb@nightclub@mini@drinking@drinking_shots@ped_a@drunk@`
- Champagne: `ANIM@AMB@NIGHTCLUB@MINI@DRINKING@CHAMPAGNE_DRINKING@BASE@`

The player-bartender set is the standout — a complete serve-drinks-behind-a-bar
mechanic, numbered by how many drinks are being carried.

## Jobs

- `taxiservice.c` (272K) — custom `taxi_display` scaleform for the fare meter.
  Small and readable; a proper taxi job template.
- `towing.c` (324K) — `MIDSIZED_MESSAGE` only; hook mechanics are native calls.
- `carwash1.c` (776K) — no scaleform, pure effects and vehicle state.
- `hunting2.c` (1008K) — animal AI worth stealing: `creatures@deer@amb@world_deer_grazing@base`
  with `@enter` `@exit` `@idle_a`, plus `oddjobs@hunter` and an elk-call facial
  (`facials@p_m_one@variations@elkcall`).

## `gb_*` business & VIP work (70 scripts)

Mostly **boilerplate-heavy and low yield** for anim mining. The big ones
(9–16 MB: `gb_deathmatch`, `gb_casino_heist`, all the `gb_biker_*`) share an
identical shell — spectator cards, `anim@amb@facility@hanger_doors`,
`SOCIAL_CLUB_TV`, `BREAKING_NEWS` — with the mission logic buried deep inside.

The VIP work scripts are the small, readable ones and the better starting point:

- `gb_sightseer.c` (1.7M) — checkpoint collection loop.
- `gb_headhunter.c` (1.6M) — targets with bodyguard AI.

Both use only the shared matchmaking/spectator scaleforms, so their value is the
job *structure* (objective spawning, timers, blips, rival players), not assets.
`gb_biker_safecracker.c` and `gb_data_hack.c` are where the safe and hacking
minigames live, but both are ~10 MB and need targeted greps to reach the logic.

## Phone (`cellphone_controller.c` + ~40 `app*.c`)

The controller is driven almost entirely through scaleform: **108
`SCALEFORM_MOVIE_METHOD` calls**, with `SET_MOBILE_PHONE_POSITION` for placement.
The phone is a scaleform rendered to a render target, not NUI.

App scripts range from tiny to enormous — `appextraction.c` is 8K,
`appinternet.c` is 12M (the whole in-game web), `appbusinesshub.c` and
`apparcadebusiness.c` ~7.5M each. Small ones worth reading as templates:
`appbroadcast.c` (16K), `appchecklist.c` (28K), `apphs_sleep.c` (20K),
`appmedia.c` (20K), `appemail.c` (108K), `appcamera.c` (272K, selfie mode).

GXT label prefix for phone strings is `CELL_*` (`CELL_SIGHTS`, `CELL_SECHACK`,
`CELL_HACKER_ROB`, `CELL_EXTRACT`, `CELL_BOSSAGE`, `CELL_CIRCBREAK`, …).

## Races (`fm_race_controler.c`, 15M)

Checkpoint and timing system, all standard natives — portable as-is:

- `CREATE_CHECKPOINT` with `SET_CHECKPOINT_RGBA` and **`SET_CHECKPOINT_DIRECTION`**
  (the arrow that points at the next checkpoint — 18 call sites).
- Blip control: `SET_BLIP_SPRITE`, `SET_BLIP_SCALE`, `SET_BLIP_PRIORITY`,
  `SET_BLIP_ROUTE`, `SET_BLIP_DISPLAY`, `SET_BLIP_NAME_FROM_TEXT_FILE`.
- Timing is plain `GET_GAME_TIMER` deltas — 125 call sites, no special natives.

Race scaleforms: `COUNTDOWN`, `DRAG_RACE`, `MP_CELEBRATION` (+ `_BG` / `_FG`),
`OPEN_WHEEL_HEALTH_INDICATOR`, `BLIMP_TEXT`, `SAVING_FOOTER`.

`MP_CELEBRATION` with its separate background and foreground movies is the
vanilla end-of-race results sequence — reusable for any job payout screen.

## Arcade cabinets — self-contained playable games

Each cabinet is its own script, which makes them unusually good port targets:

| Script | Size | Notes |
|---|---|---|
| `am_mp_arcade_fortune_teller.c` | 60K | Tiniest activity in the repo |
| `grid_arcade_cabinet.c` | 276K | Full texture set, see below |
| `photographymonkey.c` | 460K | `MIDSIZED_MESSAGE` |
| `am_mp_arcade_claw_crane.c` | 1.8M | Claw machine |
| `am_mp_arcade_love_meter.c` | 1.8M | |
| `am_mp_arcade_strength_test.c` | 1.8M | Own scaleform **`AXE_OF_FURY`** |
| `degenatron_games.c` | 1.9M | |
| `camhedz_arcade.c` | 2.1M | |
| `gunslinger_arcade.c` | 2.1M | |
| `ggsm_arcade.c` | 2.2M | |

Plus `am_mp_arcade.c` (9.7M, the property), `am_mp_arcade_peds.c`,
`arcade_seating.c`, `apparcadebusiness.c`.

**They do not use render targets or scaleform for the screen.** The cabinets
draw with `DRAW_SPRITE` from streamed texture dictionaries. `grid_arcade_cabinet.c`
exposes the whole set: `MPArcadeCabinetGrid`, `MPArcadeCabinetGridHUD`,
`MPArcadeCabinetGridTiles`, and per-player sprites
`MPArcadeCabinetGridPlayerBlue` / `Green` / `Purple` / `Yellow`.

That means a cabinet game is: draw sprites each frame from a texture dict, read
controls, keep score. Very portable — the same approach works for any custom
minigame drawn over a screen prop.

### Correction on `VAULT_DRILL` / `VAULT_LASER`

These two are requested by nearly every arcade and heist script as **shared
boilerplate**, so grepping for them does not locate the drilling logic. The real
implementation lives in the casino heist scripts; treat the name as a pointer,
not a location.

## Shops — camera and component work, not animation

`shop_controller.c` (9.2M), `clothes_shop_sp.c` (7.6M), `carmod_shop.c` (8.3M),
`tattoo_shop.c` (2.8M), `hairdo_shop_sp.c` (3.4M), `gunclub_shop.c` (3.9M).

Almost no anim dicts. The mechanics are native-driven:

- **Clothing** — `SET_PED_COMPONENT_VARIATION` (101), `SET_PED_PROP_INDEX`,
  `GET_NUMBER_OF_PED_TEXTURE_VARIATIONS`, `SET_PED_MICRO_MORPH`.
- **Car mods** — `GET_NUM_VEHICLE_MODS` (145), `SET_VEHICLE_MOD` (107),
  `SET_VEHICLE_MOD_COLOR_` (45), with 39 `SET_CAM_ACTIVE` / 28 `SET_CAM_PARAMS`
  driving the browsing camera. This is the best reference for a mod-shop camera.
- `ADD_PED_DECORATION_FROM_HASHES` appears ~200 times in *all* shop scripts —
  shared boilerplate, not tattoo-specific.

`gunclub_shop.c` is the only one with a real anim dict:
`ANIM@SCRIPTED@FREEMODE_NPC@FIX_AGY_IG2_REQUISITIONS@`.

## Properties — mostly boilerplate, but named render scaleforms

`am_mp_property_int.c` (18M), `am_mp_car_meet_property.c` (14M),
`am_mp_auto_shop.c` (14M), `am_mp_submarine.c` (13M), `am_mp_arcade.c` (9.7M).

Low yield overall, but the custom sign/board scaleforms are worth knowing:
`CLUBHOUSE_NAME`, `ORGANISATION_NAME`, `AUTO_SHOP_CREW_NAME`,
`BIKER_MISSION_WALL`, and `SECURITY_CAM` (used across nightclub, submarine,
auto shop and property interiors).

`am_mp_car_meet_property.c` carries `SC_LEADERBOARD` for the test-track times.

## Launchers

32 `launcher_*.c` scripts, all small (`launcher_epsilon.c` 920K down to ~100K).
They are trigger/availability wrappers around SP activities — useful as a model
for gating content by time, location and player state, not for assets.

## `am_*` activities (68 scripts, excluding `am_mp_*` and `*_peds`)

Unlike `gb_*`, many of these are small and self-contained. Smallest first:

| Script | Size | Notes |
|---|---|---|
| `am_beach_washup_cinematic.c` | 16K | |
| `am_ga_pickups.c` | 40K | |
| `am_prison.c` | 44K | |
| `am_joyrider.c` | 56K | NPC steals your parked car |
| `am_backup_heli.c` | 80K | Callable support |
| `am_airstrike.c` | 88K | Callable support |
| `am_doors.c` | 104K | **Door locking / management** |
| `am_ammo_drop.c` | 120K | Callable support |
| `am_boat_taxi.c` | 140K | |
| `am_distract_cops.c` | 144K | |
| `am_bru_box.c` | 204K | |
| `am_rollercoaster.c` | 212K | |
| `am_ferriswheel.c` | 232K | |
| `am_taxi.c` | 376K | **See below** |

### `am_taxi.c` — the MP taxi job

The only one here with real assets:

- Scaleform **`TAXI_HAIL`** — the hailing prompt.
- Anim dict **`ODDJOBS@TAXI@DRIVER`**.

Combined with SP `taxiservice.c` (272K) and its **`taxi_display`** fare-meter
scaleform, these two cover a complete taxi job without writing any UI.

## Rides (cable car, rollercoaster, ferris wheel)

`cablecar.c` (632K), `rollercoaster.c` (596K), `bigwheel.c` (660K),
`am_rollercoaster.c` (212K), `am_ferriswheel.c` (232K).

No anim dicts — rides are built from entity attachment and cameras:

- `cablecar.c` — 19 `ATTACH_ENTITY_TO_ENTITY`, 15 `SET_ENTITY_COORDS`,
  14 `PLAY_SOUND_FROM_ENTITY`, 5 `SET_CAM_ACTIVE` / 4 `SET_CAM_PARAMS`.
- `rollercoaster.c` — `SET_ENTITY_COORDS` + `FREEZE_ENTITY_POSITION` with
  `SET_CAM_ROT` / `SET_CAM_PARAMS`.

The pattern is: freeze the player, attach to a moving carrier entity, drive a
scripted camera. Directly reusable for any custom ride or elevator.

## Ambient world scripts — mostly thin

- `ambient_ufos.c` — **12K, the smallest script found**. Sound-driven only
  (`PLAY_SOUND_FROM_COORD`), with `SPECIAL_EVIL_UFO_DEATH_RAY`.
- `ambient_diving.c` (52K) — `ADD_BLIP_FOR_RADIUS` search areas.
- `ambient_sonar.c` (80K) — minimal.
- `animal_controller.c` (2.1M) — `MIDSIZED_MESSAGE`; the animal spawning brain.

Note: `prop_bought_*` models appearing in these are **shared property
boilerplate**, not collectibles.

## Launchers, revisited

32 `launcher_*.c`, all trigger/availability wrappers. Model for gating content
by time, location and player state. No assets.

## Small uncategorised scripts — the last good seam

Filtering out every prefix already swept, plus stubs, leaves a set of genuinely
small self-contained systems. These are the most approachable scripts in the repo.

### Collectible hunts

- **`spaceshipparts.c` (36K)** — a complete collectible-hunt system. Uses
  `MIDSIZED_MESSAGE` and `HUD_AWARDS`, with GXT labels `SSHIP_COLLECT`,
  `COLLECTED`, `PEYOTE_COMPLETED` and a `SHARD_ANIM_OUT` transition. This is the
  template for any "find N things scattered around the map" feature — progress
  tracking, award popup and completion state in one small file.
- **`underwaterpickups.c` (32K)** — seabed pickup placement. Straight list of
  standard pickup hashes: `pickup_health_standard`, `pickup_armour_standard`,
  `pickup_money_case`, `pickup_weapon_crowbar`, `pickup_weapon_grenade`,
  `pickup_weapon_grenadelauncher`, `pickup_weapon_assaultrifle`. Good reference
  for pickup types and for scattering loot underwater.

### Ambient street characters (`pb_*`)

Tiny scripts, one per character, all following the same shape — spawn a ped,
run a looping performance, react to the player:

- `pb_busker.c` (20K) — dict `amb@BUSKER`, ped `a_f_m_bevhills_02`.
- `pb_preacher.c` (16K) — dict `amb@PREACHER`, ped `s_m_m_strpreach_01`,
  speech label `PREACH`.
- `pb_homeless.c` (24K) — dict `amb@drug_dealer`, peds `a_m_o_tramp_01`,
  `g_m_y_strpunk_01`.

Each also references `player_timetable_scene`. Together with `ob_poledancer`
these are the cleanest ambient-NPC templates in the repo — ideal for populating
a city with street life.

### Other systems worth knowing

- **`drunk_controller.c` (16K)** — the drunk state machine. `DRUNK_SHAKE` camera
  shake and a `drunk` clipset, plus `SAFEHOUSE_STONED_MICHAEL`. Pairs directly
  with the safehouse drinking anims and `MOVE_M@DRUNK@*` clipsets already noted.
- **`vehicle_stealth_mode.c` (28K)** — toggle system with audio labels
  `STEALTH_ON` / `STEALTH_OFF` (plus `_P` / `_S` variants).
- **`emergencycall.c` (16K)** + `emergencycalllauncher.c` (24K) — 911 calls,
  routed through `cellphone_flashhand`.
- `fake_interiors.c` (20K), `controller_races.c` (16K),
  `controller_ambientarea.c` (12K), `minigame_stats_tracker.c` (12K),
  `context_controller.c` (24K), `charactergoals.c` (32K),
  `ambientblimp.c` (16K), `buddydeathresponse.c` (12K).
- `scaleformtest.c` and `scaleformminigametest.c` (12K each) — R* test harnesses,
  useful as minimal scaleform API examples.

## Duplication warning

Large parts of the repo are near-identical clones. Do not mistake them for
distinct systems:

- **13 `*_carmod.c` scripts**, all ~8.3M — `arena_`, `base_`, `car_meet_`,
  `hacker_den_`, `hangar_`, `mansion_`, `tuner_property_`, `personal_`, etc.
  All clones of `carmod_shop.c`.
- **~10 `*_seating.c` scripts**, all ~8.4M — `mansion_`, `fixer_hq_`,
  `salvage_yard_`, `multistorey_garage_`, `juggalo_hideout_`, `base_lounge_`.
- Dozens of 1K stubs: `*_test.c`, `debug_*.c`, `globals_*_registration.c`.

Read one of each family, ignore the rest.

## Rare-scaleform sweep — the fastest way to find unique mechanics

Counting every `REQUEST_SCALEFORM_MOVIE` across all 1156 scripts and keeping
only names used **three times or fewer** surfaces the one-off systems, because
shared boilerplate appears in dozens of files. Command worth reusing:

    grep -ohE 'REQUEST_SCALEFORM_MOVIE\("[^"]+"' *.c \
      | sed 's/.*("//;s/"//' | sort | uniq -c | sort -n | awk '$1<=3'

### Best hits, mapped to their scripts

| Scaleform | Script | Size |
|---|---|---|
| `ATM` | `atm_trigger.c` | 112K |
| `LETTER_SCRAPS` | `letterscraps.c` | 48K |
| `dont_cross_the_line` | `dont_cross_the_line.c` | 164K |
| `SLOT_MACHINE` | `casino_slots.c` | 360K |
| `taxi_display` | `taxiservice.c` | 272K |
| `AXE_OF_FURY` | `am_mp_arcade_strength_test.c` | 1.8M |
| `mission_complete` | `minigame_stats_tracker.c` | 12K |
| `PLAYER_SWITCH`, `PLAYER_SWITCH_STATS_PANEL` | `selector.c` | 2.1M |
| `remote_sniper_hud`, `REMOTE_SNIPER_LOADING` | `martin1.c` | |
| `CASINO_HEIST_BOARD_PREP` / `_SETUP` / `_FINALE` | `gb_casino_heist_planning.c` | |
| `BANK_JOB_LOGIN` | `gb_bank_job.c` | |
| `DIGITAL_CAMERA` | `maintransition.c` | |
| `TEXTFIELD` | `am_contact_requests.c` | |

**`atm_trigger.c` (112K)** — a dedicated `ATM` scaleform and a small script.
Probably the single easiest UI-bearing system to port.

**`letterscraps.c` (48K)** — second complete collectible hunt alongside
`spaceshipparts.c`, with its own `LETTER_SCRAPS` scaleform. Two independent
implementations of the same idea to compare.

**`minigame_stats_tracker.c` (12K)** owns `mission_complete` — a tiny script
holding the generic completion screen. Useful for any activity payout.

### Terminal / computer UIs (all in phone apps)

`ROBBERY_COMPUTER` (`apphackerden.c`), `hacker_truck_desktop`
(`apphackertruck.c`), `securoserv` (`appsecuroserv.c`), `BOUNTY_COMPUTER`
(`appbailoffice.c`), `AVENGER_OPERATIONS_TERMINAL`, `JHPB_02_Laptop`,
`FIXER_APP`, `COVERT_OPS`.

Ready-made computer interfaces — no NUI needed for a laptop or terminal prop.

### Business management UIs

`NIGHTCLUB`, `BIKER_BUSINESSES`, `ARCADE_MANAGEMENT`, `ARCADE_BUSINESS_HUB`,
`warehouse`, `IMPORT_EXPORT_WAREHOUSE`, `HANGAR_CARGO`, `DISRUPTION_LOGISTICS`,
`SALVAGE_PLANNING`, `SALVAGE_VEHICLE_TARGETS`, `STARTER_PACK_BROWSER`.

### Misc named scaleforms

`MP_MENU_GLARE` (`wardrobe_mp.c`), `camera_gallery` (all `*_creator.c` —
the snapmatic gallery), `MP_MISSION_DETAILS_CARD`, `ARENA_CAREER_WALL`,
`YACHT_GAMERNAME`, `ORBITAL_CANNON_CAM`, `PARTY_BUS`, `SPLASH_TEXT`,
`graphic_design`, `font_lib_web`, `POWER_PLAY_*` (turf, vehicle, biker,
day_night, special_races).

`p_bubblegum` in `scaleformminigametest.c` — R* test harness, minimal
scaleform example.

## Creators

`creator.c` (4.7M), `fm_race_creator.c` (21M), `fm_deathmatch_creator.c` (14M),
`public_mission_creator.c` (13M), plus capture/LTS/survival variants.

Editor UIs rather than mechanics. Their one reusable asset is `camera_gallery`,
and they are the best reference for prop-placement tooling if a server ever
needs an in-game editor.

## Activity anim dictionaries (`mini@` / `oddjobs@`)

Listing every `mini@` and `oddjobs@` dict repo-wide is a better sweep than the
rare-name trick for animations, because these prefixes are activity-specific by
convention. The high-value results, with the script that implements each:

### `mini@cpr@` — CPR / revive (`fanatic1.c`)

Four dicts: `mini@cpr@char_a@cpr_str`, `char_a@cpr_def`, `char_b@cpr_str`,
`char_b@cpr_def` (`_str` = struggling, `_def` = default; `char_a`/`char_b` are
the two roles — medic and patient).

Anims: `cpr_intro`, `cpr_pumpchest`.

A two-person synced revive animation, exactly what an EMS script needs. The
paired `char_a`/`char_b` structure means medic and patient can be driven
together as a sync scene.

### `mini@safe_cracking` — full safe-cracking minigame

Used by `business_battles.c` and all three `fm_mission_controller*` variants.
The complete anim set is present:

- `step_into` — approach
- `idle_base`, `idle_look_around`, `idle_heavy_breathe` — waiting states
- `dial_turn_clock_fast`, `dial_turn_anti_fast` — the dial in both directions
- `DOOR_OPEN_SUCCEED_STAND`, `DOOR_OPEN_SUCCEED_STAND_SAFE` — success

Everything needed for a dial-turning safe minigame, including nervous idles.
`gb_biker_safecracker.c` is the other implementation.

### `mini@repair` — vehicle repair (`fbi4_prep2.c`)

Single anim `fixing_a_ped`. The mechanic-job animation.

### `mini@biotech@blowtorch_str` / `_def` — cutting

`fbi5a.c`, `fm_mission_controller_2020.c`, `public_mission_controller.c`.
Blowtorch/cutting for break-ins.

### Others

- `mini@racing@bike@`, `mini@racing@quad@` — `offroad_races.c`
- `mini@ears_defenders` — `range_modern.c`, ear defenders at the range
- `mini@arm_wrestling`, `mini@darts` (+ `dartsintro`, `dartsintro_alt1`,
  `dartsoutro`), `mini@golf` (+ `golfclub_bag`, `golfclubhouse`),
  `mini@tennis` (+ `@female`, `tennisexit@male`/`@female`), `mini@shoot_range`

## Sweeps that were low yield

Recorded so they are not repeated:

- **Rare anim dicts (`<=2` scripts)** — returns mostly standard
  `amb@world_human_*` scenario clipsets (guard patrol, hang out street, stand
  impatient, smoking, tourist mobile). These are well-known scenario animations,
  not hidden mechanics. The `mini@`/`oddjobs@` prefix sweep above is the better
  tool.
- **Rare PTFX assets (`<=2` scripts)** — almost entirely event/DLC-specific
  effect bundles: `proj_xmas_firework`, `scr_indep_parachute`,
  `scr_indep_wheelsmoke`, `scr_mp_tankbattle`, `scr_xm_stealcar`,
  `scr_bike_contraband`, `scr_impexp_ploughed`, `scr_tn_phantom`. Useful only if
  chasing a specific effect; no general mechanics.
