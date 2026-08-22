# controller_towing.c

Jobs script. 2 anim dicts; 3 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 8,069 |
| Functions | 164 (14 unique, 150 shared) |
| Unique lines | 722 (8.9% of file) |

## Assets

**Animation dictionaries** (2) - `amb@world_human_smoking@male@male_a@base`, `oddjobs@towingcome_here`

**Models and props** (3) - `a_f_y_soucent_01`, `towtruck`, `towtruck2`

**Text labels** (4) - `TOWAUD`, `TOWDISPATCH`, `NULL`, `FRANKLIN`

**Scripts launched** (2) - `Towing`, `towing`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_ENTITY_DEAD` (11), `SET_MODEL_AS_NO_LONGER_NEEDED` (8), `GET_GAME_TIMER` (7), `PLAYER_PED_ID` (6), `DOES_ENTITY_EXIST` (6), `SET_FRONTEND_RADIO_ACTIVE` (5), `REMOVE_ANIM_DICT` (4), `PLAYER_ID` (4), `REQUEST_MODEL` (4), `IS_PED_IN_ANY_VEHICLE` (4), `IS_HELP_MESSAGE_BEING_DISPLAYED` (3), `GET_VEHICLE_PED_IS_IN` (3), `GET_ENTITY_MODEL` (3), `WAIT` (2), `IS_ENTITY_OCCLUDED` (2), `SET_PED_AS_NO_LONGER_NEEDED` (2), `DELETE_VEHICLE` (2), `IS_CONTROL_JUST_PRESSED` (2), `IS_DISABLED_CONTROL_PRESSED` (2), `IS_THREAD_ACTIVE` (2), `CLEAR_HELP` (2), `SET_SCRIPT_AS_NO_LONGER_NEEDED` (2), `CREATE_VEHICLE` (2), `REQUEST_SCRIPT` (2), `HAS_MODEL_LOADED` (2), `GET_PLAYER_WANTED_LEVEL` (2), `HAS_FORCE_CLEANUP_OCCURRED` (1), `DELETE_PED` (1), `IS_ENTITY_A_MISSION_ENTITY` (1), `SET_VEHICLE_AS_NO_LONGER_NEEDED` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`408.8376f` x3 · `-1638.952f` x3 · `28.2928f` x3 · `230.2387f` x2

## Other strings

Literals whose consuming native was not classified:

`towtruck`, `towtruck2`, `Towing`, `TOW_DISP_GEN`, `TOW_JOBOFFRD`, `TOW_MISSEDJOB`, `TOW_JOBS_AVL`, `TOW_NO_JOBS`, `TOW_WANTED`

---

Source: `decompiled_scripts/controller_towing.c`
