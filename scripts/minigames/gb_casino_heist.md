# gb_casino_heist.c

Minigames script. 30 anim dicts; 135 models; 5 scaleforms; 9 particle effects.

| | |
|---|---|
| Category | Minigames |
| Total lines | 622,775 |
| Functions | 11,743 (2,415 unique, 9,328 shared) |
| Unique lines | 109,463 (17.6% of file) |

## Assets

**Animation dictionaries** (30) - `anim_heist@hs3f@ig12_change_clothes@`, `anim@GangOps@Facility@Servers@BodySearch@`, `anim@heists@ornate_bank@hostages@ped_a@`, `amb@world_human_vehicle_mechanic@male@base`, `amb@medic@standing@kneel@idle_a`, `P_cargo_chute_S`, `mini@safe_cracking`, `anim@mugging@victim@toss_ped@`, `anim@mugging@mugger@catch_melee@`, `anim@mugging@mugger@catch_1h_gun@`, `anim@mugging@mugger@catch_2h_gun@`, `missheistdockssetup1hardhat@`, `anim@heists@narcotics@trash`, `anim@GangOps@Morgue@Table@`, `anim@heists@keycard@`, `anim_heist@hs3f@ig14_open_car_trunk@male@`, `anim_heist@hs3f@ig14_open_car_trunk@female@`, `anim@gangops@morgue@table@`, `timetable@tracy@sleep@`, `timetable@jimmy@doorknock@`, `amb@world_human_seat_wall@male@hands_by_sides@base`, `missheistdockssetup1ig_13@kick_idle`, `amb@world_human_bum_slumped@male@laying_on_right_side@base`, `move_m@drunk@a`, `anim_heist@prep_mission@drone_flight@`, `anim@apt_trans@garage`, `anim@apt_trans@hinge_l_stealth`, `anim@apt_trans@hinge_l_action`, `anim@apt_trans@hinge_l`, `anim@apt_trans@hinge_r`

**Animations** (7) - `P_cargo_chute_S`, `P_cargo_chute_S_crumple`, `anim@mugging@victim@toss_ped@`, `throw_object_left_pocket_male`, `mini@safe_cracking`, `DOOR_OPEN_SUCCEED_STAND`, `P_cargo_chute_S_deploy`

**Models and props** (135) - `prop_box_guncase_03a`, `ch_prop_ch_security_case_02a`, `ch_prop_vault_drill_01a`, `ch_prop_box_ammo01b`, `ch_prop_adv_case_sm_flash`, `v_ilev_fbisecgate`, `s_m_y_blackops_01`, `g_m_y_lost_01`, `prop_sec_gate_01c`, `prop_skid_tent_01`, `hei_prop_hei_securitypanel`, `prop_ld_keypad_01b`, `gr_prop_gr_hobo_stove_01`, `gr_prop_gr_cratespile_01a`, `g_m_m_chigoon_02`, `v_ilev_genbankdoor2`, `v_ilev_genbankdoor1`, `p_car_keys_01`, `ch_prop_casino_drone_broken01a`, `ch_prop_swipe_card_01a`, `prop_mb_crate_01a`, `prop_box_wood04a`, `g_m_y_ballaorig_01`, `g_f_importexport_01`, `v_studio_lo`, `Set_vault_gold_01`, `Set_vault_gold_02`, `Set_vault_art_01`, `Set_vault_diamonds_01`, `Set_vault_diamonds_02`, `u_m_y_juggernaut_01`, `prop_box_wood02a_pu`, `prop_armour_pickup`, `prop_barrel_exp_01a`, `prop_sec_gate_01d`, `gr_prop_gr_target_02b`, `prop_laptop_01a`, `prop_contr_03b_ld`, `prop_const_fence02a`, `prop_container_ld_pu`, `vw_prop_vw_key_cabinet_01a`, `ch_prop_ch_morgue_01a`, `bkr_prop_weed_bigbag_open_01a`, `prop_cs_duffel_01`, `prop_security_case_01`, `prop_boombox_01`, `prop_ghettoblast_02`, `ch_prop_emp_01b`, `Set_vault_cash_01`, `Set_vault_cash_02`, `Set_vault_art_02`, `g_m_m_armgoon_01`, `hei_prop_hei_timetable`, `prop_amb_phone`, `ch_prop_swipe_card_01b`, `ch_prop_vault_key_card_01a`, `prop_drug_package`, `ch_prop_boring_machine_01b`, `ch_prop_arcade_collect_01a`, `hei_prop_carrier_crate_01a` ...

**Audio banks** (4) - `DLC_CHRISTMAS2017/XM_FARM`, `DLC_HEIST3/CASINO_HEIST_FINALE_GENERAL_01`, `DLC_MPHEIST/HEIST_USE_KEYPAD`, `SAFE_CRACK`

**Sounds** (71) - `dlc_ch_armoured_equipment_bunker_interior_scene`, `DLC_HEIST_BIOLAB_PREP_HACKING_SOUNDS`, `dlc_xm_deluxos_hacking_Hacking_Sounds`, `DLC_HEISTS_ALARM_INITIAL_BOOST_SCENE`, `MP_CCTV_SOUNDSET`, `GTAO_FM_Events_Soundset`, `Clothes_Swap`, `GTAO_Change_Outfit_Sounds`, `DLC_H3_FM_FIB_Raid_Sounds`, `DLC_H3_Tracker_App_Sounds`, `HACKING_KEYPAD_SCENE`, `DLC_SM_Generic_Mission_Sounds`, `DLC_Biker_Cracked_Sounds`, `alarm_loop`, `dlc_xm_farm_sounds`, `dlc_ch_armoured_equipment_sounds`, `Menu_Accept`, `Hack_Stop`, `Hack_Start`, `Hack_Loop`, `percentageComplete`, `Hack_Complete`, `Hack_Success`, `Pin_Movement`, `PinMovementY`, `Pin_Centred`, `Pin_Good`, `Pin_Bad`, `5s`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `Air_Drop_Parachute`, `Parachute_Land`, `DLC_Exec_Air_Drop_Sounds`, `Safe_Handle_Spin`, `Safe_Door_Open`, `Criminal_Damage_Low_Value`, `Criminal_Damage_Kill_Player`, `GTAO_FM_Events_Blade_Scene`, `Criminal_Damage_High_Value`, `bin_bag_bugs`, `dlc_ch_bugstars_sounds`, `DLC_BTL_Break_In_Sounds`, `FAKE_ARRIVE`, `MP_PROPERTIES_ELEVATOR_DOORS`, `Bunker_Hatch`, `GTAO_Script_Doors_Faded_Screen_Sounds`, `sports_bag`, `dlc_xm_pickup_sweetener_sounds`, `Air_Drop_Package`, `Flight_Loop`, `DLC_H3_Prep_Drones_Sounds`, `Alarm_Interior`, `Alarm_Exterior`, `Vent_Fizzing`, `dlc_ch_maintenance_sounds`, `Bunker_Alarm_Interior`, `Bunker_Alarm_Exterior`, `Airhorn_Blast_Long`, `DLC_AW_General_Sounds`, `DLC_HEIST_EMP_IDLE_MASTER` ...

**Scaleform movies** (5) - `SET_CURSOR_VISIBILITY`, `SECURITY_CAM`, `SET_LOCATION`, `SET_DETAILS`, `SET_TIME`

**Particle effects** (9) - `scr_xm_riotvan`, `scr_ch_finale`, `strength`, `scr_xm_riotvan_extinguish`, `scr_ch_cockroach_bag_drop`, `scr_sm_hl_flare`, `scr_sm_hl_package_flare`, `scr_xm_riotvan_fire_front`, `scr_xm_riotvan_fire_back`

**Texture dicts** (5) - `hackingNG`, `DHCompHi`, `DHComp`, `DHMain`, `MPSafeCracking`

**Text labels** (119) - `BASE`, `COP`, `05SBF291`, `20DWF158`, `41DYO333`, `62QCH889`, `25EAF559`, `HS3PRAU`, `CAGTAU`, `31SLR187`, `06AJB815`, `02SAB785`, `93EAB211`, `NULL`, `DRUNK`, `08SCO384`, `OFF`, `HACK`, `08HFL983`, `53RYN511`, `64FZO284`, `34WDL675`, `47RPB540`, `68AVN999`, `45JTQ591`, `87RAP338`, `87RAP339`, `65QRB385`, `09EUQ738`, `05DUR423`, `88NWT136`, `20SKL158`, `44TRO349`, `72KQW551`, `29PRH471`, `13CTZ264`, `54LRJ312`, `28VRO609`, `87EVY108`, `62GJA507`, `HS3FAAU`, `HS3CWAU`, `HS3LEAU`, `HS3CEAU`, `LESTER`, `BUMP`, `DODGE`, `89DGH317`, `21LGX241`, `85JRS672`, `07JXB365`, `68KWK927`, `86CVG072`, `15HBW365`, `28AVY903`, `29FNS081`, `62TPS980`, `02UDE356`, `82XDI722`, `29PRH777` ...

**Scenarios** (1) - `WORLD_HUMAN_STAND_MOBILE`

**Decorators** (3) - `Not_Allow_As_Saved_Veh`, `MPBitset`, `CSHVehicle`

**Relationship groups** (1) - `COP`

**Timecycle modifiers** (2) - `CAMERA_secuirity`, `CAMERA_secuirity_FUZZ`

**Vehicle mods** (1) - `oppressor2`

**Scripts launched** (1) - `appsecurohack`

**Hashed names** (2) - `A_M_M_HillBilly_01_WHITE_PVG`, `A_M_Y_VINEWOOD_02_WHITE_PVG`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (624), `PLAYER_ID` (580), `PLAYER_PED_ID` (545), `PARTICIPANT_ID` (408), `IS_ENTITY_IN_ANGLED_AREA` (285), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (268), `SET_BIT` (210), `NET_TO_ENT` (190), `GET_ENTITY_COORDS` (178), `NET_TO_VEH` (164), `PARTICIPANT_ID_TO_INT` (160), `NET_TO_OBJ` (127), `GET_SCRIPT_TASK_STATUS` (94), `CLEAR_BIT` (91), `IS_ENTITY_DEAD` (89), `GET_PLAYER_WANTED_LEVEL` (89), `DOES_ENTITY_EXIST` (85), `IS_PED_IN_ANY_VEHICLE` (80), `NET_TO_PED` (78), `DOES_BLIP_EXIST` (74), `GET_RANDOM_INT_IN_RANGE` (73), `GET_ENTITY_MODEL` (71), `SET_PED_COMBAT_ATTRIBUTES` (68), `SET_PED_PROP_INDEX` (68), `SET_PED_ANGLED_DEFENSIVE_AREA` (68), `VDIST2` (51), `SET_PED_CONFIG_FLAG` (42), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (37), `CLEAR_HELP` (32), `GET_PED_INDEX_FROM_ENTITY_INDEX` (32)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x38 · `0.4f` x32 · `0.25f` x14 · `1.5f` x13 · `0.75f` x11 · `0.9f` x9 · `2.5f` x9 · `1.2f` x7 · `0.7f` x6 · `0.8f` x6 · `0.3f` x6 · `0.1f` x5 · `1.25f` x5 · `3.5f` x4 · `-0.04f` x4 · `18.5f` x4 · `0.01f` x3 · `-2.2f` x3 · `0.341f` x3 · `28.08061f` x3 · `-2662.873f` x3 · `-84.15887f` x3 · `6499.049f` x3 · `29.67174f` x3

## Other strings

Literals whose consuming native was not classified:

`HS3LE_SO_11`, `fugitive`, `mesa3`, `IDLE_A`, `IDLE_B`, `stockade`, `IDLE_C`, `dinghy2`, `CSH_OT_ENTER_T`, `HS3PR_GN_12A`, `HS3PR_GN_7`, `flatbed`, `CSH_LOC_C`, `buzzard`, `taillight_l`, `taillight_r`, `short_action_01_male`, `manchez`, `stryder`, `defiler`, `lectro`, `HS3PR_DS_3`, `kamacho`, `bison2`, `tropic2`, `burrito`, `insurgent3`, `HS3PR_GN_13`, `base`, `SC_START`

---

Source: `decompiled_scripts/gb_casino_heist.c`
