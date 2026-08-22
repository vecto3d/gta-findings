# traffick_ground.c

Jobs script. 1 anim dicts; 16 models; 1 particle effects.

| | |
|---|---|
| Category | Jobs |
| Total lines | 23,990 |
| Functions | 375 (120 unique, 255 shared) |
| Unique lines | 9,774 (40.7% of file) |

## Assets

**Animation dictionaries** (1) - `p_cargo_chute_s`

**Animations** (3) - `p_cargo_chute_s`, `p_cargo_chute_s_deploy`, `p_cargo_chute_s_crumple`

**Models and props** (16) - `g_m_m_mexboss_01`, `g_m_y_salvagoon_03`, `a_m_m_hillbilly_01`, `prop_flare_01b`, `a_m_y_genstreet_01`, `g_m_y_strpunk_01`, `prop_drop_armscrate_01b`, `p_cargo_chute_s`, `buzzard`, `s_f_y_cop_01`, `rebel`, `dune`, `prop_gascyl_ramp_01`, `prop_gascyl_ramp_door_01`, `prop_flare_01`, `prop_gascyl_01a`

**Sounds** (6) - `PLANE_FLY_OVER_SCENE`, `TIMER`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `PICK_UP_WEAPON`, `HUD_FRONTEND_CUSTOM_SOUNDSET`, `TRAFFIC_GROUND_ENEMY_PICK_UP_WEAPON_MASTER`

**Particle effects** (1) - `scr_drug_traffic_flare_L`

**Text labels** (8) - `ARMSAUD`, `TREVOR`, `OSCAR`, `COP`, `DTRFKGR_06`, `NULL`, `DTRFKGR`, `DTRSHRD`

**Scenarios** (1) - `PRISON_TOWERS`

**Vehicle recordings** (1) - `GroundTaxi`

**Relationship groups** (4) - `policeChasers`, `carChaserEnemies`, `SmugglerEnemies`, `ambushGroup`

**Vehicle mods** (2) - `dloader`, `dune`

**Stats** (1) - `num_trafficking_completed`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (231), `IS_ENTITY_DEAD` (158), `DOES_ENTITY_EXIST` (100), `DOES_BLIP_EXIST` (79), `IS_PED_INJURED` (71), `GET_ENTITY_COORDS` (50), `REMOVE_BLIP` (46), `IS_VEHICLE_DRIVEABLE` (45), `GET_PED_IN_VEHICLE_SEAT` (34), `IS_ENTITY_AT_COORD` (33), `CLEAR_SEQUENCE_TASK` (28), `REQUEST_MODEL` (26), `TASK_COMBAT_PED` (24), `ADD_BLIP_FOR_ENTITY` (22), `TRIGGER_MUSIC_EVENT` (21), `HAS_MODEL_LOADED` (21), `SET_PED_COMBAT_ATTRIBUTES` (21), `SET_BLIP_COLOUR` (19), `IS_PED_IN_ANY_VEHICLE` (18), `WAIT` (18), `IS_PED_IN_VEHICLE` (18), `OPEN_SEQUENCE_TASK` (17), `CLOSE_SEQUENCE_TASK` (17), `TASK_PERFORM_SEQUENCE` (17), `DELETE_OBJECT` (16), `VDIST2` (15), `SET_BLIP_NAME_FROM_TEXT_FILE` (15), `VDIST` (14), `GET_GAME_TIMER` (14), `SET_RELATIONSHIP_BETWEEN_GROUPS` (14)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x14 · `2149.328f` x2 · `4805.958f` x2 · `40.2094f` x2 · `45.9679f` x2 · `4507.976f` x2 · `2784.227f` x2 · `49.1813f` x2 · `4198.859f` x2 · `2890.96f` x2 · `40.0605f` x2 · `4760.453f` x2 · `2030.663f` x2 · `2164.038f` x2 · `4825.627f` x2 · `35.61375f` x2 · `1899.278f` x2 · `4697.752f` x2 · `49.08641f` x2 · `1757.215f` x2 · `4570.54f` x2 · `30.47729f` x2 · `1385.558f` x2 · `4495.364f` x2

## Other strings

Literals whose consuming native was not classified:

`cuban800`, `player`, `DTRFKGR_03`, `bison`, `DTRFKGR_BLIP07`, `DTRSHRD_03`, `DTRFKGR_03a`, `DTRFKGR_06`, `DTRSHRD_MPASS`, `DTRSHRD_GRT`, `DTRSHRD_MONEY`, `DTRSHRD_WEAP01`, `DTRSHRD_WEAP02`, `DTRSHRD_WEAP03`, `DTRSHRD_WEAP04`, `DTRSHRD_WEAP05`, `ARMS_PACK`, `dune`, `rebel`, `PlaneGraveyardGround`, `NEW_TYPE1_05`, `bati`, `ARMS_GRTP02`, `ARMS_GRTP03`, `ARMS_GRTP04`, `ARMS_GRTP05`, `ARMS_GRTP06`, `ARMS_GRTP07`, `police`, `buzzard`

---

Source: `decompiled_scripts/traffick_ground.c`
