# fanatic2.c

SP strangers and freaks script. 2 anim dicts; 12 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 45,056 |
| Functions | 482 (74 unique, 408 shared) |
| Unique lines | 4,414 (9.8% of file) |

## Assets

**Animation dictionaries** (2) - `rcm_fanatic2`, `rcmfanatic2`

**Animations** (6) - `rcmfanatic2`, `rcm_fanatic2`, `celebrate_a`, `ef_2_rcm_cyclist_punched_out`, `celebrate_b`, `ef_2_rcm__maryann_biking_cyclist`

**Models and props** (12) - `a_m_y_runner_01`, `a_m_y_cyclist_01`, `a_f_y_runner_01`, `s_m_y_cop_01`, `prop_fnclink_03gate1`, `u_m_y_cyclist_01`, `prop_facgate_03_l`, `prop_facgate_03_r`, `ig_maryann`, `tribike`, `penumbra`, `police3`

**Sounds** (3) - `FANATIC_MIX_SCENE`, `CHECKPOINT_NORMAL`, `HUD_MINI_GAME_SOUNDSET`

**Text labels** (5) - `FAN2AU`, `TREVOR`, `MARYANN`, `FATIC2`, `NULL`

**Waypoint recordings** (3) - `Fan2_BikeRoute`, `Fan2_Jogger1`, `Fan2_Jogger2`

**Vehicle recordings** (3) - `Fan2_Cyclist`, `Fan2_Driver`, `Fan2_DriverCop`

**Doors** (3) - `prop_fnclink_03gate1`, `prop_facgate_03_l`, `prop_facgate_03_r`

**Vehicle mods** (5) - `scorcher`, `tribike`, `fbi`, `firetruk`, `police`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (108), `GET_GAME_TIMER` (48), `GET_ENTITY_COORDS` (32), `GET_HUD_COLOUR` (28), `WAIT` (19), `SET_CHECKPOINT_RGBA` (17), `IS_ENTITY_IN_ANGLED_AREA` (17), `SET_CHECKPOINT_RGBA2` (16), `GET_DISTANCE_BETWEEN_COORDS` (15), `IS_PED_IN_VEHICLE` (14), `HAS_MODEL_LOADED` (13), `REQUEST_MODEL` (11), `IS_VEHICLE_MODEL` (11), `DOES_BLIP_EXIST` (11), `SET_VEHICLE_FORWARD_SPEED` (9), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (9), `SET_PED_INTO_VEHICLE` (9), `SET_MODEL_AS_NO_LONGER_NEEDED` (9), `SET_ENTITY_HEADING` (8), `TASK_SMART_FLEE_PED` (8), `ROUND` (8), `IS_WAYPOINT_PLAYBACK_GOING_ON_FOR_VEHICLE` (7), `DOES_ENTITY_EXIST` (7), `DOES_OBJECT_OF_TYPE_EXIST_AT_COORDS` (6), `SET_STATE_OF_CLOSEST_DOOR_OF_TYPE` (6), `TRIGGER_MUSIC_EVENT` (6), `IS_CONTROL_PRESSED` (6), `SET_PED_COORDS_KEEP_VEHICLE` (6), `DELETE_CHECKPOINT` (6), `TASK_LOOK_AT_ENTITY` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`3.5f` x12 · `801.7148f` x6 · `1270.138f` x6 · `359.2855f` x6 · `802.9195f` x4 · `1280.92f` x4 · `360.7272f` x4 · `864.3021f` x4 · `1274.852f` x4 · `361.4736f` x4 · `393.9782f` x4 · `1197.084f` x4 · `224.3141f` x4 · `1.2f` x3 · `802.9218f` x2 · `1281.675f` x2 · `359.2962f` x2 · `878.2955f` x2 · `1291.728f` x2 · `355.5366f` x2 · `817.8235f` x2 · `1271.439f` x2 · `362.9736f` x2 · `12.75f` x2

## Other strings

Literals whose consuming native was not classified:

`BLIP_CPOINT`, `MaryAnnes_Friend`, `Mary_Ann`, `MotionState_DoNothing`, `penumbra`, `police3`, `Setting PRF_PreventGoingIntoStillInVehicleState on Trevor`, `FANATIC_MIX_MARY_BIKE`, `FANATIC2_FAIL`, `Players_Bike`, `MISSION_FAILED reason=FAILED_ABANDONED_RACE`, `Bike exists, set coords/heading: `, `Bike doesn't exist, recreate: `, `Putting Trevor on bike...`, `Still loading assets.`, `tribike`, `scorcher`, `FAN2_FEM4B`, `FAN2_FEM4A`, `FAN2_FEM3`, `Bringing Mary Ann to a halt...`, `FANATIC2_STOP`, `Doing music trigger stop`, `Released jogger 1 (waypoint > 93)`, `Released jogger 2 (waypoint > 93)`, `HONKING: Entity exists!`, `Honking!`, `Init MS_COUNTDOWN`, `Doing Countdown init reset...`, `No bike in MS_COUNTDOWN init?`

---

Source: `decompiled_scripts/fanatic2.c`
