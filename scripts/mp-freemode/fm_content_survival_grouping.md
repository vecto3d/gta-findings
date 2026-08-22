# fm_content_survival_grouping.c

MP freemode script. 2 anim dicts; 1 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 466,726 |
| Functions | 9,402 (116 unique, 9,286 shared) |
| Unique lines | 2,601 (0.6% of file) |

## Assets

**Animation dictionaries** (2) - `anim@scripted@freemode@ig11_smoke_joint@heeled@`, `anim@scripted@freemode@ig11_smoke_joint@male@`

**Models and props** (1) - `prop_sh_joint_01`

**Text labels** (1) - `FM_IHELP_WAT2`

## Native vocabulary

Most-called natives inside the code unique to this script:

`HIDE_HUD_COMPONENT_THIS_FRAME` (16), `NET_TO_ENT` (8), `DISABLE_CONTROL_ACTION` (7), `SET_BIT` (5), `USE_PARTICLE_FX_ASSET` (4), `CLEAR_HELP` (4), `SET_REMOTE_PLAYER_AS_GHOST` (4), `SET_LOCAL_PLAYER_AS_GHOST` (3), `IS_PAUSE_MENU_ACTIVE` (3), `SET_PARTICLE_FX_LOOPED_ALPHA` (2), `DOES_PARTICLE_FX_LOOPED_EXIST` (2), `NETWORK_HASH_FROM_PLAYER_HANDLE` (2), `GET_ANIM_INITIAL_OFFSET_POSITION` (2), `IS_ENTITY_DEAD` (2), `SET_PED_FOOTSTEPS_EVENTS_ENABLED` (2), `INT_TO_PLAYERINDEX` (2), `GET_ENTITY_HEADING` (2), `GET_CURRENT_PED_WEAPON` (2), `SET_CURRENT_PED_WEAPON` (2), `NETWORK_GET_PLAYER_INDEX` (2), `CLEAR_BIT` (2), `NETWORK_IS_PARTICIPANT_ACTIVE` (2), `INT_TO_PARTICIPANTINDEX` (2), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (2), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (2), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (2), `PARTICIPANT_ID_TO_INT` (2), `GET_ENTITY_COORDS` (2), `PLAYER_PED_ID` (2), `IS_CONTROL_JUST_PRESSED` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x4 · `1.25f` x2 · `2330.68f` x2 · `2561.23f` x2 · `46.5232f` x2 · `2.75f` x1 · `0.1f` x1 · `-1.5f` x1 · `0.75f` x1 · `-1.1f` x1 · `0.6f` x1 · `10.1023f` x1 · `-165.894f` x1 · `113.254f` x1

## Other strings

Literals whose consuming native was not classified:

`420S_INTERACT`, `MAX_NUM_TRANSITIONS`, `VULKAN_LOCK_ON_RED`, `VULKAN_LOCK_ON_AMBER`, `smoke_player_facial`, `smoke_player`, `smoke_table`, `smoke_ashtray`, `smoke_joint`, `iNumModeStates`, `MAX_NUM_STATES`, `iNumClientModeStates`, `MAX_NUM_CLIENT_STATES`, `sModeStates[iLoop].iNumTransitions`, `sClientModeStates[iLoop].iNumTransitions`, `sPedLocal.sBehaviour[iLoop].iNumTasks`, `MAX_NUM_PED_TASKS`, `sPedLocal.sBehaviour[iLoop].Task[iLoop2].iNumTransitions`, `MAX_NUM_PED_TASK_TRANSITIONS`, `sPedLocal.sPed[iLoop].iNumTriggers`, `MAX_NUM_PED_TRIGGERS`, `GET_NUM_HELP_TEXTS()`, `MAX_NUM_HELP_TEXTS`, `DrugsMichaelAliensFightIn`, `scr_man_surv_weed_smoke`, `scr_man_surv`, `420S_BLIP`, `420S_HELP`, `420S_HELP_G`, `420S_HELP_P`

---

Source: `decompiled_scripts/fm_content_survival_grouping.c`
