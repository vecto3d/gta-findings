# launcher_epsilon.c

System and infrastructure script. 2 anim dicts; 3 models; 3 scaleforms.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 48,753 |
| Functions | 499 (30 unique, 469 shared) |
| Unique lines | 1,396 (2.9% of file) |

## Assets

**Animation dictionaries** (2) - `rcmepsilonism6`, `rcmepsilonism3`

**Animations** (8) - `rcmepsilonism6`, `cultist_upperstatic`, `cultist_idle_a`, `rcmepsilonism3`, `outro`, `rcm_epsilonism4`, `ep_4_rcm_jimmyboston_base_jb`, `ep_3_rcm_marnie_meditating`

**Models and props** (3) - `s_m_m_highsec_01`, `ig_tomepsilon`, `v_ilev_epsstoredoor`

**Sounds** (2) - `IDLE_BEEP_NPC`, `EPSILONISM_04_SOUNDSET`

**Scaleform movies** (3) - `SET_COLOUR`, `SET_DISTANCE`, `digiscanner`

**Text labels** (10) - `MARNIE`, `EPS8AU`, `EPS4AUD`, `NULL`, `JIMMYBOSTON`, `EPSGUARD5`, `EPSGUARD6`, `EPS3AUD`, `EPS5AUD`, `K1FFL0M`

**Scenarios** (1) - `WORLD_HUMAN_GUARD_STAND`

**Relationship groups** (1) - `gang`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (45), `SET_PED_COMPONENT_VARIATION` (20), `GET_GAME_TIMER` (10), `DOES_ENTITY_EXIST` (10), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (9), `SET_PED_RELATIONSHIP_GROUP_HASH` (9), `TASK_PLAY_ANIM` (7), `SET_PED_CONFIG_FLAG` (7), `REQUEST_MODEL` (6), `GIVE_WEAPON_TO_PED` (6), `SET_MODEL_AS_NO_LONGER_NEEDED` (6), `TERMINATE_THIS_THREAD` (4), `SET_VEHICLE_DOORS_LOCKED` (4), `SET_VEHICLE_COLOURS` (4), `GET_PED_RELATIONSHIP_GROUP_HASH` (4), `WAIT` (3), `IS_ENTITY_IN_ANGLED_AREA` (3), `HAS_ANIM_DICT_LOADED` (3), `TASK_SMART_FLEE_PED` (3), `SET_PED_KEEP_TASK` (3), `SET_PED_AS_NO_LONGER_NEEDED` (3), `PLAYER_ID` (3), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (3), `ADD_SCENARIO_BLOCKING_AREA` (3), `SET_VEHICLE_EXTRA_COLOURS` (3), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (2), `BEGIN_SCALEFORM_MOVIE_METHOD` (2), `END_SCALEFORM_MOVIE_METHOD` (2), `IS_WORLD_POINT_WITHIN_BRAIN_ACTIVATION_RANGE` (2), `IS_PED_FLEEING` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1826.45f` x2 · `4699.58f` x2 · `38.15f` x2 · `0.25f` x2 · `-726.45f` x2 · `33.33f` x2 · `43.23f` x2 · `-666.55f` x2 · `49.19f` x2 · `42.08f` x2 · `-2892.93f` x2 · `3192.37f` x2 · `11.66f` x2 · `0.1f` x1 · `0.24f` x1 · `0.21f` x1 · `0.51f` x1 · `1827.06f` x1 · `4700.52f` x1 · `39.16f` x1 · `237.926f` x1 · `360.2992f` x1 · `103.6515f` x1 · `244.6899f` x1

## Other strings

Literals whose consuming native was not classified:

`SCRIPT TERMINATED`, `digiscanner`, `EPS4_AMBJ`, `Jimmy_Boston`, `OUTFIT_P0_11`, `player_zero`, `EPSILON LAUNCHER RC - MARNIE`, `AZ_EPSILONISM_01_HILLS`, `EPS8_AMB1`, `EPS8_AMB2`, `Eps 6: Tom idle anim >0.98`, `Eps 6: Tom idle anim not playing`, `Force cleanup [TERMINATING]`, `Relinquishing candidate id...`, `Player out of range [TERMINATING]`, `Epsilon 8 kicking off! [TERMINATING]`, `EP3_AMB`, `Can request assets for cutscene entity in Eps 4`, `EP5_AMB`, `Triggered Mary Ann Eps 5 conv`, `Killed Eps 5 conversation (threat)`, `Can request assets for cutscene entity in Eps 7`, `Need to wear robes to launch Epsilon 7...`, `BADSUIT_HELP`, `Need robes and $ to launch Epsilon 8...`, `NOCASH_HELP`, `Tried to show help text for invalid mission`, `player`, `EPS8_AMA1`, `EPS8_AMA2`

---

Source: `decompiled_scripts/launcher_epsilon.c`
