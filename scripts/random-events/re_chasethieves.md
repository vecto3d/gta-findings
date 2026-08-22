# re_chasethieves.c

Random events script. 5 anim dicts; 7 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 40,395 |
| Functions | 434 (52 unique, 382 shared) |
| Unique lines | 2,162 (5.4% of file) |

## Assets

**Animation dictionaries** (5) - `RANDOM@CHASETHIEVES1`, `RANDOM@CHASETHIEVES2`, `RANDOM@CHASETHIEVES3`, `RANDOM@CHASETHIEVESGEN`, `RANDOM@BICYCLE_THIEF@ASK_HELP`

**Animations** (1) - `pickup_low`

**Models and props** (7) - `prop_ld_wallet_01`, `g_m_y_lost_02`, `s_m_y_busboy_01`, `hexer`, `prop_rub_binbag_03b`, `prop_rub_binbag_05`, `prop_ld_wallet_pickup`

**Sounds** (3) - `RE_CHASE_THIEVES_SCENE`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Speech contexts** (2) - `S_M_Y_BusBoy_01_WHITE_MINI_01`, `G_M_Y_Lost_02_WHITE_FULL_01`

**Text labels** (6) - `RECHAAU`, `REAR1AU`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `NULL`

**Scenarios** (1) - `WORLD_HUMAN_STAND_MOBILE`

**Relationship groups** (1) - `re_chasethieves badGuys`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (113), `IS_ENTITY_AT_ENTITY` (22), `GET_GAME_TIMER` (22), `GET_ENTITY_COORDS` (19), `IS_PED_INJURED` (16), `IS_PED_IN_ANY_VEHICLE` (14), `GIVE_WEAPON_TO_PED` (14), `IS_VEHICLE_DRIVEABLE` (11), `OPEN_SEQUENCE_TASK` (10), `CLOSE_SEQUENCE_TASK` (10), `TASK_PERFORM_SEQUENCE` (10), `CLEAR_SEQUENCE_TASK` (10), `CREATE_PED_INSIDE_VEHICLE` (10), `PLAYER_ID` (9), `IS_ENTITY_AT_COORD` (9), `GET_PICKUP_COORDS` (8), `IS_ENTITY_PLAYING_ANIM` (8), `GET_SCRIPT_TASK_STATUS` (8), `IS_PED_RUNNING_MOBILE_PHONE_TASK` (7), `SET_PED_COMBAT_ATTRIBUTES` (7), `SET_PED_CONFIG_FLAG` (7), `SET_BIT` (7), `TASK_DRIVE_BY` (7), `SET_MODEL_AS_NO_LONGER_NEEDED` (7), `GET_DISTANCE_BETWEEN_COORDS` (7), `GET_VEHICLE_PED_IS_IN` (6), `TASK_SMART_FLEE_PED` (6), `TASK_LOOK_AT_ENTITY` (6), `REQUEST_ANIM_DICT` (6), `TASK_PLAY_ANIM` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`28.27f` x3 · `0.25f` x2 · `1.5f` x2 · `0.9f` x2 · `1.4f` x2 · `0.5f` x1 · `1.2f` x1 · `335.98f` x1 · `-839.47f` x1 · `28.31f` x1 · `317.94f` x1 · `-824.33f` x1 · `336.86f` x1 · `-840.08f` x1 · `315.63f` x1 · `-826.01f` x1 · `0.96f` x1 · `0.75f` x1 · `1608.8f` x1 · `4824.81f` x1 · `1730.9f` x1 · `4856.1f` x1 · `51.1f` x1 · `1973.98f` x1

## Other strings

Literals whose consuming native was not classified:

`gburrito`, `RECHA_TK`, `RECHA_TK_1`, `player`, `GENERIC_FUCK_YOU`, `hexer`, `RECHA_THX_1`, `STRUGGLE_Loop_A_Shopkeeper`, `STRUGGLE_Loop_A_Thief`, `Return_Wallet_Positive_A_Player`, `Return_Wallet_Positive_A_Male`, `Return_Wallet_Positive_A_Cam`, `RECHA_WT`, `NEED_SOME_HELP`, `RECHA_SRDP`, `RECHA_SRDN`, `rc_wallets_recovered`, `ingot`, `FLEE_BACKWARD_Shopkeeper`, `FLEE_BACKWARD_Thief`, `MY_DADS_GOING_TO_KILL_ME`, `RECHA_OUT`, `RECHA_GET`, `GENERIC_CURSE_MED`, `RECHA_PCA`, `RECHA_PCB`, `RECHA_PCC`, `RECHA_PCD`, `RECHA_SRP`, `RECHA_GO`

---

Source: `decompiled_scripts/re_chasethieves.c`
