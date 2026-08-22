# rural_bank_setup.c

SP missions script. 3 developer state labels recovered; 7 anim dicts; 19 models; 2 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 121,971 |
| Functions | 927 (113 unique, 814 shared) |
| Unique lines | 9,568 (7.8% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`SKIP IS ACTIVE` · `MIKE WIN CUTSCENE SET TO LOAD` · `TREVOR WIN CUTSCENE SET TO LOAD`

## Assets

**Animation dictionaries** (7) - `missheistpaletoscoresetup_setup1`, `missrbhsig_2`, `missheistpaletoscore1rbhs_mcs_2`, `missheistpaletoscoresetup_setup3`, `missheistpaletoscoresetup_setup2`, `missheistpaletoscoresetup`, `missheistpaletoscore1leadinoutrbhs_int_1`

**Animations** (39) - `missrbhsig_2`, `missheistpaletoscore1rbhs_mcs_2`, `rbhs_mcs_2_leadin_action_michael`, `missheistpaletoscoresetup`, `missheistpaletoscoresetup_setup3`, `missheistpaletoscoresetup_setup2`, `missheistpaletoscoresetup_setup1`, `four_cars_trevor`, `what_do_you_got_trevor`, `rbhs_mcs_2_leadin_action_lestercrest`, `rbhs_mcs_2_leadin_action_trevor`, `this_is_them_trevor`, `trevor_arrival_1`, `four_cars_lester`, `what_do_you_got_lester`, `this_is_them_lester`, `missheistpaletoscore1leadinoutrbhs_int_1`, `_leadin_trevor`, `cops_response_waitloop_bank_manager`, `cops_response_waitloop_bank_clerk1`, `cops_response_waitloop_bank_clerk2`, `cops_response_waitloop_bank_clerk3`, `trevor_impatient_wait_1`, `trevor_impatient_wait_2`, `trevor_impatient_wait_3`, `trevor_impatient_wait_4`, `cops_response_intro_bank_manager`, `cops_response_intro_bank_clerk1`, `cops_response_intro_bank_clerk2`, `cops_response_intro_bank_clerk3`, `Cops_Response_Outro_Cop_Driver`, `Cops_Response_Outro_Cop_Passenger`, `Cops_Response_Outro_Bank_Manager`, `Cops_Response_Outro_Bank_Clerk1`, `Cops_Response_Outro_Bank_Clerk2`, `Cops_Response_Outro_Bank_Clerk3`, `four_cars_Lester`, `what_do_you_got_Lester`, `this_is_them_Lester`

**Models and props** (19) - `s_m_y_cop_01`, `prop_ld_alarm_01`, `sheriff`, `a_m_m_business_01`, `a_f_y_business_01`, `s_m_m_lsmetro_01`, `prop_ld_alarm_01_dam`, `v_ilev_cbankvauldoor01`, `a_m_y_genstreet_02`, `prop_ld_test_01`, `bus`, `ruffian`, `a_m_m_salton_02`, `player_two`, `premier`, `s_f_y_cop_01`, `s_m_y_hwaycop_01`, `ig_lestercrest`, `S_M_M_LSMetro_01`

**Audio banks** (2) - `TIME_LAPSE`, `SCRIPT\Alarms`

**Sounds** (17) - `PS_1_DRIVE_TO_GAS_STATION`, `PS_1_TREVOR_DRIVES_OFF`, `PS_1_RACE_AS_MICHAEL`, `PS_1_FOCUS_ON_BANK`, `PS_1_DRIVE_TO_BANK`, `PS_1_DRIVE_TO_PALETO`, `PS_1_RACE_AS_TREVOR`, `HINT_CAM_SCENE`, `HintCamSounds`, `PS_1_SHOOT_THE_ALARM`, `PS_1_BUS_ARRIVES`, `TOD_SHIFT_SCENE`, `FocusOut`, `TIME_LAPSE_MASTER`, `Shoot_box`, `Paleto_Score_Setup_Sounds`, `FocusIn`

**Particle effects** (2) - `cs_rbhs_int_delap_dust`, `scr_alarm_damage_sparks`

**Text labels** (13) - `LESTER`, `TREVOR`, `BANKS1`, `PALETOCOP1`, `NULL`, `RBS1AUD`, `LCITY1`, `TCITY1`, `LCITY2`, `TCITY2`, `MICHAEL`, `PALETOSCANNER`, `EXTRASUNNY`

**Scenarios** (6) - `WORLD_VEHICLE_TRUCK_LOGS`, `WORLD_HUMAN_HIKER`, `WORLD_VEHICLE_BICYCLE_MOUNTAIN`, `WORLD_HUMAN_STAND_IMPATIENT`, `WORLD_VEHICLE_DRIVE_SOLO`, `WORLD_HUMAN_HANG_OUT_STREET`

**Vehicle recordings** (1) - `RBsetup`

**Relationship groups** (3) - `player`, `THE_COPS`, `BANK_PEDS`

**Doors** (1) - `v_ilev_methdoorscuff`

**Vehicle mods** (3) - `premier`, `ruffian`, `taxi`

**Stats** (6) - `sp0_special_ability`, `sp0_special_ability_unlocked`, `sp1_special_ability`, `sp1_special_ability_unlocked`, `sp2_special_ability`, `sp2_special_ability_unlocked`

**Hashed names** (1) - `SIDE_DOOR_METHLAB`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (441), `GET_ENTITY_COORDS` (152), `IS_PED_INJURED` (151), `DOES_ENTITY_EXIST` (147), `IS_VEHICLE_DRIVEABLE` (122), `IS_PED_IN_VEHICLE` (98), `GET_GAME_TIMER` (75), `IS_ENTITY_IN_ANGLED_AREA` (72), `VDIST2` (69), `DOES_BLIP_EXIST` (69), `PLAYER_ID` (53), `REMOVE_BLIP` (43), `HAS_PED_GOT_WEAPON` (39), `GET_AMMO_IN_PED_WEAPON` (39), `TIMERA` (37), `SETTIMERA` (36), `WAIT` (28), `IS_PED_IN_ANY_VEHICLE` (28), `SET_PED_COMPONENT_VARIATION` (26), `REQUEST_MODEL` (25), `CLEAR_PED_TASKS` (25), `GET_SCRIPT_TASK_STATUS` (23), `IS_ENTITY_AT_COORD` (23), `DELETE_PED` (23), `REPLAY_RECORD_BACK_FOR_TIME` (23), `CLEAR_PRINTS` (22), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (22), `POW` (21), `IS_SYNCHRONIZED_SCENE_RUNNING` (21), `GET_CAM_VIEW_MODE_FOR_CONTEXT` (20)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x34 · `-1.5f` x10 · `11.75f` x8 · `6.75f` x8 · `4.5f` x8 · `30.47077f` x6 · `6424.185f` x6 · `-94.00424f` x6 · `0.25f` x6 · `6.25f` x5 · `-326.3011f` x4 · `6077.182f` x4 · `30.4548f` x4 · `0.9f` x4 · `30.46846f` x4 · `6451.529f` x4 · `-122.7547f` x4 · `28.62807f` x4 · `6501.802f` x4 · `-128.9157f` x4 · `30.1739f` x4 · `6460.759f` x4 · `-157.2882f` x4 · `-390.4958f` x4

## Other strings

Literals whose consuming native was not classified:

`premier`, `RBsetup`, `ruffian`, `PALETO_BAY_SCORE_ALARM`, `sheriff`, `player_two`, `missheistpaletoscoresetup_setup1`, `CMN_HINT`, `Trevor`, `MotionState_Walk`, `bus`, `Lester`, `CBH_COPFAIL`, `CBH_BNKFAIL`, `CMN_GENGETBCK`, `CBH_FCUSHLP`, `M_ThePaletoScoreSetup`, `CBH_LESTDED`, `CBH_AB2BOTH`, `FocusIn`, `FM_IHELP_HNT`, `CBH_LFTAREA`, `CBH_FCUSALM`, `rbhs_mcs_1`, `Michael`, `cops_response_intro_bank_manager`, `cops_response_intro_bank_clerk1`, `cops_response_intro_bank_clerk2`, `cops_response_intro_bank_clerk3`, `CBH_COPFAILT`

---

Source: `decompiled_scripts/rural_bank_setup.c`
