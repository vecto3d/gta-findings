# fm_content_security_contract.c

MP freemode script. 12 anim dicts; 32 models; 2 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 540,297 |
| Functions | 11,185 (786 unique, 10,399 shared) |
| Unique lines | 29,226 (5.4% of file) |

## Assets

**Animation dictionaries** (12) - `anim@door_trans@hinge_l@`, `amb@code_human_cower@male@idle_a`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@heeled@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `move_m@injured`, `move_f@injured`, `mini@safe_cracking`, `ANIM_HEIST@HS3F@IG6_PUSH_BUTTON@FEMALE@`, `ANIM_HEIST@HS3F@IG6_PUSH_BUTTON@MALE@`, `anim@scripted@player@mission@tun_bomb_plant@heeled@`, `anim@scripted@player@mission@tun_bomb_plant@male@`, `anim@apt_trans@garage`

**Animations** (1) - `DOOR_OPEN_SUCCEED_STAND_SAFE`

**Models and props** (32) - `s_m_m_highsec_01`, `a_m_o_acult_02`, `a_m_y_runner_02`, `g_m_y_mexgang_01`, `g_m_y_korlieut_01`, `a_f_y_business_02`, `a_m_y_business_03`, `prop_cd_paper_pile1`, `sf_prop_v_43_safe_s_bk_01b`, `v_club_vu_drawer`, `v_ind_rc_locker`, `v_ilev_roc_door4`, `v_ilev_vag_door`, `v_ilev_bl_shutter2`, `ch_prop_whiteboard`, `ch_prop_whiteboard_03`, `v_ilev_fib_door1`, `prop_drug_package`, `prop_strip_door_01`, `prop_magenta_door`, `sf_prop_v_43_safe_s_bk_01a`, `v_ilev_bl_door_r`, `v_ilev_bl_door_l`, `v_ilev_roc_door3`, `g_f_importexport_01`, `g_m_importexport_01`, `bkr_prop_prtmachine_dryer_spin`, `sf_prop_sf_box_cash_01a`, `ch_Prop_Ch_LD_Bomb_01a`, `v_ilev_rc_door2`, `sf_prop_sf_cam_case_01a`, `Prop_Pap_Camera_01`

**Audio banks** (2) - `SCRIPT/ALARM_KLAXON_06`, `DLC_SECURITY/DLC_Sec_Contract_Monkey`

**Sounds** (26) - `DLC_SECURITY_TAIL_AND_DESTROY_Sounds`, `Contract_Recovery_Vehicle_Collision_Mute_Scene`, `GTAO_Script_Doors_Faded_Screen_Sounds`, `Destroy`, `PICK_UP`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `Metal_Door_Push`, `GTAO_Script_Doors_Sounds`, `Barge_Door_Metal`, `DLC_Security_Door_Barge_Sounds`, `Press`, `DLC_SECURITY_BUTTON_PRESS_SOUNDS`, `Collect_Pass`, `PrSCRV_Elevator_Pass_Sounds`, `Garage_Door_Open`, `Push`, `GTAO_APT_DOOR_DOWNSTAIRS_WOOD_SOUNDS`, `Barge_Door`, `dlc_h4_Prep_FC_Sounds`, `Garage_Door_Close`, `Explosion_Internal`, `Countdown_Main`, `Countdown_5_secs`, `Countdown_0_secs`, `Smoke_Loop`, `Explosion_External`

**Speech contexts** (1) - `SPEECH_PARAMS_FORCE`

**Particle effects** (2) - `scr_tn_tr`, `scr_tn_tr_door_smoke`

**Text labels** (20) - `FXFRAUD`, `NULL`, `DODGE`, `OLG28311`, `44EVH397`, `01LHV430`, `68KWK927`, `15HBW365`, `06NZQ185`, `86CVG072`, `05YJI028`, `65GRZ071`, `84TFX949`, `77FQX299`, `83RHD141`, `49TGN381`, `ENTER`, `26IRY245`, `69OSH438`, `07FUV374`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (183), `DATADICT_GET_ARRAY` (108), `SET_BIT` (49), `NET_TO_ENT` (38), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (37), `SET_PED_PROP_INDEX` (27), `DOES_ENTITY_EXIST` (24), `GET_RANDOM_INT_IN_RANGE` (22), `GET_ENTITY_COORDS` (21), `SET_VEHICLE_DOOR_OPEN` (20), `GET_SYNCHRONIZED_SCENE_PHASE` (15), `PLAY_SOUND_FRONTEND` (13), `IS_ENTITY_VISIBLE` (13), `SET_ENTITY_HEALTH` (11), `GET_ENTITY_MODEL` (11), `SET_CURRENT_PED_WEAPON` (10), `SET_PED_COMBAT_ATTRIBUTES` (10), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (10), `NET_TO_OBJ` (10), `SET_PED_CONFIG_FLAG` (9), `IS_SYNCHRONIZED_SCENE_RUNNING` (9), `SET_ENTITY_VISIBLE` (8), `CLEAR_BIT` (8), `STOP_SOUND` (8), `IS_PED_IN_ANY_VEHICLE` (7), `HAS_PED_GOT_WEAPON` (7), `CLEAR_PED_TASKS` (7), `DISABLE_CONTROL_ACTION` (7), `GET_ENTITY_HEALTH` (6), `SET_PED_RELATIONSHIP_GROUP_HASH` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x6 · `27.7368f` x4 · `1.2f` x4 · `2712.903f` x4 · `-54.234f` x4 · `0.1f` x3 · `0.4f` x2 · `1.5f` x2 · `0.664f` x2 · `104.5863f` x2 · `-1299.615f` x2 · `110.5354f` x2 · `-1296.307f` x2 · `28.972f` x2 · `1005.168f` x2 · `-2998.267f` x2 · `-39.496f` x2 · `0.6f` x2 · `0.99f` x2 · `-366.175f` x2 · `-372.687f` x2 · `-31.724f` x1 · `-1101.847f` x1 · `26.572f` x1

## Other strings

Literals whose consuming native was not classified:

`mp_g_m_pros_01`, `pos`, `num`, `head`, `int`, `FXR_GOTO`, `typ`, `FXR_OT_RCVR`, `sprt`, `hclr`, `scl`, `FIX_FRANKLIN`, `WORLD_HUMAN_HANG_OUT_STREET`, `rad`, `bsa`, `ibs`, `FIXER_DELIVERING_START`, `GENERIC_THANKS`, `GENERIC_CURSE_MED`, `GENERIC_FRIGHTENED_HIGH`, `FXR_GOTO_THE`, `FIXER_GUNFIGHT`, `FIXER_MED_INTENSITY`, `FXR_TKE_OUT`, `FXR_ENTER_THE`, `comet7`, `maverick`, `WORLD_HUMAN_SMOKING`

---

Source: `decompiled_scripts/fm_content_security_contract.c`
