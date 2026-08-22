# am_mp_casino_apartment.c

Minigames script. 86 anim dicts; 200 models; 2 scaleforms; 9 particle effects.

| | |
|---|---|
| Category | Minigames |
| Total lines | 527,035 |
| Functions | 9,134 (740 unique, 8,394 shared) |
| Unique lines | 59,866 (11.4% of file) |

## Assets

**Animation dictionaries** (86) - `anim@amb@business@weed@weed_sorting_seated@`, `anim@amb@business@meth@meth_smash_weight_check@`, `anim@amb@business@cfm@cfm_cut_sheets@`, `ANIM@AMB@FACILITY@LAUNCH_CONTROLS@`, `anim@amb@range@load_clips@`, `anim@amb@business@coc@coc_unpack_cut@`, `anim@amb@business@cfid@cfid_desk_docs@`, `anim@amb@business@cfid@cfid_desk_id@`, `anim@amb@board_room@stenographer@computer@`, `anim@amb@board_room@supervising@`, `anim@amb@business@bgen@bgen_inspecting@`, `anim@amb@range@assemble_guns@`, `anim@amb@board_room@stenographer@paper@`, `anim@amb@business@cfm@cfm_machine_oversee@`, `anim@amb@business@coc@coc_packing_hi@`, `anim@amb@business@coc@coc_unpack_cut_left@`, `anim@amb@business@cfm@cfm_counting_notes@`, `anim@scripted@submarine@ig28_submarine_turret_control@heeled@`, `anim@scripted@submarine@ig28_submarine_turret_control@male@`, `anim@amb@business@coc@coc_packing@`, `anim@amb@business@weed@weed_inspecting_lo_med_hi@`, `anim@amb@board_room@diagram_blueprints@`, `anim@amb@business@cfm@cfm_drying_notes@`, `anim@amb@business@meth@meth_monitoring_no_work@`, `anim@amb@business@bgen@bgen_no_work@`, `anim@amb@business@weed@weed_inspecting_high_dry@`, `anim@amb@business@cfid@cfid_photograph@`, `anim@amb@board_room@whiteboard@`, `anim@amb@range@weapon_test@`, `ANIM@ARENA@AMB@SEAT_DRONE_TABLET@FEMALE@`, `ANIM@ARENA@AMB@SEAT_DRONE_TABLET@MALE@`, `anim@amb@business@meth@meth_monitoring_cooking@monitoring@`, `mp_safehousebeer@`, `anim@amb@business@cfid@cfid_desk_no_work_bgen_chair_no_work@`, `anim@amb@office@pa@male@`, `anim@safehouse@whisky`, `anim@safehouse@bong`, `anim@safehouse@wine`, `anim@amb@business@meth@meth_monitoring_cooking@cooking@`, `anim@amb@clubhouse@seating@male@var_a@base@`, `anim@amb@clubhouse@seating@female@var_a@base@`, `anim@amb@business@cfm@cfm_machine_no_work@`, `anim@amb@office@seating@male@var_a@base@`, `ANIM@AMB@NIGHTCLUB@MINI@DRINKING@CHAMPAGNE_DRINKING@BASE@`, `anim@amb@warehouse@laptop@`, `mini@repair`, `amb@world_human_hammering@male@idle_a`, `amb@world_human_smoking_pot@male@idle_a`, `amb@world_human_smoking_pot@female@idle_a`, `amb@world_human_leaning@female@smoke@idle_a`, `amb@world_human_stand_guard@male@idle_a`, `anim@amb@yacht@rail@standing@male@variant_01@`, `anim@scripted@player@fix_drink_juice@heeled@`, `anim@scripted@player@fix_drink_juice@male@`, `anim@safehouse@wheatgrass`, `anim_heist@hs3f@ig12_change_clothes@`, `anim@apt_trans@elevator`, `anim@scripted@player@fix_agy_ig6_office_chair_entry@female@`, `anim@scripted@player@fix_agy_ig6_office_chair_entry@male@`, `anim@arena@amb@seating@seat_a@` ...

**Animations** (2) - `anim_heist@hs3f@ig12_change_clothes@`, `short_action_01_male`

**Models and props** (200) - `v_ilev_garageliftdoor`, `prop_cs_beer_bot_01`, `p_cs_lighter_01`, `p_whiskey_bottle_s`, `lux_prop_cigar_01_luxe`, `vw_prop_casino_art_sculpture_01a`, `vw_prop_casino_art_ego_01a`, `vw_prop_casino_art_mod_01a`, `vw_prop_casino_art_absman_01a`, `ex_prop_exec_lighter_01`, `ba_prop_battle_decanter_02_s`, `ba_prop_battle_decanter_03_s`, `vw_prop_vw_door_dd_01a`, `p_w_grass_gls_s`, `xs_prop_arena_showerdoor_s`, `vw_prop_vw_door_ddl_01a`, `lux_prop_ashtray_luxe_01`, `vw_prop_casino_art_v_01a`, `vw_prop_casino_art_v_01b`, `vw_prop_vw_door_lounge_01a`, `vw_prop_vw_door_slide_01a`, `prop_wine_bot_01`, `prop_wine_glass`, `p_pour_wine_s`, `vw_prop_vw_safedoor_office2a_r`, `vw_prop_casino_art_vase_07a`, `s_m_y_dockwork_01`, `s_m_m_migrant_01`, `vw_prop_vw_safedoor_office2a_l`, `vw_prop_casino_art_vase_09a`, `vw_prop_vw_trolly_01a`, `vw_prop_casino_art_pill_01a`, `vw_prop_casino_art_pill_01c`, `vw_prop_casino_art_pill_01b`, `vw_prop_flowers_vase_01a`, `vw_prop_flowers_vase_02a`, `vw_prop_flowers_vase_03a`, `vw_prop_flowers_potted_01a`, `vw_prop_flowers_potted_02a`, `vw_prop_flowers_potted_03a`, `vw_prop_casino_art_vase_06a`, `vw_prop_casino_art_vase_08a`, `vw_prop_casino_art_lollipop_01a`, `vw_prop_casino_art_dog_01a`, `vw_prop_casino_art_mod_02a`, `ex_prop_exec_ashtray_01`, `p_cs_shot_glass_2_s`, `ba_prop_battle_whiskey_opaque_s`, `hei_prop_heist_tumbler_empty`, `prop_bong_01`, `w_at_scope_large`, `w_sr_marksmanrifle_mag1`, `vw_prop_art_wings_01a`, `vw_prop_vw_tray_01a`, `ch_prop_swipe_card_01a`, `vw_prop_vw_door_bath_01a`, `ba_prop_battle_control_seat`, `ba_prop_battle_control_console`, `gr_prop_highendchair_gr_01a`, `gr_prop_gr_console_01` ...

**Audio banks** (8) - `DLC_VINEWOOD/CASINO_GENERAL`, `SAFEHOUSE_FRANKLIN_SOFA`, `SCRIPT/SAFEHOUSE_TREVOR_DRINK_WHISKEY`, `SAFEHOUSE_TREVOR_DRINK_WHISKEY`, `DLC_VINEWOOD/DLC_VW_AM_IP`, `DLC_VINEWOOD/DLC_VW_AM_TW`, `DLC_BATTLE/BTL_CHAMPAGNE_MINIGAME`, `DLC_HEI4/DLC_HEI4_Anims_Tequila`

**Sounds** (22) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `SELECT`, `ERROR`, `HUD_FREEMODE_SOUNDSET`, `NAV_UP_DOWN`, `MP_PROPERTIES_ELEVATOR_DOORS`, `DLC_VW_Casino_PH_Scene`, `NAV_LEFT_RIGHT`, `CANCEL`, `dlc_vw_am_cabinet_sounds`, `BACK`, `PICK_UP`, `dlc_vw_am_tw_in_use_scene`, `dlc_vw_am_ip_in_use_scene`, `Door_Open`, `DLC_AW_Arena_Spectator_Box_Access_Sounds`, `FAKE_ARRIVE`, `BUTTON`, `OPENING`, `OPENED`, `CLOSED`, `CLOSING`

**Scaleform movies** (2) - `FM_TWO_STRINGS`, `SET_VEHICLE_INFOR_AND_STATS`

**Particle effects** (9) - `scr_safehouse`, `scr_ba_club`, `scr_ba_club_champagne_spray`, `fade`, `scr_sh_lighter_sparks`, `scr_sh_lighter_flame`, `scr_sh_cig_smoke`, `scr_sh_cig_exhale_mouth`, `scr_sh_cig_exhale_nose`

**Texture dicts** (5) - `ShopUI_Title_Casino`, `MPCarHUD`, `MPCarHUD2`, `MPCarHUD3`, `MPCarHUD4`

**Text labels** (10) - `CLOSE`, `OPEN`, `NULL`, `STRING`, `VFX`, `WHOUSEINPUTTR`, `CTOMAU`, `NUMBR`, `CONCIERGE`, `BUMP`

**Decorators** (3) - `MPBitset`, `Player_Vehicle`, `Not_Allow_As_Saved_Veh`

**Interiors and entity sets** (5) - `Garage_Room`, `Apart_Off_Room`, `Apart_Lounge_Room`, `Apart_Default_Room`, `Apart_Bedroom_Room`

**Vehicle mods** (1) - `oppressor2`

**Scripts launched** (14) - `AM_PENTHOUSE_PEDS`, `AM_MP_BOARDROOM_SEATING`, `ob_mp_shower_med`, `AM_MP_SMOKING_ACTIVITY`, `casino_interior_seating`, `casino_main_lounge_seating`, `casino_penthouse_seating`, `Three_Card_Poker`, `Blackjack`, `appInternet`, `scroll_arcade_cabinet`, `grid_arcade_cabinet`, `appmpjoblistnew`, `appjipmp`

**Hashed names** (120) - `bkr_prop_meth_openbag_02`, `G_F_Y_Vagos_01`, `bkr_prop_weed_bud_02b`, `gr_prop_gr_3s_drillcrate_01a`, `bkr_prop_fakeid_clipboard_01a`, `prop_pencil_01`, `casino_interior_seating`, `casino_main_lounge_seating`, `gr_prop_gr_2stackcrate_01a`, `bkr_prop_weed_dry_01a`, `bkr_prop_scrunched_moneypage`, `bkr_prop_weed_bud_02a`, `bkr_prop_fakeid_singledriverl`, `bkr_prop_cutter_moneystrip`, `gr_prop_GR_Chair02_ped`, `gr_prop_gr_drillcage_01a`, `bkr_prop_weed_chair_01a`, `bkr_prop_weed_leaf_01a`, `bkr_prop_weed_bucket_open_01a`, `bkr_prop_money_unsorted_01`, `bkr_prop_coke_fullscoop_01a`, `bkr_prop_coke_dollCast`, `prop_cs_credit_card`, `bkr_prop_coke_box_01a`, `gr_prop_gr_3s_millcrate_01a`, `gr_prop_gr_millcage_01a`, `vw_Prop_garage_control_panel_01a`, `ng_proc_cigarette01a`, `vw_prop_vw_offchair_01`, `gr_prop_gr_part_lathe_01a`, `bkr_prop_weed_bag_01a`, `bkr_prop_weed_bag_pile_01a`, `prop_npc_phone`, `bkr_prop_fakeid_penclipboard`, `bkr_Prop_Meth_SmashedTray_01_frag_`, `bkr_Prop_Meth_Tray_02a`, `bkr_prop_cutter_moneypage`, `bkr_prop_coke_fullmetalbowl_02`, `bkr_prop_coke_dollboxfolded`, `Three_Card_Poker`, `Blackjack`, `sm_Prop_Smug_Wall_Radio_01`, `AM_MP_BOARDROOM_SEATING`, `ob_mp_shower_med`, `vfx_xs_cig_smoke_exhale`, `w_ar_assaultrifle`, `gr_prop_gr_part_drill_01a`, `bkr_prop_fakeid_papercutter`, `bkr_prop_fakeid_table`, `bkr_prop_cutter_moneystack_01a`, `bkr_prop_meth_scoop_01a`, `bkr_prop_coke_scale_01`, `bkr_prop_meth_bigbag_04a`, `bkr_prop_meth_bigbag_03a`, `prop_off_chair_04_s`, `bkr_prop_weed_spray_01a`, `bkr_prop_money_wrapped_01`, `bkr_prop_coke_bakingsoda_o`, `gr_prop_gr_crate_mag_01a`, `w_ar_carbineriflemk2_mag1` ...

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (611), `PLAYER_PED_ID` (453), `SET_BIT` (329), `GET_HASH_KEY` (310), `CLEAR_BIT` (285), `DOES_ENTITY_EXIST` (131), `NETWORK_HAS_CONTROL_OF_ENTITY` (111), `PLAY_SOUND_FRONTEND` (81), `SET_MODEL_AS_NO_LONGER_NEEDED` (59), `REQUEST_MODEL` (56), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (56), `NETWORK_REQUEST_CONTROL_OF_ENTITY` (56), `HAS_MODEL_LOADED` (54), `NET_TO_VEH` (43), `FREEZE_ENTITY_POSITION` (42), `NETWORK_REQUEST_CONTROL_OF_NETWORK_ID` (39), `SET_ENTITY_VISIBLE` (39), `DISABLE_CONTROL_ACTION` (37), `IS_SYNCHRONIZED_SCENE_RUNNING` (36), `GET_RANDOM_INT_IN_RANGE` (35), `GET_NETWORK_TIME` (34), `NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE` (33), `HAS_ANIM_DICT_LOADED` (31), `SET_PED_CONFIG_FLAG` (30), `IS_ENTITY_IN_ANGLED_AREA` (30), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (30), `INT_TO_PLAYERINDEX` (29), `GET_SYNCHRONIZED_SCENE_PHASE` (29), `GET_PLAYER_PED` (28), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (28)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x14 · `115.1641f` x14 · `0.01f` x13 · `0.5f` x12 · `-50.0574f` x10 · `1.5f` x10 · `115.1642f` x7 · `219.0372f` x6 · `-50.061f` x6 · `263.1108f` x6 · `116.36f` x6 · `0.25f` x5 · `0.05f` x5 · `0.75f` x5 · `0.96f` x5 · `117.4142f` x5 · `1.75f` x5 · `2.5f` x4 · `116.2144f` x4 · `0.8f` x4 · `-1.5f` x4 · `972.8148f` x4 · `40.34948f` x4 · `973.9166f` x4

## Other strings

Literals whose consuming native was not classified:

`Apart_Lounge_Room`, `AwakeState`, `scr_bike_business`, `Apart_Off_Room`, `Apart_Entry_Room`, `weedInspecting`, `Apart_Default_Room`, `enter`, `base`, `Apart_Cin_Room`, `Apart_Spare_Room`, `Apart_Bedroom_Room`, `Apart_Din_Room`, `scr_bike_coc_cocaine_scoop_pour`, `Apart_Arcade_Room`, `SA_BEER`, `SAFEHOUSE_FRANKLIN_DRINK_BEER`, `SAFEHOUSE_MICHAEL_DRINK_WHISKEY`, `CT_CHANGE_WAIT`, `exit`, `SA_WHSKY`, `lux_prop_cigar_01_luxe`, `base_amy_skater_01`, `scr_bike_coc_cocaine_box_pour`, `Bartender_Outro_Bottle`, `Apart_Spa_Room`, `idle_c`, `vfx_meth_business_cocaine_scoop_pour_lh_start`

---

Source: `decompiled_scripts/am_mp_casino_apartment.c`
