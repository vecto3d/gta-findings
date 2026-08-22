# triathlonsp.c

Races script. 6 anim dicts; 29 models; 6 scaleforms.

| | |
|---|---|
| Category | Races |
| Total lines | 125,347 |
| Functions | 1,158 (386 unique, 772 shared) |
| Unique lines | 18,277 (14.6% of file) |

## Assets

**Animation dictionaries** (6) - `mini@triathlon`, `mini@triathlonintro`, `VEH@BIKE@COMMON@FRONT@BASE`, `missfbi4`, `random@escape_paparazzi@standing@`, `VEH@BICYCLE@ROADFRONT@BASE`

**Animations** (14) - `idle_a`, `mini@triathlon`, `missfbi4`, `takeoff_mask`, `idle_d`, `idle_f`, `idle_b`, `idle_c`, `idle_e`, `mini@triathlonintro`, `male_unarmed_b`, `rummage_bag`, `_table_sign_in_michael`, `_table_sign_in_ped`

**Models and props** (29) - `prop_barrier_work06a`, `a_m_y_roadcyc_01`, `prop_dock_bouy_3`, `prop_energy_drink`, `frogger`, `tribike`, `ig_2_gen_warmup_01`, `a_c_sharktiger`, `prop_pencil_01`, `ig_2_gen_warmup_02`, `ig_2_gen_warmup_03`, `ig_2_gen_warmup_04`, `ig_2_gen_warmup_05`, `ig_2_gen_warmup_06`, `ig_2_gen_warmup_07`, `ig_2_gen_warmup_08`, `ig_2_gen_warmup_09`, `ig_2_gen_warmup_10`, `ig_2_gen_warmup_11`, `ig_2_gen_warmup_12`, `ig_2_gen_warmup_13`, `A_M_Y_TRIATHLON_01_MINI_01`, `A_M_Y_TRIATHLON_01_MINI_02`, `A_M_Y_TRIATHLON_01_MINI_03`, `A_M_Y_TRIATHLON_01_MINI_04`, `prop_dock_bouy_1`, `prop_dock_bouy_2`, `tribike2`, `tribike3`

**Audio banks** (1) - `CROWD_CHEER`

**Sounds** (23) - `HUD_MINI_GAME_SOUNDSET`, `HUD_MINIGAME_SOUNDSET`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `TRI_SWIM_SCENE`, `TRI_START_SCENE`, `Phone_Generic_Key_02`, `TRI_RUN_SCENE`, `TRI_BIKE_SCENE`, `NAV_UP_DOWN`, `TRI_END_SCENE`, `Phone_Generic_Key_03`, `QUIT_WHOOSH`, `SELECT`, `LEADERBOARD_SCENE`, `QUIT`, `BACK`, `LEADERBOARD`, `MEDAL_UP`, `RACE_PLACED`, `HUD_AWARDS`, `HUD_FRONTEND_MP_SOUNDSET`, `CROWD_CHEER_MASTER`, `POSITIONED_WALLA_MASTER`

**Scaleform movies** (6) - `SET_SCROLL_TEXT`, `DISPLAY_SCROLL_TEXT`, `CLEAR_ALL_SLOTS`, `SET_TEXT`, `BREAKING_NEWS`, `SHOW_STATIC`

**Texture dicts** (16) - `digitalOverlay`, `TRIATHLON`, `Shared`, `MPHUD`, `SPRRaces`, `SPROffroad`, `Triathlon`, `nscanline1`, `nscuzz1`, `nscuzz2`, `nscuzz3`, `Static1`, `Static2`, `Static3`, `Static4`, `Static5`

**Text labels** (26) - `MGTRAUD`, `NULL`, `RANDOM`, `TRI_INTRO_IM2`, `TRINEWS`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `TRI_LEAVE_VEH`, `SPR_HELP_WARN`, `SPR_RETR_DES`, `NONE`, `CMSW`, `GRID`, `COVERED`, `TRI_INTRO_GOAL`, `TRI_INTNS`, `TRI_INTNS_KM`, `TRI_NRG_INTRO`, `TRI_HP_LOSS`, `OFF_OPP`, `GATEBLIP`, `GATEBLIPDEF`, `TRIRACER1`, `WHOOP`, `SPR_OBJ_BIKE1`

**Scenarios** (6) - `Triathlon_1`, `Triathlon_2`, `Triathlon_3`, `Triathlon_1_Start`, `Triathlon_2_Start`, `Triathlon_3_Start`

**Waypoint recordings** (5) - `Tri1_Bk_0`, `Tri1_Run`, `Tri2_Bk_0`, `Tri2_Run`, `Tri3_Run`

**Vehicle mods** (4) - `tribike`, `tribike2`, `tribike3`, `sanchez`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (225), `CREATE_OBJECT` (211), `SET_ENTITY_ROTATION` (196), `SET_BIT` (188), `IS_ENTITY_DEAD` (148), `SET_ROADS_IN_ANGLED_AREA` (125), `DOES_CAM_EXIST` (67), `PLAYER_ID` (66), `DOES_ENTITY_EXIST` (41), `CREATE_CAMERA_WITH_PARAMS` (40), `CLEAR_BIT` (40), `GET_RANDOM_FLOAT_IN_RANGE` (39), `GET_ENTITY_COORDS` (37), `GET_RANDOM_INT_IN_RANGE` (36), `IS_PED_IN_ANY_VEHICLE` (34), `IS_STRING_NULL_OR_EMPTY` (34), `SET_ENTITY_COORDS` (30), `IS_PED_INJURED` (27), `SET_DRIVE_TASK_CRUISE_SPEED` (24), `LEADERBOARDS2_READ_GET_ROW_DATA_INT` (24), `DOES_BLIP_EXIST` (23), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (23), `IS_PED_IN_VEHICLE` (22), `DESTROY_CAM` (21), `PLAY_SOUND_FRONTEND` (19), `DISABLE_CONTROL_ACTION` (19), `SET_ENTITY_HEADING` (19), `TASK_PLAY_ANIM` (18), `BEGIN_SCALEFORM_MOVIE_METHOD` (16), `END_SCALEFORM_MOVIE_METHOD` (16)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x23 · `1.5f` x9 · `0.15f` x7 · `3.23f` x7 · `0.25f` x6 · `26.221f` x6 · `42.221f` x6 · `0.2f` x5 · `-60.16f` x5 · `-63.6f` x5 · `-61.88f` x5 · `20.7f` x4 · `26.93f` x4 · `31.33f` x4 · `-61.31f` x4 · `25.78f` x4 · `-56.15f` x4 · `9.7f` x3 · `31.35f` x3 · `24.221f` x3 · `40.221f` x3 · `33.5f` x3 · `31.41f` x3 · `33.39f` x3

## Other strings

Literals whose consuming native was not classified:

`SCLB_C_RANK`, `Mission`, `SCLB_C_VEH`, `SCLB_C_KILLS`, `SCLB_C_BL`, `MICHAEL_NORMAL`, `GameType`, `FRANKLIN_NORMAL`, `TREVOR_NORMAL`, `SCLB_C_WINS`, `MGTR_IRON`, `Location`, `SCLB_C_SCORE`, `SCLB_C_TIME`, `SCLB_C_WLRAT`, `Type`, `SCLB_C_RT`, `SCLB_C_LOSES`, `SCLB_C_DEATH`, `WeaponId`, `SCLB_C_MEDAL1`, `SCLB_C_MEDAL2`, `SCLB_C_MEDAL3`, `TRI_CONT`, `PS_TITLE`, `Corona_Marker`, `player_one`, `Laps`, `StreetRace`

---

Source: `decompiled_scripts/triathlonsp.c`
