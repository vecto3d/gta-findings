# fm_content_kortz_task.c

MP freemode script. 7 anim dicts; 8 models; 4 scaleforms.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 510,111 |
| Functions | 10,583 (359 unique, 10,224 shared) |
| Unique lines | 10,323 (2.0% of file) |

## Assets

**Animation dictionaries** (7) - `anim@door_trans@hinge_l@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@heeled@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim_heist@hs3f@ig12_change_clothes@`, `anim@scripted@heist@ig9_control_tower@male@`, `ANIM@SCRIPTED@PLAYER@FREEMODE@IG5_SAFE_CRACK@HEELED@`, `ANIM@SCRIPTED@PLAYER@FREEMODE@IG5_SAFE_CRACK@MALE@`

**Models and props** (8) - `v_ret_gc_lamp`, `v_ind_cs_toolbox3`, `prop_weed_tub_01`, `v_res_officeboxfile01`, `v_ind_ss_box04`, `v_ret_gc_folder1`, `s_m_y_construct_01`, `v_ilev_ss_door5_l`

**Audio banks** (1) - `DLC_HEI4/DLCHEI4_GENERIC_01`

**Sounds** (11) - `Safe_Minigame_Sounds`, `Push`, `GTAO_APT_DOOR_DOWNSTAIRS_GENERIC_SOUNDS`, `Barge_Door`, `dlc_h4_Prep_FC_Sounds`, `Clothes_Swap`, `GTAO_Change_Outfit_Sounds`, `Input_Code_Enter_Correct_Final`, `Input_Code_Enter_Wrong`, `Input_Code_Up`, `Input_Code_Down`

**Scaleform movies** (4) - `SET_STATE`, `DIGITAL_SAFE_DISPLAY`, `SET_VALUE`, `SET_CURSOR_POSITION`

**Text labels** (3) - `LOOP`, `ENTER`, `EXIT`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (95), `NET_TO_ENT` (23), `SET_BIT` (21), `SET_PED_CONFIG_FLAG` (19), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (17), `PLAYER_PED_ID` (13), `ROUND` (12), `CREATE_MODEL_HIDE` (10), `REMOVE_MODEL_HIDE` (10), `GET_ENTITY_COORDS` (9), `SET_PED_COMBAT_ATTRIBUTES` (9), `CLEAR_BIT` (8), `GET_RANDOM_INT_IN_RANGE` (8), `DISABLE_CONTROL_ACTION` (6), `CLEAR_PED_TASKS` (6), `DOES_ENTITY_EXIST` (6), `PLAY_SOUND_FRONTEND` (6), `NETWORK_GET_PLAYER_INDEX` (5), `IS_STRING_NULL_OR_EMPTY` (5), `NETWORK_PLAYER_ID_TO_INT` (4), `GET_VEHICLE_INDIVIDUAL_DOOR_LOCK_STATUS` (4), `SET_VEHICLE_INDIVIDUAL_DOORS_LOCKED` (4), `IS_PED_INJURED` (4), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (4), `IS_DISABLED_CONTROL_JUST_PRESSED` (4), `ABSF` (4), `NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE` (4), `NETWORK_IS_PARTICIPANT_ACTIVE` (3), `DOES_BLIP_EXIST` (3), `DOES_PICKUP_EXIST` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`21.706f` x4 · `-1395.594f` x4 · `-74.224f` x4 · `-73.85f` x3 · `0.5f` x2 · `23.788f` x2 · `-1390.253f` x2 · `-73.944f` x2 · `23.787f` x2 · `-1390.21f` x2 · `-74.373f` x2 · `23.801f` x2 · `-1390.133f` x2 · `-74.727f` x2 · `21.507f` x2 · `-1395.206f` x2 · `-73.606f` x2 · `21.492f` x2 · `-1395.202f` x2 · `-73.402f` x2 · `21.279f` x2 · `-1395.285f` x2 · `-73.433f` x2 · `20.371f` x2

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `typ`, `sprt`, `hclr`, `scl`, `bsa`, `ibs`, `blp`, `veh`, `rot`, `rad`, `MAX_NUM_SCENARIOS`, `grp`, `m32_safe_01a`, `idx`, `MAX_NUM_TRANSITIONS`, `KTPD_LOC_0`, `fmbs`, `crt`, `wpn`

---

Source: `decompiled_scripts/fm_content_kortz_task.c`
