# fanatic1.c

SP strangers and freaks script. 10 anim dicts; 16 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 44,695 |
| Functions | 481 (90 unique, 391 shared) |
| Unique lines | 5,026 (11.2% of file) |

## Assets

**Animation dictionaries** (10) - `rcmfanatic1`, `rcmfanatic1out_of_breath`, `mini@cpr@char_a@cpr_def`, `mini@cpr@char_b@cpr_def`, `mini@cpr@char_a@cpr_str`, `mini@cpr@char_b@cpr_str`, `move_f@runner`, `rcmfanatic1celebrate`, `rcmfanatic1yell`, `FEMALE_FAST_RUNNER`

**Animations** (28) - `rcmfanatic1`, `base`, `move_f@runner`, `idle`, `rcmfanatic1out_of_breath`, `rcmfanatic1yell`, `idle_b`, `yell_d`, `cpr_intro`, `idle_a`, `jogging_on_spot`, `mini@cpr@char_b@cpr_def`, `cpr_pumpchest`, `KNEEL_EXIT`, `ef_1_rcm_mary_ann_streching_base`, `ef_1_rcm_mary_ann_leadin`, `rcmfanatic1celebrate`, `celebrate`, `jogging_up`, `p_zero_tired_exit`, `p_zero_tired_enter`, `p_zero_tired_01`, `p_zero_tired_02`, `yell_c`, `mini@cpr@char_a@cpr_def`, `mini@cpr@char_a@cpr_str`, `mini@cpr@char_b@cpr_str`, `idle_C`

**Models and props** (16) - `a_f_y_beach_01`, `g_m_y_salvagoon_01`, `ig_maryann`, `s_m_y_baywatch_01`, `a_c_rottweiler`, `a_m_y_beach_01`, `a_m_m_beach_01`, `blazer2`, `cs_maryann`, `banshee`, `p_zero_tired_01`, `a_f_y_fitness_01`, `regina`, `p_zero_tired_enter`, `p_zero_tired_02`, `a_m_m_trampbeac_01`

**Sounds** (3) - `FANATIC_MIX_SCENE`, `CHECKPOINT_NORMAL`, `HUD_MINI_GAME_SOUNDSET`

**Text labels** (5) - `FAN1AU`, `MARYANN`, `MICHAEL`, `NULL`, `FATIC1`

**Waypoint recordings** (2) - `Fanatic1RollingStart`, `Fanatic1Quad`

**Relationship groups** (1) - `FRIENDLIES`

**Hashed names** (1) - `UpperbodyFeathered_NoLefttArm_filter`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (167), `GET_GAME_TIMER` (48), `TASK_LOOK_AT_ENTITY` (41), `OPEN_SEQUENCE_TASK` (38), `CLOSE_SEQUENCE_TASK` (38), `TASK_PERFORM_SEQUENCE` (38), `CLEAR_SEQUENCE_TASK` (37), `TASK_PLAY_ANIM` (36), `SET_MODEL_AS_NO_LONGER_NEEDED` (36), `CLEAR_PED_TASKS` (34), `GET_ENTITY_COORDS` (33), `SET_ENTITY_COORDS` (19), `SET_ENTITY_HEADING` (19), `TASK_FOLLOW_NAV_MESH_TO_COORD` (18), `REQUEST_MODEL` (18), `WAIT` (17), `HAS_MODEL_LOADED` (17), `TASK_TURN_PED_TO_FACE_ENTITY` (17), `TRIGGER_MUSIC_EVENT` (15), `TASK_SMART_FLEE_PED` (13), `IS_PED_RAGDOLL` (13), `SET_PED_COMBAT_ATTRIBUTES` (13), `REQUEST_ANIM_DICT` (12), `HAS_ANIM_DICT_LOADED` (12), `DOES_ENTITY_EXIST` (12), `GET_HUD_COLOUR` (11), `PLAYER_ID` (11), `TASK_CLEAR_LOOK_AT` (11), `CREATE_PED` (10), `GET_DISTANCE_BETWEEN_COORDS` (10)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x11 · `0.125f` x8 · `0.5f` x7 · `0.7f` x6 · `10.48f` x5 · `10.56f` x4 · `-1875.16f` x4 · `-630.82f` x4 · `-1867.9f` x4 · `-625.78f` x4 · `10.25f` x4 · `-143.87f` x4 · `1.2f` x4 · `3.2f` x4 · `1.6f` x4 · `-2014.96f` x3 · `-455.47f` x3 · `-2018.17f` x3 · `-1954.1f` x3 · `-450.9f` x3 · `16.77f` x3 · `10.09f` x3 · `-1865.76f` x3 · `-617.48f` x3

## Other strings

Literals whose consuming native was not classified:

`RC6A_FAIL`, `FAN1_DONE`, `MotionState_Run`, `banshee`, `Mary_Ann`, `blazer2`, `RC6A_START`, `FAN1_PUSH`, `player`, `FEMALE_FAST_RUNNER`, `regina`, `rcmfanatic1out_of_breath`, `ef_1_rcm`, `Trying to set Mary Ann component variation`, `Fanatic1MaryAnn`, `FAN1_AGGRO`, `Loading ANIMS`, `FAN1_DONE_2`, `FAN1_DONE_3`, `FAN1_DONE_1`, `FAN1_DONE_4`, `FAN1_DONE_5`, `FAN1_RD3`, `Doing Mary Ann's anim...`, `FANATIC_MIX_MARY_ANNE`, `*** startRunConversation interrupted!`, `*** startRunConversation will restart on line: `, `*** Waiting for prior conversation to end before can play cheated line!`, `Michael`, `Starting music`

---

Source: `decompiled_scripts/fanatic1.c`
