# launcher_offroadracing.c

Races script. 6 anim dicts; 4 models.

| | |
|---|---|
| Category | Races |
| Total lines | 5,073 |
| Functions | 157 (32 unique, 125 shared) |
| Unique lines | 2,089 (41.2% of file) |

## Assets

**Animation dictionaries** (6) - `amb@world_human_hang_out_street@male_a@idle_a`, `amb@world_human_hang_out_street@male_b@idle_a`, `amb@world_human_hang_out_street@male_c@idle_a`, `amb@world_human_aa_smoke@male@idle_a`, `random@street_race`, `gestures@m@standing@casual`

**Animations** (4) - `gestures@m@standing@casual`, `random@street_race`, `_streetracer_wait_loop`, `amb@world_human_aa_smoke@male@idle_a`

**Models and props** (4) - `a_m_y_motox_01`, `A_M_Y_RACER_01_WHITE_MINI_01`, `prop_fncwood_14c`, `prop_fncwood_14e`

**Text labels** (5) - `NULL`, `ORRAUD`, `MALE1`, `MALE2`, `MALE3`

**Scenarios** (7) - `WORLD_HUMAN_HIKER`, `WORLD_VEHICLE_DRIVE_SOLO`, `WORLD_VEHICLE_EMPTY`, `WORLD_MOUNTAIN_LION_WANDER`, `WORLD_VEHICLE_BIKE_OFF_ROAD_RACE`, `WORLD_VEHICLE_BICYCLE_MOUNTAIN`, `QUARRY`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (25), `PLAYER_ID` (16), `DOES_ENTITY_EXIST` (14), `IS_ENTITY_DEAD` (13), `GET_RANDOM_INT_IN_RANGE` (11), `OPEN_SEQUENCE_TASK` (11), `CLOSE_SEQUENCE_TASK` (11), `TASK_PERFORM_SEQUENCE` (11), `CLEAR_SEQUENCE_TASK` (11), `TASK_PLAY_ANIM` (10), `SET_SCENARIO_TYPE_ENABLED` (9), `GET_ENTITY_COORDS` (8), `VDIST2` (7), `IS_PED_INJURED` (7), `REMOVE_ANIM_DICT` (6), `SET_ROADS_IN_ANGLED_AREA` (6), `HAS_ANIM_DICT_LOADED` (6), `REQUEST_ANIM_DICT` (6), `SET_PLAYER_CONTROL` (5), `SET_ROADS_BACK_TO_ORIGINAL_IN_ANGLED_AREA` (5), `TASK_TURN_PED_TO_FACE_ENTITY` (5), `TASK_ACHIEVE_HEADING` (5), `IS_PED_IN_VEHICLE` (5), `IS_PED_RAGDOLL` (5), `IS_PED_GETTING_UP` (5), `GET_CLOCK_HOURS` (4), `TASK_VEHICLE_TEMP_ACTION` (4), `GET_RANDOM_FLOAT_IN_RANGE` (4), `WAIT` (3), `CLEAR_HELP` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`2242.488f` x6 · `-1943.822f` x3 · `4462.286f` x3 · `-229.0783f` x3 · `4227.072f` x3 · `2568.146f` x3 · `1568.146f` x3 · `2809.948f` x3 · `2993.644f` x3 · `-9.3564f` x3 · `2952.969f` x3 · `2530.636f` x3 · `177.1921f` x3 · `-223.42f` x2 · `3948.36f` x2 · `36.52f` x2 · `-212.37f` x2 · `3818.97f` x2 · `37.53f` x2 · `-509.1254f` x2 · `1987.582f` x2 · `205.3305f` x2 · `-948.5215f` x2 · `2752.741f` x2

## Other strings

Literals whose consuming native was not classified:

`sanchez`, `mesa`, `blazer`, `MG_NA_TIME`, `CanyonCliffs_Start`, `RidgeRun_Start`, `ValleyTrail_Start`, `LakesideSplash_Start`, `EcoFriendly_Start`, `MinewardSpiral_Start`, `idle_a`, `idle_b`, `idle_c`, `bjxl`, `bfinjection`, `CC_SUBSTR`, `OFFR_NEW`, `SwitchSceneNeutral`, `ORR_GUY1`, `ORR_GUY2`, `ORR_GUY3`, `PRERACE_CHAT`, `PRERACE_TAUNT`, `gesture_what_hard`, `gesture_what_soft`, `patriot`, `dubsta2`, `sadler`, `rebel`, `offroadrace`

---

Source: `decompiled_scripts/launcher_offroadracing.c`
