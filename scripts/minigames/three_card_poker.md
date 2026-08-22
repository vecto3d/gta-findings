# three_card_poker.c

Minigames script. 4 anim dicts; 24 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 20,608 |
| Functions | 463 (159 unique, 304 shared) |
| Unique lines | 11,384 (55.2% of file) |

## Assets

**Animation dictionaries** (4) - `anim_casino_b@amb@casino@games@threecardpoker@dealer`, `anim_casino_b@amb@casino@games@shared@dealer@`, `anim_casino_b@amb@casino@games@threecardpoker@player`, `anim_casino_b@amb@casino@games@shared@player@`

**Animations** (3) - `cards_pickup`, `cards_idle`, `idle_cardgames`

**Models and props** (24) - `vw_prop_chip_10dollar_st`, `vw_prop_chip_1kdollar_st`, `vw_prop_chip_50dollar_st`, `vw_prop_chip_500dollar_st`, `vw_prop_chip_100dollar_st`, `vw_prop_casino_3cardpoker_01b`, `vw_prop_chip_5kdollar_st`, `vw_prop_chip_10kdollar_st`, `vw_prop_plaq_5kdollar_st`, `vw_prop_plaq_10kdollar_st`, `vw_prop_chip_10dollar_x1`, `vw_prop_chip_50dollar_x1`, `vw_prop_chip_100dollar_x1`, `vw_prop_chip_500dollar_x1`, `vw_prop_chip_1kdollar_x1`, `vw_prop_casino_3cardpoker_01`, `vw_prop_chip_5kdollar_x1`, `vw_prop_chip_10kdollar_x1`, `vw_prop_plaq_5kdollar_x1`, `vw_prop_plaq_10kdollar_x1`, `s_m_y_casino_01`, `s_f_y_casino_01`, `vw_prop_vw_casino_cards_01`, `vw_prop_casino_cards_01`

**Sounds** (11) - `dlc_vw_table_games_frontend_sounds`, `DLC_VW_Casino_Table_Games`, `DLC_VW_Casino_Cards_Focus_Hand`, `DLC_VW_CONTINUE`, `DLC_VW_ERROR_MAX`, `DLC_VW_RULES`, `dlc_vw_table_games_sounds`, `DLC_VW_BET_MAX`, `DLC_VW_BET_UP`, `DLC_VW_BET_DOWN`, `DLC_VW_WIN_CHIPS`

**Text labels** (2) - `NULL`, `NUMBER`

**Hashed names** (112) - `S_M_Y_Casino_01_WHITE_01`, `S_M_Y_Casino_01_ASIAN_01`, `S_F_Y_Casino_01_ASIAN_01`, `S_F_Y_Casino_01_ASIAN_02`, `S_F_Y_Casino_01_LATINA_01`, `vw_prop_vw_club_char_a_a`, `vw_prop_vw_club_char_02a`, `vw_prop_vw_club_char_03a`, `vw_prop_vw_club_char_04a`, `vw_prop_vw_club_char_05a`, `vw_prop_vw_club_char_06a`, `vw_prop_vw_club_char_07a`, `vw_prop_vw_club_char_08a`, `vw_prop_vw_club_char_09a`, `vw_prop_vw_club_char_10a`, `vw_prop_vw_club_char_j_a`, `vw_prop_vw_club_char_q_a`, `vw_prop_vw_club_char_k_a`, `vw_prop_vw_dia_char_a_a`, `vw_prop_vw_dia_char_02a`, `vw_prop_vw_dia_char_03a`, `vw_prop_vw_dia_char_04a`, `vw_prop_vw_dia_char_05a`, `vw_prop_vw_dia_char_06a`, `vw_prop_vw_dia_char_07a`, `vw_prop_vw_dia_char_08a`, `vw_prop_vw_dia_char_09a`, `vw_prop_vw_dia_char_10a`, `vw_prop_vw_dia_char_j_a`, `vw_prop_vw_dia_char_q_a`, `vw_prop_vw_dia_char_k_a`, `vw_prop_vw_hrt_char_a_a`, `vw_prop_vw_hrt_char_02a`, `vw_prop_vw_hrt_char_03a`, `vw_prop_vw_hrt_char_04a`, `vw_prop_vw_hrt_char_05a`, `vw_prop_vw_hrt_char_06a`, `vw_prop_vw_hrt_char_07a`, `vw_prop_vw_hrt_char_08a`, `vw_prop_vw_hrt_char_09a`, `vw_prop_vw_hrt_char_10a`, `vw_prop_vw_hrt_char_j_a`, `vw_prop_vw_hrt_char_q_a`, `vw_prop_vw_hrt_char_k_a`, `vw_prop_vw_spd_char_a_a`, `vw_prop_vw_spd_char_02a`, `vw_prop_vw_spd_char_03a`, `vw_prop_vw_spd_char_04a`, `vw_prop_vw_spd_char_05a`, `vw_prop_vw_spd_char_06a`, `vw_prop_vw_spd_char_07a`, `vw_prop_vw_spd_char_08a`, `vw_prop_vw_spd_char_09a`, `vw_prop_vw_spd_char_10a`, `vw_prop_vw_spd_char_j_a`, `vw_prop_vw_spd_char_q_a`, `vw_prop_vw_spd_char_k_a`, `vw_prop_cas_card_club_ace`, `vw_prop_cas_card_club_02`, `vw_prop_cas_card_club_03` ...

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (565), `NET_TO_OBJ` (144), `SET_PED_COMPONENT_VARIATION` (140), `NET_TO_PED` (133), `GET_HASH_KEY` (118), `SET_BIT` (107), `NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE` (93), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (89), `CLEAR_BIT` (89), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (82), `PLAYER_PED_ID` (68), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (66), `HAS_ANIM_EVENT_FIRED` (64), `NETWORK_REQUEST_CONTROL_OF_NETWORK_ID` (64), `NETWORK_CREATE_SYNCHRONISED_SCENE` (55), `NETWORK_START_SYNCHRONISED_SCENE` (55), `SET_ENTITY_VISIBLE` (51), `GET_SYNCHRONIZED_SCENE_PHASE` (43), `GET_ENTITY_BONE_INDEX_BY_NAME` (32), `GET_RANDOM_INT_IN_RANGE` (28), `IS_PED_INJURED` (23), `IS_ENTITY_PLAYING_ANIM` (22), `IS_CONTROL_PRESSED` (22), `REQUEST_MODEL` (21), `HAS_MODEL_LOADED` (21), `NETWORK_DOES_NETWORK_ID_EXIST` (20), `DOES_ENTITY_EXIST` (19), `IS_CONTROL_JUST_PRESSED` (19), `CLEAR_HELP` (19), `PLAY_SOUND_FRONTEND` (18)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x38 · `0.01f` x5 · `0.5f` x4 · `0.1f` x3 · `1.5f` x2 · `-52.0409f` x2 · `0.24f` x1 · `0.03f` x1 · `0.198f` x1 · `1.388f` x1 · `1133.74f` x1 · `266.6947f` x1 · `1148.74f` x1 · `251.6947f` x1

## Other strings

Literals whose consuming native was not classified:

`blend_out`, `TCP_TIME`, `TCP_WIN`, `DLC_VW_CHIP_BET_SML_MEDIUM`, `DLC_VW_CHIP_BET_SML_LARGE`, `Chair_Base_04`, `Chair_Base_03`, `Chair_Base_02`, `Chair_Base_01`, `DLC_VW_CHIP_BET_SML_SMALL`, `TCP_WAIT`, `win`, `TCP_WIN2`, `TCP_LOSE_PLAY2`, `idle_cardgames`, `CAS_MG_CTIME`, `CAS_MG_CBAN`, `CasinoUI_Cards_Three`, `CasinoUI_Cards_Three_High`, `quit`, `rm_GamingFloor_02`, `rm_GamingFloor_03`, `CAS_MG_NOCHIPS7`, `CAS_MG_NOCHIPS3`, `CAS_MG_LOWCHIPS7`, `CAS_MG_LOWCHIPS3`, `TCP_PLACE_ANTE`, `TCP_PLACE_PAIR`, `lose`, `DLC_VW_CHIP_BET_SML_SINGLE`

---

Source: `decompiled_scripts/three_card_poker.c`
