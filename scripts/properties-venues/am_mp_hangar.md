# am_mp_hangar.c

Properties and venues script. 9 anim dicts; 21 models; 2 scaleforms.

| | |
|---|---|
| Category | Properties and venues |
| Total lines | 604,531 |
| Functions | 10,406 (314 unique, 10,092 shared) |
| Unique lines | 28,778 (4.8% of file) |

## Assets

**Animation dictionaries** (9) - `ANIM@AMB@CLUBHOUSE@SEATING@FEMALE@VAR_A@BASE@`, `ANIM@AMB@CLUBHOUSE@SEATING@MALE@VAR_A@BASE@`, `ANIM@AMB@CLUBHOUSE@SEATING@FEMALE@VAR_B@BASE@`, `ANIM@AMB@CLUBHOUSE@SEATING@MALE@VAR_B@BASE@`, `ANIM@AMB@CLUBHOUSE@SEATING@FEMALE@VAR_C@BASE@`, `ANIM@AMB@CLUBHOUSE@SEATING@MALE@VAR_C@BASE@`, `ANIM@AMB@CLUBHOUSE@BOSS@FEMALE@`, `ANIM@AMB@CLUBHOUSE@BOSS@MALE@`, `anim@apt_trans@garage`

**Animations** (1) - `exit`

**Models and props** (21) - `v_ilev_rc_door2`, `hei_prop_hei_securitypanel`, `PROP_OFF_M_6`, `PROP_OFF_M_6F`, `sm_prop_smug_offchair_01a`, `s_m_m_fiboffice_02`, `prop_tool_box_04`, `sm_prop_smug_havok`, `sm_prop_smug_monitor_01`, `p_para_bag_xmas_s`, `prop_cs_server_drive`, `hei_prop_hst_usb_drive`, `sm_prop_smug_crate_m_medical`, `sm_prop_smug_crate_m_tobacco`, `sm_prop_smug_crate_m_antiques`, `sm_prop_smug_crate_m_narc`, `sm_prop_smug_crate_m_jewellery`, `sm_prop_smug_crate_m_bones`, `sm_prop_smug_crate_m_fake`, `sm_prop_smug_crate_m_hazard`, `gr_prop_gr_bench_01b`

**Sounds** (8) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `SELECT`, `HUD_FREEMODE_SOUNDSET`, `MCU_FirstPerson_Seated_Scene`, `CANCEL`, `NAV_UP_DOWN`, `BACK`, `ERROR`

**Scaleform movies** (2) - `SET_TITLE`, `LBD_DPD_CNT`

**Texture dicts** (1) - `prop_screen_sm_free_trade_shipping`

**Text labels** (10) - `WHOUSEINPUTTR`, `SECINPUTTREG`, `OFFLAPTOPPC`, `OFFLAPTOP`, `ORINPUTTREGPC`, `CLBHINPUTTRIG`, `ORINPUTTREG`, `BRSCRWTEX`, `NULL`, `64081`

**Decorators** (3) - `MPBitset`, `Player_Avenger`, `Player_Vehicle`

**Interiors and entity sets** (1) - `GtaMloRoom001`

**Vehicle mods** (3) - `valkyrie`, `strikeforce`, `tula`

**Scripts launched** (2) - `appjipmp`, `appmpjoblistnew`

**Hashed names** (4) - `sm_Prop_Smug_Wall_Radio_01`, `VEM_AAM_OPERATIONS_TERMINAL_1_t0_v0`, `PACKED_MP_INT_AVENGER_OPERATIONS_TERMINAL_v0`, `fade`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (366), `PLAYER_PED_ID` (207), `SET_BIT` (149), `CLEAR_BIT` (119), `NET_TO_VEH` (97), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (41), `GET_NETWORK_TIME` (37), `DOES_ENTITY_EXIST` (35), `IS_PED_IN_VEHICLE` (33), `GET_PLAYER_PED` (30), `GET_SCRIPT_TASK_STATUS` (29), `GET_ENTITY_MODEL` (24), `IS_CONTROL_PRESSED` (23), `IS_PED_IN_ANY_VEHICLE` (20), `DISABLE_CONTROL_ACTION` (20), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (19), `VMAG` (19), `IS_SCREEN_FADED_OUT` (19), `IS_ENTITY_DEAD` (19), `DOES_BLIP_EXIST` (18), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (17), `GET_VEHICLE_PED_IS_IN` (17), `NET_TO_ENT` (16), `GET_TIME_DIFFERENCE` (15), `NETWORK_REQUEST_CONTROL_OF_NETWORK_ID` (14), `IS_VALID_INTERIOR` (14), `SET_PED_CONFIG_FLAG` (14), `PLAY_SOUND_FRONTEND` (14), `CLEAR_HELP` (13), `GET_FRAME_COUNT` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.75f` x8 · `0.5f` x5 · `-49.49f` x5 · `-1.5f` x3 · `-3014.836f` x2 · `-1266.802f` x2 · `1.5f` x2 · `-2210.719f` x2 · `2964.25f` x2 · `31.8199f` x2 · `-1235.25f` x2 · `-3000.18f` x2 · `-42.72f` x2 · `-1234.43f` x2 · `-2986.97f` x2 · `-41.12f` x2 · `-1239.92f` x2 · `-3001.34f` x2 · `-43.26f` x2 · `-1294.71f` x2 · `-3005.12f` x2 · `-1266.801f` x2 · `-2970.337f` x2 · `-49.4897f` x2

## Other strings

Literals whose consuming native was not classified:

`Smug_Monitor_01`, `MPOFSEAT_EXIT`, `MPOFSEAT_PCEXIT`, `OFF_COMP_MIS`, `OFF_COMP_BDY`, `MPOF_AC_EXIT`, `MPOF_AC_PC_EXIT`, `HANGAR_LPTP_HLP`, `HANGAR_PAM_HLP`, `STOR_TIC_H`, `enter`, `MPJAC_SIT`, `MP_1`, `tailgater`, `WHOUSEINPUTTRPC`, `SECINPUTTREGPC`, `CLBHINPUTTRIGPC`, `OFF_COMP_CH`, `OFF_COMP_CH_PC`, `OFF_COMP_CHV`, `OFF_COMP_CHV_PC`, `GtaMloRoom001`, `avenger`, `BB_YES`, `BB_NO`, `MAN_VEH_STOR_T`, `MAN_VEH_L`, `BB_BACK`, `MPTV_WALKOFF`, `CHAR_HELP2`

---

Source: `decompiled_scripts/am_mp_hangar.c`
