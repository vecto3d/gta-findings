# am_pi_menu.c

UI and menus script. 4 anim dicts; 17 models; 18 scaleforms.

| | |
|---|---|
| Category | UI and menus |
| Total lines | 620,867 |
| Functions | 9,438 (1,221 unique, 8,217 shared) |
| Unique lines | 110,027 (17.7% of file) |

## Assets

**Animation dictionaries** (4) - `anim@apt_trans@hinge_l`, `anim@apt_trans@hinge_r`, `MP_WEAPON_DROP`, `anim@apt_trans@garage`

**Animations** (2) - `MP_WEAPON_DROP`, `DROP_LH`

**Models and props** (17) - `prop_damdoor_01`, `prop_choc_pq`, `BA_PROP_BLIP`, `prop_money_bag_01`, `prop_choc_ego`, `prop_choc_meto`, `prop_ecola_can`, `prop_amb_beer_bottle`, `prop_ld_can_01b`, `prop_cs_ciggy_01`, `prop_paper_bag_01`, `PROP_MAZ_D`, `PROP_PAL_D`, `PROP_CHAP_D`, `PROP_SEN_D`, `PROP_VITA_D`, `PROP_EXCEP_D`

**Sounds** (8) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `BACK`, `CANCEL`, `SELECT`, `NAV_UP_DOWN`, `NAV_LEFT_RIGHT`, `Apt_Style_Purchase`, `DLC_APT_Apartment_SoundSet`

**Scaleform movies** (18) - `SET_INPUT_EVENT`, `SET_ANALOG_STICK_INPUT`, `SET_DATA_SLOT`, `ADD_ITEM`, `CLEAR_ALL`, `OVERRIDE_RESPAWN_TEXT`, `SET_MOUSE_INPUT`, `GET_CURRENT_ITEM`, `GET_CURRENT_SCREEN`, `MP_MENU_GLARE`, `SET_MAX_WIDTH`, `TOGGLE_MOUSE_BUTTONS`, `SET_BACKGROUND_COLOUR`, `DRAW_INSTRUCTIONAL_BUTTONS`, `GET_CURRENT_ROLLOVER`, `CELL_EMAIL_SUBJ`, `STARTER_PACK_BROWSER`, `PURCHASE_BUTTONS_VISIBLE`

**Texture dicts** (2) - `MPInteraction`, `VW_COLLECT`

**Text labels** (83) - `PEGASUS`, `NUMBER`, `STRING`, `PIM`, `NUMBR`, `CARDS`, `OFF`, `QUCKGPSBARRA`, `BODHI2`, `NONE`, `BUZZARD2`, `PIMNCLDANSTY`, `PIMNCLDANPAR`, `DLOADER`, `FIGURINES`, `PIMNOWEEKCHA1`, `PIMNOWEEKCHA2`, `IFRUITRADIO`, `PIMNCLCROSTY`, `NULL`, `INVALID`, `PIMCOUNTERTIT`, `IESTEALVEHHUD`, `GRTRUCK`, `PIMRIVTR`, `DOCKSEXQGPS`, `QGPGUNVAN0`, `LIMO2`, `BALLER6`, `BUZZARD`, `COGNOSCENTI2`, `DINGHY3`, `VOLATUS`, `SCHAFTER6`, `BJXL`, `WASHINGTON`, `STRETCH`, `PATRIOT`, `SUPERD`, `SUPERVOLITO`, `SANCHEZ2`, `SLAMVAN`, `BFINJECTION`, `MOONBEAM`, `DUBSTA2`, `SANCHEZ`, `HAVOK`, `GSA`, `USBMIXHELPNO`, `USBMIXHELP`, `USBMIXHELP7`, `PIMCSACKBLOCK`, `ANIMALPHOHEL`, `TAGGINPIMHELP`, `LUCKCHHELPCOL`, `PIMNCLCROSTYD`, ` GEAR`, ` HATS`, ` MASKS`, ` GLASSES` ...

**Decorators** (2) - `Player_Goon`, `Player_Boss`

**Vehicle mods** (2) - `trailersmall2`, `oppressor2`

**Scripts launched** (30) - `gb_ploughed`, `heli_gun`, `gb_stockpiling`, `gb_fully_loaded`, `gb_amphibious_assault`, `gb_transporter`, `gb_fortified`, `gb_ramped_up`, `am_heli_taxi`, `am_king_of_the_castle`, `gb_salvage`, `gb_biker_bad_deal`, `gb_vehicle_export`, `appinternet`, `gb_velocity`, `am_hot_property`, `am_kill_list`, `am_pass_the_parcel`, `gb_rob_shop`, `gb_airfreight`, `gb_cashing_out`, `appInternet`, `gb_finderskeepers`, `gb_biker_search_and_destroy`, `mg_race_to_point`, `am_hot_target`, `fm_mission_creator`, `gb_biker_target_rival`, `am_mp_property_int`, `am_mp_yacht`

**Hashed names** (15) - `YachtRm_Bridge`, `PIM`, `HIDE`, `PREV`, `BothArms_filter`, `torsoDecal`, `v_39_ShopRm`, `v_39_StairsRm`, `v_66_ShopRm`, `v_66_BackRm`, `liquor_front`, `liquor_back`, `v_68_GasRm`, `v_68_BackRm`, `v_68_Toilets`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (3052), `PLAYER_PED_ID` (1102), `DOES_BLIP_EXIST` (641), `SET_BIT` (640), `CLEAR_BIT` (454), `DOES_BLIP_HAVE_GPS_ROUTE` (334), `GET_FIRST_BLIP_INFO_ID` (311), `NETWORK_IS_ACTIVITY_SESSION` (232), `DOES_SHOP_PED_APPAREL_HAVE_RESTRICTION_TAG` (192), `GET_CLOSEST_BLIP_INFO_ID` (186), `SET_NEW_WAYPOINT` (185), `GET_BLIP_COORDS` (161), `GET_ENTITY_MODEL` (147), `GET_VEHICLE_MOD` (145), `GET_HASH_KEY` (137), `PLAY_SOUND_FRONTEND` (130), `DOES_ENTITY_EXIST` (121), `TO_FLOAT` (118), `DISABLE_CONTROL_ACTION` (97), `IS_PED_IN_ANY_VEHICLE` (90), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (78), `INT_TO_PLAYERINDEX` (72), `GET_ROOM_KEY_FROM_ENTITY` (69), `IS_ENTITY_DEAD` (64), `FLOOR` (59), `GET_FILENAME_FOR_AUDIO_CONVERSATION` (59), `GET_NEXT_BLIP_INFO_ID` (59), `GET_BLIP_COLOUR` (58), `GET_VEHICLE_PED_IS_IN` (54), `GET_ENTITY_COORDS` (52)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.00138888f` x29 · `0.5f` x16 · `2.5f` x9 · `0.9f` x7 · `0.35f` x7 · `-0.05f` x6 · `0.00277776f` x5 · `0.05f` x2 · `0.00390625f` x2 · `0.00416664f` x2 · `0.0006f` x2 · `0.4f` x1 · `0.3f` x1 · `0.034722f` x1 · `-0.0375f` x1 · `-2.4f` x1 · `-0.5f` x1 · `0.25f` x1 · `-1381.524f` x1 · `-477.9127f` x1 · `71.0821f` x1 · `-1572.022f` x1 · `-573.55f` x1 · `107.5629f` x1

## Other strings

Literals whose consuming native was not classified:

`PIM_DCASH`, `WEP_TAT_D`, `PM_PREMWHR_TAT`, `SRTP_TTOO_THUMBS`, `PIM_CSEL`, `PIM_DMAGU`, `GR - Armoured`, `GR - Tactical`, `PIM_DFREE`, `PIM_DMAGUT`, `pi_menu`, `PM_PREMWHR_CLT`, `SRTP_OUT_THUMBS`, `PI_BIK_Hx10`, `PIM_DHIGH0`, `service_spend_pegasus_delivery`, `PIM_DHIGH1`, `PIM_MAGM000`, `use`, `PI_BIK_Hx25`, `mp_m_freemode_01`, `havok`, `CONT_REQ_CD`, `mp_f_freemode_01`, `service_spend_order_bodyguard_vehicle`, `trailersmall2`, `ext_player`, `PIM_DNAME`, `PIM_HISH0`, `PIM_HISH1`

---

Source: `decompiled_scripts/am_pi_menu.c`
