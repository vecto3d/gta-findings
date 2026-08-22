# fm_content_kortz_equipment.c

MP freemode script. 16 anim dicts; 29 models; 4 scaleforms.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 528,182 |
| Functions | 11,426 (836 unique, 10,590 shared) |
| Unique lines | 23,432 (4.4% of file) |

## Assets

**Animation dictionaries** (16) - `anim@door_trans@hinge_l@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@scripted@freemode@ig3_open_container@male@`, `anim@scripted@ulp_missions@computerhack@male@`, `anim@scripted@ulp_missions@garageopen@male@`, `anim@heists@humane_labs@emp@hack_door`, `anim@scripted@tycoon@bt1@ig4_usb_hack@male@`, `anim@scripted@cbr5@ig1_cctv_tape_pull@heeled@`, `anim@scripted@cbr5@ig1_cctv_tape_pull@male@`, `anim@scripted@player@mission@tun_bunk_ig1_hdd_server@heeled@`, `anim@scripted@player@mission@tun_bunk_ig1_hdd_server@male@`, `anim@scripted@heist@ig6_explosive_plant@male@`, `anim_heist@hs3f@ig4_drone@male@`, `anim@scripted@freemode@ig1_open_container@no_tools@heeled@`, `anim@scripted@freemode@ig1_open_container@no_tools@male@`, `anim@heists@keycard@`

**Models and props** (29) - `v_ilev_ct_door01`, `v_ilev_rc_door2`, `v_ilev_ct_door03`, `prop_monitor_04a`, `v_ret_gc_chair03`, `ch_prop_ch_aircon_l_broken03`, `prop_keyboard_01a`, `v_corp_offchair`, `v_corp_cd_desklamp`, `prop_cardbordbox_02a`, `prop_cctv_unit_05`, `prop_cctv_cont_01`, `v_ind_cm_ladder`, `prop_fire_exting_1a`, `prop_fire_exting_1b`, `prop_keyboard_01b`, `prop_mouse_01b`, `g_f_importexport_01`, `g_m_importexport_01`, `V_ILEV_RC_DOOR2`, `prop_phone_ing_03`, `hei_prop_hst_usb_drive`, `mp_m_freemode_01`, `mp_f_freemode_01`, `ba_prop_battle_drone_quad`, `ch_prop_ch_phone_ing_01a`, `prop_cctv_cam_04c`, `prop_controller_01`, `hei_prop_container_lock`

**Sounds** (6) - `Barge_Door_Metal`, `dlc_h4_Prep_FC_Sounds`, `Garage_Door_Open`, `GTAO_Script_Doors_Faded_Screen_Sounds`, `Background`, `MP_CCTV_SOUNDSET`

**Scaleform movies** (4) - `SHOW_START_SCREEN`, `SHOW_CODE_SCREEN`, `SHOW_END_SCREEN`, `SECURITY_CAM`

**Text labels** (4) - `15HBW365`, `68KWK927`, `KEVC_TK_12`, `41GKJ183`

**Timecycle modifiers** (1) - `MissileOutOfRange`

**Vehicle mods** (1) - `rhino`

**Scripts launched** (1) - `word_hack`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (115), `SET_BIT` (48), `CLEAR_BIT` (39), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (29), `CREATE_MODEL_HIDE_EXCLUDING_SCRIPT_OBJECTS` (28), `REMOVE_MODEL_HIDE` (28), `NET_TO_ENT` (27), `GET_ENTITY_COORDS` (21), `SET_ENTITY_INVINCIBLE` (18), `PLAYER_PED_ID` (16), `GET_ROOM_KEY_FROM_ENTITY` (15), `SET_ENTITY_VISIBLE` (15), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (14), `GET_SYNCHRONIZED_SCENE_PHASE` (13), `FREEZE_ENTITY_POSITION` (12), `SET_MODEL_AS_NO_LONGER_NEEDED` (11), `GET_PLAYER_WANTED_LEVEL` (10), `DISABLE_CONTROL_ACTION` (9), `GET_ENTITY_HEADING` (9), `DOES_ENTITY_EXIST` (9), `IS_SYNCHRONIZED_SCENE_RUNNING` (8), `HIDE_HUD_AND_RADAR_THIS_FRAME` (8), `NETWORK_GET_PLAYER_INDEX` (8), `SET_ENTITY_COLLISION` (8), `REQUEST_MODEL` (8), `SET_PED_CONFIG_FLAG` (8), `IS_STRING_NULL_OR_EMPTY` (8), `SET_ENTITY_HEALTH` (7), `IS_SCREEN_FADED_OUT` (7), `DOES_CAM_EXIST` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-61.752f` x8 · `0.5f` x6 · `93.053f` x4 · `-72.997f` x4 · `2058.106f` x4 · `2994.3f` x4 · `-72.998f` x4 · `1071.77f` x4 · `-2279.016f` x4 · `-47.15f` x4 · `91.933f` x4 · `0.6f` x3 · `0.4f` x3 · `-2220.518f` x3 · `-48.85f` x3 · `-2359.631f` x3 · `3247.564f` x3 · `0.3f` x3 · `1.5f` x3 · `2060.052f` x3 · `2976.999f` x3 · `2047.02f` x2 · `2958.558f` x2 · `2060.854f` x2

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `ibs`, `int`, `typ`, `sprt`, `hclr`, `scl`, `rot`, `bsa`, `rad`, `xm_prop_iaa_base_door_01`, `enter`, `exit`, `xm_prop_iaa_base_door_02`, `blp`, `veh`, `tun_prep_grab_midd_ig3`, `action`, `walk_cam_left`, `walk_player1`, `Facility_Raid_Sounds`, `MAX_NUM_SCENARIOS`, `grp`

---

Source: `decompiled_scripts/fm_content_kortz_equipment.c`
