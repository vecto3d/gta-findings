# re_atmrobbery.c

Random events script. 11 anim dicts; 18 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 12,522 |
| Functions | 311 (29 unique, 282 shared) |
| Unique lines | 3,444 (27.5% of file) |

## Assets

**Animation dictionaries** (11) - `random@atmrobberygen@male`, `random@atmrobberygen@female`, `random@car_thief@waiting_ig_4`, `RANDOM@ATMROBBERYGEN`, `move_m@hurry@b`, `move_f@hurry@a`, `RANDOM@ATMROBBERY1`, `RANDOM@ATMROBBERY2`, `RANDOM@BICYCLE_THIEF@IDLE_A`, `RANDOM@ATMROBBERY3`, `RANDOM@ATMROBBERY4`

**Animations** (5) - `pickup_low`, `idle_a`, `b_atm_mugging`, `random@atmrobberygen@male`, `random@atmrobberygen@female`

**Models and props** (18) - `prop_ld_wallet_pickup`, `prop_ld_purse_01`, `prop_ld_wallet_01`, `a_f_m_tourist_01`, `prop_ld_wallet_01_s`, `g_m_y_armgoon_02`, `G_M_Y_ArmGoon_02_White_Armenian_MINI_01`, `A_F_M_BEVHILLS_02_WHITE_FULL_02`, `g_m_y_famfor_01`, `G_M_Y_FamFor_01_BLACK_MINI_01`, `a_m_y_hipster_02`, `A_M_Y_Hipster_02_White_Full_01`, `A_F_Y_Tourist_01_White_Mini_01`, `g_m_y_salvagoon_02`, `G_M_Y_SalvaGoon_02_SALVADORIAN_MINI_03`, `A_F_M_BevHills_02_WHITE_FULL_01`, `g_m_y_azteca_01`, `G_M_Y_Latino01_Latino_MINI_01`

**Text labels** (8) - `NULL`, `REAR1AU`, `REAR2AU`, `REAR5AU`, `REAR3AU`, `MICHAEL`, `FRANKLIN`, `TREVOR`

**Stats** (2) - `rc_wallets_recovered`, `rc_wallets_returned`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (181), `GET_DISTANCE_BETWEEN_COORDS` (50), `GET_ENTITY_COORDS` (45), `IS_PED_INJURED` (36), `VDIST` (34), `IS_ENTITY_IN_ANGLED_AREA` (33), `IS_ENTITY_AT_ENTITY` (25), `DOES_ENTITY_EXIST` (24), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (24), `TASK_PLAY_ANIM` (23), `CLEAR_SEQUENCE_TASK` (21), `PLAYER_ID` (20), `OPEN_SEQUENCE_TASK` (18), `CLOSE_SEQUENCE_TASK` (18), `TASK_PERFORM_SEQUENCE` (18), `WAIT` (15), `DOES_BLIP_EXIST` (14), `TASK_FOLLOW_NAV_MESH_TO_COORD` (14), `TASK_SMART_FLEE_PED` (13), `SET_PED_COMBAT_ATTRIBUTES` (12), `TASK_WANDER_STANDARD` (12), `SETTIMERA` (10), `GET_ANIM_INITIAL_OFFSET_POSITION` (10), `SET_ENTITY_HEADING` (10), `GET_SCRIPT_TASK_STATUS` (10), `CLEAR_PED_TASKS` (9), `IS_PED_IN_ANY_VEHICLE` (9), `IS_VEHICLE_DRIVEABLE` (9), `GET_ENTITY_HEADING` (9), `GET_GAME_TIMER` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x14 · `0.5f` x9 · `3.5f` x6 · `-203.72f` x5 · `-861.8f` x5 · `29.27f` x5 · `28.44f` x5 · `-712.9f` x4 · `-819.32f` x4 · `22.73f` x4 · `288.46f` x4 · `-1256.71f` x4 · `9.5f` x4 · `-387.12f` x4 · `6045.79f` x4 · `30.5f` x4 · `-3044.11f` x4 · `594.34f` x4 · `6.73f` x4 · `7.5f` x4 · `-203.758f` x3 · `-861.738f` x3 · `29.2684f` x3 · `14.47f` x3

## Other strings

Literals whose consuming native was not classified:

`waiting`, `idle_a`, `MotionState_Walk`, `Return_Wallet_Positive_A_Player`, `Return_Wallet_Positive_A_Cam`, `ruiner`, `b_atm_mugging`, `IF NOT IS_WORLD_POINT_WITHIN_BRAIN_ACTIVATION_RANGE()\n`, `GENERIC_CURSE_MED`, `GENERIC_FRIGHTENED_HIGH`, `GENERIC_HI`, `sanchez`, `REAR1_ATTR`, `REAR1_HELP`, `REAR1_PROMPT`, `REAR1_CHASE`, `REAR1_FLEE`, `REAR1_THX`, `REAR1_DAMN`, `REAR1_REM`, `REAR1_FKM`, `REAR1_WM`, `REAR1_GYM`, `REAR1_REF`, `REAR1_FKF`, `REAR1_WF`, `REAR1_GYF`, `REAR1_RET`, `REAR1_FKT`

---

Source: `decompiled_scripts/re_atmrobbery.c`
