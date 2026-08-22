# re_drunkdriver.c

Random events script. 6 anim dicts; 4 models; 1 particle effects.

| | |
|---|---|
| Category | Random events |
| Total lines | 12,169 |
| Functions | 278 (41 unique, 237 shared) |
| Unique lines | 3,959 (32.5% of file) |

## Assets

**Animation dictionaries** (6) - `MOVE_M@DRUNK@VERYDRUNK`, `MOVE_M@DRUNK@SLIGHTLYDRUNK`, `MOVE_M@DRUNK@MODERATEDRUNK_HEAD_UP`, `MOVE_M@DRUNK@MODERATEDRUNK`, `random@drunk_driver_1`, `random@drunk_driver_2`

**Animations** (23) - `random@drunk_driver_2`, `random@drunk_driver_1`, `cardrunksex_loop_f`, `cardrunksex_outro_m`, `driver_idle_m`, `cardrunksex_loop_m`, `driver_enter_m`, `driver_exit_m`, `drunk_fall_over`, `cardrunksex_intro_m`, `exit_1`, `drunk_argument_dd1`, `drunk_argument_dd2`, `drunk_breakout_dd1`, `drunk_breakout_dd2`, `cardrunkflirt_intro_m`, `cardrunkflirt_loop_m`, `cardrunkflirt_intro_f`, `cardrunkflirt_loop_f`, `cardrunksex_intro_f`, `cardrunksex_outro_f`, `drunk_driver_stand_loop_dd1`, `drunk_driver_stand_loop_dd2`

**Models and props** (4) - `a_m_y_beachvesp_01`, `a_m_y_beachvesp_02`, `a_m_y_genstreet_01`, `a_f_y_hipster_03`

**Audio banks** (2) - `Taxi_Vomit`, `CONSTRUCTION_ACCIDENT_1`

**Sounds** (1) - `SUSPENSION_SCRIPT_FORCE`

**Speech contexts** (4) - `REDR1Drunk1_AI_Drunk`, `A_M_Y_VINEWOOD_01_BLACK_MINI_01`, `A_M_Y_BeachVesp_01_White_Mini_01`, `A_F_Y_EastSA_03_Latino_FULL_01`

**Particle effects** (1) - `scr_puke_in_car`

**Text labels** (7) - `REDR1AU`, `REDR2AU`, `NULL`, `REHH1AU`, `MICHAEL`, `FRANKLIN`, `TREVOR`

**Scenarios** (1) - `WORLD_HUMAN_BUM_STANDING`

**Relationship groups** (1) - `rghDrunkPeds`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (174), `IS_PED_INJURED` (112), `GET_GAME_TIMER` (67), `DOES_BLIP_EXIST` (38), `GET_VEHICLE_PED_IS_IN` (36), `TASK_LOOK_AT_ENTITY` (32), `TASK_PLAY_ANIM` (29), `WAIT` (28), `IS_ENTITY_DEAD` (27), `CLEAR_PED_TASKS` (27), `IS_VEHICLE_DRIVEABLE` (27), `SETTIMERA` (26), `OPEN_SEQUENCE_TASK` (25), `CLOSE_SEQUENCE_TASK` (25), `TASK_PERFORM_SEQUENCE` (25), `CLEAR_SEQUENCE_TASK` (25), `IS_PED_IN_ANY_VEHICLE` (23), `REMOVE_BLIP` (22), `DOES_ENTITY_EXIST` (21), `REMOVE_PED_FROM_GROUP` (19), `SET_PED_KEEP_TASK` (19), `IS_PED_IN_VEHICLE` (19), `IS_ENTITY_PLAYING_ANIM` (18), `PLAYER_ID` (17), `IS_PED_IN_GROUP` (16), `IS_ENTITY_AT_ENTITY` (15), `GET_ENTITY_ANIM_CURRENT_TIME` (15), `TASK_FOLLOW_NAV_MESH_TO_COORD` (14), `GET_PLAYERS_LAST_VEHICLE` (13), `SET_PED_CONFIG_FLAG` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x15 · `1.5f` x3 · `0.1f` x3 · `0.3f` x3 · `0.9f` x3 · `-1052.215f` x2 · `-1354.937f` x2 · `4.3754f` x2 · `-1061.464f` x2 · `-1384.922f` x2 · `4.2462f` x2 · `10.5f` x2 · `1.5062f` x2 · `33.0256f` x2 · `0.0242f` x2 · `41.7126f` x2 · `-5.6746f` x2 · `-0.1271f` x2 · `33.7683f` x2 · `37.1487f` x2 · `-0.4f` x2 · `42.7808f` x1 · `-1324.405f` x1 · `98.245f` x1

## Other strings

Literals whose consuming native was not classified:

`REDR1_SWV`, `player`, `REDR2_DC`, `REDR2_TK`, `REDR2_AKA`, `REDR2_OFFR`, `REDR2_CULT`, `REDR2_JIC`, `REDR1_TK`, `REDR1_TK1`, `REDR1_GBM`, `REDR1_GBF`, `REDR1_GBT`, `REDR1_CRAZY`, `REDR2_TRY`, `REDR2_CH`, `REDR2_WH2`, `REDR2_BCK`, `REDR2_JIA`, `REDR2_JIB`, `REDR2_WHA`, `REDR2_WHB`, `REDR2_WHC`, `REDR2_PSM`, `REDR2_PSF`, `REDR2_PST`, `REDR2_FU`, `REDR1_LFC`, `REDR1_OFFR`, `REDR1_CULT`

---

Source: `decompiled_scripts/re_drunkdriver.c`
