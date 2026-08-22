# launcher_triathlon.c

Races script. 1 anim dicts; 6 models.

| | |
|---|---|
| Category | Races |
| Total lines | 5,604 |
| Functions | 132 (19 unique, 113 shared) |
| Unique lines | 1,298 (23.2% of file) |

## Assets

**Animation dictionaries** (1) - `amb@prop_human_seat_chair@male@generic@idle_a`

**Models and props** (6) - `a_m_y_roadcyc_01`, `prop_tri_table_01`, `prop_chair_08`, `p_cs_clipboard`, `prop_pencil_01`, `A_M_Y_TRIATHLON_01_MINI_0`

**Text labels** (2) - `MG_GET_ON_FOOT`, `NULL`

**Scenarios** (4) - `Triathlon_1_Start`, `Triathlon_2_Start`, `Triathlon_3_Start`, `PROP_HUMAN_SEAT_CHAIR`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_ENTITY_EXIST` (14), `PLAYER_ID` (10), `PLAYER_PED_ID` (7), `IS_ENTITY_DEAD` (5), `GET_ENTITY_COORDS` (5), `VDIST2` (5), `IS_PED_INJURED` (5), `SET_MODEL_AS_NO_LONGER_NEEDED` (5), `HAS_MODEL_LOADED` (5), `REQUEST_MODEL` (5), `CREATE_OBJECT` (4), `GET_PLAYER_PED` (3), `SET_INPUT_EXCLUSIVE` (3), `SET_PLAYER_CONTROL` (3), `CLEAR_HELP` (3), `SET_ENTITY_AS_MISSION_ENTITY` (3), `CLEAR_BIT` (3), `DOES_SCENARIO_GROUP_EXIST` (3), `SET_SCENARIO_GROUP_ENABLED` (3), `SET_PED_COMPONENT_VARIATION` (3), `IS_IPL_ACTIVE` (3), `REQUEST_IPL` (3), `WAIT` (2), `CLEAR_THIS_PRINT` (2), `REQUEST_SCRIPT` (2), `IS_THREAD_ACTIVE` (2), `PLAYSTATS_MISSION_CHECKPOINT` (2), `SET_BIT` (2), `DOES_NAVMESH_BLOCKING_OBJECT_EXIST` (2), `REMOVE_NAVMESH_BLOCKING_OBJECT` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x1

## Other strings

Literals whose consuming native was not classified:

`AP1_04_TriAf01`, `CS2_06_TriAf02`, `CS4_04_TriAf03`, `CC_SUBSTR`, `MG_GET_ON_FOOT`, `TRI_NEWRC`, `TRI_DEATH`, `TRIATHLON_WARMUP`, `TriathlonSP`, `PLAY_TRIATH`

---

Source: `decompiled_scripts/launcher_triathlon.c`
