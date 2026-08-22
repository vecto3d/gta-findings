# heist_ctrl_docks.c

Heists script. 1 anim dicts; 4 models.

| | |
|---|---|
| Category | Heists |
| Total lines | 101,414 |
| Functions | 586 (6 unique, 580 shared) |
| Unique lines | 611 (0.6% of file) |

## Assets

**Animation dictionaries** (1) - `SWITCH@TREVOR@WATCHING_TV`

**Animations** (3) - `SWITCH@TREVOR@WATCHING_TV`, `LOOP`, `EXIT`

**Models and props** (4) - `prop_cs_remote_01`, `ig_floyd`, `cs_floyd`, `ig_wade`

**Audio banks** (2) - `TIME_LAPSE`, `SAFEHOUSE_FRANKLIN_SOFA`

**Text labels** (15) - `WADE`, `TREVOR`, `EXIT`, `DHP8A`, `DHP8B`, `NULL`, `BOARD1`, `DHFAUD`, `CRWAUD`, `DHP1`, `DHP10`, `DHP5`, `DHP6`, `DHP7`, `OBJECTRELEASE`

**Interiors and entity sets** (1) - `V_TREVORS`

**Scripts launched** (2) - `docks_heista`, `docks_heistb`

## Native vocabulary

Most-called natives inside the code unique to this script:

`APPLY_PED_DAMAGE_DECAL` (26), `PLAYER_PED_ID` (22), `SET_BIT` (19), `DISABLE_CONTROL_ACTION` (12), `CLEAR_BIT` (8), `SET_CUTSCENE_PED_COMPONENT_VARIATION` (6), `NEW_LOAD_SCENE_STOP` (4), `STREAMVOL_IS_VALID` (4), `STREAMVOL_DELETE` (4), `IS_ENTITY_DEAD` (4), `REGISTER_ENTITY_FOR_CUTSCENE` (4), `PLAYER_ID` (4), `REMOVE_CUTSCENE` (3), `SET_PED_PATHS_IN_AREA` (3), `SET_MAX_WANTED_LEVEL` (3), `SET_CONTROL_SHAKE_SUPPRESSED_ID` (3), `REQUEST_AMBIENT_AUDIO_BANK` (3), `GET_CUTSCENE_TIME` (3), `HAS_THIS_CUTSCENE_LOADED` (2), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (2), `GET_GAME_TIMER` (2), `WAIT` (2), `REMOVE_SCENARIO_BLOCKING_AREA` (2), `DOES_NAVMESH_BLOCKING_OBJECT_EXIST` (2), `REMOVE_NAVMESH_BLOCKING_OBJECT` (2), `CLEAR_PED_NON_CREATION_AREA` (2), `REQUEST_MODEL` (2), `HAS_MODEL_LOADED` (2), `SET_MODEL_AS_NO_LONGER_NEEDED` (2), `START_CUTSCENE` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.866f` x13 · `0.557f` x8 · `0.576f` x8 · `0.542f` x6 · `0.554f` x5 · `0.01f` x5 · `0.9f` x5 · `0.577f` x5 · `0.536f` x5 · `0.861f` x4 · `0.411f` x4 · `0.485f` x4 · `0.03f` x4 · `0.988f` x4 · `-1159.273f` x3 · `-1522.504f` x3 · `9.634f` x3 · `1.5f` x3 · `0.414f` x2 · `0.504f` x2 · `0.752f` x2 · `-1157.126f` x1 · `-1520.959f` x1 · `11.1336f` x1

## Other strings

Literals whose consuming native was not classified:

`bruise`, `scar`, `LSDHS_MCS_3_P1_CONCAT`, `H_TD_SUB`, `LSDHS_MCS_3_P2`, `player_two`, `HEIST_DOCKS`, `H_TD_PHSH`, `H_TD_INVE`, `H_TD_SECU`, `H_TD_PLAN`, `H_TD_AIR`, `DHP4a`, `DHP4b`, `DHP8B_1`, `Floyd`, `DEFAULT_ANIMATED_CAMERA`, `EXIT_CAM`, `WALKINTERRUPTABLE`, `MotionState_Idle`

---

Source: `decompiled_scripts/heist_ctrl_docks.c`
