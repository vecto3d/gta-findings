# shoprobberies.c

SP missions script. 3 anim dicts; 15 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 15,066 |
| Functions | 344 (111 unique, 233 shared) |
| Unique lines | 8,226 (54.6% of file) |

## Assets

**Animation dictionaries** (3) - `oddjobs@shop_robbery@rob_till`, `misscommon@response`, `random@shop_robbery_reactions@`

**Animations** (10) - `mp_am_hold_up`, `oddjobs@shop_robbery@rob_till`, `misscommon@response`, `numbnuts`, `loop`, `handsup_base`, `give_me_a_break`, `purchase_chocbar_shopkeeper`, `enter`, `exit`

**Models and props** (15) - `s_m_y_cop_01`, `p_poly_bag_01_s`, `v_ilev_247door`, `v_ilev_247door_r`, `prop_choc_pq`, `v_ilev_gasdoor`, `v_ilev_gasdoor_r`, `v_ilev_ml_door1`, `prop_choc_ego`, `prop_choc_meto`, `prop_till_01`, `prop_till_02`, `prop_till_03`, `p_till_01_s`, `a_m_y_soucent_04`

**Audio banks** (1) - `SCRIPT\MARKET_CASH_REGISTER`

**Sounds** (11) - `HUD_LIQUOR_STORE_SOUNDSET`, `NAV_UP_DOWN`, `ROBBERY_MONEY_TOTAL`, `HUD_FRONTEND_CUSTOM_SOUNDSET`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `PURCHASE`, `ERROR`, `SELECT`, `CANCEL`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Text labels** (5) - `NUMBER`, `NULL`, `BUMP`, `SURROUNDED`, `OJSRAUD`

**Interiors and entity sets** (3) - `v_gasstation`, `v_gen_liquor`, `v_shop_247`

**Scripts launched** (1) - `fm_mission_creator`

**Hashed names** (34) - `HIDE`, `eCRIM_HUP_GAS_2A`, `eCRIM_HUP_GAS_2B`, `eCRIM_HUP_GAS_3A`, `eCRIM_HUP_GAS_3B`, `eCRIM_HUP_GAS_4A`, `eCRIM_HUP_GAS_4B`, `eCRIM_HUP_GAS_1A`, `eCRIM_HUP_GAS_1B`, `eCRIM_HUP_GAS_5A`, `eCRIM_HUP_GAS_5B`, `eCRIM_HUP_LIQUOR_1A`, `eCRIM_HUP_LIQUOR_2A`, `eCRIM_HUP_LIQUOR_3A`, `eCRIM_HUP_LIQUOR_4A`, `eCRIM_HUP_LIQUOR_5A`, `eCRIM_HUP_SHOP247_3A`, `eCRIM_HUP_SHOP247_3B`, `eCRIM_HUP_SHOP247_2A`, `eCRIM_HUP_SHOP247_2B`, `eCRIM_HUP_SHOP247_4A`, `eCRIM_HUP_SHOP247_4B`, `eCRIM_HUP_SHOP247_5A`, `eCRIM_HUP_SHOP247_5B`, `eCRIM_HUP_SHOP247_6A`, `eCRIM_HUP_SHOP247_6B`, `eCRIM_HUP_SHOP247_7A`, `eCRIM_HUP_SHOP247_7B`, `eCRIM_HUP_SHOP247_8A`, `eCRIM_HUP_SHOP247_8B`, `eCRIM_HUP_SHOP247_9A`, `eCRIM_HUP_SHOP247_9B`, `eCRIM_HUP_SHOP247_10A`, `eCRIM_HUP_SHOP247_10B`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (101), `IS_ENTITY_DEAD` (92), `GET_HASH_KEY` (61), `GET_RANDOM_INT_IN_RANGE` (48), `IS_PED_INJURED` (35), `PLAYER_ID` (27), `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME` (24), `GET_GAME_TIMER` (23), `IS_ENTITY_IN_ANGLED_AREA` (22), `ADD_TEXT_COMPONENT_SUBSTRING_TEXT_LABEL` (22), `DOES_ENTITY_EXIST` (17), `GET_SYNCHRONIZED_SCENE_PHASE` (17), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (16), `TASK_PLAY_ANIM` (15), `CLEAR_HELP` (12), `CLEAR_BIT` (12), `SET_ENTITY_VISIBLE` (12), `SET_ENTITY_HEALTH` (12), `SET_INPUT_EXCLUSIVE` (12), `GET_HUD_COLOUR` (12), `GET_RENDERED_CHARACTER_HEIGHT` (11), `IS_SYNCHRONIZED_SCENE_RUNNING` (10), `GET_ENTITY_COORDS` (10), `PLAY_SOUND_FRONTEND` (10), `ADD_TEXT_COMPONENT_INTEGER` (10), `IS_PED_RAGDOLL` (9), `ADD_TEXT_COMPONENT_FLOAT` (9), `IS_PED_IN_ANY_VEHICLE` (8), `TASK_SMART_FLEE_PED` (8), `OPEN_SEQUENCE_TASK` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.00138888f` x27 · `0.5f` x20 · `0.35f` x9 · `0.00277776f` x5 · `-0.05f` x4 · `-1.5f` x3 · `0.894f` x3 · `0.871f` x3 · `0.1f` x3 · `1.5f` x3 · `-0.040857f` x3 · `0.366089f` x3 · `1.45f` x2 · `0.00390625f` x2 · `0.00416664f` x2 · `-0.75f` x2 · `0.68f` x2 · `0.3008f` x2 · `0.25f` x1 · `0.478f` x1 · `0.447f` x1 · `0.117f` x1 · `0.154f` x1 · `0.477f` x1

## Other strings

Literals whose consuming native was not classified:

`mp_m_shopkeep_01`, `SHR_HOLDUP_1`, `police`, `SHR_SNK_TUT`, `SHR_MENU`, `CommonMenu`, `sheriff`, `SHOP_THREATENED`, `SHOP_SCARED`, `SHOP_NO_COPS_START`, `SHOP_NO_COPS_END`, `Gradient_Bgd`, `SHR_ROBTILL`, `CM_ITEM_COUNT`, `SHOP_CLOSED`, `object`, `HAND_SHAKE`, `ITEM_COST`, `SHOP_NO_ENTRY`, `SHOP_BRAVE`, `SHOP_RECOGNISE`, `SNK_ITEM1_D`, `shop_arrows_upANDdown`, `mp_am_hold_up`, `GROUP_PISTOL`, `hold_up_head_additive_pistol`, `GROUP_MG`, `GROUP_RIFLE`, `GROUP_SHOTGUN`, `GROUP_SNIPER`

---

Source: `decompiled_scripts/shoprobberies.c`
