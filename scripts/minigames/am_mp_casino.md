# am_mp_casino.c

Minigames script. 67 anim dicts; 200 models; 19 scaleforms; 3 particle effects.

| | |
|---|---|
| Category | Minigames |
| Total lines | 510,002 |
| Functions | 9,048 (899 unique, 8,149 shared) |
| Unique lines | 62,473 (12.2% of file) |

## Assets

**Animation dictionaries** (67) - `anim@amb@business@weed@weed_sorting_seated@`, `anim@amb@business@meth@meth_smash_weight_check@`, `anim@amb@business@cfm@cfm_cut_sheets@`, `ANIM@AMB@FACILITY@LAUNCH_CONTROLS@`, `anim@amb@range@load_clips@`, `anim@amb@business@coc@coc_unpack_cut@`, `anim@amb@business@cfid@cfid_desk_docs@`, `anim@amb@business@cfid@cfid_desk_id@`, `anim@amb@board_room@stenographer@computer@`, `anim@amb@board_room@supervising@`, `anim@amb@business@bgen@bgen_inspecting@`, `anim@amb@range@assemble_guns@`, `anim@amb@board_room@stenographer@paper@`, `anim@amb@business@coc@coc_packing_hi@`, `anim@amb@business@cfm@cfm_machine_oversee@`, `anim@amb@business@coc@coc_unpack_cut_left@`, `anim@amb@business@cfm@cfm_counting_notes@`, `anim@amb@business@coc@coc_packing@`, `anim@scripted@submarine@ig28_submarine_turret_control@heeled@`, `anim@scripted@submarine@ig28_submarine_turret_control@male@`, `anim@amb@business@weed@weed_inspecting_lo_med_hi@`, `anim@amb@board_room@diagram_blueprints@`, `anim@amb@business@cfm@cfm_drying_notes@`, `anim@amb@business@meth@meth_monitoring_no_work@`, `anim@amb@business@cfid@cfid_photograph@`, `anim@amb@business@bgen@bgen_no_work@`, `anim@amb@business@weed@weed_inspecting_high_dry@`, `anim@amb@board_room@whiteboard@`, `anim@amb@range@weapon_test@`, `ANIM@ARENA@AMB@SEAT_DRONE_TABLET@FEMALE@`, `ANIM@ARENA@AMB@SEAT_DRONE_TABLET@MALE@`, `anim@amb@business@meth@meth_monitoring_cooking@monitoring@`, `mp_safehousebeer@`, `anim@amb@business@cfid@cfid_desk_no_work_bgen_chair_no_work@`, `anim@amb@office@pa@male@`, `ANIM@AMB@OFFICE@PA@FEMALE@`, `anim@safehouse@whisky`, `anim@safehouse@bong`, `ANIM@AMB@OFFICE@PA@MALE@`, `anim@safehouse@wine`, `anim@amb@business@meth@meth_monitoring_cooking@cooking@`, `anim@amb@clubhouse@seating@male@var_a@base@`, `anim@amb@clubhouse@seating@female@var_a@base@`, `anim@amb@business@cfm@cfm_machine_no_work@`, `anim@amb@office@seating@male@var_a@base@`, `anim@amb@warehouse@laptop@`, `mini@repair`, `amb@world_human_hammering@male@idle_a`, `amb@world_human_smoking_pot@male@idle_a`, `amb@world_human_smoking_pot@female@idle_a`, `amb@world_human_leaning@female@smoke@idle_a`, `amb@world_human_stand_guard@male@idle_a`, `anim@amb@yacht@rail@standing@male@variant_01@`, `ANIM@AMB@NIGHTCLUB@MINI@DRINKING@CHAMPAGNE_DRINKING@BASE@`, `anim@scripted@player@fix_drink_juice@heeled@`, `anim@scripted@player@fix_drink_juice@male@`, `anim@safehouse@wheatgrass`, `anim@apt_trans@elevator`, `ANIM@SCRIPTED@FREEMODE@IG9_PLANT_EXPLOSIVE@HEELED@`, `ANIM@SCRIPTED@FREEMODE@IG9_PLANT_EXPLOSIVE@MALE@` ...

**Animations** (1) - `PA_BASE`

**Models and props** (200) - `v_ilev_garageliftdoor`, `prop_cs_beer_bot_01`, `vw_prop_casino_art_sculpture_01a`, `vw_prop_casino_art_mod_01a`, `vw_prop_casino_art_absman_01a`, `vw_prop_casino_art_ego_01a`, `p_whiskey_bottle_s`, `p_cs_lighter_01`, `vw_prop_casino_art_v_01a`, `vw_prop_casino_art_v_01b`, `vw_prop_casino_art_pill_01a`, `vw_prop_casino_art_pill_01c`, `vw_prop_casino_art_pill_01b`, `vw_prop_casino_art_vase_06a`, `vw_prop_casino_art_vase_07a`, `vw_prop_casino_art_vase_08a`, `vw_prop_casino_art_vase_09a`, `vw_prop_casino_art_lollipop_01a`, `vw_prop_casino_art_dog_01a`, `vw_prop_casino_art_mod_02a`, `vw_prop_flowers_vase_01a`, `vw_prop_flowers_vase_02a`, `vw_prop_flowers_vase_03a`, `vw_prop_flowers_potted_01a`, `ba_prop_battle_decanter_02_s`, `ba_prop_battle_decanter_03_s`, `s_m_y_dockwork_01`, `s_m_m_migrant_01`, `vw_prop_flowers_potted_02a`, `vw_prop_flowers_potted_03a`, `vw_prop_casino_keypad_01`, `w_ex_pe`, `vw_prop_art_wings_01a`, `hei_prop_heist_tumbler_empty`, `prop_bong_01`, `p_w_grass_gls_s`, `vw_prop_vw_luckywheel_02a`, `v_corp_bk_chair1`, `v_ret_ps_flowers_02`, `vw_prop_casino_art_guitar_01a`, `vw_prop_casino_art_sculpture_02b`, `ex_prop_offchair_exec_03`, `v_corp_offchair`, `ba_prop_battle_control_seat`, `ba_prop_battle_control_console`, `gr_prop_highendchair_gr_01a`, `gr_prop_gr_console_01`, `a_m_y_mexthug_01`, `s_m_m_dockwork_01`, `ch_prop_ch_diamond_xmastree`, `vw_prop_book_stack_01b`, `vw_prop_book_stack_01c`, `vw_prop_book_stack_02a`, `vw_prop_book_stack_02b`, `vw_prop_book_stack_02c`, `vw_prop_book_stack_03a`, `vw_prop_book_stack_03b`, `vw_prop_book_stack_03c`, `ch_prop_tree_01a`, `ch_prop_tree_02a` ...

**Audio banks** (7) - `SAFEHOUSE_TREVOR_DRINK_WHISKEY`, `DLC_VINEWOOD/CASINO_GENERAL`, `DLC_VINEWOOD/CASINO_SLOT_MACHINES_01`, `DLC_VINEWOOD/CASINO_SLOT_MACHINES_02`, `DLC_VINEWOOD/CASINO_SLOT_MACHINES_03`, `DLC_BATTLE/BTL_CHAMPAGNE_MINIGAME`, `DLC_HEI4/DLC_HEI4_Anims_Tequila`

**Sounds** (29) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `ERROR`, `SELECT`, `NAV_UP_DOWN`, `BACK`, `HUD_LIQUOR_STORE_SOUNDSET`, `NAV_LEFT_RIGHT`, `MP_PROPERTIES_ELEVATOR_DOORS`, `DLC_VW_Casino_General`, `CANCEL`, `HUD_FREEMODE_SOUNDSET`, `GTAO_VW_Casino_General_Allow_Gunfire_Scene`, `dlc_vw_table_games_frontend_sounds`, `DLC_VW_Casino_PA_Announcement_Scene`, `PURCHASE`, `DLC_VW_CONTINUE`, `Attach`, `GTAO_Bomb_Plant_Sounds`, `OK`, `DLC_VW_RULES`, `Inside_Track_Start`, `DLC_AW_Casino_Track_Inside_Game_Sounds`, `PICK_UP`, `FAKE_ARRIVE`, `BUTTON`, `OPENING`, `OPENED`, `CLOSED`, `CLOSING`

**Speech contexts** (2) - `CAS_PA`, `SPEECH_PARAMS_FORCE_NORMAL_CRITICAL`

**Scaleform movies** (19) - `SET_INPUT_EVENT`, `CLEAR_ALL_PLAYERS`, `GET_CURRENT_SELECTION`, `SET_BETTING_VALUES`, `SET_RACE_TYPE`, `SET_ANALOG_STICK_INPUT`, `GET_RACE_IS_COMPLETE`, `GET_HORSE_POSITIONS`, `ADD_PLAYER`, `SET_DETAIL_HORSE`, `START_RACE`, `SHOW_SCREEN`, `SET_PLAYER_RESULT`, `SET_HORSE`, `SET_COUNTDOWN`, `SHOW_ERROR`, `SET_BETTING_ENABLED`, `SET_MOUSE_INPUT`, `SET_MAIN_EVENT_IN_PROGRESS`

**Particle effects** (3) - `scr_ba_club`, `scr_ba_club_champagne_spray`, `fade`

**Texture dicts** (1) - `ShopUI_Title_Casino`

**Text labels** (19) - `READYIDLE`, `STRING`, `NULL`, `BUMP`, `CTOMAU`, `NUMBR`, `VFX`, `SALV23_FLOW_TCK0`, `ACTION`, `XM4R4AU`, `MP_SPINLOADING`, `BRSCRWTEX`, `EXCPAAU`, `ADMITTANCE`, `FAREWELL`, `WELCOME`, `CONCIERGE`, `BETTING`, `NONE`

**Interiors and entity sets** (4) - `rm_Elevator_01`, `rm_GamingFloor_01`, `rm_Manager`, `rm_Reception`

**Scripts launched** (9) - `AM_MP_SMOKING_ACTIVITY`, `AM_CASINO_PEDS`, `CASINO_LUCKY_WHEEL`, `CASINO_SLOTS`, `Three_Card_Poker`, `CasinoRoulette`, `Blackjack`, `casino_bar_seating`, `appInternet`

**Hashed names** (117) - `bkr_prop_meth_openbag_02`, `G_F_Y_Vagos_01`, `bkr_prop_weed_bud_02b`, `bkr_prop_fakeid_clipboard_01a`, `gr_prop_gr_3s_drillcrate_01a`, `prop_pencil_01`, `gr_prop_gr_2stackcrate_01a`, `bkr_prop_weed_dry_01a`, `bkr_prop_scrunched_moneypage`, `bkr_prop_weed_bud_02a`, `bkr_prop_fakeid_singledriverl`, `bkr_prop_cutter_moneystrip`, `gr_prop_GR_Chair02_ped`, `gr_prop_gr_3s_millcrate_01a`, `gr_prop_gr_millcage_01a`, `gr_prop_gr_drillcage_01a`, `bkr_prop_weed_chair_01a`, `bkr_prop_weed_leaf_01a`, `bkr_prop_weed_bucket_open_01a`, `bkr_prop_money_unsorted_01`, `bkr_prop_coke_fullscoop_01a`, `bkr_prop_coke_dollCast`, `prop_cs_credit_card`, `bkr_prop_coke_box_01a`, `gr_prop_gr_part_lathe_01a`, `bkr_prop_weed_bag_01a`, `bkr_prop_weed_bag_pile_01a`, `prop_npc_phone`, `bkr_prop_fakeid_penclipboard`, `bkr_Prop_Meth_SmashedTray_01_frag_`, `bkr_Prop_Meth_Tray_02a`, `bkr_prop_cutter_moneypage`, `bkr_prop_coke_fullmetalbowl_02`, `bkr_prop_coke_dollboxfolded`, `gr_prop_gr_crate_mag_01a`, `w_ar_carbineriflemk2_mag1`, `w_ar_assaultrifle`, `gr_prop_gr_part_mill_01a`, `gr_prop_gr_part_drill_01a`, `bkr_prop_fakeid_papercutter`, `bkr_prop_fakeid_table`, `bkr_prop_cutter_moneystack_01a`, `bkr_prop_meth_scoop_01a`, `bkr_prop_coke_scale_01`, `bkr_prop_meth_bigbag_04a`, `bkr_prop_meth_bigbag_03a`, `prop_off_chair_04_s`, `bkr_prop_weed_spray_01a`, `bkr_prop_money_wrapped_01`, `bkr_prop_coke_bakingsoda_o`, `AM_MP_SMOKING_ACTIVITY`, `A_F_Y_GenCasPat_01`, `SNK_ITEM1`, `SNK_ITEM2`, `SNK_ITEM3`, `SNK_ITEM4`, `SNK_ITEM5`, `SNK_ITEM7`, `SNK_ITEM6`, `xm_prop_x17_corp_offchair` ...

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (597), `PLAYER_PED_ID` (369), `SET_BIT` (333), `SET_PED_COMPONENT_VARIATION` (300), `GET_HASH_KEY` (293), `CLEAR_BIT` (233), `PLAY_SOUND_FRONTEND` (138), `DOES_ENTITY_EXIST` (102), `NETWORK_HAS_CONTROL_OF_ENTITY` (102), `GET_RANDOM_INT_IN_RANGE` (82), `GET_ENTITY_MODEL` (56), `NETWORK_REQUEST_CONTROL_OF_ENTITY` (53), `DISABLE_CONTROL_ACTION` (50), `CLEAR_HELP` (49), `IS_CONTROL_JUST_PRESSED` (47), `GET_NETWORK_TIME` (43), `TO_FLOAT` (43), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (38), `BEGIN_SCALEFORM_MOVIE_METHOD` (32), `GET_ENTITY_COORDS` (31), `GET_SYNCHRONIZED_SCENE_PHASE` (29), `SET_PED_CONFIG_FLAG` (29), `IS_PED_INJURED` (28), `NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE` (27), `NETWORK_IS_ACTIVITY_SESSION` (26), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (26), `NET_TO_PED` (22), `IS_ENTITY_IN_ANGLED_AREA` (20), `GET_GAME_TIMER` (20), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (19)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x14 · `0.01f` x11 · `0.5f` x9 · `0.25f` x8 · `0.1f` x8 · `-51.0409f` x6 · `-51.44085f` x6 · `-50.2005f` x6 · `267.6397f` x6 · `-52.041f` x6 · `-52.0408f` x5 · `1.25f` x5 · `-50.0408f` x4 · `0.96f` x4 · `1134.076f` x3 · `5.75f` x3 · `1096.867f` x3 · `0.9f` x3 · `1085.463f` x3 · `213.3851f` x3 · `1084.402f` x3 · `214.4458f` x3 · `1118.639f` x3 · `1120.139f` x3

## Other strings

Literals whose consuming native was not classified:

`AwakeState`, `scr_bike_business`, `weedInspecting`, `base`, `purchase`, `enter`, `scr_bike_coc_cocaine_scoop_pour`, `SA_BEER`, `SAFEHOUSE_FRANKLIN_DRINK_BEER`, `SAFEHOUSE_MICHAEL_DRINK_WHISKEY`, `SA_WHSKY`, `MPCT_PA_HELD`, `base_amy_skater_01`, `scr_bike_coc_cocaine_box_pour`, `CAS_MG_CBAN`, `Bartender_Outro_Bottle`, `vfx_meth_business_cocaine_scoop_pour_lh_start`, `vfx_meth_business_cocaine_scoop_pour_lh_stop`, `ITEM_SELECT`, `ITEM_BACK`, `SHR_MENU`, `mp_m_counterfeit_01`, `mp_m_meth_01`, `scr_bike_meth_meth_scoop_pour`, `vfx_meth_business_meth_pour_start`, `vfx_meth_business_meth_pour_stop`, `CAS_MG_MEMB2`, `OF_PA_MEN_VEHD3`

---

Source: `decompiled_scripts/am_mp_casino.c`
