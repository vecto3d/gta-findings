# am_taxi.c

Jobs script. 2 anim dicts; 1 models; 10 scaleforms.

| | |
|---|---|
| Category | Jobs |
| Total lines | 15,802 |
| Functions | 409 (111 unique, 298 shared) |
| Unique lines | 6,617 (41.9% of file) |

## Assets

**Animation dictionaries** (2) - `ODDJOBS@TAXI@DRIVER`, `TAXI_HAIL`

**Animations** (6) - `ODDJOBS@TAXI@DRIVER`, `leanover_exit`, `leanover_idle`, `leanover_enter`, `TAXI_HAIL`, `HAIL_TAXI`

**Models and props** (1) - `prop_taxi_meter_2`

**Scaleform movies** (10) - `HIGHLIGHT_DESTINATION`, `SET_TAXI_PRICE`, `STRING`, `STRTNM1`, `SHOW_TAXI_DESTINATION`, `SET_INPUT_EVENT`, `instructional_buttons`, `CLEAR_TAXI_DISPLAY`, `ADD_TAXI_DESTINATION`, `STRTNM2`

**Text labels** (2) - `MPTXIAU`, `NULL`

**Vehicle mods** (1) - `taxi`

**Scripts launched** (1) - `ambient_solomon`

**Hashed names** (1) - `NORMAL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`NET_TO_PED` (103), `NET_TO_VEH` (101), `IS_POINT_IN_ANGLED_AREA` (87), `CLEAR_BIT` (81), `SET_BIT` (45), `PLAYER_PED_ID` (40), `PLAYER_ID` (31), `NETWORK_DOES_NETWORK_ID_EXIST` (29), `GET_ENTITY_COORDS` (27), `INT_TO_PARTICIPANTINDEX` (23), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (21), `GET_BLIP_COORDS` (21), `DOES_BLIP_EXIST` (20), `IS_ENTITY_PLAYING_ANIM` (17), `NETWORK_GET_PLAYER_INDEX` (16), `SET_NETWORK_ID_CAN_MIGRATE` (16), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (15), `NETWORK_IS_PARTICIPANT_ACTIVE` (11), `DOES_CAM_EXIST` (11), `BEGIN_SCALEFORM_MOVIE_METHOD` (11), `END_SCALEFORM_MOVIE_METHOD` (11), `IS_CAM_ACTIVE` (11), `GET_VEHICLE_NUMBER_OF_PASSENGERS` (10), `GET_PLAYER_PED` (10), `DOES_ENTITY_EXIST` (10), `SETTIMERB` (9), `IS_PED_INJURED` (8), `DISABLE_CONTROL_ACTION` (8), `GET_BLIP_INFO_ID_TYPE` (8), `IS_VEHICLE_DRIVEABLE` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x4 · `4.5f` x4 · `-1061.018f` x3 · `-2540.235f` x3 · `18.66932f` x3 · `-1023.332f` x3 · `-2562.115f` x3 · `31.57616f` x3 · `-1061.059f` x3 · `-2540.254f` x3 · `10.94467f` x3 · `-1023.297f` x3 · `-2562.052f` x3 · `18.51685f` x3 · `-1043.364f` x3 · `-2747.29f` x3 · `16.96057f` x3 · `-991.5368f` x3 · `-2657.682f` x3 · `69.12349f` x3 · `-1047.646f` x3 · `-2754.947f` x3 · `2.941969f` x3 · `-991.7314f` x3

## Other strings

Literals whose consuming native was not classified:

`taxi`, `TXM_H02`, `TXM_SLCT`, `leanover_enter`, `TaxiDispatch`, `FM_TAXI`, `TXM_H01`, `FREEMODE_`, `TXM_EXIT`, `TXM_CDES`, `TXM_STOP`, `TXM_HURY`, `TXM_STRT`, `SPEC_PAUSE`, `\ntaxiService currentJourneyPrice = `, `INSERT_NEW_DESTINATION_TO_LIST - start \n`, `SHIFT_LIST_DOWN_1_PLACE_FROM_POSITION - start, position = `, `REPLACE_LIST_DESTINATION_WITH_NEW_DESTINATION - start \n`, `MPTXI_WT`, `MPTXI_BJ`, `MPTXI_AR`, `MPTXI_NM`, `MPTXI_CD`, `MPTXI_RA`, `MPTXI_OE`, `MPTXI_SR`, `MPTXI_ST`, `MPTXI_DB`, `MPTXI_US`

---

Source: `decompiled_scripts/am_taxi.c`
