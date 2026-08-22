# am_mp_vehicle_weapon.c

Vehicles script. 11 models; 7 scaleforms.

| | |
|---|---|
| Category | Vehicles |
| Total lines | 6,122 |
| Functions | 215 (71 unique, 144 shared) |
| Unique lines | 2,771 (45.3% of file) |

## Assets

**Animations** (12) - `ANIM@AMB@FACILITY@LAUNCH_CONTROLS@`, `COMPUTER_idle`, `COMPUTER_idle_control`, `COMPUTER_enter_control`, `COMPUTER_enter`, `enter`, `enter_left`, `exit`, `exit_left`, `base`, `computer_enter`, `computer_exit`

**Models and props** (11) - `SET_SHOCK_METER_IS_VISIBLE`, `SET_DETONATE_METER_IS_VISIBLE`, `SET_RETICLE_IS_VISIBLE`, `SET_HEADING_METER_IS_VISIBLE`, `SET_ZOOM_METER_IS_VISIBLE`, `SET_BOTTOM_LEFT_CORNER_IS_VISIBLE`, `SET_MISSILE_METER_IS_VISIBLE`, `SET_INFO_LIST_IS_VISIBLE`, `SET_BOOST_METER_IS_VISIBLE`, `SET_SOUND_WAVE_IS_VISIBLE`, `SET_WARNING_IS_VISIBLE`

**Audio banks** (1) - `SCRIPT\POLICE_CHOPPER_CAM`

**Sounds** (10) - `DLC_BTL_Terrobyte_Turret_Sounds`, `Fire`, `Ctrl`, `Dir`, `Turret_Camera_Hum_Loop`, `DLC_GR_MOC_Turret_View_Scene`, `VULKAN_LOCK_ON_AMBER`, `VULKAN_LOCK_ON_RED`, `COP_HELI_CAM_ZOOM`, `COP_HELI_CAM_TURN`

**Scaleform movies** (7) - `SET_ALT_FOV_HEADING`, `SET_CAM_LOGO`, `SET_MISSILE_PERCENTAGE`, `SET_HEADING`, `SET_ZOOM`, `SET_RETICLE_STATE`, `SET_RETICLE_ON_TARGET`

**Texture dicts** (3) - `helicopterhud`, `hud_corner`, `droneHUD`

**Text labels** (1) - `NULL`

**Timecycle modifiers** (1) - `eyeinthesky`

**Vehicle mods** (1) - `terbyte`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (54), `PLAYER_PED_ID` (32), `ENABLE_CONTROL_ACTION` (32), `DOES_ENTITY_EXIST` (29), `CLEAR_BIT` (21), `GET_PLAYER_PED` (17), `DOES_CAM_EXIST` (14), `IS_ENTITY_PLAYING_ANIM` (14), `SET_BIT` (13), `IS_ENTITY_DEAD` (13), `GET_ENTITY_COORDS` (11), `GET_VEHICLE_PED_IS_IN` (10), `HAS_SOUND_FINISHED` (10), `IS_USING_KEYBOARD_AND_MOUSE` (9), `COS` (9), `STOP_SOUND` (8), `IS_PED_IN_ANY_VEHICLE` (8), `BEGIN_SCALEFORM_MOVIE_METHOD` (7), `END_SCALEFORM_MOVIE_METHOD` (7), `IS_CAM_RENDERING` (7), `ROUND` (6), `SIN` (6), `GET_SOUND_ID` (6), `PLAY_SOUND_FRONTEND` (6), `RELEASE_SOUND_ID` (6), `GET_DISABLED_CONTROL_UNBOUND_NORMAL` (6), `CLEAR_HELP` (6), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (5), `GET_CAM_COORD` (5), `GET_ENTITY_MODEL` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x8 · `0.6f` x4 · `-136.1614f` x2 · `4617.176f` x2 · `124.5134f` x2 · `-490.3058f` x2 · `4924.749f` x2 · `159.0677f` x2 · `19.5f` x2 · `0.54f` x1 · `0.44f` x1

## Other strings

Literals whose consuming native was not classified:

`HUNTGUN_1b`, `maverick`, `CELL_284`, `BLIP_184`, `BLIP_39`, `MOVE_DRONE_RE`, `DRONE_CAM`, `heli_cam`, `vehicle_weapon_hacker_missile_homing`, `vehicle_weapon_hacker_missile`, `misc_c`, `HUNTGUN_2b`, `avenger`, `MP_HTRUCK_T_2`

---

Source: `decompiled_scripts/am_mp_vehicle_weapon.c`
