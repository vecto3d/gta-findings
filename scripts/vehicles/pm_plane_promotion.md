# pm_plane_promotion.c

Vehicles script. 1 models; 2 particle effects.

| | |
|---|---|
| Category | Vehicles |
| Total lines | 6,195 |
| Functions | 153 (6 unique, 147 shared) |
| Unique lines | 837 (13.5% of file) |

## Assets

**Models and props** (1) - `stunt`

**Audio banks** (1) - `PLANES`

**Sounds** (3) - `PROPERTIES_PLANE_PROMO_MASTER`, `CHECKPOINT_NORMAL`, `HUD_MINI_GAME_SOUNDSET`

**Particle effects** (2) - `scr_property_leaflet_drop`, `spawn`

**Text labels** (8) - `LEAFLET`, `NULL`, `PMPLANE`, `TAKEOFF`, `LAND`, `DONE`, `PPROM`, `MICHAEL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_BLIP_EXIST` (22), `SET_BIT` (19), `REMOVE_BLIP` (17), `CLEAR_BIT` (15), `PLAYER_PED_ID` (13), `IS_PED_INJURED` (8), `GET_GAME_TIMER` (8), `DOES_ENTITY_EXIST` (6), `IS_PED_IN_VEHICLE` (6), `IS_VEHICLE_DRIVEABLE` (4), `CLEAR_PRINTS` (4), `DOES_PARTICLE_FX_LOOPED_EXIST` (3), `SET_WANTED_LEVEL_MULTIPLIER` (2), `SET_IGNORE_NO_GPS_FLAG` (2), `WAIT` (2), `IS_ENTITY_IN_AIR` (2), `REQUEST_SCRIPT_AUDIO_BANK` (2), `CLEAR_HELP` (2), `GET_RANDOM_INT_IN_RANGE` (2), `IS_ENTITY_AT_COORD` (2), `IS_PLAYER_WANTED_LEVEL_GREATER` (2), `PLAYER_ID` (2), `IS_STRING_NULL` (2), `SET_VEHICLE_AS_NO_LONGER_NEEDED` (1), `TERMINATE_THIS_THREAD` (1), `SET_MISSION_FLAG` (1), `HAS_FORCE_CLEANUP_OCCURRED` (1), `IS_CONTROL_JUST_PRESSED` (1), `START_PARTICLE_FX_LOOPED_ON_ENTITY` (1), `PLAY_SOUND_FROM_ENTITY` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-0.65f` x1 · `121.2244f` x1 · `-1067.083f` x1 · `-2922.601f` x1 · `12.82418f` x1 · `-1091.854f` x1 · `-2965.403f` x1 · `23.94564f` x1 · `31.5625f` x1 · `0.75f` x1 · `0.1f` x1

## Other strings

Literals whose consuming native was not classified:

`LOSE_WANTED`, `MORE_SEATS`, `VEHICLE_POLICE_PURSUIT`, `BK_PLANE`, `stunt`, `LOSE_WANTED_LEVEL`, `GET_PLANE`, `RAND_`, `FLY_DROP`, `GET_IN_CAR`, `NEED_A_BIGGER_VEHICLE`

---

Source: `decompiled_scripts/pm_plane_promotion.c`
