# mp_weapons.c

MP freemode script. 8 scaleforms.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 15,840 |
| Functions | 167 (39 unique, 128 shared) |
| Unique lines | 5,749 (36.3% of file) |

## Assets

**Sounds** (4) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `NAV_LEFT_RIGHT`, `BACK`, `SELECT`

**Scaleform movies** (8) - `SET_COLUMN_TITLE`, `MENU_SHIFT_DEPTH`, `SET_DATA_SLOT`, `DISPLAY_DATA_SLOT`, `SET_COLUMN_HIGHLIGHT`, `SET_DESCRIPTION`, `SET_INPUT_EVENT`, `SET_COLUMN_SCROLL`

**Texture dicts** (3) - `MPWeaponsCommon`, `MPWeaponsGang0`, `MPWeaponsGang1`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`TO_FLOAT` (195), `IS_WEAPON_VALID` (144), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (56), `BEGIN_SCALEFORM_MOVIE_METHOD_ON_FRONTEND` (19), `END_SCALEFORM_MOVIE_METHOD` (19), `PLAY_SOUND_FRONTEND` (7), `IS_CONTROL_PRESSED` (6), `HAS_PED_GOT_WEAPON` (5), `PLAYER_PED_ID` (5), `SET_BIT` (4), `CLEAR_BIT` (4), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_BOOL` (4), `NETWORK_IS_GAME_IN_PROGRESS` (4), `WAIT` (3), `REQUEST_STREAMED_TEXTURE_DICT` (3), `HAS_STREAMED_TEXTURE_DICT_LOADED` (3), `ARE_STRINGS_EQUAL` (3), `FORCE_SCRIPTED_GFX_WHEN_FRONTEND_ACTIVE` (2), `SET_SCRIPT_GFX_DRAW_ORDER` (2), `PAUSE_MENU_ACTIVATE_CONTEXT` (2), `PAUSE_MENU_REDRAW_INSTRUCTIONAL_BUTTONS` (2), `RELEASE_CONTROL_OF_FRONTEND` (2), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_FLOAT` (2), `ADD_TEXT_COMPONENT_INTEGER` (2), `NETWORK_SET_SCRIPT_IS_SAFE_FOR_NETWORK_GAME` (1), `IS_FRONTEND_READY_FOR_CONTROL` (1), `TAKE_CONTROL_OF_FRONTEND` (1), `PAUSE_MENU_DEACTIVATE_CONTEXT` (1), `HAS_MENU_TRIGGER_EVENT_OCCURRED` (1), `GET_MENU_TRIGGER_EVENT_DETAILS` (1)

## Other strings

Literals whose consuming native was not classified:

`component_at_ar_flsh`, `component_at_ar_afgrip`, `component_at_ar_supp_02`, `component_at_pi_supp`, `component_at_pi_flsh`, `component_at_ar_supp`, `component_at_scope_medium_mk2`, `component_at_scope_macro_mk2`, `component_at_scope_small`, `WCD_MK1_LOCK`, `component_gunrun_mk2_upgrade`, `component_at_scope_macro`, `component_at_scope_medium`, `component_at_scope_max`, `component_at_scope_large`, `component_at_ar_afgrip_02`, `component_at_sights`, `component_at_scope_macro_02_smg_mk2`, `component_at_scope_small_smg_mk2`, `component_pistol_clip_02`, `component_at_pi_supp_02`, `component_pistol50_clip_02`, `component_combatpistol_clip_02`, `component_appistol_clip_02`, `component_microsmg_clip_02`, `component_assaultsmg_clip_02`, `component_smg_clip_02`, `component_smg_clip_03`, `component_assaultrifle_clip_02`, `component_assaultrifle_clip_03`

---

Source: `decompiled_scripts/mp_weapons.c`
