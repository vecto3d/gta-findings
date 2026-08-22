# assassin_multi.c

SP missions script. 11 anim dicts; 16 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 24,840 |
| Functions | 539 (96 unique, 443 shared) |
| Unique lines | 3,838 (15.5% of file) |

## Assets

**Animation dictionaries** (11) - `oddjobs@assassinate@multi@call`, `ODDJOBS@assassinate@vice@incar`, `misscommon@response`, `veh@boat@marquis@rps@enter_exit`, `mini@hookers_spvanilla`, `ODDJOBS@assassinate@old_lady`, `move_m@casual@d`, `oddjobs@assassinate@multi@windowwasher`, `oddjobs@assassinate@multi@yachttarget@lapdance`, `amb@world_human_sunbathe@female@back@idle_a`, `oddjobs@assassinate@multi@`

**Animations** (29) - `oddjobs@assassinate@multi@yachttarget@lapdance`, `oddjobs@assassinate@multi@windowwasher`, `oddjobs@assassinate@multi@`, `exit_cower_loop_f`, `exit_quick_f`, `misscommon@response`, `idle_a_pros`, `yacht_ld_m`, `yacht_ld_f`, `_shot_reaction`, `bring_it_on`, `threaten`, `react_big_variations_a`, `react_big_variations_b`, `react_big_variations_c`, `idle_a`, `_idle`, `ODDJOBS@ASSASSINATE@VICE@HOOKER`, `idle_b`, `veh@boat@marquis@rps@enter_exit`, `jump_out`, `exit_steer_m`, `exit_steer_f`, `_idle_to_up`, `_wash_loop`, `_up_loop`, `_up_to_wash`, `oddjobs@assassinate@multi@call`, `ass_multi_target_call_p1`

**Models and props** (16) - `a_f_y_beach_01`, `a_f_y_fitness_02`, `p_phonebox_01b_s`, `premier`, `dilettante`, `vigero`, `seashark`, `camper`, `bjxl`, `u_m_y_sbike`, `s_m_y_winclean_01`, `prop_bmu_02_ld`, `prop_bmu_02_ld_sup`, `a_m_m_beach_01`, `u_m_y_babyd`, `prop_phonebox_01b`

**Audio banks** (1) - `SCRIPT\ASSASSINATION_MULTI`

**Sounds** (3) - `HUD_MINI_GAME_SOUNDSET`, `10_SEC_WARNING`, `TIMER_STOP`

**Text labels** (5) - `OJASAUD`, `NULL`, `FRANKLIN`, `LESTER`, `INVESTOR`

**Scenarios** (1) - `WORLD_HUMAN_SUNBATHE`

**Waypoint recordings** (9) - `OJASbs_102`, `OJASbs01`, `OJASbs02`, `OJASbs03`, `OJASbs04`, `OJAShk_101`, `OJAShk_102`, `OJAShk_103`, `OJAShk_104`

**Relationship groups** (1) - `Target`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (62), `DOES_ENTITY_EXIST` (39), `IS_PED_INJURED` (37), `PLAYER_ID` (23), `TASK_PLAY_ANIM` (22), `GET_SCRIPT_TASK_STATUS` (21), `SET_PED_COMPONENT_VARIATION` (18), `GET_IS_WAYPOINT_RECORDING_LOADED` (18), `IS_ENTITY_DEAD` (17), `REQUEST_MODEL` (13), `DOES_ROPE_EXIST` (12), `HAS_MODEL_LOADED` (11), `DOES_BLIP_EXIST` (10), `CLEAR_SEQUENCE_TASK` (9), `IS_VEHICLE_DRIVEABLE` (9), `SET_PED_COMBAT_ATTRIBUTES` (9), `GET_ENTITY_COORDS` (9), `CREATE_VEHICLE` (9), `REQUEST_WAYPOINT_RECORDING` (9), `OPEN_SEQUENCE_TASK` (8), `CLOSE_SEQUENCE_TASK` (8), `TASK_PERFORM_SEQUENCE` (8), `SET_MODEL_AS_NO_LONGER_NEEDED` (8), `SET_PED_AS_NO_LONGER_NEEDED` (8), `SET_ENTITY_LOAD_COLLISION_FLAG` (8), `TASK_SMART_FLEE_PED` (8), `GET_RANDOM_INT_IN_RANGE` (8), `SETTIMERA` (7), `REMOVE_BLIP` (7), `SET_VEHICLE_AS_NO_LONGER_NEEDED` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-648.59f` x4 · `305.73f` x4 · `-638.93f` x3 · `304.92f` x3 · `0.2f` x3 · `-700.1226f` x3 · `-916.8699f` x3 · `18.1667f` x3 · `-690.763f` x2 · `-1607.467f` x2 · `-100.9649f` x2 · `-404.4197f` x2 · `-1856.529f` x2 · `100.5908f` x2 · `-644.93f` x2 · `-0.10296f` x2 · `-468.8926f` x2 · `-2182.363f` x2 · `0.5f` x2 · `18.0173f` x2 · `-480.9742f` x1 · `-1801.922f` x1 · `19.28045f` x1 · `-712.8968f` x1

## Other strings

Literals whose consuming native was not classified:

`OJASml_ytT1`, `ASS_ML_T01`, `ASS_HK_COMP`, `ASS_BS_COMP`, `ASS_ML_COMP`, `premier`, `dilettante`, `vigero`, `WINDOWWASHERFALL_MASTER`, `OJASml_bkTP2`, `ASS_HK_LOST`, `OJAmlGymOnlookerF`, `OJASml_bbId0`, `OJAmlBODYBUILDER`, `OJAmlYACHTTARGET`, `OJAmlBIKER`, `seat_dside_r`, `player`, `ASS_TIME`, `OJAS_BDCOM`, `OJAS_YACOM`, `OJAS_WWCOM`, `OJAS_BICOM`, `ASS_ML_COPS`, `SCRIPTED_SCANNER_REPORT_ASS_MULTI_01`, `OJASml_wwTP`, `OJAS_MULTI_C`, `OJASml_ytT1_1`, `OJASml_bkTP1`, `M_ASS2`

---

Source: `decompiled_scripts/assassin_multi.c`
