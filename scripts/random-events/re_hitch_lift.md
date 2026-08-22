# re_hitch_lift.c

Random events script. 3 anim dicts; 7 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 12,524 |
| Functions | 275 (43 unique, 232 shared) |
| Unique lines | 4,867 (38.9% of file) |

## Assets

**Animation dictionaries** (3) - `random@hitch_lift`, `facials@gen_female@base`, `move_m@brave`

**Animations** (9) - `random@hitch_lift`, `idle_f`, `f_distressed_loop`, `001445_01_gangintimidation_1_female_idle_b`, `carjack_mainloop_female`, `facials@gen_female@base`, `mood_sleeping_1`, `come_here_idle_c`, `idle_a`

**Models and props** (7) - `prop_fnclink_03gate1`, `a_m_m_business_01`, `a_f_y_hiker_01`, `a_f_y_hipster_03`, `s_m_m_security_01`, `ig_bride`, `a_m_y_business_01`

**Audio banks** (1) - `timer`

**Sounds** (6) - `TIMER_SCENE`, `VARIABLE_COUNTDOWN_CLOCK_wp`, `countdown_fadein`, `countdown_fast`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Text labels** (10) - `BUSINESSMAN`, `NULL`, `MICHAEL`, `TREVOR`, `FRANKLIN`, `REHH1AU`, `REHH2AU`, `REHH3AU`, `REHH5AU`, `COP`

**Scenarios** (2) - `WORLD_HUMAN_STAND_MOBILE`, `WORLD_HUMAN_HANG_OUT_STREET`

**Relationship groups** (1) - `rghBoyfriend`

**Doors** (1) - `prop_fnclink_03gate1`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (259), `IS_PED_INJURED` (112), `TASK_LOOK_AT_ENTITY` (52), `IS_PED_IN_ANY_VEHICLE` (42), `WAIT` (38), `GET_GAME_TIMER` (35), `DOES_BLIP_EXIST` (34), `PLAYER_ID` (31), `OPEN_SEQUENCE_TASK` (30), `CLOSE_SEQUENCE_TASK` (30), `TASK_PERFORM_SEQUENCE` (30), `CLEAR_SEQUENCE_TASK` (30), `GET_PLAYERS_LAST_VEHICLE` (30), `IS_VEHICLE_DRIVEABLE` (25), `GET_ENTITY_COORDS` (24), `TASK_FOLLOW_NAV_MESH_TO_COORD` (24), `SETTIMERA` (23), `GET_VEHICLE_PED_IS_IN` (22), `DOES_ENTITY_EXIST` (20), `REMOVE_BLIP` (20), `TASK_TURN_PED_TO_FACE_ENTITY` (19), `SET_PED_COMPONENT_VARIATION` (19), `IS_ENTITY_AT_COORD` (16), `DISABLE_CONTROL_ACTION` (16), `CLEAR_PED_TASKS` (14), `CLEAR_PED_SECONDARY_TASK` (14), `IS_ENTITY_AT_ENTITY` (13), `REMOVE_PED_FROM_GROUP` (13), `IS_PLAYER_PRESSING_HORN` (13), `TASK_PLAY_ANIM` (13)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x24 · `2.5f` x10 · `801.7148f` x6 · `1270.138f` x6 · `359.2855f` x6 · `802.9218f` x6 · `1281.675f` x6 · `359.2962f` x6 · `10.5f` x3 · `-1055.515f` x2 · `-2533.221f` x2 · `19.3049f` x2 · `-1046.832f` x2 · `-2518.146f` x2 · `12.9447f` x2 · `170.3572f` x2 · `1.5f` x2 · `655.7768f` x2 · `1282.45f` x2 · `359.048f` x2 · `802.4241f` x2 · `1278.077f` x2 · `382.4866f` x2 · `178.993f` x1

## Other strings

Literals whose consuming native was not classified:

`REHH1_HHOUR`, `REHH1_VEH`, `REHH1_VEH2`, `TIMER_TIME`, `REHH2_VEH`, `REHH2_VEH2`, `REHH2_SLW`, `REHH1_NOV`, `REHH3_VEH`, `REHH3_VEH2`, `REHH5_VEH`, `REHH5_VEH2`, `REHH3_SLW`, `REHH5_SLW`, `REHH1_1HOUR`, `REHH1_CRASH`, `REHH5_STO`, `REHH2Hiker`, `REHH3Hipster`, `REHH5Bride`, `REHH3_AGG`, `REHH1_WLK`, `REHH2_WLK`, `REHH3_WLK`, `REHH5_WLK`, `REHH1_SLR`, `REHH1_SLW`, `REHH1_OUT`, `REHH2_GETOUT`, `REHH3_GETOUT`

---

Source: `decompiled_scripts/re_hitch_lift.c`
