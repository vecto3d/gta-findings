# tennis.c

Minigames script. 1 developer state labels recovered; 24 anim dicts; 14 models; 19 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 123,369 |
| Functions | 1,181 (221 unique, 960 shared) |
| Unique lines | 15,418 (12.5% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`Disabling First Person Cam`

## Assets

**Animation dictionaries** (24) - `mini@tennis`, `mini@tennis@female`, `mini@tennisintro_alt1`, `mini@tennisintro`, `mini@triathlon`, `misscommon@response`, `weapons@tennis@male`, `mini@tennisreactions@michael`, `mini@tennisreactions@trevor`, `mini@tennistrevor`, `facials@p_m_zero@base`, `facials@p_m_zero@variations@happy`, `mini@tennisoutro@michael`, `facials@p_m_two@base`, `facials@p_m_two@variations@happy`, `mini@tennisoutro@trevor`, `mini@tennisexit@male`, `mini@tennisexit@female`, `facials@gen_male@base`, `facials@gen_male@variations@happy`, `facials@gen_female@base`, `facials@gen_female@variations@happy`, `mini@tennisoutro@`, `mini@tennisexit@`

**Animations** (16) - `mini@tennis`, `intro_a`, `intro_b`, `idle`, `idle_2_serve`, `serve`, `mini@triathlon`, `idle_e`, `ready_2_idle`, `mini@tennisintro_alt1`, `mini@tennisintro`, `misscommon@response`, `screw_you`, `bring_it_on`, `mini@tennis@female`, `idle_2_ready`

**Models and props** (14) - `prop_tennis_rack_01b`, `prop_vb_34_tencrt_lighting`, `prop_tennis_ball`, `a_f_y_tennis_01`, `a_m_m_tennis_01`, `prop_energy_drink`, `SET_PT`, `SET_PT_STRAP`, `SET_LOST`, `SET_WON`, `A_M_M_TENNIS_01_BLACK_MINI_01`, `A_M_M_TENNIS_01_WHITE_MINI_01`, `A_F_Y_TENNIS_01_BLACK_MINI_01`, `A_F_Y_TENNIS_01_WHITE_MINI_01`

**Audio banks** (2) - `SCRIPT\Tennis`, `SCRIPT\TENNIS_VER2_A`

**Sounds** (25) - `HUD_AWARDS`, `OTHER_TEXT`, `HUD_MINI_GAME_SOUNDSET`, `NAV_UP_DOWN`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `TENNIS_PLYR_SERVE_MASTER`, `TENNIS_POINT_WON`, `TENNIS_SCENE`, `LEADERBOARD_SCENE`, `SELECT`, `QUIT_WHOOSH`, `TENNIS_PLYR_SMASH_MASTER`, `TENNIS_MATCH_POINT`, `HUD_FRONTEND_MP_SOUNDSET`, `NO`, `YES`, `LEADER_BOARD`, `LOSER`, `TENNIS_AMB_SMASH_MASTER`, `TENNIS_NPC_SMASH_MASTER`, `TENNIS_AMB_SERVE_MASTER`, `TENNIS_NPC_SERVE_MASTER`, `TENNIS_PLYR_FOREARM_MASTER`, `LEADERBOARD`, `CANCEL`

**Scaleform movies** (19) - `RESET_MOVIE`, `CLEAR_ALL_SLOTS`, `STRING`, `SET_SCOREPANEL`, `SET_SCOREBOARD`, `SWING_METER_POSITION`, `DISPLAY_SCOREBOARD`, `DISPLAY_PLAYER_CARD`, `SWING_METER_TRANSITION_OUT`, `SWING_METER_TRANSITION_IN`, `SWING_METER_SET_APEX_MARKER`, `SWING_METER_SET_MARKER`, `SET_SCOREBOARD_SLOT`, `SET_SCOREBOARD_TITLE`, `SET_PLAYERCARD_SLOT`, `SET_PLAYERCARD_TITLE`, `SWING_METER_SET_FILL`, `SWING_METER_SET_TARGET`, `tennis`

**Texture dicts** (2) - `MPHUD`, `ShopUI_Title_Tennis`

**Text labels** (25) - `NUMBER`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `DEUCE`, `RANDOM`, `LAMAR`, `AMANDA`, `JIMMY`, `TENNIS`, `NULL`, `NONE`, `EXTRASUNNY`, `ACE`, `ACED`, `FOUL`, `CMSW`, `GRID`, `COVERED`, `FINISH`, `REMATCH`, `TENNISPLAYER3`, `TENNISPLAYER4`, `TENNISPLAYER2`, `TENNISPLAYER1`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (189), `IS_PED_INJURED` (75), `PLAYER_PED_ID` (51), `GET_GAME_TIMER` (51), `DOES_ENTITY_EXIST` (45), `CLEAR_BIT` (40), `PLAY_SOUND_FRONTEND` (37), `IS_STRING_NULL_OR_EMPTY` (34), `GET_HEADING_FROM_VECTOR_2D` (32), `SET_CAM_PARAMS` (28), `GET_ENTITY_COORDS` (26), `GET_RANDOM_FLOAT_IN_RANGE` (26), `BEGIN_SCALEFORM_MOVIE_METHOD` (25), `ARE_STRINGS_EQUAL` (25), `RENDER_SCRIPT_CAMS` (25), `SET_ENTITY_COORDS` (25), `SET_PED_COMPONENT_VARIATION` (25), `PLAYER_ID` (24), `LEADERBOARDS2_READ_GET_ROW_DATA_INT` (24), `REQUEST_ANIM_DICT` (23), `VDIST2` (23), `TO_FLOAT` (23), `SET_ENTITY_HEADING` (22), `END_SCALEFORM_MOVIE_METHOD` (21), `SET_CAM_ACTIVE` (20), `DELETE_OBJECT` (19), `IS_CONTROL_JUST_PRESSED` (18), `TASK_PLAY_ANIM` (18), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (18), `IS_ENTITY_DEAD` (15)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x19 · `0.25f` x13 · `0.33f` x6 · `26.75f` x5 · `1.5f` x5 · `0.66f` x5 · `0.2f` x4 · `0.75f` x4 · `0.3f` x4 · `0.65f` x3 · `-0.1f` x2 · `-0.127f` x2 · `-0.2f` x2 · `2.925f` x2 · `0.9f` x2 · `0.1f` x2 · `0.88f` x2 · `-0.0375f` x1 · `4.113f` x1 · `-1134.478f` x1 · `-1577.908f` x1 · `3.431f` x1 · `0.15f` x1 · `0.98f` x1

## Other strings

Literals whose consuming native was not classified:

`SCLB_C_RANK`, `Mission`, `SCLB_C_VEH`, `SCLB_C_KILLS`, `GameType`, `SCLB_C_BL`, `SCLB_C_WINS`, `SCLB_C_SCORE`, `SCLB_C_TIME`, `SCLB_C_WLRAT`, `Type`, `Location`, `SCLB_C_RT`, `SCLB_C_LOSES`, `SCLB_C_DEATH`, `WeaponId`, `SCLB_C_MEDAL1`, `SCLB_C_MEDAL2`, `SCLB_C_MEDAL3`, `PS_TITLE`, `MinigameTransitionIn`, `B4_BNCE`, `Laps`, `StreetRace`, `running`, `CUC_QUIT`, `OOB_TENN`, `HUD_MG_TENNIS`

---

Source: `decompiled_scripts/tennis.c`
