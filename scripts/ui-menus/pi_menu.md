# pi_menu.c

UI and menus script. 3 anim dicts; 2 scaleforms.

| | |
|---|---|
| Category | UI and menus |
| Total lines | 101,131 |
| Functions | 523 (60 unique, 463 shared) |
| Unique lines | 4,121 (4.1% of file) |

## Assets

**Animation dictionaries** (3) - `cellphone@self@michael@`, `cellphone@self@franklin@`, `cellphone@self@trevor@`

**Sounds** (6) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `BACK`, `SELECT`, `NAV_UP_DOWN`, `NAV_LEFT_RIGHT`, `CANCEL`

**Scaleform movies** (2) - `SET_TEXT`, `TEXTFIELD`

**Text labels** (1) - `NULL`

**Scripts launched** (31) - `michael1`, `prologue1`, `armenian1`, `appinternet`, `hao1`, `fanatic1`, `fanatic2`, `fanatic3`, `family2`, `lester1`, `michael2`, `michael4`, `franklin0`, `franklin2`, `carsteal3`, `fbi1`, `fbi2`, `fbi4`, `fbi5a`, `agency_heist2`, `agency_heist3a`, `agency_heist3b`, `docks_setup`, `docks_heista`, `docks_heistb`, `finale_heist2a`, `finale_heist2b`, `jewelry_setup1`, `jewelry_heist`, `rural_bank_heist`, `chop`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (124), `ARE_STRINGS_EQUAL` (59), `DISABLE_CONTROL_ACTION` (58), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (32), `GET_GAME_TIMER` (29), `REFRESH_WAYPOINT` (20), `SET_NEW_WAYPOINT` (19), `GET_DISTANCE_BETWEEN_COORDS` (15), `SET_INPUT_EXCLUSIVE` (14), `PLAY_SOUND_FRONTEND` (12), `IS_STRING_NULL_OR_EMPTY` (11), `GET_ENTITY_COORDS` (10), `IS_USING_KEYBOARD_AND_MOUSE` (8), `PLAYER_ID` (8), `SET_BIT` (7), `IS_CONTROL_JUST_PRESSED` (7), `IS_PED_INJURED` (6), `IS_DISABLED_CONTROL_PRESSED` (6), `CLEAR_BIT` (5), `IS_PED_IN_ANY_VEHICLE` (5), `SET_PLAYER_CONTROL` (5), `GET_HUD_COLOUR` (5), `GET_ENTITY_MODEL` (5), `HIDE_HUD_COMPONENT_THIS_FRAME` (4), `DOES_LATEST_BRIEF_STRING_EXIST` (4), `IS_DISABLED_CONTROL_JUST_RELEASED` (4), `TO_FLOAT` (4), `IS_CONTROL_PRESSED` (4), `IS_PAUSE_MENU_ACTIVE` (3), `GET_ACTUAL_SCREEN_RESOLUTION` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.05f` x2 · `0.225f` x2 · `0.25f` x2 · `0.5f` x1 · `-0.05f` x1 · `-0.0755f` x1 · `0.113f` x1 · `0.1125f` x1 · `0.003f` x1 · `0.7f` x1

## Other strings

Literals whose consuming native was not classified:

`PIM_FIB`, `PIM_CEXI`, `PIM_BIGS`, `PIM_TITLE1`, `PIM_THELP`, `PIM_TOBJ`, `PIM_MIKE`, `PIM_TINVE`, `PIM_QGPS0`, `CM_IN_TIT`, `PIM_FRANK`, `PIM_JEWEL`, `PIM_DOCKS`, `PIM_HECLTH`, `IMPOUND_TITLE`, `PIM_SHDE5`, `VEUI_HDR_ALERT`, `VE_DIR_MODE_SURE`, `PIM_TMASK`, `PIM_NHELM1`, `PROPS_P0_H2`, `PIM_P0_H2`, `PROPS_P0_E4_6`, `PIM_P0_E4_6`, `PROPS_P0_E5`, `PIM_P0_E5`, `PROPS_P0_E5_1`, `PIM_P0_E5_1`, `PROPS_P0_E5_2`, `PIM_P0_E5_2`

---

Source: `decompiled_scripts/pi_menu.c`
