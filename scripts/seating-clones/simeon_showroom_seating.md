# simeon_showroom_seating.c

Seating clones script. 4 anim dicts.

| | |
|---|---|
| Category | Seating clones |
| Total lines | 3,340 |
| Functions | 113 (19 unique, 94 shared) |
| Unique lines | 1,027 (30.7% of file) |

## Assets

**Animation dictionaries** (4) - `ANIM@AMB@CLUBHOUSE@SEATING`, `ANIM@AMB@OFFICE@SEATING`, `ANIM@AMB@FACILITY@BRIEFING_ROOM@SEATING`, `ANIM@AMB@YACHT@JACUZZI@SEATED`

**Text labels** (3) - `ENTER`, `BASE`, `EXIT`

**Hashed names** (3) - `BLOCK_INTERRUPT`, `BREAKOUT_FINISH`, `BREAK_OUT`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (18), `DISABLE_CONTROL_ACTION` (11), `GET_GAME_TIMER` (5), `PLAYER_ID` (4), `SET_CAM_VIEW_MODE_FOR_CONTEXT` (4), `HAS_ANIM_EVENT_FIRED` (4), `GET_HASH_KEY` (4), `GET_RANDOM_INT_IN_RANGE` (3), `GET_ENTITY_HEADING` (3), `SET_BIT` (3), `GET_CAM_VIEW_MODE_FOR_CONTEXT` (3), `IS_USING_KEYBOARD_AND_MOUSE` (3), `GET_ANIM_INITIAL_OFFSET_ROTATION` (2), `GET_SCRIPT_TASK_STATUS` (2), `NETWORK_CREATE_SYNCHRONISED_SCENE` (2), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (2), `NETWORK_START_SYNCHRONISED_SCENE` (2), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (2), `IS_SYNCHRONIZED_SCENE_RUNNING` (2), `GET_SYNCHRONIZED_SCENE_PHASE` (2), `NETWORK_STOP_SYNCHRONISED_SCENE` (2), `GET_CONTROL_NORMAL` (2), `DOES_ENTITY_EXIST` (1), `IS_SCREEN_FADED_OUT` (1), `NETWORK_IS_SCRIPT_ACTIVE` (1), `NETWORK_SET_THIS_SCRIPT_IS_NETWORK_SCRIPT` (1), `SET_THIS_SCRIPT_CAN_BE_PAUSED` (1), `IS_PED_IN_ANY_VEHICLE` (1), `IS_PED_IN_COMBAT` (1), `IS_PED_IN_MELEE_COMBAT` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.12f` x2 · `-1.5f` x1 · `0.7f` x1

## Other strings

Literals whose consuming native was not classified:

`@VAR_B@BASE@`, `IDLE_B`, `IDLE_A`, `IDLE_C`, `D_TO_B`, `B_TO_C`, `C_TO_A`, `E_TO_A`, `invalid_clip`, `@VAR_C@BASE@`, `@VAR_D@BASE@`, `C_TO_D`, `A_TO_B`, `D_TO_E`, `B_TO_E`, `D_TO_A`, `@VAR_A@BASE@`, `@VAR_E@BASE@`, `B_TO_A`, `A_TO_D`, `BASE_A`, `@FEMALE`, `@MALE`, `@VAR_A@`, `@VAR_B@`, `@VAR_C@`, `@VAR_D@`, `@VAR_E@`, `@VARIATION_01@`, `@VARIATION_02@`

---

Source: `decompiled_scripts/simeon_showroom_seating.c`
