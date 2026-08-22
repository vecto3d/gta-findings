# am_mp_simeon_showroom.c

MP ambient script. 2 anim dicts; 13 models; 4 scaleforms.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 481,080 |
| Functions | 7,849 (166 unique, 7,683 shared) |
| Unique lines | 18,547 (3.9% of file) |

## Assets

**Animation dictionaries** (2) - `anim@amb@prop_human_seat_computer@male@idle_a`, `AMB@WORLD_HUMAN_STAND_MOBILE@MALE@TEXT@IDLE_A`

**Models and props** (13) - `prop_off_chair_05`, `prop_bin_12a`, `prop_box_wood06a`, `tr_prop_tr_laptop_jimmy`, `prop_vend_soda_01`, `v_club_officechair`, `v_15_garg_delta_doorup`, `v_ilev_csr_door_l`, `v_ilev_csr_door_r`, `v_ret_csr_signtrismall`, `prop_vend_soda_02`, `sf_prop_sf_vend_drink_01a`, `prop_amb_phone`

**Sounds** (4) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `NAV_UP_DOWN`, `SELECT`, `BACK`

**Speech contexts** (1) - `SIMEON`

**Scaleform movies** (4) - `SET_VEHICLE_INFOR_AND_STATS`, `FM_TWO_STRINGS`, `SET_PLAYER_NAME`, `SET_CREW_NAME`

**Texture dicts** (4) - `MPCarHUD`, `MPCarHUD2`, `MPCarHUD3`, `MPCarHUD4`

**Text labels** (2) - `NULL`, `BUMP`

**Interiors and entity sets** (5) - `csr_beforeMission`, `csr_inMission`, `csr_afterMissionA`, `csr_afterMissionB`, `shutter_closed`

**Doors** (1) - `v_ilev_fib_door1`

**Scripts launched** (2) - `simeon_showroom_seating`, `appinternet`

**Hashed names** (2) - `simeon_showroom_seating`, `sm_Prop_Smug_Wall_Radio_01`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (111), `PLAYER_PED_ID` (78), `DISABLE_CONTROL_ACTION` (41), `GET_NETWORK_TIME` (31), `DOES_ENTITY_EXIST` (29), `SET_BIT` (22), `GET_ENTITY_COORDS` (19), `VMAG` (19), `FREEZE_ENTITY_POSITION` (16), `CLEAR_BIT` (13), `SET_ENTITY_COLLISION` (13), `SET_ENTITY_VISIBLE` (12), `GET_RANDOM_FLOAT_IN_RANGE` (12), `IS_ENTITY_IN_ANGLED_AREA` (12), `SET_ENTITY_INVINCIBLE` (11), `SET_MODEL_AS_NO_LONGER_NEEDED` (11), `GET_TIME_DIFFERENCE` (11), `GET_ID_OF_THIS_THREAD` (10), `SET_ENTITY_COORDS_NO_OFFSET` (9), `IS_PED_IN_ANY_VEHICLE` (9), `VDIST` (9), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (7), `SET_ENTITY_CAN_BE_DAMAGED` (7), `GET_ENTITY_HEADING` (7), `GET_ENTITY_MODEL` (7), `DO_SCREEN_FADE_OUT` (6), `IS_PLAYER_DEAD` (6), `IS_SCREEN_FADED_IN` (6), `REQUEST_STREAMED_TEXTURE_DICT` (6), `HAS_STREAMED_TEXTURE_DICT_LOADED` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`25.5f` x7 · `30.4602f` x7 · `0.5f` x3 · `-57.07786f` x2 · `-1098.043f` x2 · `26.31279f` x2 · `3.5f` x2 · `-31.72f` x2 · `-1101.85f` x2 · `26.57f` x2 · `-152.75f` x1 · `-56.60036f` x1 · `-1097.348f` x1 · `25.42234f` x1 · `-57.79908f` x1 · `-1098.031f` x1 · `27.42243f` x1 · `1.5f` x1 · `-52.441f` x1 · `-1088.067f` x1 · `26.36107f` x1 · `-59.5f` x1 · `-1091.125f` x1 · `-31.2f` x1

## Other strings

Literals whose consuming native was not classified:

`ob_vend1`, `IDLE_A`, `simeon_showroom_seating`, `tr_prop_tr_laptop_jimmy`, `KEEP_LIV_P`, `SIM_SRM_M_D_0b`, `SIM_SRM_M_D_0a`, `windscreen`, `tailgater`, `GENERIC_HI`, `dlc_mpsum2_v_carshowroom_scene`, `BROWSEINPUTTRIG`, `WWW_SOUTHERNSANANDREASSUPERAUTOS_COM`, `SIM_SRM_VEH_IC`, `net_test_drive`, `HAND_SHAKE`, `SIM_SRM_BLIP`, `SIM_SRM_M_D_0`, `BUY_VEH_CONF`, `LUX_SRM_M_D_1`, `SIM_SRM_M_D_1b`, `SIM_SRM_M_TTL`, `SIM_SRM_M_O_0`, `SIM_SRM_M_O_1`, `ITEM_SELECT`, `ITEM_BACK`, `ShopUI_Title_Premium_Deluxe_Motorsport`, `SIM_SRM_DEF`, `SIM_SRM_WANTED`, `SIM_SRM_DEATHM`

---

Source: `decompiled_scripts/am_mp_simeon_showroom.c`
