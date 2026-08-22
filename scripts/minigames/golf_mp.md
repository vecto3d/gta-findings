# golf_mp.c

Minigames script. 17 anim dicts; 13 models; 50 scaleforms; 2 particle effects.

| | |
|---|---|
| Category | Minigames |
| Total lines | 176,229 |
| Functions | 2,510 (696 unique, 1,814 shared) |
| Unique lines | 23,785 (13.5% of file) |

## Assets

**Animation dictionaries** (17) - `mini@golf`, `mini@golfreactions@trevor@clubs`, `mini@golfclub_bag`, `mini@golfreactions@michael@clubs`, `mini@golfreactions@franklin@putter`, `mini@golfreactions@franklin@clubs`, `mini@golfclubhouse`, `facials@p_m_zero@variations@happy`, `mini@golfreactions@michael@putter`, `mini@golfreactions@trevor@putter`, `mini@golfreactions@generic@`, `reaction@shove`, `facials@p_m_one@variations@happy`, `facials@p_m_two@variations@happy`, `mini@golfhole_preview`, `amb@world_human_golf_player@male@base`, `amb@world_human_golf_player@male@idle_a`

**Animations** (74) - `base`, `idle_a`, `idle_b`, `idle_c`, `react_win_club_01_michael`, `react_win_club_02_michael`, `react_win_club_03_michael`, `react_win_club_01_franklin`, `react_win_club_02_franklin`, `react_win_club_03_franklin`, `react_win_club_01_trevor`, `react_win_club_02_trevor`, `putt_2_wedge`, `wedge_2_putt`, `putt_2_iron`, `iron_2_putt`, `wedge_2_iron`, `iron_2_wedge`, `iron_2_wood`, `wood_2_iron`, `wood_2_wedge`, `wedge_2_wood`, `Wood_shuffle`, `Iron_shuffle`, `Wedge_shuffle`, `Putt_shuffle`, `mini@golfai`, `putt_approach_no_ball`, `reaction@shove`, `shoved_front`, `react_lose_putter_01_michael`, `react_lose_putter_02_michael`, `react_lose_putter_03_michael`, `react_win_putter_01_michael`, `react_win_putter_02_michael`, `react_win_putter_03_michael`, `react_lose_club_01_michael`, `react_lose_club_02_michael`, `react_lose_club_03_michael`, `react_lose_putter_01_franklin_frank`, `react_lose_putter_02_franklin_frank`, `react_lose_putter_03_franklin_frank`, `react_win_putter_01_franklin_frank`, `react_win_putter_02_franklin_frank`, `react_win_putter_03_franklin_frank`, `react_lose_club_01_franklin`, `react_lose_club_02_franklin`, `react_lose_club_03_franklin`, `react_lose_putter_01_trevor`, `react_lose_putter_02_trevor`, `react_lose_putter_03_trevor`, `react_win_putter_01_trevor`, `react_win_putter_02_trevor`, `react_win_putter_03_trevor`, `react_lose_club_01_trevor`, `react_lose_club_02_trevor`, `react_lose_club_03_trevor`, `react_win_club_03_trevor`, `putt_react_bad_01`, `putt_react_bad_02` ...

**Models and props** (13) - `prop_golfflag`, `prop_golf_ball`, `prop_golf_bag_01b`, `prop_golf_tee`, `prop_golf_marker_01`, `SET_DATA_SLOT`, `prop_golf_putter_01`, `prop_golf_pitcher_01`, `prop_golf_wood_01`, `prop_golf_iron_01`, `caddy`, `a_m_y_golfer_01`, `a_m_m_golfer_01`

**Audio banks** (3) - `GOLF_I`, `GOLF_2`, `GOLF_3`

**Sounds** (28) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `MP_CELEB_SCREEN_SCENE`, `HUD_AWARDS`, `GOLF_FLY_CAM`, `MP_JOB_CHANGE_RADIO_MUTE`, `GOLF_TRANQUIL`, `SELECT`, `QUIT_WHOOSH`, `HUD_MINI_GAME_SOUNDSET`, `GOLF_BALL_IMPACT_FLAG_MASTER`, `SwingSpeed`, `HIGHLIGHT`, `GOLF_HUD_HOLE_IN_ONE_MASTER`, `GOLF_EAGLE`, `GOLF_BIRDIE`, `GOLF_NEW_RECORD`, `OTHER_TEXT`, `GOLF_BALL_CUP_MASTER`, `GOLF_BALL_IN_WATER_MASTER`, `GOLF_HUD_SCORECARD_MASTER`, `GOLF_BALL_ROLL_PUTT_MASTER`, `GOLF_BALL_CUP_MISS_MASTER`, `GOLF_BALL_IMPACT_LEAVES_MASTER`, `GOLF_FORWARD_SWING_PERFECT_VB_MASTER`, `GOLF_FORWARD_SWING_VB_MASTER`, `NAV_UP_DOWN`, `NAV_LEFT_RIGHT`, `HIGHLIGHT_NAV_UP_DOWN`

**Scaleform movies** (50) - `STRING`, `NUMBER`, `ADD_WINNER_TO_WALL`, `ADD_BACKGROUND_TO_WALL`, `ADD_REP_POINTS_AND_RANK_BAR_TO_WALL`, `ADD_MISSION_RESULT_TO_WALL`, `ADD_POSITION_TO_WALL`, `CREATE_STAT_WALL`, `SET_DISPLAY`, `SHARD_ANIM_OUT`, `instructional_buttons`, `COURSE_PAR`, `SET_SCOREBOARD_TITLE`, `golf`, `golf_floating_ui`, `MP_BIG_MESSAGE_FREEMODE`, `MIDSIZED_MESSAGE`, `DPAD_SURV`, `v`, `TRANSITION_UP`, `SET_CLEAR_SPACE`, `SET_MAX_WIDTH`, `SET_DATA_SLOT_EMPTY`, `TOGGLE_MOUSE_BUTTONS`, `SET_DATA_SLOT`, `DRAW_INSTRUCTIONAL_BUTTONS`, `SET_BACKGROUND_COLOUR`, `SWING_METER_TRANSITION_OUT`, `SWING_METER_TRANSITION_IN`, `SWING_METER_POSITION`, `SWING_METER_SET_MARKER`, `SWING_METER_SET_TARGET`, `SWING_METER_SET_FILL`, `SET_SCOREBOARD_SLOT`, `SET_PLAYERCARD_HEADSET`, `SET_PLAYERCARD_SLOT`, `SET_DISTANCE`, `SET_SWING_DISTANCE`, `SET_SWING_DISPLAY`, `GOLF_WIND_PLUS`, `SHOT_NUM`, `SET_STRENGTH`, `STRENGTH_PER`, `SET_HEIGHT`, `SET_PIN_DISTANCE`, `CLEAR_PLAYERCARD_SLOT`, `CLEAR_SCOREBOARD_SLOT`, `SET_HOLE_DISPLAY`, `GOLF_HOLE_NUM`, `GOLF_PAR_NUM`

**Particle effects** (2) - `scr_golf_landing_water`, `scr_golf_ball_trail`

**Text labels** (25) - `GAME`, `RAIN`, `HOLEINONE`, `EXTRASUNNY`, `DIST`, `NULL`, `QUIT`, `MP_SPINLOADING`, `NAV1`, `NAV2`, `OOB`, `THUNDER`, `OVERCAST`, `EAGLE2`, `EAGLE`, `BIRDIE`, `PAR`, `BOGEY`, `BOGEY2`, `BOGEY3`, `BOGEY4`, `BOGEY5`, `GOLF`, `GIR`, `FIR`

**Vehicle mods** (1) - `caddy`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (138), `VDIST2` (134), `DOES_ENTITY_EXIST` (129), `IS_ENTITY_PLAYING_ANIM` (111), `GET_ENTITY_COORDS` (94), `PARTICIPANT_ID_TO_INT` (91), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (84), `DOES_CAM_EXIST` (62), `ARE_STRINGS_EQUAL` (59), `BEGIN_TEXT_COMMAND_SCALEFORM_STRING` (56), `END_TEXT_COMMAND_SCALEFORM_STRING` (56), `BEGIN_SCALEFORM_MOVIE_METHOD` (55), `END_SCALEFORM_MOVIE_METHOD` (55), `FLOOR` (55), `IS_ENTITY_DEAD` (42), `PLAYER_ID` (40), `INT_TO_PARTICIPANTINDEX` (40), `GET_ENTITY_ANIM_CURRENT_TIME` (35), `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME` (34), `IS_STRING_NULL_OR_EMPTY` (33), `ABSF` (33), `GET_CONTROL_INSTRUCTIONAL_BUTTONS_STRING` (31), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (31), `NETWORK_GET_PLAYER_INDEX` (30), `GET_GAME_TIMER` (29), `LEADERBOARDS_WRITE_ADD_COLUMN` (29), `IS_PED_INJURED` (27), `DESTROY_CAM` (26), `DISABLE_CONTROL_ACTION` (25), `VDIST` (24)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x17 · `0.5f` x14 · `0.25f` x13 · `0.1f` x13 · `0.05f` x13 · `29.75f` x13 · `25.75f` x12 · `0.15f` x11 · `0.3f` x8 · `18.75f` x8 · `1.85f` x8 · `3.5f` x8 · `25.25f` x6 · `22.75f` x6 · `38.5f` x6 · `0.75f` x5 · `0.1601f` x5 · `0.33f` x4 · `37.5f` x4 · `36.25f` x4 · `26.75f` x4 · `58.25f` x4 · `33.5f` x4 · `33.25f` x4

## Other strings

Literals whose consuming native was not classified:

`_BAD`, `PAR_4`, `FLY_TITLE`, `swing_react_good_01_cam`, `GOLF_QUIT`, `GolfFlags`, `DPAD_FRIEND`, `INST_QUIT`, `react_win_club_01_cam`, `react_win_club_02_cam`, `react_win_club_03_cam`, `DIST_METER`, `CLUB_WOOD`, `CLUB_IRON`, `CLUB_WEDGE`, `CLUB_PUTTER`, `STYLE_POWER`, `STYLE_APPROACH`, `STYLE_PUNCH`, `_GOOD`, `INST_SCORECARD`, `GOLF_STAT_HELP`, `LIE_UNPLAYABLE`, `putt_react_good_01_cam`, `react_`, `good_0`, `bad_0`

---

Source: `decompiled_scripts/golf_mp.c`
