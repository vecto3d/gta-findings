# epsilon4.c

SP strangers and freaks script. 3 anim dicts; 4 models; 3 scaleforms.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 43,808 |
| Functions | 432 (58 unique, 374 shared) |
| Unique lines | 3,263 (7.4% of file) |

## Assets

**Animation dictionaries** (3) - `weapons@holster_1h`, `rcm_epsilonism4`, `rcm_epsilonism4leadinout`

**Animations** (14) - `rcm_epsilonism4`, `weapons@holster_1h`, `holster`, `rcm_epsilonism4leadinout`, `ep_4_rcm_leadin_marnie`, `eps_4_ig_1_jimmy_lookaround_entry_jb`, `eps_4_ig_1_jimmy_lookaround_idle_a_jb`, `eps_4_ig_1_jimmy_lookaround_exit_jb`, `eps_4_ig_1_marnie_lookaround_entry_marnie`, `eps_4_ig_1_marnie_lookaround_idle_a_marnie`, `eps_4_ig_1_marnie_lookaround_exit_marnie`, `ep_4_rcm_jimmyboston_base_jb`, `peeing`, `hippy_a`

**Models and props** (4) - `bison`, `prop_tv_test`, `prop_battery_01`, `prop_old_boot`

**Sounds** (8) - `EPSILONISM_04_SOUNDSET`, `EPSILONISM_04_MIX`, `IsOnTarget`, `DEVICE`, `IDLE_BEEP_NPC`, `CONTINUAL_BEEP`, `IDLE_BEEP`, `SCAN`

**Scaleform movies** (3) - `SET_COLOUR`, `SET_DISTANCE`, `digiscanner`

**Text labels** (6) - `EPS4AUD`, `MARNIE`, `EPS4`, `NULL`, `MICHAEL`, `JIMMYBOSTON`

**Relationship groups** (1) - `player`

**Stats** (1) - `num_epsilon_step`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (141), `GET_GAME_TIMER` (73), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (36), `TASK_PLAY_ANIM` (21), `REGISTER_ENTITY_FOR_CUTSCENE` (19), `WAIT` (18), `ARE_STRINGS_EQUAL` (14), `IS_MESSAGE_BEING_DISPLAYED` (12), `HIDE_HUD_COMPONENT_THIS_FRAME` (12), `SET_ENTITY_COORDS` (11), `SET_ENTITY_HEADING` (9), `IS_ENTITY_DEAD` (9), `DISABLE_CONTROL_ACTION` (9), `IS_PED_IN_GROUP` (8), `TASK_LOOK_AT_ENTITY` (8), `GET_ENTITY_COORDS` (8), `IS_CUTSCENE_ACTIVE` (8), `CAN_SET_EXIT_STATE_FOR_REGISTERED_ENTITY` (8), `GIVE_WEAPON_TO_PED` (8), `STOP_SOUND` (8), `CLEAR_PED_TASKS` (7), `REMOVE_CUTSCENE` (7), `SET_GAMEPLAY_CAM_RELATIVE_PITCH` (7), `PLAYER_ID` (7), `DOES_ENTITY_EXIST` (7), `SET_CONTROL_SHAKE` (7), `BEGIN_SCALEFORM_MOVIE_METHOD` (7), `END_SCALEFORM_MOVIE_METHOD` (7), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (6), `GET_ENTITY_ANIM_CURRENT_TIME` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x5 · `0.25f` x4 · `0.1f` x4 · `6.2f` x4 · `2.5f` x3 · `0.24f` x3 · `0.21f` x3 · `0.51f` x3 · `1827.161f` x2 · `4698.645f` x2 · `38.094f` x2 · `184.1384f` x2 · `1829.8f` x2 · `4693.48f` x2 · `1826.621f` x2 · `4698.734f` x2 · `41.36862f` x2 · `1831.158f` x2 · `4680.191f` x2 · `32.42626f` x2 · `16.5f` x2 · `1.5f` x2 · `1751.65f` x2 · `4676.77f` x2

## Other strings

Literals whose consuming native was not classified:

`Michael`, `Jimmy_Boston`, `Marnie`, `Artefact_Detector`, `NO_RECENT_ANIM`, `digiscanner`, `MotionState_Walk`, `EPS_4_MCS_1`, `EPS_4_MCS_2`, `EPS_4_MCS_3`, `Trying to set player component variation`, `Trying to set Jimmy prop variation`, `Requesting midtro now`, `Player moved away - unloading midtro`, `bison`, `*** Forcing Michael's move state`, `EP_4_RCM_CONCAT`, `EPS4_T0`, `EPS4_T1`, `rcm_epsilonism4`, `player`, `SF_Epsilon4`, `Cutscene not active, setting event -1`, `MotionState_Idle`, `EPS4_JKNOCK`, `EPS4_MKNOCK`, `Can request assets for cutscene entity in Eps 4`, `SKIP: Doing sync for intro skip`, `ep_4_rcm_concat`, `In Intro setup, waiting for cutscene to be ready...`

---

Source: `decompiled_scripts/epsilon4.c`
