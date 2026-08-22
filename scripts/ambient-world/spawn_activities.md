# spawn_activities.c

Ambient world script. 5 anim dicts; 1 models.

| | |
|---|---|
| Category | Ambient world |
| Total lines | 105,060 |
| Functions | 782 (42 unique, 740 shared) |
| Unique lines | 1,949 (1.9% of file) |

## Assets

**Animation dictionaries** (5) - `GET_UP@DIRECTIONAL@TRANSITION@PRONE_TO_SEATED@INJURED`, `get_up@directional@movement@from_seated@standard`, `switch@michael@smoking2`, `anim@scripted@heist@ig25_beach@heeled@`, `anim@scripted@heist@ig25_beach@male@`

**Animations** (6) - `GET_UP@DIRECTIONAL@TRANSITION@PRONE_TO_SEATED@INJURED`, `front`, `get_up@directional@movement@from_seated@standard`, `get_up_l_0`, `switch@michael@smoking2`, `exit`

**Models and props** (1) - `prop_cigar_01`

**Text labels** (1) - `NULL`

**Scripts launched** (2) - `AM_MP_PROPERTY_INT`, `am_mp_property_int`

**Hashed names** (1) - `NO_LABEL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (64), `SET_BIT` (41), `PLAYER_ID` (35), `DOES_CAM_EXIST` (11), `IS_ENTITY_PLAYING_ANIM` (10), `REQUEST_SCRIPT` (10), `HAS_SCRIPT_LOADED` (10), `START_NEW_SCRIPT` (10), `SET_SCRIPT_AS_NO_LONGER_NEEDED` (10), `DESTROY_CAM` (9), `CLEAR_BIT` (8), `CLEAR_PED_TASKS` (7), `REQUEST_ANIM_DICT` (7), `HAS_ANIM_DICT_LOADED` (7), `FREEZE_ENTITY_POSITION` (6), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (6), `SET_GAMEPLAY_CAM_RELATIVE_PITCH` (6), `REMOVE_ANIM_DICT` (6), `GET_NETWORK_TIME` (5), `RENDER_SCRIPT_CAMS` (5), `TASK_PLAY_ANIM` (5), `GET_GAME_TIMER` (5), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (5), `NETWORK_IS_SCRIPT_ACTIVE` (5), `GET_DISTANCE_BETWEEN_COORDS` (5), `IS_ENTITY_IN_ANGLED_AREA` (5), `GET_ENTITY_ANIM_CURRENT_TIME` (4), `IS_PED_IN_ANY_VEHICLE` (3), `TASK_WANDER_STANDARD` (3), `IS_SCREEN_FADED_OUT` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.85f` x4 · `0.7f` x3 · `0.99f` x1 · `0.2f` x1 · `-1589.074f` x1 · `-3015.353f` x1 · `-74.8535f` x1 · `-15.8449f` x1 · `78.0001f` x1 · `25.1368f` x1 · `-1589.807f` x1 · `-3008.426f` x1 · `-74.9934f` x1 · `-17.1168f` x1 · `104.7282f` x1 · `34.7654f` x1 · `-1592.237f` x1 · `-3008.188f` x1 · `-78.166f` x1 · `-3.025f` x1 · `121.1804f` x1 · `35.9f` x1 · `0.1f` x1

## Other strings

Literals whose consuming native was not classified:

`AM_MP_PROPERTY_INT`, `rebreather`, `exit_cam`, `DEFAULT_SCRIPTED_CAMERA`, `HAND_SHAKE`, `action`, `action_camera`

---

Source: `decompiled_scripts/spawn_activities.c`
