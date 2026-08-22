# fm_content_cargo.c

MP freemode script. 12 anim dicts; 9 models; 2 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 531,313 |
| Functions | 10,823 (518 unique, 10,305 shared) |
| Unique lines | 17,846 (3.4% of file) |

## Assets

**Animation dictionaries** (12) - `anim@scripted@player@mission@tunf_train_ig1_container_p1@male@`, `anim@door_trans@hinge_l@`, `anim@scripted@player@freemode@tun_prep_ig3_grab_high@heeled@`, `anim@scripted@player@freemode@tun_prep_ig3_grab_high@male@`, `anim@apt_trans@garage`, `ANIM_HEIST@HS4F@IG14_OPEN_CAR_TRUNK@FEMALE@`, `ANIM_HEIST@HS4F@IG14_OPEN_CAR_TRUNK@MALE@`, `ANIM@SCRIPTED@PLAYER@FREEMODE@TUN_PREP_GRAB_MIDD_IG3@HEELED@`, `ANIM@SCRIPTED@PLAYER@FREEMODE@TUN_PREP_GRAB_MIDD_IG3@MALE@`, `ANIM_HEIST@HS3F@IG12_CHANGE_CLOTHES@`, `ANIM@SCRIPTED@FREEMODE@UNDERWATER_SATCHEL_BOMB@HEELED@`, `ANIM@SCRIPTED@FREEMODE@UNDERWATER_SATCHEL_BOMB@MALE@`

**Animations** (2) - `action_container`, `anim@scripted@player@mission@tunf_train_ig1_container_p1@male@`

**Models and props** (9) - `prop_security_case_01`, `sm_prop_smug_cover_01a`, `sm_prop_smug_cont_01a`, `prop_box_wood06a`, `v_serv_abox_1`, `bkr_prop_biker_case_shut`, `hei_prop_heist_thermite_case`, `prop_idol_case_01`, `prop_idol_case_02`

**Sounds** (2) - `collect_keys`, `dlc_vw_recover_luxury_car_sounds`

**Particle effects** (2) - `scr_xm_submarine`, `exp_underwater_mine`

**Text labels** (16) - `86CVG072`, `84TFX949`, `06NZQ185`, `65GRZ071`, `68KWK927`, `15HBW365`, `SM2WBAU`, `44RUK973`, `86DUO860`, `78LJI764`, `42XUR612`, `41OML010`, `08BGR520`, `ACTION`, `CONTRAVALUE`, `CONTRAVALUES`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (97), `SET_BIT` (31), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (21), `NET_TO_ENT` (14), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (13), `SET_PED_COMBAT_ATTRIBUTES` (13), `NETWORK_DOES_NETWORK_ID_EXIST` (12), `DOES_ENTITY_EXIST` (12), `GET_ENTITY_COORDS` (12), `PLAYER_ID` (11), `GET_SYNCHRONIZED_SCENE_PHASE` (9), `GET_RANDOM_INT_IN_RANGE` (8), `SET_ENTITY_VISIBLE` (7), `TO_FLOAT` (6), `SET_ENTITY_COLLISION` (6), `NET_TO_VEH` (5), `ROUND` (5), `DISABLE_CONTROL_ACTION` (5), `CLEAR_PED_TASKS` (5), `IS_ENTITY_IN_ANGLED_AREA` (5), `NETWORK_IS_PARTICIPANT_ACTIVE` (5), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (5), `IS_SYNCHRONIZED_SCENE_RUNNING` (4), `HAS_ENTITY_CLEAR_LOS_TO_ENTITY` (4), `GET_RANDOM_FLOAT_IN_RANGE` (4), `SET_ENTITY_HEALTH` (4), `ENABLE_DISPATCH_SERVICE` (4), `SET_ENTITY_COMPLETELY_DISABLE_COLLISION` (4), `NETWORK_FADE_IN_ENTITY` (4), `ARE_STRINGS_EQUAL` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x5 · `-3.5f` x4 · `1.25f` x3 · `0.15f` x3 · `0.99f` x2 · `-0.5f` x2 · `-0.75f` x2 · `0.8f` x2 · `0.28f` x2 · `-0.25f` x1 · `0.56f` x1 · `-0.27f` x1 · `0.3f` x1 · `1.64f` x1 · `0.21f` x1 · `0.55f` x1 · `-0.02f` x1 · `0.67f` x1 · `-0.9f` x1 · `0.9f` x1 · `-0.52f` x1 · `0.37f` x1 · `1.5f` x1 · `-1320.178f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `sultanrs`, `banshee2`, `int`, `typ`, `sprt`, `hclr`, `scl`, `bsa`, `ibs`, `ASR_OT_ENTAUTO`, `ASR_OT_EXTAUTO`, `blp`, `veh`, `rot`, `idx`, `rad`, `youga`, `dinghy3`, `MAX_NUM_SCENARIOS`, `grp`, `MPSUM2_GNRL_SUSPENSE`, `walk_cam_left`, `walk_player1`

---

Source: `decompiled_scripts/fm_content_cargo.c`
