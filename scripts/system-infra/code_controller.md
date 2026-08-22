# code_controller.c

System and infrastructure script. 2 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 61,681 |
| Functions | 599 (213 unique, 386 shared) |
| Unique lines | 4,888 (7.9% of file) |

## Assets

**Models and props** (2) - `v_ilev_frnkwarddr1`, `v_ilev_frnkwarddr2`

**Text labels** (2) - `NULL`, `FEED_CREW_U`

**Scenarios** (1) - `LOST_BIKERS`

**Stats** (50) - `sp1_weap_addon_unlock_0`, `sp0_weap_addon_unlock_0`, `sp0_weap_addon_unlock_5`, `sp0_weap_addon_unlock_3`, `sp2_weap_addon_unlock_3`, `sp1_weap_addon_unlock_2`, `sp2_weap_addon_unlock_2`, `sp1_weap_addon_unlock_5`, `sp2_weap_addon_unlock_5`, `sp0_weap_addon_unlock_6`, `sp1_weap_addon_unlock_4`, `sp2_weap_addon_unlock_0`, `sp0_hits_peds_vehicles`, `sp0_weap_addon_unlock_1`, `sp1_weap_addon_unlock_1`, `sp2_weap_addon_unlock_1`, `sp0_weap_addon_unlock_2`, `sp1_weap_addon_unlock_3`, `sp2_weap_addon_unlock_6`, `sp2_weap_addon_unlock_4`, `sp1_weap_addon_unlock_6`, `sp0_weap_addon_unlock_4`, `sp0_dist_running`, `sp0_unarmed_hits`, `sp0_number_near_miss`, `sp0_dist_walk_st`, `sp0_kills_stealth`, `sp0_hits_mission`, `sp1_dist_running`, `sp1_unarmed_hits`, `sp1_number_near_miss`, `sp1_dist_walk_st`, `sp1_kills_stealth`, `sp1_hits_mission`, `sp2_dist_running`, `sp2_unarmed_hits`, `sp2_number_near_miss`, `sp2_dist_walk_st`, `sp2_kills_stealth`, `sp2_hits_mission`, `sp2_hits_peds_vehicles`, `sp0_weap_unlock_0`, `sp1_weap_unlock_0`, `sp2_weap_unlock_0`, `sp0_weap_unlock_1`, `sp1_weap_unlock_1`, `sp2_weap_unlock_1`, `sp0_weap_unlock_2`, `sp2_weap_unlock_2`, `sp1_weap_unlock_2`

**Scripts launched** (1) - `chop`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (138), `STAT_GET_INT` (36), `PLAYER_PED_ID` (32), `STAT_SET_INT` (31), `CLEAR_BIT` (14), `GET_GAME_TIMER` (12), `PLAYER_ID` (12), `TO_FLOAT` (7), `STAT_GET_FLOAT` (6), `IS_PED_INJURED` (5), `NETWORK_IS_GAME_IN_PROGRESS` (5), `VDIST2` (5), `FREEZE_ENTITY_POSITION` (4), `SET_BLIP_FLASHES` (4), `SET_BLIP_FLASH_TIMER` (4), `ROUND` (4), `FLOOR` (4), `GET_ENTITY_COORDS` (3), `IS_ENTITY_ATTACHED` (3), `DOES_BLIP_EXIST` (3), `IS_PLAYER_PLAYING` (3), `TERMINATE_THIS_THREAD` (2), `REMOVE_MODEL_HIDE` (2), `CLEAR_AREA` (2), `IS_PED_IN_ANY_VEHICLE` (2), `GET_HASH_KEY` (2), `GET_STANDARD_BLIP_ENUM_ID` (1), `GET_WAYPOINT_BLIP_ENUM_ID` (1), `HAS_FORCE_CLEANUP_OCCURRED` (1), `SET_SCENARIO_GROUP_ENABLED` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`31.305f` x2 · `0.8f` x2 · `-18.3539f` x1 · `-1438.784f` x1 · `-18.3594f` x1 · `-1438.133f` x1 · `689.6588f` x1 · `-962.4214f` x1 · `22.4975f` x1

## Other strings

Literals whose consuming native was not classified:

`player_zero`, `player_one`, `player_two`, `AM_H_GAUNT_R`, `esskey`, `AM_H_CHOP`, `AM_H_SHOOT`, `AM_H_SWTCH5`, `AM_H_TATTOO`, `AM_H_SHOUT`, `AM_H_GARAGEP`, `AM_H_LHNGR`, `AM_H_CREWU`, `CMOD_TYR_LG`, `strikeforce`, `AM_H_CRCE`, `AM_H_FOU`, `launcher_stunts`, `AM_H_STNTP`, `AM_H_SRAC`, `AM_H_SEAR`, `AM_H_PLTSC`, `AM_H_OFFRR`, `AM_H_HUNT`, `AM_H_GOLF`, `AM_H_BASEJ`, `ASS1_MIS`, `AM_H_STOCKS`, `avarus`, `chimera`

---

Source: `decompiled_scripts/code_controller.c`
