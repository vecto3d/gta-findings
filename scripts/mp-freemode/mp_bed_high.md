# mp_bed_high.c

MP freemode script. 8 anim dicts.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 76,679 |
| Functions | 384 (34 unique, 350 shared) |
| Unique lines | 985 (1.3% of file) |

## Assets

**Animation dictionaries** (8) - `anim@mp_bedmid@left_var_01`, `anim@mp_bedmid@right_var_01`, `anim@mp_bedmid@left_var_02`, `anim@mp_bedmid@left_var_03`, `anim@mp_bedmid@left_var_04`, `anim@mp_bedmid@right_var_02`, `anim@mp_bedmid@right_var_03`, `anim@mp_bedmid@right_var_04`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (40), `PLAYER_PED_ID` (36), `IS_SYNCHRONIZED_SCENE_RUNNING` (6), `CLEAR_BIT` (6), `GET_ENTITY_COORDS` (5), `NETWORK_CREATE_SYNCHRONISED_SCENE` (5), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (5), `NETWORK_START_SYNCHRONISED_SCENE` (5), `IS_PED_INJURED` (4), `SET_BIT` (4), `CLEAR_HELP` (4), `SET_PED_CAPSULE` (4), `IS_SCREEN_FADED_OUT` (3), `GET_DISTANCE_BETWEEN_COORDS` (3), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (3), `IS_NEW_LOAD_SCENE_ACTIVE` (3), `IS_PLAYER_TELEPORT_ACTIVE` (3), `IS_ENTITY_IN_ANGLED_AREA` (3), `FINALIZE_HEAD_BLEND` (2), `NETWORK_IS_IN_MP_CUTSCENE` (2), `SET_PED_CONFIG_FLAG` (2), `GET_ANIM_INITIAL_OFFSET_POSITION` (2), `TASK_GO_STRAIGHT_TO_COORD` (2), `GET_FOLLOW_PED_CAM_VIEW_MODE` (2), `SET_PED_DESIRED_HEADING` (2), `GET_PED_NEARBY_PEDS` (2), `DOES_ENTITY_EXIST` (2), `NETWORK_GET_PLAYER_INDEX_FROM_PED` (2), `HAS_ANIM_EVENT_FIRED` (2), `GET_RANDOM_INT_IN_RANGE` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x1 · `0.9f` x1

## Other strings

Literals whose consuming native was not classified:

`SA_BED_OUT`, `SA_BED_IN`, `f_getout_l_bighouse`, `f_getin_l_bighouse`, `f_sleep_l_loop_bighouse`, `f_getout_r_bighouse`, `MotionState_Aiming`, `f_getin_r_bighouse`, `mp_bedmid`, `f_sleep_r_loop_bighouse`

---

Source: `decompiled_scripts/mp_bed_high.c`
