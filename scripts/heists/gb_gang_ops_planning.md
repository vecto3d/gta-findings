# gb_gang_ops_planning.c

Heists script. 1 models; 28 scaleforms.

| | |
|---|---|
| Category | Heists |
| Total lines | 31,091 |
| Functions | 867 (290 unique, 577 shared) |
| Unique lines | 12,007 (38.6% of file) |

## Assets

**Models and props** (1) - `Prop_x17DLC_Monitor_Wall_01a`

**Audio banks** (1) - `DLC_MPHEIST/HEIST_PLANNING_BOARD`

**Sounds** (20) - `Nav_Blocked`, `Select`, `Nav_Up_Down_Photo_Change`, `Nav_Left_Right`, `Error`, `Use`, `Back`, `Nav_Up_Down`, `Draw_Board`, `Bootup`, `Background`, `x`, `y`, `scale`, `Nav_Left_Right_Photo_Change`, `Pay`, `Finale_Available`, `Launch_Mission`, `Decrease_Loot_Share`, `Increase_Loot_Share`

**Scaleform movies** (28) - `DISABLE_NAVIGATION`, `GET_CURRENT_SELECTION`, `ENABLE_NAVIGATION`, `IAA_HEIST_BOARD`, `INSTRUCTIONAL_BUTTONS`, `SET_LAUNCH_STATE`, `UPDATE_FINALE_PLAYER_STATUS`, `UPDATE_FINALE_PLAYER_ROLE`, `SET_SPY_CAM_TEXTURES`, `REMOVE_FINALE_PLAYER`, `SET_FINALE_PLAYER`, `UPDATE_FINALE_PLAN`, `ADD_MAP_MARKER`, `REMOVE_MAP_MARKER`, `SET_MAP_DISPLAY`, `UPDATE_CASH_DISTRIBUTION`, `SET_ACTIVE_ITEM_SELECTED`, `SHOW_FINALE`, `SHOW_SETUP`, `SET_SETUP_MISSION`, `SET_CURRENT_SELECTION`, `PULSE_ELEMENT`, `FLASH_ACTIVE_ELEMENT`, `SHOW_LAUNCH`, `HEIST_SETUP`, `SHOW_REPLAY`, `SET_REPLAY_MISSION`, `HEIST_REPLAY`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (103), `NETWORK_PLAYER_ID_TO_INT` (87), `PLAY_SOUND_FROM_COORD` (86), `CLEAR_BIT` (68), `SET_BIT` (66), `BEGIN_SCALEFORM_MOVIE_METHOD` (23), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (23), `GET_FILENAME_FOR_AUDIO_CONVERSATION` (22), `END_SCALEFORM_MOVIE_METHOD` (20), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_TEXTURE_NAME_STRING` (20), `IS_USING_KEYBOARD_AND_MOUSE` (19), `PLAYER_PED_ID` (14), `IS_CONTROL_JUST_PRESSED` (13), `INT_TO_PLAYERINDEX` (13), `CLEAR_HELP` (12), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_BOOL` (12), `NETWORK_IS_ACTIVITY_SESSION` (9), `IS_CONTROL_JUST_RELEASED` (9), `CALL_SCALEFORM_MOVIE_METHOD` (9), `SET_SCRIPT_GFX_DRAW_BEHIND_PAUSEMENU` (8), `SET_TEXT_RENDER_ID` (8), `DOES_TEXT_LABEL_EXIST` (8), `ABSI` (8), `GET_CONTROL_INSTRUCTIONAL_BUTTONS_STRING` (8), `CEIL` (6), `SET_VARIABLE_ON_SOUND` (6), `REQUEST_SCALEFORM_MOVIE` (6), `DISABLE_CONTROL_ACTION` (5), `IS_ENTITY_IN_ANGLED_AREA` (5), `IS_STRING_NULL_OR_EMPTY` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.501f` x4 · `0.5f` x4 · `350.8064f` x3 · `4872.391f` x3 · `-61.79424f` x3 · `-58.35142f` x3 · `1.75f` x3 · `-56.74947f` x2 · `353.7038f` x1 · `4877.579f` x1 · `-61.60188f` x1 · `348.4844f` x1 · `4866.69f` x1 · `346.1474f` x1 · `4868.041f` x1 · `346.9441f` x1 · `4866.924f` x1 · `0.19f` x1 · `353.7142f` x1 · `4877.06f` x1 · `-59.14812f` x1 · `345.1879f` x1 · `4864.415f` x1 · `-60.02681f` x1

## Other strings

Literals whose consuming native was not classified:

`HEIST_IB_ZOOM`, `HEIST_IB_LOOK`, `HEIST_IB_NAV`, `HEIST_IB_QUIT`, `1_1_prep_spy_mid1`, `2_1_setup_spy_mid1`, `3_1_B_prep_spy_mid1`, `HP_OVERVIEW`, `HP_SURVEIL`, `HP_MAP`, `HP_TUT_WAIT`, `1_3_Prep_spy_mid2`, `2_4_setup_spy_mid2`, `3_3_prep_spy_mid2`, `1_FINALE_spy_mid1`, `1_1_setup_spy_mid1`, `1_2_Prep_spy_mid1`, `1_2_Setup_spy_mid1`, `1_3_Prep_spy_mid1`, `1_3_Setup_spy_mid1`, `2_FINALE_spy_mid1`, `2_1_Prep_spy_mid1`, `2_2_Prep_spy_mid1`, `2_2_setup_spy_mid1`, `2_3_Prep_spy_mid1`, `2_3_setup_spy_mid1`, `2_4_A_Prep_spy_mid1`, `2_4_B_Prep_spy_mid1`, `2_4_setup_spy_mid1`, `3_finale_spy_mid1`

---

Source: `decompiled_scripts/gb_gang_ops_planning.c`
