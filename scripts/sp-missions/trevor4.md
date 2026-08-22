# trevor4.c

SP missions script. 1 anim dicts; 2 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 110,910 |
| Functions | 769 (33 unique, 736 shared) |
| Unique lines | 1,340 (1.2% of file) |

## Assets

**Animation dictionaries** (1) - `SWITCH@MICHAEL@BENCH`

**Animations** (5) - `SWITCH@MICHAEL@BENCH`, `CELLPHONE_CALL_OUT`, `bench_on_phone_idle`, `exit_forward`, `CELLPHONE_CALL_LISTEN_BASE`

**Models and props** (2) - `prop_phone_ing`, `v_michael`

**Text labels** (6) - `TRV5AUD`, `TRV5`, `NULL`, `MICHAEL`, `LESTER`, `TREVOR`

**Scenarios** (1) - `WORLD_HUMAN_GUARD_STAND`

**Relationship groups** (1) - `player`

**Doors** (1) - `v_ilev_trev_doorfront`

**Vehicle mods** (1) - `bodhi2`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (101), `APPLY_PED_BLOOD_SPECIFIC` (31), `PLAYER_ID` (9), `SET_PED_CONFIG_FLAG` (9), `WAIT` (8), `DOES_ENTITY_EXIST` (7), `GET_GAME_TIMER` (6), `HIDE_HUD_AND_RADAR_THIS_FRAME` (6), `SET_PED_RESET_FLAG` (6), `IS_PED_IN_ANY_VEHICLE` (5), `GET_VEHICLE_PED_IS_IN` (5), `CLEAR_PRINTS` (4), `CLEAR_HELP` (4), `SET_BIT` (4), `IS_CUTSCENE_PLAYING` (4), `DISABLE_CONTROL_ACTION` (4), `GET_PLAYER_WANTED_LEVEL` (4), `REPLAY_CHECK_FOR_EVENT_THIS_FRAME` (3), `REGISTER_ENTITY_FOR_CUTSCENE` (3), `REPLAY_RECORD_BACK_FOR_TIME` (3), `SET_CAM_PARAMS` (3), `GET_ENTITY_COORDS` (3), `SET_MODEL_AS_NO_LONGER_NEEDED` (3), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (3), `OPEN_SEQUENCE_TASK` (3), `CLOSE_SEQUENCE_TASK` (3), `TASK_PERFORM_SEQUENCE` (3), `CLEAR_SEQUENCE_TASK` (3), `REQUEST_ADDITIONAL_TEXT` (3), `SIMULATE_PLAYER_INPUT_GAIT` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.95f` x10 · `0.9f` x5 · `0.85f` x4 · `0.25f` x3 · `0.607f` x3 · `23.11205f` x2 · `0.712f` x2 · `0.451f` x2 · `0.754f` x2 · `0.852f` x2 · `0.615f` x2 · `0.582f` x2 · `0.23f` x2 · `0.985f` x2 · `9.63f` x2 · `0.196f` x2 · `29.2f` x2 · `-1150.039f` x1 · `-1521.761f` x1 · `9.6331f` x1 · `130.2632f` x1 · `-1295.035f` x1 · `28.2695f` x1 · `98.5821f` x1

## Other strings

Literals whose consuming native was not classified:

`Scripted_Ped_Splash_Back`, `Trevor`, `M_HangTen`, `AM_H_TRCLUB`, `bodhi2`, `MotionState_Walk`, `TRV_5_EXT`, `DEFAULT_SCRIPTED_CAMERA`, `Force cleanup [TERMINATING]`, `M_FAIL`, `TRV5_FWADE`, `TRV5_ABAN`, `HAND_SHAKE`, `TRV5_Miccall`, `TRV5_where`, `TRV5_Start`, `TRV5_arrive`, `TRV5_CLUB`, `TRV5_WADE`, `TRV_5_INT`, `Floyd`, `Wade`

---

Source: `decompiled_scripts/trevor4.c`
