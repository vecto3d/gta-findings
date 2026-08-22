# gb_gunrunning.c

MP gang ops script. 13 anim dicts; 74 models; 26 scaleforms; 2 particle effects.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 307,781 |
| Functions | 4,173 (977 unique, 3,196 shared) |
| Unique lines | 59,304 (19.3% of file) |

## Assets

**Animation dictionaries** (13) - `MOVE_M@FEMME@`, `MOVE_F@FEMME@`, `MOVE_M@GANGSTER@NG`, `MOVE_F@GANGSTER@NG`, `MOVE_M@POSH@`, `MOVE_F@POSH@`, `MOVE_M@TOUGH_GUY@`, `MOVE_F@TOUGH_GUY@`, `ANIM@MOVE_M@GROOVING@`, `ANIM@MOVE_F@GROOVING@`, `P_cargo_chute_S`, `ANIM_GROUP_MOVE_BALLISTIC`, `MOVE_STRAFE_BALLISTIC`

**Animations** (3) - `P_cargo_chute_S`, `P_cargo_chute_S_crumple`, `P_cargo_chute_S_deploy`

**Models and props** (74) - `g_m_y_korlieut_01`, `g_m_m_chigoon_02`, `prop_box_wood04a`, `a_m_o_acult_02`, `s_m_y_marine_03`, `s_m_m_chemsec_01`, `prop_generator_03b`, `gr_prop_gr_cratespile_01a`, `prop_air_cargo_04a`, `prop_conc_blocks01a`, `prop_woodpile_01c`, `prop_barier_conc_05c`, `prop_armour_pickup`, `prop_box_wood02a_pu`, `hei_prop_heist_apecrate`, `SET_DATA_SLOT`, `s_m_m_fiboffice_01`, `ex_prop_adv_case_sm_03`, `g_m_y_lost_01`, `hei_prop_hei_securitypanel`, `prop_gascyl_04a`, `prop_skid_tent_01`, `s_m_m_scientist_01`, `prop_cratepile_07a`, `prop_boxpile_07a`, `prop_barrier_work04a`, `gr_prop_gr_hobo_stove_01`, `prop_mb_crate_01b`, `ex_prop_adv_case_sm`, `g_m_y_pologoon_01`, `s_m_y_blackops_02`, `ex_prop_exec_crashedp`, `prop_box_wood02a_mws`, `gr_prop_gr_rsply_crate01a`, `gr_prop_gr_rsply_crate03a`, `gr_prop_gr_rsply_crate02a`, `s_f_y_cop_01`, `s_m_m_fibsec_01`, `prop_const_fence03a_cr`, `prop_portacabin01`, `prop_worklight_03b`, `prop_sec_gate_01d`, `hei_prop_carrier_crate_01b`, `hei_prop_heist_transponder`, `gr_prop_gr_rsply_crate04a`, `prop_box_ammo03a_set`, `ex_prop_adv_case`, `v_ilev_ss_door01`, `v_31_newtun5`, `v_31_newtun4b`, `v_31_newtun4`, `v_recycle`, `v_lab`, `prop_ld_case_01`, `prop_drug_package`, `s_m_y_blackops_01`, `g_m_m_armgoon_01`, `s_m_y_swat_01`, `s_m_y_cop_01`, `prop_rub_cont_01b` ...

**Audio banks** (1) - `SCRIPT/ALARM_KLAXON_06`

**Sounds** (39) - `HACKING_MOVE_CURSOR`, `HACKING_CLICK_BAD`, `HACKING_FAILURE`, `HACKING_COUNTDOWN_IP_FIND`, `HACKING_COUNTDOWN_CRACK_PASS`, `DLC_GR_Steal_Railguns_Sounds`, `5s`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `HACKING_CLICK_GOOD`, `DLC_GR_Steal_Miniguns_Clothing_Boost_Scene`, `DLC_GR_Ambushed_Sounds`, `DLC_GR_FTL_Sounds`, `ALARMS_SOUNDSET`, `DLC_GR_Flashlight_Amb_Boost_Scene`, `HACKING_CLICK`, `Hack_Success`, `HACKING_SUCCESS`, `unlocked_bleep`, `HACKING_DOOR_UNLOCK_SOUNDS`, `Parachute_Land`, `DLC_Exec_Air_Drop_Sounds`, `Signal_Off`, `Signal_On`, `Connection_Established`, `Connection_Lost`, `02`, `Armour_On`, `DLC_GR_Steal_Miniguns_Sounds`, `Pickup_Standard`, `GTAO_Biker_Modes_Soundset`, `Crates_Blipped`, `GTAO_Magnate_Boss_Modes_Soundset`, `Klaxon_06`, `Bell_02`, `04`, `05`, `03`, `07`, `01`

**Speech contexts** (1) - `S_M_Y_Cop_01_WHITE_FULL_01`

**Scaleform movies** (26) - `SET_COLUMN_SPEED`, `SET_INPUT_EVENT`, `SET_LIVES`, `SET_INPUT_EVENT_SELECT`, `CLOSE_APP`, `SET_SPEED`, `OPEN_APP`, `SET_DATA_SLOT`, `SET_IP_OUTCOME`, `SET_ROULETTE_OUTCOME`, `SET_COUNTDOWN`, `SET_INPUT_EVENT_BACK`, `RUN_PROGRAM`, `SET_ROULETTE_WORD`, `LOSTIP`, `LOSEBRUTE`, `SET_CURSOR`, `MOVE_CURSOR`, `ADD_PROGRAM`, `EXIT`, `WINIP`, `RESET_ROULETTE`, `STOP_ROULETTE`, `WINBRUTE`, `SHOW_MAP`, `OPEN_DOWNLOAD`

**Particle effects** (2) - `scr_gr_def_flare`, `scr_gr_def_package_flare`

**Text labels** (17) - `HACKOBJ5`, `TRYDL`, `ACCESSD`, `HACKOBJ2`, `HACKOBJ3`, `TRYBRUTE`, `TRYHACK`, `HACKOBJ7`, `HACKOBJ1`, `AGENT14`, `GNRCAUD`, `HACK`, `A14`, `29KXR232`, `06DET110`, `NULL`, `OFF`

**Decorators** (2) - `MPBitset`, `Not_Allow_As_Saved_Veh`

**Timecycle modifiers** (1) - `scanline_cam`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (355), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (177), `NET_TO_VEH` (162), `PLAYER_PED_ID` (161), `PARTICIPANT_ID` (122), `NET_TO_ENT` (108), `TO_FLOAT` (106), `SET_BIT` (93), `IS_ENTITY_IN_ANGLED_AREA` (90), `NET_TO_PED` (89), `IS_ENTITY_DEAD` (85), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (84), `GET_ENTITY_COORDS` (76), `NET_TO_OBJ` (75), `IS_CONTROL_JUST_PRESSED` (74), `SET_PED_COMBAT_ATTRIBUTES` (66), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (63), `IS_NETWORK_ID_OWNED_BY_PARTICIPANT` (55), `GET_ENTITY_MODEL` (55), `CALL_SCALEFORM_MOVIE_METHOD_WITH_NUMBER` (54), `PLAY_SOUND_FRONTEND` (52), `DOES_BLIP_EXIST` (52), `DOES_ENTITY_EXIST` (51), `GET_SCRIPT_TASK_STATUS` (46), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (44), `PARTICIPANT_ID_TO_INT` (38), `GET_GAME_TIMER` (37), `BEGIN_SCALEFORM_MOVIE_METHOD` (36), `IS_PED_IN_ANY_VEHICLE` (35), `GET_RANDOM_INT_IN_RANGE` (34)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x10 · `0.2f` x4 · `1.5f` x3 · `1.8f` x2 · `0.8f` x2 · `-78.85024f` x2 · `-2366.086f` x2 · `-252.7938f` x2 · `-2366.265f` x2 · `661.7083f` x2 · `146.3549f` x2 · `74.7868f` x2 · `722.2554f` x2 · `112.2816f` x2 · `129.9532f` x2 · `580.7896f` x2 · `-1631.694f` x2 · `25.16575f` x2 · `533.9995f` x2 · `-1588.752f` x2 · `78.28825f` x2 · `-806.3783f` x2 · `-2823.253f` x2 · `11.95457f` x2

## Other strings

Literals whose consuming native was not classified:

`ratloader`, `buzzard`, `insurgent`, `daemon`, `huntley`, `slamvan2`, `barracks`, `insurgent3`, `insurgent2`, `crusader`, `mesa3`, `rhino`, `enduro`, `speedo`, `kuruma`, `fbi2`, `dune3`, `marshall`, `dubsta2`, `cargobob`, `ruiner2`, `dloader`, `burrito`, `youga2`, `ratbike`, `fugitive`, `frogger`, `mule3`, `contender`, `flatbed`

---

Source: `decompiled_scripts/gb_gunrunning.c`
