# fm_content_car_wash_work.c

MP freemode script. 28 anim dicts; 25 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 528,927 |
| Functions | 11,491 (942 unique, 10,549 shared) |
| Unique lines | 25,598 (4.8% of file) |

## Assets

**Animation dictionaries** (28) - `anim@door_trans@hinge_l@`, `anim@heists@ornate_bank@grab_cash_heels`, `anim@heists@ornate_bank@grab_cash`, `move_m@bag`, `anim@scripted@freemode@ig3_open_container@heeled@`, `anim@scripted@freemode@ig3_open_container@male@`, `anim@scripted@freemode@ig1_open_container@no_tools@heeled@`, `anim@scripted@freemode@ig1_open_container@no_tools@male@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@male@`, `ANIM@SCRIPTED@PLAYER@FREEMODE@IG6_STASH_ENTRY@DOOR_TRANS@HINGE_L@`, `anim@scripted@freemode@ig1_handover@heeled@`, `anim@scripted@freemode@ig1_handover@male@`, `anim_heist@hs3f@ig12_change_clothes@`, `anim@heists@keycard@`, `ANIM_HEIST@HS3F@IG12_CHANGE_CLOTHES@`, `ANIM_HEIST@HS3F@IG11_STEAL_PAINTING@MALE@`, `ANIM@SCRIPTED@PLAYER@MISSION@TUN_TABLE_GRAB@CASH@HEELED@`, `ANIM@SCRIPTED@PLAYER@MISSION@TUN_TABLE_GRAB@CASH@`, `ANIM@SCRIPTED@PLAYER@MISSION@TUN_TABLE_GRAB@GOLD@HEELED@`, `ANIM@SCRIPTED@PLAYER@MISSION@TUN_TABLE_GRAB@GOLD@`, `anim@scripted@cbr1@ig1_washmach_grab_cash@heeled@`, `anim@scripted@cbr1@ig1_washmach_grab_cash@male@`, `anim@heists@ornate_bank@ig_4_grab_gold`, `anim@heists@money_grab@duffel`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@scripted@heist@ig6_explosive_plant@male@`, `anim_heist@hs4f@ig14_open_car_trunk@male@`, `anim_heist@hs4f@ig14_open_car_trunk@female@`

**Animations** (2) - `grab`, `exit`

**Models and props** (25) - `v_ilev_genbankdoor1`, `v_ilev_genbankdoor2`, `v_ilev_gb_vaubar`, `ch_prop_gold_bar_01a`, `v_ilev_gb_vauldr`, `imp_prop_impexp_coke_trolly`, `v_corp_bk_secpanel`, `imp_prop_impexp_coke_pile`, `ch_prop_vault_dimaondbox_01a`, `hei_prop_heist_cash_pile`, `hei_prop_hei_cash_trolly_01`, `prop_gold_trolly_full`, `prop_hw1_03_gardoor_01`, `w_am_case`, `prop_facgate_06_l`, `prop_facgate_06_r`, `hei_prop_heist_sec_door`, `hei_prop_hei_securitypanel`, `hei_prop_heist_weed_block_01b`, `v_corp_filecabtall_01`, `v_corp_filecabtall`, `bkr_prop_clubhouse_laptop_01a`, `prop_air_sechut_01`, `prop_drug_package`, `vw_Prop_VW_Key_Card_01a`

**Audio banks** (6) - `DLC_HEI4/DLCHEI4_GENERIC_01`, `DLC_MPHEIST/HEIST_STASH_SWAG`, `VEHICLE_SHOP_HUD_1`, `VEHICLE_SHOP_HUD_2`, `DLC_25-1/DLC_25-1_Car_Wash_01`, `DLC_23_2/DLC_23_2_Freemode_1`

**Sounds** (8) - `PICKUP_DEFAULT`, `HUD_FRONTEND_STANDARD_PICKUPS_SOUNDSET`, `Barge_Door_Metal`, `dlc_h4_Prep_FC_Sounds`, `Strip_Vehicle`, `DLC_25-1_Car_Wash_Sounds`, `Door_Unlock`, `DLC_25-1_Stockade_Steal_Sounds`

**Text labels** (4) - `HACK`, `S25RCAU`, `HAO`, `LOOTED`

**Scenarios** (1) - `WORLD_HUMAN_WINDOW_SHOP_BROWSE_SHOWROOM`

**Hashed names** (2) - `CASH_APPEAR`, `EXIT`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (118), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (44), `DOES_ENTITY_EXIST` (43), `GET_ENTITY_COORDS` (43), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (36), `NET_TO_OBJ` (33), `GET_SYNCHRONIZED_SCENE_PHASE` (25), `REMOVE_MODEL_HIDE` (24), `SET_ENTITY_INVINCIBLE` (23), `SET_ENTITY_VISIBLE` (23), `IS_SYNCHRONIZED_SCENE_RUNNING` (19), `GET_ENTITY_MODEL` (18), `NET_TO_ENT` (16), `GET_ENTITY_HEADING` (15), `SET_MODEL_AS_NO_LONGER_NEEDED` (15), `SET_PED_CONFIG_FLAG` (15), `SET_BIT` (15), `IS_STRING_NULL_OR_EMPTY` (15), `NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE` (14), `SET_PED_COMPONENT_VARIATION` (14), `FORCE_ENTITY_AI_AND_ANIMATION_UPDATE` (14), `FREEZE_ENTITY_POSITION` (13), `CREATE_MODEL_HIDE` (13), `HAS_MODEL_LOADED` (13), `IS_ENTITY_PLAYING_ANIM` (12), `REQUEST_MODEL` (12), `GET_ENTITY_ROTATION` (12), `REQUEST_SCRIPT_AUDIO_BANK` (11), `PLAYER_PED_ID` (11), `CREATE_MODEL_HIDE_EXCLUDING_SCRIPT_OBJECTS` (11)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x8 · `1.5f` x5 · `16.048f` x4 · `38.132f` x4 · `29.719f` x4 · `2703.613f` x4 · `38.439f` x4 · `54.516f` x4 · `30.379f` x4 · `0.99f` x4 · `-3193.013f` x4 · `-41.399f` x4 · `0.3f` x2 · `523.982f` x2 · `167.7104f` x2 · `100.5962f` x2 · `1001.321f` x2 · `-2229.674f` x2 · `-48.033f` x2 · `-2965.821f` x2 · `481.63f` x2 · `-2965.71f` x2 · `484.219f` x2 · `-1215.386f` x2

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `ibs`, `typ`, `sprt`, `hclr`, `scl`, `rot`, `bsa`, `rad`, `hei_p_m_bag_var22_arm_s`, `DLC_HEI4/DLCHEI4_GENERIC_01`, `grab_gold`, `cart_cash_disappear`, `blp`, `veh`, `TYCSC_TIK_10`, `TYCSC_TIK_9`, `TYC_GEN_GOTO`, `TYCSS_HLP_2`, `exit`, `MAX_NUM_SCENARIOS`, `grp`, `TYCSC_TIK_4`

---

Source: `decompiled_scripts/fm_content_car_wash_work.c`
