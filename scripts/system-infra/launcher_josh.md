# launcher_josh.c

System and infrastructure script. 3 anim dicts; 3 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 13,276 |
| Functions | 319 (17 unique, 302 shared) |
| Unique lines | 860 (6.5% of file) |

## Assets

**Animation dictionaries** (3) - `rcmjosh2`, `rcmjosh3`, `rcmjosh4`

**Animations** (7) - `rcmjosh4`, `rcmjosh3`, `sit_stairs_idle`, `rcmjosh2`, `josh_wait_loop`, `BECKON_A_COP_B`, `BECKON_A_COP_A`

**Models and props** (3) - `prop_lrggate_01c_r`, `prop_lrggate_01c_l`, `s_m_y_cop_01`

**Text labels** (7) - `JOSH`, `JOSHCOP`, `JOSH1AU`, `JOSH2AU`, `JOSH3AU`, `NULL`, `JOSH4AU`

**Doors** (2) - `prop_lrggate_01c_l`, `prop_lrggate_01c_r`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (22), `DOES_ENTITY_EXIST` (11), `DOOR_SYSTEM_SET_OPEN_RATIO` (6), `DOOR_SYSTEM_SET_DOOR_STATE` (6), `REQUEST_MODEL` (4), `HAS_ANIM_DICT_LOADED` (4), `SET_PED_CONFIG_FLAG` (4), `SET_MODEL_AS_NO_LONGER_NEEDED` (4), `TERMINATE_THIS_THREAD` (4), `GET_VEHICLE_PED_IS_IN` (4), `SET_VEHICLE_DOORS_LOCKED` (3), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (3), `GET_GAME_TIMER` (3), `IS_PED_IN_ANY_VEHICLE` (3), `SET_PED_COMPONENT_VARIATION` (3), `CREATE_FORCED_OBJECT` (2), `REQUEST_ANIM_DICT` (2), `CREATE_SYNCHRONIZED_SCENE` (2), `TASK_SYNCHRONIZED_SCENE` (2), `SET_SYNCHRONIZED_SCENE_LOOPED` (2), `SET_VEHICLE_COLOUR_COMBINATION` (2), `SET_VEHICLE_AUTOMATICALLY_ATTACHES` (2), `SET_VEHICLE_DISABLE_TOWING` (2), `WAIT` (2), `SET_CUTSCENE_PED_COMPONENT_VARIATION_FROM_PED` (2), `TASK_LEAVE_ANY_VEHICLE` (2), `SET_PED_COMBAT_ATTRIBUTES` (2), `GIVE_WEAPON_TO_PED` (2), `CLEAR_PED_TASKS` (2), `TASK_PLAY_ANIM` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`64.76f` x3 · `-1101.62f` x2 · `290.36f` x2 · `563.76f` x2 · `-1773.86f` x2 · `28.36f` x2 · `-110.7f` x2 · `0.02f` x2 · `566.7472f` x2 · `-1771.875f` x2 · `28.35786f` x2 · `-1103.44f` x2 · `290.18f` x2 · `63.28f` x2 · `-1138.32f` x2 · `299.69f` x2 · `65.94f` x2 · `-1107.01f` x1 · `289.38f` x1 · `-0.9f` x1 · `566.1639f` x1 · `-1773.817f` x1 · `14.4f` x1 · `0.05f` x1

## Other strings

Literals whose consuming native was not classified:

`JOSH LAUNCHER RC`, `SCRIPT TERMINATED`, `JOSH4_AMB`, `josh_3_intp1`, `josh_2_intp1_t4`, `JOSH_1_INT_CONCAT`, `rcmjosh1`, `idle`, `Force cleanup [TERMINATING]`, `Player out of range [TERMINATING]`, `Making Josh cops attack`, `JOSH1_AMB1`, `JOSH2_AMB`, `JOSH3_AMB`, `Josh 4: Trying to set Cop 1 component variation`, `Cop_standing_idle`, `Josh 4: Trying to set Cop 2 component variation`, `Cop_with_notepad`, `Created initial scene`, `SCRIPT TERMINATING: Cleaning up entities in Launcher`, `SCRIPT TERMINATING: Ending off-mission cutscene request`, `Special launching Josh 4 (not in vehicle)`, `Special launching Josh 4 (in vehicle)`, `Special launching Josh 3`, `Special launching Josh 2`, `felon2`, `Relinquishing candidate id...`, `Josh 4 conversation finished and will not loop`, `police3`, `JOSH_4_INT_CONCAT`

---

Source: `decompiled_scripts/launcher_josh.c`
