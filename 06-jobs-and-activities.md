# Jobs, activities and races

Part of the [GTA V decompiled script findings](README.md).

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

## Launchers, revisited

32 `launcher_*.c`, all trigger/availability wrappers. Model for gating content
by time, location and player state. No assets.

## Bail bond bounty hunting

`bailbond1.c` through `bailbond4.c` (~930K each) plus `bailbond_launcher.c`
(264K) and `postkilled_bailbond2.c`. Four complete bounty targets with a
launcher that gates availability — a ready-made bounty job structure.

## Racing variants beyond `fm_race_controler`

`country_race.c`, `offroad_races.c`, `stunt_plane_races.c`, `mission_race.c`,
`mg_race_to_point.c`, `triathlonsp.c`.

`mg_race_to_point.c` is the simplest race form — a single point-to-point dash.
