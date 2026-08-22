# tennis_network_mp.c

Minigames script. 1 developer state labels recovered; 11 anim dicts; 6 models; 19 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 149,667 |
| Functions | 1,945 (232 unique, 1,713 shared) |
| Unique lines | 9,940 (6.6% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`Disabling First Person Cam`

## Assets

**Animation dictionaries** (11) - `mini@tennis`, `mini@tennis@female`, `weapons@tennis@male`, `facials@gen_male@base`, `facials@gen_male@variations@happy`, `facials@gen_female@base`, `facials@gen_female@variations@happy`, `mini@triathlon`, `mini@tennisreactions@michael`, `mini@tennistrevor`, `mini@tennisreactions@trevor`

**Animations** (7) - `mini@tennis`, `ready_2_idle`, `idle_2_serve`, `serve`, `idle`, `mini@tennis@female`, `idle_2_ready`

**Models and props** (6) - `prop_tennis_rack_01b`, `prop_tennis_ball`, `SET_WON`, `SET_LOST`, `SET_PT`, `SET_PT_STRAP`

**Audio banks** (2) - `SCRIPT\Tennis`, `SCRIPT\TENNIS_VER2_A`

**Sounds** (18) - `HUD_AWARDS`, `OTHER_TEXT`, `MP_CELEB_SCREEN_SCENE`, `TENNIS_PLYR_SERVE_MASTER`, `TENNIS_PLYR_SMASH_MASTER`, `HUD_MINI_GAME_SOUNDSET`, `TENNIS_POINT_WON`, `TENNIS_SCENE`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `TENNIS_NPC_FOREARM_MASTER`, `TENNIS_NPC_BACKSLICE_MASTER`, `TENNIS_NPC_TOPSPIN_MASTER`, `SELECT`, `CANCEL`, `10_SEC_WARNING`, `TENNIS_MATCH_POINT`, `LOSER`

**Scaleform movies** (19) - `SET_SCOREPANEL`, `SET_SCOREBOARD`, `tennis`, `RESET_MOVIE`, `STRING`, `SWING_METER_SET_FILL`, `SET_PLAYERCARD_HEADSET`, `SET_SCOREBOARD_TITLE`, `SWING_METER_SET_TARGET`, `SET_SCOREBOARD_SLOT`, `SET_PLAYERCARD_SLOT`, `SET_PLAYERCARD_TITLE`, `DISPLAY_SCOREBOARD`, `DISPLAY_PLAYER_CARD`, `SWING_METER_TRANSITION_OUT`, `SWING_METER_TRANSITION_IN`, `SWING_METER_POSITION`, `SWING_METER_SET_APEX_MARKER`, `SWING_METER_SET_MARKER`

**Texture dicts** (2) - `MPHUD`, `ShopUI_Title_Tennis`

**Text labels** (18) - `NUMBER`, `SUMMARY`, `FINISH`, `DEUCE`, `NULL`, `EXTRASUNNY`, `TENNIS`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `LAMAR`, `AMANDA`, `JIMMY`, `WINNER`, `REMATCH`, `ACE`, `ACED`, `FOUL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_PED_INJURED` (49), `PLAYER_ID` (49), `PARTICIPANT_ID_TO_INT` (39), `NETWORK_GET_PLAYER_INDEX` (30), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (26), `PLAY_SOUND_FRONTEND` (26), `DOES_ENTITY_EXIST` (25), `INT_TO_PARTICIPANTINDEX` (24), `GET_GAME_TIMER` (24), `TO_FLOAT` (24), `PLAYER_PED_ID` (24), `BEGIN_SCALEFORM_MOVIE_METHOD` (22), `ROUND` (22), `GET_FRAME_TIME` (18), `END_SCALEFORM_MOVIE_METHOD` (18), `VDIST2` (18), `SET_ENTITY_COORDS` (15), `ARE_STRINGS_EQUAL` (15), `GET_ENTITY_COORDS` (14), `IS_TENNIS_MODE` (14), `IS_ENTITY_PLAYING_ANIM` (14), `PLAY_SOUND_FROM_ENTITY` (14), `DETACH_ENTITY` (13), `RENDER_SCRIPT_CAMS` (13), `GET_HEADING_FROM_VECTOR_2D` (12), `IS_CONTROL_JUST_PRESSED` (12), `TASK_PLAY_ANIM` (11), `NETWORK_GET_PARTICIPANT_INDEX` (11), `NETWORK_GET_PLAYER_INDEX_FROM_PED` (11), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_FLOAT` (11)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x8 · `0.25f` x8 · `1.5f` x5 · `0.9f` x3 · `8.5f` x3 · `0.75f` x3 · `0.33f` x2 · `0.3f` x2 · `0.88f` x2 · `-0.1f` x2 · `-0.127f` x2 · `0.1f` x1 · `0.211f` x1 · `4.113f` x1 · `0.8f` x1 · `0.72f` x1 · `0.4f` x1 · `-769.058f` x1 · `165.294f` x1 · `66.474f` x1 · `-1171.28f` x1 · `-1599.59f` x1 · `3.34f` x1 · `487.5186f` x1

## Other strings

Literals whose consuming native was not classified:

`MATCH_PT`, `CUC_QUIT`, `B4_BNCE`, `mpply_tennis_matches_won`, `mpply_tennis_matches_lost`, `TENNIS_G_WON`, `TENNIS_G_LOST`, `MATCH_PT_STRAP`, `TENNIS_SCR_0`, `TENNIS_SCR_40`, `TEN_SB_PLAIN`, `CUC_MOVEAIM`, `running`, `OOB_TENN`, `<C>`, `~HUD_COLOUR_WHITE~`, `~HUD_COLOUR_RED~`, `</C>`, `~s~`, `TennisServeSet`, `MP_QUITTER`, `XPT_TENNIS`, `TENNIS_QUIT`, `react_ball_out`, `GAME_PT`, `GAME_PT_STRAP`, `BREAK_PT`, `BREAK_PT_STRAP`, `Idle1`, `MinigameTransitionIn`

---

Source: `decompiled_scripts/tennis_network_mp.c`
