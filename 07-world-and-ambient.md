# World, ambient life and small systems

Part of the [GTA V decompiled script findings](README.md).

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

## Ambient world scripts — mostly thin

- `ambient_ufos.c` — **12K, the smallest script found**. Sound-driven only
  (`PLAY_SOUND_FROM_COORD`), with `SPECIAL_EVIL_UFO_DEATH_RAY`.
- `ambient_diving.c` (52K) — `ADD_BLIP_FOR_RADIUS` search areas.
- `ambient_sonar.c` (80K) — minimal.
- `animal_controller.c` (2.1M) — `MIDSIZED_MESSAGE`; the animal spawning brain.

Note: `prop_bought_*` models appearing in these are **shared property
boilerplate**, not collectibles.

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

## `chop.c` (212K) — complete companion-dog system

The richest single find of this pass. Full animal AI for a rottweiler:

- `creatures@rottweiler@move` — locomotion
- `creatures@rottweiler@tricks@` — trick animations
- `creatures@rottweiler@indication@` — the scent-indication pose
- `creatures@rottweiler@melee@streamed_taunts@` — attack
- `creatures@rottweiler@amb@world_dog_barking@enter` / `@idle_a` / `@exit`
- `creatures@rottweiler@amb@sleep_in_kennel@`
- `creatures@rottweiler@in_vehicle@std_car` — riding in a car
- `misschop_vehicleenter_exit` — getting in and out

Everything a K9 unit or companion pet needs, including the scent indication that
police K9 scripts normally fake.

## `gpb_*` — 14 street characters / strangers

All exactly 68K (Pamela Drake 72K), one script each, identical structure:
`andymoon`, `baygor`, `billbinder`, `clinton`, `griff`, `jane`, `jerome`,
`jesse`, `mani`, `mime`, `pameladrake`, `superhero`, `tonya`, `zombie`.

No anim dicts — they run on scenarios and speech. Together with the four `pb_*`
performers, that is 18 worked examples of a wandering ambient character.

## World systems worth stealing

- **`restrictedareas.c` (40K)** — restricted-zone enforcement. Small.
- **`flyunderbridges.c` (52K)** — tracks flying under bridges, `MIDSIZED_MESSAGE`.
  The pattern generalises to any "player did a stunt" detector.
- **`forsalesigns.c`** — property for-sale signs.
- **`vehicle_plate.c`** and **`vehicle_stealth_mode.c` (28K)**.
- **`laptop_trigger.c` (128K)** and **`atm_trigger.c` (112K)** — prop-triggered
  interactions, the same object-brain idea as `ob_*`.
- **`save_anywhere.c`**, **`savegame_bed.c`** — save points.
- **`wp_partyboombox.c` (4K)** — boombox as a carried weapon/prop.
- **`mp_player_damage_numbers.c`** — floating damage numbers.
- **`mp_awards.c`**, **`mp_unlocks.c`** — award and unlock systems.
- **`shrinkletter.c` (40K)** — owns the `PSYCHOLOGY_REPORT` scaleform.
- **`ufo.c` (68K)** — larger than `ambient_ufos.c`.
- **`photographywildlife.c`** — wildlife photography objectives.
- **`murdermystery.c`** — has its own `vintage_filmcan` prop.
- **`dialogue_handler.c`**, **`localpopulator.c`**, **`spawn_activities.c`**,
  **`walking_ped.c`**, **`idlewarper.c`** — population and dialogue plumbing.
- **`minigame_ending_stinger.c`**, **`minigame_stats_tracker.c`** — the shared
  ending/results pieces every activity uses.
- **`celebrations.c` (9.1M)**, **`celebration_editor.c`** — the celebration
  sequence driver behind `MP_CELEBRATION`.

## Nightlife

`nightclubpeds.c`, `sclub_front_bouncer.c`, `stripperhome.c`,
`si_dancing_activity.c`, `music_studio_smoking.c`, `mansion_club_bar.c`,
`fairgroundhub.c`, `luxe_veh_activity.c`.

`sclub_front_bouncer.c` is the door-bouncer behaviour, and the
`BOUNCER_EJECT_GENERIC` speech context (745 uses, by far the most-used speech
line in the repo) belongs to it.
