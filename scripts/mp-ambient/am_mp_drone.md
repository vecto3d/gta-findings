# am_mp_drone.c

MP ambient script. 3 anim dicts; 27 models; 17 scaleforms; 7 particle effects.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 15,847 |
| Functions | 583 (215 unique, 368 shared) |
| Unique lines | 8,385 (52.9% of file) |

## Assets

**Animation dictionaries** (3) - `anim@scripted@submarine@ig28_submarine_turret_control@male@`, `anim@scripted@submarine@ig28_submarine_turret_control@heeled@`, `ANIM_HEIST@HS3F@IG4_DRONE@MALE@`

**Animations** (9) - `ANIM@AMB@FACILITY@LAUNCH_CONTROLS@`, `enter`, `enter_left`, `exit`, `exit_left`, `COMPUTER_idle`, `COMPUTER_idle_control`, `COMPUTER_enter_control`, `COMPUTER_enter`

**Models and props** (27) - `SET_WARNING_IS_VISIBLE`, `SET_SOUND_WAVE_IS_VISIBLE`, `SET_DETONATE_METER_IS_VISIBLE`, `SET_SHOCK_METER_IS_VISIBLE`, `SET_MG_METER_IS_VISIBLE`, `SET_EMP_METER_IS_VISIBLE`, `SET_RETICLE_IS_VISIBLE`, `SET_BOOST_METER_IS_VISIBLE`, `SET_TRANQUILIZE_METER_IS_VISIBLE`, `ch_prop_casino_drone_01a`, `SET_HEADING_METER_IS_VISIBLE`, `SET_ZOOM_METER_IS_VISIBLE`, `SET_MISSILE_METER_IS_VISIBLE`, `SET_BOTTOM_LEFT_CORNER_IS_VISIBLE`, `SET_INFO_LIST_IS_VISIBLE`, `ba_prop_battle_secpanel`, `ba_prop_battle_secpanel_dam`, `v_faceoffice`, `ch_prop_ch_phone_ing_01a`, `xs_prop_arena_drone_01`, `xs_prop_arena_drone_02`, `xs_prop_arena_airmissile_01a`, `ch_prop_arcade_drone_01d`, `ch_prop_arcade_drone_01a`, `ch_prop_arcade_drone_01c`, `ch_prop_arcade_drone_01b`, `ba_prop_battle_drone_quad`

**Sounds** (30) - `Out_Of_Bounds_Alarm_Loop`, `DroneRotationalSpeed`, `DLC_BTL_Hacker_Drone_HUD_Scene`, `DLC_Arena_Battle_Drone_HUD_Scene`, `DLC_Arena_Spectator_Drone_HUD_Scene`, `dlc_aw_arena_piloted_missile_scene`, `dlc_hei4_submarine_guided_missile_Scene`, `HUD_Startup`, `HUD_Static_Loop`, `signalstrength`, `DLC_H3_Drone_Tranq_Weapon_Sounds`, `Shock_Fire`, `Flight_Loop`, `HUD_Disconnect`, `Scanner_Loop`, `DLC_BTL_Target_Pursuit_Sounds`, `HUD_Shock_Recharge`, `Time`, `Gun_Fire`, `Remote_Perspective_Fire`, `Pilot_Perspective_Fire`, `Destroyed`, `HUD_Detonate_Charge`, `HUD_Zoom_Change`, `HUD_Boost_Loop`, `HUD_Boost_Recharge_Loop`, `HUD_Loop`, `Missile_Launch`, `Select_Spec_Drone`, `DLC_AW_Spectator_Tablet_Sounds`

**Scaleform movies** (17) - `DRONE_CAM`, `SET_ALT_FOV_HEADING`, `SET_WEAPON_VALUES`, `SET_ZOOM_VISIBLE`, `SET_WARNING_FLASH_RATE`, `ATTENUATE_SOUND_WAVE`, `SET_HEADING`, `SET_RETICLE_ON_TARGET`, `SET_RETICLE_STATE`, `SET_ZOOM`, `SET_ZOOM_LABEL`, `SET_BOOST_PERCENTAGE`, `SET_MG_PERCENTAGE`, `SET_TRANQUILIZE_PERCENTAGE`, `SET_DETONATE_PERCENTAGE`, `SET_EMP_PERCENTAGE`, `SET_SHOCK_PERCENTAGE`

**Particle effects** (7) - `scr_xs_guided_missile_trail`, `scr_ie_vv`, `scr_xs_dr`, `flame`, `scr_ih_sub_missile_launch`, `scr_ie_vv_muzzle_flash`, `scr_xs_dr_emp`

**Text labels** (7) - `ENTER`, `NULL`, `COP`, `BASE`, `FAIL`, `EXIT`, `CREATE`

**Timecycle modifiers** (2) - `IslandPeriscope`, `eyeinthesky`

**Scripts launched** (1) - `fm_mission_controller_2020`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (162), `NET_TO_OBJ` (122), `SET_BIT` (84), `CLEAR_BIT` (82), `PLAYER_PED_ID` (65), `HAS_SOUND_FINISHED` (51), `ENABLE_CONTROL_ACTION` (48), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (47), `RELEASE_SOUND_ID` (34), `STOP_SOUND` (33), `GET_SOUND_ID` (24), `IS_ENTITY_DEAD` (23), `IS_USING_KEYBOARD_AND_MOUSE` (22), `DOES_ENTITY_EXIST` (20), `GET_ENTITY_COORDS` (18), `PLAY_SOUND_FRONTEND` (18), `COS` (18), `GET_ENTITY_HEADING` (16), `BEGIN_SCALEFORM_MOVIE_METHOD` (16), `END_SCALEFORM_MOVIE_METHOD` (16), `GET_PED_TYPE` (16), `GET_CONTROL_UNBOUND_NORMAL` (16), `APPLY_FORCE_TO_ENTITY_CENTER_OF_MASS` (16), `ROUND` (15), `NET_TO_ENT` (15), `SET_ENTITY_VISIBLE` (14), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (13), `DOES_CAM_EXIST` (13), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (13), `ABSI` (13)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x12 · `0.5f` x5 · `-0.25f` x4 · `-2.6f` x4 · `0.7f` x3 · `0.15f` x3 · `-77.74994f` x3 · `-77.99994f` x3 · `1.6f` x3 · `0.25f` x2 · `-0.1f` x2 · `2.5f` x2 · `-0.8f` x2 · `0.01f` x2 · `-1423.142f` x2 · `-3012.295f` x2 · `-1420.684f` x2 · `-3010.617f` x2 · `-0.7f` x2 · `-79.99994f` x2 · `-0.5f` x1 · `-1071.258f` x1 · `-242.5484f` x1 · `48.02133f` x1

## Other strings

Literals whose consuming native was not classified:

`DRONE_TRIG`, `scr_xs_props`, `DRONE_POSITION`, `DRONE_SPEEDU`, `DRONE_SLOWD`, `MOVE_DRONE_RE`, `CELL_284`, `BOOST_DRONE_E`, `MOVE_DRONE_UP`, `MOVE_DRONE_DO`, `RaceTurbo`, `scr_ih_sub`, `sub_hatch4`, `DLC_Arena_Drone_Sounds`, `DLC_Arena_Battle_Drone_Sounds`, `DLC_Arena_Piloted_Missile_Sounds`, `DLC_H4_Piloted_Missile_Sounds`, `DLC_BTL_Drone_Sounds`, `AM_MP_DRONE`, `MissileOutOfRange`, `RemixDrone`, `ARENA_GUN_CAM_APOCALYPSE`, `ARENA_GUN_CAM_SCIFI`, `ARENA_GUN_CAM_CONSUMER`, `INVALID_THEME`, `SUBMARINE_MISSILES`, `DRONE_SPACE`, `DRONE_ZOOM_1`, `DRONE_ZOOM_2`, `DRONE_ZOOM_3`

---

Source: `decompiled_scripts/am_mp_drone.c`
