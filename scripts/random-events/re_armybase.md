# re_armybase.c

Random events script. 4 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 3,078 |
| Functions | 70 (30 unique, 40 shared) |
| Unique lines | 1,631 (53.0% of file) |

## Assets

**Models and props** (4) - `s_m_y_marine_01`, `s_m_y_marine_03`, `lazer`, `crusader`

**Text labels** (3) - `ARMYAUD`, `COP`, `NULL`

**Scenarios** (1) - `WORLD_HUMAN_GUARD_STAND_ARMY`

**Waypoint recordings** (2) - `OfficerMarch01`, `AccomMarching01`

**Vehicle recordings** (4) - `SingleRoute`, `ArmyBaseNew`, `LazerTakeOff`, `CargoTakeOff`

**Relationship groups** (1) - `army`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (77), `IS_ENTITY_DEAD` (56), `DOES_ENTITY_EXIST` (53), `PLAYER_ID` (23), `IS_PED_INJURED` (21), `IS_ENTITY_OCCLUDED` (17), `GET_ENTITY_COORDS` (15), `SET_RELATIONSHIP_BETWEEN_GROUPS` (13), `GET_PLAYER_WANTED_LEVEL` (12), `IS_ENTITY_IN_ANGLED_AREA` (12), `SET_VEHICLE_AS_NO_LONGER_NEEDED` (12), `CREATE_PED` (10), `CLEAR_PED_TASKS` (10), `SET_PED_AS_NO_LONGER_NEEDED` (10), `REMOVE_VEHICLE_RECORDING` (10), `GIVE_WEAPON_TO_PED` (9), `SET_PED_KEEP_TASK` (9), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (8), `REQUEST_MODEL` (8), `HAS_MODEL_LOADED` (8), `SET_PED_RELATIONSHIP_GROUP_HASH` (8), `DELETE_PED` (8), `CLEAR_SEQUENCE_TASK` (7), `GET_SCRIPT_TASK_STATUS` (7), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (7), `DELETE_VEHICLE` (7), `DOES_BLIP_EXIST` (7), `REMOVE_BLIP` (7), `CLEAR_AREA_OF_VEHICLES` (6), `SET_ENTITY_LOD_DIST` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`57.3018f` x8 · `140.0094f` x5 · `0.1f` x4 · `0.25f` x4 · `-1588.977f` x3 · `2793.941f` x3 · `14.98289f` x3 · `-1575.664f` x3 · `2779.558f` x3 · `26.11536f` x3 · `29.75f` x3 · `-2306.916f` x3 · `3390.545f` x3 · `29.17826f` x3 · `-2322.245f` x3 · `3401.719f` x3 · `35.63131f` x3 · `0.5f` x2 · `31.124f` x2 · `-1931.548f` x1 · `3026.929f` x1 · `31.8104f` x1 · `-1587.327f` x1 · `2798.517f` x1

## Other strings

Literals whose consuming native was not classified:

`army`, `player`, `PORT_OF_LS_HEIST_FORT_ZANCUDO_ALARMS`, `crusader`, `ARMY_WRN1`, `ARMY_WRN1a`, `ARMY_WRN2`, `ARMY_WRN2a`, `lazer`, `ARMY_ANNOUNCER`, `FIRING_PATTERN_FULL_AUTO`, `ARMY_ANN1`, `ARMY_ANN2`, `ARMY_ANN3`, `ARMY_ANN4`, `ARMY_Guard01`, `ARMY_Guard02`

---

Source: `decompiled_scripts/re_armybase.c`
