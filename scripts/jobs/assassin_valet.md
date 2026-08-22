# assassin_valet.c

Jobs script. 5 anim dicts; 11 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 24,956 |
| Functions | 554 (145 unique, 409 shared) |
| Unique lines | 5,825 (23.3% of file) |

## Assets

**Animation dictionaries** (5) - `oddjobs@assassinate@hotel@`, `ODDJOBS@ASSASSINATE@GUARD`, `oddjobs@assassinate@hotel@leadin`, `oddjobs@assassinate@hotel@leaning@`, `move_lester_CaneUp`

**Animations** (15) - `oddjobs@assassinate@hotel@`, `ODDJOBS@ASSASSINATE@GUARD`, `alert_gunshot`, `enter`, `oddjobs@assassinate@hotel@leadin`, `idle_a`, `Lester_Getup`, `base`, `oddjobs@assassinate@hotel@leaning@`, `unarmed_earpiece_a`, `unarmed_earpiece_b`, `unarmed_fold_arms`, `unarmed_look`, `argue_b`, `lester_leadin`

**Models and props** (11) - `a_m_m_bevhills_01`, `a_f_m_bevhills_02`, `a_m_y_hipster_01`, `a_f_m_bevhills_01`, `ig_lestercrest`, `prop_cs_walking_stick`, `taxi`, `a_m_y_beachvesp_02`, `s_m_m_highsec_01`, `s_m_m_highsec_02`, `prop_bench_08`

**Audio banks** (1) - `SCRIPT\ASSASSINATION_MULTI`

**Sounds** (4) - `ASSASSINATIONS_HOTEL_TIMER_COUNTDOWN`, `ASSASSINATION_MULTI`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Text labels** (6) - `OJASAUD`, `COP`, `NULL`, `OFF`, `LESTER`, `FRANKLIN`

**Scenarios** (3) - `WORLD_HUMAN_GUARD_STAND`, `WORLD_HUMAN_TOURIST_MOBILE`, `WORLD_HUMAN_TOURIST_MAP`

**Waypoint recordings** (4) - `OJASva_104`, `OJASva_101a`, `OJASva_101`, `OJAS_HotelTaxi01`

**Vehicle recordings** (1) - `ASSOJva`

**Relationship groups** (1) - `Guards`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (153), `DOES_ENTITY_EXIST` (103), `IS_PED_INJURED` (100), `IS_ENTITY_DEAD` (96), `IS_VEHICLE_DRIVEABLE` (50), `GET_SCRIPT_TASK_STATUS` (40), `IS_PED_IN_ANY_VEHICLE` (33), `SET_PED_COMPONENT_VARIATION` (30), `IS_PED_IN_VEHICLE` (29), `CLEAR_SEQUENCE_TASK` (25), `PLAYER_ID` (24), `OPEN_SEQUENCE_TASK` (19), `CLOSE_SEQUENCE_TASK` (19), `TASK_PERFORM_SEQUENCE` (18), `GET_ENTITY_COORDS` (16), `GET_RANDOM_INT_IN_RANGE` (16), `SET_PED_COMBAT_ATTRIBUTES` (15), `TASK_PLAY_ANIM` (15), `TASK_COMBAT_PED` (14), `GET_VEHICLE_PED_IS_IN` (13), `GET_ENTITY_MODEL` (12), `GET_PED_IN_VEHICLE_SEAT` (12), `REQUEST_MODEL` (12), `HAS_MODEL_LOADED` (12), `DOES_BLIP_EXIST` (11), `TASK_ENTER_VEHICLE` (11), `SET_MODEL_AS_NO_LONGER_NEEDED` (11), `IS_ENTITY_IN_ANGLED_AREA` (10), `IS_PLAYER_WANTED_LEVEL_GREATER` (10), `TASK_LEAVE_ANY_VEHICLE` (10)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x10 · `0.2f` x9 · `-1220.57f` x5 · `-185.96f` x5 · `38.4f` x5 · `0.0498f` x5 · `1.5f` x4 · `38.3251f` x4 · `0.1f` x3 · `0.25f` x3 · `-9.2001f` x3 · `6.3064f` x3 · `38.3255f` x3 · `-100.7554f` x3 · `100.8606f` x3 · `44.5f` x2 · `-1223.024f` x2 · `-187.3076f` x2 · `-1220.311f` x2 · `-186.2481f` x2 · `40.42538f` x2 · `38.3253f` x2 · `3.519839f` x2 · `-0.000706f` x2

## Other strings

Literals whose consuming native was not classified:

`FIRING_PATTERN_FULL_AUTO`, `OJAvaGUARD`, `HAND_SHAKE`, `Lester`, `ASS_VA_LOSECOPS`, `WalkingStick_Lester`, `ASS_VA_COMP`, `OJAvaGUARD2`, `OJASva_PANIC`, `ASS1_LOST`, `ASS1_FAIL`, `OJASva_CAR3`, `OJASva_CAR3_1`, `OJAS_FEED`, `ASS_VA_COVER`, `OJASva_EXPLO`, `OJASva_SNIPE`, `OJAva_TARGET`, `OJASva_TARG`, `ASS1_ALERT`, `ASS_VA_GO`, `OJAS_HOCOM`, `taxi`, `move_lester_CaneUp`, `player`, `Franklin`, `fbi2`, `washington`, `M_ASS1`, `OJASva_CAR2`

---

Source: `decompiled_scripts/assassin_valet.c`
