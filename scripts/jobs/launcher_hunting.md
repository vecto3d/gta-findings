# launcher_hunting.c

Jobs script. 2 anim dicts.

| | |
|---|---|
| Category | Jobs |
| Total lines | 11,905 |
| Functions | 285 (6 unique, 279 shared) |
| Unique lines | 378 (3.2% of file) |

## Assets

**Animation dictionaries** (2) - `special_ped@cletus@base`, `rcmhunting2`

**Animations** (4) - `rcmhunting2`, `_idle_loop`, `special_ped@cletus@base`, `cletus_base`

**Text labels** (3) - `NULL`, `HUNT1AU`, `CLETUS`

**Scenarios** (3) - `WORLD_HUMAN_HANG_OUT_STREET`, `WORLD_HUMAN_DRINKING`, `WORLD_HUMAN_SMOKING`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_ENTITY_EXIST` (7), `PLAYER_PED_ID` (6), `TERMINATE_THIS_THREAD` (4), `HAS_ANIM_DICT_LOADED` (4), `SET_VEHICLE_EXTRA` (3), `IS_SCENARIO_TYPE_ENABLED` (3), `SET_SCENARIO_TYPE_ENABLED` (3), `GET_WEAPON_COMPONENT_TYPE_MODEL` (2), `WAIT` (2), `SET_PED_MAX_MOVE_BLEND_RATIO` (2), `REQUEST_MODEL` (2), `REQUEST_ANIM_DICT` (2), `GIVE_WEAPON_TO_PED` (2), `GIVE_WEAPON_COMPONENT_TO_WEAPON_OBJECT` (2), `SET_MODEL_AS_NO_LONGER_NEEDED` (2), `CLEAR_AREA_OF_PEDS` (2), `SET_PED_NON_CREATION_AREA` (2), `GET_STANDARD_BLIP_ENUM_ID` (1), `GET_WAYPOINT_BLIP_ENUM_ID` (1), `GET_WEAPONTYPE_MODEL` (1), `SET_THIS_IS_A_TRIGGER_SCRIPT` (1), `HAS_FORCE_CLEANUP_OCCURRED` (1), `IS_WORLD_POINT_WITHIN_BRAIN_ACTIVATION_RANGE` (1), `CLEAR_AREA` (1), `IS_ENTITY_DEAD` (1), `GET_ENTITY_COORDS` (1), `VDIST2` (1), `ABSF` (1), `CREATE_WEAPON_OBJECT` (1), `TASK_PLAY_ANIM_ADVANCED` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`2.5f` x1 · `-683.3276f` x1 · `5841.042f` x1 · `17.217f` x1 · `8.33f` x1 · `-683.152f` x1 · `5841.281f` x1 · `17.32f` x1 · `17.024f` x1 · `-162.64f` x1 · `1804.33f` x1 · `3931.33f` x1 · `33.83f` x1 · `91.63f` x1 · `1804.501f` x1 · `3922.917f` x1 · `32.8091f` x1 · `1801.159f` x1 · `3919.606f` x1 · `33.0662f` x1 · `1803.603f` x1 · `3920.191f` x1 · `32.9855f` x1 · `1798.416f` x1

## Other strings

Literals whose consuming native was not classified:

`SCRIPT TERMINATED`, `dune`, `Force cleanup [TERMINATING]`, `Relinquishing candidate id...`, `Player out of range [TERMINATING]`, `HUNT1_AMB`, `Created initial scene`, `HUN_2_MCS_1`, `RC HUNTER 2`, `CLETUS_MCS_1_concat`, `cletus_base`, `RC HUNTER 1`, `SCRIPT TERMINATING: Cleaning up entities in Launcher`, `SCRIPT TERMINATING: Ending off-mission cutscene request`

---

Source: `decompiled_scripts/launcher_hunting.c`
