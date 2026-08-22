# launcher_minute.c

System and infrastructure script. 1 anim dicts; 2 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 12,393 |
| Functions | 301 (10 unique, 291 shared) |
| Unique lines | 555 (4.5% of file) |

## Assets

**Animation dictionaries** (1) - `rcmminute1`

**Animations** (3) - `rcmminute1`, `base_joe`, `base_josef`

**Models and props** (2) - `prop_table_03_chr`, `prop_cs_rolled_paper`

**Text labels** (6) - `NULL`, `MIN1AUD`, `JOE`, `JOSEF`, `MIN3AUD`, `MANUEL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_ENTITY_EXIST` (11), `PLAYER_PED_ID` (7), `TERMINATE_THIS_THREAD` (4), `CLEAR_AREA` (4), `SET_PED_PROP_INDEX` (4), `SET_VEHICLE_MODEL_IS_SUPPRESSED` (4), `REQUEST_MODEL` (3), `SET_MODEL_AS_NO_LONGER_NEEDED` (3), `SET_CUTSCENE_PED_PROP_VARIATION` (3), `WAIT` (2), `SET_ALL_VEHICLE_GENERATORS_ACTIVE_IN_AREA` (2), `SET_VEHICLE_COLOUR_COMBINATION` (2), `SET_VEHICLE_DOORS_LOCKED` (2), `HAS_ANIM_DICT_LOADED` (2), `CLEAR_PED_TASKS` (2), `TASK_PLAY_ANIM` (2), `SET_PED_CONFIG_FLAG` (2), `GET_STANDARD_BLIP_ENUM_ID` (1), `GET_WAYPOINT_BLIP_ENUM_ID` (1), `SET_THIS_IS_A_TRIGGER_SCRIPT` (1), `HAS_FORCE_CLEANUP_OCCURRED` (1), `IS_WORLD_POINT_WITHIN_BRAIN_ACTIVATION_RANGE` (1), `REMOVE_VEHICLES_FROM_GENERATORS_IN_AREA` (1), `GET_ENTITY_COORDS` (1), `ADD_SCENARIO_BLOCKING_AREA` (1), `SET_ENTITY_COLLISION` (1), `FREEZE_ENTITY_POSITION` (1), `SET_PED_CAN_RAGDOLL_FROM_PLAYER_IMPACT` (1), `TASK_LOOK_AT_ENTITY` (1), `ATTACH_ENTITY_TO_ENTITY` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`321.69f` x2 · `3408.64f` x2 · `35.34f` x2 · `35.8f` x2 · `329.513f` x1 · `3402.691f` x1 · `36.258f` x1 · `-309.1f` x1 · `6205.4f` x1 · `-279.33f` x1 · `6217.98f` x1 · `-2.8f` x1 · `0.12f` x1 · `0.03f` x1 · `329.3f` x1 · `3404.2f` x1 · `-174.9f` x1 · `328.1f` x1 · `3403.8f` x1 · `-149.6f` x1

## Other strings

Literals whose consuming native was not classified:

`SCRIPT TERMINATED`, `MIN1_AMB`, `MIN3_AMB`, `Josef`, `pranger`, `Force cleanup [TERMINATING]`, `Relinquishing candidate id...`, `Player out of range [TERMINATING]`, `Player has moved SURFER2 vehicle [TERMINATING]`, `Created initial scene`, `sabregt`, `bison`, `MMB_3_RCM`, `rcmminute3base`, `base`, `beckon`, `RCM MINUTE - MANUEL`, `start conversation`, `MMB_2_RCM`, `surfer2`, `MMB_1_RCM`, `RCM MINUTE - JOE`, `RCM MINUTE - JOSEF`, `unpause conversation`, `conversation ended`, `pause conversation`, `SCRIPT TERMINATING: Cleaning up entities in Launcher`, `SCRIPT TERMINATING: Ending off-mission cutscene request`, `Joe`

---

Source: `decompiled_scripts/launcher_minute.c`
