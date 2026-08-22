# fm_bj_race_controler.c

Races script. 30 anim dicts; 200 models; 23 scaleforms; 29 particle effects.

| | |
|---|---|
| Category | Races |
| Total lines | 717,180 |
| Functions | 12,800 (1,528 unique, 11,272 shared) |
| Unique lines | 90,068 (12.6% of file) |

## Assets

**Animation dictionaries** (30) - `MP_BASEJUMP`, `SKYDIVE@base`, `SKYDIVE@FREEFALL`, `SKYDIVE@PARACHUTE@CHUTE`, `SKYDIVE@PARACHUTE@`, `mp_parachute_outro@male@win`, `mp_parachute_outro@male@middle`, `mp_parachute_outro@male@lose`, `mp_parachute_outro@female@win`, `mp_parachute_outro@female@middle`, `mp_parachute_outro@female@lose`, `MP_INTRO_SEQ@MCS_7_RACE_TAUNT`, `anim@veh@skydive@parachute@chute`, `skydive@freefall`, `amb@world_human_cheering@male_e`, `anim@scripted@races@ig1_street_race@female@`, `Move_m@_idles@shake_off`, `Move_m@generic_idles@std`, `Move_f@generic_idles@std`, `anim@mp_player_intincarslow_clapstd@rps@`, `amb@world_human_cheering@female_c`, `amb@world_human_cheering@female_d`, `amb@world_human_cheering@male_a`, `amb@world_human_cheering@male_d`, `amb@world_human_cop_idles@male@idle_a`, `amb@world_human_window_shop@male@idle_a`, `amb@world_human_stand_impatient@male@no_sign@idle_a`, `random@street_race`, `stt_mp_stunt_tubes`, `stt_mp_stunt_course`

**Animations** (8) - `MP_BASEJUMP`, `base_jump_spot`, `exit`, `MP_INTRO_SEQ@MCS_7_RACE_TAUNT`, `intro`, `loop`, `MCS_7_TAUNT_MALE`, `MCS_7_TAUNT_FEMALE`

**Models and props** (200) - `v_res_d_dildo_b`, `ba_prop_battle_tube_fn_01`, `ba_prop_battle_tube_fn_02`, `ba_prop_battle_tube_fn_03`, `ba_prop_battle_tube_fn_04`, `ba_prop_battle_tube_fn_05`, `s_m_m_pilot_02`, `prop_cs_dildo_01`, `prop_barrier_work06a`, `prop_mb_cargo_03a`, `prop_mb_cargo_04a`, `prop_air_cargo_04a`, `prop_mb_cargo_02a`, `imp_prop_impexp_boxpile_01`, `prop_mb_crate_01a`, `gr_prop_gr_crates_pistols_01a`, `gr_prop_gr_crates_rifles_01a`, `gr_prop_gr_crates_rifles_02a`, `gr_prop_gr_crates_rifles_03a`, `gr_prop_gr_crates_rifles_04a`, `gr_prop_gr_crates_sam_01a`, `gr_prop_gr_crates_weapon_mix_01a`, `gr_prop_gr_gunsmithsupl_01a`, `gr_prop_gr_gunsmithsupl_02a`, `gr_prop_gr_gunsmithsupl_03a`, `gr_prop_gr_rsply_crate01a`, `gr_prop_gr_rsply_crate02a`, `gr_prop_gr_rsply_crate03a`, `prop_dumpster_02a`, `prop_jetski_ramp_01`, `prop_container_ld_pu`, `gr_prop_gr_target_02b`, `gr_prop_gr_target_02a`, `hei_prop_hei_cash_trolly_03`, `gr_prop_gr_bench_02b`, `sf_prop_sf_swift2_01a`, `prop_flare_01`, `ch_prop_ch_service_trolley_01a`, `imp_prop_ship_01a`, `gr_prop_damship_01a`, `Set_Crowd_A`, `Set_Crowd_B`, `Set_Crowd_C`, `Set_Crowd_D`, `Set_Team_Band_A`, `Set_Team_Band_B`, `Set_Team_Band_C`, `Set_Team_Band_D`, `prop_bowling_pin`, `prop_const_fence02b`, `prop_offroad_bale03`, `prop_offroad_bale02`, `prop_offroad_bale01`, `prop_offroad_tyres02`, `prop_barier_conc_02a`, `prop_barier_conc_05c`, `prop_barier_conc_05a`, `prop_barier_conc_05b`, `prop_barier_conc_01a`, `prop_barrier_work05` ...

**Audio banks** (14) - `HUD_321_GO`, `MP_RACES_SLIPSTREAM`, `DLC_STUNT/STUNT_RACE_01`, `DLC_STUNT/STUNT_RACE_02`, `DLC_24-2/DLC_24-2_LUNAR_RACE_SFX`, `DLC_STUNT/STUNT_RACE_03`, `DLC_AIRRACES/AIR_RACE_01`, `DLC_AIRRACES/AIR_RACE_02`, `DLC_HEIST3/Circuit_Racing`, `DLC_MPSUM2/Island_Races`, `DLC_23_2/DLC_23_2_Drag_Race`, `DLC_23_2/DLC_23_2_Drift_Race`, `DLC_MP2023_1/DLC_MP2023_1_HW`, `DLC_AWXM2018/Arena_Traps`

**Sounds** (118) - `DLC_23_2_Drift_Sounds`, `DLC_23_2_Drag_Race_Sounds`, `HUD_AWARDS`, `MP_LEADERBOARD_SCENE`, `MP_CELEB_SCREEN_ARENA_SCENE`, `OTHER_TEXT`, `MP_CELEB_SCREEN_SCENE`, `HUD_MINI_GAME_SOUNDSET`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `DLC_Stunt_Race_Frontend_Sounds`, `Checkpoint_Lap`, `Checkpoint`, `DLC_sum20_Open_Wheel_Racing_Sounds`, `Car_Club_Races_Pursuit_Series_Sounds`, `Car_Club_Races_Street_Race_Sounds`, `Island_Race_Soundset`, `321`, `Countdown_2_1`, `DLC_Air_Race_Sounds_Player`, `Checkpoint_Finish`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `RACES_SLIPSTREAM_SCENE`, `DLC_AR_Beast_Soundset`, `MP_RACE_GENERAL_SCENE`, `Countdown_3`, `Countdown_Go`, `DLC_23_2_Drag_Race_Mixscenes_General_Scene`, `DLC_AW_Frontend_Sounds`, `RACES_RADIO_MUTE_scene`, `DLC_23_2_Drift_Race_Mixscenes_General_Scene`, `dlc_aw_arena_pit_vehicle_repairing_scene`, `Countdown_321`, `3_2_1`, `Score_Mulitply_Amount`, `DLC_23_2_Drag_Race_Mixscenes_Perfect_Shift_Scene`, `DLC_23_2_Drag_Race_Mixscenes_Nitrous_Boost_Scene`, `MP_JOB_CHANGE_RADIO_MUTE`, `health_lost`, `Hit`, `RESPAWN_ONLINE_SOUNDSET`, `INFO`, `DLC_Biker_SL_Sounds`, `Go`, `Score_Tick_Loop`, `MP_POSITIONED_RADIO_MUTE_SCENE`, `Vehicle_Warp`, `Beast_Sprint_Loop`, `Intensity`, `Vehicle_Transform`, `DLC_23_2_Drag_Race_Mixscenes_Intro_mixscene`, `DLC_AW_Arena_Lobby_Veh_Select_To_VIP_Transition_Scene`, `DLC_AW_Arena_Lobby_Veh_Select_To_Arena_Transition_Scene`, `BACK`, `Checkpoint_Final`, `NET_RACE_START_EVENT_MASTER`, `DLC_23_2_Drag_Race_Mixscenes_Intro_Mixscene`, `WIN`, `RACE_PLACED`, `Count_Start` ...

**Scaleform movies** (23) - `STRING`, `ADD_WORLD_RECORD_TO_WALL`, `ADD_TIME_TO_WALL`, `ADD_MISSION_RESULT_TO_WALL`, `ADD_SCORE_TO_WALL`, `DRAG_RACE`, `SET_MESSAGE`, `SET_SCREEN_POSITION`, `SET_PART_TO_DESTROYED`, `SET_WHEEL_DAMAGE`, `SET_DIRECTION`, `NUMBER`, `SET_COUNTDOWN_LIGHTS`, `SET_GEAR`, `SET_METER_VALUE`, `SET_OUTER_GOAL`, `SET_IS_DRIFT_RACE`, `OPEN_WHEEL_HEALTH_INDICATOR`, `SET_SPEED`, `SET_SPEED_UNITS`, `SET_INNER_GOAL`, `FLASH_OUTER_GOAL`, `FLASH_INNER_GOAL`

**Particle effects** (29) - `scr_sv_drift`, `scr_sv_drag`, `scr_sm`, `scr_as_trans`, `scr_as_target`, `scr_as_trans_smoke`, `scr_sv_drag_burnout`, `buildup`, `scr_sum_ow`, `scr_lowrider`, `scr_indep_fireworks`, `scr_xm_submarine`, `scr_dst_inflatable`, `scr_hr_lny_races`, `wheel_fric_hard`, `scr_sv_drag_wheel_fric_smoke`, `wheel_spin_snow`, `wheel_fric_grass`, `scr_sv_drag_wheel_fric_sand`, `wheel_fric_sand`, `veh_xs_vehicle_mods`, `scr_sr_adversary`, `ent_dst_gen_cardboard`, `scr_sv_drift_cc_trigger`, `scr_sv_drift_cc_persist`, `ent_dst_polystyrene`, `scr_sr_dst_cardboard`, `scr_powerplay`, `scr_sum_ow_race_repair_smoke`

**Text labels** (112) - `FMMC_PLYLOAD`, `OFF`, `SUMMARY`, `SUMMARY2`, `WINNER`, `ARM1AUD`, `44DCT175`, `44ABV623`, `08MGJ922`, `LAMAR`, `RACES`, `FMMC`, `BASEOPPOINT`, `NULL`, `FVTEE`, `321GO`, `47BQT444`, `03QPK213`, `12TCU014`, `49EAJ692`, `00EVK569`, `00NFP794`, `49QQX185`, `23OBR306`, `69VJG707`, `26EIU049`, `46JCA498`, `24IXX594`, `43OMR762`, `65GRZ071`, `06NZQ185`, `68KWK927`, `15HBW365`, `86CVG072`, `84TFX949`, `83OSX036`, `87LWG803`, `ANG3L1S`, `80WEG614`, `TAO1`, `66SBX027`, `27CLR579`, `48XTJ224`, `23IJE671`, `08ICY997`, `20WUI734`, `21VJM767`, `45IZW098`, `86VME156`, `85JFW893`, `87BYW202`, `41KKV206`, `22SCY913`, `ANCESTOR`, `04DZM900`, `65LNN730`, `88WFR722`, `63CMS702`, `23GVN817`, `86ACK549` ...

**Decorators** (2) - `MC_EntityID`, `Not_Allow_As_Saved_Veh`

**Waypoint recordings** (1) - `multirace0_route3`

**Timecycle modifiers** (7) - `Lunar_NewYear_Spectacle`, `Lunar_NewYear_LapOfHonor`, `Lunar_NewYear_TheBigBash`, `DragRaceGearPerf`, `DragRaceGearGood`, `DragRaceGearBad`, `DLC_mp2023_02_Race_AO`

**Interiors and entity sets** (4) - `xs_x18_int_01`, `entity_set_test_lights`, `entity_set_time_trial`, `entity_set_meet_lights`

**Vehicle mods** (14) - `mamba`, `stromberg`, `thruster`, `bodhi2`, `chino`, `voltic`, `buccaneer`, `buccaneer2`, `chino2`, `faction`, `faction2`, `voltic2`, `oppressor`, `vigilante`

**Stats** (1) - `mp0_char_fm_race_record_times`

**Scripts launched** (1) - `TimersHUD`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (814), `PARTICIPANT_ID_TO_INT` (770), `SET_BIT` (666), `PLAYER_ID` (544), `CLEAR_BIT` (275), `DOES_ENTITY_EXIST` (220), `LEADERBOARDS_WRITE_ADD_COLUMN` (209), `IS_PED_IN_ANY_VEHICLE` (183), `GET_VEHICLE_PED_IS_IN` (165), `IS_ENTITY_DEAD` (132), `TO_FLOAT` (131), `PLAY_SOUND_FRONTEND` (126), `DISABLE_CONTROL_ACTION` (124), `INT_TO_PARTICIPANTINDEX` (111), `GET_ENTITY_COORDS` (104), `GET_ENTITY_MODEL` (101), `GET_NETWORK_TIME` (81), `NETWORK_IS_PARTICIPANT_ACTIVE` (79), `ROUND` (77), `NETWORK_HAS_CONTROL_OF_ENTITY` (73), `SET_PED_COMPONENT_VARIATION` (73), `NETWORK_GET_PLAYER_INDEX` (57), `GET_PLAYER_PED` (55), `NET_TO_VEH` (54), `IS_PED_INJURED` (44), `DOES_CAM_EXIST` (41), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (40), `GET_TIME_DIFFERENCE` (40), `GET_DISTANCE_BETWEEN_COORDS` (39), `SET_CAM_FOV` (38)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.3f` x26 · `0.5f` x25 · `1.2f` x12 · `0.6f` x11 · `0.4f` x9 · `0.75f` x9 · `1.32f` x9 · `0.7f` x8 · `0.2f` x7 · `0.85f` x7 · `0.8f` x6 · `7.5f` x6 · `0.66f` x5 · `0.73333f` x5 · `0.1f` x4 · `0.001f` x4 · `38.4708f` x4 · `4.2f` x4 · `2.5f` x3 · `36.2397f` x3 · `1.5f` x3 · `1.6f` x3 · `0.25f` x2 · `0.12f` x2

## Other strings

Literals whose consuming native was not classified:

`DEFAULT_SCRIPTED_CAMERA`, `XPT_GTA_PICK`, `FM_1AU`, `ruiner2`, `CrossLine`, `Mission`, `HAND_SHAKE`, `blazer5`, `SeasonId`, `stromberg`, `ROAD_VIBRATION_SHAKE`, `scr_hr_lny_races`, `rcbandito`, `deluxo`, `submersible`, `submersible2`, `MobileRadioInGame`, `RACE_SPAWNH0`, `BASEJ_HLP_START`, `rallytruck`, `AllowScoreAndRadio`, `stt_prop_stunt_tube_jmp2`, `stt_prop_track_stop_sign`, `mp_m_freemode_01`, `DLC_23_2_Drag_Race_Sounds`, `MP_job_load`, `Laps`, `RACE_RAL5`, `BASEJ_HELP1`

---

Source: `decompiled_scripts/fm_bj_race_controler.c`
