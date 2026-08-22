# family4.c

SP missions script. 12 anim dicts; 17 models; 2 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 128,774 |
| Functions | 1,035 (135 unique, 900 shared) |
| Unique lines | 10,452 (8.1% of file) |

## Assets

**Animation dictionaries** (12) - `missfam4`, `missfam4leadinoutmcs2`, `veh@truck@ds@idle_panic`, `amb@prop_human_seat_chair@male@elbows_on_knees@react_shock`, `amb@prop_human_seat_chair@male@generic_skinny@react_shock`, `amb@prop_human_seat_chair@male@left_elbow_on_knee@react_shock`, `amb@prop_human_seat_chair@female@arms_folded@react_shock`, `amb@prop_human_seat_chair@female@legs_crossed@react_shock`, `amb@prop_human_seat_chair@female@proper@react_shock`, `amb@prop_human_seat_chair@female@proper_skinny@react_shock`, `missfam4mcs3`, `missfamily4_fameshame`

**Animations** (19) - `missfam4`, `missfam4mcs3`, `base`, `loop_lazlow`, `say_hurry_up_a_trevor`, `veh@truck@ds@idle_panic`, `sit`, `amb@prop_human_seat_chair@male@elbows_on_knees@react_shock`, `amb@prop_human_seat_chair@male@generic_skinny@react_shock`, `amb@prop_human_seat_chair@male@left_elbow_on_knee@react_shock`, `amb@prop_human_seat_chair@female@arms_folded@react_shock`, `amb@prop_human_seat_chair@female@legs_crossed@react_shock`, `amb@prop_human_seat_chair@female@proper@react_shock`, `amb@prop_human_seat_chair@female@proper_skinny@react_shock`, `missfam4leadinoutmcs2`, `tracy_loop`, `loop_intro_lazlow`, `missfamily4_fameshame`, `lazlow_getincar_l`

**Models and props** (17) - `a_m_y_hipster_03`, `sentinel`, `schafter2`, `a_f_y_hipster_03`, `manana`, `prop_gascyl_01a`, `v_ilev_chair02_ped`, `a_m_y_bevhills_02`, `towtruck`, `premier`, `freight`, `p_cs_clipboard`, `prop_v_bmike_01`, `prop_v_cam_01`, `s_m_y_doorman_01`, `p_laz_j02_s`, `taco`

**Audio banks** (1) - `SCRIPT\FAM4_UNHITCH_TRAILER`

**Sounds** (13) - `FAMILY_4_CHASE_TRUCK_1`, `FAMILY_4_CHASE_TRUCK_2`, `FAMILY_4_CHASE_TRUCK_CAMERA`, `FAMILY_4_CHASE_TRUCK_TRACKS`, `FAMILY_4_CHASE_TRUCK_TUNNEL`, `FAMILY_4_CHASE_TRUCK_JUMP`, `FAMILY_4_CHASE_FOOT`, `FAMILY_4_CHASE_FOOT_OUTSIDE`, `FAMILY_4_DRIVE_TO_STADIUM`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `UNHITCH_TRAILER`, `FAM4_UNHITCH_TRAILER`

**Particle effects** (2) - `scr_fam4_truck_vent`, `scr_fam4_trailer_sparks`

**Text labels** (2) - `NULL`, `NUMBER`

**Scenarios** (8) - `base`, `amb@prop_human_seat_chair@male@elbows_on_knees@base`, `amb@prop_human_seat_chair@male@generic_skinny@base`, `amb@prop_human_seat_chair@male@left_elbow_on_knee@base`, `amb@prop_human_seat_chair@female@arms_folded@base`, `amb@prop_human_seat_chair@female@legs_crossed@base`, `amb@prop_human_seat_chair@female@proper@base`, `amb@prop_human_seat_chair@female@proper_skinny@base`

**Waypoint recordings** (3) - `family4_1`, `family4_0`, `family4_2`

**Vehicle recordings** (2) - `lkfamily4`, `lkfamily4b`

**Relationship groups** (3) - `players group`, `enemy group`, `gropie group`

**Interiors and entity sets** (2) - `v_stadium`, `V_Michael`

**Doors** (1) - `v_ilev_stad_fdoor`

**Vehicle mods** (6) - `utillitruck`, `utillitruck2`, `utillitruck3`, `towtruck`, `schafter2`, `taxi`

**Hashed names** (2) - `GtaMloRoom004`, `GtaMloRoom001`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (306), `DOES_ENTITY_EXIST` (148), `REQUEST_VEHICLE_RECORDING` (121), `HAS_VEHICLE_RECORDING_BEEN_LOADED` (121), `GET_ENTITY_COORDS` (109), `HAS_MODEL_LOADED` (107), `REQUEST_MODEL` (104), `SET_MODEL_AS_NO_LONGER_NEEDED` (70), `IS_VEHICLE_DRIVEABLE` (62), `SET_VEHICLE_MODEL_IS_SUPPRESSED` (50), `GET_DISTANCE_BETWEEN_COORDS` (46), `CREATE_VEHICLE` (46), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (43), `SET_ENTITY_HEADING` (41), `IS_ENTITY_IN_ANGLED_AREA` (40), `IS_PED_INJURED` (40), `PLAYER_ID` (39), `GET_TIME_POSITION_IN_RECORDING` (38), `CLEAR_AREA` (35), `SET_ENTITY_COORDS` (33), `CLOSE_SEQUENCE_TASK` (32), `OPEN_SEQUENCE_TASK` (31), `TASK_PERFORM_SEQUENCE` (31), `SET_VEHICLE_AS_NO_LONGER_NEEDED` (31), `WAIT` (30), `CLEAR_SEQUENCE_TASK` (30), `START_PLAYBACK_RECORDED_VEHICLE` (28), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (25), `STOP_PLAYBACK_RECORDED_VEHICLE` (24), `GET_GAME_TIMER` (24)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x22 · `0.5f` x21 · `29.1458f` x19 · `26.6199f` x13 · `0.01f` x12 · `23.6855f` x11 · `-221.051f` x9 · `-2039.714f` x9 · `26.62f` x9 · `-217.358f` x9 · `-2033.186f` x9 · `29.62f` x9 · `26.6207f` x8 · `-239.1158f` x7 · `-2005.142f` x7 · `0.2f` x7 · `-260.7652f` x7 · `-2026.163f` x7 · `23.6856f` x6 · `1.58f` x6 · `0.59f` x6 · `-249.8176f` x6 · `-2008.059f` x6 · `-800.31f` x6

## Other strings

Literals whose consuming native was not classified:

`sentinel`, `schafter2`, `manana`, `trevor`, `fam4aud`, `michael`, `fam4Aud`, `default_scripted_camera`, `MotionState_Walk`, `family4_fail_11`, `MotionState_Run`, `family4_fail_1`, `lazlow`, `family4_fail_3`, `speedo`, `judges_security`, `family4_fail_0`, `family4_fail_6`, `Lazlow`, `Lazlow_Jeans`, `phantom`, `lkfamily4`, `FAM4_MISSION_START`, `family4_fail_9`, `player`, `outside stadium`, `Tracy`, `FAM4_DRV2`, `family4_god_5`, `right`

---

Source: `decompiled_scripts/family4.c`
