# golf.c

Minigames script. 17 anim dicts; 12 models; 41 scaleforms; 2 particle effects.

| | |
|---|---|
| Category | Minigames |
| Total lines | 151,435 |
| Functions | 2,066 (600 unique, 1,466 shared) |
| Unique lines | 23,141 (15.3% of file) |

## Assets

**Animation dictionaries** (17) - `mini@golfclubhouse`, `mini@golf`, `mini@golfreactions@trevor@clubs`, `mini@golfclub_bag`, `mini@golfreactions@michael@clubs`, `mini@golfreactions@franklin@putter`, `mini@golfreactions@franklin@clubs`, `move_m@golfer@`, `facials@p_m_zero@variations@happy`, `mini@golfreactions@michael@putter`, `mini@golfreactions@trevor@putter`, `mini@golfreactions@generic@`, `facials@p_m_one@variations@happy`, `facials@p_m_two@variations@happy`, `amb@world_human_golf_player@male@base`, `amb@world_human_golf_player@male@idle_a`, `mini@golfhole_preview`

**Animations** (75) - `base`, `mini@golfclubhouse`, `idle_a`, `idle_b`, `idle_c`, `clubhouse_exit_plyr`, `react_win_club_01_michael`, `react_win_club_02_michael`, `react_win_club_03_michael`, `react_win_club_01_franklin`, `react_win_club_02_franklin`, `react_win_club_03_franklin`, `react_win_club_01_trevor`, `react_win_club_02_trevor`, `putt_2_wedge`, `wedge_2_putt`, `putt_2_iron`, `iron_2_putt`, `wedge_2_iron`, `iron_2_wedge`, `iron_2_wood`, `wood_2_iron`, `wood_2_wedge`, `wedge_2_wood`, `Wood_shuffle`, `Iron_shuffle`, `Wedge_shuffle`, `Putt_shuffle`, `mini@golfai`, `putt_approach_no_ball`, `mood_happy_1`, `react_lose_putter_01_michael`, `react_lose_putter_02_michael`, `react_lose_putter_03_michael`, `react_win_putter_01_michael`, `react_win_putter_02_michael`, `react_win_putter_03_michael`, `react_lose_club_01_michael`, `react_lose_club_02_michael`, `react_lose_club_03_michael`, `react_lose_putter_01_franklin_frank`, `react_lose_putter_02_franklin_frank`, `react_lose_putter_03_franklin_frank`, `react_win_putter_01_franklin_frank`, `react_win_putter_02_franklin_frank`, `react_win_putter_03_franklin_frank`, `react_lose_club_01_franklin`, `react_lose_club_02_franklin`, `react_lose_club_03_franklin`, `react_lose_putter_01_trevor`, `react_lose_putter_02_trevor`, `react_lose_putter_03_trevor`, `react_win_putter_01_trevor`, `react_win_putter_02_trevor`, `react_win_putter_03_trevor`, `react_lose_club_01_trevor`, `react_lose_club_02_trevor`, `react_lose_club_03_trevor`, `react_win_club_03_trevor`, `putt_react_bad_01` ...

**Models and props** (12) - `a_m_y_golfer_01`, `a_m_m_golfer_01`, `prop_golf_bag_01b`, `caddy`, `prop_golf_ball`, `prop_golfflag`, `prop_golf_tee`, `prop_golf_marker_01`, `prop_golf_putter_01`, `prop_golf_pitcher_01`, `prop_golf_wood_01`, `prop_golf_iron_01`

**Audio banks** (4) - `GOLF_I`, `GOLF_2`, `GOLF_3`, `generic_failed`

**Sounds** (34) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `HUD_MINI_GAME_SOUNDSET`, `HUD_AWARDS`, `SELECT`, `GOLF_FLY_CAM`, `NAV_UP_DOWN`, `GOLF_TRANQUIL`, `NO`, `QUIT_WHOOSH`, `YES`, `GOLF_BALL_IMPACT_FLAG_MASTER`, `SwingSpeed`, `CANCEL`, `LOSER`, `GOLF_HUD_HOLE_IN_ONE_MASTER`, `GOLF_EAGLE`, `GOLF_BIRDIE`, `GOLF_NEW_RECORD`, `OTHER_TEXT`, `ScreenFlash`, `MissionFailedSounds`, `HIGHLIGHT`, `GOLF_HUD_SCORECARD_MASTER`, `GOLF_BALL_ROLL_PUTT_MASTER`, `GOLF_BALL_CUP_MISS_MASTER`, `GOLF_BALL_CUP_MASTER`, `GOLF_BALL_IN_WATER_MASTER`, `GOLF_BALL_IMPACT_LEAVES_MASTER`, `GOLF_FORWARD_SWING_PERFECT_VB_MASTER`, `GOLF_FORWARD_SWING_VB_MASTER`, `NAV_LEFT_RIGHT`, `HIGHLIGHT_NAV_UP_DOWN`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Speech contexts** (1) - `REDOCastro`

**Scaleform movies** (41) - `STRING`, `TRANSITION_UP`, `SET_DISPLAY`, `TOGGLE_MOUSE_BUTTONS`, `golf`, `golf_floating_ui`, `MP_BIG_MESSAGE_FREEMODE`, `MIDSIZED_MESSAGE`, `SHARD_ANIM_OUT`, `CLEAR_PLAYERCARD_SLOT`, `CLEAR_SCOREBOARD_SLOT`, `instructional_buttons`, `SET_CLEAR_SPACE`, `SET_MAX_WIDTH`, `SET_DATA_SLOT_EMPTY`, `SET_DATA_SLOT`, `DRAW_INSTRUCTIONAL_BUTTONS`, `SET_BACKGROUND_COLOUR`, `SHOW_CENTERED_MP_MESSAGE_LARGE`, `SET_SCOREBOARD_SLOT`, `SET_PLAYERCARD_SLOT`, `SET_HOLE_DISPLAY`, `GOLF_HOLE_NUM`, `GOLF_PAR_NUM`, `SET_DISTANCE`, `SET_SWING_DISTANCE`, `SET_STRENGTH`, `STRENGTH_PER`, `SET_HEIGHT`, `SET_PIN_DISTANCE`, `SWING_METER_TRANSITION_OUT`, `SWING_METER_TRANSITION_IN`, `SWING_METER_POSITION`, `SWING_METER_SET_MARKER`, `SWING_METER_SET_TARGET`, `SWING_METER_SET_FILL`, `SET_SWING_DISPLAY`, `GOLF_WIND_PLUS`, `SHOT_NUM`, `COURSE_PAR`, `SET_SCOREBOARD_TITLE`

**Particle effects** (2) - `scr_golf_landing_water`, `scr_golf_ball_trail`

**Texture dicts** (1) - `ShopUI_Title_GolfShop`

**Text labels** (25) - `GAME`, `HOLEINONE`, `DIST`, `NULL`, `QUIT`, `GIR`, `FIR`, `NAV1`, `NAV2`, `OOB`, `EAGLE2`, `EAGLE`, `BIRDIE`, `PAR`, `BOGEY`, `BOGEY2`, `BOGEY3`, `BOGEY4`, `BOGEY5`, `GOLF`, `RAIN`, `THUNDER`, `OVERCAST`, `CIVFEMALE`, `CIVMALE`

**Waypoint recordings** (1) - `golf_intro`

**Relationship groups** (1) - `golferRelGroup`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (138), `VDIST2` (135), `DOES_ENTITY_EXIST` (126), `IS_ENTITY_PLAYING_ANIM` (111), `GET_ENTITY_COORDS` (94), `PLAYER_ID` (85), `DOES_CAM_EXIST` (76), `ARE_STRINGS_EQUAL` (62), `IS_ENTITY_DEAD` (56), `FLOOR` (52), `DESTROY_CAM` (39), `DISABLE_CONTROL_ACTION` (37), `BEGIN_SCALEFORM_MOVIE_METHOD` (37), `END_SCALEFORM_MOVIE_METHOD` (36), `GET_ENTITY_ANIM_CURRENT_TIME` (35), `GET_CONTROL_INSTRUCTIONAL_BUTTONS_STRING` (32), `GET_SHOP_PED_APPAREL_FORCED_COMPONENT_COUNT` (31), `GET_FORCED_COMPONENT` (31), `ABSF` (31), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (31), `DOES_SHOP_PED_APPAREL_HAVE_RESTRICTION_TAG` (30), `SET_ENTITY_COORDS` (29), `LEADERBOARDS_WRITE_ADD_COLUMN` (29), `IS_PED_INJURED` (27), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_FLOAT` (24), `PLAY_SOUND_FRONTEND` (23), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (23), `IS_POINT_IN_ANGLED_AREA` (23), `DISPLAY_RADAR` (22), `SET_CAM_COORD` (22)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x17 · `0.1f` x13 · `0.05f` x13 · `0.25f` x13 · `29.75f` x13 · `0.5f` x13 · `25.75f` x12 · `0.15f` x10 · `1.85f` x8 · `18.75f` x8 · `3.5f` x8 · `0.3f` x7 · `25.25f` x6 · `22.75f` x6 · `38.5f` x6 · `0.1601f` x5 · `-1371.909f` x4 · `56.286f` x4 · `52.6365f` x4 · `-1389.404f` x4 · `48.943f` x4 · `52.6259f` x4 · `308.7762f` x4 · `0.33f` x4

## Other strings

Literals whose consuming native was not classified:

`_BAD`, `FLY_TITLE`, `swing_react_good_01_cam`, `PAR_4`, `GOLF_QUIT`, `GolfFlags`, `vest_shirt`, `open_collar`, `INST_QUIT`, `DIST_METER`, `FLY_INTRO2`, `react_win_club_01_cam`, `react_win_club_02_cam`, `react_win_club_03_cam`, `CLUB_WOOD`, `CLUB_IRON`, `CLUB_WEDGE`, `CLUB_PUTTER`, `STYLE_POWER`, `STYLE_APPROACH`, `STYLE_PUNCH`, `_GOOD`, `MinigameTransitionIn`, `tie`, `INST_SCORECARD`, `GOLF_NEW_RECORD`, `GOLF_STAT_HELP`, `LIE_UNPLAYABLE`

---

Source: `decompiled_scripts/golf.c`
