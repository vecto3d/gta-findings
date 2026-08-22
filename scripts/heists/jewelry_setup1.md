# jewelry_setup1.c

Heists script. 3 anim dicts; 9 models; 1 scaleforms.

| | |
|---|---|
| Category | Heists |
| Total lines | 112,816 |
| Functions | 659 (40 unique, 619 shared) |
| Unique lines | 7,819 (6.9% of file) |

## Assets

**Animation dictionaries** (3) - `MISSHEIST_JEWEL_SETUP`, `amb@world_human_window_shop@male@idle_a`, `amb@world_human_stand_guard@male@idle_a`

**Animations** (15) - `MISSHEIST_JEWEL_SETUP`, `amb@world_human_window_shop@male@idle_a`, `browse_c`, `enter_guard`, `exit_guard`, `base_guard`, `amb@world_human_stand_guard@male@idle_a`, `idle_a`, `browse_a`, `idle_storeclerk`, `browse_b`, `LESTER_GET_IN_CAR`, `lester_get_in_car_cardoor`, `veh@std@ds@enter_exit`, `jump_out`

**Models and props** (9) - `prop_pool_ball_01`, `prop_bowling_ball`, `a_m_m_bevhills_01`, `u_m_m_jewelsec_01`, `ig_jewelass`, `p_jewel_door_l`, `tailgater`, `cs_jewelass`, `v_ilev_ss_door02`

**Audio banks** (1) - `JWL_HEIST_SETUP`

**Sounds** (13) - `JSH_1_TAKE_PHOTOS`, `JSH_1_INSIDE_STORE`, `JSH_1_GET_TO_ROOF`, `JSH_1_DRIVE_TO_FACTORY`, `JSH_1_DRIVE_TO_BACK_ENTRANCE`, `JSH1_RETURN_TO_CAR`, `JSH_1_LEAVE_STORE`, `JSH_1_ENTER_STORE`, `JSH_1_DRIVE_TO_STORE`, `Phone_SoundSet_Glasses_Cam`, `Background_Sound`, `Camera_Shoot`, `Camera_Zoom`

**Scaleform movies** (1) - `camera_gallery`

**Texture dicts** (1) - `digitalOverlay`

**Text labels** (16) - `JHS1AUD`, `WANTED`, `LESTER`, `HELP2`, `MICHAEL`, `HELP1`, `GOD8`, `GOD5`, `GOD3`, `NULL`, `GOD6`, `GOD7`, `GOD4`, `GOD1`, `GOD2`, `H3SET1`

**Scenarios** (1) - `SEW_MACHINE`

**Waypoint recordings** (3) - `BB_JEW_6`, `BB_JEW_1`, `BB_JEW_2`

**Relationship groups** (1) - `player`

**Timecycle modifiers** (1) - `secret_camera`

**Doors** (1) - `p_jewel_door_l`

**Vehicle mods** (1) - `tailgater`

**Stats** (1) - `sp0_kills_innocents`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (245), `DOES_ENTITY_EXIST` (200), `GET_GAME_TIMER` (134), `DOES_BLIP_EXIST` (99), `IS_MESSAGE_BEING_DISPLAYED` (73), `DISABLE_CONTROL_ACTION` (69), `IS_ENTITY_ON_SCREEN` (67), `REMOVE_BLIP` (64), `IS_SUBTITLE_PREFERENCE_SWITCHED_ON` (64), `FREEZE_ENTITY_POSITION` (51), `IS_PED_INJURED` (48), `CREATE_OBJECT` (43), `GET_ENTITY_COORDS` (39), `IS_ENTITY_IN_ANGLED_AREA` (36), `IS_VEHICLE_DRIVEABLE` (35), `CLEAR_PRINTS` (34), `PLAYER_ID` (28), `DESTROY_TRACKED_POINT` (27), `IS_AUDIO_SCENE_ACTIVE` (27), `IS_SPHERE_VISIBLE` (27), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (27), `GET_DISTANCE_BETWEEN_COORDS` (26), `IS_ENTITY_AT_COORD` (25), `REPLAY_RECORD_BACK_FOR_TIME` (24), `IS_PED_IN_VEHICLE` (23), `IS_ENTITY_PLAYING_ANIM` (19), `SET_ENTITY_VISIBLE` (18), `WAIT` (16), `GET_PLAYER_WANTED_LEVEL` (16), `STOP_AUDIO_SCENE` (16)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x48 · `-631.3f` x13 · `-0.1f` x13 · `-631.96f` x8 · `-236.33f` x8 · `38.21f` x8 · `2.5f` x8 · `0.2f` x8 · `-0.3f` x8 · `37.4f` x7 · `-631.1307f` x6 · `-237.3734f` x6 · `36.55695f` x6 · `-617.1204f` x6 · `-227.0041f` x6 · `39.91531f` x6 · `17.75f` x6 · `-0.2f` x6 · `-611.9f` x5 · `-362.4f` x5 · `-558.6f` x5 · `-264.5f` x5 · `-538.9f` x5 · `-296.7f` x5

## Other strings

Literals whose consuming native was not classified:

`JHS1_OLDCREW`, `JHS1_PH48`, `JHS1_PH21`, `JHS1_PH20`, `JHS1_PH22`, `MISSHEIST_JEWEL_SETUP`, `GOTO_CAR2`, `JewelGuard`, `JHS1_PH37`, `JHS1_PH36`, `JHS1_PH35`, `JHS1_PH16`, `JH1_RESTART_2`, `JHS1_PH46`, `JHS1_PH43`, `HELP1_KM`, `Jewellery_Assitance`, `Michael`, `Lester`, `Michaels_car`, `tailgater`, `JH1_FAIL`, `FAIL_SHOP3`, `CMN_GENDEST`, `FAIL_CAR`, `FAIL_DIST`, `JewelSales`, `JH1_RESTART_1`, `JH1_RESTART_3`, `JH1_START`

---

Source: `decompiled_scripts/jewelry_setup1.c`
