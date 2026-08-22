# am_mp_sb_car_wash.c

MP ambient script. 1 anim dicts; 10 models.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 495,407 |
| Functions | 8,558 (175 unique, 8,383 shared) |
| Unique lines | 17,337 (3.5% of file) |

## Assets

**Animation dictionaries** (1) - `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`

**Models and props** (10) - `bkr_prop_duffel_bag_01a`, `prop_anim_cash_note`, `prop_anim_cash_pile_01`, `prop_anim_cash_pile_02`, `cinquemila`, `set_smoke`, `set_heli`, `set_carwash_tints`, `set_heli_tint`, `set_smoke_tint`

**Audio banks** (2) - `DLC_HEIST3/ARCADE_GENERAL_02`, `DLC_VINEWOOD/DLC_VW_HIDDEN_COLLECTIBLES`

**Sounds** (8) - `DLC_25-1_Business_Interiors_Mute_Explosions_Etc_Scene`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `WEAPON_PURCHASE`, `HUD_AMMO_SHOP_SOUNDSET`, `NAV_UP_DOWN`, `playing_card`, `dlc_vw_hidden_collectible_sounds`, `BACK`

**Texture dicts** (1) - `ShopUI_Title_HandsOnCarWash`

**Text labels** (5) - `S25RAU`, `NULL`, `ANG3L1S`, `CARWASH`, `INCOME`

**Interiors and entity sets** (1) - `GtaMloRoom001`

**Hashed names** (2) - `M24_1_PROP_M41_RADIO_01A`, `appInternet`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (70), `PLAYER_PED_ID` (32), `SET_BIT` (28), `CLEAR_BIT` (21), `ENABLE_CONTROL_ACTION` (15), `SET_BLIP_COLOUR` (12), `DOES_ENTITY_EXIST` (10), `IS_SCREEN_FADED_OUT` (9), `IS_STRING_NULL_OR_EMPTY` (8), `NET_TO_OBJ` (8), `SET_INPUT_EXCLUSIVE` (8), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (7), `PLAY_SOUND_FRONTEND` (6), `GET_PLAYER_PED` (6), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (6), `IS_CONTROL_PRESSED` (6), `DISABLE_CONTROL_ACTION` (6), `SET_PED_CONFIG_FLAG` (5), `NETWORK_DOES_NETWORK_ID_EXIST` (5), `GET_NUM_RESERVED_MISSION_OBJECTS` (5), `GET_BLIP_COLOUR` (5), `GET_ENTITY_COORDS` (5), `SET_BLIP_FLASHES` (4), `NETWORK_IS_GAME_IN_PROGRESS` (4), `DO_SCREEN_FADE_OUT` (4), `IS_VALID_INTERIOR` (4), `IS_INTERIOR_READY` (4), `IS_ENTITY_DEAD` (4), `DOES_BLIP_EXIST` (4), `SET_BLIP_SCALE` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.7f` x6 · `0.2f` x4 · `1.5f` x3 · `0.8f` x3 · `-72.0123f` x2 · `-16.8392f` x2 · `-73.9466f` x2 · `-5.5664f` x2 · `-73.5531f` x2 · `-9.0151f` x2 · `-22.0669f` x2 · `-0.0117f` x2 · `14.6094f` x2 · `-1399.435f` x2 · `-74.62f` x2 · `-1.5f` x2 · `23.1938f` x1 · `-1402.556f` x1 · `-17.0387f` x1 · `20.6871f` x1 · `-1401.634f` x1 · `-42.0874f` x1 · `24.0858f` x1 · `-1400.959f` x1

## Other strings

Literals whose consuming native was not classified:

`RAF_CAR_HLP`, `HUD_CASH`, `CWASH_PAY_ENTER_M`, `CWASH_COLLECT_S`, `cinquemila`, `CWASH_SAFE_FCSH`, `HOCW_Computer_Screens`, `Desktop`, `mp_bedmid`, `small_business_carwash_cutscene`, `shot_0`, `shot_1`, `shot_2`, `shot_3`, `TYFLOW_HLP_3`, `~BLIP_BUSINESS_FOR_SALE~`, `MAINTAIN_CAR_WASH_RENOVATION - Entity sets need updated`, `PERFORM_CAR_WASH_RENOVATION - Renovation complete`, `SE_m25_1_int_tycoon_car_wash_GtaMloRoom003`, `ARC_BLIP_SAFE`, `No reason given - This is bad!`, `CW_SAFE_HUD`, `cs2_29_bio_ent`, `ShopUI_Title_HandsOnCarWash`, `CWASH_S_PIC_T`, `CWASH_S_PIC_O`, `ITEM_BACK`, `CWASH_S_PIC_D`, `CWASH_S_PIC_DsW`, `CWASH_S_PIC_Ds`

---

Source: `decompiled_scripts/am_mp_sb_car_wash.c`
