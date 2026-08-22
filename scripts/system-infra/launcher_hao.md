# launcher_hao.c

System and infrastructure script. 1 anim dicts; 1 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 11,836 |
| Functions | 284 (4 unique, 280 shared) |
| Unique lines | 296 (2.5% of file) |

## Assets

**Animation dictionaries** (1) - `special_ped@hao@base`

**Animations** (1) - `hao_base`

**Models and props** (1) - `prop_npc_phone`

**Text labels** (3) - `NULL`, `HAO1AU`, `HAO`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PRELOAD_VEHICLE_MOD` (9), `SET_VEHICLE_MOD` (9), `TERMINATE_THIS_THREAD` (5), `PLAYER_PED_ID` (3), `WAIT` (3), `DOES_ENTITY_EXIST` (3), `TOGGLE_VEHICLE_MOD` (3), `GET_GAME_TIMER` (2), `GET_STANDARD_BLIP_ENUM_ID` (1), `GET_WAYPOINT_BLIP_ENUM_ID` (1), `SET_THIS_IS_A_TRIGGER_SCRIPT` (1), `HAS_FORCE_CLEANUP_OCCURRED` (1), `IS_WORLD_POINT_WITHIN_BRAIN_ACTIVATION_RANGE` (1), `ADD_SCENARIO_BLOCKING_AREA` (1), `CLEAR_AREA` (1), `GET_ENTITY_COORDS` (1), `REQUEST_MODEL` (1), `REQUEST_ANIM_DICT` (1), `HAS_ANIM_DICT_LOADED` (1), `SET_VEHICLE_COLOURS` (1), `SET_VEHICLE_EXTRA_COLOURS` (1), `SET_VEHICLE_MOD_KIT` (1), `SET_VEHICLE_DOORS_LOCKED` (1), `ROLL_DOWN_WINDOW` (1), `SET_VEHICLE_LIGHTS` (1), `SET_VEHICLE_MODEL_IS_SUPPRESSED` (1), `SET_VEHICLE_ON_GROUND_PROPERLY` (1), `SET_VEHICLE_COLOUR_COMBINATION` (1), `ATTACH_ENTITY_TO_ENTITY` (1), `GET_PED_BONE_INDEX` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-103.0011f` x1 · `-1281.636f` x1 · `26.3686f` x1 · `-23.246f` x1 · `-1241.361f` x1 · `30.335f` x1 · `-72.323f` x1 · `-1258.643f` x1 · `28.648f` x1 · `-71.93684f` x1 · `-1259.7f` x1 · `28.19359f` x1 · `-177.55f` x1

## Other strings

Literals whose consuming native was not classified:

`SCRIPT TERMINATED`, `SP_MISSION_FRANKLIN_1 is not available...`, `Force cleanup [TERMINATING]`, `Relinquishing candidate id...`, `SP_MISSION_FRANKLIN_1 is available... [TERMINATING]`, `Player out of range [TERMINATING]`, `SP_MISSION_FRANKLIN_1 became available... [TERMINATING]`, `Player has moved HAO's vehicle [TERMINATING]`, `HAO1_HCO`, `HAO_MCS_1`, `HAO LAUNCHER RC - HAO`, `chassis_dummy`, `SCRIPT TERMINATING: Cleaning up entities in Launcher`, `SCRIPT TERMINATING: Ending off-mission cutscene request`, `penumbra`, `ruiner`

---

Source: `decompiled_scripts/launcher_hao.c`
