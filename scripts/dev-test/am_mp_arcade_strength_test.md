# am_mp_arcade_strength_test.c

Dev and test harnesses script. 4 anim dicts; 15 scaleforms.

| | |
|---|---|
| Category | Dev and test harnesses |
| Total lines | 89,349 |
| Functions | 752 (149 unique, 603 shared) |
| Unique lines | 3,278 (3.7% of file) |

## Assets

**Animation dictionaries** (4) - `clipset@anim_heist@arcade@strength@male`, `clipset@anim_heist@arcade@strength@female`, `ANIM_HEIST@ARCADE@STRENGTH@MALE@`, `ANIM_HEIST@ARCADE@STRENGTH@FEMALE@`

**Animations** (5) - `ENTER`, `RESULT_PERFECT`, `RESULT_GOOD`, `RESULT_AVERAGE`, `RESULT_BAD`

**Sounds** (1) - `sum20_am_Axe_of_Fury_sounds`

**Scaleform movies** (15) - `SET_INSTANT_HIGH_SCORE`, `SET_SCORE`, `SET_INSTANT_SCORE`, `SET_METER_FILL_VALUE`, `FLASH_BUTTON`, `HIDE`, `FLASH_METER`, `SET_METER_BAR_VALUE`, `SET_BUTTON_VISIBLE`, `SET_METER_BAR_ICON_VISIBLE`, `SET_IS_KEYBOARD_CONTROL`, `SET_METER_BAR_LINE_VISIBLE`, `SHOW`, `SET_SCREEN_POSITION`, `AXE_OF_FURY`

**Texture dicts** (1) - `SCORE_DISPLAY_AXE_OF_FURY`

**Text labels** (2) - `NULL`, `DEFAULT`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (50), `TO_FLOAT` (45), `CLEAR_BIT` (45), `SET_BIT` (33), `PLAYER_ID` (25), `GET_NETWORK_TIME` (16), `BEGIN_SCALEFORM_MOVIE_METHOD` (14), `END_SCALEFORM_MOVIE_METHOD` (14), `ROUND` (12), `DOES_ENTITY_EXIST` (10), `GET_PLAYER_PED` (9), `NETWORK_IS_PLAYER_A_PARTICIPANT` (9), `_SEND_TU_SCRIPT_EVENT_NEW` (8), `GET_EVENT_DATA` (8), `ABSI` (7), `GET_TIME_DIFFERENCE` (7), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_FLOAT` (7), `GET_ENTITY_HEADING` (6), `SET_ENTITY_ALPHA` (5), `DOES_CAM_EXIST` (5), `IS_TIME_LESS_THAN` (5), `SET_TEXT_RENDER_ID` (5), `GET_ENTITY_COORDS` (5), `IS_TASK_MOVE_NETWORK_ACTIVE` (5), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (5), `NETWORK_HAS_CONTROL_OF_ENTITY` (5), `FLOOR` (5), `IS_ENTITY_PLAYING_ANIM` (5), `GET_TIME_OFFSET` (4), `GET_ENTITY_MODEL` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x5 · `0.05f` x3 · `1.4101f` x2 · `2.2f` x2 · `0.99f` x2 · `0.5909f` x1 · `0.4f` x1 · `0.375f` x1 · `0.525f` x1 · `0.575f` x1 · `2.3f` x1 · `0.01f` x1

## Other strings

Literals whose consuming native was not classified:

`ARC_CAB_AOF_MLTPLR`, `ARC_CAB_AOF_POW`, `ARC_CAB_AOF_MLTPLR_ALT`, `ARC_CAB_AOF_POW_ALT`, `ARC_CAB_TRI_STRET`, `SMALL_EXPLOSION_SHAKE`, `AM_MP_ARCADE`, `Weight`, `ArcadeUI_Axe_of_Fury`, `STRENGTH_TEST_SCORE`, `sum_prop_arcade_strength_01a`, `sum_prop_arcade_str_bar_01a`, `arc_strenght_01a`, `arc_strenght_02a`, `End_Game`, `ARC_CAB_TRI_RSTRET`, `ARC_CAB_AOF_HUD_POW`, `ARD_CAB_AOF_TROP1`, `Button_Mash_Hit`, `STRENGTH_RING_BELL`, `Hit_00`, `Hit_01`, `Hit_02`, `Result_00`, `Result_01`, `Result_02`, `Result_03`, `Result_04`, `Result_05`, `ENTER_FACIAL`

---

Source: `decompiled_scripts/am_mp_arcade_strength_test.c`
