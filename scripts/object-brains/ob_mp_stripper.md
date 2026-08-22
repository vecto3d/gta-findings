# ob_mp_stripper.c

Object brains script. 8 anim dicts; 2 models.

| | |
|---|---|
| Category | Object brains |
| Total lines | 5,963 |
| Functions | 96 (8 unique, 88 shared) |
| Unique lines | 600 (10.1% of file) |

## Assets

**Animation dictionaries** (8) - `mini@strip_club@lap_dance_2g@ld_2g_intro`, `mini@strip_club@lap_dance_2g@ld_2g_p1`, `mini@strip_club@lap_dance_2g@ld_2g_p2`, `mini@strip_club@lap_dance_2g@ld_2g_p3`, `mini@strip_club@lap_dance_2g@ld_2g_exit`, `mini@strip_club@lap_dance_2g@ld_2g_wait`, `mini@strip_club@lap_dance_2g@ld_2g_accept`, `mini@strip_club@lap_dance_2g@ld_2g_decline`

**Models and props** (2) - `s_f_y_stripper_01`, `s_f_y_stripper_02`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`NET_TO_PED` (24), `PLAYER_PED_ID` (18), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (18), `PLAY_FACIAL_ANIM` (12), `HIDE_HUD_AND_RADAR_THIS_FRAME` (10), `PLAYER_ID` (9), `REQUEST_ANIM_DICT` (8), `HAS_ANIM_DICT_LOADED` (8), `REMOVE_ANIM_DICT` (8), `CLEAR_HELP` (6), `NETWORK_CREATE_SYNCHRONISED_SCENE` (6), `NETWORK_START_SYNCHRONISED_SCENE` (6), `GET_ENTITY_HEADING` (4), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (4), `GET_SYNCHRONIZED_SCENE_PHASE` (4), `SET_MODEL_AS_NO_LONGER_NEEDED` (4), `IS_CONTROL_JUST_PRESSED` (3), `REQUEST_MODEL` (2), `HAS_MODEL_LOADED` (2), `IS_PED_INJURED` (2), `GET_DISTANCE_BETWEEN_COORDS` (2), `GET_ENTITY_COORDS` (2), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (2), `NETWORK_DOES_NETWORK_ID_EXIST` (2), `CAN_REGISTER_MISSION_PEDS` (2), `NETWORK_IS_GAME_IN_PROGRESS` (1), `NETWORK_SET_THIS_SCRIPT_IS_NETWORK_SCRIPT` (1), `SET_THIS_SCRIPT_CAN_BE_PAUSED` (1), `DOES_ENTITY_EXIST` (1), `RESERVE_NETWORK_MISSION_PEDS` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x3 · `2.5f` x1 · `0.75f` x1 · `0.5f` x1

## Other strings

Literals whose consuming native was not classified:

`SA_STRIP_CALL`, `SA_STRIP_MENU`, `SA_STRIP_CAM`, `ld_2g_intro_m`, `ld_2g_intro_s1`, `ld_2g_intro_s2`, `ld_2g_intro_s1_face`, `ld_2g_intro_s2_face`, `ld_2g_p1_m`, `ld_2g_p1_s1`, `ld_2g_p1_s2`, `ld_2g_p1_s1_face`, `ld_2g_p1_s2_face`, `ld_2g_p2_m`, `ld_2g_p2_s1`, `ld_2g_p2_s2`, `ld_2g_p2_s1_face`, `ld_2g_p2_s2_face`, `ld_2g_p3_m`, `ld_2g_p3_s1`, `ld_2g_p3_s2`, `ld_2g_p3_s1_face`, `ld_2g_p3_s2_face`, `ld_2g_exit_m`, `ld_2g_exit_s1`, `ld_2g_exit_s2`, `ld_2g_exit_s1_face`, `ld_2g_exit_s2_face`, `ld_2g_wait_m`, `ld_2g_wait_s1`

---

Source: `decompiled_scripts/ob_mp_stripper.c`
