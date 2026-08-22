# player_scene_f_lamtaunt.c

SP strangers and freaks script. 3 anim dicts; 3 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 11,042 |
| Functions | 158 (14 unique, 144 shared) |
| Unique lines | 1,014 (9.2% of file) |

## Assets

**Animation dictionaries** (3) - `SWITCH@FRANKLIN@GANG_TAUNT_P3`, `SWITCH@FRANKLIN@GANG_TAUNT_P1`, `SWITCH@FRANKLIN@GANG_TAUNT_P5`

**Models and props** (3) - `g_m_y_strpunk_01`, `g_m_y_strpunk_02`, `s_m_y_cop_01`

**Text labels** (7) - `NULL`, `FRANKLIN`, `LAMAR`, `FMFAUD`, `MICHAEL`, `TREVOR`, `PRSAUD`

**Relationship groups** (1) - `TAUNTERS`

## Native vocabulary

Most-called natives inside the code unique to this script:

`GET_RANDOM_FLOAT_IN_RANGE` (15), `IS_PED_INJURED` (10), `PLAYER_PED_ID` (9), `GET_ENTITY_COORDS` (9), `WAIT` (7), `VDIST2` (5), `IS_SYNCHRONIZED_SCENE_RUNNING` (5), `DOES_ENTITY_EXIST` (4), `IS_PLAYER_TARGETTING_ENTITY` (4), `PLAYER_ID` (4), `IS_PED_IN_COMBAT` (4), `SET_RELATIONSHIP_BETWEEN_GROUPS` (4), `GET_GAME_TIMER` (3), `GET_SCRIPT_TASK_STATUS` (3), `TASK_FOLLOW_NAV_MESH_TO_COORD` (3), `IS_PED_RAGDOLL` (3), `IS_PED_GETTING_UP` (3), `SET_PED_CONFIG_FLAG` (3), `IS_SCENARIO_TYPE_ENABLED` (2), `SET_SCENARIO_TYPE_ENABLED` (2), `IS_ENTITY_ON_SCREEN` (2), `SET_ENTITY_AS_MISSION_ENTITY` (2), `GET_SYNCHRONIZED_SCENE_PHASE` (2), `CLEAR_PED_TASKS` (2), `TASK_GO_STRAIGHT_TO_COORD` (2), `FORCE_PED_MOTION_STATE` (2), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (2), `CLEAR_RAGDOLL_BLOCKING_FLAGS` (2), `VMAG` (2), `SET_BIT` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x6 · `0.25f` x3 · `0.05f` x3 · `0.5f` x2 · `0.75f` x1

## Other strings

Literals whose consuming native was not classified:

`_M0`, `_T0`, `MotionState_Walk`, `player`, `WORLD_HUMAN_PROSTITUTE_LOW_CLASS`, `FRIEND_FOLLOWED_BY_PLAYER`, `HIT_BY_PLAYER`, `FMM_0`, `FMM_1`, `FMM_2`, `FMM_3`, `FMM_4`, `FMF_0`, `FMF_1`, `FMT_0`, `FMT_3`, `_M1`, `_T1`, `_01`, `WalkInterruptible`, `GangMember1`, `GangMember2`, `gang_taunt_loop_thug_01`, `gang_taunt_loop_thug_02`, `gang_taunt_exit_thug_01`, `gang_taunt_exit_thug_02`, `FRAS_IG_6_P1`, `gang_taunt_with_lamar_loop_g1`, `gang_taunt_with_lamar_loop_g2`

---

Source: `decompiled_scripts/player_scene_f_lamtaunt.c`
