# gb_smuggler.c

MP gang ops script. 1 anim dicts; 66 models; 25 scaleforms; 2 particle effects.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 280,608 |
| Functions | 4,242 (1,060 unique, 3,182 shared) |
| Unique lines | 67,190 (23.9% of file) |

## Assets

**Animation dictionaries** (1) - `P_cargo_chute_S`

**Animations** (3) - `P_cargo_chute_S`, `P_cargo_chute_S_crumple`, `P_cargo_chute_S_deploy`

**Models and props** (66) - `gr_prop_gr_cratespile_01a`, `sm_prop_smug_crate_01a`, `g_m_m_korboss_01`, `s_m_m_prisguard_01`, `s_m_m_highsec_01`, `prop_worklight_03b`, `prop_box_wood04a`, `prop_air_cargo_04a`, `a_m_y_epsilon_01`, `prop_barrel_exp_01c`, `prop_roadcone01a`, `s_m_y_blackops_01`, `prop_cementbags01`, `prop_air_lights_02b`, `prop_shuttering03`, `g_m_y_mexgang_01`, `g_m_m_armgoon_01`, `s_m_y_swat_01`, `sm_prop_smug_heli`, `prop_ind_barge_01_cr`, `prop_woodpile_01c`, `prop_plas_barier_01a`, `prop_skid_tent_01`, `gr_prop_gr_hobo_stove_01`, `hei_prop_hei_securitypanel`, `s_m_y_prisoner_01`, `g_m_m_chigoon_02`, `prop_worklight_04d`, `prop_elecbox_24`, `sm_prop_smug_cont_01a`, `prop_box_wood02a_pu`, `prop_armour_pickup`, `prop_barrel_exp_01a`, `hei_prop_heist_transponder`, `prop_contr_03b_ld`, `sm_prop_smug_crate_s_bones`, `sm_prop_smug_crate_s_antiques`, `sm_prop_smug_crate_s_hazard`, `sm_prop_smug_crate_s_fake`, `sm_prop_smug_crate_s_jewellery`, `sm_prop_smug_crate_s_medical`, `sm_prop_smug_crate_s_narc`, `sm_prop_smug_crate_s_tobacco`, `ex_prop_adv_case_sm`, `g_m_y_korlieut_01`, `s_m_y_xmech_01`, `s_m_y_dealer_01`, `g_m_y_lost_01`, `prop_ld_case_01`, `prop_drug_package`, `prop_elecbox_15_cr`, `prop_elecbox_14`, `bkr_prop_biker_bblock_lrg3`, `prop_elecbox_17_cr`, `sm_prop_smug_jammer`, `prop_box_wood02a`, `prop_generator_03b`, `prop_sec_gate_01d`, `prop_flare_01`, `sm_prop_smug_rsply_crate01a` ...

**Audio banks** (2) - `SCRIPT/ALARM_KLAXON_03`, `ALARM_KLAXON_05`

**Sounds** (42) - `HACKING_MOVE_CURSOR`, `HACKING_CLICK_BAD`, `DLC_SM_Generic_Mission_Sounds`, `HACKING_FAILURE`, `Target_Counter_Tick`, `HACKING_COUNTDOWN_IP_FIND`, `HACKING_COUNTDOWN_CRACK_PASS`, `DLC_SM_Infiltration_Sounds`, `DLC_SM_Precision_Delivery_Sounds`, `HACKING_CLICK_GOOD`, `5s`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `MP_AWARD`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `Air_Drop_Package`, `Klaxon_03`, `ALARMS_SOUNDSET`, `Altitude_Checkpoint`, `Altitude_Beeps`, `crashed_heli_ambience`, `DLC_SM_Blackbox_Sounds`, `alarm_loop`, `DLC_SM_Escort_Sounds`, `hook_attach`, `hook_detach`, `cargo_alarm_loop`, `DLC_SM_Cargo_Plane_Sounds`, `HACKING_CLICK`, `Hack_Success`, `DLC_GR_Steal_Railguns_Sounds`, `HACKING_SUCCESS`, `unlocked_bleep`, `HACKING_DOOR_UNLOCK_SOUNDS`, `container_detach`, `DLC_SM_Heavy_Lifting_Sounds`, `Crates_Blipped`, `GTAO_Magnate_Boss_Modes_Soundset`, `Air_Drop_Parachute`, `Parachute_Land`, `DLC_Exec_Air_Drop_Sounds`, `Altitude_Warning_Loop`, `DLC_SM_Under_The_Radar_Sounds`

**Scaleform movies** (25) - `SET_COLUMN_SPEED`, `SET_INPUT_EVENT`, `SET_LIVES`, `SET_INPUT_EVENT_SELECT`, `CLOSE_APP`, `SET_SPEED`, `OPEN_APP`, `SET_IP_OUTCOME`, `SET_ROULETTE_OUTCOME`, `RUN_PROGRAM`, `SET_ROULETTE_WORD`, `LOSTIP`, `LOSEBRUTE`, `SET_COUNTDOWN`, `SET_INPUT_EVENT_BACK`, `SET_CURSOR`, `WINIP`, `RESET_ROULETTE`, `STOP_ROULETTE`, `SHOW_MAP`, `OPEN_DOWNLOAD`, `ADD_PROGRAM`, `EXIT`, `MOVE_CURSOR`, `WINBRUTE`

**Particle effects** (2) - `scr_sm_hl_flare`, `scr_sm_hl_package_flare`

**Text labels** (13) - `HACKOBJ5`, `TRYDL`, `TRYBRUTE`, `TRYHACK`, `HACKOBJ7`, `ACCESSD`, `HACKOBJ2`, `HACKOBJ3`, `HACKOBJ1`, `SMGCAUD`, `NULL`, `HACK`, `SR2ROAU`

**Decorators** (3) - `MPBitset`, `Not_Allow_As_Saved_Veh`, `FMDeliverableID`

**Vehicle mods** (3) - `volatol`, `avenger`, `tula`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (312), `PLAYER_PED_ID` (288), `NET_TO_VEH` (213), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (202), `PARTICIPANT_ID` (135), `NET_TO_ENT` (113), `SET_BIT` (109), `IS_ENTITY_IN_ANGLED_AREA` (98), `NET_TO_OBJ` (90), `IS_ENTITY_DEAD` (82), `GET_ENTITY_MODEL` (82), `SET_VEHICLE_COLOURS` (80), `IS_CONTROL_JUST_PRESSED` (77), `GET_ENTITY_COORDS` (72), `DOES_ENTITY_EXIST` (68), `TO_FLOAT` (67), `NET_TO_PED` (56), `CALL_SCALEFORM_MOVIE_METHOD_WITH_NUMBER` (54), `GET_SCRIPT_TASK_STATUS` (54), `PARTICIPANT_ID_TO_INT` (52), `PLAY_SOUND_FRONTEND` (49), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (43), `SET_PED_COMBAT_ATTRIBUTES` (42), `SET_VEHICLE_MOD` (41), `DOES_BLIP_EXIST` (40), `GET_GAME_TIMER` (37), `GET_RANDOM_INT_IN_RANGE` (37), `IS_PED_IN_ANY_VEHICLE` (34), `GET_VEHICLE_PED_IS_IN` (34), `GET_PED_INDEX_FROM_ENTITY_INDEX` (32)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x8 · `1.2f` x5 · `0.2f` x4 · `1.5f` x3 · `1726.881f` x3 · `3325.941f` x3 · `39.22349f` x3 · `2137.559f` x3 · `4770.657f` x3 · `39.02285f` x3 · `2.5f` x2 · `1.8f` x2 · `1271.787f` x2 · `-3351.372f` x2 · `0.528373f` x2 · `1273.703f` x2 · `-3227.049f` x2 · `14.9016f` x2 · `1740.011f` x2 · `3280.441f` x2 · `44.5896f` x2 · `2120.968f` x2 · `4807.37f` x2 · `45.19595f` x2

## Other strings

Literals whose consuming native was not classified:

`mp_g_m_pros_01`, `buzzard`, `lazer`, `frogger`, `mule`, `buzzard2`, `tug`, `rogue`, `mogul`, `starling`, `seabreeze`, `cargobob2`, `polmav`, `vehicle_weapon_bomb`, `hunter`, `trash2`, `insurgent2`, `tula`, `skylift`, `speedo`, `nokota`, `molotok`, `howard`, `bombushka`, `pyro`, `havok`, `cargoplane`, `seashark`, `riot`, `brickade`

---

Source: `decompiled_scripts/gb_smuggler.c`
