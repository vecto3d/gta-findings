# taxi_deadline.c

Jobs script. 1 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 14,046 |
| Functions | 418 (23 unique, 395 shared) |
| Unique lines | 782 (5.6% of file) |

## Assets

**Models and props** (1) - `g_m_m_chigoon_02`

**Sounds** (3) - `HUD_MINI_GAME_SOUNDSET`, `TIMER_STOP`, `10_SEC_WARNING`

**Text labels** (1) - `NULL`

**Scenarios** (1) - `WORLD_HUMAN_STAND_MOBILE`

**Doors** (2) - `prop_casino_door_01l`, `prop_casino_door_01r`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_LOCKED_UNSTREAMED_IN_DOOR_OF_TYPE` (8), `SET_PED_COMPONENT_VARIATION` (5), `PLAYER_PED_ID` (4), `SET_STATE_OF_CLOSEST_DOOR_OF_TYPE` (4), `GET_GAME_TIMER` (3), `ROUND` (2), `IS_ENTITY_DEAD` (2), `IS_PED_INJURED` (2), `SET_PED_CONFIG_FLAG` (2), `TASK_FOLLOW_NAV_MESH_TO_COORD` (2), `SET_PED_KEEP_TASK` (2), `PLAY_SOUND_FRONTEND` (2), `DOES_ENTITY_EXIST` (1), `WAIT` (1), `GET_ENTITY_SPEED` (1), `IS_VEHICLE_DRIVEABLE` (1), `IS_PED_IN_VEHICLE` (1), `SET_ENTITY_HEADING` (1), `TASK_START_SCENARIO_IN_PLACE` (1), `CLOSE_SEQUENCE_TASK` (1), `TASK_PERFORM_SEQUENCE` (1), `REQUEST_MODEL` (1), `REMOVE_BLIP` (1), `CLEAR_SEQUENCE_TASK` (1), `OPEN_SEQUENCE_TASK` (1), `TASK_LEAVE_ANY_VEHICLE` (1), `TASK_CLEAR_LOOK_AT` (1), `TERMINATE_THIS_THREAD` (1), `HAS_MODEL_LOADED` (1), `HAS_SCALEFORM_MOVIE_LOADED` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`80.0993f` x6 · `929.6144f` x3 · `46.3955f` x3 · `928.6238f` x3 · `44.9848f` x3 · `928.1625f` x3 · `43.7989f` x3 · `79.8993f` x3 · `927.4266f` x3 · `42.1881f` x3 · `80.0884f` x3 · `0.25f` x2 · `180.6f` x1 · `84.9058f` x1 · `322.1072f` x1 · `442.4288f` x1 · `140.6772f` x1 · `5.5f` x1

## Other strings

Literals whose consuming native was not classified:

`Taxi Not Driveable`, `TaxiKwak`, `TAXI_SC_BN_03`, `Player did not hit the deadline`, `TIM_TIMER`, `TAXI_ASSETS_STREAMED - Loading G_M_M_ChiGoon_02`, `TAXI_ASSETS_STREAMED - Loading shared assets`, `TX_OBJ_DL_DO`

---

Source: `decompiled_scripts/taxi_deadline.c`
