# fbi4_prep1.c

SP missions script. 2 anim dicts; 2 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 12,817 |
| Functions | 388 (92 unique, 296 shared) |
| Unique lines | 3,610 (28.2% of file) |

## Assets

**Animation dictionaries** (2) - `missfbi4prepp1`, `missfbi4prepp1_garbageman`

**Animations** (4) - `missfbi4prepp1`, `_bag_drop_garbage_man`, `_bag_pickup_garbage_man`, `_bag_throw_garbage_man`

**Models and props** (2) - `p_binbag_01_s`, `s_m_y_garbage`

**Text labels** (7) - `NULL`, `FBIPRA`, `FIBP1AU`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `FBIPRAU`

**Scenarios** (5) - `DRIVE`, `WORLD_VEHICLE_ATTRACTOR`, `WORLD_VEHICLE_DRIVE_PASSENGERS`, `WORLD_VEHICLE_DRIVE_SOLO`, `WORLD_HUMAN_MOBILE_FILM_SHOCKING`

**Relationship groups** (1) - `Enemies`

**Vehicle mods** (3) - `trash`, `towtruck`, `s_m_y_garbage`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (122), `GET_GAME_TIMER` (71), `IS_PED_IN_VEHICLE` (26), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (23), `IS_PED_IN_ANY_VEHICLE` (17), `GET_ENTITY_COORDS` (16), `SET_SCENARIO_TYPE_ENABLED` (16), `DOES_ENTITY_EXIST` (15), `TASK_FOLLOW_NAV_MESH_TO_COORD` (13), `PLAYER_ID` (12), `OPEN_SEQUENCE_TASK` (11), `CLOSE_SEQUENCE_TASK` (11), `TASK_PERFORM_SEQUENCE` (11), `CLEAR_SEQUENCE_TASK` (11), `GET_VEHICLE_PED_IS_IN` (9), `SET_VEHICLE_MODEL_IS_SUPPRESSED` (9), `GET_PLAYER_WANTED_LEVEL` (8), `SET_BIT` (8), `IS_ENTITY_AT_COORD` (8), `SET_PED_INTO_VEHICLE` (7), `SET_ENTITY_AS_MISSION_ENTITY` (7), `TASK_SMART_FLEE_PED` (7), `TASK_COMBAT_PED` (7), `GET_ENTITY_FORWARD_VECTOR` (6), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (6), `RESET_PED_MOVEMENT_CLIPSET` (6), `RESET_PED_WEAPON_MOVEMENT_CLIPSET` (6), `CLEAR_PED_TASKS` (6), `IS_PED_ARMED` (6), `IS_PED_BEING_JACKED` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x17 · `1.9f` x6 · `-5.5f` x3 · `68.0929f` x2 · `1.5f` x2 · `0.2f` x2 · `-4.8f` x2 · `0.9f` x2 · `623.3781f` x2 · `-172.26f` x2 · `1700.732f` x2 · `-2115.843f` x2 · `0.8f` x1 · `0.1f` x1 · `1228.635f` x1 · `-348.4277f` x1 · `86.7244f` x1 · `1197.861f` x1 · `-353.011f` x1 · `278.9647f` x1 · `1031.673f` x1 · `-424.599f` x1 · `64.5439f` x1 · `1027.179f` x1

## Other strings

Literals whose consuming native was not classified:

`trash`, `missfbi4prepp1_garbageman`, `player`, `PRA_LEVAREA`, `Loading`, `FP1_CHATFM`, `FP1_CHATTM`, `FP1_CHATFT`, `FIRING_PATTERN_FULL_AUTO`, `PRA_LEVVEH`, `FP1_WANTM`, `FP1_LOSTM`, `FP1_THEREM`, `FP1_WANTT`, `FP1_LOSTT`, `FP1_THERET`, `FP1_WANTF`, `FP1_LOSTF`, `FP1_THEREF`, `M_TrT`, `towtruck`, `PRA_FWRECK`, `PRA_FFAR`, `PRA_FSTUCK`, `wheel_rf`, `wheel_lf`, `PRA_TAKBACK`, `cavalcade2`, `PRA_GOVAN`, `FBI4_JACKSM`

---

Source: `decompiled_scripts/fbi4_prep1.c`
