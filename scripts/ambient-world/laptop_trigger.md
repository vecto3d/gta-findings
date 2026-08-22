# laptop_trigger.c

Ambient world script. 7 developer state labels recovered; 1 anim dicts; 4 models.

| | |
|---|---|
| Category | Ambient world |
| Total lines | 6,441 |
| Functions | 307 (28 unique, 279 shared) |
| Unique lines | 1,125 (17.5% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`walk` · `enter` · `idle_a` · `idle_b` · `idle_c` · `idle_d` · `idle_XXX`

## Assets

**Animation dictionaries** (1) - `anim@amb@warehouse@laptop@`

**Animations** (7) - `MP_COMMON_MISS`, `HACK_INTRO`, `HACK_LOOP`, `idle_a`, `idle_b`, `idle_c`, `idle_d`

**Models and props** (4) - `prop_laptop_01a`, `ex_prop_monitor_01_ex`, `prop_laptop_lester`, `prop_laptop_lester2`

**Sounds** (2) - `Login`, `GTAO_Exec_SecuroServ_Warehouse_PC_Sounds`

**Text labels** (11) - `WHSECUROBLCK`, `WHPRIVSESLAP`, `WHBIKERBLCK`, `ARENAWHINPUT`, `WHSECUROINPUT`, `BIKERWHBLCKC`, `BIKERWHBLCKD`, `BIKERWHINPUT`, `BIKERWHBLCKA`, `BIKERWHBLCKB`, `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (60), `PLAYER_PED_ID` (55), `GET_ENTITY_COORDS` (16), `DOES_ENTITY_EXIST` (13), `IS_SYNCHRONIZED_SCENE_RUNNING` (10), `CLEAR_HELP` (9), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (8), `NETWORK_START_SYNCHRONISED_SCENE` (8), `GET_ENTITY_HEADING` (7), `DRAW_DEBUG_TEXT` (7), `WAIT` (6), `TERMINATE_THIS_THREAD` (6), `IS_ENTITY_PLAYING_ANIM` (6), `GET_ENTITY_ROTATION` (6), `NETWORK_IS_ACTIVITY_SESSION` (5), `DETACH_SYNCHRONIZED_SCENE` (5), `NETWORK_CREATE_SYNCHRONISED_SCENE` (5), `GET_ENTITY_MODEL` (4), `IS_ENTITY_DEAD` (4), `HAS_ANIM_DICT_LOADED` (4), `ARE_STRINGS_EQUAL` (4), `NETWORK_IS_PLAYER_IN_MP_CUTSCENE` (4), `IS_ENTITY_IN_AREA` (4), `INT_TO_PLAYERINDEX` (3), `REMOVE_ANIM_DICT` (3), `REQUEST_ANIM_DICT` (3), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (3), `GET_SYNCHRONIZED_SCENE_PHASE` (3), `IS_HELP_MESSAGE_BEING_DISPLAYED` (3), `IS_ENTITY_AT_COORD` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.6f` x3 · `1.5f` x2 · `0.0328f` x1 · `-0.8f` x1 · `0.3f` x1 · `0.05f` x1 · `0.25f` x1 · `0.1f` x1 · `0.93f` x1 · `0.96f` x1 · `0.99f` x1 · `-3200.515f` x1 · `-40.05f` x1 · `1176.79f` x1 · `-3189.532f` x1 · `-34.785f` x1 · `-1470.88f` x1 · `-528.8513f` x1 · `75.0839f` x1 · `-1472.63f` x1 · `-526.5934f` x1 · `73.3136f` x1 · `1008.467f` x1 · `-3167.947f` x1

## Other strings

Literals whose consuming native was not classified:

`idle_a`, `idle_b`, `idle_c`, `idle_d`, `SECINPUTTREGLAP`, `WHSECUROMAXVIP`, `PIM_EXECH0x1`, `tvscreen`, `MPLA_BILL`, `BROWSEINPUTTRIG`, `exit`, `mp_f_freemode_01`, `enter`, `idle_XXX`, `MP_OFF_LAP_1`

---

Source: `decompiled_scripts/laptop_trigger.c`
