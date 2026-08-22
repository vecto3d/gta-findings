# re_muggings.c

Random events script. 6 developer state labels recovered; 12 anim dicts; 15 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 12,698 |
| Functions | 308 (59 unique, 249 shared) |
| Unique lines | 3,969 (31.3% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`ABLE_TO_RETRIEVE_DROPPED_BAG` · `MUGGING_INTERACTION` · `INITIAL_MUGGING_SEQ` · `VIC_CRY_OUT` · `ASK_PLAYER_FOR_HELP` · `PLAYER_HAS_BAG`

## Assets

**Animation dictionaries** (12) - `RANDOM@MUGGING3`, `move_m@hurry@b`, `random@mugging2`, `move_f@hurry@a`, `RANDOM@BICYCLE_THIEF@RETURN_FRONT`, `RANDOM@MUGGING1`, `RANDOM@MUGGING4`, `RANDOM@ATM_ROBBERY@RETURN_WALLET_FEMALE`, `RANDOM@ATM_ROBBERY@RETURN_WALLET_MALE`, `AMB@PROP_HUMAN_SEAT_CHAIR@MALE@GENERIC@BASE`, `AMB@PROP_HUMAN_SEAT_CHAIR@MALE@GENERIC@EXIT`, `RANDOM@BICYCLE_THIEF@IDLE_A`

**Animations** (24) - `agitated_loop_c`, `RANDOM@BICYCLE_THIEF@IDLE_A`, `pickup_low`, `agitated_loop_a`, `agitated_loop_b`, `flee_forward_loop_shopkeeper`, `flee_forward_outro_shopkeeper`, `IDLE_A`, `IDLE_B`, `IDLE_C`, `handsup_standing_enter`, `handsup_standing_base`, `handsup_standing_exit`, `flee_backward_loop_shopkeeper`, `flee_backward_outro_shopkeeper`, `RETURNING_FRONT_A`, `IG_1_guy_stickup_loop`, `ortega_stand_loop_ort`, `AMB@PROP_HUMAN_SEAT_CHAIR@MALE@GENERIC@BASE`, `base`, `AMB@PROP_HUMAN_SEAT_CHAIR@MALE@GENERIC@EXIT`, `exit_forward`, `flee_backward_intro_shopkeeper`, `flee_forward_intro_shopkeeper`

**Models and props** (15) - `a_m_y_business_02`, `g_m_y_strpunk_01`, `prop_ld_wallet_pickup`, `G_M_Y_StreetPunk_01_BLACK_MINI_03`, `a_m_y_genstreet_01`, `A_M_Y_Business_02_WHITE_FULL_01`, `a_f_y_genhot_01`, `prop_ld_handbag`, `a_f_y_hipster_01`, `a_m_o_tramp_01`, `prop_ld_purse_01`, `G_M_Y_Korean_02_Korean_MINI_02`, `a_f_m_tourist_01`, `g_m_y_armgoon_02`, `G_M_Y_ArmGoon_02_White_Armenian_MINI_02`

**Text labels** (11) - `CIVMALE`, `CIVFEMALE`, `NULL`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `REMG1AU`, `REMG2AU`, `REMG3AU`, `MUGGEDHIPSTER`, `REMG4AU`

**Relationship groups** (1) - `theAssailant`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (167), `IS_PED_INJURED` (108), `TASK_PLAY_ANIM` (65), `DOES_ENTITY_EXIST` (39), `OPEN_SEQUENCE_TASK` (35), `CLOSE_SEQUENCE_TASK` (35), `TASK_PERFORM_SEQUENCE` (35), `CLEAR_SEQUENCE_TASK` (35), `SET_PED_KEEP_TASK` (31), `DOES_BLIP_EXIST` (30), `CLEAR_PED_TASKS` (28), `TASK_SMART_FLEE_PED` (28), `GET_ENTITY_COORDS` (27), `PLAYER_ID` (24), `IS_ENTITY_PLAYING_ANIM` (23), `REMOVE_BLIP` (22), `WAIT` (21), `IS_ENTITY_AT_ENTITY` (20), `IS_ENTITY_DEAD` (20), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (18), `TASK_LOOK_AT_ENTITY` (17), `VDIST` (17), `SET_PED_AS_NO_LONGER_NEEDED` (16), `GET_DISTANCE_BETWEEN_COORDS` (14), `DOES_PICKUP_EXIST` (11), `GET_SCRIPT_TASK_STATUS` (11), `DOES_PICKUP_OBJECT_EXIST` (11), `GET_GAME_TIMER` (10), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (10), `TASK_TURN_PED_TO_FACE_ENTITY` (10)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x10 · `0.02f` x8 · `1.5f` x6 · `0.25f` x6 · `0.5f` x5 · `5.3f` x4 · `1.2f` x3 · `0.922f` x2 · `28.5315f` x2 · `-1027.565f` x2 · `37.1197f` x2 · `0.75f` x2 · `123.75f` x2 · `-325.7037f` x2 · `-829.31f` x2 · `30.5812f` x2 · `-127.9025f` x1 · `-1574.084f` x1 · `36.4128f` x1 · `0.9f` x1 · `38.2412f` x1 · `-992.2134f` x1 · `28.4317f` x1 · `58.803f` x1

## Other strings

Literals whose consuming native was not classified:

`MotionState_Run`, `MuggerGang`, `REMG2_FKIT`, `FLEE_BACKWARD_Shopkeeper`, `FLEE_BACKWARD_Thief`, `FLEE_FORWARD_Shopkeeper`, `FLEE_FORWARD_Thief`, `Return_Wallet_Positive_A_Player`, `Return_Wallet_Positive_A_Cam`, `Return_Wallet_Positive_B_Player`, `Return_Wallet_Positive_B_Cam`, `Return_Wallet_Positive_C_Player`, `Return_Wallet_Positive_C_Cam`, `MotionState_Walk`, `FIRING_PATTERN_FULL_AUTO`, `REMG2_ARG`, `player`, `STRUGGLE_Loop_A_Thief`, `STRUGGLE_Loop_A_Shopkeeper`, `REMG1_VIC`, `REMG1_SHT`, `REMG1_ASK`, `REMG1_DRP`, `REMG1_OHY`, `REMG1_THK`, `REMG1_GIV`, `REMG1_MUGA`, `REMG1_WHO`, `REMG1_HOM`, `REMG1_WAM`

---

Source: `decompiled_scripts/re_muggings.c`
