# finale_heist1.c

Heists script. 6 anim dicts; 8 models; 4 scaleforms; 1 particle effects.

| | |
|---|---|
| Category | Heists |
| Total lines | 139,736 |
| Functions | 1,016 (89 unique, 927 shared) |
| Unique lines | 12,659 (9.1% of file) |

## Assets

**Animation dictionaries** (6) - `move_lester_CaneUp`, `missbigscore1guard_wait_rifle`, `shake_cam_all@`, `missheist_the_big_score_setup_1@heli_exit`, `missheist_the_big_score_setup_1@camera@idle_a`, `missbigscore1_mcs1`

**Animations** (21) - `missbigscore1_mcs1`, `missheist_the_big_score_setup_1@camera@idle_a`, `missbigscore1guard_wait_rifle`, `michael_bss_1_mcs_1`, `franklin_bss_1_mcs_1`, `idle_a`, `idle_c`, `mid_mission_inside_helicopter_trevor`, `mid_mission_inside_helicopter_lester`, `bss_1_mcs_2_leadout_fra`, `bss_1_mcs_2_leadout_mic`, `wait_base`, `wait_a`, `wait_b`, `wait_c`, `missheist_the_big_score_setup_1@heli_exit`, `lester_exit_heli`, `bss_1_mcs_2_leadin_fra`, `bss_1_mcs_2_leadin_mic`, `PISS_LOOP`, `PISS_OUTRO`

**Models and props** (8) - `s_m_m_armoured_01`, `frogger2`, `prop_pap_camera_01`, `bulldozer`, `prop_ld_test_01`, `stockade`, `police3`, `prop_bollard_02a`

**Sounds** (26) - `HUD_MINI_GAME_SOUNDSET`, `10_SEC_WARNING`, `BS_1_drive_START`, `BS_1_BANK_CHECK_OUT`, `BS_1_BANK_HINT_CAM`, `BS_1_SWITCH_TO_TREVOR`, `BS_1_FLY_TO_TRUCKS`, `BS_1_TRUCKS_SPOTTED`, `BS_1_DRIVE_AROUND_BACK`, `BS_1_TRUCKS_HINT_CAM`, `BS_1_SEARCH_FOR_ENTRANCE`, `BS_1_HELI_RETURN_TO_AIRSTRIP`, `BS_1_TRUCKS_ENTER_TUNNEL`, `BS_1_VIEW_RECORDING`, `BS_1_CAR_RETURN_TO_FRANKLINS`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `BIG_SCORE_SETUP_SOUNDS`, `HINT_CAM_SCENE`, `FocusOut`, `HintCamSounds`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `TIMER_STOP`, `Camera_Zoom`, `Camera_Hum`

**Scaleform movies** (4) - `SET_TIME`, `SECURITY_CAM`, `SET_LAYOUT`, `SET_LOCATION`

**Particle effects** (1) - `scr_bigscore_peeing`

**Text labels** (12) - `FH1AUD`, `TREVOR`, `MICHAEL`, `FRANKLIN`, `LESTER`, `FH1REC`, `FH1RECMIKE`, `NULL`, `FH1UBER`, `OFF`, `EXTRASUNNY`, `FINH1`

**Vehicle recordings** (3) - `FH1RECMIKE`, `FH1REC`, `FH1UBER`

**Relationship groups** (2) - `BUDDY`, `GUARD`

**Timecycle modifiers** (1) - `scanline_cam_cheap`

**Vehicle mods** (3) - `tailgater`, `bodhi2`, `bus`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (170), `GET_GAME_TIMER` (117), `IS_PED_IN_VEHICLE` (100), `DOES_ENTITY_EXIST` (87), `IS_ENTITY_DEAD` (66), `PLAYER_ID` (61), `GET_ENTITY_COORDS` (58), `IS_PED_INJURED` (56), `WAIT` (56), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (56), `IS_VEHICLE_DRIVEABLE` (52), `SET_ENTITY_ONLY_DAMAGED_BY_PLAYER` (47), `FREEZE_ENTITY_POSITION` (47), `IS_AUDIO_SCENE_ACTIVE` (42), `SET_PLAYER_CONTROL` (40), `SET_PED_INTO_VEHICLE` (37), `RENDER_SCRIPT_CAMS` (36), `GET_SCRIPT_TASK_STATUS` (34), `SET_ENTITY_VISIBLE` (34), `IS_MESSAGE_BEING_DISPLAYED` (33), `IS_ENTITY_VISIBLE` (30), `DISPLAY_HUD` (29), `DOES_CAM_EXIST` (29), `DISPLAY_RADAR` (28), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (26), `DOES_BLIP_EXIST` (25), `STOP_SOUND` (25), `SET_ENTITY_COORDS` (24), `SET_CAM_FOV` (24), `SET_PLAYBACK_SPEED` (23)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x20 · `15.08808f` x8 · `-1.5f` x6 · `0.25f` x5 · `0.5f` x5 · `-9.34495f` x4 · `-741.3211f` x4 · `43.15848f` x4 · `-2.55928f` x4 · `-743.9714f` x4 · `-14.34047f` x4 · `-739.4463f` x4 · `43.15934f` x4 · `4.46f` x4 · `1527.602f` x4 · `-591.3962f` x4 · `336.5655f` x4 · `1758.309f` x4 · `3284.528f` x4 · `40.7f` x4 · `133.1852f` x4 · `1799.963f` x3 · `3321.91f` x3 · `40.8868f` x3

## Other strings

Literals whose consuming native was not classified:

`premier`, `serrano`, `frogger2`, `Lester`, `move_lester_CaneUp`, `FH1_BANK`, `Franklin`, `Michael`, `FH1_FILM`, `FH1_FRCAR`, `Trevor`, `missbigscore1guard_wait_rifle`, `hand_shake`, `stockade`, `FH1_AIR`, `CMN_GENGETINY`, `CMN_GENGETBCKY`, `FH1_BKHELI`, `MotionState_Walk`, `FH1_FAIL`, `player`, `FH1_HOLECAM`, `security_guard`, `thisSwitchCam`, `missbigscore1_mcs1`, `FH1_HELI`, `Stage 2: Back of bank`, `Stage 1: Front of bank`, `bs_1_int`, `bulldozer`

---

Source: `decompiled_scripts/finale_heist1.c`
