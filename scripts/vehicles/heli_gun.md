# heli_gun.c

Vehicles script. 8 models; 9 scaleforms; 2 particle effects.

| | |
|---|---|
| Category | Vehicles |
| Total lines | 14,400 |
| Functions | 365 (179 unique, 186 shared) |
| Unique lines | 9,169 (63.7% of file) |

## Assets

**Animations** (10) - `ANIM@AMB@FACILITY@LAUNCH_CONTROLS@`, `enter`, `exit`, `ANIM@ARENA@AMB@SEAT_DRONE_TABLET@MALE@`, `ANIM@ARENA@AMB@SEAT_DRONE_TABLET@FEMALE@`, `base`, `computer_exit`, `enter_left`, `exit_left`, `computer_enter`

**Models and props** (8) - `w_lr_rpg_rocket`, `SET_ZOOM_METER_IS_VISIBLE`, `SET_CANNON_METER_IS_VISIBLE`, `SET_RETICLE_IS_VISIBLE`, `SET_STRIPES_VISIBLE`, `SET_HEADING_METER_IS_VISIBLE`, `SET_BOTTOM_LEFT_CORNER_IS_VISIBLE`, `w_ex_vehiclemissile_3`

**Audio banks** (1) - `SCRIPT\POLICE_CHOPPER_CAM`

**Sounds** (17) - `MP_HELI_CAM_FILTERING`, `CAR_2_HELI_FILTERING`, `Ctrl`, `COP_HELI_CAM_BLEEP`, `COP_HELI_CAM_SCAN_PED_LOOP`, `COP_HELI_CAM_SCAN_PED_SUCCESS`, `COP_HELI_CAM_SCAN_PED_FAILURE`, `COP_HELI_CAM_BLEEP_TOO_FAR`, `Pan_Loop`, `Pan`, `COP_HELI_CAM_TURN`, `Zoom_Loop`, `Zoom`, `COP_HELI_CAM_ZOOM`, `Dir`, `HeliFiltering`, `COP_HELI_CAM_BACKGROUND`

**Scaleform movies** (9) - `SET_CAM_LOGO`, `SET_ALT_FOV_HEADING`, `SET_ZOOM`, `SET_ZOOM_LABEL`, `SET_CANNON_NAME`, `SET_CANNON_PERCENTAGE`, `SET_RETICLE_STATE`, `SET_CANNON_LABEL`, `CANNON_AMMO`

**Particle effects** (2) - `muz_xm_volatol_twinmg`, `scr_xm_volatol_turret_camera`

**Texture dicts** (7) - `helicopterhud`, `hud_corner`, `TargetLost`, `hud_dest`, `hud_line`, `hudArrow`, `helicopterHUD`

**Text labels** (4) - `CHOPPER`, `PREV`, `NULL`, `INVALID`

**Decorators** (1) - `MC_EntityID`

**Timecycle modifiers** (2) - `eyeinthesky`, `heliGunCam`

**Vehicle mods** (1) - `terbyte`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (169), `PLAYER_PED_ID` (102), `GET_ENTITY_MODEL` (68), `DISABLE_CONTROL_ACTION` (59), `DOES_ENTITY_EXIST` (40), `IS_ENTITY_DEAD` (37), `ABSF` (34), `CLEAR_HELP` (32), `GET_SCREEN_COORD_FROM_WORLD_COORD` (26), `IS_VEHICLE_SEAT_FREE` (25), `COS` (24), `HAS_SOUND_FINISHED` (24), `GET_PED_BONE_COORDS` (20), `SIN` (19), `IS_CONTROL_JUST_PRESSED` (18), `STOP_SOUND` (18), `DOES_CAM_EXIST` (17), `GET_ENTITY_COORDS` (17), `PLAY_SOUND_FRONTEND` (16), `IS_VEHICLE_MODEL` (16), `SET_DRAW_ORIGIN` (16), `IS_PED_INJURED` (15), `IS_VEHICLE_DRIVEABLE` (15), `DOES_BLIP_EXIST` (15), `GET_PLAYER_PED` (15), `GET_MAIN_PLAYER_BLIP_ID` (14), `IS_ENTITY_PLAYING_ANIM` (14), `PARTICIPANT_ID_TO_INT` (13), `ATTACH_CAM_TO_ENTITY` (13), `IS_PAUSE_MENU_ACTIVE` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x14 · `0.013f` x8 · `0.4f` x5 · `1.958f` x4 · `0.01f` x3 · `2.75f` x3 · `-1.25f` x3 · `-0.618f` x3 · `0.54f` x2 · `0.44f` x2 · `-0.5f` x2 · `0.68f` x2 · `0.042f` x2 · `0.29f` x2 · `5.32f` x2 · `-0.3f` x2 · `0.6f` x2 · `0.25f` x2 · `0.65f` x1 · `3.5f` x1 · `0.02f` x1 · `0.04f` x1 · `1.7f` x1 · `0.1f` x1

## Other strings

Literals whose consuming native was not classified:

`hunter`, `akula`, `savage`, `buzzard`, `volatol`, `bombushka`, `conada2`, `valkyrie`, `avenger`, `BOMBGUN_FULL`, `TITAN2_1c3`, `TITAN2_1c3c`, `avenger3`, `TITAN2_1c3b`, `TITAN2_1c3d`, `TITAN2_1c3e`, `polmav`, `BOMBGUN_T_2c`, `vehicle_weapon_mobileops_cannon`, `HUNTGUN_2`, `HUNTGUN_2b`, `HUNTGUN_2c`, `HUNTGUN_4`, `HUNTGUN_4b`, `AKULAGUN_P1`, `HUNTGUN_3`, `HUNTGUN_3b`, `HUNTGUN_3c`, `AKULAGUN_2`, `BOMBGUN_1o`

---

Source: `decompiled_scripts/heli_gun.c`
