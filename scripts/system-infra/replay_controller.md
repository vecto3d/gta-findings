# replay_controller.c

System and infrastructure script. 11 scaleforms.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 112,324 |
| Functions | 824 (90 unique, 734 shared) |
| Unique lines | 3,849 (3.4% of file) |

## Assets

**Audio banks** (1) - `generic_failed`

**Sounds** (13) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `MissionFailedSounds`, `YES`, `NO`, `REPLAY_SCREEN_SCENE`, `SKIP`, `RETRY`, `RESTART`, `TextHit`, `OK`, `EXIT`, `ScreenFlash`, `Bed`

**Scaleform movies** (11) - `MP_BIG_MESSAGE_FREEMODE`, `INSTRUCTIONAL_BUTTONS`, `SHOW_SHARD_CENTERED_MP_MESSAGE_LARGE`, `UPDATE_MESSAGE`, `TRANSITION_UP`, `CLEAR_ALL`, `SET_CLEAR_SPACE`, `SET_BACKGROUND_COLOUR`, `TOGGLE_MOUSE_BUTTONS`, `SET_DATA_SLOT`, `DRAW_INSTRUCTIONAL_BUTTONS`

**Text labels** (1) - `NULL`

**Stats** (1) - `times_mission_skipped`

**Scripts launched** (2) - `mission_stat_watcher`, `taxiservice`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (147), `DOES_ENTITY_EXIST` (33), `IS_PED_INJURED` (27), `WAIT` (26), `SET_BIT` (21), `CLEAR_BIT` (17), `PLAY_SOUND_FRONTEND` (17), `PLAYER_ID` (16), `GET_GAME_TIMER` (15), `GET_ENTITY_COORDS` (15), `IS_CONTROL_JUST_PRESSED` (15), `IS_PLAYER_PLAYING` (11), `ARE_STRINGS_EQUAL` (11), `SETTIMERA` (9), `IS_PED_IN_ANY_VEHICLE` (9), `BEGIN_SCALEFORM_MOVIE_METHOD` (9), `GET_CONTROL_INSTRUCTIONAL_BUTTONS_STRING` (9), `CLEAR_AREA` (8), `SET_ENTITY_COORDS` (8), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (8), `IS_VEHICLE_DRIVEABLE` (8), `IS_SCREEN_FADED_OUT` (8), `SET_GAME_PAUSED` (7), `TIMERA` (7), `FREEZE_ENTITY_POSITION` (7), `DISABLE_CONTROL_ACTION` (7), `END_SCALEFORM_MOVIE_METHOD` (7), `IS_NEW_LOAD_SCENE_ACTIVE` (6), `GET_VEHICLE_PED_IS_IN` (6), `SET_GAMEPLAY_CAM_RELATIVE_PITCH` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.075f` x8 · `0.2f` x3 · `0.7f` x2 · `207.4336f` x1 · `-1019.795f` x1 · `-100.4728f` x1 · `189.9338f` x1 · `-1019.623f` x1 · `-95.56883f` x1 · `17.1875f` x1 · `483.7175f` x1 · `-1326.63f` x1 · `28.2135f` x1 · `474.9644f` x1 · `-1307.998f` x1 · `34.49498f` x1 · `439.5432f` x1 · `-996.9769f` x1 · `24.88307f` x1 · `428.2935f` x1 · `-997.0192f` x1 · `28.57458f` x1 · `8.5f` x1 · `0.15f` x1

## Other strings

Literals whose consuming native was not classified:

`DeathFailOut`, `REPLAY_RESTART`, `Traffick_Ground`, `Traffick_Air`, `BailBond1`, `BailBond2`, `BailBond3`, `BailBond4`, `startup_positioning`, `DeathFailMichaelIn`, `DeathFailFranklinIn`, `DeathFailTrevorIn`, `replay_controller`, `REPLAY_TMG`, `REPLAY_T`, `REPLAY_OK`, `REPLAY_YES`, `REPLAY_RETRY`, `REPLAY_NO`, `REPLAY_EXIT`, `REPLAY_SKIP_S`, `REPLAY_SKIP_M`, `REPLAY_SKIPM`, `REPLAY_SKIPS`, `IMPOUND_HELPM`, `IMPOUND_HELPF`, `IMPOUND_HELPT`, `taxi`, `AM_RHP_REAP`

---

Source: `decompiled_scripts/replay_controller.c`
