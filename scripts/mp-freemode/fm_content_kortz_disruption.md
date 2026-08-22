# fm_content_kortz_disruption.c

MP freemode script. 6 anim dicts; 10 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 521,831 |
| Functions | 11,008 (575 unique, 10,433 shared) |
| Unique lines | 26,174 (5.0% of file) |

## Assets

**Animation dictionaries** (6) - `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@scripted@heist@ig9_control_tower@male@`, `anim_heist@hs4f@ig14_open_car_trunk@male@`, `anim@scripted@heist@ig6_explosive_plant@male@`, `anim@scripted@tycoon@bt1@ig4_usb_hack@male@`, `anim@door_trans@hinge_l@`

**Models and props** (10) - `prop_cctv_cam_04c`, `prop_elecbox_10`, `gr_prop_inttruck_anchor`, `p_parachute_s_shop`, `gr_prop_inttruck_command_01`, `gr_prop_inttruck_carmod_01`, `gr_prop_inttruck_light_co_w_ol`, `gr_prop_inttruck_light_ca_w_ol`, `v_ilev_rc_door2`, `V_ILEV_RC_DOOR2`

**Audio banks** (1) - `DLC_MP2023_1/DLC_MP2023_1_FM`

**Sounds** (2) - `Barge_Door`, `dlc_h4_Prep_FC_Sounds`

**Texture dicts** (2) - `Prop_Screen_GR_Login`, `Prop_Screen_GR_Turret`

**Text labels** (3) - `ENTER`, `LOOP`, `EXIT`

**Interiors and entity sets** (2) - `GtaMloRoom001`, `Main_RM`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (121), `DOES_ENTITY_EXIST` (62), `IS_ENTITY_DEAD` (43), `NET_TO_VEH` (40), `NETWORK_DOES_NETWORK_ID_EXIST` (31), `NET_TO_OBJ` (31), `SET_PED_COMBAT_ATTRIBUTES` (23), `GET_ENTITY_COORDS` (22), `CLEAR_BIT` (19), `PLAYER_PED_ID` (17), `SET_PED_CONFIG_FLAG` (17), `GET_DISTANCE_BETWEEN_COORDS` (16), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (16), `SET_BIT` (16), `PLAYER_ID` (15), `DOES_BLIP_EXIST` (15), `IS_PED_IN_ANY_VEHICLE` (13), `SET_ENTITY_VISIBLE` (13), `GET_GAME_TIMER` (10), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (10), `SET_ENTITY_PROOFS` (10), `REMOVE_MODEL_HIDE` (10), `GET_ENTITY_HEALTH` (9), `NET_TO_PED` (9), `IS_ENTITY_VISIBLE` (9), `CREATE_MODEL_HIDE_EXCLUDING_SCRIPT_OBJECTS` (9), `REMOVE_BLIP` (8), `GET_BLIP_FROM_ENTITY` (8), `IS_PED_IN_VEHICLE` (7), `IS_ENTITY_PLAYING_ANIM` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x6 · `0.3f` x5 · `-2182.986f` x4 · `251.079f` x4 · `187.243f` x4 · `-0.4f` x4 · `0.43f` x2 · `-0.33f` x2 · `0.4f` x2 · `-2.5f` x2 · `-2261.073f` x2 · `211.593f` x2 · `177.462f` x2 · `-2308.08f` x2 · `250.621f` x2 · `174.112f` x2 · `-2214.276f` x2 · `337.7503f` x2 · `198.1113f` x2 · `-2182.266f` x2 · `250.606f` x2 · `183.564f` x2 · `-2195.544f` x2 · `267.948f` x2

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `ibs`, `int`, `typ`, `scl`, `sprt`, `hclr`, `rad`, `bsa`, `rot`, `KDEC_BLIP5`, `blp`, `veh`, `TXM_EXIT`, `KDEC_IHELP3`, `KOR_BM_TITLE`, `MAX_NUM_SCENARIOS`, `grp`, `speedo4`, `KDEC_HUDPLANT`, `KHD_INT_HLP3`, `tun_prep_grab_midd_ig3`, `GANGOPS_NM`, `KDEC_BLIP2`

---

Source: `decompiled_scripts/fm_content_kortz_disruption.c`
