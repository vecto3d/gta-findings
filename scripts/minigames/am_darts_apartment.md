# am_darts_apartment.c

Minigames script. 4 anim dicts; 5 models; 11 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 86,394 |
| Functions | 1,085 (156 unique, 929 shared) |
| Unique lines | 7,946 (9.2% of file) |

## Assets

**Animation dictionaries** (4) - `anim@amb@clubhouse@mini@darts@`, `mini@dartsintro_alt1`, `mini@darts`, `mini@dartsoutro`

**Animations** (7) - `anim@amb@clubhouse@mini@darts@`, `throw_idle_a_down`, `outro`, `throw_overlay`, `mini@dartsintro_alt1`, `darts_ig_intro_alt1_guy2`, `darts_ig_intro_alt1_guy1`

**Models and props** (5) - `prop_phonebox_03`, `prop_dart_1`, `prop_dart_2`, `prop_dart_bd_cab_01`, `prop_target_bull`

**Audio banks** (1) - `SCRIPT\DARTS`

**Sounds** (17) - `MP_CELEB_SCREEN_SCENE`, `DARTS_HIT_BOARD_MASTER`, `CELEBRATION_SOUNDSET`, `DARTS_THROW_DART_MASTER`, `WINNER`, `LOSER`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `DLC_Biker_Darts_Hit_Board_Remote_Master`, `GOLF_NEW_RECORD`, `HUD_AWARDS`, `DARTS_HIT_DART_MASTER`, `DARTS_HIT_BULLSEYE_MASTER`, `DARTS_HIT_WALL_MASTER`, `DARTS_SCORE_TRIPLE_MASTER`, `DARTS_SCORE_DOUBLE_MASTER`, `DARTS_HIT_WIRE_MASTER`

**Scaleform movies** (11) - `instructional_buttons`, `SET_PLAYER_SETS_AND_LEGS`, `SET_CREW_TAG`, `DARTS_SCOREBOARD_BIKER`, `SET_PLAYER_HIGHLIGHT`, `ADD_DARTS_SCORE`, `CLEAR_ALL`, `RESET_MOVIE`, `STRING`, `SET_DARTS_PLAYER_NAMES`, `CLEAR_SCORES`

**Texture dicts** (1) - `Darts`

**Text labels** (8) - `SUMMARY`, `NULL`, `WINNER`, `DARTS`, `NORMAL`, `HOST`, `SPECTATOR`, `INVALID`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (78), `INT_TO_PARTICIPANTINDEX` (44), `NETWORK_GET_PLAYER_INDEX` (43), `PARTICIPANT_ID_TO_INT` (34), `PLAYER_PED_ID` (32), `GET_RANDOM_FLOAT_IN_RANGE` (32), `DOES_ENTITY_EXIST` (31), `SET_BIT` (29), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (26), `GET_GAME_TIMER` (22), `CLEAR_HELP` (19), `CREATE_CAMERA_WITH_PARAMS` (19), `GET_PLAYER_PED` (18), `IS_PED_INJURED` (18), `SET_CAM_ACTIVE` (16), `ROUND` (13), `PLAY_SOUND_FROM_COORD` (13), `CLEAR_PRINTS` (13), `_SEND_TU_SCRIPT_EVENT_NEW` (12), `IS_CAM_ACTIVE` (10), `IS_PAUSE_MENU_ACTIVE` (9), `RENDER_SCRIPT_CAMS` (9), `GET_PLAYER_NAME` (9), `REQUEST_ANIM_DICT` (9), `BEGIN_SCALEFORM_MOVIE_METHOD` (9), `END_SCALEFORM_MOVIE_METHOD` (9), `GET_PLAYER_INDEX` (8), `NETWORK_IS_PARTICIPANT_ACTIVE` (8), `TASK_PLAY_ANIM` (8), `IS_SCREEN_FADED_OUT` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`40.3693f` x8 · `-1.7272f` x6 · `0.1f` x6 · `-2.6f` x4 · `-18.4027f` x4 · `0.02f` x3 · `8.5f` x3 · `0.3f` x2 · `0.66f` x2 · `0.33f` x2 · `-0.35f` x2 · `0.35f` x2 · `-2.4f` x2 · `-0.1f` x2 · `7.56f` x2 · `47.0142f` x2 · `-3.567f` x2 · `112.2157f` x2 · `-1.6441f` x2 · `122.4329f` x2 · `560.8927f` x2 · `-419.1003f` x2 · `-67.8403f` x2 · `90.0239f` x2

## Other strings

Literals whose consuming native was not classified:

`DARTS_INSTR_B`, `DARTS_INSTR_W`, `DARTS_AIM_HLP`, `DARTS_END_QT`, `DARTS_SHT_USE`, `Darts`, `DARTS_SHT_CLCK`, `DARTS_CLOCK`, `Current client is waiting for other client to finish throwing`, `XPT_DARTS`, `DARTS_WINNER`, `DARTS_FST_HLP`, `Dart_Reticules`, `HAND_SHAKE`, `DARTS_REMAIN`, `DARTS_STD_HLP`, `DARTS_THROW`, `DARTS_AIM`, `AllowRadioOverScreenFade`, `DARTS_ENEMIES`, `MN_DART`, `DARTS_TIOT`, `[AM_DARTS] current client is THROWING`, `Waiting for other client to get to DARTS_MPWAIT_TURN_CHANGE`, `Current client is waiting for other client to throw`, `DARTS_DOUBLE_T`, `DARTS_TRIPLE_T`, `DARTS_BULL_T`, `DARTS_DBL_WIN`, `Waiting for other client to get to DARTS_MPTHROW_TURN_CHANGE`

---

Source: `decompiled_scripts/am_darts_apartment.c`
