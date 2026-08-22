# trevor3.c

SP missions script. 11 anim dicts; 14 models; 1 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 65,819 |
| Functions | 652 (99 unique, 553 shared) |
| Unique lines | 12,473 (19.0% of file) |

## Assets

**Animation dictionaries** (11) - `misstrevor3`, `misstrevor3_beatup`, `reaction@male_stand@big_variations@b`, `reaction@male_stand@big_intro@left`, `reaction@male_stand@big_intro@right`, `reaction@male_stand@big_intro@backward`, `move_f@flee@a`, `reaction@male_stand@big_variations@idle_c`, `misschinese2_bank1`, `misstrevor3ig_7`, `misstrevor3leadinout`

**Animations** (65) - `misschinese2_bank1`, `misstrevor3`, `misstrevor3_beatup`, `buddy_shot_b`, `alert_gunshot`, `react_forward_small_intro_a`, `react_left_small_intro_a`, `react_right_small_intro_a`, `react_backward_small_intro_a`, `reaction@male_stand@big_variations@b`, `reaction_forward_big_intro_a`, `misstrevor3ig_7`, `spot_high`, `spot_low`, `spot_mid`, `alert_body`, `reaction@male_stand@big_intro@left`, `reaction@male_stand@big_intro@right`, `reaction@male_stand@big_intro@backward`, `shove_trev`, `react_big_variations_d`, `brokendown_longlook`, `brokendown_wrongwithyou`, `bike_chat_b_loop_1`, `biker_mourns`, `horny_biker`, `bike_chat_b_outro_2`, `misstrevor3leadinout`, `reaction@male_stand@big_variations@idle_c`, `react_big_variations_e`, `react_big_variations_f`, `reaction_left_big_intro_a`, `reaction_left_big_intro_b`, `reaction_left_big_intro_c`, `reaction_right_big_intro_a`, `reaction_right_big_intro_b`, `reaction_right_big_intro_c`, `reaction_backward_big_intro_a`, `reaction_backward_big_intro_b`, `reaction_backward_big_intro_c`, `brokendown_suchabitch`, `horny_biker_loop`, `bike_chat_b_loop_2`, `bike_chat_a_1`, `bike_chat_a_2`, `guard_beatup_startidle_dockworker`, `guard_beatup_startidle_guard1`, `guard_beatup_startidle_guard2`, `biker_exit_1`, `biker_exit_2`, `bike_chat_b_outro_1`, `guard_beatup_mainaction_dockworker`, `guard_beatup_mainaction_guard1`, `guard_beatup_mainaction_guard2`, `guard_beatup_kickidle_dockworker`, `guard_beatup_kickidle_guard1`, `guard_beatup_kickidle_guard2`, `guard_beatup_exit_dockworker`, `guard_beatup_exit_guard1`, `guard_beatup_exit_guard2` ...

**Models and props** (14) - `g_m_y_lost_01`, `g_m_y_lost_02`, `hexer`, `prop_coffin_01`, `prop_cs_beer_bot_01`, `a_f_m_salton_01`, `dloader`, `prop_cs4_05_tdoor`, `prop_magenta_door`, `prop_ld_test_01`, `bodhi2`, `ig_wade`, `blazer`, `g_m_y_lost_03`

**Audio banks** (1) - `TIME_LAPSE`

**Sounds** (14) - `TREVOR_3_TRAILER_PARK_OVERVIEW`, `TREVOR_3_PLANT_BOMBS_STEALTH`, `TREVOR_3_RAYFIRE`, `TREVOR_3_DRIVE_TO_LS_DIALOGUE`, `TREVOR_3_DRIVE_TO_FLOYDS`, `TREVOR_3_DRIVE_TO_TRAILER_PARK`, `TREVOR_3_PLANT_BOMBS_SHOOTOUT`, `TREVOR_3_DETONATE_BOMBS`, `TOD_SHIFT_SCENE`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `TREVOR_3_ESCAPE_TO_CAR`, `TIME_LAPSE_MASTER`, `DAMAGED_TRUCK_IDLE`

**Speech contexts** (3) - `SPEECH_PARAMS_FORCE`, `CHAT_STATE`, `CHAT_RESP`

**Particle effects** (1) - `scr_trev3_trailer_plume`

**Text labels** (17) - `TREVOR`, `TRV3BIKER2`, `TREV3BIKER2`, `THUNDER`, `SMOG`, `TREV3BIKER3`, `WADE`, `DEFAULT`, `NULL`, `TRV3BIKER3`, `TRV3AUD`, `OVERCAST`, `OFF`, `CLEARING`, `FLOYD`, `TREV3`, `EXTRASUNNY`

**Scenarios** (4) - `PROP_HUMAN_SEAT_CHAIR`, `PROP_HUMAN_SEAT_ARMCHAIR`, `WORLD_HUMAN_AA_SMOKE`, `WORLD_HUMAN_SMOKING_POT`

**Waypoint recordings** (2) - `trev3_trL`, `trev3_trR`

**Vehicle recordings** (1) - `trev3`

**Relationship groups** (5) - `relGroupDislike`, `Gangb`, `Wade`, `fought ped`, `player`

**Timecycle modifiers** (1) - `trailer_explosion_optimise`

**Vehicle mods** (2) - `bodhi2`, `taxi`

**Hashed names** (1) - `EXP_VFXTAG_TREV3_TRAILER`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (383), `GET_GAME_TIMER` (134), `GET_ENTITY_COORDS` (84), `DOES_ENTITY_EXIST` (72), `SET_PED_COMPONENT_VARIATION` (61), `IS_PED_IN_ANY_VEHICLE` (48), `SET_ENTITY_COORDS` (39), `SET_ENTITY_HEADING` (38), `GET_ENTITY_MODEL` (33), `TASK_SYNCHRONIZED_SCENE` (32), `PLAYER_ID` (31), `IS_PED_INJURED` (30), `TASK_PLAY_ANIM` (30), `ADD_CAM_SPLINE_NODE` (26), `GET_RANDOM_INT_IN_RANGE` (26), `IS_SYNCHRONIZED_SCENE_RUNNING` (25), `SET_MODEL_AS_NO_LONGER_NEEDED` (24), `IS_ENTITY_PLAYING_ANIM` (24), `GET_VEHICLE_PED_IS_IN` (23), `REQUEST_MODEL` (23), `GET_SYNCHRONIZED_SCENE_PHASE` (23), `IS_VEHICLE_DRIVEABLE` (21), `STOP_AUDIO_SCENE` (21), `SET_PLAYER_CONTROL` (21), `TASK_SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (21), `CREATE_SYNCHRONIZED_SCENE` (21), `HIDE_HUD_AND_RADAR_THIS_FRAME` (20), `HAS_MODEL_LOADED` (20), `REMOVE_ANIM_DICT` (18), `TASK_FOLLOW_NAV_MESH_TO_COORD` (18)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.9f` x13 · `72.0823f` x13 · `3695.32f` x13 · `42.9907f` x13 · `0.2f` x9 · `0.25f` x9 · `-1350.147f` x7 · `725.3141f` x7 · `185.3831f` x7 · `38.8369f` x6 · `3656.937f` x6 · `43.4604f` x6 · `-1152.782f` x6 · `-1523.988f` x6 · `3.5198f` x6 · `-1.5f` x6 · `51.367f` x5 · `3697.315f` x5 · `38.756f` x5 · `-28.44f` x5 · `38.7549f` x5 · `0.8f` x4 · `59.8307f` x4 · `3605.682f` x4

## Other strings

Literals whose consuming native was not classified:

`Wade`, `Trevor`, `DEFAULT_SPLINE_CAMERA`, `TRV3_EXPLOSIONS`, `TRV3_BIKER1`, `misstrevor3`, `bodhi2`, `TRV3_ALERTED`, `hexer`, `MotionState_Walk`, `WomanInTrailer`, `player`, `TRV3_ST5`, `dloader`, `TRV3_GIRL1`, `TRV3_attr`, `TRV3_BDY1`, `Hand_shake`, `chi2_hear`, `Paper_Car`, `TRV3_DRI`, `TRV3_INT`, `TRV3_BIKER6`, `TRV3_dirW`, `TRV3_6a`, `TRV3_6`, `MotionState_Aiming`, `TRV3_CHAT`, `CamPushInNeutral`, `DisableAbortConversationForDeathAndInjury`

---

Source: `decompiled_scripts/trevor3.c`
