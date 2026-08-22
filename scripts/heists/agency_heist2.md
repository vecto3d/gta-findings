# agency_heist2.c

Heists script. 12 anim dicts; 16 models.

| | |
|---|---|
| Category | Heists |
| Total lines | 115,730 |
| Functions | 774 (105 unique, 669 shared) |
| Unique lines | 6,283 (5.4% of file) |

## Assets

**Animation dictionaries** (12) - `missheist_agency2aig_4`, `missheist_agency2aig_8`, `missheist_agency2aig_3`, `MISSAH_2_EXT_ALTLEADINOUT`, `veh@bike@common@Front@base`, `missagency_heist_2a`, `missheist_agency2aig_2`, `MOVE_P_M_ONE_BRIEFCASE`, `MOVE_P_M_ONE`, `missheistdockssetup1ig_10@idle_d`, `missheist_agency2aig_12`, `missheist_agency2aig_1`

**Animations** (34) - `missheist_agency2aig_8`, `throw_helmet_player1`, `missheist_agency2aig_4`, `missheist_agency2aig_3`, `handsup_exit`, `veh@bike@common@Front@base`, `take_off_helmet_walk`, `missheist_agency2aig_12`, `start_loop_foreman`, `look_at_plan_base`, `handsup_loop`, `MISSAH_2_EXT_ALTLEADINOUT`, `look_plan_base_worker1`, `look_plan_base_worker2`, `throw_helmet_foreman`, `chat_a_worker1`, `chat_a_worker2`, `walk_by_chat_worker1`, `walk_by_chat_worker2`, `chat_b_worker1`, `chat_b_worker2`, `missagency_heist_2a`, `push_button`, `walk_by_worker1`, `walk_by_worker2`, `look_plan_a_worker1`, `look_plan_a_worker2`, `missheist_agency2aig_2`, `look_at_phone_c`, `missheist_agency2aig_1`, `direct_traffic_c`, `handsup_enter`, `HACK_LOOP`, `SOFA_LOOP`

**Models and props** (16) - `s_m_y_construct_01`, `s_m_y_construct_02`, `prop_hard_hat_01`, `u_m_m_fibarchitect`, `prop_cs_walking_stick`, `prop_const_fence02b`, `p_cs_clipboard`, `prop_conslift_lift`, `prop_sub_release`, `prop_chair_06`, `prop_tool_box_05`, `prop_tool_hardhat`, `frogger`, `prop_ld_case_01`, `zion2`, `prop_fnclink_03gate4`

**Audio banks** (3) - `Freight_Elevator`, `FBI_Heist_Mug_Architect`, `SCRIPT\FBI_Heist_Mug_Architect`

**Sounds** (10) - `AGENCY_H_2_TAKE_OUT_ARCHITECT`, `AGENCY_H_2_FOLLOW_ARCHITECT_1`, `AGENCY_H_2_USE_ELEVATOR`, `AGENCY_H_2_FOLLOW_ARCHITECT_2`, `AGENCY_H_2_COVER_BLOWN`, `AGENCY_H_2_LEAVE_SITE`, `Architect_Fall`, `FBI_HEIST_SOUNDSET`, `FBI_HEIST_H2_ARCHITECT_GRAB_CASE`, `FREIGHT_ELEVATOR_02_MOTOR`

**Text labels** (4) - `MICHAEL`, `FRANKLIN`, `NULL`, `H1SET3A`

**Scenarios** (3) - `WORLD_HUMAN_CLIPBOARD`, `WORLD_HUMAN_HANG_OUT_STREET`, `WORLD_HUMAN_SMOKING`

**Waypoint recordings** (3) - `agency2Afloor`, `agency2Aground`, `agency2aground`

**Relationship groups** (2) - `construction workers`, `agency2setupbg`

**Vehicle mods** (1) - `buffalo`

**Hashed names** (2) - `ACT_stealth_kill_a`, `ACT_stealth_kill_b`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (385), `GET_ENTITY_COORDS` (236), `IS_PED_INJURED` (136), `DOES_ENTITY_EXIST` (121), `PLAYER_ID` (71), `SET_PED_COMPONENT_VARIATION` (70), `VDIST2` (66), `GET_GAME_TIMER` (58), `CLEAR_PED_TASKS` (49), `DOES_BLIP_EXIST` (32), `IS_ENTITY_IN_ANGLED_AREA` (29), `REQUEST_MODEL` (28), `HAS_MODEL_LOADED` (26), `DISABLE_CONTROL_ACTION` (26), `VDIST` (24), `IS_ENTITY_DEAD` (23), `REMOVE_BLIP` (23), `IS_SYNCHRONIZED_SCENE_RUNNING` (22), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (20), `GET_SCRIPT_TASK_STATUS` (20), `IS_ENTITY_ATTACHED` (19), `TASK_LOOK_AT_ENTITY` (19), `WAIT` (18), `REQUEST_ANIM_DICT` (18), `TASK_SYNCHRONIZED_SCENE` (18), `IS_PED_IN_ANY_VEHICLE` (17), `IS_PED_ARMED` (17), `SET_ENTITY_COORDS` (17), `SET_PLAYER_CONTROL` (17), `IS_AUDIO_SCENE_ACTIVE` (16)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`4.5f` x8 · `0.5f` x6 · `334.8835f` x6 · `0.1f` x5 · `0.25f` x5 · `1.5f` x5 · `28.7762f` x4 · `-1037.519f` x4 · `-107.925f` x4 · `24.4869f` x4 · `-1113.94f` x4 · `-219.0097f` x4 · `-147.6221f` x3 · `-1033.464f` x3 · `10.5f` x3 · `0.95f` x3 · `113.1388f` x3 · `30.4f` x3 · `-183.1873f` x2 · `-1022.583f` x2 · `28.03928f` x2 · `-160.4385f` x2 · `-938.4265f` x2 · `115.4342f` x2

## Other strings

Literals whose consuming native was not classified:

`FIBConstruction`, `F3A_JANRUN`, `FIBConstruction2`, `WORLD_HUMAN_SMOKING`, `F3A_CONFLEE`, `WORLD_HUMAN_HANG_OUT_STREET`, `worker `, `FIBArchitect`, `S3A_LOST`, `MOVE_P_M_ONE_BRIEFCASE`, `MOVE_P_M_ONE`, `S3A_PICKUP`, `SHOUT_THREATEN`, `WORLD_HUMAN_CLIPBOARD`, `frogger`, `player`, `S3A_ARCLABEL`, `missfbi5ig_21`, `missheist_agency2ahands_up`, `hand_up_scientist`, `handsup_anxious`, `hands_up_shocked_scientist`, `FB3aAUD`, `theagencytwo`, `M_BR2`, `SCRIPTED_SCANNER_REPORT_AH_MUGGING_01`, `F3A_MAKE`, `F3A_GUN`, `F3A_CONSPOT`, `F3A_CONRUN`

---

Source: `decompiled_scripts/agency_heist2.c`
