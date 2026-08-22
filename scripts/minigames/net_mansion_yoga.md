# net_mansion_yoga.c

Minigames script. 1 anim dicts; 16 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 93,314 |
| Functions | 460 (57 unique, 403 shared) |
| Unique lines | 2,239 (2.4% of file) |

## Assets

**Animation dictionaries** (1) - `anim@scripted@freemode@ig9_yoga@male@`

**Animations** (20) - `enter_01_player`, `idle_01_player`, `trans_02_player`, `idle_02_player`, `trans_03_player`, `idle_03_player`, `trans_04_player`, `idle_04_player`, `trans_05_player`, `idle_05_player`, `trans_06_player`, `idle_06_player`, `trans_07_player`, `idle_07_player`, `trans_08_player`, `idle_08_player`, `trans_09_player`, `idle_09_player`, `trans_10_player`, `idle_10_player`

**Sounds** (6) - `YOGA_MINIGAME_TRANQUIL`, `FAMILY_5_SOUNDS`, `YOGA_EXHALE`, `Version`, `YOGA_FAIL`, `YOGA_INHALE`

**Scaleform movies** (16) - `REPLACE_KEYS_WITH_STICK`, `REPLACE_STICK_WITH_KEYS`, `HIDE_STICK_POINTER`, `SET_STICK_POINTER_ANGLE`, `SET_STICK_POINTER_RGB`, `REMOVE_BUTTONS`, `BUTTON_PRESSED`, `BUTTON_DEPRESSED`, `SET_BUTTON_TARGET`, `ADD_BUTTON_TO_LIST`, `SET_PLAYER_INPUT_COLOUR`, `SET_STICK_POINTER_HIGHLIGHT_ANGLE`, `yoga_buttons`, `yoga_keys`, `DRAW_BUTTONS`, `instructional_buttons`

**Text labels** (3) - `STICKS`, `NULL`, `YOGA`

**Timecycle modifiers** (1) - `STONED_CUTSCENE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (64), `PLAYER_PED_ID` (40), `BEGIN_SCALEFORM_MOVIE_METHOD` (30), `END_SCALEFORM_MOVIE_METHOD` (30), `IS_ENTITY_PLAYING_ANIM` (20), `PLAYER_ID` (14), `CLEAR_HELP` (12), `IS_PED_INJURED` (10), `IS_PC_VERSION` (9), `HAS_SOUND_FINISHED` (9), `SETTIMERA` (8), `IS_USING_KEYBOARD_AND_MOUSE` (8), `IS_CONTROL_PRESSED` (8), `TIMERA` (7), `SET_PLAYER_CONTROL` (6), `CLEAR_TIMECYCLE_MODIFIER` (6), `GET_SYNCHRONIZED_SCENE_PHASE` (6), `NETWORK_CREATE_SYNCHRONISED_SCENE` (6), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (6), `NETWORK_START_SYNCHRONISED_SCENE` (6), `TO_FLOAT` (6), `TIMESTEP` (6), `RENDER_SCRIPT_CAMS` (5), `IS_HELP_MESSAGE_BEING_DISPLAYED` (4), `CLEAR_PED_DAMAGE_DECAL_BY_ZONE` (4), `SET_SCALEFORM_MOVIE_AS_NO_LONGER_NEEDED` (4), `GET_SHOP_PED_COMPONENT` (4), `STOP_SOUND` (4), `PLAY_SOUND_FROM_ENTITY` (4), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x5 · `0.99f` x4 · `0.513f` x3 · `2.3f` x1 · `0.1f` x1 · `9.25f` x1 · `1.5f` x1

## Other strings

Literals whose consuming native was not classified:

`blushing`, `STICKS_KM`, `INHALE_NEW`, `EXHALE_NEW`, `PLAY_YOGA`, `DLC_MP_APA_F_FEET_1_0`, `DLC_MP_APA_M_FEET_1_0`, `MGYG_POSITION_COMPLETE`, `exit_10_player`, `YOGA_MANS_HELP`, `Yoga`, `MGYG_END`, `morph_suit`, `stunt_draw_0`, `exit_01_player`, `exit_02_player`, `exit_03_player`, `exit_04_player`, `exit_05_player`, `exit_06_player`, `exit_07_player`, `exit_08_player`, `exit_09_player`, `idle_01_player`, `H_YOGA_QUIT`, `HUD_INPUT87`, `enter_01_player`, `trans_02_player`, `idle_02_player`, `trans_03_player`

---

Source: `decompiled_scripts/net_mansion_yoga.c`
