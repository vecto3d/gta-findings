# re_cartheft.c

Random events script. 7 anim dicts; 6 models; 1 particle effects.

| | |
|---|---|
| Category | Random events |
| Total lines | 9,653 |
| Functions | 250 (27 unique, 223 shared) |
| Unique lines | 2,085 (21.6% of file) |

## Assets

**Animation dictionaries** (7) - `random@car_thief@waving_ig_1`, `RANDOM@CAR_THEFT_1@MCS_2`, `RANDOM@CAR_THIEF@waiting_ig_4`, `RANDOM@CAR_THIEF@VICTIMPOINTS_IG_3`, `RANDOM@CAR_THIEF@WAITING_IG_4`, `RANDOM@CAR_THEFT_1@MCS_3`, `random@car_thief@waving_ig_2`

**Animations** (6) - `arms_waving`, `waiting`, `RANDOM@CAR_THIEF@WAITING_IG_4`, `idle_a`, `agitated_idle_a`, `pointing`

**Models and props** (6) - `a_f_y_vinewood_04`, `g_m_y_salvagoon_01`, `A_F_Y_VINEWOOD_04_WHITE_MINI_02`, `a_f_y_indian_01`, `a_m_m_soucent_04`, `A_M_M_SOUCENT_04_BLACK_MINI_01`

**Sounds** (1) - `RE_CAR_STEAL_SCENE`

**Particle effects** (1) - `scr_wheel_burnout`

**Text labels** (8) - `STRING`, `CIVMALE`, `NULL`, `RECT1AU`, `RECT2AU`, `MICHAEL`, `FRANKLIN`, `TREVOR`

**Scenarios** (1) - `WORLD_HUMAN_STAND_MOBILE`

**Relationship groups** (1) - `re_cartheft relGroupThief`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (103), `IS_PED_INJURED` (36), `GET_ENTITY_COORDS` (25), `DOES_BLIP_EXIST` (16), `VDIST` (14), `WAIT` (13), `SET_PED_RESET_FLAG` (13), `OPEN_SEQUENCE_TASK` (12), `CLOSE_SEQUENCE_TASK` (12), `TASK_PERFORM_SEQUENCE` (12), `CLEAR_SEQUENCE_TASK` (12), `TASK_PLAY_ANIM` (12), `SET_PED_KEEP_TASK` (10), `IS_PED_IN_ANY_VEHICLE` (10), `GET_GAME_TIMER` (10), `PLAYER_ID` (9), `IS_PED_IN_VEHICLE` (9), `GET_VEHICLE_PED_IS_IN` (9), `IS_ENTITY_AT_ENTITY` (8), `HIDE_HUD_AND_RADAR_THIS_FRAME` (8), `GET_SYNCHRONIZED_SCENE_PHASE` (8), `SET_PED_COMPONENT_VARIATION` (8), `REMOVE_BLIP` (7), `SET_ENTITY_COORDS` (7), `IS_ENTITY_PLAYING_ANIM` (7), `TASK_TURN_PED_TO_FACE_ENTITY` (7), `TASK_SMART_FLEE_PED` (6), `SET_MODEL_AS_NO_LONGER_NEEDED` (6), `GET_ENTITY_MODEL` (6), `IS_SYNCHRONIZED_SCENE_RUNNING` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x3 · `1.5f` x3 · `-0.5f` x2 · `0.25f` x2 · `0.83f` x2 · `-743.3924f` x1 · `-2129.82f` x1 · `12.07619f` x1 · `-708.892f` x1 · `-2160.705f` x1 · `19.7035f` x1 · `124.5f` x1 · `0.1f` x1 · `-2255.21f` x1 · `4271.04f` x1 · `44.875f` x1 · `-500.924f` x1 · `-2165.36f` x1 · `7.6988f` x1 · `64.6764f` x1 · `0.2f` x1 · `0.86f` x1 · `0.847f` x1 · `0.99f` x1

## Other strings

Literals whose consuming native was not classified:

`rocoto`, `peyote`, `car_returned_peyote`, `girl_car_returned`, `player_car_returned`, `wheel_lr`, `wheel_rr`, `waiting`, `GENERIC_CURSE_HIGH`, `chassis`, `DEFAULT_ANIMATED_CAMERA`, `car_returned_cam`, `RECT2_REWARD`, `MotionState_Idle`, `CThiefVictim`, `RECT1_ATTR`, `RECT1_HELP`, `RECT1_FYOU`, `RECT1_JOY`, `RECT1_OK`, `RECT1_BAD`, `RECT1_GOOD`, `waving_l`, `waving`, `CThiefGolfer`, `RECT2_ATTR`, `RECT2_HELP`, `RECT2_FYOU`, `RECT2_JOY`, `RECT2_OK`

---

Source: `decompiled_scripts/re_cartheft.c`
