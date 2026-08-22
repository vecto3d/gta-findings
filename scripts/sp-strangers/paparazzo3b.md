# paparazzo3b.c

SP strangers and freaks script. 5 anim dicts; 8 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 55,318 |
| Functions | 629 (48 unique, 581 shared) |
| Unique lines | 3,680 (6.7% of file) |

## Assets

**Animation dictionaries** (5) - `rcmpaparazzo_3big_1`, `amb@world_human_stand_impatient@male@no_sign@idle_a`, `amb@world_human_stand_impatient@male@no_sign@base`, `amb@world_human_smoking@female@idle_a`, `amb@world_human_smoking@female@base`

**Animations** (14) - `rcmpaparazzo_3big_1`, `amb@world_human_smoking@female@idle_a`, `_action_dealer_a`, `_action_dealer_b`, `_action_guard_a`, `_action_guard_b`, `_action_princess`, `idle_a`, `idle_b`, `idle_c`, `_idle_dealer_a`, `_idle_dealer_b`, `_idle_guard_a`, `_idle_guard_b`

**Models and props** (8) - `prop_drug_package_02`, `prop_cash_pile_02`, `g_m_y_mexgoon_03`, `s_m_m_highsec_02`, `s_m_m_highsec_01`, `p_amb_joint_01`, `u_f_y_princess`, `s_m_y_dealer_01`

**Speech contexts** (6) - `Paparazzo3BBodyGuard1`, `SPEECH_PARAMS_STANDARD`, `PAP3B_BDAA`, `PAP3B_BCAA`, `PAP3B_BFAA`, `SPEECH_PARAMS_FORCE`

**Text labels** (6) - `FRANKLIN`, `BEVERLY`, `PAP3BAU`, `PRINCESS`, `NULL`, `PAP3`

**Scenarios** (3) - `WORLD_HUMAN_SMOKING`, `WORLD_HUMAN_GUARD_STAND`, `WORLD_HUMAN_STAND_IMPATIENT`

**Waypoint recordings** (1) - `PAP3_Security1`

**Vehicle recordings** (1) - `PAP3Security1`

**Relationship groups** (2) - `PrincessGroup`, `DealersGroup`

**Scripts launched** (1) - `appcamera`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (167), `GET_GAME_TIMER` (49), `IS_ENTITY_IN_ANGLED_AREA` (35), `SET_PED_COMPONENT_VARIATION` (35), `ARE_STRINGS_EQUAL` (34), `GET_SCRIPT_TASK_STATUS` (29), `HAS_MODEL_LOADED` (22), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (19), `TASK_COMBAT_PED` (18), `IS_PED_IN_COMBAT` (15), `TASK_SYNCHRONIZED_SCENE` (14), `TASK_LOOK_AT_ENTITY` (13), `SET_PED_COMBAT_ATTRIBUTES` (12), `IS_PED_IN_VEHICLE` (11), `TASK_TURN_PED_TO_FACE_ENTITY` (11), `IS_PED_FACING_PED` (11), `SET_PED_SEEING_RANGE` (11), `SET_RELATIONSHIP_BETWEEN_GROUPS` (11), `SET_PED_FLEE_ATTRIBUTES` (11), `GET_SYNCHRONIZED_SCENE_PHASE` (11), `SET_MODEL_AS_NO_LONGER_NEEDED` (10), `FREEZE_ENTITY_POSITION` (10), `REQUEST_MODEL` (10), `TASK_ENTER_VEHICLE` (9), `CLEAR_PRINTS` (9), `WAIT` (8), `DOES_BLIP_EXIST` (8), `IS_PED_IN_ANY_VEHICLE` (8), `GET_PLAYERS_LAST_VEHICLE` (8), `IS_VEHICLE_SEAT_FREE` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1158.52f` x4 · `-759.3739f` x4 · `56.32278f` x4 · `1116.869f` x4 · `-759.6908f` x4 · `61.70632f` x4 · `13.75f` x4 · `61.01268f` x4 · `11.75f` x4 · `4.5f` x2 · `0.1f` x2 · `1046.05f` x2 · `-754.8271f` x2 · `56.04185f` x2 · `1144.92f` x2 · `-755.2141f` x2 · `59.98388f` x2 · `20.75f` x2 · `56.7705f` x2 · `-761.915f` x2 · `1090.248f` x2 · `0.758f` x2 · `1114.694f` x2 · `-779.025f` x2

## Other strings

Literals whose consuming native was not classified:

`player`, `pap3bau`, `PAP3_DEALER`, `Paparazzo3BDealerGoon1`, `Paparazzo3BBodyGuard1`, `Paparazzo3BDrugDealer`, `PAP3_SECUR4`, `PAP3_DEALER_23`, `PAP3_DEALER_20`, `PAP3_HELP2`, `PAP3_HELP6`, `MotionState_Walk`, `PAP3_CON`, `PAP3_HELP8`, `PAP3_10`, `PAP3_SECUR4_3`, `Paparazzo3BBodyGuard2`, `PAP3_SHOCK`, `PAP3_PRIN`, `landstalker`, `PAP3_HELP1`, `PAP3_DEALER_2`, `PAP3_DEALER_3`, `PAP3_DEALER_4`, `PAP3_DEALER_5`, `PAP3_DEALER_6`, `PAP3_DEALER_7`, `PAP3_DEALER_8`, `PAP3_DEALER_9`, `PAP3_DEALER_10`

---

Source: `decompiled_scripts/paparazzo3b.c`
