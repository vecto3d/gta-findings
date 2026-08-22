# gunclub_shop.c

Shops script. 3 anim dicts; 42 models; 2 scaleforms.

| | |
|---|---|
| Category | Shops |
| Total lines | 191,191 |
| Functions | 1,495 (317 unique, 1,178 shared) |
| Unique lines | 61,808 (32.3% of file) |

## Assets

**Animation dictionaries** (3) - `ANIM@SCRIPTED@FREEMODE_NPC@FIX_AGY_IG2_REQUISITIONS@`, `ANIM@SCRIPTED@NPC@FREEMODE@IG2_GUN_SHOP@`, `random@shop_gunstore`

**Animations** (9) - `_idle`, `_idle_a`, `_positive_goodbye`, `_impatient_a`, `_impatient_b`, `_positive_a`, `_greeting`, `_neutral_to_idle`, `_idle_b`

**Models and props** (42) - `prop_ld_test_01`, `v_lirg_gunlight`, `hei_prop_heist_off_chair`, `w_pi_pistol`, `sf_prop_sf_cleaning_pad_01a`, `prop_armour_pickup`, `prop_bodyarmour_02`, `prop_bodyarmour_03`, `prop_bodyarmour_04`, `prop_bodyarmour_05`, `p_parachute_s_shop`, `prop_w_me_knife_01`, `prop_w_me_bottle`, `prop_w_me_dagger`, `prop_w_me_hatchet`, `v_ilev_gc_weapons`, `v_ilev_gc_handguns`, `p_parachute_s`, `v_7_wallhooks`, `v_22_wallhooks`, `v_ilev_gc_grenades`, `prop_box_ammo07b`, `v_ret_gc_calc`, `v_ret_gc_mags`, `v_7_wallguns`, `v_22_wallguns`, `s_m_y_ammucity_01`, `hei_prop_heist_binbag`, `v_ilev_gunsign_pistol50`, `v_ilev_gunsign_asssmg`, `v_ilev_gunsign_assmg`, `v_ilev_gunsign_bull`, `v_ilev_gunsign_asssniper`, `v_ilev_gunsign_progar`, `bkr_prop_grenades_02`, `ch_prop_board_wpnwall_01a`, `ch_prop_board_wpnwall_02a`, `xm3_prop_xm3_crate_ammo_01a`, `ig_req_officer`, `s_m_m_ammucountry`, `ig_gunvanseller`, `prop_npc_phone_02`

**Audio banks** (1) - `HUD_AMMO_SHOP`

**Sounds** (25) - `HUD_AMMO_SHOP_SOUNDSET`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `SELECT`, `CANCEL`, `NAV_UP_DOWN`, `BACK`, `NAV`, `WEAPON_PURCHASE`, `ERROR`, `WEAPON_SELECT_OTHER`, `WEAPON_AMMO_PURCHASE`, `WEAPON_ATTACHMENT_EQUIP`, `WEAPON_ATTACHMENT_UNEQUIP`, `Weapon_Upgrade`, `DLC_GR_Weapon_Upgrade_Soundset`, `WEAPON_SELECT_HANDGUN`, `WEAPON_SELECT_SHOTGUN`, `WEAPON_SELECT_RIFLE`, `WEAPON_SELECT_GRENADE_LAUNCHER`, `WEAPON_SELECT_RPG_LAUNCHER`, `WEAPON_SELECT_KNIFE`, `WEAPON_SELECT_PARACHUTE`, `WEAPON_SELECT_FUEL_CAN`, `WEAPON_SELECT_BATON`, `WEAPON_SELECT_ARMOR`

**Speech contexts** (78) - `SPEECH_PARAMS_FORCE`, `WEPSEXP`, `WEPSEXPERT_UPGRDSHOPGEN`, `SHOP_BROWSE_FRANKLIN`, `SHOP_BROWSE_TREVOR`, `COMMENT_FRANKLIN`, `COMMENT_LAMAR`, `COMMENT_CHOP`, `COMMENT_IMANI`, `MELVIN`, `S_M_M_AMMUCOUNTRY_WHITE_MINI_01`, `FIX_WEAPONS1`, `AMMUCITY`, `S_M_Y_AMMUCITY_01_WHITE_MINI_01`, `SHOP_GREET_MICHAEL`, `SHOP_GREET_FRANKLIN`, `SHOP_GREET_TREVOR`, `SHOP_GREET`, `SHOP_SHOOTING`, `SHOP_NO_WEAPON`, `SHOP_BANTER_FRANKLIN`, `SHOP_BANTER_TREVOR`, `SHOP_BANTER`, `SHOP_BROWSE_MELEE`, `SHOP_BROWSE_GUN`, `SHOP_BROWSE`, `SHOP_BROWSE_THROWN`, `SHOP_BROWSE_BIG`, `SHOP_BROWSE_ARMOUR`, `SHOP_SELL`, `SHOP_OUT_OF_STOCK`, `SHOP_GOODBYE`, `SHOP_NO_COPS`, `SHOP_REMOVE_VEHICLE`, `WEPSEXPERT_GREETSHOPGEN`, `WEPSEXPERT_GREETGUNMOD`, `WEPSEXPERT_QUESTSHOPGEN`, `WEPSEXPERT_QUESTGUNMOD`, `WEPSEXPERT_BASEUPGUNMOD`, `WEPSEXPERT_BYESHOPGEN`, `WEPSEXPERT_BYECGUNMOD`, `WEPSEXPERT_ATTCHGUNMOD`, `WEPSEXPERT_APPGUNMOD`, `WEPSEXPERT_AMMOGUNMOD`, `WEPSEXPERT_IDLESHOPGEN`, `WEPSEXPERT_OGREETTRUCK`, `WEPSEXPERT_MGREETTRUCK`, `WEPSEXPERT_IDLETRUCK`, `WEPSEXPERT_MODWEPTRUCK`, `WEPSEXPERT_NEWMODWEPTRUCK`, `WEPSEXPERT_BYETRUCK`, `WEPSEXPERT_BUMPTRUCK`, `SHOP_GREET_SPECIAL`, `SHOP_SPECIAL_DISCOUNT`, `BYE_OWNER`, `BYE_OTHER_PLAYER`, `OPEN_MENU`, `MENU_IDLE`, `WEAPON_AMMO`, `WEAPON_ATTACHMENT` ...

**Scaleform movies** (2) - `MP_BIG_MESSAGE_FREEMODE`, `SHOW_WEAPON_PURCHASED`

**Text labels** (24) - `TINT`, `STRING`, `AMMUCITY`, `NULL`, `WEAPON`, `GUNKEEPER`, `AMMUCOUNTRY`, `31EVL500`, `FRANKLIN`, `MELVIN`, `TREVOR`, `WEPSEXP`, `GNRWEAU`, `IDLE`, `MELEE`, `PISTOL`, `RIFLE`, `SHOTGUN`, `SNIPER`, `EXPLOSIVE`, `PM_DAMAGE`, `PM_FIRERATE`, `PM_ACCURACY`, `PM_RANGE`

**Relationship groups** (1) - `SHOPKEEPER_GUN_VAN`

**Stats** (174) - `sp0_parachute_current_tint`, `sp1_parachute_current_tint`, `sp2_parachute_current_tint`, `sp1_weap_purch_1`, `sp1_weap_purch_2`, `sp2_weap_purch_2`, `sp0_weap_addon_view_6`, `sp1_weap_addon_view_6`, `sp2_weap_addon_view_6`, `sp0_weap_tint_purch_1`, `sp1_weap_tint_purch_1`, `sp2_weap_tint_purch_7`, `sp0_weap_tint_purch_12`, `sp1_weap_tint_purch_12`, `sp2_weap_tint_purch_12`, `sp2_weap_addon_view_3`, `sp0_sp_money_spent_on_weapons`, `sp1_sp_money_spent_on_weapons`, `sp2_sp_money_spent_on_weapons`, `sp0_weap_addon_purch_0`, `sp1_weap_addon_purch_0`, `sp2_weap_addon_purch_0`, `sp0_weap_addon_purch_1`, `sp1_weap_addon_purch_1`, `sp2_weap_addon_purch_1`, `sp0_weap_addon_purch_2`, `sp1_weap_addon_purch_2`, `sp2_weap_addon_purch_2`, `sp0_weap_addon_purch_3`, `sp1_weap_addon_purch_3`, `sp2_weap_addon_purch_3`, `sp0_weap_addon_purch_4`, `sp1_weap_addon_purch_4`, `sp2_weap_addon_purch_4`, `sp0_weap_addon_purch_5`, `sp1_weap_addon_purch_5`, `sp2_weap_addon_purch_5`, `sp0_weap_addon_purch_6`, `sp1_weap_addon_purch_6`, `sp2_weap_addon_purch_6`, `sp0_weap_purch_0`, `sp1_weap_purch_0`, `sp2_weap_purch_0`, `sp0_weap_purch_1`, `sp2_weap_purch_1`, `sp0_weap_purch_2`, `sp1_weap_addon_view_2`, `sp2_weap_addon_view_2`, `sp0_weap_addon_view_4`, `sp1_weap_addon_view_4`, `sp2_weap_addon_view_4`, `sp0_weap_view_0`, `sp1_weap_view_0`, `sp2_weap_view_0`, `sp0_weap_view_1`, `sp1_weap_view_1`, `sp2_weap_view_1`, `sp0_weap_view_2`, `sp1_weap_view_2`, `sp2_weap_view_2` ...

**Scripts launched** (2) - `lamar1`, `trevor2`

**Hashed names** (20) - `v_gun2`, `V_22_GunShopRm`, `v_gun`, `gr_grdlc_int_01`, `ba_dlc_int_03_ba`, `xs_x18_int_mod`, `ch_dlc_plan`, `h4_int_sub_h4`, `sf_dlc_office_sec`, `xm3_dlc_int_03_xm3`, `sm_smugdlc_int_01`, `m24_2_int_hacker_basement`, `m25_2_int_mansion_2`, `WCT_KNUCK_01`, `V_7_GunShopRm`, `room_office_hacker`, `GSM_TINT_CASH`, `GSM_TINT_KILL`, `V_7_ShootRm`, `Weapons`

## Native vocabulary

Most-called natives inside the code unique to this script:

`NETWORK_IS_GAME_IN_PROGRESS` (470), `SET_BIT` (449), `PLAYER_PED_ID` (344), `TO_FLOAT` (222), `CLEAR_BIT` (217), `GET_HASH_KEY` (216), `PLAYER_ID` (202), `FLOOR` (184), `STAT_SET_INT` (177), `STAT_GET_INT` (165), `DOES_ENTITY_EXIST` (69), `GET_RANDOM_INT_IN_RANGE` (67), `PLAY_PED_AMBIENT_SPEECH_NATIVE` (57), `GET_GAME_TIMER` (56), `PLAY_SOUND_FRONTEND` (55), `GET_NETWORK_TIME` (52), `HAS_PED_GOT_WEAPON` (51), `SET_PED_COMPONENT_VARIATION` (46), `IS_CONTROL_PRESSED` (41), `ROUND` (41), `SET_MOUSE_CURSOR_STYLE` (41), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (40), `GET_ENTITY_MODEL` (39), `IS_PED_INJURED` (33), `GET_WEAPON_COMPONENT_TYPE_MODEL` (30), `GET_TIME_OFFSET` (28), `NET_TO_OBJ` (25), `HAS_WEAPON_GOT_WEAPON_COMPONENT` (23), `PLAY_PED_AMBIENT_SPEECH_WITH_VOICE_NATIVE` (23), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (22)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.13f` x194 · `0.475f` x111 · `-0.755f` x71 · `-0.4f` x58 · `0.95f` x55 · `0.85f` x48 · `47.3919f` x35 · `0.02f` x30 · `0.03f` x25 · `0.5f` x24 · `-70.1585f` x24 · `-405.1899f` x24 · `559.6697f` x24 · `-79.51f` x24 · `-3015.85f` x24 · `-1422.9f` x24 · `0.96f` x24 · `-89.06f` x24 · `5200.17f` x24 · `203.065f` x24 · `-55.62f` x24 · `-354.37f` x24 · `2715.03f` x24 · `-56.4789f` x24

## Other strings

Literals whose consuming native was not classified:

`gun_root`, `WAPClip`, `component_gunrun_mk2_upgrade`, `component_at_ar_flsh`, `WAPSupp`, `WAPScop`, `PD_CONTENT_9`, `component_at_ar_afgrip`, `AMMO_PISTOL`, `WAPFlshLasr`, `gadget_parachute`, `component_at_ar_supp`, `PS_BAG_0`, `component_at_ar_supp_02`, `WAPSupp_2`, `WAPGrip`, `component_at_scope_medium`, `component_at_sights`, `component_at_pi_flsh`, `WCD_MK1_LOCK`, `WAPScop_2`, `AMMO_SHOTGUN`, `component_at_muzzle_01`, `component_at_muzzle_02`, `component_at_muzzle_03`, `component_at_muzzle_04`, `component_at_muzzle_05`, `component_at_muzzle_06`, `component_at_muzzle_07`, `AMMO_RIFLE`

---

Source: `decompiled_scripts/gunclub_shop.c`
