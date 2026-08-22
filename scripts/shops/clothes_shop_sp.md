# clothes_shop_sp.c

Shops script. 9 anim dicts; 15 models.

| | |
|---|---|
| Category | Shops |
| Total lines | 359,608 |
| Functions | 1,544 (190 unique, 1,354 shared) |
| Unique lines | 60,596 (16.9% of file) |

## Assets

**Animation dictionaries** (9) - `mp_clothing@female@shirt`, `mp_clothing@female@glasses`, `mp_clothing@female@trousers`, `mp_clothing@female@shoes`, `anim@random@shop_clothes@watches`, `mp@clothing@female@shoes`, `random@shop_clothes@low`, `random@shop_clothes@mid`, `mp_clothing@female@clothingshoes`

**Animations** (18) - `clothingshirt`, `INTRO`, `BASE`, `OUTRO`, `try_shirt_positive_a`, `try_shirt_positive_b`, `try_shirt_positive_c`, `try_shirt_positive_d`, `try_shirt_negative_a`, `try_shirt_negative_b`, `try_shirt_negative_c`, `try_shirt_negative_d`, `try_shirt_neutral_a`, `try_shirt_neutral_b`, `try_shirt_neutral_c`, `shop_ig_3_player`, `shop_ig_3_cashier`, `shop_ig_3_customer`

**Models and props** (15) - `v_lirg_shop_low`, `vw_prop_vw_wallart_139a`, `v_clothesmid`, `s_f_y_shop_low`, `a_m_y_hipster_01`, `s_f_y_shop_mid`, `s_f_m_shop_high`, `s_m_y_shop_mask`, `s_f_m_retailstaff_01`, `vw_prop_vw_wallart_60a`, `vw_prop_vw_wallart_140a`, `vw_prop_vw_wallart_58a`, `v_lirg_shop_mid`, `v_lirg_shop_high`, `u_f_m_casinoshop_01`

**Audio banks** (1) - `CLOTHES_STORE`

**Sounds** (13) - `HUD_AMMO_SHOP_SOUNDSET`, `HUD_FRONTEND_CLOTHESSHOP_SOUNDSET`, `ERROR`, `SELECT`, `WEAPON_SELECT_ARMOR`, `NAV`, `NAV_UP_DOWN`, `CANCEL`, `BACK`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `Ls_Car_Meet_Merch_Shop_Scene`, `WEAPON_PURCHASE`, `OK`

**Speech contexts** (41) - `SPEECH_PARAMS_FORCE`, `SHOP_SELL`, `SHOP_NO_COPS`, `BUMP`, `SHOP_TRY_ON_ITEM`, `SHOP_GOODBYE`, `KIFFLOM_GREET`, `SHOP_GREET`, `SHOP_BANTER`, `GENERIC_BYE`, `FAREWELL_GROUP`, `FAREWELL_NO_SALE`, `FAREWELL`, `SHOP_GREET_UNUSUAL`, `SHOP_GIVE_FOR_FREE`, `SHOP_NO_MESSING`, `SHOP_NO_WEAPON`, `S_M_Y_SHOP_MASK_WHITE_MINI_01`, `SHOPASSISTANT`, `NEW_WELCOME`, `WELCOME`, `WELCOME_MALE`, `WELCOME_FEMALE`, `WELCOME_POSSE`, `WELCOME_BACK`, `WELCOME_BACK_FOLLOW_UP_LONG_TIME`, `WELCOME_BACK_ALREADY`, `SHOPKEEPER_CHAT_IDLE`, `OFFER_ASSISTANCE`, `HAVE_A_LOOK`, `PROMOTE_STORE`, `MENU_BROWSING`, `MENU_BROWSING_IDLE`, `TAKE_YOUR_TIME`, `HANGING_AROUND_PURCHASED`, `GENERIC_BUY_RESPONSE`, `ANYTHING_ELSE`, `MENU_NOT_ENOUGH_CHIPS`, `PLAYER_LOITERING`, `PLAYER_STARING`, `SHOP_OUT_OF_STOCK`

**Texture dicts** (2) - `MPShops`, `ShopUI_Title_Graphics_SALE`

**Text labels** (10) - `BASE`, `MICHAEL`, `DLC`, `NULL`, `SHOPASS`, `BRSCRWTEX`, `SHOPASSISTANT`, `INTRO`, `OUTRO`, `SOL5AUD`

**Scenarios** (1) - `WORLD_HUMAN_AA_COFFEE`

**Timecycle modifiers** (1) - `DLC_MpSecurity_Stu_Wardrobe`

**Stats** (3) - `sp0_sp_money_spent_on_clothes`, `sp1_sp_money_spent_on_clothes`, `sp2_sp_money_spent_on_clothes`

**Scripts launched** (3) - `fbi4_prep4`, `fbi4_prep5`, `michael4`

**Hashed names** (28) - `wardrobe_mp`, `crewLogo`, `CSHOP_UNLOCK_C`, `MainRoom`, `v_clotheslo`, `v_clothesmid`, `v_clotheshi`, `V_51_ShopFloorRm`, `V_ClothesMidRm`, `V_7_GunShopRm`, `V_22_GunShopRm`, `Meet_rm`, `room_office_hacker`, `room_lobby`, `RM_ARMOURY`, `CSHOP_BUY`, `CSHOP_LCKCREW`, `CCR_CLO_LOCK`, `wardrobe_sp`, `v_gun`, `v_gun2`, `vw_dlc_casino_main`, `tr_tuner_car_meet`, `sf_dlc_office_sec`, `sf_dlc_studio_sec`, `m25_2_int_mansion_2`, `CSHOP_LCKCREWR`, `CSHOP_LCKCREWR_TUT`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_SHOP_PED_APPAREL_HAVE_RESTRICTION_TAG` (459), `PLAYER_PED_ID` (337), `NETWORK_IS_GAME_IN_PROGRESS` (259), `SET_BIT` (254), `GET_HASH_KEY` (148), `CLEAR_BIT` (133), `TASK_PLAY_ANIM` (88), `PLAY_SOUND_FRONTEND` (88), `PLAY_PED_AMBIENT_SPEECH_NATIVE` (71), `IS_PED_INJURED` (60), `PLAYER_ID` (56), `GET_ENTITY_MODEL` (50), `DOES_ENTITY_EXIST` (44), `SET_PED_COMPONENT_VARIATION` (44), `IS_STRING_NULL_OR_EMPTY` (39), `ARE_STRINGS_EQUAL` (38), `GET_GAME_TIMER` (38), `GET_PED_TEXTURE_VARIATION` (31), `GET_RANDOM_INT_IN_RANGE` (31), `GET_PED_DRAWABLE_VARIATION` (27), `GET_HASH_NAME_FOR_COMPONENT` (21), `IS_ENTITY_PLAYING_ANIM` (18), `GET_PED_PROP_INDEX` (16), `GET_NETWORK_TIME` (15), `GET_PED_PROP_TEXTURE_INDEX` (14), `GET_ENTITY_COORDS` (14), `OPEN_SEQUENCE_TASK` (14), `CLOSE_SEQUENCE_TASK` (14), `IS_CONTROL_JUST_PRESSED` (13), `IS_HELP_MESSAGE_BEING_DISPLAYED` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.1f` x6 · `7.5f` x4 · `2.5f` x3 · `72.607f` x3 · `-1389.26f` x3 · `28.3823f` x3 · `28.3761f` x2 · `0.045f` x2 · `1101.262f` x1 · `197.1068f` x1 · `-50.44016f` x1 · `1102.38f` x1 · `195.9243f` x1 · `-48.19017f` x1 · `-1334.879f` x1 · `-1275.976f` x1 · `4.963415f` x1 · `164.2634f` x1 · `73.6779f` x1 · `-1393.129f` x1 · `270.7799f` x1 · `197.0619f` x1 · `76.5739f` x1 · `-1392.641f` x1

## Other strings

Literals whose consuming native was not classified:

`mp_m_freemode_01`, `mp_f_freemode_01`, `CSHOP_TRY_T`, `clothingshirt`, `CSHOP_LCKFIN`, `CSHOP_TRY_SHO`, `CSHOP_TRY_SH`, `CSHOP_TRY_P`, `CSHOP_TRY_HAT`, `multi_decal`, `hood_up`, `CSHOP_TRY_JK`, `clothingspecs`, `player_zero`, `clothingshoes`, `CSHOP_TRY_OUT`, `clothingtrousers`, `player_one`, `ITEM_COST`, `alt_special_2`, `CSHOP_LCKPRP`, `ITEM_BACK`, `tie`, `SHOP_NONE`, `CSHOP_TRY_GLS`, `CSHOP_TRY_GEAR`, `CSHOP_TRY_ACC`, `tux_tie`, `alt_vest`, `tux_vest`

---

Source: `decompiled_scripts/clothes_shop_sp.c`
