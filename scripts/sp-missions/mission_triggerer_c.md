# mission_triggerer_c.c

SP missions script. 10 anim dicts; 26 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 118,079 |
| Functions | 985 (161 unique, 824 shared) |
| Unique lines | 4,519 (3.8% of file) |

## Assets

**Animation dictionaries** (10) - `misscarsteal1leadinout@i_fought_the_law`, `missmic1leadinoutmic_1_int`, `missbigscore1leadinoutbs_1_int`, `MISSMARTIN1@LEADINOUTMARTIN_1_INT`, `oddjobs@assassinate@hotel@leaning@`, `misstrevor4leadinouttrv_4_int`, `missheistpaletoscore1leadinoutrbhs_int_1`, `MISSEXILE3`, `missheistdockssetup1ig_13@start_idle`, `misscarsteal1leadin`

**Animations** (36) - `misscarsteal1leadinout@i_fought_the_law`, `missbigscore1leadinoutbs_1_int`, `misscarsteal1leadin`, `misstrevor4leadinouttrv_4_int`, `MISSFBI5LEADINOUT`, `leadin_loop_c_trevor`, `missmic1leadinoutmic_1_int`, `_leadin_michael`, `missheistdockssetup1ig_13@start_idle`, `missheistpaletoscore1leadinoutrbhs_int_1`, `_leadin_trevor`, `MISSMARTIN1@LEADINOUTMARTIN_1_INT`, `leadin_action_a_trevor`, `leadin_action_c_michael`, `leadin_loop_b_trevor`, `leadin_loop_start_idle_floyd`, `leadin_action_floyd`, `leadin_loop_exit_idle_floyd`, `DEVON_Fra_enters_leadin`, `MOLLY_Fra_enters_leadin`, `devon_idle_01`, `molly_idle_01`, `leadin_loop_devin`, `leadin_loop_molly`, `leadin_loop_franklin`, `MicArrive_LeadIn_LOOP_DEVIN`, `MicArrive_LeadIn_LOOP_MOLLY`, `MicArrive_LeadIn_LOOP_FRANKLIN`, `MicArrive_LeadIn_LOOP_TREVOR`, `LEADIN_1_MIC`, `LEADIN_2_MIC`, `LEADIN_2_FRA`, `guard_beatup_startidle_guard1`, `guard_beatup_startidle_dockworker`, `Leadin_loop`, `Leadin_action`

**Models and props** (26) - `v_ilev_trev_doorfront`, `prop_cs_fridge_door`, `prop_cs_fridge`, `prop_cs_beer_bot_01`, `s_m_y_cop_01`, `prop_mil_crate_01`, `a_m_y_genstreet_02`, `s_m_y_marine_03`, `s_m_m_marine_01`, `a_m_m_hillbilly_02`, `crusader`, `player_zero`, `fusilade`, `barracks`, `player_two`, `u_m_m_spyactor`, `u_f_y_spyactress`, `a_f_y_hipster_04`, `prop_a_trailer_door_01`, `felon`, `f620`, `adder`, `a_m_y_business_01`, `dinghy`, `prop_phone_ing_03`, `prop_phone_ing`

**Audio banks** (1) - `SCRIPT\ASSASSINATION_MULTI`

**Sounds** (2) - `ASS_PAYPHONE_RING_master`, `PS_PREP_INTERCEPT_CONVOY`

**Text labels** (17) - `TREVOR`, `DEVIN`, `MICHAEL`, `FRANKLIN`, `MOLLY`, `FH1AUD`, `TRV5AUD`, `FBI5AAU`, `NULL`, `CHHEIST`, `FLOYD`, `CST3AUD`, `FBIPRAU`, `OFF`, `RURALP`, `SLM1AUD`, `CHRETURN`

**Scenarios** (5) - `WORLD_HUMAN_CLIPBOARD`, `WORLD_HUMAN_HANG_OUT_STREET`, `WORLD_HUMAN_BUM_STANDING`, `WORLD_HUMAN_STAND_IMPATIENT`, `WORLD_HUMAN_GUARD_STAND`

**Waypoint recordings** (1) - `paletoleadin`

**Relationship groups** (2) - `Player Group`, `MICHAEL_1_TS_RELGROUP`

**Interiors and entity sets** (1) - `v_trevors`

**Hashed names** (2) - `DOORHASH_T_TRAILER_CS`, `START_CUTSCENE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (205), `DOES_ENTITY_EXIST` (58), `IS_PED_INJURED` (53), `IS_ENTITY_IN_ANGLED_AREA` (47), `GET_ENTITY_COORDS` (41), `VDIST2` (30), `SET_PED_COMPONENT_VARIATION` (29), `TASK_SYNCHRONIZED_SCENE` (28), `SET_MODEL_AS_NO_LONGER_NEEDED` (27), `CREATE_SYNCHRONIZED_SCENE` (26), `SET_BIT` (23), `PLAYER_ID` (23), `SET_SYNCHRONIZED_SCENE_LOOPED` (23), `REQUEST_MODEL` (19), `DISABLE_CONTROL_ACTION` (19), `HAS_MODEL_LOADED` (18), `REMOVE_SCENARIO_BLOCKING_AREA` (16), `CLEAR_BIT` (15), `REMOVE_RELATIONSHIP_GROUP` (12), `ADD_SCENARIO_BLOCKING_AREA` (12), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (11), `IS_GAMEPLAY_HINT_ACTIVE` (11), `GET_GAME_TIMER` (10), `REMOVE_ANIM_DICT` (10), `CLEAR_AREA` (10), `STOP_GAMEPLAY_HINT` (9), `IS_VEHICLE_DRIVEABLE` (9), `CREATE_PED` (9), `SET_PLAYER_CONTROL` (9), `IS_SYNCHRONIZED_SCENE_RUNNING` (9)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x13 · `40.23f` x10 · `66.5f` x10 · `74.83471f` x7 · `3.5f` x7 · `2.5f` x6 · `-1149.71f` x6 · `-1521.09f` x6 · `10.78f` x6 · `1.75f` x5 · `0.25f` x5 · `29.6895f` x5 · `0.8f` x5 · `71.10547f` x4 · `30.15f` x4 · `107.1844f` x4 · `-434.6098f` x4 · `37.23969f` x4 · `124.4786f` x4 · `-385.5533f` x4 · `52.27139f` x4 · `39.69191f` x4 · `3611.205f` x4 · `1393.025f` x4

## Other strings

Literals whose consuming native was not classified:

`Michael`, `Trevor`, `player_zero`, `Franklin`, `player_two`, `CAR_1_INT_CONCAT`, `FBI_5_INT`, `MIC1_LEFT_HOUSE`, `misstrevor4leadinouttrv_4_int`, `PS_PREP_VEHICLES_GROUP`, `barracks`, `crusader`, `missbigscore1leadinoutbs_1_int`, `fusilade`, `felon`, `f620`, `adder`, `dinghy`, `AM_H_PREP4`, `AM_RHP_REAP`, `Rural_prep_trigger1`, `Rural_prep_trigger2`, `AM_RHP_MISS`, `MIC1_PRE_MISSION_MUSIC`, `MIC_1_INT`, `leadin_action_a_fridge_door`, `leadin_action_a_fridge`, `FH1_INTLI3`, `FH1_INTLI4`, `hand_shake`

---

Source: `decompiled_scripts/mission_triggerer_c.c`
