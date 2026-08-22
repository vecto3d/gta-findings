# am_mp_arcade.c

Minigames script. 15 anim dicts; 60 models; 2 scaleforms; 3 particle effects.

| | |
|---|---|
| Category | Minigames |
| Total lines | 474,491 |
| Functions | 8,430 (444 unique, 7,986 shared) |
| Unique lines | 29,670 (6.3% of file) |

## Assets

**Animation dictionaries** (15) - `anim@amb@nightclub@mini@drinking@bar@player_bartender@one`, `anim@amb@nightclub@mini@drinking@bar@player_bartender@idle_a`, `anim@amb@nightclub@mini@drinking@bar@player_bartender@base`, `anim@amb@nightclub@mini@drinking@bar@player_bartender@two`, `anim@amb@nightclub@mini@drinking@bar@player_bartender@three`, `anim@amb@nightclub@mini@drinking@bar@player_bartender@four`, `ANIM@AMB@NIGHTCLUB@MINI@DRINKING@CHAMPAGNE_DRINKING@BASE@`, `ANIM@AMB@CLUBHOUSE@BOSS@FEMALE@`, `ANIM@AMB@CLUBHOUSE@BOSS@MALE@`, `anim@scripted@player@fix_agy_ig6_office_chair_entry@female@`, `anim@scripted@player@fix_agy_ig6_office_chair_entry@male@`, `ANIM_HEIST@ARCADE_PROPERTY@FORTUNE_TELLER_DOOR@LESTER_SPEAKS@`, `ANIM_HEIST@ARCADE_PROPERTY@FORTUNE_TELLER_DOOR@MALE@`, `ANIM_HEIST@ARCADE_PROPERTY@FORTUNE_TELLER_DOOR@FEMALE@`, `anim_heist@arcade_property@wendy@bar@`

**Animations** (14) - `anim@amb@nightclub@mini@drinking@bar@player_bartender@one`, `anim@amb@nightclub@mini@drinking@bar@player_bartender@two`, `anim@amb@nightclub@mini@drinking@bar@player_bartender@three`, `anim@amb@nightclub@mini@drinking@bar@player_bartender@four`, `one_player`, `two_player`, `three_player`, `four_player`, `one_whiskey`, `one_shot_glass`, `one_bartender`, `two_bartender`, `three_bartender`, `four_bartender`

**Models and props** (60) - `prop_anim_cash_pile_02`, `p_whiskey_bottle_s`, `p_cs_shot_glass_2_s`, `hei_prop_hei_securitypanel`, `ch_prop_laptop_01a`, `prop_radio_01`, `ch_prop_whiteboard`, `w_at_scope_large`, `w_sr_marksmanrifle_mag1`, `ch_prop_arcade_street_01a`, `ch_prop_arcade_street_01b`, `ch_prop_arcade_street_01c`, `ch_prop_arcade_street_01d`, `prop_anim_cash_note`, `bkr_prop_clubhouse_offchair_01a`, `ch_prop_arcade_fortune_door_01a`, `vw_prop_vw_offchair_01`, `set_plan_no_bed`, `set_plan_bed`, `set_plan_garage`, `set_plan_wall`, `set_plan_pre_setup`, `set_plan_setup`, `set_plan_scribbles`, `set_plan_computer`, `set_plan_arcade_x4`, `set_plan_plans`, `set_plan_casino`, `set_plan_keypad`, `set_plan_vault`, `set_plan_mechanic`, `set_plan_hacker`, `set_plan_weapons`, `Set_Plan_Vault_Laser`, `Set_Plan_Vault_Drill`, `Set_Plan_Electric_Drill`, `Set_Plan_Plastic_Explosives`, `Set_Plan_Hacking_Device`, `Set_Plan_Cockroaches`, `Set_Plan_Stealth_Outfits`, `Set_Plan_Gruppe_Sechs_Outfits`, `Set_Plan_Fireman_Helmet`, `Set_Plan_Drone_Parts`, `Set_Plan_Vault_KeyCard_01a`, `Set_Plan_Swipe_Card_01a`, `Set_Plan_Swipe_Card_01b`, `Set_Plan_Vault_Laser_Alt`, `Set_Plan_Vault_Drill_Alt`, `ch_prop_ch_arcade_safe_body`, `ch_prop_ch_arcade_safe_door`, `prop_anim_cash_pile_01`, `sm_prop_smug_offchair_01a`, `w_pi_pistol`, `w_ar_specialcarbine`, `w_ar_assaultrifle`, `w_sb_microsmg`, `w_ex_pe`, `w_ex_grenadefrag`, `w_mg_combatmg`, `w_sr_marksmanrifle`

**Audio banks** (6) - `SAFEHOUSE_TREVOR_DRINK_WHISKEY`, `DLC_HEIST3/ARCADE_GENERAL_01`, `DLC_TUNER/DLC_Tuner_Arcade_General`, `DLC_HEIST3/ARCADE_GENERAL_02`, `DLC_HEI4/DLC_HEI4_Anims_Tequila`, `DLC_BATTLE/BTL_CHAMPAGNE_MINIGAME`

**Sounds** (9) - `HUD_FREEMODE_SOUNDSET`, `DLC_H3_Arcade_Interior_Scene`, `SELECT`, `NAV_UP_DOWN`, `CANCEL`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `WEAPON_PURCHASE`, `HUD_AMMO_SHOP_SOUNDSET`, `PICK_UP`

**Scaleform movies** (2) - `FM_TWO_STRINGS`, `SET_VEHICLE_INFOR_AND_STATS`

**Particle effects** (3) - `scr_ba_club`, `fade`, `scr_ba_club_champagne_spray`

**Texture dicts** (7) - `MPCarHUD`, `MPCarHUD2`, `MPCarHUD3`, `MPCarHUD4`, `Heist3_Board_Scribble_1`, `Heist3_Board_Scribble_2`, `Heist3_Board_Scribble_3`

**Text labels** (67) - `VFX`, `AROFFPCNOSET`, `ARCPRIVSES`, `NULL`, `83OSX036`, `47BQT444`, `04DZM900`, `88WFR722`, `23GVN817`, `60UYD615`, `01SRP848`, `82ATK858`, `28AAK928`, `01JCP664`, `43TBV742`, `48OQX480`, `43HDN501`, `45YZY588`, `85PFY881`, `89BVQ075`, `88GCM611`, `22IUD069`, `68ADW760`, `46ZLJ093`, `87LWG803`, `03QPK213`, `65LNN730`, `63CMS702`, `86ACK549`, `05SKJ131`, `28OKO870`, `63LUV750`, `68BPK026`, `28OAE229`, `89FAZ643`, `08PPT772`, `27TIB223`, `05VIC098`, `09QNN844`, `61KCQ803`, `46AOM725`, `84USA531`, `02AFC413`, `82AKQ481`, `81BJX061`, `28BPV442`, `28DJW797`, `06THT542`, `61XWF939`, `85LDY796`, `63ASU750`, `47RPB540`, `28AVY903`, `29FNS081`, `49FDX766`, `82WUZ423`, `62QCH889`, `66SBX027`, `27CLR579`, `23IJE671` ...

**Decorators** (3) - `MPBitset`, `Not_Allow_As_Saved_Veh`, `Player_Vehicle`

**Interiors and entity sets** (1) - `Mainw_RM`

**Vehicle mods** (1) - `oppressor2`

**Scripts launched** (10) - `am_mp_arc_cab_manager`, `gb_casino_heist_planning`, `ob_jukebox`, `arcade_seating`, `AM_MP_ARCADE_PEDS`, `AM_MP_BOARDROOM_SEATING`, `appmpjoblistnew`, `appjipmp`, `AM_MP_ARC_CAB_MANAGER`, `Apartment_Minigame_Launcher`

**Hashed names** (17) - `arcade_seating`, `appArcadeBusinessHub`, `AM_MP_BOARDROOM_SEATING`, `BottleDetach`, `Ba_Prop_Battle_Champ_Open`, `Ba_Prop_Battle_Champ_Open_02`, `Ba_Prop_Battle_Champ_Open_03`, `fade`, `basement_shot_beginning`, `Load_Interior`, `Image_Switch_01`, `Image_Switch_02`, `appInternet`, `ob_jukebox`, `AM_MP_ARCADE_PEDS`, `PickupBottle`, `Swap_Bottle_Open`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (343), `PLAYER_PED_ID` (306), `SET_BIT` (245), `CLEAR_BIT` (226), `NETWORK_HAS_CONTROL_OF_ENTITY` (109), `DOES_ENTITY_EXIST` (83), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (81), `NET_TO_VEH` (65), `NETWORK_REQUEST_CONTROL_OF_ENTITY` (57), `NETWORK_REQUEST_CONTROL_OF_NETWORK_ID` (46), `GET_PLAYER_PED` (36), `NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE` (35), `DISABLE_CONTROL_ACTION` (33), `IS_VALID_INTERIOR` (31), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (29), `GET_HASH_KEY` (25), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (25), `REQUEST_ANIM_DICT` (25), `HAS_ANIM_DICT_LOADED` (25), `SET_VEHICLE_COLOURS` (25), `IS_SCREEN_FADED_OUT` (25), `NET_TO_OBJ` (25), `FREEZE_ENTITY_POSITION` (24), `SET_INPUT_EXCLUSIVE` (24), `NETWORK_START_SYNCHRONISED_SCENE` (23), `NETWORK_CREATE_SYNCHRONISED_SCENE` (22), `SET_MODEL_AS_NO_LONGER_NEEDED` (22), `SET_PED_CONFIG_FLAG` (22), `GET_ENTITY_COORDS` (22), `SET_ENTITY_COORDS_NO_OFFSET` (21)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x26 · `1.5f` x17 · `0.99f` x12 · `-49.99991f` x10 · `0.01f` x9 · `-47.99991f` x9 · `-55.7809f` x6 · `2727.592f` x6 · `-387.6024f` x6 · `2726.221f` x6 · `-387.6064f` x6 · `0.75f` x4 · `2728.795f` x4 · `-383.9991f` x4 · `-49.9659f` x4 · `0.7f` x3 · `-56.1867f` x3 · `0.25f` x3 · `-1.5f` x3 · `0.3f` x3 · `0.1f` x3 · `0.8f` x3 · `2.5f` x2 · `2712.904f` x2

## Other strings

Literals whose consuming native was not classified:

`Main_RM`, `Bartender_Outro_Bottle`, `idle_a_bartender`, `CHAMP_SHAKE`, `GETA_MOD_COST`, `SHAKE_INTENSITY`, `HORIZONTAL_AIM`, `VERTICLE_AIM`, `manchez`, `stryder`, `defiler`, `lectro`, `MP_PROP_CAR1`, `enter_bartender`, `zhaba`, `CLU_BAR_PROMPT`, `POD_TOO_MANY`, `one_whiskey`, `one_shot_glass`, `Mainw_RM`, `AZ_dlc_ch_plan_Master_Control`, `AZ_dlc_ch_plan_Drone_Station`, `AZ_dlc_ch_plan_Hacker_Area`, `intro_bartender`, `issi3`, `asbo`, `kanjo`, `sentinel3`, `retinue2`, `yosemite2`

---

Source: `decompiled_scripts/am_mp_arcade.c`
