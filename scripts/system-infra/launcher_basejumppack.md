# launcher_basejumppack.c

System and infrastructure script. 2 anim dicts; 2 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 3,813 |
| Functions | 147 (29 unique, 118 shared) |
| Unique lines | 1,398 (36.7% of file) |

## Assets

**Animation dictionaries** (2) - `oddjobs@basejump@ig_15`, `pickup_object`

**Animations** (4) - `pickup_object`, `pickup_low`, `oddjobs@basejump@ig_15`, `puton_parachute`

**Models and props** (2) - `p_parachute_s`, `bati`

**Sounds** (2) - `Grab_Parachute`, `BASEJUMPS_SOUNDS`

**Text labels** (1) - `NULL`

**Scripts launched** (1) - `bj`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (54), `IS_ENTITY_DEAD` (16), `PLAYER_ID` (13), `GET_ENTITY_COORDS` (13), `SET_PED_RESET_FLAG` (9), `WAIT` (8), `DOES_ENTITY_EXIST` (7), `SET_PLAYER_CONTROL` (6), `REQUEST_ANIM_DICT` (6), `VDIST2` (4), `IS_ENTITY_PLAYING_ANIM` (4), `HAS_ANIM_DICT_LOADED` (4), `IS_PED_INJURED` (3), `CLEAR_PED_TASKS` (3), `SET_ENTITY_ANIM_SPEED` (3), `SET_PED_COMPONENT_VARIATION` (3), `CREATE_OBJECT_NO_OFFSET` (3), `SET_ENTITY_ROTATION` (3), `GET_PLAYER_PED` (2), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (2), `SET_INPUT_EXCLUSIVE` (2), `REQUEST_SCRIPT` (2), `CLEAR_HELP` (2), `IS_THREAD_ACTIVE` (2), `PLAYSTATS_MISSION_CHECKPOINT` (2), `REMOVE_ANIM_DICT` (2), `GET_ENTITY_SPEED` (2), `TASK_FOLLOW_NAV_MESH_TO_COORD` (2), `DELETE_OBJECT` (2), `CREATE_CAMERA_WITH_PARAMS` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.3f` x3 · `0.25f` x2 · `0.8f` x2 · `0.5f` x1 · `0.22f` x1 · `0.7f` x1 · `0.2f` x1 · `0.6f` x1

## Other strings

Literals whose consuming native was not classified:

`CC_SUBSTR`, `HAND_SHAKE`, `puton_parachute_bag`, `DEFAULT_ANIMATED_CAMERA`, `puton_parachute_cam`, `bati`, `PLAY_BASEJUMP_G`

---

Source: `decompiled_scripts/launcher_basejumppack.c`
