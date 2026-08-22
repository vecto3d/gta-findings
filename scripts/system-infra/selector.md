# selector.c

System and infrastructure script. 16 scaleforms.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 108,819 |
| Functions | 909 (97 unique, 812 shared) |
| Unique lines | 5,312 (4.9% of file) |

## Assets

**Sounds** (12) - `SWITCH_TO_MP_SCENE`, `MP_MENU_SCENE`, `PLAYER_SWITCH_RED_ALERT_SCENE`, `SPECIAL_ABILITY_SOUNDSET`, `PLAYER_SWITCH_WHITE_ALERT_SCENE`, `CHARACTER_CHANGE_CHARACTER_01_MASTER`, `CHARACTER_CHANGE_DPAD_DOWN_MP_MASTER`, `CHARACTER_CHANGE_DPAD_DOWN_MASTER`, `SwitchRedWarning`, `SwitchWhiteWarning`, `CHARACTER_SELECT`, `HUD_FRONTEND_DEFAULT_SOUNDSET`

**Scaleform movies** (16) - `SET_SWITCH_VISIBLE`, `SET_PLAYER_SELECTED`, `SET_SWITCH_SLOT`, `SET_PLAYER_DAMAGE`, `SET_SWITCH_HINTED_ALL`, `SET_SWITCH_COUNTER_ALL`, `SET_MULTIPLAYER_HEAD`, `director`, `SET_MP_LABEL`, `SET_STATS_LABELS`, `TR_RANKNUM`, `PCARD_MENTAL_STATE`, `FADE_BAR_OUT`, `PLAYER_SWITCH_PROLOGUE`, `PLAYER_SWITCH`, `PLAYER_SWITCH_STATS_PANEL`

**Text labels** (15) - `~INPUT_REPLAY_START_STOP_RECORDING~`, `~INPUT_SAVE_REPLAY_CLIP~`, `MP_SPINLOADING`, `NULL`, `REC_FEED_WAR`, `REC_FEED_5`, `REC_FEED_4`, `REC_FEED_3`, `REC_FEED_2`, `REC_FEED_1`, `REC_FEED_0`, `~INPUT_REPLAY_START_STOP_RECORDING_SECONDARY~`, `REC_FEED_6`, `REC_FEED_7`, `ERROR`

**Scripts launched** (7) - `MainTransition`, `creator`, `appcamera`, `golf`, `franklin0`, `am_mp_property_int`, `startup_positioning`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (70), `SET_BIT` (46), `NETWORK_IS_GAME_IN_PROGRESS` (46), `PLAYER_ID` (46), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (44), `GET_GAME_TIMER` (42), `CLEAR_BIT` (39), `HIDE_HUD_COMPONENT_THIS_FRAME` (36), `END_SCALEFORM_MOVIE_METHOD` (27), `BEGIN_SCALEFORM_MOVIE_METHOD` (26), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_BOOL` (24), `SET_WARNING_MESSAGE_WITH_HEADER` (22), `IS_PLAYER_SWITCH_IN_PROGRESS` (17), `DISABLE_CONTROL_ACTION` (17), `GET_NETWORK_TIME` (16), `IS_SCREEN_FADED_OUT` (13), `SET_INPUT_EXCLUSIVE` (12), `ANIMPOSTFX_IS_RUNNING` (12), `ANIMPOSTFX_PLAY` (12), `SET_AUDIO_FLAG` (11), `DO_SCREEN_FADE_IN` (10), `IS_DISABLED_CONTROL_PRESSED` (9), `TO_FLOAT` (9), `BEGIN_TEXT_COMMAND_THEFEED_POST` (9), `IS_PED_INJURED` (9), `IS_SYSTEM_UI_BEING_DISPLAYED` (9), `GET_IS_LOADING_SCREEN_ACTIVE` (9), `SET_PED_COMPONENT_VARIATION` (9), `ANIMPOSTFX_STOP` (8), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x3 · `0.67f` x2 · `1.75f` x2 · `0.3f` x1 · `-11.9823f` x1 · `-14.7217f` x1 · `499.0583f` x1

## Other strings

Literals whose consuming native was not classified:

`HUD_CONNPROB`, `HUD_RETURNSP`, `AllowRadioOverScreenFade`, `ActivateSwitchWheelAudio`, `SwitchHUDMichaelIn`, `SwitchHUDFranklinIn`, `SwitchHUDTrevorIn`, `SwitchHUDIn`, `GTA Online`, `SwitchOpenMichaelIn`, `SwitchShortMichaelIn`, `SwitchHUDMichaelOut`, `SwitchOpenFranklinIn`, `SwitchShortFranklinIn`, `SwitchHUDFranklinOut`, `SwitchOpenTrevorIn`, `SwitchShortTrevorIn`, `SwitchHUDTrevorOut`, `SwitchHUDOut`, `AM_H_EDIT_3`, `AM_H_EDIT_4`, `MainTransition`, `selector_ui_headshot`, `PM_QUIT_WARN`, `PM_QUIT_WARN5`, `PM_QUIT_WARN3`, `FMEVNT_SUREQUIT`, `HUD_PERM`, `T_Bv`

---

Source: `decompiled_scripts/selector.c`
