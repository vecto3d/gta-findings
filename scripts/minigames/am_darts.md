# am_darts.c

Minigames script. 5 anim dicts; 4 models; 10 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 138,119 |
| Functions | 1,496 (106 unique, 1,390 shared) |
| Unique lines | 6,820 (4.9% of file) |

## Assets

**Animation dictionaries** (5) - `mini@dartsoutro`, `mini@dartsintro_alt1`, `mini@darts`, `facials@gen_male@variations@happy`, `facials@gen_male@variations@angry`

**Animations** (6) - `mini@dartsoutro`, `mini@dartsintro_alt1`, `darts_ig_intro_alt1_guy1`, `darts_ig_intro_alt1_guy2`, `darts_ig_intro_alt1_guy1_face`, `darts_ig_intro_alt1_guy2_face`

**Models and props** (4) - `prop_dart_1`, `prop_dart_2`, `prop_dart_bd_cab_01`, `prop_target_bull`

**Audio banks** (3) - `SCRIPT\DARTS`, `SCRIPT\FAMILY1_2`, `HUD_AWARDS`

**Sounds** (15) - `MP_CELEB_SCREEN_SCENE`, `DARTS_HIT_BOARD_MASTER`, `HUD_AWARDS`, `DARTS_THROW_DART_MASTER`, `WIN`, `LOSER`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `GOLF_NEW_RECORD`, `DARTS_HIT_DART_MASTER`, `DARTS_HIT_BULLSEYE_MASTER`, `DARTS_HIT_WALL_MASTER`, `DARTS_SCORE_TRIPLE_MASTER`, `DARTS_SCORE_DOUBLE_MASTER`, `DARTS_HIT_WIRE_MASTER`

**Scaleform movies** (10) - `RESET_MOVIE`, `STRING`, `ADD_DARTS_SCORE`, `SET_PLAYER_HIGHLIGHT`, `SET_PLAYER_SETS_AND_LEGS`, `SET_DARTS_PLAYER_NAMES`, `CLEAR_SCORES`, `SET_CREW_TAG`, `instructional_buttons`, `darts_scoreboard`

**Texture dicts** (1) - `Darts`

**Text labels** (4) - `SUMMARY`, `NULL`, `WINNER`, `DARTS`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (62), `PLAYER_PED_ID` (58), `NETWORK_GET_PLAYER_INDEX` (49), `IS_PED_INJURED` (43), `INT_TO_PARTICIPANTINDEX` (43), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (29), `GET_RANDOM_FLOAT_IN_RANGE` (28), `CLEAR_HELP` (22), `GET_RANDOM_INT_IN_RANGE` (22), `SET_CAM_ACTIVE` (22), `TASK_SYNCHRONIZED_SCENE` (22), `GET_GAME_TIMER` (20), `SET_BIT` (20), `CLEAR_PRINTS` (16), `IS_SCREEN_FADED_OUT` (15), `TASK_PLAY_ANIM` (14), `ROUND` (13), `SET_PLAYER_INVISIBLE_LOCALLY` (12), `PLAY_SOUND_FROM_COORD` (12), `DO_SCREEN_FADE_IN` (11), `RENDER_SCRIPT_CAMS` (11), `DESTROY_CAM` (11), `GET_PLAYER_PED` (10), `SET_ENTITY_COORDS` (10), `IS_PAUSE_MENU_ACTIVE` (10), `CREATE_CAMERA_WITH_PARAMS` (10), `IS_CAM_ACTIVE` (10), `DOES_CAM_EXIST` (9), `SET_PLAYER_CONTROL` (9), `GET_PLAYER_NAME` (9)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-1.5f` x32 · `1.5f` x13 · `0.5f` x9 · `-2.4f` x8 · `-0.7744f` x6 · `0.1f` x6 · `-0.4f` x4 · `-1.7272f` x4 · `0.3f` x3 · `0.995f` x2 · `-3.4831f` x2 · `0.0223f` x2 · `60.6925f` x2 · `-0.3f` x2 · `-2.6f` x2 · `0.02f` x2 · `-0.1f` x2 · `0.66f` x2 · `0.33f` x2 · `-0.0375f` x1 · `1991.159f` x1 · `3045.976f` x1 · `46.2151f` x1 · `1.6f` x1

## Other strings

Literals whose consuming native was not classified:

`DARTS_INSTR_W`, `DARTS_INSTR_B`, `DARTS_END_QT`, `DARTS_AIM_HLP`, `DARTS_SHT_USE`, `Darts`, `DARTS_SHT_CLCK`, `DEFAULT_ANIMATED_CAMERA`, `DARTS_WINP`, `DARTS_CLOCK`, `Current client is waiting for other client to finish throwing`, `DARTS_FST_HLP`, `XPT_DARTS`, `Dart_Reticules`, `DARTS_STD_HLP`, `DARTS_REMAIN`, `DARTS_WINNER`, `DARTS_THROW`, `DARTS_AIM`, `DARTS_ENEMIES`, `MN_DART`, `DARTS_TIOT`, `[AM_DARTS] current client is THROWING`, `Waiting for other client to get to DARTS_MPWAIT_TURN_CHANGE`, `Current client is waiting for other client to throw`, `Waiting for other client to get to DARTS_MPTHROW_TURN_CHANGE`, `<C>`, `</C>`, `~s~`, `DARTS_FIRST`

---

Source: `decompiled_scripts/am_darts.c`
