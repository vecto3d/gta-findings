# carsteal1.c

Heists script. 2 anim dicts; 18 models.

| | |
|---|---|
| Category | Heists |
| Total lines | 136,801 |
| Functions | 1,032 (66 unique, 966 shared) |
| Unique lines | 14,708 (10.8% of file) |

## Assets

**Animation dictionaries** (2) - `veh@bike@quad@front@base`, `shake_cam_all@`

**Animations** (9) - `racer_argue_action_01`, `racer_argue_action_02`, `point_right_micheal`, `point_left`, `racer_argue_01`, `racer_argue_02`, `punch_air`, `byBike_idle_Mic`, `byBike_idle_Trev`

**Models and props** (18) - `ig_car3guy2`, `ig_car3guy1`, `prop_donut_02b`, `SET_CAR_HIGH_SPEED_BUMP_SEVERITY_MULTIPLIER`, `prop_sc1_06_gate_l`, `prop_sc1_06_gate_r`, `prop_player_phone_01`, `prop_donut_02`, `s_m_y_dwservice_02`, `f620`, `entityxf`, `cheetah`, `p_ld_id_card_01`, `g_m_y_lost_01`, `adder`, `prop_mp_ramp_03`, `s_m_y_hwaycop_01`, `policeb`

**Audio banks** (1) - `RACE_IGNITIONS`

**Sounds** (19) - `CAR_1_RACE_CARS_FOCUS_CAM`, `CAR_1_GET_TO_RACE`, `CAR_1_BIKE_ENTER_TUNNEL`, `CAR_1_BIKE_PASS_THE_LOST`, `CAR_1_FRANKLIN_CALLS_MICHAEL`, `CAR_1_RACE_MAIN`, `CAR_1_RACE_SKIDDING_CARS`, `CAR_1_GARAGE_ARRIVAL`, `CAR_1_BIKE_CHASE_MAIN`, `CAR_1_PARK_UP_CUTSCENE`, `CAR_1_GET_TO_GARAGE`, `CAR_STEAL_1_SOUNDSET`, `CAR_1_DEVIN_DRIVES_AWAY`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `CAR_STEAL_1_IGNITIONS`, `Hit_Out`, `Short_Transition_In`, `TRUCK_HORN`, `BUS_HORN`

**Text labels** (11) - `DEVIN`, `CST3RACER1`, `CST3RACER2`, `MOLLY`, `TREVOR`, `MICHAEL`, `CST3AUD`, `FRANKLIN`, `EXTRASUNNY`, `NULL`, `CRSTL3`

**Vehicle recordings** (2) - `ALubersetup`, `ALuberSetup`

**Relationship groups** (3) - `rgh_traffic`, `BUDDIES`, `ENEMIES`

**Interiors and entity sets** (1) - `v_chopshop`

**Doors** (1) - `prop_sc1_06_gate_r`

**Vehicle mods** (4) - `policeb`, `f620`, `entityxf`, `cheetah`

**Stats** (6) - `sp0_special_ability_unlocked`, `sp0_special_ability`, `sp1_special_ability`, `sp1_special_ability_unlocked`, `sp2_special_ability`, `sp2_special_ability_unlocked`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (351), `DOES_ENTITY_EXIST` (285), `GET_ENTITY_COORDS` (273), `GET_DISTANCE_BETWEEN_COORDS` (139), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (105), `IS_ENTITY_DEAD` (93), `GET_GAME_TIMER` (84), `IS_PED_IN_VEHICLE` (77), `SET_MODEL_AS_NO_LONGER_NEEDED` (59), `IS_PED_INJURED` (56), `GET_TIME_POSITION_IN_RECORDING` (55), `IS_AUDIO_SCENE_ACTIVE` (46), `REQUEST_MODEL` (44), `HAS_MODEL_LOADED` (44), `SET_PED_INTO_VEHICLE` (44), `HIDE_HUD_COMPONENT_THIS_FRAME` (44), `GET_PED_IN_VEHICLE_SEAT` (43), `REGISTER_ENTITY_FOR_CUTSCENE` (43), `PLAYER_ID` (39), `GET_SCRIPT_TASK_STATUS` (39), `IS_ENTITY_IN_ANGLED_AREA` (37), `TIMESTEP` (35), `ENABLE_DISPATCH_SERVICE` (35), `SET_VEHICLE_ENGINE_ON` (33), `STOP_PLAYBACK_RECORDED_VEHICLE` (32), `STOP_AUDIO_SCENE` (32), `GET_TOTAL_DURATION_OF_VEHICLE_RECORDING` (31), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (31), `SET_PED_COMPONENT_VARIATION` (29), `REMOVE_ENTITY_FROM_AUDIO_MIX_GROUP` (29)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`492.9378f` x28 · `-1317.739f` x28 · `29.25194f` x28 · `17.5f` x10 · `107.662f` x10 · `358.981f` x10 · `2581.546f` x10 · `56.0588f` x9 · `4597.978f` x9 · `-1928.376f` x9 · `28.2534f` x8 · `-3439.024f` x8 · `1435.432f` x8 · `0.1f` x7 · `490.8354f` x7 · `-1311.987f` x7 · `28.2584f` x7 · `0.5f` x6 · `479.905f` x6 · `-1314.857f` x6 · `29.1361f` x6 · `0.25f` x6 · `116.4686f` x6 · `361.8055f` x6

## Other strings

Literals whose consuming native was not classified:

`minivan`, `asterope`, `emperor`, `journey`, `mule`, `f620`, `cheetah`, `entityxf`, `policeb`, `surfer`, `Franklin`, `Michael`, `Trevor`, `CST3_Pull`, `Racer_that_dies`, `S3_BLIPVEH`, `Franklins_car`, `Racer_that_runsaway`, `adder`, `CAR1_MISSION_START`, `CAR1_CHASE_START`, `ChopShopDoors`, `MotionState_Run`, `SwitchOnce`, `Devins_car`, `car_1_ext_concat`, `Car_Racer_runsaway`, `Car_Racer_dies`, `CMN_GENGETIN`, `LOAD_ALL_PATH_NODES`

---

Source: `decompiled_scripts/carsteal1.c`
