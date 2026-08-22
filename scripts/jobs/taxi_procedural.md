# taxi_procedural.c

Jobs script. 4 anim dicts; 10 models; 1 scaleforms.

| | |
|---|---|
| Category | Jobs |
| Total lines | 15,786 |
| Functions | 435 (36 unique, 399 shared) |
| Unique lines | 1,913 (12.1% of file) |

## Assets

**Animation dictionaries** (4) - `gestures@m@standing@casual`, `oddjobs@taxi@`, `oddjobs@towingcome_here`, `misscommon@response`

**Models and props** (10) - `a_f_y_vinewood_04`, `A_F_Y_VINEWOOD_04_WHITE_MINI_02`, `a_m_m_soucent_04`, `a_m_y_salton_01`, `a_m_y_soucent_04`, `a_m_y_vinewood_01`, `A_M_M_SOUCENT_04_BLACK_MINI_01`, `A_M_Y_SALTON_01_WHITE_MINI_02`, `A_M_Y_SOUCENT_04_BLACK_MINI_01`, `A_M_Y_VINEWOOD_01_BLACK_MINI_01`

**Sounds** (2) - `CHECKPOINT_UNDER_THE_BRIDGE`, `HUD_MINI_GAME_SOUNDSET`

**Scaleform movies** (1) - `STRING`

**Text labels** (2) - `NULL`, `COP`

**Scenarios** (2) - `WORLD_HUMAN_STAND_MOBILE`, `WORLD_HUMAN_AA_SMOKE`

**Relationship groups** (1) - `TAXI_Passenger`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_BLIP_EXIST` (10), `GET_PLAYER_INDEX` (9), `GET_RANDOM_INT_IN_RANGE` (8), `IS_PED_INJURED` (8), `IS_ENTITY_DEAD` (6), `FLOOR` (5), `REMOVE_BLIP` (5), `IS_ENTITY_AT_ENTITY` (5), `GET_PLAYER_WANTED_LEVEL` (5), `SET_PED_CONFIG_FLAG` (4), `SET_BLIP_NAME_FROM_TEXT_FILE` (4), `CLEAR_PRINTS` (4), `HAS_ANIM_DICT_LOADED` (4), `PLAYER_PED_ID` (3), `SET_BLIP_ROUTE` (3), `IS_VEHICLE_DRIVEABLE` (3), `PLAYER_ID` (3), `ADD_TEXT_COMPONENT_INTEGER` (3), `IS_PED_IN_ANY_VEHICLE` (3), `IS_PED_SHOOTING` (3), `SET_RELATIONSHIP_BETWEEN_GROUPS` (2), `CLEAR_SEQUENCE_TASK` (2), `OPEN_SEQUENCE_TASK` (2), `TASK_SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (2), `CLOSE_SEQUENCE_TASK` (2), `TASK_PERFORM_SEQUENCE` (2), `SET_PED_KEEP_TASK` (2), `SET_PLAYER_CONTROL` (2), `BEGIN_TEXT_COMMAND_SCALEFORM_STRING` (2), `END_TEXT_COMMAND_SCALEFORM_STRING` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.2f` x2 · `1.5f` x2 · `0.25f` x1

## Other strings

Literals whose consuming native was not classified:

`TAXI_DBG_NTAXI`, `TAXI_BLIP_PASS`, `TAXI_BLIP_MONE`, `TAXI_OBJ_POL`, `No Taxi`, `Taxi Not Driveable`, `TC_HOWTOSTART`, `TaxiGeneric`, `player`, `TAXI_2CANCEL`, `Player cancelled on dispatch`, `TAXI_FARE_FIN`, `TAXI_FARE_DET`, `TX_OBJ_PRO_DO`, `PED_RANT`, `GENERIC_INSULT_MED`, `TAXI_GOOD`, `GENERIC_THANKS`, `Region 0 - Los Puerta`, `Region 1 - South Los Santos`, `Region 2 - Vinewood Hills`, `Region 3 - Del Perro`, `Region 4 - Little Seoul`, `Region 5 -  Downtown`, `Region 6 - SouthGate`, `Region 7 - City Hills`, `Region 8 - Country Hills`, `Region 9 - Bel Air`, `Region 10 - West Hollywood`, `Region 11 - Echo Park`

---

Source: `decompiled_scripts/taxi_procedural.c`
