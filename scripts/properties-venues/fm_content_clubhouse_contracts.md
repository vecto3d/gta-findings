# fm_content_clubhouse_contracts.c

Properties and venues script. 8 anim dicts; 8 models; 2 particle effects.

| | |
|---|---|
| Category | Properties and venues |
| Total lines | 517,211 |
| Functions | 10,711 (415 unique, 10,296 shared) |
| Unique lines | 15,227 (2.9% of file) |

## Assets

**Animation dictionaries** (8) - `anim@scripted@player@mission@tunf_train_ig1_container_p1@male@`, `move_m@bag`, `anim@scripted@player@mission@tunf_train_ig1_container_p1@heeled@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@scripted@player@freemode@tun_prep_ig3_grab_high@male@`, `anim@scripted@heist@ig3_button_press@male@`, `anim@door_trans@hinge_l@`, `anim@door_trans@hinge_r@`

**Animations** (1) - `action_container`

**Models and props** (8) - `prop_compressor_02`, `prop_aircon_m_02`, `CH_PROP_CON`, `s_m_m_dockwork_01`, `s_m_m_ciasec_01`, `v_ilev_rc_door2`, `apa_mp_h_str_avunitm_01`, `ex_prop_crate_elec_bc`

**Audio banks** (2) - `ALARM_KLAXON_04`, `DLC_HEI4/DLCHEI4_GENERIC_01`

**Sounds** (6) - `Push`, `GTAO_APT_DOOR_DOWNSTAIRS_WOOD_SOUNDS`, `Barge_Door`, `dlc_h4_Prep_FC_Sounds`, `collect_keys`, `dlc_vw_recover_luxury_car_sounds`

**Particle effects** (2) - `scr_tn_tr`, `scr_tn_tr_angle_grinder_sparks`

**Text labels** (10) - `61DKZ202`, `48CPZ610`, `60HNT782`, `SM2MAAU`, `MALCOLM`, `06MHZ853`, `25OAH874`, `23SOP726`, `43TNX375`, `62AVU759`

**Interiors and entity sets** (1) - `mp_h_02_bedroom`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (110), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (48), `NET_TO_ENT` (40), `SET_BIT` (40), `DOES_ENTITY_EXIST` (23), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (15), `NETWORK_GET_ENTITY_FROM_NETWORK_ID` (13), `DISABLE_CONTROL_ACTION` (10), `FREEZE_ENTITY_POSITION` (9), `NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE` (9), `GET_SYNCHRONIZED_SCENE_PHASE` (9), `GET_ENTITY_COORDS` (9), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (8), `SET_ENTITY_COLLISION` (8), `NET_TO_VEH` (8), `IS_SYNCHRONIZED_SCENE_RUNNING` (7), `IS_ENTITY_ATTACHED` (7), `IS_VEHICLE_DRIVEABLE` (7), `SET_ENTITY_VISIBLE` (7), `IS_STRING_NULL_OR_EMPTY` (6), `CLEAR_PED_TASKS` (6), `IS_ENTITY_DEAD` (6), `NETWORK_HAS_CONTROL_OF_ENTITY` (6), `GET_DISTANCE_BETWEEN_COORDS` (6), `SET_ENTITY_INVINCIBLE` (6), `CLEAR_BIT` (6), `GET_RANDOM_INT_IN_RANGE` (6), `DOES_BLIP_EXIST` (5), `IS_ENTITY_VISIBLE` (5), `SET_CAN_CLIMB_ON_ENTITY` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x5 · `0.5f` x4 · `0.25f` x3 · `0.6f` x2 · `0.01f` x2 · `219.4385f` x2 · `-797.76f` x2 · `326.07f` x2 · `221.183f` x2 · `-797.762f` x2 · `328.692f` x2 · `221.04f` x2 · `206.963f` x2 · `-997.835f` x2 · `-100.001f` x2 · `-793.941f` x2 · `324.588f` x2 · `217.188f` x2 · `-1295.031f` x2 · `-726.788f` x2 · `30.638f` x2 · `0.4f` x2 · `-0.5f` x1 · `-0.01f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `typ`, `ibs`, `sprt`, `hclr`, `scl`, `rot`, `bsa`, `rad`, `blp`, `veh`, `landstalker2`, `oppressor`, `action_container`, `ACTION_BAG`, `ACTION_ANGLE_GRINDER`, `ACTION_LOCK`, `tr_prop_tr_cont_coll_01a`, `MAX_NUM_SCENARIOS`, `grp`, `MPSUM2_BIKER_SUSPENSE`, `CH_BLIP_CON`, `benson`

---

Source: `decompiled_scripts/fm_content_clubhouse_contracts.c`
