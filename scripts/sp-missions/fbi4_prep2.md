# fbi4_prep2.c

SP missions script. 3 anim dicts; 1 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 41,347 |
| Functions | 477 (78 unique, 399 shared) |
| Unique lines | 3,033 (7.3% of file) |

## Assets

**Animation dictionaries** (3) - `mini@repair`, `amb@code_human_cower@male@enter`, `amb@code_human_cower@male@react_cowering`

**Animations** (2) - `mini@repair`, `fixing_a_ped`

**Models and props** (1) - `s_m_m_trucker_01`

**Sounds** (2) - `Tow_truck_damage`, `FBI_04_HEAT_SOUNDS`

**Speech contexts** (2) - `S_M_M_TRUCKER_01_BLACK_FULL_02`, `SPEECH_PARAMS_FORCE`

**Text labels** (3) - `NULL`, `FBIPRB`, `FIBP2AU`

**Relationship groups** (1) - `ENEMY`

**Vehicle mods** (2) - `towtruck`, `trash`

**Hashed names** (2) - `AR_stealth_kill_a`, `AR_stealth_kill_knife`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (102), `GET_GAME_TIMER` (27), `IS_PED_IN_ANY_VEHICLE` (19), `IS_PED_IN_VEHICLE` (17), `GET_RANDOM_INT_IN_RANGE` (15), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (13), `IS_ENTITY_UPSIDEDOWN` (8), `SET_PED_CAPSULE` (8), `GET_VEHICLE_PED_IS_IN` (8), `SET_ENTITY_AS_MISSION_ENTITY` (8), `IS_PED_SITTING_IN_VEHICLE` (7), `DOES_ENTITY_EXIST` (7), `IS_ENTITY_AT_COORD` (7), `PLAYER_ID` (6), `SET_VEHICLE_MODEL_IS_SUPPRESSED` (6), `CLEAR_PED_TASKS` (6), `SET_PED_INTO_VEHICLE` (5), `GET_ENTITY_COORDS` (5), `CLEAR_PRINTS` (5), `CLEAR_THIS_PRINT` (5), `SET_VEHICLE_DOORS_LOCKED` (5), `GET_ENTITY_HEADING` (5), `IS_PED_ARMED` (5), `TASK_ENTER_VEHICLE` (5), `SET_BIT` (4), `GET_ENTITY_ATTACHED_TO_TOW_TRUCK` (4), `IS_ENTITY_IN_ANGLED_AREA` (4), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (4), `OPEN_SEQUENCE_TASK` (4), `CLOSE_SEQUENCE_TASK` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`9.3184f` x6 · `0.1f` x6 · `0.5f` x5 · `1.5f` x4 · `-399.8117f` x3 · `-2172.942f` x3 · `-417.198f` x3 · `-2155.886f` x3 · `8.36266f` x3 · `-383.4908f` x3 · `-2188.511f` x3 · `12.9213f` x3 · `-1.5f` x3 · `-632.498f` x2 · `-2424.908f` x2 · `1710.123f` x2 · `-1791.79f` x2 · `0.25f` x2 · `-414.4899f` x2 · `-2181.967f` x2 · `11.93531f` x2 · `-414.1714f` x2 · `-2170.252f` x2 · `5.64993f` x2

## Other strings

Literals whose consuming native was not classified:

`player`, `PRB_LEVAREA`, `Loading`, `FP2_REACTCAR`, `FP2_ENTCAR`, `GENERIC_CURSE_MED`, `GENERIC_CURSE_HIGH`, `PRB_GOVAN`, `M_ToT`, `towtruck`, `peyote`, `ruiner`, `PRB_LEVVEH`, `FIBP2TowGuy`, `PRB_LOSETOW`, `FP2_MTAKEDOW`, `FP2_FTAKEDOW`, `FP2_TTAKEDOW`, `PRB_TAKBACK`, `FP2_RPAIR`, `FP2_REACTTOW`, `FP2_ABUSETOW`, `FP2_RETRPAIR`, `FP2_ENTTOW`, `FP2_VEHCHASE`, `FP2_FLEE`, `GENERIC_FRIGHTENED_MED`, `GENERIC_FRIGHTENED_HIGH`, `FP2_ATTACK`, `FP2_TOW`

---

Source: `decompiled_scripts/fbi4_prep2.c`
