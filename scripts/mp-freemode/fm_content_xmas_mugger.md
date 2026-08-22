# fm_content_xmas_mugger.c

MP freemode script. 2 models; 2 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 466,032 |
| Functions | 9,357 (110 unique, 9,247 shared) |
| Unique lines | 2,376 (0.5% of file) |

## Assets

**Models and props** (2) - `xm3_prop_xm3_present_01a`, `u_m_m_yulemonster`

**Audio banks** (1) - `DLC_CM2022/CM2022_FREEMODE_01`

**Particle effects** (2) - `scr_xt_mugger`, `scr_xt_mug_appear`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_CONFIG_FLAG` (11), `DOES_ENTITY_EXIST` (9), `SET_PED_COMBAT_ATTRIBUTES` (8), `SET_BIT` (6), `IS_PED_IN_ANY_VEHICLE` (5), `GET_ENTITY_COORDS` (5), `NETWORK_PLAYER_ID_TO_INT` (5), `GET_VEHICLE_PED_IS_IN` (5), `NET_TO_PED` (4), `SET_ENTITY_HEALTH` (3), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (3), `IS_ENTITY_DEAD` (3), `TO_FLOAT` (3), `DOES_BLIP_EXIST` (3), `SET_ENTITY_VISIBLE` (3), `PLAYER_PED_ID` (3), `IS_PED_JACKING` (3), `PLAYER_ID` (3), `NETWORK_HASH_FROM_PLAYER_HANDLE` (2), `REMOVE_BLIP` (2), `SET_ENTITY_PROOFS` (2), `NETWORK_SPENT_ROBBED_BY_MUGGER` (2), `IS_PED_RAGDOLL` (2), `IS_PED_INJURED` (2), `GET_JACK_TARGET` (2), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (2), `PARTICIPANT_ID_TO_INT` (2), `SET_COMBAT_FLOAT` (2), `REMOVE_NAMED_PTFX_ASSET` (1), `RELEASE_NAMED_SCRIPT_AUDIO_BANK` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.2f` x1 · `1.5f` x1 · `0.5f` x1 · `-0.3f` x1

## Other strings

Literals whose consuming native was not classified:

`CM2022_Mugger_Sounds`, `xm3_prop_xm3_present_01a`, `fm_content_xmas_mugger`, `MAX_NUM_TRANSITIONS`, `VULKAN_LOCK_ON_RED`, `VULKAN_LOCK_ON_AMBER`, `XM_TICK_RE_XM_3`, `XM_HELP_RE_XM_0`, `XM_HELP_RE_XM_1`, `XM_HELP_RE_XM_2`, `Spawn`, `Chase_Loop`, `Steal`, `Die`, `De_Spawn`, `XM_TICK_RE_XM_2`, `service_earn_ambient_job_xmas_mugger`, `XM_GOUTF`, `XM_PRESENT`, `iNumModeStates`, `MAX_NUM_STATES`, `iNumClientModeStates`, `MAX_NUM_CLIENT_STATES`, `sModeStates[iLoop].iNumTransitions`, `sClientModeStates[iLoop].iNumTransitions`, `sPedLocal.sBehaviour[iLoop].iNumTasks`, `MAX_NUM_PED_TASKS`, `sPedLocal.sBehaviour[iLoop].Task[iLoop2].iNumTransitions`, `MAX_NUM_PED_TASK_TRANSITIONS`, `sPedLocal.sPed[iLoop].iNumTriggers`

---

Source: `decompiled_scripts/fm_content_xmas_mugger.c`
