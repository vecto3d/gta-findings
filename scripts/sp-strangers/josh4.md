# josh4.c

SP strangers and freaks script. 3 anim dicts; 3 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 47,558 |
| Functions | 514 (24 unique, 490 shared) |
| Unique lines | 1,923 (4.0% of file) |

## Assets

**Animation dictionaries** (3) - `rcmjosh4`, `combat@gestures@pistol@halt`, `combat@gestures@pistol@glances`

**Animations** (10) - `rcmjosh4`, `josh_4_leadin_josh`, `josh_leadout_loop`, `josh_4_leadin_cop_a`, `combat@gestures@pistol@glances`, `90`, `beckon_a_josh`, `josh_4_leadin_cop_b`, `BECKON_A_COP_B`, `BECKON_A_COP_A`

**Models and props** (3) - `prop_lrggate_01c_l`, `prop_lrggate_01c_r`, `s_m_y_cop_01`

**Text labels** (17) - `JOSH4AU`, `TREVOR`, `JOSH`, `JOSHCOP`, `JOSH4CAR1`, `JOSH4COP3`, `JOSH4COP2`, `NULL`, `JOSH4CAR2`, `JOSH4CAR3`, `JOSH4BEGS`, `JOSH4CHASE`, `JOSH4KILL`, `JOSH4GIVEUP`, `JOSH4COP1`, `JOSH4JOSH`, `JOSH4`

**Doors** (2) - `prop_lrggate_01c_l`, `prop_lrggate_01c_r`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (70), `GET_GAME_TIMER` (18), `TRIGGER_MUSIC_EVENT` (10), `CLEAR_PED_TASKS` (10), `SET_PLAYBACK_SPEED` (10), `OPEN_SEQUENCE_TASK` (9), `CLOSE_SEQUENCE_TASK` (9), `TASK_PERFORM_SEQUENCE` (9), `ENABLE_DISPATCH_SERVICE` (9), `WAIT` (8), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (8), `HAS_ANIM_DICT_LOADED` (8), `TASK_PLAY_ANIM` (8), `CLEAR_SEQUENCE_TASK` (7), `IS_ENTITY_IN_ANGLED_AREA` (6), `TASK_SMART_FLEE_PED` (6), `REQUEST_MODEL` (6), `DOES_ENTITY_EXIST` (6), `REQUEST_ANIM_DICT` (6), `CAN_SET_EXIT_STATE_FOR_REGISTERED_ENTITY` (6), `REGISTER_ENTITY_FOR_CUTSCENE` (6), `HAS_MODEL_LOADED` (5), `GIVE_WEAPON_TO_PED` (5), `TASK_LOOK_AT_ENTITY` (4), `IS_PED_IN_ANY_VEHICLE` (4), `SET_CUTSCENE_PED_COMPONENT_VARIATION_FROM_PED` (4), `SET_ENTITY_COORDS` (4), `SET_ENTITY_HEADING` (4), `SET_GAMEPLAY_CAM_RELATIVE_PITCH` (4), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x6 · `0.1f` x4 · `-1138.32f` x4 · `299.69f` x4 · `65.94f` x4 · `-1140.223f` x3 · `271.745f` x3 · `-1082.403f` x3 · `344.8568f` x3 · `1.4f` x2 · `-1106.08f` x2 · `288.55f` x2 · `63.31f` x2 · `-1137.52f` x2 · `297.02f` x2 · `65.81f` x2 · `-1137.054f` x2 · `295.5856f` x2 · `67.18046f` x2 · `-1107.353f` x2 · `281.626f` x2 · `61.46451f` x2 · `-1099.521f` x2 · `282.5073f` x2

## Other strings

Literals whose consuming native was not classified:

`Cop_standing_idle`, `Cop_with_notepad`, `JOSH4_START`, `felon2`, `police3`, `JOSH4_COPS_LOST`, `************************************** TOO FAR - ATTACK next frame`, `Starting 'JOSH4_START' via cutscene skip`, `JOSH_4_INT_CONCAT`, `Josh`, `Security_guard_pistol`, `FBI_Agent_1_Gun`, `MotionState_Aiming`, `FIRING_PATTERN_FULL_AUTO`, `Trevor`, `josh_4_int_concat`, `*** Now in Josh 4 loop ***`, `Force cleanup [TERMINATING]`, `JOSH4_MISSION_FAIL`, `*** Setting up initial scene for replay`, `*** Replay setup started`, `*** Josh 4 scene set up`, `*** About to set up positions...`, `*** Creating replay vehicle and jumping to post-cutscene`, `asterope`, `JOSH4_RESTART1`, `SF_BOC`, `JOSH4_LOSECOPS`, `JOSH4_COPS_LOST_RADIO`, `Starting 'JOSH4_COPS_LOST_RADIO'`

---

Source: `decompiled_scripts/josh4.c`
