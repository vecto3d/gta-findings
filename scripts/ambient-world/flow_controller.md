# flow_controller.c

Ambient world script.

| | |
|---|---|
| Category | Ambient world |
| Total lines | 140,575 |
| Functions | 1,159 (237 unique, 922 shared) |
| Unique lines | 13,191 (9.4% of file) |

## Assets

**Text labels** (7) - `NONE`, `NULL`, `JH2A`, `JH2B`, `FH2A`, `FH2B`, `ORANGE`

**Vehicle mods** (5) - `faggio2`, `hexer`, `policeb`, `sanchez`, `vader`

**Stats** (38) - `sp0_crouched`, `sp0_kills_innocents`, `sp0_kills_cop`, `sp0_kills_swat`, `sp0_number_stolen_cars`, `sp0_number_stolen_bikes`, `sp0_number_stolen_quadbikes`, `sp0_large_accidents`, `sp0_weap_addon_unlock_0`, `sp1_weap_addon_unlock_0`, `sp2_weap_addon_unlock_0`, `sp0_weap_addon_unlock_1`, `sp1_weap_addon_unlock_1`, `sp2_weap_addon_unlock_1`, `sp0_weap_addon_unlock_2`, `sp1_weap_addon_unlock_2`, `sp2_weap_addon_unlock_2`, `sp0_weap_addon_unlock_3`, `sp1_weap_addon_unlock_3`, `sp2_weap_addon_unlock_3`, `sp0_weap_addon_unlock_4`, `sp1_weap_addon_unlock_4`, `sp2_weap_addon_unlock_4`, `sp0_weap_addon_unlock_5`, `sp1_weap_addon_unlock_5`, `sp2_weap_addon_unlock_5`, `sp0_weap_addon_unlock_6`, `sp1_weap_addon_unlock_6`, `sp2_weap_addon_unlock_6`, `sp0_weap_unlock_0`, `sp1_weap_unlock_0`, `sp2_weap_unlock_0`, `sp0_weap_unlock_1`, `sp1_weap_unlock_1`, `sp2_weap_unlock_1`, `sp0_weap_unlock_2`, `sp1_weap_unlock_2`, `sp2_weap_unlock_2`

**Scripts launched** (2) - `mission_stat_watcher`, `buddyDeathResponse`

**Hashed names** (1) - `ShopRobberies`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (83), `PLAYER_PED_ID` (46), `STAT_GET_INT` (39), `STAT_SET_INT` (36), `GET_GAME_TIMER` (30), `CLEAR_BIT` (22), `PLAYER_ID` (19), `ARE_STRINGS_EQUAL` (14), `IS_PED_INJURED` (12), `REQUEST_SCRIPT_WITH_NAME_HASH` (11), `GET_CLOCK_HOURS` (10), `SET_SRL_FORCE_PRESTREAM` (10), `SET_SCRIPT_WITH_NAME_HASH_AS_NO_LONGER_NEEDED` (9), `DOES_ENTITY_EXIST` (8), `IS_PLAYER_PLAYING` (7), `HAS_SCRIPT_WITH_NAME_HASH_LOADED` (6), `START_NEW_SCRIPT_WITH_NAME_HASH` (6), `TO_FLOAT` (6), `GET_CLOCK_MONTH` (5), `GET_CLOCK_DAY_OF_MONTH` (5), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (5), `IS_THREAD_ACTIVE` (5), `IS_PED_IN_ANY_VEHICLE` (5), `SET_VEHICLE_MODEL_IS_SUPPRESSED` (5), `GET_ENTITY_COORDS` (4), `IS_ENTITY_DEAD` (4), `SET_PED_CONFIG_FLAG` (4), `FACEBOOK_POST_COMPLETED_HEIST` (4), `GET_CLOCK_DAY_OF_WEEK` (3), `TASK_LEAVE_ANY_VEHICLE` (3)

## Other strings

Literals whose consuming native was not classified:

`cities_passed`, `player`, `TRIG_T`, `TRIG_FT`, `TRIG_F`, `TRIG_MT`, `TRIG_M`, `buddyDeathResponse`, `GLOBAL_KILL_MUSIC`, `benson`, `bobcatxl`, `bullet`, `dominator`, `minivan`, `peyote`, `radi`, `sadler`, `sadler2`, `sandking`, `sandking2`, `speedo`, `speedo2`, `stanier`, `boxville`, `camper`, `pony`, `pony2`, `stockade`

---

Source: `decompiled_scripts/flow_controller.c`
