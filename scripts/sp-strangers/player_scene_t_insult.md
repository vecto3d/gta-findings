# player_scene_t_insult.c

SP strangers and freaks script. 9 anim dicts; 14 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 7,516 |
| Functions | 60 (11 unique, 49 shared) |
| Unique lines | 1,122 (14.9% of file) |

## Assets

**Animation dictionaries** (9) - `SWITCH@TREVOR@CHASE_STRIPPERS`, `SWITCH@TREVOR@SCARES_TRAMP`, `SWITCH@TREVOR@THROW_FOOD`, `SWITCH@TREVOR@MOCKS_LAPDANCE`, `SWITCH@TREVOR@ANNOYS_SUNBATHERS`, `move_f@scared`, `move_m@hurry_Butch@A`, `SWITCH@TREVOR@RUDE_AT_CAFE`, `SWITCH@TREVOR@UNDER_PIER`

**Models and props** (14) - `p_trev_rope_01_s`, `s_f_y_stripper_01`, `a_f_y_beach_01`, `prop_cs_beachtowel_01`, `a_m_y_musclbeac_01`, `s_f_y_stripper_02`, `a_m_y_hipster_01`, `a_m_y_beach_01`, `a_f_y_hipster_03`, `a_m_o_tramp_01`, `a_m_y_stlat_01`, `a_m_m_business_01`, `prop_rolled_sock_01`, `A_M_O_TRAMP_01_BLACK_FULL_01`

**Text labels** (6) - `PRSAUD`, `NULL`, `PIERWOMAN`, `TREVOR`, `STRIPPER1`, `STRIPPER2`

## Native vocabulary

Most-called natives inside the code unique to this script:

`GET_RANDOM_FLOAT_IN_RANGE` (19), `IS_STRING_NULL_OR_EMPTY` (13), `PLAYER_PED_ID` (10), `SET_PED_RESET_FLAG` (9), `ARE_STRINGS_EQUAL` (8), `IS_SYNCHRONIZED_SCENE_RUNNING` (7), `TASK_SYNCHRONIZED_SCENE` (7), `PLAY_SYNCHRONIZED_ENTITY_ANIM` (7), `DOES_ENTITY_EXIST` (6), `GET_ENTITY_COORDS` (5), `REQUEST_MODEL` (4), `IS_PED_INJURED` (4), `GET_GAME_TIMER` (4), `WAIT` (3), `GET_SYNCHRONIZED_SCENE_PHASE` (3), `GET_RANDOM_INT_IN_RANGE` (3), `IS_ENTITY_PLAYING_ANIM` (3), `CREATE_SYNCHRONIZED_SCENE` (3), `SET_SYNCHRONIZED_SCENE_LOOPED` (3), `SET_PED_CAN_RAGDOLL_FROM_PLAYER_IMPACT` (3), `SET_ENTITY_CAN_BE_DAMAGED` (3), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (3), `HAS_MODEL_LOADED` (2), `REQUEST_ANIM_DICT` (2), `SET_PED_COMBAT_ATTRIBUTES` (2), `VDIST` (2), `FIND_ANIM_EVENT_PHASE` (2), `CLEAR_PED_TASKS` (2), `STOP_SYNCHRONIZED_ENTITY_ANIM` (2), `TASK_FOLLOW_NAV_MESH_TO_COORD` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x2 · `0.1f` x1 · `0.75f` x1 · `0.99f` x1

## Other strings

Literals whose consuming native was not classified:

`WalkInterruptible`, `EXIT_Ped`, `EXIT_STRIPPER_01`, `EXIT_STRIPPER_02`, `001443_01_TRVS_28_IDLE_STRIPPER`, `001443_01_TRVS_28_IDLE_MAN`, `trev_scares_tramp_exit_tramp`, `LOOP_Ped`, `MotionState_Run`, `LOOP_STRIPPER_01`, `LOOP_STRIPPER_02`, `TRVS_IG_35`, `001443_01_TRVS_28_EXIT_STRIPPER`, `001443_01_TRVS_28_EXIT_MAN`, `trev_annoys_sunbathers_loop_girl`, `trev_annoys_sunbathers_exit_girl`, `trev_annoys_sunbathers_loop_guy`, `trev_annoys_sunbathers_exit_guy`, `001218_03_TRVS_23_RUDE_AT_CAFE_IDLE_FEMALE`, `001218_03_TRVS_23_RUDE_AT_CAFE_EXIT_FEMALE`, `trev_scares_tramp_idle_tramp`, `EXIT_LOOP_Ped`, `DEATH_Ped`, `DEATH_LOOP_Ped`, `LOOP_Rope`, `EXIT_Rope`, `EXIT_LOOP_Rope`, `DEATH_Rope`, `DEATH_LOOP_Rope`, `LOOP_Sock`

---

Source: `decompiled_scripts/player_scene_t_insult.c`
