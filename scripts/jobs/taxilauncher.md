# taxilauncher.c

Jobs script. 1 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 6,446 |
| Functions | 148 (76 unique, 72 shared) |
| Unique lines | 4,441 (68.9% of file) |

## Assets

**Animations** (6) - `HAIL_TAXI`, `FP_HAIL_TAXI`, `FUCK_U`, `FORGET_IT`, `Aknowledge_R`, `Aknowledge_L`

**Models and props** (1) - `a_m_y_stlat_01`

**Speech contexts** (1) - `A_M_M_EASTSA_02_LATINO_FULL_01`

**Text labels** (5) - `NULL`, `TAXISAU`, `MICHAEL`, `FRANKLIN`, `TREVOR`

**Vehicle mods** (1) - `taxi`

**Scripts launched** (2) - `taxiService`, `ambient_solomon`

**Hashed names** (3) - `UpperbodyAndIk_filter`, `BONEMASK_HEAD_NECK_AND_L_ARM`, `NORMAL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (124), `IS_POINT_IN_ANGLED_AREA` (81), `DOES_ENTITY_EXIST` (29), `IS_PED_INJURED` (26), `IS_ENTITY_PLAYING_ANIM` (22), `PLAYER_ID` (19), `IS_VEHICLE_DRIVEABLE` (16), `GET_ENTITY_COORDS` (14), `GET_PED_IN_VEHICLE_SEAT` (14), `SET_PED_CONFIG_FLAG` (12), `IS_VEHICLE_SEAT_FREE` (12), `IS_PED_SITTING_IN_VEHICLE` (11), `GET_SCRIPT_TASK_STATUS` (10), `GET_GAME_TIMER` (8), `TASK_SMART_FLEE_PED` (7), `IS_ENTITY_DEAD` (7), `SET_MODEL_AS_NO_LONGER_NEEDED` (7), `TASK_VEHICLE_TEMP_ACTION` (7), `GET_RANDOM_INT_IN_RANGE` (7), `STOP_ENTITY_ANIM` (6), `IS_PED_IN_ANY_VEHICLE` (6), `IS_ENTITY_A_MISSION_ENTITY` (6), `GET_ENTITY_MODEL` (6), `IS_PLAYER_PLAYING` (6), `SET_ENTITY_AS_MISSION_ENTITY` (6), `STOP_PED_SPEAKING` (6), `DISABLE_CONTROL_ACTION` (6), `SET_PED_CAN_PLAY_AMBIENT_ANIMS` (5), `CLEAR_HELP` (5), `IS_GAMEPLAY_HINT_ACTIVE` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x4 · `1.5f` x3 · `0.5f` x3 · `49.75f` x2 · `-804.05f` x2 · `4216.412f` x2 · `204.4872f` x2 · `-509.0679f` x2 · `4135.19f` x2 · `123.2502f` x2 · `-1538.981f` x2 · `-941.1323f` x2 · `10.56623f` x2 · `-1715.57f` x2 · `-1139.766f` x2 · `52.20361f` x2 · `-1739.989f` x2 · `-1115.973f` x2 · `10.08726f` x2 · `-1800.515f` x2 · `-1187.18f` x2 · `52.0172f` x2 · `-1801.766f` x2 · `-1180.252f` x2

## Other strings

Literals whose consuming native was not classified:

`TX_H02`, `TAXI_HAIL`, `FP_HAIL_TAXI`, `TXM_H01`, `HAIL_TAXI`, `taxiService`, `TX_2`, `TX_2A`, `FUCK_U`, `FORGET_IT`, `Aknowledge_R`, `Aknowledge_L`, `TXM_BLIP`, `\ntaxi_functions - IS_ANY_DIALOGUE_PLAYING - IS_AMBIENT_SPEECH_PLAYING(DriverID)\n`, `\ntaxi_functions - IS_ANY_DIALOGUE_PLAYING - IS_AMBIENT_SPEECH_PLAYING(PLAYER_PED_ID())\n`, `\ntaxi_functions - IS_ANY_DIALOGUE_PLAYING - IS_ANY_CONVERSATION_ONGOING_OR_QUEUED()\n`, `\ntaxi_functions - IS_ANY_DIALOGUE_PLAYING - IS_MESSAGE_BEING_DISPLAYED()\n`, `\ntaxi_functions - IS_ANY_DIALOGUE_PLAYING - IS_AMBIENT_SPEECH_PLAYING(TempGroupPedID)\n`, `TAXI_HAIL_DRUNK`, `TAXI_DRIVES_PAST`, `\nIS_COORD_ON_SAME_LEVEL_AS_COORD - fTemp < acceptableHeight, RETURN TRUE\n`, `TaxiDispatch`, `TX_1M`, `TX_3M`, `TX_1F`, `TX_3F`, `TX_1T`, `TX_3T`

---

Source: `decompiled_scripts/taxilauncher.c`
