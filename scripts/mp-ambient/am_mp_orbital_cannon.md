# am_mp_orbital_cannon.c

MP ambient script. 1 anim dicts; 5 scaleforms; 2 particle effects.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 7,615 |
| Functions | 265 (44 unique, 221 shared) |
| Unique lines | 1,853 (24.3% of file) |

## Assets

**Animation dictionaries** (1) - `anim@scripted@player@mission@tun_control_tower@male@`

**Audio banks** (1) - `DLC_CHRISTMAS2017/XM_ION_CANNON`

**Sounds** (11) - `dlc_xm_orbital_cannon_sounds`, `dlc_xm_orbital_cannon_camera_active_scene`, `Firing`, `zoom_out_loop`, `cannon_active`, `inactive_fire_fail`, `pan_loop`, `DLC_XM_Explosions_Orbital_Cannon`, `cannon_charge_fire_loop`, `background_loop`, `cannon_activating_loop`

**Scaleform movies** (5) - `SET_ZOOM_LEVEL`, `SET_COUNTDOWN`, `SET_CHARGING_LEVEL`, `ORBITAL_CANNON_CAM`, `SET_STATE`

**Particle effects** (2) - `scr_xm_orbital`, `scr_xm_orbital_blast`

**Texture dicts** (1) - `helicopterhud`

**Text labels** (1) - `NULL`

**Hashed names** (2) - `fm_mission_controller_2020`, `fm_mission_controller_v3`

## Native vocabulary

Most-called natives inside the code unique to this script:

`CLEAR_BIT` (67), `SET_BIT` (46), `PLAYER_PED_ID` (31), `PLAYER_ID` (15), `BEGIN_SCALEFORM_MOVIE_METHOD` (13), `END_SCALEFORM_MOVIE_METHOD` (13), `TIMESTEP` (12), `ABSF` (10), `DISABLE_CONTROL_ACTION` (9), `PLAY_SOUND_FRONTEND` (8), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_FLOAT` (7), `GET_ENTITY_COORDS` (7), `DOES_CAM_EXIST` (6), `GET_SOUND_ID` (6), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (6), `GET_CONTROL_INSTRUCTIONAL_BUTTONS_STRING` (6), `HIDE_HUD_COMPONENT_THIS_FRAME` (5), `GET_PLAYER_PED` (5), `DOES_ENTITY_EXIST` (5), `IS_ENTITY_AT_COORD` (5), `NETWORK_SET_IN_FREE_CAM_MODE` (4), `RENDER_SCRIPT_CAMS` (4), `IS_PED_INJURED` (4), `SET_CONTROL_SHAKE` (4), `IS_USING_KEYBOARD_AND_MOUSE` (4), `GET_GAME_TIMER` (4), `CLEAR_FOCUS` (3), `CASCADE_SHADOWS_SET_AIRCRAFT_MODE` (3), `CLEAR_OVERRIDE_WEATHER` (3), `DESTROY_CAM` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x13

## Other strings

Literals whose consuming native was not classified:

`MP_OrbitalCannon`, `loop`, `GAMEPLAY_EXPLOSION_SHAKE`, `Clear`, `DEFAULT_SCRIPTED_CAMERA`, `HUD_INPUT3`, `ORB_CAN_RE`, `ORB_CAN_ZOOMO`, `ORB_CAN_ZOOMI`, `ORB_CAN_ZOOM`, `ORB_CAN_FIRE`, `ORB_CAN_START`

---

Source: `decompiled_scripts/am_mp_orbital_cannon.c`
