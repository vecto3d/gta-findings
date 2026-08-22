# ob_vend1.c

Object brains script. 5 developer state labels recovered; 1 anim dicts; 14 models.

| | |
|---|---|
| Category | Object brains |
| Total lines | 80,150 |
| Functions | 428 (21 unique, 407 shared) |
| Unique lines | 1,148 (1.4% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`runVendingMachine` · `playerOutOfRange` · `waitForPlayer` · `grabPlayer` · `resetVend`

## Assets

**Animation dictionaries** (1) - `MINI@SPRUNK@FIRST_PERSON`

**Animations** (3) - `PLYR_BUY_DRINK_PT1`, `PLYR_BUY_DRINK_PT3`, `PLYR_BUY_DRINK_PT2`

**Models and props** (14) - `mt_vend_soda_t0_v0`, `prop_bin_06a`, `v_ret_gc_chair02`, `prop_ld_can_01b`, `prop_vend_soda_01`, `prop_ecola_can`, `prop_vend_soda_02`, `prop_vend_coffe_01`, `prop_vend_condom_01`, `prop_vend_fags_01`, `prop_vend_snak_01`, `prop_vend_water_01`, `sf_prop_sf_vend_drink_01a`, `sf_prop_sf_can_01a`

**Audio banks** (1) - `VENDING_MACHINE`

**Text labels** (4) - `NULL`, `VENDHLP`, `VENDEMP`, `VENDCSH`

**Hashed names** (2) - `V_7_RecAreaRm`, `V_7_GunSHopRm`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (76), `PLAYER_ID` (23), `DISABLE_CONTROL_ACTION` (13), `IS_ENTITY_PLAYING_ANIM` (10), `NETWORK_IS_GAME_IN_PROGRESS` (8), `DOES_ENTITY_EXIST` (7), `GET_ENTITY_ANIM_CURRENT_TIME` (7), `SET_PLAYER_CONTROL` (5), `DRAW_DEBUG_TEXT_2D` (5), `IS_ENTITY_DEAD` (4), `CLEAR_BIT` (4), `SET_CURRENT_PED_WEAPON` (4), `IS_ENTITY_AT_COORD` (4), `NETWORK_GET_VC_WALLET_BALANCE` (3), `USE_FAKE_MP_CASH` (3), `SET_ENTITY_HEALTH` (3), `IS_PED_INJURED` (3), `SET_PED_USING_ACTION_MODE` (3), `SET_PED_RESET_FLAG` (3), `GET_SCRIPT_TASK_STATUS` (3), `TASK_PLAY_ANIM` (3), `SET_EVERYONE_IGNORE_PLAYER` (3), `ARE_STRINGS_EQUAL` (3), `NETWORK_GET_VC_BANK_BALANCE` (3), `HIDE_HUD_COMPONENT_THIS_FRAME` (2), `WAIT` (2), `IS_ENTITY_A_MISSION_ENTITY` (2), `CLEAR_ENTITY_LAST_DAMAGE_ENTITY` (2), `CLEAR_PED_TASKS` (2), `IS_WEAPON_VALID` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x8 · `0.05f` x5 · `0.2f` x4 · `3.2f` x3 · `0.02f` x1 · `0.9f` x1 · `0.52f` x1 · `-1.5f` x1 · `0.98f` x1

## Other strings

Literals whose consuming native was not classified:

`purchase`

---

Source: `decompiled_scripts/ob_vend1.c`
