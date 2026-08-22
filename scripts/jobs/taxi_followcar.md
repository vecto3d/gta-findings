# taxi_followcar.c

Jobs script. 7 anim dicts; 4 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 16,398 |
| Functions | 462 (72 unique, 390 shared) |
| Unique lines | 2,964 (18.1% of file) |

## Assets

**Animation dictionaries** (7) - `veh@truck@ds@base`, `gestures@m@standing@casual`, `MOVE_DUCK_FOR_COVER`, `amb@world_human_hang_out_street@male_c@idle_a`, `amb@world_human_hang_out_street@male_c@exit`, `amb@world_human_hang_out_street@female_hold_arm@idle_a`, `amb@world_human_hang_out_street@female_hold_arm@exit`

**Animations** (13) - `oddjobs@towingcome_here`, `MOVE_DUCK_FOR_COVER`, `come_here_idle_a`, `exit`, `come_here_idle_c`, `gestures@m@standing@casual`, `gesture_nod_yes_hard`, `idle_b`, `idle_a`, `enter`, `loop`, `veh@truck@ds@base`, `start_engine`

**Models and props** (4) - `a_f_y_genhot_01`, `a_f_y_bevhills_01`, `prop_sec_barrier_ld_02a`, `s_m_m_doctor_01`

**Sounds** (4) - `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `CHECKPOINT_UNDER_THE_BRIDGE`, `HUD_MINI_GAME_SOUNDSET`

**Speech contexts** (1) - `TaxiJames`

**Text labels** (7) - `TAXI_OBJ_DRIVE`, `NULL`, `OJTXAUD`, `BRAVEST`, `BOLDEST`, `BADDEST`, `PUSSYWAG`

**Vehicle recordings** (2) - `txm_fc_h1_`, `taxi_oj_fc3`

**Relationship groups** (2) - `TAXI_Escapee`, `TAXI_Whore`

**Doors** (1) - `prop_sec_barrier_ld_02a`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_ENTITY_DEAD` (45), `IS_PED_INJURED` (31), `IS_VEHICLE_DRIVEABLE` (30), `PLAYER_PED_ID` (30), `CLEAR_SEQUENCE_TASK` (27), `CLEAR_PED_TASKS` (18), `OPEN_SEQUENCE_TASK` (17), `CLOSE_SEQUENCE_TASK` (17), `TASK_PERFORM_SEQUENCE` (17), `SET_PED_KEEP_TASK` (16), `SET_PED_COMPONENT_VARIATION` (13), `SET_PED_COMBAT_ATTRIBUTES` (13), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (13), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (13), `DOES_BLIP_EXIST` (11), `PLAYER_ID` (10), `REMOVE_BLIP` (8), `TASK_PLAY_ANIM` (8), `GET_GAME_TIMER` (8), `REMOVE_ANIM_DICT` (7), `SET_MODEL_AS_NO_LONGER_NEEDED` (7), `REQUEST_ANIM_DICT` (7), `GET_ENTITY_COORDS` (7), `DOES_ENTITY_EXIST` (6), `GET_ENTITY_SPEED` (6), `SET_ENTITY_COORDS` (6), `TASK_SMART_FLEE_COORD` (6), `TASK_STAND_STILL` (6), `REQUEST_MODEL` (6), `TASK_SMART_FLEE_PED` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`2.25f` x3 · `0.1f` x3 · `0.8f` x2 · `1346.9f` x2 · `-1606.52f` x2 · `31.16f` x2 · `1457.25f` x2 · `-1508.19f` x2 · `83.05f` x2 · `-685.0081f` x2 · `-1101.297f` x2 · `13.527f` x2 · `-678.677f` x2 · `-1110.64f` x2 · `15.5871f` x2 · `0.5f` x2 · `-691.48f` x2 · `-1113.31f` x2 · `13.53f` x2 · `17.2f` x2 · `0.2f` x2 · `413.8f` x2 · `-1416.19f` x2 · `29.26f` x2

## Other strings

Literals whose consuming native was not classified:

`FIRING_PATTERN_FULL_AUTO`, `HAND_SHAKE`, `TAXI_FAIL`, `TAXI_OBJ_FAIL`, `TAXI_OBJ_F_SPT`, `Taxi Not Driveable`, `TAXI_OBJ_F_SPK`, `_shot1`, `_noDri2`, `_noDri1`, `Taxi let the Chasee lose him`, `Taxi was ID'd by the Chasee`, `ambulance`, `bison`, `TAXI_SC_BN_04`, `_aband2`, `_aband1`, `CamPushInNeutral`, `Taxi shot up the car`, `taxi_oj_fc_2`, `Didn't lose police in time.`, `TaxiKeyla`, `player`, `Passenger injured.`, `UPDATE_FINAL_SCENE()`, `txm4_aggro`, `UPDATE_FINAL_SCENE - FINAL_SCENE_WAIT_FOR_DIALOGUE`, `FINAL_SCENE_KILL_WOMAN`, `FINAL_SCENE_KILL_MAN`, `FINAL_SCENE_FLEE`

---

Source: `decompiled_scripts/taxi_followcar.c`
