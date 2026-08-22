# atm_trigger.c

Ambient world script. 8 developer state labels recovered; 11 anim dicts; 3 models; 29 scaleforms.

| | |
|---|---|
| Category | Ambient world |
| Total lines | 4,967 |
| Functions | 112 (30 unique, 82 shared) |
| Unique lines | 3,078 (62.0% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`walk` · `enter` · `base` · `idle_a` · `idle_b` · `idle_c` · `idle_d` · `idle_XXX`

## Assets

**Animation dictionaries** (11) - `anim@amb@prop_human_atm@interior@male@idle_a`, `mini@atmexit`, `anim@amb@prop_human_atm@interior@female@enter`, `anim@amb@prop_human_atm@interior@female@base`, `anim@amb@prop_human_atm@interior@female@idle_a`, `anim@amb@prop_human_atm@interior@male@enter`, `mini@atmenter`, `anim@amb@prop_human_atm@interior@male@base`, `mini@atmbase`, `anim@amb@prop_human_atm@interior@male@exit`, `anim@amb@prop_human_atm@interior@female@exit`

**Animations** (4) - `idle_a`, `idle_b`, `idle_c`, `idle_d`

**Models and props** (3) - `W_BA_LGOF`, `W_BA_ATL`, `W_BA_BAL`

**Audio banks** (1) - `ATM`

**Sounds** (3) - `ATM_PLAYER_SCENE`, `PIN_BUTTON`, `ATM_SOUNDS`

**Scaleform movies** (29) - `SET_DATA_SLOT`, `DISPLAY_MESSAGE`, `ESDOLLA`, `SET_INPUT_EVENT`, `SHOW_CURSOR`, `SET_DATA_SLOT_EMPTY`, `SET_ANALOG_STICK_INPUT`, `DISPLAY_CASH_OPTIONS`, `ATM`, `INSTRUCTIONAL_BUTTONS`, `UPDATE_TEXT`, `SET_INPUT_SELECT`, `GET_CURRENT_SELECTION`, `SET_MOUSE_INPUT`, `DISPLAY_MENU`, `MPATM_LOG`, `DISPLAY_TRANSACTIONS`, `MPATM_XDOL`, `MPATM_XDOL2`, `MPATM_CONF`, `MPATC_CONFW`, `DISPLAY_BALANCE`, `MPATM_ACBA`, `MPATM_PLCHLDR_CRF`, `MPATM_PLCHLDR_CST`, `CLEAR_ALL`, `SET_CLEAR_SPACE`, `TOGGLE_MOUSE_BUTTONS`, `DRAW_INSTRUCTIONAL_BUTTONS`

**Text labels** (3) - `NULL`, `SHOP_JUGG_NONE`, `GB_COUT_ATM`

## Native vocabulary

Most-called natives inside the code unique to this script:

`BEGIN_SCALEFORM_MOVIE_METHOD` (95), `END_SCALEFORM_MOVIE_METHOD` (94), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (72), `PLAYER_PED_ID` (62), `ENABLE_CONTROL_ACTION` (21), `BEGIN_TEXT_COMMAND_SCALEFORM_STRING` (20), `END_TEXT_COMMAND_SCALEFORM_STRING` (20), `ADD_TEXT_COMPONENT_FORMATTED_INTEGER` (16), `IS_SYNCHRONIZED_SCENE_RUNNING` (15), `IS_CONTROL_JUST_PRESSED` (14), `TERMINATE_THIS_THREAD` (12), `GET_ENTITY_COORDS` (11), `WAIT` (11), `NETWORK_GET_VC_BANK_BALANCE` (11), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (10), `NETWORK_START_SYNCHRONISED_SCENE` (10), `GET_GAME_TIMER` (10), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_FLOAT` (9), `NETWORK_IS_GAME_IN_PROGRESS` (8), `DISABLE_CONTROL_ACTION` (8), `NETWORK_GET_VC_WALLET_BALANCE` (8), `DRAW_DEBUG_TEXT` (8), `DOES_ANIM_DICT_EXIST` (8), `NETWORK_CREATE_SYNCHRONISED_SCENE` (7), `GET_ENTITY_ROTATION` (7), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_BOOL` (7), `IS_ENTITY_DEAD` (6), `IS_PC_VERSION` (6), `GET_CONTROL_NORMAL` (6), `DOES_ENTITY_EXIST` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.01f` x3 · `1.5f` x3 · `0.99f` x2 · `0.25f` x1 · `130.1504f` x1 · `-1291.626f` x1 · `28.2714f` x1 · `0.33f` x1

## Other strings

Literals whose consuming native was not classified:

`MPATM_BACK`, `ATM_1TM_TUT`, `MO_YES`, `MO_NO`, `base`, `idle_a`, `idle_b`, `idle_c`, `idle_d`, `mpply_last_mp_char`, `MPATM_PEND`, `MPATM_NODO`, `MPATM_NODO2`, `money_spent_betting`, `MONEY_SPENT_PASSIVEMODE`, `MONEY_EARN_ROCKSTAR_AWARD`, `MONEY_EARN_REFUND`, `ACCNA_MIKE`, `mp_f_freemode_01`, `FINH_ATMNEAR`, `exit`, `MPATM_SER`, `MPATM_DIDM`, `MPATM_WITM`, `MPATM_LOG`, `MPATM_DITMT`, `MPATM_WITMT`, `MPATM_ERR`, `MPATM_TRANCOM`, `MPATM_PLCHLDR_WDR`

---

Source: `decompiled_scripts/atm_trigger.c`
