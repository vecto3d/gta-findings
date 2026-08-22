# family5.c

SP missions script. 11 anim dicts; 17 models; 15 scaleforms; 1 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 123,864 |
| Functions | 928 (112 unique, 816 shared) |
| Unique lines | 11,562 (9.3% of file) |

## Assets

**Animation dictionaries** (11) - `missfam5_yoga`, `missfam5leadinoutmcs_5`, `missfam5mcs_6`, `missfam5_wet_walk`, `missfam5mcs_4leadin`, `missfam5_flying`, `missfam2mcs_intp1`, `missfam5_blackout`, `missfam5_drink`, `missfam5mcs_6drag`, `move_m@drunk@verydrunk`

**Animations** (72) - `missfam5_yoga`, `missfam5leadinoutmcs_5`, `missfam5_drink`, `start_pose`, `missfam5mcs_6`, `leadin_action_dealer`, `Drink_Michael&Jimmy_Plyer0`, `leadin_loop_alt_dealer`, `leadout_car_door`, `Drink_Michael&Jimmy_JimmyIdle`, `missfam5_wet_walk`, `wet_idle`, `missfam5_flying`, `falling_to_skydive`, `f_yogapose_c`, `i_yogapose_c`, `start_to_a1`, `a2_to_a3`, `a3_to_b4`, `c1_to_c2`, `c6_to_c7`, `f_yogapose_b`, `i_yogapose_b`, `f_yogapose_a`, `i_yogapose_a`, `push_michael_out_player0`, `push_michael_out_jimmy`, `leadout_mic`, `leadout_alt_jimmy`, `missfam5mcs_6drag`, `fam_5_mcs_6_drag_michael`, `Push_Michael_Out_Car`, `leadout_dealer`, `missfam5mcs_4leadin`, `family_5_mcs_4_loop_jimmy`, `Drink_Michael&Jimmy_Jimmy`, `a1_pose`, `a1_to_a2`, `a2_pose`, `a3_pose`, `b4_pose`, `start_to_c1`, `c1_pose`, `c2_pose`, `c2_to_c3`, `c3_pose`, `c3_to_c4`, `c4_pose`, `c4_to_c5`, `c5_pose`, `c5_to_c6`, `c6_pose`, `c7_pose`, `fail_to_start_a`, `fail_to_start_b`, `fail_to_start_c`, `A1_POSE`, `C1_POSE`, `A2_POSE`, `C2_POSE` ...

**Models and props** (17) - `s_m_m_movalien_01`, `u_m_y_burgerdrug_01`, `prop_controller_01`, `prop_headset_01`, `prop_yoga_mat_01`, `prop_yoga_mat_02`, `prop_yoga_mat_03`, `ig_fabien`, `prop_cs_bs_cup`, `prop_amanda_note_01`, `p_jimmyneck_03_s`, `v_ilev_mm_doorm_l`, `v_ilev_mm_doorm_r`, `prop_bs_map_door_01`, `p_bs_map_door_01_s`, `prop_cs_ciggy_01`, `p_meth_bag_01_s`

**Audio banks** (10) - `FAM5_MICHAEL_LONG_SCREAM`, `TIME_LAPSE`, `FAM5_DRUG_FLIGHT_END`, `FAM5_YOGA_01`, `FAM5_YOGA_02`, `FAM5_YOGA_CHIMPS`, `FAM5_YOGA_ALIENS`, `FAM5_YOGA_DRUGS_01`, `TAXI_VOMIT`, `FAM5_WASH_FACE`

**Sounds** (25) - `FAMILY_5_SOUNDS`, `FAMILY_5_GO_TO_JIMMY`, `FAMILY_5_TAKE_JIMMY`, `FAMILY_5_YOGA_ON_DRUGS`, `FAMILY_5_TAKE_JIMMY_FOCUS_CAM`, `FAMILY_5_YOGA_TRANQUIL`, `FAMILY_5_GO_HOME_INT`, `FAMILY_5_WAKE_UP_VOMIT`, `FAMILY_5_GO_HOME`, `FAMILY_5_DRUGS`, `FAMILY_5_DRUGS_FOCUS_CAM`, `FAMILY_5_GO_TO_BURGERSHOT`, `FAMILY_5_YOGA_MG`, `FAMILY_5_FLYING`, `YOGA_EXHALE`, `Version`, `YOGA_FAIL`, `YOGA_INHALE`, `TOD_SHIFT_SCENE`, `DrugsEffect`, `DrugsEffectSpeech`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `FLYING_STREAM_END_INSTANT`, `MICHAEL_LONG_SCREAM`

**Scaleform movies** (15) - `REPLACE_KEYS_WITH_STICK`, `REPLACE_STICK_WITH_KEYS`, `HIDE_STICK_POINTER`, `SET_STICK_POINTER_ANGLE`, `SET_STICK_POINTER_RGB`, `REMOVE_BUTTONS`, `yoga_buttons`, `yoga_keys`, `BUTTON_PRESSED`, `BUTTON_DEPRESSED`, `SET_BUTTON_TARGET`, `ADD_BUTTON_TO_LIST`, `SET_PLAYER_INPUT_COLOUR`, `SET_STICK_POINTER_HIGHLIGHT_ANGLE`, `DRAW_BUTTONS`

**Particle effects** (1) - `scr_trev_puke`

**Text labels** (12) - `FAM5AUD`, `JIMMY`, `STICKS`, `EXTRASUNNY`, `FAM5DEALER`, `MICHAEL`, `CLOUDS`, `NULL`, `YOGA`, `FAM5`, `AMANDA`, `FABIAN`

**Timecycle modifiers** (3) - `STONED_CUTSCENE`, `stoned_monkeys`, `stoned_aliens`

**Doors** (1) - `v_ilev_mm_doorson`

**Vehicle mods** (1) - `police`

**Hashed names** (3) - `Interrupt`, `Drink_Sfx`, `Detach`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (471), `DOES_ENTITY_EXIST` (145), `IS_PED_INJURED` (139), `IS_ENTITY_IN_ANGLED_AREA` (90), `IS_ENTITY_PLAYING_ANIM` (72), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (64), `IS_ENTITY_DEAD` (61), `PLAYER_ID` (60), `SET_CUTSCENE_PED_COMPONENT_VARIATION` (58), `IS_SCREEN_FADED_OUT` (50), `IS_DOOR_REGISTERED_WITH_SYSTEM` (43), `DOES_CAM_EXIST` (42), `GET_GAME_TIMER` (42), `GET_ENTITY_COORDS` (39), `DISABLE_CONTROL_ACTION` (38), `DOOR_SYSTEM_SET_DOOR_STATE` (37), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (36), `DISPLAY_RADAR` (35), `DOOR_SYSTEM_SET_OPEN_RATIO` (35), `REGISTER_ENTITY_FOR_CUTSCENE` (31), `IS_VEHICLE_DRIVEABLE` (30), `BEGIN_SCALEFORM_MOVIE_METHOD` (30), `END_SCALEFORM_MOVIE_METHOD` (30), `HAS_ANIM_DICT_LOADED` (29), `RENDER_SCRIPT_CAMS` (29), `TASK_PLAY_ANIM_ADVANCED` (26), `DISPLAY_HUD` (26), `GET_PLAYERS_LAST_VEHICLE` (26), `IS_PED_IN_VEHICLE` (25), `DO_SCREEN_FADE_IN` (24)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`78.74073f` x42 · `75.24073f` x24 · `74.83471f` x16 · `2.5f` x13 · `4.5f` x12 · `-809.1252f` x10 · `173.5482f` x10 · `75.74007f` x10 · `-806.509f` x10 · `166.3648f` x10 · `71.10547f` x10 · `0.5f` x9 · `-817.305f` x9 · `179.33f` x9 · `75.15309f` x8 · `71.241f` x8 · `3.5f` x7 · `-804.6793f` x7 · `183.0435f` x7 · `70.84778f` x7 · `-816.2804f` x7 · `178.597f` x7 · `0.125f` x7 · `-806.1502f` x6

## Other strings

Literals whose consuming native was not classified:

`Amanda`, `Fabien`, `Michael`, `FAM5_YOGA_MOVE_START`, `Jimmy`, `player`, `Burgershot_drugdealer`, `blushing`, `HAND_SHAKE`, `mansion_1`, `f5_jimmy1`, `FAM5_SON5`, `Michaels_YogaMat`, `Fabiens_YogaMat`, `Amandas_yogamat`, `INHALE_NEW`, `Headset_Jimmy`, `Jimmy_Controller`, `player_zero`, `DMT_flight`, `DisableAbortConversationForRagdoll`, `Jimmy_necklace`, `FAM5_WNTD1`, `FAM5_SON1A`, `FAM5_SON1B`, `FAM5_SON1D`, `FAM5_JROOM1`, `FAM5_SUNBF`, `STICKS_KM`, `missfam5mcs_6`

---

Source: `decompiled_scripts/family5.c`
