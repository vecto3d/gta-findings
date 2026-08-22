# launcher_paparazzo.c

System and infrastructure script. 3 anim dicts; 7 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 12,619 |
| Functions | 295 (11 unique, 284 shared) |
| Unique lines | 874 (6.9% of file) |

## Assets

**Animation dictionaries** (3) - `rcmpaparazzo_2`, `rcmpaparazzo_4`, `rcmpaparazzo1beckon`

**Animations** (11) - `rcmpaparazzo_4`, `pap_4_rcm_leadin`, `Idle_Camman`, `Idle_Prod`, `idle_closed_pap_3_rcm_beverly`, `rcmpaparazzo_2`, `pap_2_rcm_base`, `pap_idle_01`, `pap_idle_action_01`, `pap_idle_02`, `pap_idle_action_02`

**Models and props** (7) - `prop_cs_dumpster_01a`, `prop_cs_dumpster_lidr`, `prop_cs_dumpster_lidl`, `prop_pap_camera_01`, `s_m_y_grip_01`, `a_f_y_bevhills_02`, `prop_v_cam_01`

**Text labels** (5) - `BEVERLY`, `NULL`, `PAP2AUD`, `PAP4AUD`, `P4P4R4Z0`

**Scenarios** (1) - `WORLD_HUMAN_PAPARAZZI`

**Scripts launched** (1) - `paparazzo3`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_ENTITY_EXIST` (17), `SET_PED_COMPONENT_VARIATION` (15), `SET_MODEL_AS_NO_LONGER_NEEDED` (9), `TASK_PLAY_ANIM` (6), `REQUEST_MODEL` (5), `HAS_ANIM_DICT_LOADED` (5), `ATTACH_ENTITY_TO_ENTITY` (5), `GET_PED_BONE_INDEX` (5), `REMOVE_ANIM_DICT` (4), `TERMINATE_THIS_THREAD` (4), `REQUEST_ANIM_DICT` (4), `SET_PED_DEFAULT_COMPONENT_VARIATION` (4), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (4), `SET_VEHICLE_COLOUR_COMBINATION` (4), `SET_SCENARIO_TYPE_ENABLED` (3), `REMOVE_MODEL_HIDE` (3), `WAIT` (3), `CREATE_SYNCHRONIZED_SCENE` (3), `SET_SYNCHRONIZED_SCENE_LOOPED` (3), `TASK_SYNCHRONIZED_SCENE` (3), `SET_VEHICLE_DOORS_LOCKED` (3), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (3), `GET_CLOSEST_OBJECT_OF_TYPE` (3), `CREATE_MODEL_HIDE` (3), `CREATE_OBJECT_NO_OFFSET` (3), `SET_ENTITY_ROTATION` (3), `SET_CAN_CLIMB_ON_ENTITY` (3), `PLAY_SYNCHRONIZED_ENTITY_ANIM` (3), `SET_PED_NAME_DEBUG` (2), `PLAYER_PED_ID` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-260.62f` x3 · `-261.58f` x3 · `291.66f` x3 · `92.06f` x3 · `2.5f` x3 · `-190.0199f` x3 · `260.1082f` x3 · `-131.572f` x3 · `285.8091f` x3 · `292.13f` x2 · `90.6f` x2 · `-261.54f` x2 · `292.54f` x2 · `92.1f` x2 · `-490.809f` x2 · `232.39f` x2 · `82.018f` x2 · `33.84f` x2 · `-71.283f` x2 · `301.557f` x2 · `106.711f` x2 · `4.659f` x2 · `-74.8392f` x1 · `300.5241f` x1

## Other strings

Literals whose consuming native was not classified:

`SCRIPT TERMINATED`, `PAPARAZZO LAUNCHER RC`, `SCRIPT TERMINATING: Cleaning up entities in Launcher`, `SCRIPT TERMINATING: Ending off-mission cutscene request`, `SCRIPT TERMINATING: Holding on to launcher until Paparazzo 3 cleans up...`, `pcj`, `Force cleanup [TERMINATING]`, `Relinquishing candidate id...`, `Player out of range [TERMINATING]`, `PAP2_AMB`, `PAP4_AMB`, `Created initial scene`, `rcmpaparazzo_4`, `issi2`, `rumpo`, `PAP_4_RCM`, `Camera Man`, `Makeup Woman`, `jackal`, `rcmpaparazzo_3leadinoutpap_3_rcm`, `PAP_3_RCM`, `idle_closed_pap_3_rcm_dumpster`, `idle_closed_pap_3_rcm_lid_l`, `idle_closed_pap_3_rcm_lid_r`, `fq2`, `PAP_2_RCM_P2`, `rcmpaparazzo1beckon`, `PAP_1_RCM`

---

Source: `decompiled_scripts/launcher_paparazzo.c`
