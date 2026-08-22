# finale_heist_prepb.c

Heists script. 2 anim dicts; 7 models.

| | |
|---|---|
| Category | Heists |
| Total lines | 12,179 |
| Functions | 230 (33 unique, 197 shared) |
| Unique lines | 5,253 (43.1% of file) |

## Assets

**Animation dictionaries** (2) - `cellphone@str`, `misscarsteal4@director_grip`

**Animations** (4) - `misscarsteal4@director_grip`, `mcs_2_loop_grip1`, `cellphone@str`, `cellphone_call_listen_c`

**Models and props** (7) - `S_M_M_GENERICSECURITY_01_LATINO_MINI_01`, `S_M_M_GENERICSECURITY_01_LATINO_MINI_02`, `s_m_m_security_01`, `s_m_y_construct_01`, `armytrailer2`, `packer`, `bison2`

**Speech contexts** (2) - `S_M_M_GENERICSECURITY_01_LATINO_MINI_01`, `S_M_M_GENERICSECURITY_01_LATINO_MINI_02`

**Text labels** (12) - `SOL1AUD`, `FHPBAUD`, `COP`, `CONSTRUCTION3`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `FIGHT`, `CONSTRUCTION2`, `NULL`, `FINPRB`, `LESTER`

**Scenarios** (1) - `SCRAP_SECURITY`

**Relationship groups** (2) - `WorkerPedMainGroup`, `GuardMainGroup`

**Doors** (1) - `prop_sec_barrier_ld_01a`

**Vehicle mods** (2) - `packer`, `phantom`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (266), `GET_GAME_TIMER` (130), `DOES_ENTITY_EXIST` (99), `GET_SCRIPT_TASK_STATUS` (62), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (55), `IS_PED_INJURED` (54), `DOES_SCENARIO_EXIST_IN_AREA` (41), `CAN_PED_SEE_HATED_PED` (39), `IS_ENTITY_ON_SCREEN` (37), `PLAYER_ID` (36), `CLEAR_PED_TASKS` (36), `TASK_USE_NEAREST_SCENARIO_CHAIN_TO_COORD` (31), `IS_PED_IN_VEHICLE` (30), `IS_VEHICLE_DRIVEABLE` (28), `CLEAR_PED_TASKS_IMMEDIATELY` (26), `DOES_BLIP_EXIST` (24), `GET_ENTITY_COORDS` (21), `IS_ENTITY_IN_ANGLED_AREA` (21), `SET_PED_RELATIONSHIP_GROUP_HASH` (18), `SET_ENTITY_AS_MISSION_ENTITY` (17), `REMOVE_BLIP` (17), `IS_PED_IN_ANY_VEHICLE` (17), `IS_PED_FACING_PED` (17), `IS_AMBIENT_SPEECH_PLAYING` (16), `GET_VEHICLE_PED_IS_IN` (15), `GET_PLAYER_WANTED_LEVEL` (14), `TASK_LOOK_AT_ENTITY` (13), `DOES_ENTITY_BELONG_TO_THIS_SCRIPT` (12), `SET_RELATIONSHIP_BETWEEN_GROUPS` (11), `CREATE_PED` (11)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`889.5f` x9 · `29.7f` x9 · `0.25f` x9 · `8.25f` x8 · `912.2f` x8 · `-1542.5f` x8 · `29.8f` x8 · `917.4f` x8 · `-1517.4f` x8 · `869.8f` x8 · `-1541.2f` x8 · `29.4f` x8 · `884.2f` x8 · `-1574.1f` x8 · `905.9f` x8 · `-1574.8f` x8 · `29.9f` x8 · `863.1551f` x5 · `-1564.572f` x5 · `29.3231f` x5 · `940.2881f` x5 · `-1573.877f` x5 · `29.3866f` x5 · `0.5f` x4

## Other strings

Literals whose consuming native was not classified:

`PROVOKE_TRESPASS`, `PROVOKE_GENERIC`, `HELP_1`, `police3`, `player`, `FHPRB_STOP`, `FHPRB_COPS`, `GUN_COOL`, `FHPRB_START`, `FHPRB_TRUCK`, `FHPRB_LOST`, `FHPBSecGuard`, `SOL1_SEE6`, `armytrailer2`, `packer`, `bison2`, `GOD_4`, `GOD_6`, `GOD_5`, `SOL1_SEC3`, `SOL1_OUT3`, `GENERIC_INSULT_HIGH`, `GENERIC_CURSE_HIGH`, `SOL1_TALK`, `FHPrepBWorker`, `M_FINPRB`, `FHPRA_FAIL`, `FPB_FAIL1`, `FPB_FAIL2`, `FPB_FAIL3`

---

Source: `decompiled_scripts/finale_heist_prepb.c`
