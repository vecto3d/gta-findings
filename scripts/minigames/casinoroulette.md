# casinoroulette.c

Minigames script. 5 anim dicts; 17 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 380,154 |
| Functions | 7,413 (775 unique, 6,638 shared) |
| Unique lines | 24,612 (6.5% of file) |

## Assets

**Animation dictionaries** (5) - `anim_casino_b@amb@casino@games@roulette@player`, `anim_casino_b@amb@casino@games@shared@player@`, `anim_casino_b@amb@casino@games@roulette@dealer`, `anim_casino_b@amb@casino@games@roulette@dealer_female`, `anim_casino_b@amb@casino@games@roulette@table`

**Models and props** (17) - `vw_prop_chip_10dollar_x1`, `vw_prop_roulette_ball`, `vw_prop_casino_roulette_01`, `vw_prop_casino_roulette_01b`, `vw_prop_chip_10dollar_st`, `vw_prop_chip_50dollar_st`, `vw_prop_chip_100dollar_st`, `vw_prop_chip_500dollar_st`, `vw_prop_chip_1kdollar_st`, `vw_prop_chip_5kdollar_st`, `vw_prop_chip_10kdollar_st`, `vw_prop_chip_50dollar_x1`, `vw_prop_chip_100dollar_x1`, `vw_prop_chip_500dollar_x1`, `vw_prop_chip_1kdollar_x1`, `vw_prop_chip_5kdollar_x1`, `vw_prop_chip_10kdollar_x1`

**Sounds** (2) - `DLC_VW_Casino_Table_Games`, `DLC_VW_Casino_Roulette_Focus_Wheel`

**Text labels** (3) - `NULL`, `CAS_MG_MEMB2`, `NUMBER`

**Interiors and entity sets** (2) - `rm_GamingFloor_02`, `rm_GamingFloor_03`

**Hashed names** (41) - `none`, `BLEND_OUT`, `S_M_Y_Casino_01_WHITE_01`, `READY_UP_START`, `S_M_Y_Casino_01_ASIAN_01`, `S_F_Y_Casino_01_ASIAN_01`, `S_F_Y_Casino_01_ASIAN_02`, `S_F_Y_Casino_01_LATINA_01`, `high stakes`, `standard`, `s_f_y_casino_01`, `S_M_Y_Casino_01`, `S_M_Y_Casino_01_ASIAN_02`, `S_M_Y_Casino_01_WHITE_02`, `S_F_Y_Casino_01_LATINA_02`, `CLEAR_CHIPS_ZONE_THREE`, `CLEAR_CHIPS_ZONE_TWO`, `CLEAR_CHIPS_ZONE_ONE`, `end_result`, `SHOW_BALL`, `default_loop_position`, `BREAK_OUT`, `roulette is blocked`, `no access to highstakes tables`, `no membership`, `no chips`, `low chips`, `win cutoff`, `loss cutoff`, `time cutoff`, `vw_prop_vw_marker_01a`, `vw_prop_vw_marker_02a`, `Roulette`, `VIP membership`, `Paid membership`, `Gang membership`, `No membership`, `black`, `red`, `green`, `SHOWUI`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (140), `PLAYER_ID` (67), `GET_HASH_KEY` (58), `CLEAR_BIT` (54), `SET_BIT` (51), `DOES_ENTITY_EXIST` (44), `PLAYER_PED_ID` (30), `SET_MODEL_AS_NO_LONGER_NEEDED` (22), `REQUEST_MODEL` (22), `HAS_MODEL_LOADED` (21), `BEGIN_TEXT_COMMAND_DISPLAY_HELP` (17), `SET_ENTITY_VISIBLE` (16), `END_TEXT_COMMAND_DISPLAY_HELP` (16), `SET_PED_VOICE_GROUP` (14), `SET_PED_DEFAULT_COMPONENT_VARIATION` (14), `IS_CONTROL_PRESSED` (14), `NETWORK_DOES_NETWORK_ID_EXIST` (12), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (11), `NET_TO_PED` (11), `DOES_ENTITY_HAVE_DRAWABLE` (11), `HAS_ANIM_DICT_LOADED` (10), `IS_ENTITY_PLAYING_ANIM` (10), `FORCE_ENTITY_AI_AND_ANIMATION_UPDATE` (10), `PLAY_SOUND_FRONTEND` (9), `GET_CONTROL_INSTRUCTIONAL_BUTTONS_STRING` (9), `HAS_ANIM_EVENT_FIRED` (8), `DELETE_OBJECT` (8), `GET_CONTROL_NORMAL` (8), `IS_CONTROL_JUST_PRESSED` (8), `IS_USING_KEYBOARD_AND_MOUSE` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x4 · `0.6f` x3 · `0.125f` x2 · `0.01f` x2 · `0.24f` x1 · `0.081287f` x1 · `2.718282f` x1 · `0.45f` x1 · `0.35f` x1

## Other strings

Literals whose consuming native was not classified:

`quit`, `EMPTY_TABLE_IDLE_VAR01`, `IDLE_VAR01`, `REACTION_DEFLATED_VAR01_SEAT1`, `REACTION_TERRIBLE_VAR01_SEAT1`, `REACTION_NO_BET_VAR01_SEAT1`, `REACTION_GREAT_VAR01_SEAT1`, `REACTION_BAD_VAR01_SEAT1`, `REACTION_GOOD_VAR01_SEAT1`, `ROUL_PROMPT`, `CAS_MG_MEMB_PF`, `EMPTY_TABLE_IDLE_VAR02`, `IDLE_VAR02`, `IDLE_VAR03`, `IDLE_VAR04`, `IDLE_VAR05`, `Error`, `READY_UP_HIGH_BET_LOOP_SEAT1`, `READY_UP_MID_BET_LOOP_SEAT1`, `READY_UP_NO_BET_LOOP_SEAT1`, `READY_UP_HIGH_BET_INTRO_SEAT1`, `READY_UP_MID_BET_INTRO_SEAT1`, `READY_UP_NO_BET_INTRO_SEAT1`, `REACTION_DEFLATED_VAR01_SEAT2`, `REACTION_DEFLATED_VAR01_SEAT3`, `REACTION_DEFLATED_VAR01_SEAT4`, `REACTION_TERRIBLE_VAR01_SEAT2`, `REACTION_TERRIBLE_VAR01_SEAT3`, `REACTION_TERRIBLE_VAR01_SEAT4`, `REACTION_NO_BET_VAR01_SEAT2`

---

Source: `decompiled_scripts/casinoroulette.c`
