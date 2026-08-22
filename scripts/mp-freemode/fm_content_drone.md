# fm_content_drone.c

MP freemode script. 17 models; 11 scaleforms.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 10,757 |
| Functions | 451 (140 unique, 311 shared) |
| Unique lines | 4,595 (42.7% of file) |

## Assets

**Models and props** (17) - `SET_WARNING_IS_VISIBLE`, `SET_BOOST_METER_IS_VISIBLE`, `ba_prop_battle_drone_quad`, `ba_prop_battle_secpanel`, `ba_prop_battle_secpanel_dam`, `v_faceoffice`, `SET_DETONATE_METER_IS_VISIBLE`, `SET_SHOCK_METER_IS_VISIBLE`, `SET_EMP_METER_IS_VISIBLE`, `SET_RETICLE_IS_VISIBLE`, `SET_HEADING_METER_IS_VISIBLE`, `SET_ZOOM_METER_IS_VISIBLE`, `SET_TRANQUILIZE_METER_IS_VISIBLE`, `SET_MISSILE_METER_IS_VISIBLE`, `SET_BOTTOM_LEFT_CORNER_IS_VISIBLE`, `SET_SOUND_WAVE_IS_VISIBLE`, `SET_INFO_LIST_IS_VISIBLE`

**Sounds** (19) - `DroneRotationalSpeed`, `HUD_Static_Loop`, `HUD_Disconnect`, `HUD_Shock_Recharge`, `Time`, `Destroyed`, `HUD_Detonate_Charge`, `Shock_Fire`, `Drone_Scan_Complete`, `Scan_Progress`, `Drone_Scan_Wrong_Ped`, `Drone_Scan_Right_Ped`, `HUD_Zoom_Change`, `Out_Of_Bounds_Alarm_Loop`, `HUD_Boost_Loop`, `HUD_Boost_Recharge_Loop`, `HUD_Loop`, `Flight_Loop`, `HUD_Startup`

**Scaleform movies** (11) - `DRONE_CAM`, `SET_WARNING_FLASH_RATE`, `SET_HEADING`, `SET_RETICLE_ON_TARGET`, `SET_RETICLE_OUTER_LINES_VISIBLE`, `SET_RETICLE_STATE`, `SET_ZOOM`, `SET_ZOOM_LABEL`, `SET_BOOST_PERCENTAGE`, `SET_DETONATE_PERCENTAGE`, `SET_SHOCK_PERCENTAGE`

**Texture dicts** (2) - `helicopterhud`, `hud_outline`

**Text labels** (2) - `NULL`, `COP`

**Vehicle mods** (1) - `terbyte`

**Hashed names** (1) - `AM_MP_DRONE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`NET_TO_OBJ` (74), `PLAYER_ID` (70), `CLEAR_BIT` (50), `SET_BIT` (49), `ENABLE_CONTROL_ACTION` (48), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (36), `HAS_SOUND_FINISHED` (30), `RELEASE_SOUND_ID` (20), `PLAYER_PED_ID` (19), `STOP_SOUND` (19), `IS_ENTITY_DEAD` (17), `DOES_ENTITY_EXIST` (16), `GET_PED_TYPE` (16), `GET_SOUND_ID` (14), `GET_PLAYER_PED` (14), `PLAY_SOUND_FRONTEND` (13), `IS_USING_KEYBOARD_AND_MOUSE` (13), `NET_TO_ENT` (12), `GET_CONTROL_UNBOUND_NORMAL` (12), `DOES_CAM_EXIST` (11), `GET_PED_INDEX_FROM_ENTITY_INDEX` (11), `APPLY_FORCE_TO_ENTITY_CENTER_OF_MASS` (11), `GET_ENTITY_COORDS` (10), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (10), `BEGIN_SCALEFORM_MOVIE_METHOD` (10), `END_SCALEFORM_MOVIE_METHOD` (10), `NETWORK_REQUEST_CONTROL_OF_NETWORK_ID` (9), `ROUND` (9), `COS` (9), `TO_FLOAT` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x11 · `0.5f` x5 · `-0.25f` x3 · `0.7f` x2 · `0.04f` x2 · `0.01f` x2 · `-0.8f` x1 · `-1036.27f` x1 · `-228.704f` x1 · `53.76435f` x1 · `-1096.765f` x1 · `-258.69f` x1 · `35.77808f` x1 · `0.2f` x1 · `-1071.258f` x1 · `-242.5484f` x1 · `48.02133f` x1 · `-1069.456f` x1 · `-245.9234f` x1 · `43.87983f` x1 · `2494.398f` x1 · `-276.2f` x1 · `-69.09f` x1 · `2494.342f` x1

## Other strings

Literals whose consuming native was not classified:

`CELL_284`, `BOOST_DRONE_E`, `FMC_DRONE_SCN`, `MOVE_DRONE_ST`, `MOVE_DRONE_UP`, `MOVE_DRONE_DO`, `RaceTurbo`, `GTAO_Hacker_Drone_HUD_Medium_Drone_Scene`, `RemixDrone`, `avenger`, `blazer5`, `GTAO_Drone_Sounds`, `DRONE_TRIG`, `GtaMloRoom001`, `DLC_24-2_Penthouse_Robbery_Sounds`, `VEX_SCAN`, `VEX_TARACQ`, `VEX_TARINV`, `Drone_Scan_Loop`, `army`, `chernobog`, `dune4`, `dune5`, `skylift`, `taco`, `DRONE_ZOOM_1`, `DRONE_ZOOM_2`, `DRONE_ZOOM_3`, `DRONE_MOVE`, `DRONE_POSITION`

---

Source: `decompiled_scripts/fm_content_drone.c`
