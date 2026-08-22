# respawn_controller.c

System and infrastructure script. 15 anim dicts; 1 models; 3 scaleforms.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 99,357 |
| Functions | 538 (32 unique, 506 shared) |
| Unique lines | 2,026 (2.0% of file) |

## Assets

**Animation dictionaries** (15) - `facials@P_M_ZERO@BASE`, `facials@P_M_ONE@BASE`, `facials@P_M_TWO@BASE`, `RESPAWN@HOSPITAL@ROCKFORD`, `RESPAWN@HOSPITAL@SOUTH_CENTRAL`, `RESPAWN@HOSPITAL@DOWNTOWN`, `RESPAWN@HOSPITAL@SANDY_SHORES`, `RESPAWN@HOSPITAL@PALETO_BAY`, `RESPAWN@POLICE@VESPUCCI`, `RESPAWN@POLICE@SOUTH_CENTRAL_A`, `RESPAWN@POLICE@ROCKFORD`, `RESPAWN@POLICE@SANDY_SHORES`, `RESPAWN@POLICE@PALETO_BAY`, `RESPAWN@POLICE@VINEWOOD`, `RESPAWN@POLICE@DOWN_TOWN`

**Models and props** (1) - `prop_map_door_01`

**Audio banks** (1) - `OFFMISSION_WASTED`

**Sounds** (4) - `FBI_3_TORTURE_ZOOM`, `Bed`, `ScreenFlash`, `TextHit`

**Scaleform movies** (3) - `MP_BIG_MESSAGE_FREEMODE`, `RESET_MOVIE`, `STRING`

**Text labels** (13) - `EXTRASUNNY`, `ROCKFORD`, `NULL`, `DOWNTOWN`, `DIEM`, `DIEF`, `DIET`, `VESPUCCI`, `VINEWOOD`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `PRSAUD`

**Relationship groups** (1) - `player`

**Doors** (1) - `prop_map_door_01`

**Scripts launched** (2) - `director_mode`, `bj`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (52), `REMOVE_IPL` (33), `IS_STRING_NULL_OR_EMPTY` (17), `PLAYER_ID` (11), `IS_ENTITY_DEAD` (11), `WAIT` (10), `APPLY_PED_DAMAGE_PACK` (10), `IS_SCREEN_FADED_OUT` (8), `IS_NEW_LOAD_SCENE_ACTIVE` (6), `SETTIMERA` (6), `PLAY_SOUND_FRONTEND` (6), `TIMERA` (6), `CLEAR_AREA` (6), `SET_GAME_PAUSED` (5), `IS_PED_INJURED` (4), `STOP_AUDIO_SCENE` (4), `SET_FADE_OUT_AFTER_DEATH` (4), `SET_FADE_OUT_AFTER_ARREST` (4), `PAUSE_DEATH_ARREST_RESTART` (4), `DISPLAY_HUD` (4), `CLEAR_BIT` (4), `DO_SCREEN_FADE_OUT` (4), `SET_CAM_DEATH_FAIL_EFFECT_STATE` (4), `GET_DISTANCE_BETWEEN_COORDS` (4), `REQUEST_ANIM_DICT` (4), `GET_GAME_TIMER` (4), `SET_GAMEPLAY_CAM_RELATIVE_PITCH` (4), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (4), `IS_PLAYER_BEING_ARRESTED` (3), `GET_ENTITY_MODEL` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`7.25f` x2 · `-656.98f` x2 · `17.14f` x2 · `-1104.657f` x2 · `-1638.481f` x2 · `4.6754f` x2 · `0.2f` x2 · `0.075f` x2 · `-1.5f` x2 · `0.25f` x1

## Other strings

Literals whose consuming native was not classified:

`MotionState_Walk`, `mood_injured_1`, `DeathFailOut`, `AM_H_DISRU`, `mood_angry_1`, `MotionState_Idle`, `RespawnMichael`, `RespawnFranklin`, `RespawnTrevor`, `RESPAWN_SOUNDSET`, `Hit`, `Whoosh`, `ROCKFORD_CAM`, `SANDY_SHORES`, `SANDY_SHORES_CAM`, `PALETO_BAY`, `PALETO_BAY_CAM`, `player_zero`, `player_one`, `player_two`, `airfield`, `prologue01`, `prologue02`, `prologue03`, `prologue04`, `prologue05`, `prologue06`, `prologuerd`, `Prologue01c`, `Prologue01d`

---

Source: `decompiled_scripts/respawn_controller.c`
