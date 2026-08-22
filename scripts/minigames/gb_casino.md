# gb_casino.c

Minigames script. 16 anim dicts; 144 models; 2 particle effects.

| | |
|---|---|
| Category | Minigames |
| Total lines | 575,219 |
| Functions | 10,855 (1,760 unique, 9,095 shared) |
| Unique lines | 88,910 (15.5% of file) |

## Assets

**Animation dictionaries** (16) - `anim@mugging@mugger@catch_melee@`, `anim@mugging@mugger@catch_1h_gun@`, `anim@mugging@mugger@catch_2h_gun@`, `P_cargo_chute_S`, `anim@mugging@victim@toss_ped@`, `mini@safe_cracking`, `weapons@first_person@aim_lt@p_m_zero@submachine_gun@smg@fidgets@a`, `amb@world_human_window_shop@male@idle_a`, `anim@amb@waving@male`, `anim@amb@casino@staff_problems@ig_0_v0@`, `anim@amb@casino@staff_problems@ig_1_v1@`, `anim@amb@casino@staff_problems@ig_2_v2@`, `anim@apt_trans@hinge_r`, `anim@heists@keycard@`, `anim@GangOps@Morgue@Office@Laptop@`, `anim@GangOps@Facility@Servers@BodySearch@`

**Animations** (7) - `anim@mugging@victim@toss_ped@`, `throw_object_left_pocket_male`, `P_cargo_chute_S`, `P_cargo_chute_S_crumple`, `mini@safe_cracking`, `DOOR_OPEN_SUCCEED_STAND`, `P_cargo_chute_S_deploy`

**Models and props** (144) - `g_m_y_pologoon_01`, `a_m_y_smartcaspat_01`, `s_m_m_highsec_01`, `g_m_y_lost_01`, `g_m_y_korean_01`, `s_m_m_armoured_01`, `s_m_m_pilot_01`, `a_m_y_genstreet_02`, `s_m_m_security_01`, `a_m_m_business_01`, `a_m_y_runner_01`, `prop_box_wood04a`, `s_m_m_highsec_02`, `prop_air_cargo_01a`, `gr_prop_gr_target_02b`, `a_m_o_genstreet_01`, `g_m_importexport_01`, `prop_ld_keypad_01b`, `vw_prop_vw_table_01a`, `prop_const_fence02b`, `s_m_m_ciasec_01`, `a_f_y_hipster_04`, `a_m_y_bevhills_02`, `s_m_y_pestcont_01`, `s_m_y_construct_02`, `s_m_m_gentransport`, `prop_laptop_01a`, `prop_conc_sacks_02a`, `a_m_y_runner_02`, `u_m_y_croupthief_01`, `a_m_o_beach_01`, `g_m_y_mexgoon_02`, `a_m_o_acult_02`, `a_f_y_vinewood_01`, `a_m_y_hipster_01`, `prop_sec_gate_01c`, `prop_const_fence02a`, `vw_prop_vw_chipsmachine_01a`, `vw_prop_vw_chip_carrier_01a`, `vw_prop_vw_whousedoor_01a`, `s_m_m_dockwork_01`, `a_m_y_business_01`, `s_m_m_movalien_01`, `prop_skid_tent_01`, `gr_prop_gr_hobo_stove_01`, `hei_prop_hei_securitypanel`, `prop_contr_03b_ld`, `vw_prop_vw_key_cabinet_01a`, `vw_prop_vw_v_brochure_01a`, `vw_prop_vw_board_01a`, `vw_prop_vw_v_blueprt_01a`, `a_m_m_bevhills_02`, `a_m_m_golfer_01`, `s_m_y_cop_01`, `a_m_m_genfat_01`, `s_m_y_grip_01`, `a_f_y_hipster_02`, `s_m_m_paramedic_01`, `prop_lrggate_01_l`, `prop_lrggate_01_r` ...

**Audio banks** (5) - `ALARM_KLAXON_01`, `SAFE_CRACK`, `DLC_VINEWOOD/VW_COUNTERFEIT_CHIPS`, `DLC_VINEWOOD/VW_TRACKING_CHIPS`, `DLC_MPHEIST/HEIST_USE_KEYPAD`

**Sounds** (37) - `GTAO_FM_Events_Soundset`, `dlc_vw_slot_machines_sounds`, `DLC_SM_Generic_Mission_Sounds`, `DLC_Biker_Cracked_Sounds`, `dlc_vw_body_disposal_sounds`, `dlc_vw_heisters_sounds`, `HACKING_KEYPAD_SCENE`, `collect_chips_handed`, `dlc_vw_tracking_chips_sounds`, `container_attach`, `Air_Drop_Parachute`, `Parachute_Land`, `DLC_Exec_Air_Drop_Sounds`, `Safe_Door_Open`, `Criminal_Damage_Low_Value`, `Criminal_Damage_Kill_Player`, `GTAO_FM_Events_Blade_Scene`, `Criminal_Damage_High_Value`, `container_detach`, `car_crushed`, `Safe_Handle_Spin`, `Garage_Door_Open_Loop`, `GTAO_Script_Doors_Sounds`, `sports_bag`, `dlc_xm_pickup_sweetener_sounds`, `Air_Drop_Package`, `Klaxon_01`, `ALARMS_SOUNDSET`, `laptop_download`, `boot_pop`, `distant_gunfire`, `dlc_vw_missing_delivery_sounds`, `DLC_BTL_Break_In_Sounds`, `MP_AWARD`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `5s`, `MP_MISSION_COUNTDOWN_SOUNDSET`

**Particle effects** (2) - `scr_sm_hl_flare`, `scr_sm_hl_package_flare`

**Texture dicts** (1) - `MPSafeCracking`

**Text labels** (25) - `CAGTAU`, `23RNV734`, `BUMP`, `DODGE`, `NULL`, `68KWK927`, `4NC0RM4N`, `85ZBO520`, `05SBF291`, `20DWF158`, `03OHO142`, `47OKY642`, `DIAMOND1`, `DIAMOND2`, `43WCE752`, `67AGF834`, `84WMY831`, `09DAM225`, `DRUNK`, `ENTER`, `IDLE`, `EXIT`, `HACK`, `XMFMAUD`, `NUMBER`

**Scenarios** (1) - `WORLD_HUMAN_STAND_MOBILE`

**Decorators** (3) - `MPBitset`, `Not_Allow_As_Saved_Veh`, `GBCVehicle`

**Vehicle mods** (1) - `oppressor2`

**Hashed names** (9) - `A_M_Y_GenStreet_01_White_PVG`, `A_M_Y_GenStreet_02_Black_PVG`, `A_M_O_GenStreet_01_White_PVG`, `A_M_M_Genfat_01_Latino_PVG`, `A_M_Y_Business_01_BLACK_PVG`, `A_M_Y_Business_03_Black_PVG`, `A_F_Y_Business_03_Chinese_PVG`, `A_F_O_GenStreet_01_WHITE_PVG`, `A_M_Y_Business_02_BLACK_PVG`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (379), `PLAYER_PED_ID` (314), `SET_PED_COMPONENT_VARIATION` (260), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (251), `PARTICIPANT_ID` (212), `NET_TO_VEH` (186), `NET_TO_ENT` (167), `GET_ENTITY_COORDS` (129), `NET_TO_OBJ` (128), `PARTICIPANT_ID_TO_INT` (119), `SET_BIT` (105), `GET_SCRIPT_TASK_STATUS` (94), `IS_ENTITY_DEAD` (91), `NET_TO_PED` (91), `DOES_ENTITY_EXIST` (84), `GET_ENTITY_MODEL` (79), `SET_PED_COMBAT_ATTRIBUTES` (79), `IS_ENTITY_IN_ANGLED_AREA` (74), `GET_RANDOM_INT_IN_RANGE` (59), `DOES_BLIP_EXIST` (55), `IS_PED_IN_ANY_VEHICLE` (54), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (45), `CLEAR_BIT` (41), `SET_PED_CONFIG_FLAG` (38), `IS_VEHICLE_DRIVEABLE` (35), `GET_VEHICLE_PED_IS_IN` (34), `GET_PED_INDEX_FROM_ENTITY_INDEX` (33), `SET_ALL_VEHICLE_GENERATORS_ACTIVE_IN_AREA` (29), `SET_ENTITY_INVINCIBLE` (27), `SET_VEHICLE_DOORS_LOCKED_FOR_ALL_PLAYERS` (27)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x12 · `1.5f` x6 · `1.2f` x5 · `0.25f` x4 · `0.1f` x4 · `0.9f` x3 · `0.75f` x3 · `0.01f` x3 · `-2667.846f` x3 · `11.0003f` x3 · `77.99091f` x3 · `1.25f` x3 · `0.7f` x2 · `-2.85f` x2 · `-2.64f` x2 · `-226.0547f` x2 · `4.026411f` x2 · `-226.331f` x2 · `-2641.294f` x2 · `722.629f` x2 · `-924.4095f` x2 · `22.46657f` x2 · `758.4235f` x2 · `-924.0587f` x2

## Other strings

Literals whose consuming native was not classified:

`BIN_SH_FAIL`, `stockade`, `rumpo`, `kuruma`, `stretch`, `ambulance`, `banshee2`, `sanchez2`, `PROVOKE_GENERIC`, `PROVOKE_TRESPASS`, `baller2`, `hexer`, `cavalcade`, `slamvan2`, `GBC_STOVER_T`, `chassis_dummy`, `landstalker`, `tornado2`, `xm_prop_x17_bag_01a`, `SC_START`, `insurgent3`, `riot`, `gburrito`, `mule`, `police3`, `GBC_HLP_TA_RA`, `GBC_HLP_TA_IA`, `GBC_FAIL_HR`, `FIRING_PATTERN_FULL_AUTO`, `GBC_BLIP_ENY`

---

Source: `decompiled_scripts/gb_casino.c`
