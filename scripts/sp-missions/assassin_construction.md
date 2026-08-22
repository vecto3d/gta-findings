# assassin_construction.c

SP missions script. 2 anim dicts; 8 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 23,805 |
| Functions | 507 (124 unique, 383 shared) |
| Unique lines | 5,663 (23.8% of file) |

## Assets

**Animation dictionaries** (2) - `oddjobs@assassinate@construction@call`, `oddjobs@assassinate@construction@`

**Animations** (7) - `oddjobs@assassinate@construction@`, `unarmed_fold_arms`, `ig_1_button`, `CS_GetInLift`, `idle_a`, `oddjobs@assassinate@construction@call`, `ass_construction_call_p1`

**Models and props** (8) - `prop_conslift_lift`, `p_phonebox_01b_s`, `prop_conc_blocks01a`, `a_m_y_business_01`, `s_m_m_highsec_01`, `prop_conslift_door`, `prop_sub_release`, `prop_phonebox_01b`

**Audio banks** (2) - `Freight_Elevator`, `SCRIPT\ASSASSINATION_MULTI`

**Sounds** (8) - `ASSASSINATION_CONSTRUCT_LEAVE_THE_AREA`, `ASSASSINATION_CONSTRUCT_CAR_ARRIVES`, `ASSASSINATION_CONSTRUCT_SHOOTOUT_ROOFTOP`, `ASSASSINATION_CONSTRUCT_HELICOPTER_SCENE`, `ASSASSINATION_CONSTRUCT_SHOOTOUT_START`, `ASSASSINATION_CONSTRUCT_CUTSCENE`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Text labels** (6) - `OJASAUD`, `MAFIABOSS`, `FRANKLIN`, `LESTER`, `NULL`, `OFF`

**Waypoint recordings** (1) - `OJAScs_101`

**Vehicle recordings** (1) - `OJAScs`

**Relationship groups** (1) - `ConstructionEnemies`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_ENTITY_EXIST` (91), `PLAYER_PED_ID` (85), `IS_PED_INJURED` (73), `GET_RANDOM_INT_IN_RANGE` (34), `IS_ENTITY_DEAD` (32), `PLAYER_ID` (24), `SET_PED_COMBAT_ATTRIBUTES` (20), `IS_AUDIO_SCENE_ACTIVE` (20), `GET_ENTITY_COORDS` (19), `ADD_PATROL_ROUTE_NODE` (19), `ADD_PATROL_ROUTE_LINK` (19), `SET_PED_COMPONENT_VARIATION` (18), `STOP_AUDIO_SCENE` (17), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (16), `TASK_COMBAT_PED` (16), `IS_PED_IN_ANY_VEHICLE` (15), `SET_ENTITY_COORDS` (15), `SETTIMERA` (15), `TIMERA` (15), `SET_PED_COMBAT_MOVEMENT` (15), `ATTACH_ENTITY_TO_ENTITY` (14), `DETACH_ENTITY` (14), `SET_PED_SPHERE_DEFENSIVE_AREA` (14), `CREATE_PED` (14), `TRIGGER_MUSIC_EVENT` (13), `SET_GAMEPLAY_CAM_RELATIVE_PITCH` (13), `IS_ENTITY_IN_ANGLED_AREA` (13), `CREATE_OBJECT` (12), `GET_SCRIPT_TASK_STATUS` (12), `CLEAR_SEQUENCE_TASK` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x12 · `0.2f` x9 · `-158.84f` x8 · `-942.24f` x8 · `0.5f` x7 · `113.1339f` x5 · `-150.5964f` x3 · `-945.8911f` x3 · `268.1318f` x3 · `74.1208f` x3 · `31.44f` x3 · `270.46f` x3 · `-182.17f` x3 · `-1016.09f` x3 · `115.46f` x3 · `26.2731f` x3 · `809.3085f` x3 · `-1074.928f` x3 · `27.6018f` x3 · `-182.0891f` x2 · `-1004.055f` x2 · `113.1355f` x2 · `-250.5509f` x2 · `-1126.146f` x2

## Other strings

Literals whose consuming native was not classified:

`WORLD_HUMAN_GUARD_STAND`, `ASS_CS_ELEHELP`, `HAND_SHAKE`, `OJAcsGUARD2`, `OJAcsGUARD`, `FIRING_PATTERN_FULL_AUTO`, `ASS_CS_COMP`, `OJAcsGUARD4`, `OJAS_COCOM`, `ASS_CS_PARA`, `OJAScsWARN1`, `ASS5_FAIL`, `DT1_21_prop_lift_on`, `DT1_21_ConSiteAssass`, `ASS_CS_ESCAPED`, `OJAScs_GDb`, `OJAcsGUARD5`, `OJAScs_G4`, `OJAScs_SPOT`, `ASS5_STOP`, `assassin_construction_rooftop_battle`, `miss_Ass0`, `miss_Ass4`, `miss_Ass6`, `miss_Ass3`, `ASS_CS_TARGET`, `OJAScs_SCARE`, `player`, `M_ASS5`, `ASS_CS_RTNY`

---

Source: `decompiled_scripts/assassin_construction.c`
