# yoga.c

Minigames script. 3 anim dicts; 8 models; 17 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 94,355 |
| Functions | 435 (49 unique, 386 shared) |
| Unique lines | 3,401 (3.6% of file) |

## Assets

**Animation dictionaries** (3) - `mini@yoga`, `move_p_m_zero_idles@generic`, `missfam5_yoga`

**Animations** (45) - `start_pose`, `mini@yoga`, `move_p_m_zero_idles@generic`, `fidget_impatient`, `start_to_a1`, `a2_to_a3`, `a3_to_b4`, `c1_to_c2`, `c6_to_c7`, `fail_to_start_a`, `fail_to_start_b`, `fail_to_start_c`, `outro_1`, `outro_2`, `A1_POSE`, `C1_POSE`, `A2_POSE`, `C2_POSE`, `A3_POSE`, `C3_POSE`, `B4_POSE`, `C4_POSE`, `C5_POSE`, `C6_POSE`, `C7_POSE`, `C8_POSE`, `intro`, `missfam5_yoga`, `a1_pose`, `a1_to_a2`, `a2_pose`, `a3_pose`, `b4_pose`, `start_to_c1`, `c1_pose`, `c2_pose`, `c2_to_c3`, `c3_pose`, `c3_to_c4`, `c4_pose`, `c4_to_c5`, `c5_pose`, `c5_to_c6`, `c6_pose`, `c7_pose`

**Models and props** (8) - `prop_yoga_mat_03`, `a_c_mtlion`, `prop_mem_candle_04`, `prop_mem_candle_05`, `prop_mem_candle_06`, `prop_mp3_dock`, `prop_phone_ing`, `prop_npc_phone`

**Audio banks** (2) - `FAM5_YOGA_01`, `FAM5_YOGA_02`

**Sounds** (6) - `YOGA_MINIGAME_TRANQUIL`, `FAMILY_5_SOUNDS`, `YOGA_EXHALE`, `Version`, `YOGA_INHALE`, `YOGA_FAIL`

**Scaleform movies** (17) - `REPLACE_KEYS_WITH_STICK`, `REPLACE_STICK_WITH_KEYS`, `HIDE_STICK_POINTER`, `SET_STICK_POINTER_ANGLE`, `SET_STICK_POINTER_RGB`, `REMOVE_BUTTONS`, `BUTTON_PRESSED`, `BUTTON_DEPRESSED`, `SET_BUTTON_TARGET`, `ADD_BUTTON_TO_LIST`, `SET_PLAYER_INPUT_COLOUR`, `SET_STICK_POINTER_HIGHLIGHT_ANGLE`, `yoga_buttons`, `yoga_keys`, `DRAW_BUTTONS`, `instructional_buttons`, `DISPLAY_VIEW`

**Text labels** (3) - `STICKS`, `NULL`, `YOGA`

**Scenarios** (1) - `WORLD_MOUNTAIN_LION_WANDER`

**Timecycle modifiers** (1) - `STONED_CUTSCENE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (65), `PLAYER_PED_ID` (60), `IS_ENTITY_PLAYING_ANIM` (42), `BEGIN_SCALEFORM_MOVIE_METHOD` (31), `END_SCALEFORM_MOVIE_METHOD` (31), `IS_PED_INJURED` (20), `SET_CAM_PARAMS` (20), `PLAYER_ID` (13), `CLEAR_HELP` (11), `DOES_CAM_EXIST` (11), `IS_PC_VERSION` (10), `PLAY_FACIAL_ANIM` (10), `IS_SYNCHRONIZED_SCENE_RUNNING` (10), `GET_GAME_TIMER` (9), `HAS_SOUND_FINISHED` (9), `TASK_PLAY_ANIM_ADVANCED` (8), `IS_USING_KEYBOARD_AND_MOUSE` (8), `IS_SCREEN_FADED_IN` (8), `CREATE_CAMERA` (8), `RENDER_SCRIPT_CAMS` (8), `TRIGGER_MUSIC_EVENT` (8), `SET_FACIAL_IDLE_ANIM_OVERRIDE` (8), `TO_FLOAT` (7), `CLEAR_PED_TASKS_IMMEDIATELY` (7), `DISPLAY_HUD` (7), `DISPLAY_RADAR` (7), `DOES_ENTITY_EXIST` (7), `GET_SYNCHRONIZED_SCENE_PHASE` (7), `CLEAR_SEQUENCE_TASK` (6), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`39.35555f` x18 · `-782.8024f` x5 · `187.4389f` x5 · `73.32661f` x5 · `-3.540541f` x5 · `99.79994f` x5 · `2870.826f` x5 · `5943.485f` x5 · `356.9121f` x5 · `11.16632f` x5 · `0.034383f` x5 · `76.03407f` x5 · `-787.033f` x4 · `186.8823f` x4 · `73.06341f` x4 · `-3.376375f` x4 · `97.66577f` x4 · `2867.668f` x4 · `5944.266f` x4 · `357.5547f` x4 · `9.696003f` x4 · `0.034384f` x4 · `75.40434f` x4 · `0.25f` x4

## Other strings

Literals whose consuming native was not classified:

`INHALE_NEW`, `blushing`, `MGYG_POSITION_COMPLETE`, `STICKS_KM`, `HAND_SHAKE`, `EXHALE_NEW`, `MGYG_END`, `npcphone`, `start_to_a1`, `a1_pose`, `a1_to_a2`, `a2_pose`, `a2_to_a3`, `a3_pose`, `MGYG_START`, `a2_fail_to_start`, `c1_fail_to_start`, `c2_fail_to_start`, `c6_fail_to_start`, `michael_breathing_face`, `michael_breathing_face_exhale`, `michael_breathing_face_exhale_oow`, `START_POSE`, `Yoga`, `fail_face`, `a3_to_start`, `a3_to_b4`, `b4_pose`, `b4_to_start`, `start_to_c1`

---

Source: `decompiled_scripts/yoga.c`
