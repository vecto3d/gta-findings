# mission_triggerer_a.c

SP missions script. 7 anim dicts; 39 models; 4 scaleforms.

| | |
|---|---|
| Category | SP missions |
| Total lines | 112,201 |
| Functions | 814 (121 unique, 693 shared) |
| Unique lines | 4,465 (4.0% of file) |

## Assets

**Animation dictionaries** (7) - `MISSHEIST_JEWELLEADINOUT`, `MissLester1ALeadInOut`, `missheist_jewelleadinoutjh_endscene`, `misslsdhsclipboard@base`, `misstimelapse@franklinold_home`, `get_up@directional@movement@from_knees@panic`, `missarmenian3leadinoutArmenian_3_int`

**Animations** (30) - `MISSHEIST_JEWELLEADINOUT`, `get_up@directional@movement@from_knees@panic`, `missfam3leadinoutfam_3_int`, `_leadout_coach`, `lester_1st_suitless_entrance_negative_a`, `lester_base_idle`, `MissLester1ALeadInOut`, `get_up_180`, `get_up_0`, `missarmenian3leadinoutArmenian_3_int`, `missheist_jewelleadinoutjh_endscene`, `missarmenian3leadinoutarmenian_3_int`, `Lester_Leadin_Action`, `lester_hanging_around_suitless_negative_a`, `action_mic`, `loop_mic`, `_leadin_look_left_simeon`, `_leadin_look_right_simeon`, `_leadin_customer`, `_intro_loop_simeon`, `_intro_loop_customer`, `misslsdhsclipboard@base`, `base`, `lester_leadin_loop`, `missarmenian2leadinoutint_alt2`, `arm_2_int_alt2_leadin`, `lester_1_int_leadin_doorway_michael`, `lester_1_int_leadin_doorway_cam`, `Lester_1_INT_LeadIn_loop_Lester`, `Lester_1_INT_LeadIn_action_Lester`

**Models and props** (39) - `v_ilev_ss_door02`, `s_m_m_armoured_01`, `s_m_y_pestcont_01`, `prop_cctv_cam_06a`, `prop_cs_walking_stick`, `s_m_m_security_01`, `ig_lestercrest`, `prop_wheelchair_01_s`, `p_cctv_s`, `prop_tennis_rack_01`, `prop_tumbler_01_empty`, `tailgater`, `prop_box_ammo03a`, `s_m_y_swat_01`, `burrito2`, `p_amb_clipboard_01`, `v_ilev_fib_door1`, `prop_employee_month_02`, `prop_tennis_rack_01b`, `a_m_m_bevhills_02`, `dilettante2`, `ig_tenniscoach`, `bjxl`, `fbi2`, `boxville3`, `prop_idol_case_02`, `prop_yell_plastic_target`, `ig_siemonyetarian`, `baller`, `schwarzer`, `v_ilev_fa_frontdoor`, `blista`, `premier`, `player_zero`, `player_two`, `s_m_y_cop_01`, `prop_employee_month_01`, `bison2`, `bullet`

**Audio banks** (2) - `Lester1A_01`, `FAMILY3_2`

**Sounds** (6) - `LESTER_1A_ENTER_LESTERS_HOUSE`, `FAMILY3_COACH_OUT_WINDOW_MASTER`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `UNLOCK_DOOR`, `LESTER1A_SOUNDS`

**Scaleform movies** (4) - `SECURITY_CAM`, `SET_TIME`, `SET_DETAILS`, `SET_LOCATION`

**Text labels** (16) - `MICHAEL`, `JHS1AUD`, `ARM3AUD`, `FAM3AUD`, `SIMEON`, `LS1AAUD`, `TREVOR`, `FRANKLIN`, `AMANDA`, `TENNISCOACH`, `NULL`, `FBIPRAU`, `JHP1B`, `AR2AUD`, `LESTER`, `JH1TRIG`

**Scenarios** (2) - `SEW_MACHINE`, `WORLD_HUMAN_STAND_MOBILE`

**Waypoint recordings** (1) - `bb_jew_7`

**Relationship groups** (3) - `Player Group`, `FAMILY_3_TS_RELGROUP`, `TS_LES1A`

**Timecycle modifiers** (1) - `scanline_cam`

**Interiors and entity sets** (2) - `po1_08_warehouseint1`, `v_carshowroom`

**Doors** (4) - `prop_com_gar_door_01`, `v_ilev_mm_doorw`, `v_ilev_csr_door_l`, `v_ilev_csr_door_r`

**Vehicle mods** (1) - `boxville3`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (222), `SET_PED_COMPONENT_VARIATION` (61), `IS_PED_INJURED` (52), `IS_ENTITY_IN_ANGLED_AREA` (50), `DOES_ENTITY_EXIST` (49), `SET_MODEL_AS_NO_LONGER_NEEDED` (41), `SET_VEHICLE_EXTRA` (24), `SET_BIT` (24), `REQUEST_MODEL` (22), `GET_ENTITY_COORDS` (22), `CREATE_VEHICLE` (21), `IS_DOOR_REGISTERED_WITH_SYSTEM` (20), `HAS_MODEL_LOADED` (19), `DOOR_SYSTEM_SET_DOOR_STATE` (18), `GET_GAME_TIMER` (17), `DISABLE_CONTROL_ACTION` (17), `IS_PED_IN_ANY_VEHICLE` (16), `CREATE_SYNCHRONIZED_SCENE` (15), `TASK_SYNCHRONIZED_SCENE` (15), `IS_VEHICLE_DRIVEABLE` (15), `IS_SYNCHRONIZED_SCENE_RUNNING` (14), `IS_ENTITY_DEAD` (14), `REMOVE_RELATIONSHIP_GROUP` (14), `IS_ENTITY_AT_COORD` (13), `GET_VEHICLE_PED_IS_IN` (13), `GET_SYNCHRONIZED_SCENE_PHASE` (12), `SET_VEHICLE_COLOURS` (12), `GET_CLOCK_HOURS` (12), `CLEAR_BIT` (12), `PLAYER_ID` (11)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x19 · `-37.20001f` x10 · `-1114.964f` x10 · `25.43914f` x10 · `3.5f` x7 · `0.25f` x7 · `25.4223f` x7 · `716.06f` x7 · `-965.837f` x7 · `29.396f` x7 · `6.75f` x7 · `1276.49f` x6 · `-1720.06f` x6 · `56.47f` x6 · `29.43694f` x6 · `-1105.479f` x6 · `-46.89022f` x6 · `709.9806f` x6 · `-963.5297f` x6 · `30.546f` x6 · `25.85983f` x6 · `-1098.932f` x6 · `-43.78194f` x6 · `2.5625f` x6

## Other strings

Literals whose consuming native was not classified:

`Lamar`, `Amanda`, `Lester`, `player_two`, `player_zero`, `tailgater`, `fbi2`, `MissLester1ALeadInOut`, `blista`, `bison2`, `Michael`, `Franklin`, `missarmenian3leadinoutArmenian_3_int`, `bjxl`, `boxville3`, `MISSHEIST_JEWELLEADINOUT`, `ARMENIAN_3_INT`, `ARM3_INT_LI`, `AZL_LESTERS_DOGS`, `MotionState_Run`, `player`, `premier`, `AM_H_JHP1B_REAP`, `JHP1bRoute2`, `JHP1b`, `AM_H_JHP1B_MISS`, `AM_H_JHP2A_REAP`, `AM_H_JHP2A_MISS`, `burrito2`, `dilettante2`

---

Source: `decompiled_scripts/mission_triggerer_a.c`
