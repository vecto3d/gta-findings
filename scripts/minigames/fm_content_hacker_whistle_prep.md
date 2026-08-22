# fm_content_hacker_whistle_prep.c

Minigames script. 9 anim dicts; 17 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 518,283 |
| Functions | 11,142 (672 unique, 10,470 shared) |
| Unique lines | 17,541 (3.4% of file) |

## Assets

**Animation dictionaries** (9) - `anim@door_trans@hinge_l@`, `anim@scripted@freemode@ig3_hold_up_phone@male@`, `anim@scripted@freemode@ig3_hold_up_phone@female@`, `anim@scripted@player@mission@tun_bunk_ig1_hdd_server@male@`, `anim@scripted@player@mission@tun_bunk_ig1_hdd_server@heeled@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@heeled@`, `anim@scripted@freemode@ig8_radio_car@male@`, `anim@scripted@freemode@ig8_radio_car@heeled@`

**Models and props** (17) - `v_res_j_tablelamp2`, `v_res_j_lowtable`, `prop_gascyl_04a`, `v_res_j_stool`, `v_res_j_phone`, `v_3_main_mesh_blinds`, `prop_radio_01`, `v_res_jcushiond`, `v_res_jcushionb`, `v_res_j_sofa`, `v_res_jcushionc`, `v_3_lng_mesh_timed`, `v_res_j_magrack`, `xs_prop_arena_screen_tv_01`, `prop_phone_ing`, `prop_rub_cardpile_07`, `hei_prop_heist_thermite_case`

**Audio banks** (1) - `ALARM_KLAXON_04`

**Sounds** (4) - `PICKUP_DEFAULT`, `HUD_FRONTEND_STANDARD_PICKUPS_SOUNDSET`, `Barge_Door`, `dlc_h4_Prep_FC_Sounds`

**Text labels** (2) - `HACK`, `UNKNOWN`

**Scripts launched** (1) - `AM_MP_RC_VEHICLE`

**Hashed names** (2) - `s_grab`, `AM_MP_RC_VEHICLE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (110), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (20), `SET_BIT` (11), `NET_TO_ENT` (11), `GET_ENTITY_COORDS` (10), `NETWORK_IS_PARTICIPANT_ACTIVE` (8), `NETWORK_GET_PLAYER_INDEX` (7), `DOES_ENTITY_EXIST` (7), `DISABLE_CONTROL_ACTION` (7), `GET_ENTITY_MODEL` (6), `GET_ENTITY_BONE_POSTION` (6), `GET_RANDOM_INT_IN_RANGE` (6), `NET_TO_VEH` (5), `SET_ENTITY_VISIBLE` (5), `CLEAR_PED_TASKS` (5), `PLAY_SOUND_FRONTEND` (5), `GET_PLAYER_PED` (4), `GET_VEHICLE_PED_IS_IN` (4), `IS_ENTITY_VISIBLE` (4), `GET_ENTITY_BONE_INDEX_BY_NAME` (4), `SET_TV_CHANNEL` (4), `NETWORK_GET_PARTICIPANT_INDEX` (3), `SET_ENTITY_COLLISION` (3), `POW` (3), `SET_NETWORK_ID_CAN_MIGRATE` (3), `GET_HASH_KEY` (3), `IS_VEHICLE_DRIVEABLE` (3), `PARTICIPANT_ID_TO_INT` (3), `IS_SYNCHRONIZED_SCENE_RUNNING` (3), `GET_SYNCHRONIZED_SCENE_PHASE` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`69.52f` x6 · `-111.229f` x3 · `-12.262f` x3 · `0.1f` x1 · `-111.304f` x1 · `-12.372f` x1 · `69.929f` x1 · `-112.713f` x1 · `-12.767f` x1 · `-112.251f` x1 · `-13.961f` x1 · `-110.974f` x1 · `-9.748f` x1 · `71.309f` x1 · `-114.1774f` x1 · `-10.0945f` x1 · `70.4813f` x1 · `-112.66f` x1 · `-9.171f` x1 · `70.1f` x1 · `-113.076f` x1 · `-9.206f` x1 · `70.074f` x1 · `-112.121f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `rcbandito`, `head`, `int`, `typ`, `ibs`, `hclr`, `sprt`, `scl`, `bsa`, `rad`, `rot`, `X24_JODI`, `blp`, `veh`, `HF_BMT_3`, `MAX_NUM_SCENARIOS`, `grp`, `tri`, `erot`, `wrpc`, `WBMW_BLP_MALW`, `crt`, `brd`

---

Source: `decompiled_scripts/fm_content_hacker_whistle_prep.c`
