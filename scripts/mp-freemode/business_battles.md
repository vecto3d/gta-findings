# business_battles.c

MP freemode script. 5 anim dicts; 98 models; 25 scaleforms; 2 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 288,763 |
| Functions | 4,417 (1,092 unique, 3,325 shared) |
| Unique lines | 56,193 (19.5% of file) |

## Assets

**Animation dictionaries** (5) - `random@street_race`, `mini@safe_cracking`, `P_cargo_chute_S`, `anim@apt_trans@hinge_r`, `anim@GangOps@Morgue@Office@Laptop@`

**Animations** (5) - `P_cargo_chute_S`, `P_cargo_chute_S_crumple`, `mini@safe_cracking`, `DOOR_OPEN_SUCCEED_STAND`, `P_cargo_chute_S_deploy`

**Models and props** (98) - `s_m_y_blackops_02`, `g_m_y_strpunk_02`, `s_m_m_highsec_01`, `g_m_importexport_01`, `g_m_y_lost_01`, `g_m_y_pologoon_01`, `a_m_y_busicas_01`, `s_m_m_armoured_01`, `g_m_m_chigoon_02`, `prop_box_wood04a`, `prop_mb_sandblock_04`, `a_f_y_tourist_01`, `g_m_y_korean_01`, `prop_worklight_03b`, `g_m_y_korean_02`, `a_f_y_business_04`, `prop_worklight_04d`, `s_m_y_sheriff_01`, `gr_prop_gr_target_02b`, `sm_prop_smug_cont_01a`, `g_m_y_armgoon_02`, `prop_air_cargo_04a`, `prop_contr_03b_ld`, `prop_laptop_01a`, `prop_conc_sacks_02a`, `prop_box_wood03a`, `hei_prop_hei_securitypanel`, `s_m_y_cop_01`, `a_m_y_business_03`, `prop_sec_gate_01d`, `prop_boxpile_04a`, `prop_mb_hesco_06`, `prop_sec_gate_01c`, `a_f_y_bevhills_03`, `prop_mb_cargo_04b`, `prop_watercrate_01`, `prop_bin_13a`, `prop_skid_tent_01`, `gr_prop_gr_hobo_stove_01`, `prop_ld_keypad_01b`, `g_m_y_mexgoon_02`, `g_m_y_ballaorig_01`, `s_m_y_xmech_01`, `a_m_y_yoga_01`, `a_m_y_runner_02`, `s_f_y_hooker_02`, `a_f_y_yoga_01`, `prop_storagetank_02b`, `prop_barier_conc_01a`, `prop_container_ld_pu`, `imp_prop_groupbarrel_03`, `prop_champset`, `prop_elecbox_17_cr`, `prop_dumpster_02a`, `prop_box_wood02a_pu`, `prop_armour_pickup`, `prop_barrel_exp_01a`, `gr_prop_gr_cratespile_01a`, `hei_prop_heist_transponder`, `v_ilev_shrf2door` ...

**Audio banks** (3) - `SAFE_CRACK`, `DLC_EXEC1/SELL_AIR_DROP`, `SCRIPT/ALARM_BELL_02`

**Sounds** (44) - `HACKING_MOVE_CURSOR`, `HACKING_CLICK_BAD`, `DLC_SM_Generic_Mission_Sounds`, `HACKING_FAILURE`, `GTAO_FM_Events_Soundset`, `DLC_BTL_Break_In_Sounds`, `HACKING_COUNTDOWN_IP_FIND`, `HACKING_COUNTDOWN_CRACK_PASS`, `Target_Counter_Tick`, `DLC_Biker_Cracked_Sounds`, `HACKING_KEYPAD_SCENE`, `HACKING_CLICK_GOOD`, `Criminal_Damage_Low_Value`, `Criminal_Damage_Kill_Player`, `GTAO_FM_Events_Blade_Scene`, `Criminal_Damage_High_Value`, `Safe_Handle_Spin`, `Safe_Door_Open`, `sports_bag`, `dlc_xm_pickup_sweetener_sounds`, `Air_Drop_Package`, `Flyover`, `DLC_Exec_Buy_Air_Drop_Sounds`, `download_start`, `download_complete`, `Bell_02`, `ALARMS_SOUNDSET`, `MP_AWARD`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `Garage_Door_Unlocked`, `DLC_BTL_Showroom_Sounds`, `HACKING_CLICK`, `Hack_Success`, `DLC_GR_Steal_Railguns_Sounds`, `HACKING_SUCCESS`, `unlocked_bleep`, `HACKING_DOOR_UNLOCK_SOUNDS`, `5s`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `Garage_Door_Open_Loop`, `GTAO_Script_Doors_Sounds`, `Air_Drop_Parachute`, `Parachute_Land`, `DLC_Exec_Air_Drop_Sounds`

**Scaleform movies** (25) - `SET_COLUMN_SPEED`, `SET_INPUT_EVENT`, `SET_LIVES`, `SET_INPUT_EVENT_SELECT`, `CLOSE_APP`, `SET_SPEED`, `OPEN_APP`, `SET_IP_OUTCOME`, `SET_ROULETTE_OUTCOME`, `SET_COUNTDOWN`, `SET_INPUT_EVENT_BACK`, `RUN_PROGRAM`, `SET_ROULETTE_WORD`, `LOSTIP`, `LOSEBRUTE`, `SET_CURSOR`, `MOVE_CURSOR`, `ADD_PROGRAM`, `EXIT`, `WINIP`, `RESET_ROULETTE`, `STOP_ROULETTE`, `WINBRUTE`, `SHOW_MAP`, `OPEN_DOWNLOAD`

**Particle effects** (2) - `scr_sm_hl_flare`, `scr_sm_hl_package_flare`

**Texture dicts** (1) - `MPSafeCracking`

**Text labels** (34) - `HACKOBJ5`, `TRYDL`, `ACCESSD`, `HACKOBJ2`, `HACKOBJ3`, `TRYBRUTE`, `TRYHACK`, `HACKOBJ7`, `XMFMAUD`, `HACKOBJ1`, `81UKN529`, `NULL`, `ENTER`, `IDLE`, `EXIT`, `HACK`, `LESTER`, `85VVX241`, `05SBF291`, `75GTR201`, `21MAY016`, `27GLZ820`, `20DWF158`, `25EAF559`, `40XHW363`, `62UYW893`, `81TTR412`, `41CMF473`, `31WGC903`, `01CEV285`, `RA1NE`, `20ROF370`, `07EMN393`, `C607287R`

**Scenarios** (1) - `WORLD_HUMAN_STAND_MOBILE`

**Decorators** (3) - `MPBitset`, `Not_Allow_As_Saved_Veh`, `BBCarrier`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (308), `SET_BIT` (219), `PLAYER_PED_ID` (218), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (168), `NET_TO_VEH` (149), `NET_TO_ENT` (129), `DOES_SHOP_PED_APPAREL_HAVE_RESTRICTION_TAG` (127), `PARTICIPANT_ID` (122), `NET_TO_OBJ` (103), `PARTICIPANT_ID_TO_INT` (96), `IS_ENTITY_IN_ANGLED_AREA` (80), `GET_ENTITY_MODEL` (77), `IS_CONTROL_JUST_PRESSED` (76), `GET_ENTITY_COORDS` (75), `SET_PED_COMPONENT_VARIATION` (75), `GET_SCRIPT_TASK_STATUS` (68), `IS_ENTITY_DEAD` (66), `TO_FLOAT` (66), `DOES_ENTITY_EXIST` (60), `CALL_SCALEFORM_MOVIE_METHOD_WITH_NUMBER` (54), `PLAY_SOUND_FRONTEND` (48), `CLEAR_BIT` (46), `GET_RANDOM_INT_IN_RANGE` (45), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (42), `GET_GAME_TIMER` (37), `DOES_BLIP_EXIST` (36), `SET_VEHICLE_DOOR_OPEN` (36), `NET_TO_PED` (34), `IS_PED_IN_ANY_VEHICLE` (33), `GET_VEHICLE_PED_IS_IN` (33)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x7 · `1.25f` x5 · `0.3f` x4 · `0.9f` x3 · `3.5f` x3 · `24.68959f` x3 · `46.10632f` x2 · `0.75f` x2 · `1.5f` x2 · `1304.161f` x2 · `3228.053f` x2 · `35.48594f` x2 · `1294.995f` x2 · `3259.828f` x2 · `49.60658f` x2 · `2608.468f` x2 · `4501.082f` x2 · `34.55606f` x2 · `2633.972f` x2 · `4475.67f` x2 · `46.00249f` x2 · `1556.494f` x2 · `1588.758f` x2 · `103.9459f` x2

## Other strings

Literals whose consuming native was not classified:

`banshee2`, `sultanrs`, `mesa3`, `elegy`, `slamvan3`, `faction3`, `mp_g_m_pros_01`, `insurgent3`, `FMBB_STOVER_T`, `cognoscenti`, `kuruma`, `hc_gunman`, `dubsta`, `xm_prop_x17_trail_02a`, `insurgent2`, `ambulance`, `halftrack`, `technical3`, `barrage`, `stockade`, `hexer`, `SC_START`, `fugitive`, `issi3`, `dune5`, `FIRING_PATTERN_FULL_AUTO`, `_car_a_gawker_male_b`, `ruiner2`, `huntley`, `xm_prop_x17_trail_01a`

---

Source: `decompiled_scripts/business_battles.c`
