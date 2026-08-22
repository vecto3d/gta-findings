# paparazzo4.c

SP strangers and freaks script. 3 anim dicts; 4 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 41,475 |
| Functions | 425 (55 unique, 370 shared) |
| Unique lines | 2,475 (6.0% of file) |

## Assets

**Animation dictionaries** (3) - `MISSCOMMON@HANDS_UP_FLINCH`, `reaction@back_away@f`, `random@escape_paparazzi@standing@`

**Animations** (5) - `flinch_additive_a`, `rcmpaparazzo_4`, `pap_4_rcm_leadin`, `Idle_Camman`, `Idle_Prod`

**Models and props** (4) - `s_m_y_grip_01`, `a_f_y_bevhills_02`, `prop_pap_camera_01`, `prop_v_cam_01`

**Text labels** (6) - `PAP4AUD`, `NULL`, `CAMERA`, `PAP4`, `FRANKLIN`, `BEVERLY`

**Hashed names** (3) - `ACT_takedown_a`, `ACT_takedown_heavy`, `ACT_armed_takedown`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (126), `GET_GAME_TIMER` (37), `IS_PED_FLEEING` (31), `DOES_ENTITY_EXIST` (26), `IS_PED_IN_COMBAT` (22), `IS_PED_IN_ANY_VEHICLE` (21), `TASK_SMART_FLEE_PED` (16), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (16), `TASK_TURN_PED_TO_FACE_ENTITY` (15), `IS_ENTITY_PLAYING_ANIM` (14), `SET_PED_COMPONENT_VARIATION` (12), `IS_PED_IN_VEHICLE` (11), `IS_PED_IN_MELEE_COMBAT` (11), `SET_PED_FLEE_ATTRIBUTES` (10), `IS_ENTITY_ON_FIRE` (10), `STOP_ANIM_TASK` (10), `DOES_BLIP_EXIST` (9), `TASK_COMBAT_PED` (9), `CLOSE_SEQUENCE_TASK` (8), `TASK_PERFORM_SEQUENCE` (8), `CLEAR_SEQUENCE_TASK` (8), `OPEN_SEQUENCE_TASK` (8), `TASK_PLAY_ANIM` (8), `IS_PED_RAGDOLL` (8), `ARE_STRINGS_EQUAL` (8), `STOP_SYNCHRONIZED_ENTITY_ANIM` (7), `IS_MESSAGE_BEING_DISPLAYED` (7), `SET_BLIP_SCALE` (7), `TASK_SYNCHRONIZED_SCENE` (7), `ACTION_MANAGER_ENABLE_ACTION` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.7f` x6 · `1.5f` x4 · `0.25f` x4 · `0.3f` x2 · `0.5f` x2 · `-483.5037f` x2 · `231.0559f` x2 · `82.1456f` x2 · `-490.809f` x2 · `232.39f` x2 · `82.018f` x2 · `33.84f` x2 · `0.1f` x1 · `0.45f` x1 · `-0.01f` x1 · `0.1561f` x1 · `-0.003f` x1 · `-0.0344f` x1 · `202.8703f` x1 · `-124.43f` x1 · `-121.5398f` x1 · `0.1181f` x1 · `0.2229f` x1 · `-0.1535f` x1

## Other strings

Literals whose consuming native was not classified:

`PAP4_THREAT`, `object`, `PAP4_ATTACK`, `rcmpaparazzo_4`, `BLIP_FRIEND`, `BLIP_ENEMY`, `PAP4_STEAL`, `pap_4_rcm`, `Franklin`, `Beverley`, `film_guy`, `makeup_artist`, `Beverlys_camera`, `Video_camera_forMan`, `pcj`, `lift_hands_in_air_loop`, `base_pap`, `base_camman`, `base_prod`, `gesture_to_cam_pap`, `gesture_to_cam_camman`, `gesture_to_cam_prod`, `idle_pap`, `idle_camman`, `idle_prod`, `pap4_BevRoute`, `pap4_CamRoute`, `PAPARAZZO_04_SOUNDSET`, `Force cleanup [TERMINATING]`

---

Source: `decompiled_scripts/paparazzo4.c`
