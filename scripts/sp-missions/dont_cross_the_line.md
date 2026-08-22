# dont_cross_the_line.c

SP missions script. 11 scaleforms.

| | |
|---|---|
| Category | SP missions |
| Total lines | 8,251 |
| Functions | 223 (100 unique, 123 shared) |
| Unique lines | 3,576 (43.3% of file) |

## Assets

**Audio banks** (1) - `DLC_EXEC1/OFFICE_BOARDROOM`

**Sounds** (25) - `DLC_EXEC_ARC_MAC_SOUNDS`, `Music_Game_Over`, `Background`, `X`, `Y`, `321`, `DLC_Exec_Arc_Mac_Playing_Game_Scene`, `Insert_Coin`, `Cancel`, `Turning`, `FadeOut`, `Game_Over_Blink`, `Music_Win`, `Trail_1`, `Trail_2`, `Trail_3`, `Trail_4`, `Turn`, `Turn_NPC`, `Crash`, `Crash_NPC`, `Go`, `Ready`, `Degenatron_Logo`, `Degenatron_Star`

**Scaleform movies** (11) - `SET_CENTRAL_MESSAGE`, `HIDE_LOBBY`, `INIT_LOBBY`, `SET_MICS`, `UPDATE_LOBBY`, `HIDE_HUD`, `SHOW_HUD`, `CLEAR_CENTRAL_MESSAGE`, `HIDE_LOADING_SCREEN`, `SHOW_LOADING_SCREEN`, `dont_cross_the_line`

**Texture dicts** (5) - `LineArcadeMinigame`, `Degenatron_DontCrossTheLine_Home`, `Degenatron_DontCrossTheLine_Game`, `Tail`, `HeadPixel`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (49), `CLEAR_BIT` (46), `INT_TO_PARTICIPANTINDEX` (39), `NETWORK_IS_PARTICIPANT_ACTIVE` (36), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (31), `PLAYER_ID` (29), `PLAY_SOUND_FRONTEND` (27), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (17), `HAS_SCALEFORM_MOVIE_LOADED` (14), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (13), `ABSF` (13), `BEGIN_SCALEFORM_MOVIE_METHOD` (11), `END_SCALEFORM_MOVIE_METHOD` (11), `SET_VARIABLE_ON_SOUND` (10), `HAS_SOUND_FINISHED` (9), `STOP_SOUND` (8), `IS_STRING_NULL_OR_EMPTY` (8), `IS_CONTROL_JUST_PRESSED` (7), `NETWORK_GET_NUM_PARTICIPANTS` (6), `GET_SOUND_ID` (6), `NETWORK_IS_GAME_IN_PROGRESS` (5), `IS_PAUSE_MENU_ACTIVE` (5), `TIMESTEP` (5), `DRAW_SPRITE` (4), `IS_CONTROL_PRESSED` (4), `IS_SCREEN_FADED_OUT` (4), `_SEND_TU_SCRIPT_EVENT_NEW` (3), `PARTICIPANT_ID_TO_INT` (3), `IS_STREAM_PLAYING` (3), `STOP_STREAM` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x9 · `0.001f` x5 · `0.003f` x4 · `-0.65f` x2 · `0.65f` x2 · `0.012f` x1

## Other strings

Literals whose consuming native was not classified:

`DCTL_REPLAY`, `DCTL_INSERT`, `DCTL_GAMEOVER`, `DCTL_REPLAYHELP`, `mp_m_freemode_01`, `MP_exec_prizes_015_M`, `MP_exec_prizes_015_F`, `DCTL_WINNERV2`, `DCTL_DRAW`, `DCTL_GAMEHELP`, `Music_Stream`, `DLC_EXEC_ARC_MAC_SOUNDS`, `DCTL_COUNTDOWNGO`, `DCTL_COUNTDOWN3`, `DCTL_COUNTDOWN2`, `DCTL_COUNTDOWN1`, `DCTL_READY`, `DCTL_LOADING`, `DCTL_TITLEHELP`

---

Source: `decompiled_scripts/dont_cross_the_line.c`
