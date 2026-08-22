# exile3.c

SP missions script. 6 anim dicts; 15 models; 8 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 137,892 |
| Functions | 1,106 (225 unique, 881 shared) |
| Unique lines | 18,001 (13.1% of file) |

## Assets

**Animation dictionaries** (6) - `MISSEXILE3@TRAIN_`, `missexile3@trevor_idle@enter`, `missexile3@trevor_idle@base`, `missexile3@trevor_idle@idle_a`, `missexile3@trevor_idle@exit`, `MISSEXILE3@TRAINCRASH`

**Animations** (19) - `p_cs1_14b_train_s_break`, `p_cs1_14b_train_s`, `base`, `EX03_DINGY_PICKUP_CASE_MICHAEL`, `EX03_DINGY_GET_RPG_TREVOR`, `EX03_DINGY_STOW_RPG_TREVOR`, `enter`, `idle_a`, `idle`, `ig_14_switch_mic_to_trev`, `EX03_TRAIN_BIKE_SCENE`, `EX03_TRAIN_BIKE_SCENE_DRIVER`, `_enter_trailer`, `ex03_attack_driver_outro_driver`, `EX03_DINGY_CLIMB_DOWN_ENTER_MICHAEL`, `EX03_DINGY_CARRY_CASE_MICHAEL`, `EX03_TREVOR_LOOK_DINGHY`, `exit`, `traincrash_revised_trevor`

**Models and props** (15) - `cs_fam5_water_splash_ped_in`, `cs_fam5_water_splash_ped_out`, `P_IDOL_CASE_S`, `p_cs1_14b_train_s_break`, `s_m_m_lsmetro_01`, `s_m_y_blackops_01`, `p_cs1_14b_train_s`, `prop_box_ammo04a`, `prop_idol_case_02`, `prop_box_wood01a`, `prop_barrel_01a`, `p_cs1_14b_train_s_col`, `p_cs1_14b_train_esdoor`, `v_ilev_trevtraildr`, `cs_fam5_water_splash_ped_wade`

**Sounds** (17) - `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `1st_Person_Transition`, `Hit_In`, `BOAT_WAVE_HIT_SCRIPT`, `EXILE_3_TYRE_CHIRPS_MASTER`, `EXILE_3_LAND_ON_TRAIN_MASTER`, `EXILE_3_TRAIN_BRAKE_PULL_MASTER`, `EXILE_3_TRAIN_BRAKE_RELEASE_MASTER`, `EXILE_3_TRAIN_ACCEL_CONTROL_SCENE`, `TimeAccelerateHeldDown`, `EXILE_3_TRAIN_DECEL_CONTROL_SCENE`, `TimeDecelerateHeldDown`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `EXILE_3_TRAIN_FALL_MASTER`, `Hit_Out`, `Short_Transition_In`

**Particle effects** (8) - `debris`, `ent_ray_train_falling_debris`, `scr_ex3_water_dinghy_wash`, `splashes`, `ent_ray_train_debris_splash`, `scr_ex3_engine_fire`, `scr_ex3_container_smoke`, `ent_ray_train_splash`

**Text labels** (7) - `MICHAEL`, `EXL3AUD`, `TREVOR`, `NULL`, `MISSTRCRASH`, `MISSEXILE3`, `TCRASH`

**Scenarios** (2) - `WORLD_HUMAN_STAND_IMPATIENT`, `WORLD_HUMAN_HANG_OUT_STREET`

**Waypoint recordings** (2) - `exile35`, `exile31`

**Vehicle recordings** (1) - `trcrash`

**Relationship groups** (2) - `player`, `Enemy Group`

**Timecycle modifiers** (1) - `canyon_mission`

**Vehicle mods** (5) - `pranger`, `scorcher`, `blazer`, `cuban800`, `lazer`

**Hashed names** (1) - `DOORHASH_T_TRAILER_CS`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (340), `GET_GAME_TIMER` (213), `IS_PED_INJURED` (167), `IS_VEHICLE_DRIVEABLE` (165), `DOES_ENTITY_EXIST` (95), `GET_ENTITY_COORDS` (63), `WAIT` (43), `PLAYER_ID` (41), `IS_ENTITY_AT_COORD` (36), `DOES_BLIP_EXIST` (35), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (32), `IS_ENTITY_AT_ENTITY` (29), `DISABLE_CONTROL_ACTION` (29), `TIMESTEP` (27), `SET_PED_CONFIG_FLAG` (26), `IS_PED_IN_ANY_VEHICLE` (25), `GET_TRAIN_CARRIAGE` (24), `IS_PED_IN_VEHICLE` (24), `SET_ENTITY_COORDS` (22), `FREEZE_ENTITY_POSITION` (22), `STOP_PLAYBACK_RECORDED_VEHICLE` (21), `DELETE_PED` (19), `SET_PED_INTO_VEHICLE` (19), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (19), `DELETE_OBJECT` (19), `DOES_PARTICLE_FX_LOOPED_EXIST` (19), `REMOVE_BLIP` (18), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (17), `STOP_PARTICLE_FX_LOOPED` (17), `SET_CURRENT_PED_WEAPON` (16)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x10 · `0.25f` x8 · `1973.857f` x7 · `1.5f` x6 · `0.2f` x6 · `3818.708f` x6 · `32.43631f` x6 · `0.7f` x5 · `1.8f` x4 · `0.99f` x4 · `30.4f` x4 · `-492.59f` x4 · `4433.52f` x4 · `29.8f` x4 · `-491.36f` x4 · `4436.4f` x4 · `32.7f` x4 · `-491.2f` x4 · `4435.3f` x4 · `31.7f` x4 · `2.5f` x3 · `6.75f` x3 · `1.2f` x3 · `-490.5f` x3

## Other strings

Literals whose consuming native was not classified:

`Michael`, `Trevor`, `thisSwitchCam`, `FIRING_PATTERN_FULL_AUTO`, `FIRING_PATTERN_BURST_FIRE`, `TC_JUMP`, `EX03_DINGY_PICKUP_CASE_MICHAEL`, `EX03_DINGY_GET_RPG_TREVOR`, `EX03_DINGY_STOW_RPG_TREVOR`, `TC_DRVTRN`, `CamPushInNeutral`, `EXL3_SEE_TRAIN`, `EXL3_BIKE_LAND`, `CMN_GENGETINBK`, `CMN_GENGETBCKBK`, `TC_CAR`, `MotionState_Walk`, `SwitchSceneTrevor`, `gadget_parachute`, `EXL3_RAPIDS_START`, `TC_BMBHLP3`, `TC_CYCLEW`, `TC_BMBHLP`, `TC_BMBHLPB`, `EX03_TRAIN_BIKE_LAND`, `EXL3_PANIC`, `TC_FOLTR`, `TC_PATHLP`, `SMALL_EXPLOSION_SHAKE`, `EXL3_RAD1`

---

Source: `decompiled_scripts/exile3.c`
