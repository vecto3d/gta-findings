# startup_positioning.c

System and infrastructure script. 3 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 130,616 |
| Functions | 789 (76 unique, 713 shared) |
| Unique lines | 7,557 (5.8% of file) |

## Assets

**Models and props** (3) - `v_strip3`, `v_michael`, `v_trailer`

**Audio banks** (1) - `TIME_LAPSE`

**Sounds** (1) - `TOD_SHIFT_SCENE`

**Text labels** (2) - `THUNDER`, `NULL`

**Scenarios** (1) - `WORLD_MOUNTAIN_LION_WANDER`

**Stats** (1) - `sp_ambient_switch_count`

**Scripts launched** (1) - `blip_controller`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (88), `WAIT` (27), `VDIST2` (25), `GET_GAME_TIMER` (21), `IS_PED_INJURED` (18), `DOES_ENTITY_EXIST` (17), `FREEZE_ENTITY_POSITION` (13), `GET_ENTITY_COORDS` (10), `IS_ENTITY_DEAD` (8), `PLAYER_ID` (8), `GET_ENTITY_MODEL` (6), `SHUTDOWN_LOADING_SCREEN` (5), `CLEAR_AREA` (5), `GET_GROUND_Z_FOR_3D_COORD` (5), `IS_PED_IN_ANY_VEHICLE` (5), `GET_MODEL_DIMENSIONS` (5), `TO_FLOAT` (5), `IS_STRING_NULL_OR_EMPTY` (5), `SET_ENTITY_LOAD_COLLISION_FLAG` (5), `SET_ENTITY_SHOULD_FREEZE_WAITING_ON_COLLISION` (4), `ROUND` (4), `IS_VEHICLE_DRIVEABLE` (4), `SET_GAME_PAUSED` (4), `GET_INTERIOR_AT_COORDS` (4), `IS_THIS_MODEL_A_BOAT` (4), `GET_SHAPE_TEST_RESULT` (4), `SET_PED_GET_OUT_UPSIDE_DOWN_VEHICLE` (4), `DOES_CAM_EXIST` (4), `DESTROY_CAM` (4), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x2 · `1.75f` x2 · `7.5f` x2 · `-1155.25f` x1 · `-1519.25f` x1 · `3.34375f` x1 · `-1690.65f` x1 · `-3130.951f` x1 · `12.95889f` x1 · `-1625.34f` x1 · `-3169.573f` x1 · `29.69495f` x1 · `3.5f` x1 · `207.4336f` x1 · `-1019.795f` x1 · `-100.4728f` x1 · `189.9338f` x1 · `-1019.623f` x1 · `-95.56883f` x1 · `17.1875f` x1 · `483.7175f` x1 · `-1326.63f` x1 · `28.2135f` x1 · `474.9644f` x1

## Other strings

Literals whose consuming native was not classified:

`rain`, `snow`, `miljet`, `jet`, `startup_positioning`, `IMPOUND_HELPM`, `IMPOUND_HELPF`, `IMPOUND_HELPT`, `submersible`, `submersible2`, `DEFAULT_SCRIPTED_CAMERA`

---

Source: `decompiled_scripts/startup_positioning.c`
