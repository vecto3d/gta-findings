# darts.c

Minigames script. 7 anim dicts; 19 models; 10 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 25,435 |
| Functions | 515 (147 unique, 368 shared) |
| Unique lines | 10,718 (42.1% of file) |

## Assets

**Animation dictionaries** (7) - `mini@dartsoutro`, `mini@dartsintro`, `mini@dartsintro_alt1`, `facials@gen_female@variations@happy`, `facials@p_m_zero@variations@happy`, `facials@p_m_one@variations@happy`, `facials@p_m_two@variations@happy`

**Animations** (9) - `mini@dartsoutro`, `mini@dartsintro`, `mini@dartsintro_alt1`, `darts_ig_intro_guy1`, `darts_ig_intro_guy2`, `darts_ig_intro_guy1_face`, `darts_ig_intro_alt1_guy1`, `darts_ig_intro_alt1_guy2`, `darts_ig_intro_alt1_guy1_face`

**Models and props** (19) - `prop_dart_bd_cab_01`, `a_f_m_salton_01`, `a_f_o_salton_01`, `prop_dart_1`, `a_m_y_vinewood_01`, `a_m_y_vinewood_03`, `a_m_y_vinewood_04`, `a_m_y_stlat_01`, `a_m_y_stwhi_02`, `prop_dart_2`, `prop_target_bull`, `A_F_M_SALTON_01_WHITE_FULL_03`, `A_F_M_SALTON_01_WHITE_FULL_02`, `A_F_M_SALTON_01_WHITE_FULL_01`, `G_M_Y_LOST_01_BLACK_FULL_01`, `G_M_Y_LOST_02_LATINO_FULL_01`, `G_M_Y_LOST_01_BLACK_FULL_02`, `G_M_Y_LOST_02_LATINO_FULL_02`, `G_M_Y_LOST_01_WHITE_FULL_01`

**Audio banks** (2) - `SCRIPT\DARTS`, `SCRIPT\FAMILY1_2`

**Sounds** (24) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `NAV_UP_DOWN`, `DARTS_HIT_BOARD_MASTER`, `HUD_MINI_GAME_SOUNDSET`, `DARTS_THROW_DART_MASTER`, `HUD_AWARDS`, `LEADERBOARD_SCENE`, `NAV_LEFT_RIGHT`, `CAM_PAN_DARTS`, `TENNIS_POINT_WON`, `OTHER_TEXT`, `LOOSE_MATCH`, `YES`, `NO`, `SELECT`, `HUD_FRONTEND_MP_SOUNDSET`, `DARTS_SCOREBOARD_MASTER`, `DARTS_HIT_DART_MASTER`, `DARTS_HIT_BULLSEYE_MASTER`, `DARTS_HIT_WALL_MASTER`, `DARTS_SCORE_TRIPLE_MASTER`, `DARTS_SCORE_DOUBLE_MASTER`, `DARTS_HIT_WIRE_MASTER`, `OK`

**Scaleform movies** (10) - `CLEAR_ALL_SLOTS`, `CLEAR_SCORES`, `ADD_DARTS_SCORE`, `SET_PLAYER_SETS_AND_LEGS`, `RESET_MOVIE`, `STRING`, `TRANSITION_UP`, `SET_PLAYER_HIGHLIGHT`, `SET_DARTS_PLAYER_NAMES`, `darts_scoreboard`

**Texture dicts** (2) - `Darts`, `ShopUI_Title_Darts`

**Text labels** (20) - `MICHAEL`, `FRANKLIN`, `TREVOR`, `RAYMOND`, `JOHAN`, `STAN`, `VINCE`, `KRISTY`, `MARLENE`, `LORIE`, `SHELLEY`, `NUMBER`, `LAMAR`, `JIMMY`, `RANDOM`, `NULL`, `CMSW`, `GRID`, `COVERED`, `DARTS`

**Scenarios** (2) - `WORLD_HUMAN_HANG_OUT_STREET`, `WORLD_HUMAN_STAND_IMPATIENT`

**Decorators** (1) - `Darts_name`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (210), `IS_PED_INJURED` (45), `CLEAR_BIT` (43), `IS_STRING_NULL_OR_EMPTY` (35), `PLAYER_PED_ID` (34), `GET_RANDOM_FLOAT_IN_RANGE` (30), `GET_RANDOM_INT_IN_RANGE` (26), `SET_CAM_ACTIVE` (26), `LEADERBOARDS2_READ_GET_ROW_DATA_INT` (24), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (23), `DOES_ENTITY_EXIST` (22), `IS_CONTROL_JUST_PRESSED` (21), `IS_CONTROL_PRESSED` (21), `GET_GAME_TIMER` (20), `CLEAR_HELP` (19), `PLAY_SOUND_FRONTEND` (17), `ARE_STRINGS_EQUAL` (17), `SET_CAM_ACTIVE_WITH_INTERP` (15), `LEADERBOARDS2_READ_GET_ROW_DATA_FLOAT` (14), `LEADERBOARDS2_READ_GET_ROW_DATA_INFO` (13), `PLAY_SOUND_FROM_COORD` (13), `PLAYER_ID` (12), `CREATE_CAMERA_WITH_PARAMS` (12), `TASK_SYNCHRONIZED_SCENE` (12), `SET_ENTITY_COORDS` (12), `IS_USING_KEYBOARD_AND_MOUSE` (12), `LEADERBOARDS2_READ_GET_ROW_DATA_END` (12), `CLEAR_PED_TASKS` (11), `BEGIN_SCALEFORM_MOVIE_METHOD` (11), `END_SCALEFORM_MOVIE_METHOD` (11)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-1.5f` x8 · `0.1f` x6 · `0.25f` x5 · `0.5f` x2 · `0.337842f` x2 · `-0.243051f` x2 · `-0.329731f` x2 · `3.783146f` x2 · `0.95f` x2 · `0.99f` x2 · `0.02f` x2 · `-0.1f` x2 · `0.8f` x2 · `-0.8f` x2 · `-2.4f` x2 · `-1.7272f` x2 · `-0.0375f` x1 · `0.7792f` x1 · `-1.138f` x1 · `0.1814f` x1 · `0.55f` x1 · `0.85f` x1 · `0.995f` x1 · `-0.0301f` x1

## Other strings

Literals whose consuming native was not classified:

`SCLB_C_RANK`, `Mission`, `SCLB_C_VEH`, `GameType`, `SCLB_C_KILLS`, `SCLB_C_BL`, `SCLB_C_WINS`, `SCLB_C_SCORE`, `SCLB_C_TIME`, `SCLB_C_WLRAT`, `Type`, `Location`, `SCLB_C_RT`, `SCLB_C_LOSES`, `SCLB_C_DEATH`, `WeaponId`, `SCLB_C_MEDAL1`, `SCLB_C_MEDAL2`, `SCLB_C_MEDAL3`, `DARTS_INSTR_W`, `DARTS_INSTR_B`, `PS_TITLE`, `Darts`, `Laps`, `StreetRace`, `DARTS_SHT_USE`, `DARTS_LEGD`, `DEFAULT_ANIMATED_CAMERA`

---

Source: `decompiled_scripts/darts.c`
