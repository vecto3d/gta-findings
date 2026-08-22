# fm_race_controler.c

Races script. 30 anim dicts; 200 models; 23 scaleforms; 29 particle effects.

| | |
|---|---|
| Category | Races |
| Total lines | 724,187 |
| Functions | 13,155 (1,689 unique, 11,466 shared) |
| Unique lines | 94,687 (13.1% of file) |

## Assets

**Animation dictionaries** (30) - `MP_BASEJUMP`, `SKYDIVE@base`, `SKYDIVE@FREEFALL`, `SKYDIVE@PARACHUTE@CHUTE`, `SKYDIVE@PARACHUTE@`, `mp_parachute_outro@male@win`, `mp_parachute_outro@male@middle`, `mp_parachute_outro@male@lose`, `mp_parachute_outro@female@win`, `mp_parachute_outro@female@middle`, `mp_parachute_outro@female@lose`, `MP_INTRO_SEQ@MCS_7_RACE_TAUNT`, `anim@veh@skydive@parachute@chute`, `skydive@freefall`, `amb@world_human_cheering@male_e`, `anim@scripted@races@ig1_street_race@female@`, `Move_m@_idles@shake_off`, `Move_m@generic_idles@std`, `Move_f@generic_idles@std`, `anim@mp_player_intincarslow_clapstd@rps@`, `amb@world_human_cheering@female_c`, `amb@world_human_cheering@female_d`, `amb@world_human_cheering@male_a`, `amb@world_human_cheering@male_d`, `amb@world_human_cop_idles@male@idle_a`, `amb@world_human_window_shop@male@idle_a`, `amb@world_human_stand_impatient@male@no_sign@idle_a`, `random@street_race`, `stt_mp_stunt_tubes`, `stt_mp_stunt_course`

**Animations** (8) - `MP_BASEJUMP`, `base_jump_spot`, `exit`, `MP_INTRO_SEQ@MCS_7_RACE_TAUNT`, `intro`, `loop`, `MCS_7_TAUNT_MALE`, `MCS_7_TAUNT_FEMALE`

**Models and props** (200) - `v_res_d_dildo_b`, `prop_container_ld_pu`, `ba_prop_battle_tube_fn_01`, `ba_prop_battle_tube_fn_02`, `ba_prop_battle_tube_fn_03`, `ba_prop_battle_tube_fn_04`, `ba_prop_battle_tube_fn_05`, `s_m_m_pilot_02`, `prop_cs_dildo_01`, `prop_roadcone02a`, `xs_prop_arena_pit_fire_01a`, `xs_prop_arena_pit_fire_02a`, `xs_prop_arena_pit_fire_03a`, `xs_prop_arena_pit_fire_04a`, `prop_barrier_work06a`, `prop_mb_cargo_03a`, `prop_mb_cargo_04a`, `prop_air_cargo_04a`, `prop_mb_cargo_02a`, `imp_prop_impexp_boxpile_01`, `prop_mb_crate_01a`, `gr_prop_gr_crates_pistols_01a`, `gr_prop_gr_crates_rifles_01a`, `gr_prop_gr_crates_rifles_02a`, `gr_prop_gr_crates_rifles_03a`, `gr_prop_gr_crates_rifles_04a`, `gr_prop_gr_crates_sam_01a`, `gr_prop_gr_crates_weapon_mix_01a`, `gr_prop_gr_gunsmithsupl_01a`, `gr_prop_gr_gunsmithsupl_02a`, `gr_prop_gr_gunsmithsupl_03a`, `gr_prop_gr_rsply_crate01a`, `gr_prop_gr_rsply_crate02a`, `gr_prop_gr_rsply_crate03a`, `prop_dumpster_02a`, `prop_jetski_ramp_01`, `gr_prop_gr_target_02b`, `gr_prop_gr_target_02a`, `hei_prop_hei_cash_trolly_03`, `gr_prop_gr_bench_02b`, `sf_prop_sf_swift2_01a`, `prop_flare_01`, `ch_prop_ch_service_trolley_01a`, `imp_prop_ship_01a`, `gr_prop_damship_01a`, `Set_Crowd_A`, `Set_Crowd_C`, `Set_Crowd_D`, `Set_Team_Band_A`, `Set_Team_Band_B`, `Set_Team_Band_D`, `prop_bowling_pin`, `prop_const_fence02b`, `prop_offroad_bale03`, `prop_offroad_bale02`, `prop_offroad_bale01`, `prop_offroad_tyres02`, `prop_barier_conc_02a`, `prop_barier_conc_05c`, `prop_barier_conc_05a` ...

**Audio banks** (16) - `DLC_AWXM2018/AJ_Interrupts`, `DLC_AWXM2018/AV_Interrupts`, `HUD_321_GO`, `MP_RACES_SLIPSTREAM`, `DLC_STUNT/STUNT_RACE_01`, `DLC_STUNT/STUNT_RACE_02`, `DLC_24-2/DLC_24-2_LUNAR_RACE_SFX`, `DLC_STUNT/STUNT_RACE_03`, `DLC_AIRRACES/AIR_RACE_01`, `DLC_AIRRACES/AIR_RACE_02`, `DLC_HEIST3/Circuit_Racing`, `DLC_MPSUM2/Island_Races`, `DLC_23_2/DLC_23_2_Drag_Race`, `DLC_23_2/DLC_23_2_Drift_Race`, `DLC_MP2023_1/DLC_MP2023_1_HW`, `DLC_AWXM2018/Arena_Traps`

**Sounds** (124) - `DLC_23_2_Drift_Sounds`, `DLC_23_2_Drag_Race_Sounds`, `HUD_AWARDS`, `MP_LEADERBOARD_SCENE`, `OTHER_TEXT`, `MP_CELEB_SCREEN_ARENA_SCENE`, `MP_CELEB_SCREEN_SCENE`, `HUD_MINI_GAME_SOUNDSET`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `DLC_Stunt_Race_Frontend_Sounds`, `Checkpoint_Lap`, `Checkpoint`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `DLC_sum20_Open_Wheel_Racing_Sounds`, `Car_Club_Races_Pursuit_Series_Sounds`, `Car_Club_Races_Street_Race_Sounds`, `Island_Race_Soundset`, `321`, `Countdown_2_1`, `DLC_Air_Race_Sounds_Player`, `Checkpoint_Finish`, `RACES_SLIPSTREAM_SCENE`, `DLC_AR_Beast_Soundset`, `dlc_aw_arena_speech_ducking_scene`, `MP_RACE_GENERAL_SCENE`, `Countdown_3`, `Countdown_Go`, `DLC_23_2_Drag_Race_Mixscenes_General_Scene`, `DLC_AW_Frontend_Sounds`, `RACES_RADIO_MUTE_scene`, `DLC_23_2_Drift_Race_Mixscenes_General_Scene`, `dlc_aw_arena_pit_vehicle_repairing_scene`, `Countdown_321`, `3_2_1`, `Score_Mulitply_Amount`, `DLC_23_2_Drag_Race_Mixscenes_Perfect_Shift_Scene`, `DLC_23_2_Drag_Race_Mixscenes_Nitrous_Boost_Scene`, `dlc_aw_arena_turret_scene`, `DLC_23_2_Drag_Race_Mixscenes_Intro_mixscene`, `MP_JOB_CHANGE_RADIO_MUTE`, `Hit`, `RESPAWN_ONLINE_SOUNDSET`, `health_lost`, `INFO`, `DLC_Biker_SL_Sounds`, `Go`, `Score_Tick_Loop`, `MP_POSITIONED_RADIO_MUTE_SCENE`, `Vehicle_Warp`, `Beast_Sprint_Loop`, `Intensity`, `Vehicle_Transform`, `Checkpoint_Final`, `DLC_AW_Arena_Lobby_Veh_Select_To_VIP_Transition_Scene`, `DLC_AW_Arena_Lobby_Veh_Select_To_Arena_Transition_Scene`, `BACK`, `ERROR`, `DPAD_WEAPON_SCROLL`, `Focus` ...

**Scaleform movies** (23) - `STRING`, `DRAG_RACE`, `ADD_WORLD_RECORD_TO_WALL`, `ADD_TIME_TO_WALL`, `ADD_MISSION_RESULT_TO_WALL`, `ADD_SCORE_TO_WALL`, `SET_MESSAGE`, `SET_SCREEN_POSITION`, `SET_PART_TO_DESTROYED`, `SET_DIRECTION`, `NUMBER`, `SET_COUNTDOWN_LIGHTS`, `SET_GEAR`, `SET_SPEED`, `SET_SPEED_UNITS`, `SET_METER_VALUE`, `SET_OUTER_GOAL`, `SET_INNER_GOAL`, `SET_IS_DRIFT_RACE`, `FLASH_OUTER_GOAL`, `FLASH_INNER_GOAL`, `SET_WHEEL_DAMAGE`, `OPEN_WHEEL_HEALTH_INDICATOR`

**Particle effects** (29) - `scr_sv_drag`, `scr_sv_drift`, `scr_sm`, `scr_as_trans`, `scr_as_target`, `scr_as_trans_smoke`, `scr_sv_drag_burnout`, `buildup`, `scr_lowrider`, `scr_indep_fireworks`, `scr_xm_submarine`, `scr_sum_ow`, `scr_dst_inflatable`, `scr_hr_lny_races`, `veh_xs_vehicle_mods`, `wheel_fric_hard`, `scr_sv_drag_wheel_fric_smoke`, `wheel_spin_snow`, `wheel_fric_grass`, `scr_sv_drag_wheel_fric_sand`, `wheel_fric_sand`, `scr_sr_adversary`, `ent_dst_gen_cardboard`, `scr_sv_drift_cc_trigger`, `scr_sv_drift_cc_persist`, `ent_dst_polystyrene`, `scr_sr_dst_cardboard`, `scr_powerplay`, `scr_sum_ow_race_repair_smoke`

**Text labels** (119) - `FMMC_PLYLOAD`, `OFF`, `SUMMARY`, `CLOUDS`, `SUMMARY2`, `LAMAR`, `WINNER`, `44DCT175`, `44ABV623`, `08MGJ922`, `ARM1AUD`, `RACES`, `FMMC`, `SMOG`, `OVERCAST`, `BASEOPPOINT`, `NULL`, `ARANNAU`, `47BQT444`, `03QPK213`, `12TCU014`, `49EAJ692`, `00EVK569`, `00NFP794`, `49QQX185`, `23OBR306`, `69VJG707`, `26EIU049`, `46JCA498`, `FVTEE`, `86CVG072`, `84TFX949`, `83OSX036`, `87LWG803`, `ANG3L1S`, `80WEG614`, `TAO1`, `66SBX027`, `27CLR579`, `48XTJ224`, `23IJE671`, `08ICY997`, `20WUI734`, `21VJM767`, `45IZW098`, `86VME156`, `85JFW893`, `87BYW202`, `41KKV206`, `22SCY913`, `ANCESTOR`, `04DZM900`, `65LNN730`, `88WFR722`, `63CMS702`, `23GVN817`, `86ACK549`, `60UYD615`, `05SKJ131`, `01SRP848` ...

**Decorators** (3) - `MC_EntityID`, `MC_ChasePedID`, `Not_Allow_As_Saved_Veh`

**Waypoint recordings** (1) - `multirace0_route3`

**Timecycle modifiers** (7) - `DLC_mp2023_02_Race_AO`, `Lunar_NewYear_Spectacle`, `Lunar_NewYear_LapOfHonor`, `Lunar_NewYear_TheBigBash`, `DragRaceGearPerf`, `DragRaceGearGood`, `DragRaceGearBad`

**Interiors and entity sets** (5) - `xs_x18_int_01`, `Arena_Room`, `entity_set_test_lights`, `entity_set_time_trial`, `entity_set_meet_lights`

**Vehicle mods** (14) - `mamba`, `stromberg`, `thruster`, `bodhi2`, `chino`, `voltic`, `buccaneer`, `buccaneer2`, `chino2`, `faction`, `faction2`, `voltic2`, `oppressor`, `vigilante`

**Stats** (1) - `mp0_char_fm_race_record_times`

**Scripts launched** (4) - `AM_MP_RC_VEHICLE`, `fm_deathmatch_controler`, `fm_race_controler`, `TimersHUD`

**Hashed names** (2) - `xs_x18intvip_vip_light_dummy`, `AM_MP_RC_VEHICLE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (856), `PARTICIPANT_ID_TO_INT` (778), `SET_BIT` (755), `PLAYER_ID` (513), `CLEAR_BIT` (327), `DOES_ENTITY_EXIST` (229), `LEADERBOARDS_WRITE_ADD_COLUMN` (209), `IS_PED_IN_ANY_VEHICLE` (185), `GET_VEHICLE_PED_IS_IN` (169), `TO_FLOAT` (134), `IS_ENTITY_DEAD` (133), `PLAY_SOUND_FRONTEND` (130), `DISABLE_CONTROL_ACTION` (127), `INT_TO_PARTICIPANTINDEX` (119), `GET_ENTITY_COORDS` (108), `GET_ENTITY_MODEL` (103), `NETWORK_IS_PARTICIPANT_ACTIVE` (85), `ROUND` (82), `NETWORK_HAS_CONTROL_OF_ENTITY` (80), `SET_PED_COMPONENT_VARIATION` (73), `NET_TO_VEH` (64), `NETWORK_GET_PLAYER_INDEX` (61), `GET_PLAYER_PED` (56), `IS_PED_INJURED` (54), `GET_NETWORK_TIME` (53), `DOES_CAM_EXIST` (47), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (42), `GET_RANDOM_INT_IN_RANGE` (42), `GET_DISTANCE_BETWEEN_COORDS` (41), `GET_FRAME_TIME` (38)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x29 · `0.3f` x26 · `0.75f` x16 · `1.2f` x14 · `0.6f` x12 · `0.7f` x11 · `0.4f` x9 · `1.32f` x9 · `0.8f` x8 · `0.85f` x8 · `0.2f` x7 · `-0.75f` x6 · `7.5f` x6 · `0.66f` x5 · `0.73333f` x5 · `0.25f` x4 · `0.1f` x4 · `0.001f` x4 · `38.4708f` x4 · `4.2f` x4 · `0.9f` x3 · `1.25f` x3 · `2.5f` x3 · `36.2397f` x3

## Other strings

Literals whose consuming native was not classified:

`DEFAULT_SCRIPTED_CAMERA`, `XPT_GTA_PICK`, `ruiner2`, `FM_1AU`, `CrossLine`, `Mission`, `blazer5`, `HAND_SHAKE`, `stromberg`, `SeasonId`, `ROAD_VIBRATION_SHAKE`, `rcbandito`, `deluxo`, `scr_hr_lny_races`, `submersible`, `submersible2`, `MobileRadioInGame`, `RACE_SPAWNH0`, `BASEJ_HLP_START`, `rallytruck`, `AllowScoreAndRadio`, `stt_prop_stunt_tube_jmp2`, `stt_prop_track_stop_sign`, `mp_m_freemode_01`, `DLC_23_2_Drag_Race_Sounds`, `MP_job_load`, `Laps`, `RACE_RAL5`, `BASEJ_HELP1`

---

Source: `decompiled_scripts/fm_race_controler.c`
