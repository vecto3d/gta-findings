# re_homeland_security.c

Random events script. 1 anim dicts; 2 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 9,002 |
| Functions | 224 (28 unique, 196 shared) |
| Unique lines | 2,024 (22.5% of file) |

## Assets

**Animation dictionaries** (1) - `random@homelandsecurity`

**Animations** (12) - `random@homelandsecurity`, `idle_girl`, `idle_to_knees_girl`, `knees_loop_girl`, `knees_to_stand_girl`, `idle_cop_ground`, `idle_to_stand_cop_ground`, `exit_girl`, `exit_cop_gun`, `exit_cop_ground`, `exit_car`, `idle_cop_gun`

**Models and props** (2) - `a_f_y_tourist_01`, `a_m_o_acult_01`

**Speech contexts** (1) - `REHOMGirl`

**Text labels** (5) - `REHOMAU`, `COP`, `NULL`, `MICHAEL`, `FRANKLIN`

**Scenarios** (1) - `WORLD_HUMAN_SMOKING`

**Relationship groups** (1) - `OFFICERS`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (106), `IS_PED_INJURED` (71), `DOES_BLIP_EXIST` (26), `IS_ENTITY_AT_ENTITY` (23), `GET_GAME_TIMER` (22), `REMOVE_BLIP` (17), `PLAYER_ID` (16), `WAIT` (16), `IS_VEHICLE_DRIVEABLE` (15), `IS_PED_ARMED` (15), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (14), `SET_PED_KEEP_TASK` (13), `IS_PED_IN_VEHICLE` (13), `DOES_ENTITY_EXIST` (12), `IS_ENTITY_PLAYING_ANIM` (10), `OPEN_SEQUENCE_TASK` (10), `CLOSE_SEQUENCE_TASK` (10), `TASK_PERFORM_SEQUENCE` (10), `IS_ENTITY_DEAD` (10), `CLEAR_SEQUENCE_TASK` (9), `TASK_SYNCHRONIZED_SCENE` (9), `IS_PED_IN_GROUP` (8), `TASK_LOOK_AT_ENTITY` (8), `TASK_CLEAR_LOOK_AT` (8), `GET_PLAYERS_LAST_VEHICLE` (8), `IS_SYNCHRONIZED_SCENE_RUNNING` (8), `GET_SCRIPT_TASK_STATUS` (7), `CAN_PED_SEE_HATED_PED` (6), `REQUEST_MODEL` (6), `SET_MODEL_AS_NO_LONGER_NEEDED` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x6 · `0.1f` x5 · `1.5f` x4 · `0.25f` x2 · `38.9844f` x2 · `2.5f` x2 · `420.5f` x1 · `0.3f` x1 · `0.8f` x1 · `0.85f` x1 · `0.98f` x1 · `0.45f` x1 · `0.9f` x1 · `0.95f` x1 · `374.869f` x1 · `-1358.043f` x1 · `25.667f` x1 · `452.41f` x1 · `-1423.882f` x1 · `38.337f` x1

## Other strings

Literals whose consuming native was not classified:

`REHOM_PLEA`, `REHOM_WRONG`, `REHOM_CULT`, `REHOM_HOME`, `REHOM_GETOUT`, `REHOM_JACK`, `REHOM_SHOOT`, `REHOM_QM`, `REHOM_ARR`, `AC_STOP`, `RE_RA`, `REHOM_YELL`, `REHOM_YELL2`, `REHOM_THNK`, `REHOM_ASK`, `REHOM_RES1_M`, `REHOM_GOGO`, `REHOM_COME`, `REHOM_WTF_M`, `REHOM_WTF_F`, `REHOM_CORR`, `REHOM_TALK`, `REHOM_CAR_M`, `REHOM_CAR_F`, `REHOM_TALK2`, `REHOM_REJ_M`, `REHOM_REJ_F`, `REHOM_TALK2b`, `REHOM_TALK3`, `REHOM_INT_M`

---

Source: `decompiled_scripts/re_homeland_security.c`
