# net_apartment_activity_light.c

Properties and venues script. 64 anim dicts; 21 models.

| | |
|---|---|
| Category | Properties and venues |
| Total lines | 379,666 |
| Functions | 6,979 (339 unique, 6,640 shared) |
| Unique lines | 24,219 (6.4% of file) |

## Assets

**Animation dictionaries** (64) - `ANIM@AMB@FACILITY@LAUNCH_CONTROLS@`, `anim@amb@board_room@stenographer@computer@`, `anim@amb@machinery@lathe@`, `anim@amb@business@weed@weed_sorting_seated@`, `anim@amb@board_room@supervising@`, `anim@amb@business@weed@weed_inspecting_lo_med_hi@`, `anim@amb@machinery@vertical_mill@`, `anim@amb@machinery@speed_drill@`, `anim@amb@business@bgen@bgen_inspecting@`, `anim@scripted@submarine@ig28_submarine_turret_control@heeled@`, `anim@scripted@submarine@ig28_submarine_turret_control@male@`, `anim@amb@range@load_clips@`, `anim@amb@board_room@diagram_blueprints@`, `anim@amb@range@assemble_guns@`, `anim@amb@board_room@stenographer@paper@`, `anim@amb@business@cfid@cfid_desk_docs@`, `anim@amb@business@bgen@bgen_no_work@`, `anim@amb@board_room@whiteboard@`, `anim@amb@business@meth@meth_smash_weight_check@`, `anim@amb@business@meth@meth_monitoring_no_work@`, `anim@amb@business@cfm@cfm_cut_sheets@`, `ANIM@ARENA@AMB@SEAT_DRONE_TABLET@FEMALE@`, `ANIM@ARENA@AMB@SEAT_DRONE_TABLET@MALE@`, `mp_safehousebeer@`, `anim@amb@business@cfm@cfm_machine_oversee@`, `anim@amb@business@cfm@cfm_drying_notes@`, `anim@amb@business@coc@coc_packing@`, `anim@amb@business@coc@coc_unpack_cut_left@`, `anim@amb@business@weed@weed_inspecting_high_dry@`, `anim@amb@business@cfid@cfid_desk_id@`, `anim@amb@business@cfid@cfid_photograph@`, `anim@amb@business@cfm@cfm_counting_notes@`, `anim@amb@office@pa@male@`, `anim@amb@business@meth@meth_monitoring_cooking@monitoring@`, `anim@amb@business@coc@coc_unpack_cut@`, `anim@amb@range@weapon_test@`, `anim@amb@business@cfid@cfid_desk_no_work_bgen_chair_no_work@`, `anim@amb@business@coc@coc_packing_hi@`, `anim@safehouse@bong`, `anim@safehouse@whisky`, `anim@amb@clubhouse@seating@male@var_a@base@`, `anim@amb@clubhouse@seating@female@var_a@base@`, `anim@amb@business@cfm@cfm_machine_no_work@`, `anim@amb@office@seating@male@var_a@base@`, `anim@amb@warehouse@laptop@`, `amb@world_human_aa_coffee@idle_a`, `mini@repair`, `amb@world_human_hammering@male@idle_a`, `amb@world_human_smoking_pot@male@idle_a`, `amb@world_human_smoking_pot@female@idle_a`, `amb@world_human_leaning@female@smoke@idle_a`, `amb@world_human_stand_guard@male@idle_a`, `anim@amb@yacht@rail@standing@male@variant_01@`, `anim@safehouse@wine`, `anim@scripted@player@fix_drink_juice@heeled@`, `anim@scripted@player@fix_drink_juice@male@`, `anim@safehouse@wheatgrass`, `anim@amb@business@meth@meth_monitoring_cooking@cooking@`, `mini@strip_club@throwout_d@`, `amb@world_human_hammering@male@base` ...

**Animations** (7) - `mp_doorbell`, `ring_bell_a`, `throwout_d_bouncer_a`, `throwout_d_bouncer_b`, `throwout_d_victim`, `anim@amb@warehouse@laptop@`, `enter`

**Models and props** (21) - `prop_cs_beer_bot_01`, `p_whiskey_bottle_s`, `ba_prop_battle_decanter_02_s`, `ba_prop_battle_decanter_03_s`, `s_m_y_dockwork_01`, `s_m_m_migrant_01`, `prop_bong_01`, `p_w_grass_gls_s`, `ba_prop_battle_control_seat`, `gr_prop_highendchair_gr_01a`, `a_m_y_mexthug_01`, `s_m_m_dockwork_01`, `s_m_y_clubbar_01`, `s_m_m_bouncer_01`, `prop_wine_bot_01`, `ba_prop_battle_decanter_01_s`, `sf_prop_sf_bong_01a`, `hei_prop_dlc_tablet`, `s_m_m_cntrybar_01`, `s_f_m_sweatshop_01`, `s_m_y_construct_01`

**Text labels** (1) - `NULL`

**Hashed names** (32) - `gr_prop_gr_drillcage_01a`, `gr_prop_gr_millcage_01a`, `G_F_Y_Vagos_01`, `prop_pencil_01`, `gr_prop_gr_3s_drillcrate_01a`, `gr_prop_GR_Chair02_ped`, `gr_prop_gr_2stackcrate_01a`, `bkr_prop_weed_dry_01a`, `prop_npc_phone`, `gr_prop_gr_3s_millcrate_01a`, `bkr_prop_fakeid_papercutter`, `bkr_prop_fakeid_clipboard_01a`, `bkr_prop_weed_spray_01a`, `bkr_prop_coke_bakingsoda_o`, `xm_prop_x17_corp_offchair`, `gr_prop_gr_bulletscrate_01a`, `prop_mug_04`, `TAILGATER`, `bkr_prop_weed_chair_01a`, `p_loose_rag_01_s`, `bkr_prop_meth_scoop_01a`, `w_me_hammer`, `bkr_prop_meth_sacid`, `bkr_prop_fakeid_openpassport`, `prop_ing_camera_01`, `close_inspection_ruler`, `mp_m_weed_01`, `bkr_prop_money_pokerbucket`, `bkr_prop_clubhouse_chair_01`, `bkr_prop_scrunched_moneypage`, `bkr_prop_coke_fullscoop_01a`, `bkr_prop_coke_fullmetalbowl_02`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (106), `PLAYER_ID` (100), `GET_HASH_KEY` (99), `IS_ENTITY_DEAD` (48), `GET_ENTITY_MODEL` (33), `DOES_ENTITY_EXIST` (26), `GET_RANDOM_INT_IN_RANGE` (22), `IS_STRING_NULL_OR_EMPTY` (17), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (17), `GET_SYNCHRONIZED_SCENE_PHASE` (15), `IS_SYNCHRONIZED_SCENE_RUNNING` (10), `SET_BIT` (9), `IS_ENTITY_PLAYING_ANIM` (7), `HAS_ANIM_EVENT_FIRED` (7), `CLEAR_HELP` (6), `FREEZE_ENTITY_POSITION` (6), `SET_PED_COMPONENT_VARIATION` (6), `GET_PLAYER_PED` (6), `GET_INTERIOR_FROM_ENTITY` (6), `USE_PARTICLE_FX_ASSET` (5), `GET_ENTITY_COORDS` (4), `TASK_SYNCHRONIZED_SCENE` (4), `REQUEST_ANIM_DICT` (4), `HAS_ANIM_DICT_LOADED` (4), `DISABLE_CONTROL_ACTION` (4), `ABSI` (4), `IS_SCREEN_FADED_OUT` (3), `TERMINATE_THIS_THREAD` (3), `IS_VALID_INTERIOR` (3), `NETWORK_HAS_CONTROL_OF_ENTITY` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.3f` x4 · `92.60599f` x2 · `275.8115f` x2 · `0.01f` x1 · `0.8f` x1 · `0.5f` x1 · `3.96051f` x1 · `175.4051f` x1 · `227.3487f` x1

## Other strings

Literals whose consuming native was not classified:

`AwakeState`, `scr_bike_business`, `base`, `enter`, `SAFEHOUSE_FRANKLIN_DRINK_BEER`, `SA_BEER`, `SAFEHOUSE_MICHAEL_DRINK_WHISKEY`, `SA_WHSKY`, `base_amy_skater_01`, `scr_bike_coc_cocaine_box_pour`, `idle_a`, `mp_m_counterfeit_01`, `mp_m_meth_01`, `SA_BONG2`, `MPYACHT_LEAN`, `enter_left`, `enter_left_chair`, `base_chair`, `COMPUTER_enter`, `COMPUTER_enter_chair`, `COMPUTER_idle`, `COMPUTER_idle_chair`, `COMPUTER_exit`, `COMPUTER_exit_chair`, `idle_b`, `idle_c`, `vfx_weed_business_spraybottle_spray`, `scr_bike_spraybottle_spray`, `SAFEHOUSE_MICHAEL_USE_BONG`, `mp_m_cocaine_01`

---

Source: `decompiled_scripts/net_apartment_activity_light.c`
