# franklin0.c

SP missions script. 2 anim dicts; 11 models; 1 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 130,953 |
| Functions | 1,075 (235 unique, 840 shared) |
| Unique lines | 18,309 (14.0% of file) |

## Assets

**Animation dictionaries** (2) - `ANIM_GROUP_GESTURE_MISS_FRA0`, `MISSCHOP_VEHICLE@BACK_OF_VAN`

**Animations** (56) - `put_chop_in_van_van`, `FRA0_IG_12_CHOP_WAITING_B`, `InCar_GetOutofBack_Speedo`, `InCar_PhoneIdle_Lem`, `Incar_Phonetalk_enter_Lem`, `InCar_PhoneSnatch_Fra`, `open_train_car_og`, `FRA_0_IG_15_CHOP_SPOTS_DOG`, `Take_off_Bandana`, `CHOP_GROWL_TO_SIT`, `Incar_Phonetalk_exit_Lem`, `FRA0_IG_12_CHOP_FAST_TURN_B`, `REACTION_FORWARD_BIG_INTRO_A`, `BIG_EXIT_TO_GENERIC`, `FRA0_IG_12_CHOP_FAST_TURN_A`, `BARK`, `van_get_out_van`, `find_ballasog_og`, `CHOP_BARK_AT_CARRIAGE`, `FRA0_IG_14_CHOP_SNIFF_FWDS`, `find_ballasOG_Fra`, `FRA0_IG_12_CHOP_WAITING_A`, `move_climb`, `BARK_SEQ`, `find_ballasog_chop`, `Hump_Exit_Scene_FRANKLIN`, `Hump_Exit_Scene_CHOP`, `Hump_Exit_Scene_LADYDOG`, `take_off_bandana_bandana`, `CHOP_SIT_LOOP`, `Incar_Phonetalk_loop_Lem`, `InCar_PhoneSnatch_Lem`, `FRA_0_IG_15_FEMALE_DOG_IDLE`, `InCar_GetOutofBack_Ballas`, `Hump_enter_chop`, `Hump_enter_ladydog`, `Hump_loop_chop`, `Hump_loop_ladydog`, `Hump_exit_chop`, `Hump_exit_ladydog`, `Call_Chop_R`, `Call_Chop_L`, `FRA_0_IG_CHOP_TAKE_DOWN_BALLA_CHOP`, `FRA_0_IG_CHOP_TAKE_DOWN_BALLA_VICTIM`, `CHOP_BARK_AT_BALLAS`, `open_train_car_fra`, `bonnet_slide_r_in`, `bonnet_slide_l_in`, `BallasOG_JumpOnTrain_IG7`, `franklin_wallcrash`, `REACT_SMALL_VARIATIONS_H`, `VAN_GET_OUT_FRANKLIN`, `van_get_out_lamar`, `van_get_out_chop`, `put_chop_in_van_lam`, `put_chop_in_van_chop`

**Models and props** (11) - `ig_ballasog`, `prop_rail_boxcar5_d`, `prop_fncconstruc_01d`, `ig_lamardavis`, `a_c_rottweiler`, `a_f_y_genhot_01`, `s_m_y_construct_02`, `prop_boxcar5_handle`, `prop_npc_phone`, `p_cs_bandana_s`, `prop_ld_test_01`

**Audio banks** (6) - `CHOP_CAM_A_01`, `CHOP_CAM_A_02`, `CHOP_CAM_B_01`, `CHOP_CAM_B_02`, `CHOP_CAM_C_01`, `CHOP_CAM_C_02`

**Sounds** (11) - `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `FRANKLIN_0_SOUNDS`, `CHOP_CAM_A`, `Franklin_Whistle_For_Chop`, `SPEECH_RELATED_SOUNDS`, `CHOP_CAM_B`, `CHOP_CAM_C`, `Boxcar_Door_Slide`, `Boxcar_Door_Limit`, `Crash_Through_Fence`

**Particle effects** (1) - `scr_franklin0_chop_trail`

**Text labels** (8) - `FKN0AUD`, `NULL`, `FRANKLIN`, `CHOP`, `LAMAR`, `FCHASE`, `BALLASOG`, `OFF`

**Waypoint recordings** (10) - `hood8`, `hood4`, `hood7`, `hood5`, `hood6`, `hood11`, `hood9`, `hood10`, `hood1`, `hood12`

**Relationship groups** (1) - `player`

**Timecycle modifiers** (1) - `chop`

**Vehicle mods** (3) - `bus`, `SPEEDO`, `forklift`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (438), `GET_GAME_TIMER` (239), `IS_PED_INJURED` (231), `IS_VEHICLE_DRIVEABLE` (106), `DOES_ENTITY_EXIST` (101), `IS_ENTITY_AT_ENTITY` (78), `GET_ENTITY_COORDS` (74), `PLAYER_ID` (65), `GET_SCRIPT_TASK_STATUS` (47), `IS_ENTITY_AT_COORD` (42), `SET_PED_MIN_MOVE_BLEND_RATIO` (36), `TASK_PLAY_ANIM` (35), `SET_ENTITY_COORDS` (35), `DISABLE_CONTROL_ACTION` (33), `DOES_BLIP_EXIST` (29), `GET_RANDOM_INT_IN_RANGE` (29), `IS_ENTITY_PLAYING_ANIM` (27), `SET_ENTITY_HEADING` (26), `IS_SYNCHRONIZED_SCENE_RUNNING` (24), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (24), `WAIT` (23), `GET_ENTITY_SPEED` (23), `DELETE_PED` (23), `TASK_LOOK_AT_ENTITY` (23), `SET_PED_MOVE_RATE_OVERRIDE` (22), `CREATE_SYNCHRONIZED_SCENE` (22), `SET_PED_COMPONENT_VARIATION` (22), `TASK_SYNCHRONIZED_SCENE` (21), `HAS_MODEL_LOADED` (21), `REMOVE_BLIP` (20)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.98f` x14 · `0.5f` x12 · `1.5f` x11 · `2.5f` x11 · `0.695f` x6 · `3.6f` x6 · `3.2f` x6 · `1.15f` x5 · `0.1f` x5 · `1.1f` x5 · `3.5f` x5 · `1.8f` x5 · `23.75121f` x4 · `0.2f` x4 · `23.75f` x4 · `0.536f` x4 · `551.07f` x4 · `-573.04f` x4 · `23.8f` x4 · `0.3f` x4 · `1.2f` x4 · `0.06f` x4 · `-14.20779f` x4 · `-1448.726f` x4

## Other strings

Literals whose consuming native was not classified:

`Lamar`, `Chop`, `Ballas_OG`, `emperor`, `Franklin`, `surge`, `MotionState_Sprint`, `picador`, `stab`, `EXIT_TO_GENERIC`, `ChopVision`, `MotionState_Aiming`, `issi2`, `ruiner`, `dilettante`, `MotionState_Walk`, `FC_CLOSER`, `bus`, `ANIM_GROUP_GESTURE_MISS_FRA0`, `MotionState_Run`, `FC_GOCHOP`, `DisableAbortConversationForRagdoll`, `CamPushInNeutral`, `FC_POSHLP`, `invalid`, `dominator`, `FC_GOBOX`, `FC_BOXHLP`, `polmav`, `FC_FOLLAM`

---

Source: `decompiled_scripts/franklin0.c`
