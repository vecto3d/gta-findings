# blackjack.c

Minigames script. 4 anim dicts; 24 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 22,167 |
| Functions | 465 (166 unique, 299 shared) |
| Unique lines | 13,246 (59.8% of file) |

## Assets

**Animation dictionaries** (4) - `anim_casino_b@amb@casino@games@blackjack@dealer`, `anim_casino_b@amb@casino@games@shared@dealer@`, `anim_casino_b@amb@casino@games@blackjack@player`, `anim_casino_b@amb@casino@games@shared@player@`

**Animations** (7) - `idle_cardgames`, `request_card`, `request_card_alt1`, `request_card_alt2`, `decline_card_001`, `decline_card_alt1`, `decline_card_alt2`

**Models and props** (24) - `vw_prop_chip_10dollar_st`, `vw_prop_chip_1kdollar_st`, `vw_prop_chip_50dollar_st`, `vw_prop_chip_500dollar_st`, `vw_prop_chip_100dollar_st`, `vw_prop_casino_blckjack_01b`, `vw_prop_chip_5kdollar_st`, `vw_prop_chip_10kdollar_st`, `vw_prop_plaq_5kdollar_st`, `vw_prop_plaq_10kdollar_st`, `vw_prop_chip_10dollar_x1`, `vw_prop_chip_50dollar_x1`, `vw_prop_chip_100dollar_x1`, `vw_prop_chip_500dollar_x1`, `vw_prop_chip_1kdollar_x1`, `vw_prop_casino_blckjack_01`, `vw_prop_chip_5kdollar_x1`, `vw_prop_chip_10kdollar_x1`, `vw_prop_plaq_5kdollar_x1`, `vw_prop_plaq_10kdollar_x1`, `s_m_y_casino_01`, `s_f_y_casino_01`, `vw_prop_vw_jo_char_01a`, `vw_prop_casino_cards_single`

**Sounds** (10) - `dlc_vw_table_games_frontend_sounds`, `DLC_VW_Casino_Table_Games`, `DLC_VW_Casino_Cards_Focus_Hand`, `dlc_vw_table_games_sounds`, `DLC_VW_CONTINUE`, `DLC_VW_RULES`, `DLC_VW_ERROR_MAX`, `DLC_VW_BET_UP`, `DLC_VW_BET_MAX`, `DLC_VW_WIN_CHIPS`

**Text labels** (2) - `NULL`, `NUMBER`

**Hashed names** (114) - `S_M_Y_Casino_01_WHITE_01`, `S_M_Y_Casino_01_ASIAN_01`, `S_F_Y_Casino_01_ASIAN_01`, `S_F_Y_Casino_01_ASIAN_02`, `S_F_Y_Casino_01_LATINA_01`, `S_M_Y_Casino_01_ASIAN_02`, `S_M_Y_Casino_01_WHITE_02`, `S_F_Y_Casino_01_LATINA_02`, `vw_prop_vw_club_char_a_a`, `vw_prop_vw_club_char_02a`, `vw_prop_vw_club_char_03a`, `vw_prop_vw_club_char_04a`, `vw_prop_vw_club_char_05a`, `vw_prop_vw_club_char_06a`, `vw_prop_vw_club_char_07a`, `vw_prop_vw_club_char_08a`, `vw_prop_vw_club_char_09a`, `vw_prop_vw_club_char_10a`, `vw_prop_vw_club_char_j_a`, `vw_prop_vw_club_char_q_a`, `vw_prop_vw_club_char_k_a`, `vw_prop_vw_dia_char_a_a`, `vw_prop_vw_dia_char_02a`, `vw_prop_vw_dia_char_03a`, `vw_prop_vw_dia_char_04a`, `vw_prop_vw_dia_char_05a`, `vw_prop_vw_dia_char_06a`, `vw_prop_vw_dia_char_07a`, `vw_prop_vw_dia_char_08a`, `vw_prop_vw_dia_char_09a`, `vw_prop_vw_dia_char_10a`, `vw_prop_vw_dia_char_j_a`, `vw_prop_vw_dia_char_q_a`, `vw_prop_vw_dia_char_k_a`, `vw_prop_vw_hrt_char_a_a`, `vw_prop_vw_hrt_char_02a`, `vw_prop_vw_hrt_char_03a`, `vw_prop_vw_hrt_char_04a`, `vw_prop_vw_hrt_char_05a`, `vw_prop_vw_hrt_char_06a`, `vw_prop_vw_hrt_char_07a`, `vw_prop_vw_hrt_char_08a`, `vw_prop_vw_hrt_char_09a`, `vw_prop_vw_hrt_char_10a`, `vw_prop_vw_hrt_char_j_a`, `vw_prop_vw_hrt_char_q_a`, `vw_prop_vw_hrt_char_k_a`, `vw_prop_vw_spd_char_a_a`, `vw_prop_vw_spd_char_02a`, `vw_prop_vw_spd_char_03a`, `vw_prop_vw_spd_char_04a`, `vw_prop_vw_spd_char_05a`, `vw_prop_vw_spd_char_06a`, `vw_prop_vw_spd_char_07a`, `vw_prop_vw_spd_char_08a`, `vw_prop_vw_spd_char_09a`, `vw_prop_vw_spd_char_10a`, `vw_prop_vw_spd_char_j_a`, `vw_prop_vw_spd_char_q_a`, `vw_prop_vw_spd_char_k_a` ...

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (556), `NET_TO_PED` (310), `SET_PED_COMPONENT_VARIATION` (140), `SET_BIT` (132), `HAS_ANIM_EVENT_FIRED` (131), `GET_HASH_KEY` (120), `CLEAR_BIT` (79), `IS_ENTITY_PLAYING_ANIM` (78), `NETWORK_CREATE_SYNCHRONISED_SCENE` (68), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (68), `NETWORK_START_SYNCHRONISED_SCENE` (68), `PLAYER_PED_ID` (68), `IS_PED_INJURED` (52), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (51), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (50), `GET_SYNCHRONIZED_SCENE_PHASE` (45), `DOES_ENTITY_EXIST` (44), `GET_RANDOM_INT_IN_RANGE` (36), `GET_ENTITY_BONE_INDEX_BY_NAME` (32), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (31), `DELETE_OBJECT` (31), `CLEAR_HELP` (23), `SET_ENTITY_COORDS_NO_OFFSET` (22), `SET_ENTITY_ROTATION` (20), `GET_ENTITY_ALPHA` (18), `GET_CONTROL_INSTRUCTIONAL_BUTTONS_STRING` (16), `FLOOR` (16), `ADD_TEXT_COMPONENT_INTEGER` (16), `GET_ENTITY_BONE_ROTATION` (16), `GET_ENTITY_BONE_POSTION` (16)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x40 · `0.1f` x7 · `2.5f` x6 · `0.3f` x4 · `0.01f` x3 · `1.5f` x2 · `-52.041f` x2 · `0.24f` x1 · `0.03f` x1 · `-0.0094f` x1 · `-0.0611f` x1 · `1.5098f` x1 · `0.245f` x1 · `1.415f` x1 · `1129.406f` x1 · `262.3578f` x1 · `1144.429f` x1 · `247.3352f` x1

## Other strings

Literals whose consuming native was not classified:

`BJACK_BJ`, `blend_out`, `BJACK_BUSTED`, `BJACK_7CC`, `BJACK_SHOW_4`, `push`, `BJACK_WIN_6`, `BJACK_P_HAND2`, `win`, `lose`, `Bust`, `DLC_VW_CHIP_BET_SML_MEDIUM`, `DLC_VW_CHIP_BET_SML_LARGE`, `Chair_Base_04`, `Chair_Base_03`, `Chair_Base_02`, `Chair_Base_01`, `DLC_VW_CHIP_BET_SML_SMALL`, `BJACK_WIN_4`, `BJACK_WIN_5`, `BJACK_SHOW_3`, `BJACK_SHOW_2`, `CAS_MG_CTIME`, `CAS_MG_CBAN`, `BJACK_TURN_S`, `BJACK_TURN_D`, `BJACK_TURN`, `reaction_bad_var_01`, `reaction_bad_var_02`, `reaction_bad_var_03`

---

Source: `decompiled_scripts/blackjack.c`
