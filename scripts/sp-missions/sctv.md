# sctv.c

SP missions script. 6 scaleforms.

| | |
|---|---|
| Category | SP missions |
| Total lines | 411,924 |
| Functions | 7,448 (108 unique, 7,340 shared) |
| Unique lines | 15,165 (3.7% of file) |

## Assets

**Audio banks** (2) - `DLC_MPHEIST/HEIST_PLANNING_BOARD`, `DLC_MPHEIST/HEIST_APARTMENT_FOLEY`

**Sounds** (3) - `MP_POSITIONED_RADIO_MUTE_SCENE`, `MP_JOB_CHANGE_RADIO_MUTE`, `HUD_FREEMODE_CANCEL_MASTER`

**Scaleform movies** (6) - `REMOVE_ALL_POSTITS`, `REMOVE_ALL_HIGHLIGHTS`, `REMOVE_ALL_AREAS`, `REMOVE_ALL_ARROWS`, `REMOVE_ALL_TEXT`, `REMOVE_ALL_PINS`

**Text labels** (2) - `NULL`, `MP_SPINLOADING`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (60), `PLAYER_PED_ID` (52), `CLEAR_BIT` (47), `SET_BIT` (44), `DOES_ENTITY_EXIST` (24), `GET_CAM_COORD` (23), `SET_CAM_COORD` (19), `DOES_CAM_EXIST` (19), `SET_CAM_ROT` (15), `GET_ENTITY_COORDS` (14), `GET_CAM_ROT` (14), `SET_CAM_PARAMS` (12), `DESTROY_CAM` (11), `SET_CAM_ACTIVE` (11), `IS_NEW_LOAD_SCENE_ACTIVE` (11), `IS_CONTROL_PRESSED` (10), `GET_CAM_FOV` (9), `IS_ENTITY_DEAD` (9), `IS_USING_KEYBOARD_AND_MOUSE` (9), `NEW_LOAD_SCENE_STOP` (9), `IS_PLAYER_SWITCH_IN_PROGRESS` (8), `HIDE_HUD_AND_RADAR_THIS_FRAME` (8), `RENDER_SCRIPT_CAMS` (8), `GET_CONTROL_NORMAL` (7), `NETWORK_GET_PLAYER_INDEX_FROM_PED` (7), `IS_SCREEN_FADED_OUT` (7), `SET_ENTITY_VISIBLE` (6), `IS_SCREEN_FADED_IN` (6), `GET_SHAPE_TEST_RESULT` (6), `CREATE_CAM` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-89.5f` x4 · `0.5f` x3 · `0.25f` x1 · `-0.0375f` x1 · `0.2f` x1

## Other strings

Literals whose consuming native was not classified:

`DEFAULT_SCRIPTED_CAMERA`, `VIBRATE_SHAKE`, `DEFAULT_SCRIPTED_FLY_CAMERA`, `MenuMGHeistIntro`, `impexp_garage_level2_cost`, `HEIST_PRE_VIEW`, `HEIST_PRE_DONE`, `HEIST_NOTE_2`, `mp_m_freemode_01`, `mp_f_freemode_01`

---

Source: `decompiled_scripts/sctv.c`
