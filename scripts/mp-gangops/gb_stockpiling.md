# gb_stockpiling.c

MP gang ops script. 1 models.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 478,428 |
| Functions | 8,682 (120 unique, 8,562 shared) |
| Unique lines | 18,337 (3.8% of file) |

## Assets

**Models and props** (1) - `imp_prop_impexp_cargo_01`

**Sounds** (5) - `Crate_Pickup_Player`, `Crate_Destroy_Player`, `Explosion_Countdown`, `GTAO_FM_Events_Soundset`, `Time`

**Text labels** (2) - `OFF`, `NULL`

**Decorators** (2) - `MPBitset`, `Not_Allow_As_Saved_Veh`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (87), `GET_NETWORK_TIME` (31), `PLAYER_PED_ID` (20), `VMAG` (19), `SET_BIT` (13), `GET_RANDOM_FLOAT_IN_RANGE` (12), `GET_TIME_DIFFERENCE` (11), `GET_ID_OF_THIS_THREAD` (10), `GET_ENTITY_COORDS` (6), `VDIST` (6), `IS_PLAYER_DEAD` (6), `PARTICIPANT_ID_TO_INT` (5), `PARTICIPANT_ID` (5), `NETWORK_CANCEL_RESPAWN_SEARCH` (5), `SPAWNPOINTS_CANCEL_SEARCH` (5), `SET_ENTITY_INVINCIBLE` (4), `SET_ENTITY_CAN_BE_DAMAGED` (4), `DOES_BLIP_EXIST` (4), `REMOVE_BLIP` (4), `GET_RANDOM_INT_IN_RANGE` (4), `DOES_ENTITY_EXIST` (4), `SET_AUDIO_FLAG` (4), `TRIGGER_MUSIC_EVENT` (4), `CLEAR_HELP` (4), `GET_PED_IN_VEHICLE_SEAT` (4), `SPAWNPOINTS_START_SEARCH_IN_ANGLED_AREA` (4), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (3), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (3), `GET_ENTITY_MODEL` (3), `SET_BLIP_SPRITE` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x6 · `3.5f` x1 · `1.5f` x1

## Other strings

Literals whose consuming native was not classified:

`GB_WINNER`, `GB_WORK_OVER`, `IE_STK_END_S5`, `DisableFlightMusic`, `IE_STK_END_S6`, `GB_WORK_START`, `IE_STK_HUD_02`, `IE_STK_HUD_01`, `GB_WORK_END`, `IE_STK_OBJ_01`, `tailgater`, `IE_STK_OBJ_03`, `IE_STK_OBJ_02`, `IE_STK_INT_T`, `IE_STK_END_S3`, `IE_STK_END_S4`, `IE_STK_END_S4b`, `IE_RAM_HUD_02`, `blazer5`, `IE_STK_HUD_03`, `DLC_IE_Vip_Stockpile_Sounds`, `IE_START_MUSIC`, `IE_FORTIFIED_FAIL`, `IE_FORTIFIED_STOP`, `IE_STK_INT_S1`, `IE_STK_INT_S2`, `IE_STK_END_S1`, `IE_STK_END_S2`, `IE_STK_END_S2b`, `HTV_DESTR_R`

---

Source: `decompiled_scripts/gb_stockpiling.c`
