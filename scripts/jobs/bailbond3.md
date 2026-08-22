# bailbond3.c

Jobs script. 1 anim dicts; 3 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 48,368 |
| Functions | 609 (34 unique, 575 shared) |
| Unique lines | 3,765 (7.8% of file) |

## Assets

**Animation dictionaries** (1) - `oddjobs@bailbond_mountain`

**Animations** (7) - `oddjobs@bailbond_mountain`, `base_jump_spot`, `Idle_Camman`, `base_jump_idle`, `excited_idle_a`, `excited_idle_b`, `excited_idle_c`

**Models and props** (3) - `s_m_y_xmech_02`, `a_m_y_skater_01`, `prop_v_cam_01`

**Text labels** (9) - `BBS_05`, `BBS_COPS`, `MAUDE`, `BBS_DROP`, `NULL`, `BB3AUD`, `BBCAUD`, `BBONDS`, `TREVOR`

**Relationship groups** (2) - `player`, `ENEMIES`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (93), `GET_GAME_TIMER` (74), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (23), `SET_PED_CONFIG_FLAG` (21), `GET_RANDOM_INT_IN_RANGE` (21), `PLAYER_ID` (17), `SET_PED_COMBAT_ATTRIBUTES` (17), `CLEAR_PED_TASKS` (15), `SET_PED_FLEE_ATTRIBUTES` (15), `IS_PED_IN_ANY_VEHICLE` (15), `SET_PED_COMPONENT_VARIATION` (13), `DOES_ENTITY_EXIST` (12), `CLEAR_PRINTS` (11), `TASK_LOOK_AT_ENTITY` (11), `CLEAR_THIS_PRINT` (11), `ENABLE_DISPATCH_SERVICE` (10), `GET_ENTITY_COORDS` (10), `SET_PED_KEEP_TASK` (10), `IS_PED_RAGDOLL` (10), `TASK_TURN_PED_TO_FACE_ENTITY` (8), `IS_PED_IN_GROUP` (7), `REMOVE_PED_FROM_GROUP` (7), `GET_PED_PARACHUTE_STATE` (7), `TASK_PLAY_ANIM` (7), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (6), `SET_GAMEPLAY_CAM_RELATIVE_PITCH` (6), `DOES_BLIP_EXIST` (6), `CLEAR_RELATIONSHIP_BETWEEN_GROUPS` (6), `IS_PED_BEING_STUNNED` (6), `SET_PED_RESET_FLAG` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x4 · `2.5f` x3 · `509.6743f` x1 · `5532.435f` x1 · `776.0009f` x1 · `153.1431f` x1 · `2704.078f` x1 · `4152.24f` x1 · `42.2514f` x1 · `175.193f` x1 · `-27.29f` x1 · `254.9762f` x1 · `0.2f` x1 · `2724.02f` x1 · `4145.08f` x1 · `43.29f` x1 · `-84.2f` x1 · `1.1f` x1 · `-1.5f` x1 · `1.7f` x1 · `0.413f` x1 · `1.5f` x1 · `3.5f` x1 · `0.5f` x1

## Other strings

Literals whose consuming native was not classified:

`player`, `BBS_APPSUS`, `BBS_APPSUS2`, `BBS_05`, `BBS_COPS`, `BBS_APHEND`, `BBS_APHEND2`, `BBC_T6`, `BBC_T8`, `BBS_DROP`, `BBC_T14`, `BB3_J10`, `asterope`, `BBC_T13`, `BB3_FLEE`, `CODE_HUMAN_STAND_COWER`, `BBC_T9`, `BBC_T5`, `BBC_T10`, `BB3_J5`, `BB3_STOP`, `BB3_J9`, `BBS_VH1`, `BB3_WTF`, `BB3_JACK`, `BBC_T7`, `BB3_OUT`, `BB3_J11`, `BB3_J2`, `Trevor`

---

Source: `decompiled_scripts/bailbond3.c`
