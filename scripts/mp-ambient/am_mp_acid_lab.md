# am_mp_acid_lab.c

MP ambient script. 3 anim dicts; 23 models.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 501,822 |
| Functions | 8,636 (192 unique, 8,444 shared) |
| Unique lines | 19,827 (4.0% of file) |

## Assets

**Animation dictionaries** (3) - `anim@scripted@player@freemode@ig3_lab@male@`, `anim@scripted@player@freemode@ig3_lab@heeled@`, `anim@scripted@tutorial@freemode@ig_acid_lab@`

**Models and props** (23) - `gr_prop_gr_gunsmithsupl_01a`, `gr_prop_gr_gunsmithsupl_02a`, `gr_prop_gr_gunsmithsupl_03a`, `v_ind_cs_chemcan`, `v_ind_cfbox`, `set_product_01`, `set_product_02`, `set_product_03`, `set_product_04`, `set_product_05`, `set_supplies_01`, `set_supplies_02`, `set_supplies_03`, `set_supplies_04`, `set_supplies_05`, `set_equipment_upgrade`, `bkr_prop_weed_bigbag_01a`, `bkr_prop_coke_block_01a`, `bkr_prop_coke_doll_bigbox`, `bkr_prop_fakeid_boxdriverl_01a`, `bkr_prop_fakeid_boxpassport_01a`, `bkr_prop_moneypack_02a`, `bkr_prop_meth_bigbag_01a`

**Audio banks** (1) - `DLC_CM2022/CM2022_FREEMODE_01`

**Sounds** (6) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `NAV_UP_DOWN`, `Select_Mission_Unavailable`, `DLC_GR_MOC_Computer_Sounds`, `ERROR`, `SELECT`

**Text labels** (2) - `XM3LAAU`, `NULL`

**Hashed names** (2) - `ACID_PHONE_MENU`, `ACID_COOK_MENU`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (96), `PLAYER_PED_ID` (54), `SET_BIT` (48), `CLEAR_BIT` (35), `DISABLE_CONTROL_ACTION` (16), `SET_BLIP_COLOUR` (13), `GET_CAM_VIEW_MODE_FOR_CONTEXT` (11), `CLEAR_HELP` (11), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (10), `NET_TO_ENT` (10), `DOES_ENTITY_EXIST` (7), `IS_STRING_NULL_OR_EMPTY` (7), `GET_BLIP_COLOUR` (7), `IS_ENTITY_IN_ANGLED_AREA` (7), `SET_PED_CONFIG_FLAG` (7), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (6), `GET_PLAYER_PED` (6), `SET_BLIP_SCALE` (6), `ENABLE_CONTROL_ACTION` (6), `TO_FLOAT` (6), `SET_CAM_VIEW_MODE_FOR_CONTEXT` (5), `NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE` (5), `PLAY_SOUND_FRONTEND` (5), `IS_SCREEN_FADED_OUT` (5), `NETWORK_IS_GAME_IN_PROGRESS` (4), `DOES_BLIP_EXIST` (4), `GET_RANDOM_INT_IN_RANGE` (4), `IS_CONTROL_JUST_PRESSED` (4), `SET_ENTITY_VISIBLE` (4), `IS_VALID_INTERIOR` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.8f` x6 · `0.75f` x4 · `-2625.264f` x3 · `-2625.756f` x3 · `-2626.124f` x3 · `0.01f` x3 · `-49.66f` x2 · `486.6956f` x2 · `-2624.395f` x2 · `-49.91408f` x2 · `486.6902f` x2 · `-2623.177f` x2 · `-47.91408f` x2 · `-2624.111f` x2 · `-49.66405f` x2 · `486.22f` x1 · `-2623.93f` x1 · `-48.83f` x1 · `481.06f` x1 · `-2625.99f` x1 · `481.03f` x1 · `-2623.97f` x1 · `0.99f` x1 · `486.219f` x1

## Other strings

Literals whose consuming native was not classified:

`xm3_prop_xm3_product_box_01`, `xm3_prop_xm3_product_bottle_01`, `xm3_prop_xm3_med_chm_01a`, `xm3_prop_xm3_pipette_01b`, `xm3_prop_xm3_lsd_bottle_01a`, `xm3_prop_xm3_product_tabs_single`, `ACID_TUT_SCN_3`, `xm3_prop_xm3_lab_acetone`, `SE_xm3_dlc_int_01_xm3_radioemitter`, `xm3_prop_xm3_product_tabs_full`, `ACID_SLL_FAIL`, `ACID_TUT_SCN_1`, `ACID_TUT_SCN_2`, `ACID_TUT_SCN_3b`, `ACID_TUT_SCN_4`, `xm3_prop_xm3_lsd_bottles3`, `xm3_prop_xm3_lsd_beaker_01d`, `ACID_SRC_HLP1c`, `ACID_SRC_HLP1f`, `xm3_prop_xm3_lab_hcacid`, `xm3_prop_xm3_lsd_bottles1`, `xm3_prop_xm3_lab_ammonia`, `xm3_prop_xm3_lsd_bottle_03a`, `xm3_prop_xm3_rack_vial_01b`, `crewlogo_01`, `xm3_prop_xm3_drying_tabs_f1`, `crewlogo_02`, `xm3_prop_xm3_drying_tabs_b1`, `crewlogo_03`, `xm3_prop_xm3_drying_tabs_f2`

---

Source: `decompiled_scripts/am_mp_acid_lab.c`
