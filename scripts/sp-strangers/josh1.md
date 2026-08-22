# josh1.c

SP strangers and freaks script. 2 anim dicts; 3 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 38,816 |
| Functions | 339 (9 unique, 330 shared) |
| Unique lines | 670 (1.7% of file) |

## Assets

**Animation dictionaries** (2) - `rcmjosh1leadinout`, `rcmjosh1@impatient`

**Animations** (6) - `rcmjosh1leadinout`, `leadout_josh`, `rcmjosh1@impatient`, `enter`, `idle_b`, `leadin_josh`

**Models and props** (3) - `prop_lrggate_01c_l`, `p_amb_phone_01`, `prop_lrggate_01c_r`

**Text labels** (2) - `JOSH1AU`, `NULL`

**Vehicle recordings** (1) - `Josh1Driveaway`

**Doors** (2) - `prop_lrggate_01c_l`, `prop_lrggate_01c_r`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (18), `DOES_ENTITY_EXIST` (11), `DOES_OBJECT_OF_TYPE_EXIST_AT_COORDS` (7), `SET_STATE_OF_CLOSEST_DOOR_OF_TYPE` (7), `CREATE_SYNCHRONIZED_SCENE` (5), `TASK_SYNCHRONIZED_SCENE` (5), `PLAY_SYNCHRONIZED_ENTITY_ANIM` (5), `STOP_SYNCHRONIZED_ENTITY_ANIM` (5), `CLEAR_AREA_OF_VEHICLES` (5), `IS_ENTITY_IN_ANGLED_AREA` (4), `GET_SYNCHRONIZED_SCENE_PHASE` (4), `CLEAR_PED_TASKS` (4), `WAIT` (4), `REQUEST_ANIM_DICT` (4), `FORCE_ENTITY_AI_AND_ANIMATION_UPDATE` (4), `TASK_PLAY_ANIM` (4), `SET_GAMEPLAY_CAM_RELATIVE_PITCH` (4), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (4), `GET_CLOSEST_OBJECT_OF_TYPE` (3), `REQUEST_CUTSCENE_WITH_PLAYBACK_LIST` (3), `FORCE_PED_MOTION_STATE` (3), `DOOR_SYSTEM_SET_OPEN_RATIO` (3), `TASK_LOOK_AT_ENTITY` (2), `REMOVE_CUTSCENE` (2), `IS_SYNCHRONIZED_SCENE_RUNNING` (2), `REQUEST_MODEL` (2), `HAS_ANIM_DICT_LOADED` (2), `GET_GAME_TIMER` (2), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (2), `OPEN_SEQUENCE_TASK` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`64.76f` x19 · `-1107.01f` x16 · `289.38f` x16 · `-1112.67f` x3 · `287.38f` x3 · `62.85f` x3 · `-1096.41f` x3 · `297.5f` x3 · `65.59f` x3 · `-1104.65f` x3 · `289.02f` x3 · `63.25f` x3 · `16.6717f` x3 · `-1101.62f` x3 · `290.36f` x3 · `-1115.071f` x2 · `279.6581f` x2 · `62.42184f` x2 · `-1092.428f` x2 · `284.1398f` x2 · `67.31652f` x2 · `15.75f` x2 · `-1115.44f` x2 · `317.46f` x2

## Other strings

Literals whose consuming native was not classified:

`Josh`, `rcmjosh1leadinout`, `JOSH_1_INT_CONCAT`, `leadout_gate`, `Trevor`, `Cannot play lead-in, re-requesting cutscene with new sections`, `Replay in progress, skipping leadin`, `Trying to set Josh component variation`, `MotionState_Idle`, `leadin_gate`, `Done Josh leadin anim`, `JOSH1_LEADIN`, `Leadin convo done`, `Leadin anim done, launch cutscene`, `Leadin not playing, launch cutscene`, `felon2`, `Force cleanup [TERMINATING]`, `SF_EC`, `Doing setup for leadout`, `Skip detected, waiting 500ms...`, `Done Josh leadout anim`, `JOSH1_OUT`, `Leadout convo done`, `Leadout done, end mission`, `Too close, stopping scene`, `Stopping Josh?`, `Leadout ended early, end mission`, `MotionState_Walk`, `Josh 4: PROP_LRGGATE_01c_L - Closed`, `rcmjosh1`

---

Source: `decompiled_scripts/josh1.c`
