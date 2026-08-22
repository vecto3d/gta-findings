# tattoo_shop.c

Shops script. 4 anim dicts; 7 models.

| | |
|---|---|
| Category | Shops |
| Total lines | 141,146 |
| Functions | 1,130 (110 unique, 1,020 shared) |
| Unique lines | 14,744 (10.4% of file) |

## Assets

**Animation dictionaries** (4) - `misstattoo_parlour@shop_ig_4`, `misstattoo_parlour@shop_ig_4b`, `misstattoo_parlour@shop_ig_5_b`, `MISSTATTOO_PARLOUR@SHOP_IG_4BPLAYER`

**Animations** (2) - `customer_loop`, `tattooist_loop`

**Models and props** (7) - `v_ilev_ta_tatgun`, `g_m_y_mexgoon_03`, `v_ret_ta_stool`, `u_m_y_tattoo_01`, `s_m_m_tattoo_01`, `v_ilev_ta_door`, `v_ilev_ml_door1`

**Audio banks** (1) - `HUD_TATTOO_SHOP`

**Sounds** (10) - `HUD_FRONTEND_TATTOO_SHOP_SOUNDSET`, `NAV_UP_DOWN`, `ERROR`, `Ls_Car_Meet_Tattoo_Shop_Scene`, `BACK`, `TATTOOIST_SOUNDS`, `SELECT`, `Tattooing_Oneshot`, `PURCHASE`, `Tattooing_Oneshot_Remove`

**Speech contexts** (11) - `SPEECH_PARAMS_FORCE`, `SHOP_TATTOO_APPLIED`, `SHOP_GREET_UNUSUAL`, `KIFFLOM_GREET`, `SHOP_GREET`, `U_M_Y_TATTOO_01_WHITE_MINI_01`, `SHOP_NO_COPS`, `SHOP_BANTER`, `SHOP_BROWSE_TATTOO_MENU`, `SHOP_SELL`, `SHOP_GOODBYE`

**Texture dicts** (2) - `MPShops`, `ShopUI_Title_Graphics_SALE`

**Text labels** (3) - `ALL`, `NULL`, `TATARTIST`

**Hashed names** (9) - `v_tattoo`, `tr_tuner_car_meet`, `m25_2_int_mansion`, `v_tattoo2`, `MainTatRm`, `V_49_Tat2_Room`, `Meet_rm`, `RM_POOL_SPA`, `torsoDecal`

## Native vocabulary

Most-called natives inside the code unique to this script:

`TO_FLOAT` (539), `ROUND` (536), `PLAYER_PED_ID` (156), `NETWORK_IS_GAME_IN_PROGRESS` (99), `SET_PED_COMPONENT_VARIATION` (58), `IS_PED_INJURED` (47), `GET_HASH_KEY` (42), `DOES_ENTITY_EXIST` (34), `GET_ENTITY_HEADING` (21), `GET_ENTITY_MODEL` (20), `GET_GAME_TIMER` (20), `PLAYER_ID` (18), `SET_BIT` (17), `PLAY_SOUND_FRONTEND` (17), `GET_NETWORK_TIME` (14), `IS_STRING_NULL_OR_EMPTY` (13), `GET_ENTITY_COORDS` (13), `PLAY_PED_AMBIENT_SPEECH_NATIVE` (13), `ARE_STRINGS_EQUAL` (12), `HIDE_PED_BLOOD_DAMAGE_BY_ZONE` (12), `GET_PED_DECORATION_ZONE_FROM_HASHES` (11), `GET_RANDOM_INT_IN_RANGE` (9), `GET_LENGTH_OF_LITERAL_STRING` (9), `DELETE_PED` (8), `CLEAR_BIT` (8), `GET_NUM_TATTOO_SHOP_DLC_ITEMS` (7), `GET_TATTOO_SHOP_DLC_ITEM_DATA` (7), `TASK_LOOK_AT_ENTITY` (7), `USE_FAKE_MP_CASH` (7), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`32.0619f` x3 · `-17.3353f` x3 · `-3.6541f` x3 · `337.4353f` x3 · `2.5f` x2 · `102.5865f` x2 · `1862.844f` x2 · `3748.159f` x2 · `33.03185f` x2 · `60.912f` x2 · `-2163.247f` x2 · `1073.873f` x2 · `-25.3537f` x2 · `0.62f` x1 · `0.877f` x1 · `0.955f` x1 · `0.9f` x1 · `322.5702f` x1 · `182.0852f` x1 · `196.6765f` x1 · `319.618f` x1 · `181.5184f` x1 · `246.6867f` x1 · `324.1968f` x1

## Other strings

Literals whose consuming native was not classified:

`torsoDecal`, `ITEM_COST`, `TAT_ZONE_0a`, `player_zero`, `ITEM_FREE`, `_BASE`, `CMM_HT_TAT`, `CLO_BRAND_EVENT`, `TAT_ZONE_0b`, `TAT_ZONE_0c`, `TAT_ZONE_0d`, `TAT_ZONE_1`, `TAT_ZONE_2`, `TAT_ZONE_3`, `TAT_ZONE_4`, `TAT_ZONE_5`, `TAT_LOCK`, `SHOP_CLOSED`, `TAT_TRY_TAT`, `SHOP_CONTENT_36`, `TAT_CREW`, `TAT_CREWT`, `TAT_LCKPC`, `TAT_UNLOCK`, `TAT_SALE`, `player_one`, `player_two`, `mpply_ingamestore_moneyspent`, `shop_ig_4_tattoogun`

---

Source: `decompiled_scripts/tattoo_shop.c`
