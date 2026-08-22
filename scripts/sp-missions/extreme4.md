# extreme4.c

SP missions script. 2 anim dicts; 7 models; 2 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 39,785 |
| Functions | 371 (25 unique, 346 shared) |
| Unique lines | 1,314 (3.3% of file) |

## Assets

**Animation dictionaries** (2) - `rcmextreme4`, `skydive@parachute@`

**Animations** (9) - `rcmextreme4`, `idle`, `Base_Jump_Spot_02`, `Fall_and_impact`, `Base_Jump_Spot`, `fidget_01`, `fidget_02`, `Chute_Off_Bag`, `skydive@parachute@`

**Models and props** (7) - `prop_box_wood01a`, `p_parachute_s`, `prop_box_guncase_03a`, `a_c_retriever`, `sanchez`, `bmx`, `cs_dom`

**Audio banks** (3) - `EXTREME_04_DOM_A`, `EXTREME_04_DOM_B`, `EXTREME_04_DOM_C`

**Sounds** (3) - `EXTREME_04_CUSTOM_QUIET_SCENE`, `DOM`, `EXTREME_04_SOUNDSET`

**Particle effects** (2) - `scr_extrm4_water_blood`, `scr_extrm4_water_splash`

**Text labels** (5) - `EXT4AUD`, `FRANKLIN`, `NULL`, `DOM`, `EXT4`

**Scenarios** (1) - `WORLD_VEHICLE_BICYCLE_MOUNTAIN`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (71), `GET_GAME_TIMER` (19), `DOES_ENTITY_EXIST` (13), `DOES_CAM_EXIST` (12), `IS_SYNCHRONIZED_SCENE_RUNNING` (11), `WAIT` (9), `IS_ENTITY_IN_ANGLED_AREA` (9), `IS_CONTROL_PRESSED` (8), `TASK_PLAY_ANIM` (7), `REQUEST_MODEL` (7), `SET_CAM_ACTIVE` (6), `RENDER_SCRIPT_CAMS` (6), `HAS_MODEL_LOADED` (6), `SET_PLAYER_CONTROL` (5), `PLAYER_ID` (5), `GET_SYNCHRONIZED_SCENE_PHASE` (5), `CREATE_CAM` (5), `GET_VEHICLE_PED_IS_IN` (5), `IS_ENTITY_DEAD` (4), `SET_TIME_SCALE` (4), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (4), `IS_PED_IN_ANY_VEHICLE` (4), `TASK_FOLLOW_NAV_MESH_TO_COORD` (4), `SET_ENTITY_ROTATION` (4), `REPLAY_START_EVENT` (3), `CREATE_SYNCHRONIZED_SCENE` (3), `TASK_SYNCHRONIZED_SCENE` (3), `SET_SYNCHRONIZED_SCENE_HOLD_LAST_FRAME` (3), `PLAY_SYNCHRONIZED_CAM_ANIM` (3), `DESTROY_CAM` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.2f` x4 · `172.6748f` x3 · `1656.378f` x3 · `-12.057f` x3 · `169.038f` x3 · `115.85f` x3 · `1655.27f` x3 · `-20.8134f` x3 · `175.0248f` x2 · `1665.729f` x2 · `-26.27869f` x2 · `172.5815f` x2 · `1672.652f` x2 · `-24.58394f` x2 · `177.2547f` x2 · `1650.519f` x2 · `5.134407f` x2 · `172.6743f` x2 · `1656.571f` x2 · `9.669823f` x2 · `176.7743f` x2 · `15.25f` x2 · `133.842f` x2 · `1659.893f` x2

## Other strings

Literals whose consuming native was not classified:

`rcmextreme4`, `Dom`, `DEFAULT_ANIMATED_CAMERA`, `EXT4_JUMPED_OS`, `es_4_rcm_p2_concat`, `SLOWMO_EXTREME_04`, `DEFAULT_SCRIPTED_CAMERA`, `EXT4_ATTACK`, `MotionState_Walk`, `EXT4_F2`, `Force cleanup [TERMINATING]`, `SF_UR`, `EXT4_WIL2`, `Base_Jump_Spot_02_CAM`, `RCM_Extreme4_Fall_and_impact`, `Fall_and_impact_CAM`, `EXT4_DUMB`, `Base_Jump_Spot_CAM`, `EXT4_01`, `EXT4_ATTACK_1`, `EXT4_ATTACK_2`, `EXT4_COMM`, `EXT4_DOM`, `EXTREME LAUNCHER RC`, `es_4_rcm_p1`, `Hudson`, `Franklin`, `EXT4_F1`, `bmx`, `Ext4-Dom`

---

Source: `decompiled_scripts/extreme4.c`
