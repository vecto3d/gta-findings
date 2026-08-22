# am_vehicle_spawn.c

Vehicles script. 9 models; 7 scaleforms.

| | |
|---|---|
| Category | Vehicles |
| Total lines | 435,313 |
| Functions | 7,726 (553 unique, 7,173 shared) |
| Unique lines | 50,606 (11.6% of file) |

## Assets

**Models and props** (9) - `g_m_m_chigoon_02`, `SET_SHOCK_METER_IS_VISIBLE`, `SET_DETONATE_METER_IS_VISIBLE`, `SET_HEADING_METER_IS_VISIBLE`, `SET_ZOOM_METER_IS_VISIBLE`, `SET_BOOST_METER_IS_VISIBLE`, `SET_MISSILE_METER_IS_VISIBLE`, `ba_prop_battle_secpanel`, `ba_prop_battle_secpanel_dam`

**Audio banks** (1) - `SCRIPT\POLICE_CHOPPER_CAM`

**Sounds** (17) - `DLC_XM_Vehicle_Interior_Security_Camera_Sounds`, `DLC_BTL_Hacker_Truck_Player_Scanner_Scene`, `Fly_Loop`, `Drive_Loop`, `avengerRotorSpeed`, `Ctrl`, `Dir`, `Surface`, `Submarine_First_Time_Surface`, `Background_Hum`, `Scanner_Loop`, `DLC_BTL_Target_Pursuit_Sounds`, `signalstrength`, `dlc_xm_avngr_sounds`, `DLC_GR_MOC_Sounds`, `COP_HELI_CAM_ZOOM`, `COP_HELI_CAM_TURN`

**Scaleform movies** (7) - `SET_INFO_LIST_IS_VISIBLE`, `SET_SOUND_WAVE_IS_VISIBLE`, `PARTY_BUS`, `SET_RETICLE_IS_VISIBLE`, `DRONE_CAM`, `ATTENUATE_SOUND_WAVE`, `SET_INFO_LIST_DATA`

**Texture dicts** (3) - `helicopterhud`, `hud_outline`, `droneHUD`

**Text labels** (8) - `NULL`, `PAIGE`, `PAIFMAU`, `FCP2`, `OFF`, `PEGASUS`, `BOSSAGENCY`, `BACALAU`

**Decorators** (14) - `MPBitset`, `CreatedByPegasus`, `Player_Truck`, `Player_Avenger`, `Player_Hacker_Truck`, `Player_Mansion_Heli`, `Player_Acid_Lab`, `Player_Submarine`, `Player_Submarine_Dinghy`, `UsingForTimeTrial`, `Player_Support_Bike_Vehicle`, `EnableVehLuxeActs`, `Mansion_Spawned_Heli`, `Creator_Trailer`

**Timecycle modifiers** (2) - `CAMERA_secuirity`, `eyeinthesky`

**Vehicle mods** (5) - `avenger`, `brickade2`, `pbus2`, `terbyte`, `trash2`

**Scripts launched** (2) - `luxe_veh_activity`, `am_mp_property_int`

**Hashed names** (1) - `ba_prop_battle_pbus_screen`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (1808), `NET_TO_VEH` (407), `PLAYER_PED_ID` (264), `DOES_ENTITY_EXIST` (261), `SET_BIT` (249), `CLEAR_BIT` (239), `IS_ENTITY_DEAD` (196), `NETWORK_DOES_NETWORK_ID_EXIST` (150), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (111), `GET_ENTITY_COORDS` (101), `NETWORK_HAS_CONTROL_OF_ENTITY` (92), `GET_PLAYER_PED` (77), `NET_TO_PED` (74), `IS_VEHICLE_DRIVEABLE` (71), `INT_TO_PLAYERINDEX` (62), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (58), `DOES_ENTITY_BELONG_TO_THIS_SCRIPT` (56), `IS_PED_IN_ANY_VEHICLE` (53), `GET_VEHICLE_PED_IS_IN` (50), `NETWORK_PLAYER_ID_TO_INT` (48), `IS_ENTITY_A_MISSION_ENTITY` (48), `GET_ENTITY_MODEL` (47), `NET_TO_ENT` (44), `NETWORK_REQUEST_CONTROL_OF_ENTITY` (42), `SET_NETWORK_ID_ALWAYS_EXISTS_FOR_PLAYER` (37), `SET_ENTITY_AS_MISSION_ENTITY` (36), `NETWORK_IS_ACTIVITY_SESSION` (35), `IS_PED_IN_VEHICLE` (32), `IS_HELP_MESSAGE_BEING_DISPLAYED` (32), `GET_SCRIPT_TASK_STATUS` (32)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x6 · `62.28f` x5 · `0.9f` x4 · `4785.679f` x4 · `489.5733f` x4 · `2.5f` x4 · `0.1f` x3 · `0.2f` x3 · `1097.535f` x2 · `-3016.011f` x2 · `-40.7658f` x2 · `1109.298f` x2 · `-2983.69f` x2 · `-34.1882f` x2 · `0.8f` x2 · `0.04f` x2 · `506.9767f` x2 · `4750.366f` x2 · `-69.99597f` x2 · `509.3737f` x2 · `4750.375f` x2 · `-67.49597f` x2 · `2.75f` x2 · `-1831.333f` x2

## Other strings

Literals whose consuming native was not classified:

`submersible`, `seashark`, `blimp3`, `SCAN_USE`, `SCAN_USEc`, `riot`, `bulldozer`, `blazer`, `barracks`, `buzzard`, `maverick`, `annihilator`, `SCAN_USEb`, `jetmax`, `chassis_dummy`, `SCAN_EXIT`, `SCAN_EXITc`, `submersible2`, `mammatus`, `stunt`, `marquis`, `frogger`, `PBus_Screen`, `SCAN_BUSY`, `stretch`, `luxe_veh_activity`, `AV_MOD_HOLD_1`, `AV_MOD_HOLD_2`, `AV_MOD_HOLD_3`, `avenger`

---

Source: `decompiled_scripts/am_vehicle_spawn.c`
