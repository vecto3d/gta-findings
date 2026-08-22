# re_shoprobbery.c

Random events script. 2 anim dicts; 9 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 12,574 |
| Functions | 248 (38 unique, 210 shared) |
| Unique lines | 2,761 (22.0% of file) |

## Assets

**Animation dictionaries** (2) - `random@robbery`, `random@shop_robbery`

**Animations** (19) - `random@shop_robbery`, `random@robbery`, `kneel_getup_p`, `exit_flee`, `stand_worried_female`, `robbery_intro_loop_f`, `cower`, `f_distressed_loop`, `robbery_action_p`, `robbery_action_b`, `robbery_action_a`, `robbery_action_f`, `robbery_intro_loop_a`, `run`, `robbery_main_female`, `kneel_loop_p`, `f_cower_02`, `f_cower_01`, `robbery_intro_loop_b`

**Models and props** (9) - `prop_cs_duffel_01`, `prop_anim_cash_pile_01`, `g_m_y_korean_01`, `a_f_y_bevhills_02`, `a_m_y_hipster_01`, `a_f_y_hipster_04`, `a_m_y_bevhills_02`, `v_ilev_clothmiddoor`, `g_m_y_strpunk_02`

**Speech contexts** (4) - `G_M_Y_KorLieut_01_Korean_MINI_01`, `G_M_Y_Korean_01_Korean_MINI_02`, `A_M_Y_BevHills_01_White_Mini_01`, `A_M_Y_BeachVesp_01_White_Mini_01`

**Text labels** (7) - `REROBAU`, `WHIMPER`, `COP`, `NULL`, `MICHAEL`, `FRANKLIN`, `TREVOR`

**Waypoint recordings** (2) - `re_shoprobbery`, `re_shoprobbery2`

**Relationship groups** (1) - `ROBBERS`

**Interiors and entity sets** (1) - `Hair_room`

**Doors** (1) - `v_ilev_clothmiddoor`

**Vehicle mods** (1) - `baller`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_PED_INJURED` (93), `PLAYER_PED_ID` (90), `DOES_ENTITY_EXIST` (43), `DOES_BLIP_EXIST` (34), `SET_PED_KEEP_TASK` (31), `SET_PED_COMPONENT_VARIATION` (30), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (28), `REMOVE_BLIP` (24), `GET_ENTITY_COORDS` (22), `CLEAR_SEQUENCE_TASK` (19), `OPEN_SEQUENCE_TASK` (19), `CLOSE_SEQUENCE_TASK` (19), `TASK_PERFORM_SEQUENCE` (19), `SET_PED_AS_NO_LONGER_NEEDED` (19), `PLAYER_ID` (18), `TASK_PLAY_ANIM` (17), `TASK_SYNCHRONIZED_SCENE` (16), `SET_ENTITY_LOAD_COLLISION_FLAG` (15), `SET_PED_COMBAT_ATTRIBUTES` (15), `IS_ENTITY_IN_ANGLED_AREA` (15), `REQUEST_MODEL` (14), `TASK_SMART_FLEE_COORD` (13), `CLEAR_PED_TASKS` (12), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (12), `SET_PED_NAME_DEBUG` (12), `TASK_SMART_FLEE_PED` (11), `SET_PED_CONFIG_FLAG` (11), `GET_PLAYERS_LAST_VEHICLE` (11), `WAIT` (11), `IS_ENTITY_AT_COORD` (10)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`2.25f` x6 · `-823.1281f` x4 · `-187.9591f` x4 · `36.6189f` x4 · `-1201.017f` x4 · `-777.5527f` x4 · `16.3398f` x4 · `1.5f` x4 · `0.06f` x3 · `-1201.476f` x3 · `-790.2733f` x3 · `15.5475f` x3 · `0.25f` x3 · `11.9375f` x3 · `-1204.031f` x3 · `-779.629f` x3 · `16.33565f` x3 · `-1174.799f` x3 · `-757.0704f` x3 · `21.01281f` x3 · `12.125f` x3 · `-1206.545f` x3 · `-777.8941f` x3 · `21.20355f` x3

## Other strings

Literals whose consuming native was not classified:

`RE51A_SHOP`, `DEFAULT_ANIMATED_CAMERA`, `REROB_CH2`, `REROB_CH`, `WAVELOAD_PAIN_FEMALE`, `player`, `pedWorker[0]`, `pedWorker[1]`, `pedShopper[0]`, `pedShopper[1]`, `MotionState_Run`, `robbery_action_cam`, `robbery_action_bag`, `baller`, `RE_SR`, `REROB_CH2_1`, `REROB_CH_1`, `REROB_CLAWAY`, `REROB_LSTH`, `REROB_CLLOST`, `REROBRobber1`, `return_bag_stand_b`, `return_bag_stand_b_female`, `return_bag_stand_b_bag`, `return_bag_stand_b_cam`, `return_bag_stand_c_rt`, `return_bag_stand_c_rt_female`, `return_bag_stand_c_rt_bag`, `return_bag_stand_c_rt_cam`, `REROB_TKH`

---

Source: `decompiled_scripts/re_shoprobbery.c`
