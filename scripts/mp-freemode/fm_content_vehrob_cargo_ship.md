# fm_content_vehrob_cargo_ship.c

MP freemode script. 16 anim dicts; 3 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 541,009 |
| Functions | 11,158 (671 unique, 10,487 shared) |
| Unique lines | 19,419 (3.6% of file) |

## Assets

**Animation dictionaries** (16) - `anim@scripted@player@freemode@ig6_stash_entry@door_trans@hinge_l@`, `anim@scripted@freemode@ig3_open_container@heeled@`, `anim@scripted@freemode@ig3_open_container@male@`, `timetable@jimmy@doorknock@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@heeled@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@male@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@heeled@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@amb@warehouse@laptop@`, `anim_heist@hs3f@ig6_push_button@heeled@`, `anim_heist@hs3f@ig6_push_button@male@`, `weapons@first_person@aim_rng@generic@projectile@sticky_bomb@`, `anim@scripted@freemode@ig1_cut_open_container_positive@heeled@`, `anim@scripted@freemode@ig1_cut_open_container_positive@male@`, `anim@scripted@freemode@ig2_cut_open_container_negative@heeled@`, `anim@scripted@freemode@ig2_cut_open_container_negative@male@`

**Models and props** (3) - `hei_prop_wall_alarm_on`, `hei_prop_wall_alarm_off`, `v_res_binder`

**Audio banks** (1) - `DLC_HEI4/DLCHEI4_GENERIC_01`

**Sounds** (4) - `PICK_UP`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `Barge_Door_Metal_Bars`, `dlc_h4_Prep_FC_Sounds`

**Text labels** (4) - `RAIN`, `XM4R1AU`, `FINALE`, `66UFV929`

**Timecycle modifiers** (1) - `DRUG_gas_huffin`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (108), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (38), `NET_TO_ENT` (32), `GET_ENTITY_COORDS` (30), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (21), `POW` (20), `VDIST2` (15), `SET_BIT` (14), `NET_TO_VEH` (14), `NETWORK_IS_PARTICIPANT_ACTIVE` (11), `SET_ENTITY_INVINCIBLE` (11), `IS_SYNCHRONIZED_SCENE_RUNNING` (10), `GET_SYNCHRONIZED_SCENE_PHASE` (10), `SET_ENTITY_VISIBLE` (9), `SET_ENTITY_LOAD_COLLISION_FLAG` (9), `GET_MODEL_DIMENSIONS` (8), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (8), `TASK_HELI_MISSION` (8), `GET_ACTIVE_VEHICLE_MISSION_TYPE` (8), `FREEZE_ENTITY_POSITION` (8), `SET_PED_COMPONENT_VARIATION` (8), `DISABLE_CONTROL_ACTION` (7), `DOES_ENTITY_EXIST` (7), `SET_ENTITY_ROTATION` (7), `GET_ENTITY_HEADING` (7), `IS_ENTITY_IN_ANGLED_AREA` (7), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (7), `INT_TO_PARTICIPANTINDEX` (6), `NETWORK_GET_PLAYER_INDEX` (6), `CLEAR_PED_TASKS` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x4 · `0.198385f` x4 · `0.9f` x2 · `1.5f` x2 · `24.34851f` x2 · `0.25f` x2 · `-442.7875f` x1 · `-757.3036f` x1 · `18.98315f` x1 · `-481.2581f` x1 · `-757.5583f` x1 · `50.23316f` x1 · `-0.065298f` x1 · `-1109.027f` x1 · `28.15203f` x1 · `24.17291f` x1 · `-1042.147f` x1 · `43.05404f` x1 · `-1221.008f` x1 · `-386.0472f` x1 · `33.20631f` x1 · `-1235.055f` x1 · `-359.416f` x1 · `64.45631f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `ibs`, `CSF_OT_BRDSHP`, `sprt`, `hclr`, `scl`, `rot`, `bsa`, `typ`, `blp`, `veh`, `grp`, `DLC_23_2_Cargo_Ship_Robbery_Finale_Sounds`, `MAX_NUM_SCENARIOS`, `MAX_NUM_TRANSITIONS`, `MP232_DELIVERING`, `CSF_BL_CPT`, `landstalker2`, `patriot3`, `action_container`, `CSF_BL_CON`, `action`, `fcs`

---

Source: `decompiled_scripts/fm_content_vehrob_cargo_ship.c`
