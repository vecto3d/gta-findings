# taxi_clowncar.c

Jobs script. 4 anim dicts; 5 models; 5 particle effects.

| | |
|---|---|
| Category | Jobs |
| Total lines | 14,543 |
| Functions | 418 (58 unique, 360 shared) |
| Unique lines | 2,754 (18.9% of file) |

## Assets

**Animation dictionaries** (4) - `oddjobs@taxi@gyn@cc@intro`, `amb@world_human_stand_impatient@female@no_sign@exit`, `amb@world_human_stand_impatient@female@no_sign@base`, `oddjobs@taxi@gyn@cc@hotbox`

**Animations** (17) - `oddjobs@taxi@gyn@cc@intro`, `base`, `oddjobs@taxi@gyn@cc@hotbox`, `amb@world_human_stand_impatient@female@no_sign@base`, `amb@world_human_stand_impatient@female@no_sign@exit`, `exit`, `idle_b`, `f_impatient_a`, `f_impatient_b`, `f_impatient_c`, `gestures@m@standing@casual`, `gesture_nod_yes_hard`, `oddjobs@towingcome_here`, `come_here_idle_a`, `m_impatient_a`, `m_impatient_b`, `m_impatient_c`

**Models and props** (5) - `a_f_y_beach_01`, `a_m_y_business_02`, `stretch`, `superd`, `a_m_y_business_01`

**Speech contexts** (3) - `TaxiPaulie`, `TaxiClyde`, `TaxiDarren`

**Particle effects** (5) - `smoke`, `speed`, `scr_ojtaxi_hotbox_trail`, `scr_ojtaxi_hotbox_door`, `scr_ojtaxi_hotbox_window`

**Text labels** (1) - `NULL`

**Scenarios** (2) - `WORLD_HUMAN_WINDOW_SHOP_BROWSE`, `WORLD_HUMAN_STAND_MOBILE`

**Relationship groups** (1) - `TAXI_Passenger`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_PED_INJURED` (30), `SET_PARTICLE_FX_LOOPED_EVOLUTION` (20), `IS_PED_IN_ANY_VEHICLE` (19), `TASK_PLAY_ANIM` (19), `DOES_BLIP_EXIST` (18), `IS_ENTITY_DEAD` (15), `IS_VEHICLE_DRIVEABLE` (14), `GET_GAME_TIMER` (14), `CLEAR_SEQUENCE_TASK` (13), `GET_PLAYER_INDEX` (13), `TASK_TURN_PED_TO_FACE_ENTITY` (13), `DOES_PARTICLE_FX_LOOPED_EXIST` (12), `CLEAR_PED_TASKS` (11), `OPEN_SEQUENCE_TASK` (11), `CLOSE_SEQUENCE_TASK` (11), `TASK_PERFORM_SEQUENCE` (11), `SET_BLIP_ROUTE` (11), `HAS_MODEL_LOADED` (10), `SET_PED_CONFIG_FLAG` (10), `TASK_FOLLOW_NAV_MESH_TO_COORD` (10), `SET_ENTITY_AS_MISSION_ENTITY` (10), `SET_BLIP_ALPHA` (10), `SET_MODEL_AS_NO_LONGER_NEEDED` (10), `REQUEST_MODEL` (10), `TASK_LOOK_AT_ENTITY` (9), `GET_SCRIPT_TASK_STATUS` (9), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (8), `CREATE_PED` (8), `CLEAR_PED_TASKS_IMMEDIATELY` (8), `GET_RANDOM_FLOAT_IN_RANGE` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x13 · `0.25f` x11 · `0.6f` x3 · `31.05019f` x2 · `-1347.285f` x2 · `29.49703f` x2 · `90.5877f` x2 · `163.5411f` x2 · `0.4f` x2 · `0.8f` x2 · `-0.15f` x2 · `350.8689f` x1 · `-98.0071f` x1 · `-851.2611f` x1 · `40.9833f` x1 · `-83.1601f` x1 · `-835.3889f` x1 · `39.5744f` x1 · `-1.78774f` x1 · `-1.62399f` x1 · `-0.6206f` x1 · `1.78498f` x1 · `-1.24105f` x1 · `-0.6422f` x1

## Other strings

Literals whose consuming native was not classified:

`Passenger injured.`, `stretch`, `superd`, `player`, `Left Passenger`, `TAXI_ASSETS_STREAMED - Loading TAXI_AMB_P1_BRENDA`, `TAXI_ASSETS_STREAMED - Loading TAXI_AMB_P2_CANDY`, `TAXI_ASSETS_STREAMED - Loading TAXI_AMB_P4_GUEST1`, `TAXI_ASSETS_STREAMED - Loading TAXI_AMB_P6_GUEST3`, `TAXI_ASSETS_STREAMED - Loading STRETCH`, `TAXI_ASSETS_STREAMED - Loading SUPERD`, `TAXI_ASSETS_STREAMED - Anim Dicts oddjobs@taxi@gyn@cc@intro Loading...`, `Taxi attacked the entourage`, `Taxi Not Driveable`, `TAXI_SC_BN_10`, `TAXI_OBJ_CC1`, `Passenger left behind.`, `Passenger left car.`, `TAXI_OBJ_POL`, `Passenger was injured`, `Taxi was destroyed`, `You had a dead body in your back seat.`, `Taxi not drivable.`, `Player abandoned passenger on pickup.`, `windscreen`, `IS_TAXI_RIDE_ALL_READY - Taxi not drivable.`, `window_lr`, `window_rf`, `window_rr`, `TAXI_ASSETS_STREAMED - Loading A_M_Y_BUSINESS_01`

---

Source: `decompiled_scripts/taxi_clowncar.c`
