# taxiservice.c

Jobs script. 1 anim dicts; 2 models; 11 scaleforms.

| | |
|---|---|
| Category | Jobs |
| Total lines | 12,825 |
| Functions | 237 (110 unique, 127 shared) |
| Unique lines | 7,300 (56.9% of file) |

## Assets

**Animation dictionaries** (1) - `oddjobs@taxi@driver`

**Animations** (3) - `leanover_enter`, `leanover_idle`, `leanover_exit`

**Models and props** (2) - `prop_taxi_meter_2`, `a_m_y_stlat_01`

**Sounds** (1) - `FADE_OUT_WORLD_250MS_SCENE`

**Speech contexts** (1) - `A_M_M_EASTSA_02_LATINO_FULL_01`

**Scaleform movies** (11) - `HIGHLIGHT_DESTINATION`, `instructional_buttons`, `SET_TAXI_PRICE`, `STRING`, `SHOW_TAXI_DESTINATION`, `SET_INPUT_EVENT`, `taxi_display`, `CLEAR_TAXI_DISPLAY`, `ADD_TAXI_DESTINATION`, `STRTNM1`, `STRTNM2`

**Text labels** (16) - `NULL`, `THANKS`, `CANNY`, `CHU`, `CHIL`, `COSI`, `CMSW`, `HORS`, `NCHU`, `PBOX`, `RTRAK`, `RGLEN`, `SANDY`, `SKID`, `TEXTI`, `STRAW`

**Vehicle mods** (1) - `taxi`

**Stats** (1) - `sp_number_of_taxis_used`

**Scripts launched** (1) - `ambient_solomon`

## Native vocabulary

Most-called natives inside the code unique to this script:

`ARE_STRINGS_EQUAL` (102), `PLAYER_PED_ID` (101), `IS_POINT_IN_ANGLED_AREA` (90), `IS_PED_INJURED` (44), `PLAYER_ID` (32), `IS_VEHICLE_DRIVEABLE` (27), `DOES_BLIP_EXIST` (27), `DOES_ENTITY_EXIST` (24), `VDIST2` (22), `GET_ENTITY_COORDS` (21), `IS_ENTITY_PLAYING_ANIM` (18), `IS_VEHICLE_SEAT_FREE` (16), `IS_PLAYER_PLAYING` (13), `STOP_PED_SPEAKING` (13), `GET_BLIP_COORDS` (13), `GET_RANDOM_INT_IN_RANGE` (13), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (12), `CLEAR_PED_TASKS` (11), `GET_GAME_TIMER` (11), `BEGIN_SCALEFORM_MOVIE_METHOD` (11), `END_SCALEFORM_MOVIE_METHOD` (11), `GET_PED_IN_VEHICLE_SEAT` (11), `IS_PED_SITTING_IN_VEHICLE` (10), `GET_BLIP_INFO_ID_TYPE` (10), `DISABLE_CONTROL_ACTION` (10), `GET_PED_AS_GROUP_MEMBER` (9), `IS_PED_IN_VEHICLE` (8), `DOES_CAM_EXIST` (8), `IS_CAM_ACTIVE` (8), `TO_FLOAT` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`4.2f` x4 · `0.5f` x3 · `-75.59782f` x3 · `-818.6082f` x3 · `325.1745f` x3 · `1137.022f` x3 · `89.06853f` x3 · `49.75f` x2 · `1324.172f` x2 · `1110.748f` x2 · `99.65493f` x2 · `1523.097f` x2 · `1110.473f` x2 · `132.8859f` x2 · `74.89022f` x2 · `1267.821f` x2 · `292.0106f` x2 · `102.9904f` x2 · `1882.79f` x2 · `4725.034f` x2 · `34.74373f` x2 · `1701.497f` x2 · `4677.47f` x2 · `47.89289f` x2

## Other strings

Literals whose consuming native was not classified:

`taxi`, `TXM_SLCT`, `LOCATION_LA_PUERTA`, `TAXID_WHERE_TO`, `TAXID_BEGIN_JOURNEY`, `TAXID_BANTER`, `TAXID_ARRIVE_AT_DEST`, `TAXID_CLOSE_AS_POSS`, `TAXID_NO_MONEY`, `TAXI_CHANGE_DEST`, `TAXID_CHANGE_DEST`, `TAXID_RUN_AWAY`, `TAXID_GET_OUT_EARLY`, `TAXID_TRASHED`, `TAXID_AFFORD_PART_JOURNEY`, `TAXID_TAKE_FIRST_CAB`, `RADIO_REQ_VIBE`, `RADIO_REQ_LRR`, `RADIO_REQ_JNR`, `RADIO_REQ_MASSIVEB`, `RADIO_REQ_K109`, `RADIO_REQ_WKTT`, `RADIO_REQ_LCHC`, `RADIO_REQ_JOURNEY`, `RADIO_REQ_FUSION`, `RADIO_REQ_BEAT`, `RADIO_REQ_BROKER`, `RADIO_REQ_VLADIVOSTOK`, `RADIO_REQ_PLR`, `RADIO_REQ_SANJUAN`

---

Source: `decompiled_scripts/taxiservice.c`
