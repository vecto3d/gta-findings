# am_mp_smoking_activity.c

MP ambient script. 1 anim dicts; 2 models; 6 particle effects.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 362,135 |
| Functions | 6,552 (57 unique, 6,495 shared) |
| Unique lines | 12,278 (3.4% of file) |

## Assets

**Animation dictionaries** (1) - `ANIM@AMB@NIGHTCLUB@SMOKING@`

**Animations** (1) - `base`

**Models and props** (2) - `p_cs_lighter_01`, `ex_prop_exec_ashtray_01`

**Audio banks** (1) - `SAFEHOUSE_FRANKLIN_SOFA`

**Particle effects** (6) - `scr_safehouse`, `scr_sh_cig_exhale_nose`, `scr_sh_cig_exhale_mouth`, `scr_sh_lighter_sparks`, `scr_sh_lighter_flame`, `scr_sh_cig_smoke`

**Text labels** (1) - `NULL`

**Hashed names** (3) - `AM_SIMOSA`, `P_CS_Joint_01`, `ng_proc_cigarette01a`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (83), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (39), `PLAYER_PED_ID` (27), `NETWORK_DOES_NETWORK_ID_EXIST` (27), `NET_TO_OBJ` (18), `CLEAR_BIT` (17), `SET_BIT` (15), `NETWORK_REQUEST_CONTROL_OF_NETWORK_ID` (15), `GET_SYNCHRONIZED_SCENE_PHASE` (13), `GET_ANIM_INITIAL_OFFSET_POSITION` (7), `GET_ANIM_INITIAL_OFFSET_ROTATION` (7), `NETWORK_CREATE_SYNCHRONISED_SCENE` (7), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (7), `NETWORK_START_SYNCHRONISED_SCENE` (7), `USE_PARTICLE_FX_ASSET` (7), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (6), `SET_ENTITY_COORDS_NO_OFFSET` (6), `SET_ENTITY_ROTATION` (6), `FREEZE_ENTITY_POSITION` (6), `NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE` (6), `REQUEST_ANIM_DICT` (4), `HAS_ANIM_DICT_LOADED` (4), `REMOVE_ANIM_DICT` (4), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (4), `DOES_PARTICLE_FX_LOOPED_EXIST` (4), `START_NETWORKED_PARTICLE_FX_NON_LOOPED_ON_PED_BONE` (4), `STOP_PARTICLE_FX_LOOPED` (4), `RESERVE_LOCAL_NETWORK_MISSION_OBJECTS` (4), `GET_PLAYER_PED` (4), `NETWORK_IS_GAME_IN_PROGRESS` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x4 · `-0.025f` x4 · `0.05f` x3 · `0.45f` x3 · `0.12f` x2 · `0.13f` x2 · `-70.0027f` x1 · `-5.1277f` x1 · `0.25f` x1 · `0.255f` x1 · `0.27f` x1 · `0.346f` x1 · `-0.09f` x1 · `0.82f` x1 · `0.876f` x1

## Other strings

Literals whose consuming native was not classified:

`blunt_enter_lighter`, `blunt_enter_joint`, `blunt_enter_ashtray`, `enter`, `base`, `rm_GamingFloor_01`, `rm_Lounge_01`, `rm_Lounge_02`, `BLUNT_SIT_PRMPT`, `BLUNT_HELP_PC`, `BLUNT_HELP`, `exit`, `blunt_enter`, `blunt_exit`, `blunt_exit_ashtray`, `blunt_exit_joint`, `blunt_exit_lighter`

---

Source: `decompiled_scripts/am_mp_smoking_activity.c`
