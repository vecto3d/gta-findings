# fm_content_hacker_whistle_fin.c

Minigames script. 20 anim dicts; 18 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 517,200 |
| Functions | 11,052 (614 unique, 10,438 shared) |
| Unique lines | 14,355 (2.8% of file) |

## Assets

**Animation dictionaries** (20) - `move_m@bag`, `anim@heists@ornate_bank@grab_cash_heels`, `anim@heists@ornate_bank@grab_cash`, `ANIM@SCRIPTED@PLAYER@MISSION@TUN_TABLE_GRAB@CASH@HEELED@`, `anim@heists@ornate_bank@ig_4_grab_gold`, `ANIM@SCRIPTED@PLAYER@MISSION@TUN_TABLE_GRAB@CASH@`, `ANIM@SCRIPTED@PLAYER@MISSION@TUN_TABLE_GRAB@GOLD@HEELED@`, `ANIM@SCRIPTED@PLAYER@MISSION@TUN_TABLE_GRAB@GOLD@`, `anim@scripted@cbr1@ig1_washmach_grab_cash@heeled@`, `anim@scripted@cbr1@ig1_washmach_grab_cash@male@`, `ANIM_HEIST@HS3F@IG11_STEAL_PAINTING@MALE@`, `anim@heists@money_grab@duffel`, `anim@scripted@player@mission@tunf_bunk_ig2_hdd_nas@male@`, `anim@scripted@player@mission@tunf_bunk_ig2_hdd_nas@heeled@`, `anim_heist@hs3f@ig13_thermal_charge@thermal_charge@male@`, `anim_heist@hs3f@ig13_thermal_charge@thermal_charge@female@`, `anim@amb@warehouse@laptop@`, `anim@scripted@freemode@ig8_radio_car@male@`, `anim@scripted@freemode@ig8_radio_car@heeled@`, `anim@apt_trans@garage`

**Animations** (2) - `grab`, `exit`

**Models and props** (18) - `ch_prop_gold_bar_01a`, `imp_prop_impexp_coke_trolly`, `v_corp_banktrolley`, `prop_gold_vault_gate_01`, `imp_prop_impexp_coke_pile`, `ch_prop_vault_dimaondbox_01a`, `hei_prop_heist_cash_pile`, `hei_prop_hei_cash_trolly_01`, `prop_gold_trolly_full`, `hei_prop_heist_weed_block_01b`, `prop_cash_trolly`, `prop_gold_vault_fence_l`, `prop_gold_vault_fence_r`, `v_corp_cashtrolley_2`, `prop_box_wood07a`, `hei_prop_bh1_09_mp_gar2`, `v_ilev_fin_vaultdoor`, `v_ilev_fingate`

**Audio banks** (2) - `DLC_MPHEIST/HEIST_STASH_SWAG`, `DLC_HEI4/DLCHEI4_GENERIC_01`

**Sounds** (2) - `Garage_Door_Open`, `GTAO_Script_Doors_Faded_Screen_Sounds`

**Text labels** (9) - `CLEAR`, `HACK`, `LOOTED`, `NULL`, `RAIN`, `UNKNOWN`, `26GNL052`, `M4RSH4LL`, `VAULTDOOR`

**Scripts launched** (2) - `AM_MP_RC_VEHICLE`, `word_hack`

**Hashed names** (3) - `CASH_APPEAR`, `EXIT`, `AM_MP_RC_VEHICLE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (106), `NET_TO_OBJ` (32), `DOES_ENTITY_EXIST` (24), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (21), `GET_ENTITY_COORDS` (19), `HAS_MODEL_LOADED` (16), `SET_BIT` (15), `PLAYER_ID` (14), `NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE` (13), `GET_ENTITY_MODEL` (12), `NET_TO_ENT` (12), `FORCE_ENTITY_AI_AND_ANIMATION_UPDATE` (12), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (12), `GET_ENTITY_ROTATION` (11), `IS_SYNCHRONIZED_SCENE_RUNNING` (11), `IS_ENTITY_PLAYING_ANIM` (11), `REQUEST_MODEL` (11), `SET_MODEL_AS_NO_LONGER_NEEDED` (10), `NETWORK_DOES_NETWORK_ID_EXIST` (10), `SET_ENTITY_VISIBLE` (10), `DISABLE_CONTROL_ACTION` (10), `GET_SYNCHRONIZED_SCENE_PHASE` (9), `IS_USING_KEYBOARD_AND_MOUSE` (9), `NETWORK_CREATE_SYNCHRONISED_SCENE` (8), `NETWORK_START_SYNCHRONISED_SCENE` (8), `GET_HASH_KEY` (7), `REQUEST_SCRIPT_AUDIO_BANK` (7), `CLEAR_PED_TASKS` (7), `GET_NUM_RESERVED_MISSION_OBJECTS` (7), `RESERVE_LOCAL_NETWORK_MISSION_OBJECTS` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`16.7346f` x6 · `15.1306f` x3 · `15.13f` x3 · `8.0159f` x3 · `-662.7548f` x3 · `-660.8427f` x3 · `1.5f` x2 · `-9.3986f` x2 · `-682.3774f` x2 · `15.6023f` x2 · `2.7586f` x2 · `16.3586f` x2 · `1.25f` x1 · `0.34f` x1 · `0.99f` x1 · `0.25f` x1 · `-4.766f` x1 · `-666.725f` x1 · `10.212f` x1 · `-672.231f` x1 · `10.537f` x1 · `-671.173f` x1 · `3.5519f` x1 · `-677.454f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `typ`, `sprt`, `hclr`, `scl`, `ibs`, `bsa`, `hei_p_m_bag_var22_arm_s`, `grab_gold`, `cart_cash_disappear`, `blp`, `veh`, `rot`, `rad`, `exit`, `MAX_NUM_SCENARIOS`, `grp`, `**INVALID**`, `grab_dryer`, `grab_dryermoney`, `enter`, `h4_prop_h4_coke_stack_01a`, `h4_prop_h4_gold_stack_01a`

---

Source: `decompiled_scripts/fm_content_hacker_whistle_fin.c`
