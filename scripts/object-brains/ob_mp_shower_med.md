# ob_mp_shower_med.c

Object brains script. 4 anim dicts; 4 models; 2 particle effects.

| | |
|---|---|
| Category | Object brains |
| Total lines | 103,329 |
| Functions | 559 (29 unique, 530 shared) |
| Unique lines | 2,424 (2.3% of file) |

## Assets

**Animation dictionaries** (4) - `ANIM@MP_YACHT@SHOWER@MALE@`, `ANIM@MP_YACHT@SHOWER@FEMALE@`, `mp_safehouseshower@male@`, `mp_safehouseshower@female@`

**Models and props** (4) - `xs_prop_arena_showerdoor_s`, `p_mp_showerdoor_s`, `apa_p_mp_h_showerdoor_s`, `ex_p_mp_h_showerdoor_s`

**Sounds** (5) - `MP_APARTMENT_SHOWER_DOOR_OPEN_MASTER`, `MP_APARTMENT_SHOWER_GET_UNDRESSED_MASTER`, `MP_APARTMENT_SHOWER_GET_DRESSED_MASTER`, `GTAO_MP_APARTMENT_SHOWER_PLASTIC_MASTER`, `MP_APARTMENT_SHOWER_MASTER`

**Particle effects** (2) - `ent_amb_shower`, `ent_amb_shower_steam`

**Text labels** (1) - `NULL`

**Interiors and entity sets** (7) - `ac_mpapa_yacht`, `h4_islandx_yacht_01_int`, `h4_islandx_yacht_02_int`, `h4_islandx_yacht_03_int`, `sf_yacht_01_int`, `sf_yacht_02_int`, `apa_mpapa_yacht`

**Hashed names** (1) - `ob_mp_shower_med`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (79), `PLAYER_ID` (52), `CREATE_SYNCHRONIZED_SCENE` (16), `GET_SYNCHRONIZED_SCENE_PHASE` (14), `SET_CAM_PARAMS` (13), `GET_CLOSEST_OBJECT_OF_TYPE` (12), `GET_GAME_TIMER` (12), `SET_PED_COMPONENT_VARIATION` (11), `HIDE_HUD_AND_RADAR_THIS_FRAME` (10), `DOES_CAM_EXIST` (9), `DOES_ENTITY_EXIST` (8), `CLEAR_HELP` (8), `GET_INTERIOR_AT_COORDS_WITH_TYPE` (7), `TASK_SYNCHRONIZED_SCENE` (7), `PLAY_SOUND_FROM_ENTITY` (6), `CLEAR_BIT` (6), `GET_HASH_KEY` (5), `GET_ENTITY_COORDS` (5), `GET_ROOM_KEY_FROM_ENTITY` (5), `IS_ENTITY_IN_ANGLED_AREA` (5), `IS_PED_INJURED` (4), `NETWORK_IS_GAME_IN_PROGRESS` (4), `CREATE_CAMERA` (4), `SET_CAM_ACTIVE` (4), `RENDER_SCRIPT_CAMS` (4), `SHAKE_CAM` (4), `DOES_ENTITY_HAVE_DRAWABLE` (4), `PLAY_SYNCHRONIZED_ENTITY_ANIM` (4), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (4), `GET_PED_DRAWABLE_VARIATION` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.2f` x4 · `0.99f` x3 · `115.1641f` x2 · `0.3f` x1 · `0.76f` x1 · `0.8f` x1 · `0.6f` x1 · `0.252f` x1 · `0.148f` x1 · `0.02f` x1 · `202.819f` x1 · `5162.173f` x1 · `-88.8851f` x1 · `979.1015f` x1 · `72.9345f` x1 · `981.7758f` x1 · `70.6806f` x1 · `389.44f` x1 · `-69.02f` x1 · `110.96f` x1 · `-1011.08f` x1 · `-429.52f` x1 · `71.46f` x1 · `-596.73f` x1

## Other strings

Literals whose consuming native was not classified:

`SA_SHWR_IN`, `SA_SHWR_IN2`, `HAND_SHAKE`, `shower_idle_a`, `shower_idle_b`, `Apart_Bathroom_Room`, `Apart_Spare_Bath_Rm`, `MPSH_BILL`, `apa_p_mp_yacht_bathroomdoor`, `SA_SHWR_OUT2`, `SA_SHWR_OUT`, `male_shower_undress_&_turn_on_water`, `male_shower_enter_into_idle`, `male_shower_idle_a`, `male_shower_idle_b`, `male_shower_idle_c`, `male_shower_idle_d`, `Male_Shower_Exit_To_Idle`, `shower_undress_&_turn_on_water`, `shower_enter_into_idle`, `shower_Exit_To_Idle`, `dlc_EXEC1/MP_APARTMENT_SHOWER_01`, `mp_f_freemode_01`, `MP_SAM_APT_BATH_DOOR_1_YACHT_`, `MP_SAM_APT_BATH_DOOR_2_YACHT_`, `MP_SAM_APT_BATH_DOOR_3_YACHT_`, `Male_Shower_Undress_&_Turn_On_Water_PROP_DOOR`, `Male_Shower_Exit_To_Idle_PROP_DOOR`, `Shower_Undress_&_Turn_On_Water_PROP_DOOR`, `Shower_Exit_To_Idle_PROP_DOOR`

---

Source: `decompiled_scripts/ob_mp_shower_med.c`
