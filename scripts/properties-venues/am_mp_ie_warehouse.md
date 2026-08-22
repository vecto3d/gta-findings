# am_mp_ie_warehouse.c

Properties and venues script. 17 anim dicts; 20 models.

| | |
|---|---|
| Category | Properties and venues |
| Total lines | 387,311 |
| Functions | 7,076 (168 unique, 6,908 shared) |
| Unique lines | 16,554 (4.3% of file) |

## Assets

**Animation dictionaries** (17) - `ANIM@AMB@CLUBHOUSE@BOARDROOM@BOSS@FEMALE@BASE@`, `ANIM@AMB@CLUBHOUSE@BOARDROOM@BOSS@MALE@BASE@`, `ANIM@AMB@CLUBHOUSE@BOARDROOM@CREW@FEMALE@VAR_A@BASE@`, `ANIM@AMB@CLUBHOUSE@BOARDROOM@CREW@MALE@VAR_A@BASE@`, `ANIM@AMB@CLUBHOUSE@BOARDROOM@CREW@FEMALE@VAR_B@BASE@`, `ANIM@AMB@CLUBHOUSE@BOARDROOM@CREW@MALE@VAR_B@BASE@`, `ANIM@AMB@CLUBHOUSE@BOARDROOM@CREW@FEMALE@VAR_C@BASE@`, `ANIM@AMB@CLUBHOUSE@BOARDROOM@CREW@MALE@VAR_C@BASE@`, `ANIM@AMB@CLUBHOUSE@SEATING@FEMALE@VAR_A@BASE@`, `ANIM@AMB@CLUBHOUSE@SEATING@MALE@VAR_A@BASE@`, `ANIM@AMB@CLUBHOUSE@SEATING@FEMALE@VAR_B@BASE@`, `ANIM@AMB@CLUBHOUSE@SEATING@MALE@VAR_B@BASE@`, `ANIM@AMB@CLUBHOUSE@SEATING@FEMALE@VAR_C@BASE@`, `ANIM@AMB@CLUBHOUSE@SEATING@MALE@VAR_C@BASE@`, `anim@apt_trans@garage`, `ANIM@AMB@CLUBHOUSE@BOSS@FEMALE@`, `ANIM@AMB@CLUBHOUSE@BOSS@MALE@`

**Animations** (1) - `exit`

**Models and props** (20) - `Prop_ImpExp_Lappy_01a`, `PROP_OFF_M_6`, `PROP_OFF_M_6F`, `imp_prop_covered_vehicle_01a`, `prop_phonebox_03`, `imp_prop_impexp_lappy_01a`, `prop_vend_soda_01`, `v_ilev_roc_door2`, `v_ilev_roc_door3`, `ex_prop_crate_ammo_bc`, `prop_box_ammo05b`, `imp_prop_impexp_carrack`, `imp_prop_covered_vehicle_02a`, `imp_prop_covered_vehicle_03a`, `imp_prop_covered_vehicle_04a`, `imp_prop_covered_vehicle_05a`, `imp_prop_covered_vehicle_06a`, `prop_vend_soda_02`, `sf_prop_sf_vend_drink_01a`, `bkr_prop_clubhouse_offchair_01a`

**Sounds** (1) - `MP_POSITIONED_RADIO_MUTE_SCENE`

**Texture dicts** (1) - `Prop_Screen_IE_Adhawk`

**Text labels** (9) - `WHOUSEINPUTTR`, `SECINPUTTREG`, `OFFLAPTOPPC`, `OFFLAPTOP`, `ORINPUTTREGPC`, `CLBHINPUTTRIG`, `ORINPUTTREG`, `NULL`, `AHAPRIVSES`

**Decorators** (2) - `MPBitset`, `Player_Vehicle`

**Interiors and entity sets** (13) - `Basic_style_set`, `Branded_style_set`, `Urban_style_set`, `pump_01`, `pump_06`, `pump_07`, `pump_08`, `pump_02`, `pump_03`, `pump_04`, `pump_05`, `imp_impexp_intwaremed`, `imp_impexp_int_02`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (144), `PLAYER_PED_ID` (124), `PLAYER_ID` (91), `CLEAR_BIT` (50), `SET_BIT` (41), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (39), `NET_TO_VEH` (29), `DISABLE_CONTROL_ACTION` (28), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (25), `DOES_ENTITY_EXIST` (20), `GET_ENTITY_MODEL` (19), `IS_INTERIOR_ENTITY_SET_ACTIVE` (15), `RESERVE_LOCAL_NETWORK_MISSION_OBJECTS` (15), `GET_NUM_RESERVED_MISSION_OBJECTS` (15), `GET_SCRIPT_TASK_STATUS` (14), `GET_PLAYER_PED` (12), `SET_MODEL_AS_NO_LONGER_NEEDED` (11), `NETWORK_CREATE_SYNCHRONISED_SCENE` (11), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (11), `NETWORK_START_SYNCHRONISED_SCENE` (11), `NETWORK_REQUEST_CONTROL_OF_NETWORK_ID` (9), `FREEZE_ENTITY_POSITION` (9), `SET_ENTITY_ALPHA` (9), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (8), `INT_TO_PARTICIPANTINDEX` (8), `CLEAR_HELP` (8), `RESERVE_NETWORK_MISSION_VEHICLES` (8), `GET_NUM_RESERVED_MISSION_VEHICLES` (8), `ACTIVATE_INTERIOR_ENTITY_SET` (8), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x9 · `-1.5f` x6 · `-40.647f` x4 · `0.05f` x2 · `1.5f` x2 · `0.15f` x2 · `961.2841f` x2 · `-2999.709f` x2 · `-40.6349f` x2 · `967.4402f` x2 · `-3007.415f` x2 · `977.202f` x2 · `-2997.681f` x2 · `970.4088f` x1 · `-3013.568f` x1 · `-48.54214f` x1 · `970.3889f` x1 · `-2985.818f` x1 · `-43.78562f` x1 · `68.4375f` x1 · `974.9542f` x1 · `-3000.091f` x1 · `0.1f` x1 · `0.9f` x1

## Other strings

Literals whose consuming native was not classified:

`phantom2`, `dune5`, `mp_m_execpa_01`, `exit`, `MPJAC_SIT`, `RADIO_NA_PP`, `enter`, `MPOF_AC_PC_EXIT`, `MPOF_AC_EXIT`, `MPOFSEAT_PCEXIT`, `MPOFSEAT_EXIT`, `ob_vend1`, `OFF_COMP_MIS`, `OFF_COMP_BDY`, `MPOFFCH_NO_SIT`, `MPTV_WALKOFF`, `IntWareMed_office`, `WHOUSEINPUTTRPC`, `SECINPUTTREGPC`, `CLBHINPUTTRIGPC`, `OFF_COMP_CH`, `OFF_COMP_CH_PC`, `OFF_COMP_CHV`, `OFF_COMP_CHV_PC`, `Male_PA`, `Female_PA_02`, `MPJAC_NO_SIT`, `boxville5`, `wastelander`, `CUST_GAR_LEAVEH`

---

Source: `decompiled_scripts/am_mp_ie_warehouse.c`
