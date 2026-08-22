# trevor1.c

SP missions script. 8 anim dicts; 23 models; 8 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 137,722 |
| Functions | 1,017 (186 unique, 831 shared) |
| Unique lines | 22,635 (16.4% of file) |

## Assets

**Animation dictionaries** (8) - `misstrevor1`, `misstrevor1ig_7`, `misstrevor1bathroom`, `misstrevor1leadinout`, `MISSCOMMON@HANDS_UP_FLINCH`, `misstrevor1trv_1_mcs_2`, `misstrevor1ig_2`, `missheist_jewelleadinoutjh_endscene`

**Animations** (54) - `misstrevor1`, `misstrevor1ig_2`, `misstrevor1ig_7`, `gang_chatting_idle01_b`, `gang_chatting_idle02_b`, `MISSCOMMON@HANDS_UP_FLINCH`, `Ortega_02_Trevor_Arrival_Reaction`, `Ortega_03_Shouting_Idle`, `stand_ashley`, `FACIALS@GEN_MALE@BASE`, `dead_1`, `gang_chatting_leadin_b`, `gang_chatting_leadin_a`, `gang_chatting_leadin_c`, `gang_chatting_idle03_b`, `gang_chatting_idle01_a`, `gang_chatting_idle01_c`, `ortega_stand_loop_ort`, `Ortega_07_Holding_Onto_Side_Wall_Idle`, `misstrevor1trv_1_mcs_2`, `impact_large_01_wade`, `impact_large_02_wade`, `impact_large_03_wade`, `impact_small_01_wade`, `impact_small_02_wade`, `impact_small_03_wade`, `bumps_loop_large_01_wade`, `bumps_loop_large_02_wade`, `misstrevor1leadinout`, `leadout_action_wade`, `mr_philips_idle_johnny`, `mr_philips_idle_ashley`, `misstrevor1bathroom`, `trevor_peeing`, `gang_chatting_idle02_a`, `gang_chatting_idle02_c`, `gang_chatting_idle03_a`, `gang_chatting_idle03_c`, `ortega_kneel_to_stand_ort`, `ortega_kneel_loop_ort`, `ortega_stand_to_kneel_ort`, `ortega_kneel_outro_ort`, `FLINCH_ADDITIVE_A`, `FLINCH_ADDITIVE_B`, `FLINCH_ADDITIVE_C`, `Ortega_06_Fall_Back_Into_Trailer`, `Ortega_08_Run_To_Door_Outro`, `Ortega_04_1st_Hit_Reaction`, `Ortega_05_Panic_Idle`, `wait_enter_wade`, `jump_out_wade`, `ortega_01_drinking_idle_intro`, `bumps_loop_small_01_wade`, `bumps_loop_small_02_wade`

**Models and props** (23) - `g_m_y_lost_01`, `cs_trev1_blood`, `ig_johnnyklebitz`, `g_m_y_lost_02`, `prop_gascyl_02a`, `ig_clay`, `ig_terry`, `proptrailer`, `ig_ashley`, `g_m_y_lost_03`, `hexer`, `prop_gascyl_01a`, `prop_cs_beer_bot_01`, `ig_wade`, `rebel`, `prop_watercrate_01`, `ig_ortega`, `bodhi2`, `prop_wall_light_02a`, `prop_trailr_base_static`, `a_c_rottweiler`, `trflat`, `scrap`

**Audio banks** (3) - `TREVOR_1_TRAILER_IMPACTS`, `TREVOR_1_TRAILER_IMPACTS_1`, `TREVOR_1_TRAILER_IMPACTS_2`

**Sounds** (23) - `TREVOR_1_FOCUS_CAM_SCENE`, `TREVOR_1_CHASE_KILL_BIKERS`, `TREVOR_1_THREATEN_ORTEGA`, `TREVOR_1_SHOOTOUT_START`, `TREVOR_1_RAYFIRE`, `TREVOR_1_CHASE_FOLLOW_VAN`, `TREVOR_1_ORTEGA_KILLED`, `TREVOR_1_SHOOTOUT_BIKERS_FLEE`, `TREVOR_1_ARRIVE_AT_TRAILER`, `TREVOR_1_PUSH_THE_TRAILER`, `TREVOR_1_DRIVE_HOME`, `TREVOR_1_BIKES`, `TREVOR_1_DRIVE_TO_BIKERS`, `TREVOR_1_DRIVE_TO_TRAILER`, `TREVOR_1_TRAILER_IMPACT_MASTER_C`, `Trevor_1_Shootout_Start`, `TREVOR_1_LEAD_OUT_CR`, `TREVOR_1_RAM_TRAILER_REVS`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `TREVOR_1_TRAILER_IMPACT_MASTER_B`, `TREVOR_1_TRAILER_IMPACT_MASTER_A`, `SLOWMO_T1_RAYFIRE_EXPLOSION`

**Particle effects** (8) - `scr_trev1_trailer_wires`, `scr_trev1_trailer_boosh`, `scr_trev1_trailer_splash`, `scr_trev1_wheelspin_dirt`, `wheelspin`, `Speed`, `scr_trev1_crash_dust`, `ent_ray_meth_dust_settle`

**Text labels** (23) - `T1M1AUD`, `TREVOR`, `ORTEGA`, `COP`, `BLOOD`, `BIKER2`, `EXTRASUNNY`, `BIKER1`, `WIMPER`, `OFF`, `TERRY`, `CLAY`, `WADE`, `UNPIN`, `BAJS`, `LOST1`, `NULL`, `TREV1`, `WHIMPER`, `RON`, `LOST2`, `LOST3`, `VANNERSPLAYED`

**Scenarios** (1) - `WORLD_HUMAN_STAND_IMPATIENT`

**Vehicle recordings** (10) - `Trevor1dw`, `t1b`, `trev1chasedw`, `trevor1dw`, `T1Safehouse`, `trev1`, `pushtrailer`, `trevone`, `trevor1Dw`, `t1be`

**Relationship groups** (3) - `player`, `ENEMIES`, `BUDDIES`

**Vehicle mods** (3) - `hexer`, `gburrito`, `bodhi2`

**Stats** (1) - `sp_killed_ortega`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (645), `IS_PED_INJURED` (549), `IS_VEHICLE_DRIVEABLE` (364), `DOES_ENTITY_EXIST` (243), `GET_ENTITY_COORDS` (164), `IS_ENTITY_DEAD` (126), `DOES_BLIP_EXIST` (121), `GET_GAME_TIMER` (120), `REQUEST_VEHICLE_RECORDING` (110), `DISABLE_CONTROL_ACTION` (107), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (96), `IS_PED_IN_VEHICLE` (95), `HAS_VEHICLE_RECORDING_BEEN_LOADED` (89), `IS_ENTITY_IN_ANGLED_AREA` (85), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (81), `REMOVE_BLIP` (80), `REQUEST_MODEL` (74), `SET_MODEL_AS_NO_LONGER_NEEDED` (73), `SET_PED_COMBAT_ATTRIBUTES` (71), `IS_ENTITY_ON_SCREEN` (66), `PLAYER_ID` (65), `STOP_PLAYBACK_RECORDED_VEHICLE` (63), `GET_DISTANCE_BETWEEN_COORDS` (62), `HAS_MODEL_LOADED` (60), `WAIT` (59), `TRIGGER_MUSIC_EVENT` (56), `SET_ENTITY_HEALTH` (51), `SET_RELATIONSHIP_BETWEEN_GROUPS` (49), `TASK_COMBAT_PED` (49), `REMOVE_VEHICLE_RECORDING` (48)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x42 · `0.25f` x18 · `0.35f` x14 · `0.1f` x13 · `-0.45f` x13 · `-3.2f` x13 · `46.94767f` x12 · `3042.975f` x12 · `-17.54682f` x12 · `0.99f` x12 · `1.8f` x10 · `1.5f` x10 · `126.36f` x9 · `0.383f` x9 · `0.05f` x9 · `-30.8428f` x9 · `3028.216f` x9 · `29.8939f` x9 · `-10.1785f` x9 · `3051.786f` x9 · `43.0208f` x9 · `0.3f` x9 · `0.2f` x8 · `5.9328f` x7

## Other strings

Literals whose consuming native was not classified:

`TRV1_FAIL`, `player`, `hexer`, `Wade`, `T1M1_DUA`, `NervousRon`, `TREVOR_1_BIKES_GROUP`, `TRV1_Trail_end`, `TRV1_Trail_start`, `ROAD_VIBRATION_SHAKE`, `Ron`, `TRV_GT3`, `FIRING_PATTERN_FULL_AUTO`, `TRV_BDY2`, `T1M1_AL1`, `FALL_BACK`, `T1M1_SH1`, `M_MrPhilips`, `Trevors_car`, `TRV1_DRIVE_TRAILER_RT`, `T1M1_PH7`, `T1M1_PH8`, `WADE LEAVE`, `TRV_ORTRET`, `T1M1_EGA`, `T1M1_CUT1`, `GENERIC_WAR_CRY`, `T1M1_METH`, `T1M1_CH3`, `WADE NOISE REQUIRED`

---

Source: `decompiled_scripts/trevor1.c`
