# gb_gangops.c

MP gang ops script. 11 anim dicts; 98 models; 25 scaleforms; 6 particle effects.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 321,763 |
| Functions | 4,666 (1,125 unique, 3,541 shared) |
| Unique lines | 86,313 (26.8% of file) |

## Assets

**Animation dictionaries** (11) - `anim@mp_mission@dr_objective`, `P_cargo_chute_S`, `anim@apt_trans@hinge_l_action`, `mini@safe_cracking`, `anim@apt_trans@hinge_l_stealth`, `anim@apt_trans@garage`, `anim@apt_trans@hinge_r`, `amb@world_human_sunbathe@female@back@base`, `anim@AMB@WORLD_HUMAN_STANDING_MOBILE_BRF_CASE@MALE@STANDING@CALL@ENTER`, `anim@AMB@WORLD_HUMAN_STANDING_MOBILE_BRF_CASE@MALE@STANDING@CALL@BASE`, `anim@AMB@WORLD_HUMAN_STANDING_MOBILE_BRF_CASE@MALE@STANDING@CALL@EXIT`

**Animations** (5) - `P_cargo_chute_S`, `P_cargo_chute_S_crumple`, `mini@safe_cracking`, `DOOR_OPEN_SUCCEED_STAND`, `P_cargo_chute_S_deploy`

**Models and props** (98) - `a_f_y_business_04`, `s_m_y_cop_01`, `a_m_y_business_02`, `g_m_m_armgoon_01`, `prop_generator_03b`, `s_m_y_swat_01`, `s_m_m_security_01`, `prop_container_ld_pu`, `s_m_m_paramedic_01`, `g_m_m_armboss_01`, `sm_prop_smug_cont_01a`, `a_m_y_hippy_01`, `a_m_m_hillbilly_02`, `a_m_y_motox_01`, `s_m_y_construct_02`, `a_f_y_hippie_01`, `s_m_m_fibsec_01`, `a_m_m_eastsa_02`, `g_m_y_ballaorig_01`, `a_m_y_hipster_01`, `a_m_y_beach_03`, `s_m_m_doctor_01`, `s_m_m_highsec_01`, `s_m_m_movprem_01`, `a_m_y_bevhills_02`, `g_m_y_ballasout_01`, `prop_contr_03b_ld`, `a_f_y_hipster_02`, `a_f_y_bevhills_02`, `a_m_m_hillbilly_01`, `a_m_y_acult_02`, `a_f_y_beach_01`, `s_m_m_bouncer_01`, `s_m_y_sheriff_01`, `s_f_y_sheriff_01`, `prop_wall_light_06a`, `s_m_y_armymech_01`, `s_f_y_movprem_01`, `a_m_m_eastsa_01`, `s_m_m_marine_02`, `prop_container_03mb`, `prop_mb_crate_01b`, `prop_skid_tent_01`, `gr_prop_gr_hobo_stove_01`, `hei_prop_hei_securitypanel`, `g_m_importexport_01`, `s_m_y_blackops_02`, `s_m_m_pilot_02`, `a_m_m_paparazzi_01`, `s_m_y_pilot_01`, `s_m_m_marine_01`, `prop_sec_gate_01d`, `prop_boombox_01`, `prop_radio_01`, `prop_food_van_01`, `prop_box_wood02a_pu`, `prop_armour_pickup`, `prop_barrel_exp_01a`, `gr_prop_gr_cratespile_01a`, `hei_prop_heist_transponder` ...

**Audio banks** (3) - `SCRIPT\LIFTS`, `SCRIPT/ALARM_KLAXON_06`, `SAFE_CRACK`

**Sounds** (45) - `HACKING_MOVE_CURSOR`, `HACKING_CLICK_BAD`, `DLC_SM_Generic_Mission_Sounds`, `HACKING_FAILURE`, `dlc_xm_heists_fm_uc_sounds`, `HACKING_COUNTDOWN_IP_FIND`, `HACKING_COUNTDOWN_CRACK_PASS`, `dlc_xm_pickup_sweetener_sounds`, `DLC_XM17_Silo_Flight_Recorder_Sounds`, `DLC_XM17_SILO_Flight_Recorder_Plane_Crashing_Scene`, `DLC_Biker_Cracked_Sounds`, `Target_Counter_Tick`, `HACKING_CLICK_GOOD`, `5s`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `Air_Drop_Parachute`, `Parachute_Land`, `DLC_Exec_Air_Drop_Sounds`, `sports_bag`, `Air_Drop_Package`, `Tone`, `Lift_Normal_Soundset`, `security_scanner_beep_os`, `download_start`, `download_complete`, `Klaxon_06`, `ALARMS_SOUNDSET`, `keys`, `Garage_Door_Open`, `GTAO_Script_Doors_Faded_Screen_Sounds`, `Hold`, `Plane_Damaged_Loop`, `Safe_Handle_Spin`, `Safe_Door_Open`, `MP_AWARD`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `HACKING_CLICK`, `Hack_Success`, `DLC_GR_Steal_Railguns_Sounds`, `HACKING_SUCCESS`, `unlocked_bleep`, `HACKING_DOOR_UNLOCK_SOUNDS`, `Crates_Blipped`, `GTAO_Magnate_Boss_Modes_Soundset`, `Plane_Crash_Oneshot`

**Scaleform movies** (25) - `SET_COLUMN_SPEED`, `SET_INPUT_EVENT`, `SET_LIVES`, `SET_INPUT_EVENT_SELECT`, `CLOSE_APP`, `SET_SPEED`, `OPEN_APP`, `SET_IP_OUTCOME`, `SET_ROULETTE_OUTCOME`, `SET_COUNTDOWN`, `SET_INPUT_EVENT_BACK`, `RUN_PROGRAM`, `SET_ROULETTE_WORD`, `LOSTIP`, `LOSEBRUTE`, `SET_CURSOR`, `MOVE_CURSOR`, `ADD_PROGRAM`, `EXIT`, `WINIP`, `RESET_ROULETTE`, `STOP_ROULETTE`, `WINBRUTE`, `SHOW_MAP`, `OPEN_DOWNLOAD`

**Particle effects** (6) - `scr_xm_para`, `scr_xm_spybomb`, `scr_xm_para_car_smoke`, `scr_sm_hl_flare`, `scr_sm_hl_package_flare`, `scr_xm_spybomb_plane_smoke_trail`

**Texture dicts** (1) - `MPSafeCracking`

**Text labels** (19) - `HACKOBJ5`, `TRYDL`, `ACCESSD`, `HACKOBJ2`, `HACKOBJ3`, `TRYBRUTE`, `TRYHACK`, `HACKOBJ7`, `XMFMAUD`, `HACKOBJ1`, `STRING`, `NULL`, `HACK`, `ENTER`, `BASE`, `EXIT`, `H2AVON`, `LESTER`, `SMGCAUD`

**Scenarios** (1) - `WORLD_HUMAN_STAND_MOBILE`

**Decorators** (6) - `MPBitset`, `Not_Allow_As_Saved_Veh`, `FMDeliverableID`, `ContrabandOwner`, `ContrabandDeliveryType`, `ExportVehicle`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (321), `PLAYER_PED_ID` (267), `IS_ENTITY_IN_ANGLED_AREA` (251), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (210), `NET_TO_VEH` (196), `PARTICIPANT_ID` (174), `NET_TO_ENT` (131), `SET_BIT` (109), `SET_PED_COMBAT_ATTRIBUTES` (109), `GET_ENTITY_COORDS` (106), `NET_TO_OBJ` (105), `SET_PED_COMPONENT_VARIATION` (91), `NET_TO_PED` (81), `IS_CONTROL_JUST_PRESSED` (76), `IS_ENTITY_DEAD` (75), `PARTICIPANT_ID_TO_INT` (74), `GET_SCRIPT_TASK_STATUS` (74), `GET_ENTITY_MODEL` (71), `DOES_ENTITY_EXIST` (67), `TO_FLOAT` (59), `CALL_SCALEFORM_MOVIE_METHOD_WITH_NUMBER` (54), `DOES_BLIP_EXIST` (53), `SET_PED_ANGLED_DEFENSIVE_AREA` (51), `PLAY_SOUND_FRONTEND` (49), `IS_PED_IN_ANY_VEHICLE` (40), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (40), `SET_PED_CONFIG_FLAG` (37), `GET_PLAYER_WANTED_LEVEL` (37), `GET_GAME_TIMER` (37), `CLEAR_BIT` (36)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x11 · `-452.2502f` x7 · `-3050.28f` x7 · `167.2573f` x7 · `0.25f` x4 · `0.2f` x4 · `2.5f` x3 · `0.1f` x3 · `-320.4597f` x3 · `-1500.427f` x3 · `24.73458f` x3 · `-320.1006f` x3 · `-1451.808f` x3 · `-1448.307f` x3 · `-287.4942f` x3 · `40.19381f` x3 · `-1424.903f` x3 · `-266.5358f` x3 · `-540.2228f` x3 · `-1201.282f` x3 · `11.97638f` x3 · `-509.6531f` x3 · `-1215.168f` x3 · `1222.4f` x3

## Other strings

Literals whose consuming native was not classified:

`mp_g_m_pros_01`, `oppressor`, `mp_s_m_armoured_01`, `police3`, `buccaneer2`, `fugitive`, `xm_prop_x17_trail_02a`, `xm_prop_x17_trail_01a`, `tula`, `sheriff`, `seashark`, `bmx`, `ambulance`, `PM_SPAWN_A4`, `FH_LOC_ZANC`, `FH_LOC_MRRWC`, `blazer5`, `flatbed`, `wastelander`, `frogger`, `dilettante2`, `riot`, `FH_LOC_LSIA`, `SC_START`, `surfer`, `mesa3`, `chernobog`, `insurgent2`, `xm_prop_auto_salvage_elegy`, `xm_prop_x17_barge_01`

---

Source: `decompiled_scripts/gb_gangops.c`
