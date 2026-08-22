# turret_cam_script.c

Dev and test harnesses script. 3 scaleforms.

| | |
|---|---|
| Category | Dev and test harnesses |
| Total lines | 3,789 |
| Functions | 156 (57 unique, 99 shared) |
| Unique lines | 1,652 (43.6% of file) |

## Assets

**Sounds** (4) - `ERROR`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `Ctrl`, `Dir`

**Scaleform movies** (3) - `SET_ALT_FOV_HEADING`, `SET_WEAPON_VALUES`, `SET_ZOOM_VISIBLE`

**Texture dicts** (2) - `helicopterhud`, `hud_outline`

**Text labels** (2) - `NULL`, `UNDEFINED`

**Timecycle modifiers** (1) - `eyeinthesky`

**Scripts launched** (1) - `am_mp_drone`

**Hashed names** (1) - `AM_MP_DRONE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (20), `CLEAR_BIT` (13), `IS_STRING_NULL_OR_EMPTY` (13), `GET_SOUND_ID` (13), `HAS_SOUND_FINISHED` (10), `PLAY_SOUND_FRONTEND` (10), `PLAYER_PED_ID` (8), `GET_ENTITY_COORDS` (7), `ROUND` (5), `IS_PED_IN_ANY_VEHICLE` (5), `GET_VEHICLE_PED_IS_IN` (5), `GET_MAIN_PLAYER_BLIP_ID` (4), `SET_BLIP_DISPLAY` (4), `SET_BLIP_ROTATION` (4), `GET_HEADING_FROM_VECTOR_2D` (4), `GET_TIMECYCLE_MODIFIER_INDEX` (4), `GET_CAM_ROT` (4), `SET_VARIABLE_ON_SOUND` (4), `STOP_SOUND` (4), `TO_FLOAT` (4), `DO_SCREEN_FADE_IN` (4), `IS_ENTITY_DEAD` (4), `IS_PAUSE_MENU_ACTIVE` (3), `DOES_BLIP_EXIST` (3), `CLEAR_HELP` (3), `BEGIN_SCALEFORM_MOVIE_METHOD` (3), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_FLOAT` (3), `END_SCALEFORM_MOVIE_METHOD` (3), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (3), `GET_CAM_COORD` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.15f` x2 · `0.54f` x1 · `0.44f` x1 · `0.04f` x1 · `1.5f` x1

## Other strings

Literals whose consuming native was not classified:

`dlc_aw_Arena_Gun_Turret_Sounds`, `dlc_aw_Arena_Spectator_Turret_turret_Sounds`, `Fire_MG_Loop`, `SCRIPT\POLICE_CHOPPER_CAM`, `dlc_aw_arena_turret_scene`, `Turret_Camera_Hum_Loop`, `Pan`, `Zoom`, `Bleep`, `DLC_IE_Steal_EITS_Sounds`, `VULKAN_LOCK_ON_AMBER`, `TC_RELOAD`, `TC_AMMO`, `helicopterhud`, `turret_cam`, `ARENA_GUN_CAM_APOCALYPSE`, `ARENA_GUN_CAM_SCIFI`, `ARENA_GUN_CAM_CONSUMER`, `Fire_Rockets_Oneshot`, `Launch_Piloted_Missile`, `Take_Damage`, `Low_Health_Warning`

---

Source: `decompiled_scripts/turret_cam_script.c`
