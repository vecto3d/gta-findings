# casino_lucky_wheel.c

Minigames script. 2 anim dicts; 3 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 80,311 |
| Functions | 1,099 (219 unique, 880 shared) |
| Unique lines | 10,300 (12.8% of file) |

## Assets

**Animation dictionaries** (2) - `ANIM_CASINO_A@AMB@CASINO@GAMES@LUCKY7WHEEL@FEMALE`, `ANIM_CASINO_A@AMB@CASINO@GAMES@LUCKY7WHEEL@MALE`

**Models and props** (3) - `vw_prop_vw_jackpot_on`, `vw_prop_vw_luckylight_on`, `vw_prop_vw_luckywheel_02a`

**Sounds** (12) - `dlc_vw_casino_lucky_wheel_sounds`, `spinSpeed`, `dlc_vw_table_games_frontend_sounds`, `winSize`, `DLC_VW_CONTINUE`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `Win`, `Spin_Single_Ticks`, `Spin_Start`, `DLC_VW_RULES`, `SELECT`, `BACK`

**Texture dicts** (1) - `CasinoUI_Lucky_Wheel`

**Text labels** (14) - `INVALID`, `BRSCRWTEX`, `NULL`, `CAS_WHEEL_TR`, `MYSTREYCHIPS`, `MYSTREYCASH`, `HOUSECHIPS`, `PODIUMVEHICLE`, `TWOSTRINGS`, `200000`, `MYSTREYRP`, `CLOTHING`, `CASH`, `UNKNOWN`

**Hashed names** (8) - `VIP membership`, `paid membership`, `BLEND_OUT`, `EARLY_OUT`, `AM_MP_CASINO`, `LUCKYWHEEL`, `STANDARD`, `WIN`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (127), `PLAYER_PED_ID` (65), `ARE_STRINGS_EQUAL` (29), `CLEAR_BIT` (27), `SET_BIT` (26), `GET_HASH_KEY` (26), `IS_CONTROL_JUST_PRESSED` (16), `GET_ENTITY_MODEL` (16), `DOES_ENTITY_EXIST` (13), `CLEAR_HELP` (12), `IS_STRING_NULL_OR_EMPTY` (12), `GET_SCRIPT_TASK_STATUS` (11), `TO_FLOAT` (11), `HAS_SOUND_FINISHED` (10), `GET_RANDOM_MWC_INT_IN_RANGE` (10), `GET_NETWORK_TIME` (10), `RELEASE_SOUND_ID` (8), `GET_PED_AMMO_BY_TYPE` (8), `GET_MAX_AMMO` (8), `SET_PED_AMMO_BY_TYPE` (8), `IS_HELP_MESSAGE_BEING_DISPLAYED` (7), `IS_HELP_MESSAGE_ON_SCREEN` (7), `STOP_SOUND` (7), `FLOOR` (7), `GET_CLOUD_TIME_AS_INT` (6), `IS_DISABLED_CONTROL_JUST_PRESSED` (6), `IS_WARNING_MESSAGE_ACTIVE` (6), `ENABLE_CONTROL_ACTION` (6), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (5), `SET_INPUT_EXCLUSIVE` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1111.052f` x4 · `229.849f` x4 · `-50.641f` x4 · `1110.995f` x2 · `228.9034f` x2 · `-50.6408f` x2 · `1109.727f` x2 · `228.9352f` x2 · `-48.3908f` x2 · `1.5f` x2 · `1109.469f` x1 · `228.9432f` x1 · `-50.64041f` x1 · `1111.215f` x1 · `228.8777f` x1 · `-48.39041f` x1 · `1.82f` x1 · `1109.16f` x1 · `228.4484f` x1 · `-50.63083f` x1 · `1112.186f` x1 · `228.9841f` x1 · `-48.13083f` x1 · `2.75f` x1

## Other strings

Literals whose consuming native was not classified:

`LW_PLAY`, `LUCK_WHEEL_SPIN`, `LUCK_W_SPIN_PC`, `GIVE_RP_FOR_VEH`, `LUCKY_WHEEL_US`, `POD_TOO_MANY`, `squalo`, `mpply_lucky_wheel_usage`, `CASINO_LUCK_WD`, `CAS_MG_MEMB2`, `LUCKY_WHEEL_US1`, `LUCKY_WHEEL_US2`, `LUCKY_WHEEL_US3`, `CAS_LW_REGL`, `CAS_LW_RP`, `velum`, `marquis`, `mammatus`, `jetmax`, `stunt`, `cuban800`, `voltic2`, `seashark`, `tribike`, `tribike2`, `tribike3`, `scorcher`, `cruiser`, `bmx`, `dodo`

---

Source: `decompiled_scripts/casino_lucky_wheel.c`
