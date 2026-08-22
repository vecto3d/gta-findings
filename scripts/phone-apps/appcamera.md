# appcamera.c

Phone apps script. 4 models; 6 scaleforms.

| | |
|---|---|
| Category | Phone apps |
| Total lines | 10,449 |
| Functions | 198 (76 unique, 122 shared) |
| Unique lines | 3,994 (38.2% of file) |

## Assets

**Models and props** (4) - `SET_DATA_SLOT`, `SET_REMAINING_PHOTOS`, `SET_CLEAR_SPACE`, `SET_DATA_SLOT_EMPTY`

**Sounds** (3) - `Menu_Navigate`, `Camera_Zoom`, `Camera_Shoot`

**Scaleform movies** (6) - `SET_MAX_WIDTH`, `SET_FOCUS_LOCK`, `CELL_ACTTL`, `camera_gallery`, `instructional_buttons`, `DISPLAY_VIEW`

**Text labels** (1) - `CELL_SPINNER2`

**Timecycle modifiers** (1) - `phone_cam`

**Stats** (3) - `sp0_no_photos_taken`, `sp1_no_photos_taken`, `sp2_no_photos_taken`

**Scripts launched** (1) - `pi_menu`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (93), `GET_CONTROL_INSTRUCTIONAL_BUTTONS_STRING` (91), `DISABLE_CONTROL_ACTION` (79), `IS_ENTITY_DEAD` (25), `IS_USING_KEYBOARD_AND_MOUSE` (23), `GET_DISABLED_CONTROL_UNBOUND_NORMAL` (21), `CLEAR_BIT` (20), `TO_FLOAT` (20), `GET_CONTROL_GROUP_INSTRUCTIONAL_BUTTONS_STRING` (20), `IS_CONTROL_PRESSED` (18), `SET_BIT` (17), `SET_GAME_PAUSED` (17), `FLOOR` (17), `WAIT` (15), `REPLAY_PREVENT_RECORDING_THIS_FRAME` (15), `BEGIN_SCALEFORM_MOVIE_METHOD` (15), `END_SCALEFORM_MOVIE_METHOD` (15), `IS_CONTROL_JUST_PRESSED` (15), `PLAYER_ID` (14), `ABSI` (14), `GET_GAME_TIMER` (13), `SET_WARNING_MESSAGE_WITH_HEADER` (13), `PLAY_SOUND_FRONTEND` (12), `GET_PED_PARACHUTE_STATE` (11), `CLEAR_FLOATING_HELP` (11), `GET_ENTITY_COORDS` (10), `SET_MOBILE_PHONE_ROTATION` (10), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_BOOL` (10), `HIDE_HUD_COMPONENT_THIS_FRAME` (9), `STOP_SOUND` (9)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x6 · `0.275f` x4 · `0.25f` x2 · `0.85f` x2 · `-0.25f` x2 · `0.644f` x2 · `0.83f` x2 · `0.4f` x2 · `-0.0375f` x1 · `0.3f` x1 · `0.059f` x1 · `0.165f` x1 · `0.75f` x1 · `0.79f` x1

## Other strings

Literals whose consuming native was not classified:

`SHOW_PHOTO_FRAME`, `CELL_285`, `CELL_SP_2NP_XB`, `CELL_CAM_ALERT`, `CELL_DEPTH`, `CELL_281`, `CELL_284`, `DRAW_INSTRUCTIONAL_BUTTONS`, `CELL_280`, `CELL_GRID`, `DISPLAY_VIEW`, `CELL_FOCUS`, `CELL_SP_1NP_XB`, `CLOSE_SHUTTER`, `OPEN_SHUTTER`, `Mood_Normal_1`, `CELL_286`, `CELL_296`, `CELL_295`, `HUD_AGE_P`, `CELL_CAM_SELFIE_2`, `phone_cam12DUMMY`, `SHOW_REMAINING_PHOTOS`, `CELL_294`, `CELL_293`, `CELL_RT_RSTICK`, `CELL_RT_LSTICK`, `CELL_LT_LSTICK`, `CELL_CAM_SELFIE_0_KM`, `CELL_CAM_SELFIE_0`

---

Source: `decompiled_scripts/appcamera.c`
