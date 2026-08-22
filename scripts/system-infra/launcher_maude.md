# launcher_maude.c

System and infrastructure script. 1 anim dicts; 2 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 11,700 |
| Functions | 281 (5 unique, 276 shared) |
| Unique lines | 267 (2.3% of file) |

## Assets

**Animation dictionaries** (1) - `special_ped@maude@base`

**Animations** (2) - `special_ped@maude@base`, `base`

**Models and props** (2) - `prop_table_03_chr`, `prop_laptop_01a`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`TERMINATE_THIS_THREAD` (4), `DOES_ENTITY_EXIST` (3), `WAIT` (2), `CLEAR_AREA` (2), `SET_ALL_VEHICLE_GENERATORS_ACTIVE_IN_AREA` (2), `STOP_SYNCHRONIZED_ENTITY_ANIM` (2), `PLAY_SYNCHRONIZED_ENTITY_ANIM` (1), `GET_STANDARD_BLIP_ENUM_ID` (1), `SET_MODEL_AS_NO_LONGER_NEEDED` (1), `REQUEST_MODEL` (1), `REQUEST_ANIM_DICT` (1), `HAS_ANIM_DICT_LOADED` (1), `CREATE_SYNCHRONIZED_SCENE` (1), `SET_SYNCHRONIZED_SCENE_LOOPED` (1), `SET_SYNCHRONIZED_SCENE_HOLD_LAST_FRAME` (1), `TASK_SYNCHRONIZED_SCENE` (1), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (1), `GET_WAYPOINT_BLIP_ENUM_ID` (1), `HAS_FORCE_CLEANUP_OCCURRED` (1), `SET_THIS_IS_A_TRIGGER_SCRIPT` (1), `ADD_SCENARIO_BLOCKING_AREA` (1), `SET_PED_NON_CREATION_AREA` (1), `SET_ROADS_IN_AREA` (1), `REMOVE_VEHICLES_FROM_GENERATORS_IN_AREA` (1), `IS_WORLD_POINT_WITHIN_BRAIN_ACTIVATION_RANGE` (1), `REMOVE_SCENARIO_BLOCKING_AREA` (1), `CLEAR_PED_NON_CREATION_AREA` (1), `SET_ROADS_BACK_TO_ORIGINAL` (1), `IS_SYNCHRONIZED_SCENE_RUNNING` (1), `CLEAR_PED_TASKS` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`2697.222f` x2 · `4119.894f` x2 · `42.79107f` x2 · `2746.04f` x2 · `4162.974f` x2 · `43.62732f` x2 · `2728.33f` x1 · `4145.6f` x1 · `43.89f` x1 · `89.19f` x1 · `2727.4f` x1 · `4145.56f` x1 · `43.68f` x1 · `-92.17f` x1 · `2728.333f` x1 · `4144.778f` x1 · `43.29292f` x1 · `7.5f` x1

## Other strings

Literals whose consuming native was not classified:

`SCRIPT TERMINATED`, `base_chair`, `MAUDE_MCS_1`, `RC MAUDE 1`, `SCRIPT TERMINATING: Cleaning up entities in Launcher`, `SCRIPT TERMINATING: Ending off-mission cutscene request`, `Player out of range [TERMINATING]`, `Force cleanup [TERMINATING]`, `Relinquishing candidate id...`

---

Source: `decompiled_scripts/launcher_maude.c`
