# taxi_cutyouin.c

Jobs script. 2 anim dicts; 3 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 15,712 |
| Functions | 444 (28 unique, 416 shared) |
| Unique lines | 1,557 (9.9% of file) |

## Assets

**Animation dictionaries** (2) - `MOVE_P_M_ZERO_RUCKSACK`, `oddjobs@taxi@cyi`

**Animations** (1) - `oddjobs@taxi@cyi`

**Models and props** (3) - `p_banknote_s`, `u_m_m_jewelthief`, `s_m_y_cop_01`

**Audio banks** (1) - `Alarms`

**Sounds** (3) - `TAXI_CUT_U_IN`, `Burglar_Bell`, `Generic_Alarms`

**Speech contexts** (1) - `TaxiOJCop1`

**Text labels** (5) - `COP`, `TAXI_OBJ_CYI_1B`, `NULL`, `TAXI_OBJ_CYI_01`, `TAXI`

**Scenarios** (2) - `WORLD_HUMAN_GUARD_STAND_ARMY`, `WORLD_HUMAN_STAND_MOBILE`

**Relationship groups** (1) - `TAXI_Pursuers`

## Native vocabulary

Most-called natives inside the code unique to this script:

`CLEAR_SEQUENCE_TASK` (17), `IS_ENTITY_DEAD` (16), `PLAYER_PED_ID` (12), `OPEN_SEQUENCE_TASK` (11), `CLOSE_SEQUENCE_TASK` (11), `TASK_PERFORM_SEQUENCE` (11), `GET_PLAYER_INDEX` (10), `ARE_STRINGS_EQUAL` (9), `SET_RELATIONSHIP_BETWEEN_GROUPS` (8), `IS_PED_INJURED` (8), `TASK_FOLLOW_NAV_MESH_TO_COORD` (8), `DOES_BLIP_EXIST` (7), `GET_PLAYER_WANTED_LEVEL` (7), `IS_ENTITY_AT_COORD` (6), `SET_BLIP_ROUTE` (6), `SET_PED_KEEP_TASK` (6), `SET_BLIP_ALPHA` (5), `GIVE_WEAPON_TO_PED` (5), `SET_MODEL_AS_NO_LONGER_NEEDED` (4), `IS_VEHICLE_DRIVEABLE` (4), `SET_CREATE_RANDOM_COPS` (4), `GET_BLIP_ALPHA` (4), `CLEAR_PED_TASKS` (4), `IS_SCRIPTED_CONVERSATION_ONGOING` (4), `GET_RANDOM_FLOAT_IN_RANGE` (4), `TASK_START_SCENARIO_IN_PLACE` (4), `TASK_AIM_GUN_AT_ENTITY` (4), `REQUEST_MODEL` (4), `SET_BIT` (3), `IS_PED_IN_VEHICLE` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x8 · `-1036.502f` x5 · `-2742.986f` x5 · `20.16969f` x5 · `19.16969f` x4 · `-1043.706f` x3 · `-2739.234f` x3 · `337.3356f` x2 · `-997.7456f` x2 · `28.1318f` x2 · `2.5f` x2 · `116.1366f` x1 · `-1035.326f` x1 · `-2703.305f` x1 · `12.8004f` x1 · `-1056.08f` x1 · `-2568.675f` x1 · `12.8181f` x1 · `333.6208f` x1 · `-955.5027f` x1 · `28.4225f` x1 · `1.5f` x1 · `335.5314f` x1 · `-992.4785f` x1

## Other strings

Literals whose consuming native was not classified:

`FIRING_PATTERN_FULL_AUTO`, `txm8_thank1M_2`, `txm8_thank1T_2`, `txm8_thank1F_2`, `txm8_thank2M_2`, `txm8_thank2T_2`, `txm8_thank2F_2`, `txm8_thank3M_2`, `txm8_thank3T_2`, `txm8_thank3F_2`, `Taxi Not Driveable`, `TAXI_HNT_CAM`, `TaxiDerrick`, `TAXI_SC_BN_07`, `Player abandoned his accomplice while he at the jewelry store`, `FIRING_PATTERN_BURST_FIRE`, `player didn't let teh Passenger in`, `TaxiOJCop1`, `TX_OBJ_CYI_DO`, `std_hand_off_ps_money`, `std_hand_off_rps_money`, `std_hand_off_rds_money`, `std_hand_off_ps_driver`, `std_hand_off_rps_driver`, `std_hand_off_rds_driver`, `std_hand_off_ps_passenger`, `std_hand_off_rps_passenger`, `std_hand_off_rds_passenger`, `txm8_pol1_A`, `TAXI_CYI_HANDLE_PLAYER_NEAR_JEWELRY_STORE`

---

Source: `decompiled_scripts/taxi_cutyouin.c`
