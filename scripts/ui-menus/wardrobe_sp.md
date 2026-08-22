# wardrobe_sp.c

UI and menus script. 16 models; 2 scaleforms.

| | |
|---|---|
| Category | UI and menus |
| Total lines | 512,080 |
| Functions | 7,023 (151 unique, 6,872 shared) |
| Unique lines | 55,554 (10.8% of file) |

## Assets

**Models and props** (16) - `v_lirg_trevtrail_ward_main`, `v_lirg_trevtrail_ward_face`, `v_ilev_exball_blue`, `v_lirg_michael_ward_main`, `v_lirg_michael_ward_face`, `v_lirg_trevapt_ward_main`, `v_lirg_trevapt_ward_face`, `v_lirg_trevstrip_ward_main`, `v_lirg_trevstrip_ward_face`, `v_lirg_frankaunt_ward_main`, `v_lirg_frankaunt_ward_face`, `v_lirg_frankhill_ward_main`, `v_lirg_frankhill_ward_face`, `sm_prop_smug_hangar_wardrobe_lrig`, `v_lirg_mphigh_ward_main`, `v_lirg_mphigh_ward_face`

**Audio banks** (1) - `CLOTHES_STORE`

**Sounds** (5) - `HUD_FRONTEND_CLOTHESSHOP_SOUNDSET`, `SELECT`, `NAV_UP_DOWN`, `CANCEL`, `ERROR`

**Scaleform movies** (2) - `MP_MENU_GLARE`, `SET_DATA_SLOT`

**Text labels** (1) - `NULL`

**Scripts launched** (1) - `armenian1`

**Hashed names** (3) - `wardrobe_mp`, `wardrobe_sp`, `crewLogo`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (461), `DOES_SHOP_PED_APPAREL_HAVE_RESTRICTION_TAG` (383), `PLAYER_ID` (305), `NETWORK_IS_GAME_IN_PROGRESS` (113), `GET_ENTITY_MODEL` (72), `PLAY_SOUND_FRONTEND` (38), `IS_CONTROL_JUST_PRESSED` (37), `SET_ENTITY_HEADING` (24), `SET_ENTITY_COORDS` (22), `IS_PED_INJURED` (21), `CLEAR_BIT` (21), `GET_PED_TEXTURE_VARIATION` (18), `SET_BIT` (18), `GET_PED_DRAWABLE_VARIATION` (17), `IS_CONTROL_PRESSED` (17), `GET_HASH_KEY` (13), `GET_NETWORK_TIME` (12), `GET_GAME_TIMER` (12), `GET_HASH_NAME_FOR_COMPONENT` (12), `SET_INPUT_EXCLUSIVE` (11), `IS_STRING_NULL_OR_EMPTY` (9), `DOES_ENTITY_EXIST` (8), `RELEASE_PED_PRELOAD_PROP_DATA` (8), `RELEASE_PED_PRELOAD_VARIATION_DATA` (8), `IS_ENTITY_IN_ANGLED_AREA` (8), `GET_ENTITY_COORDS` (6), `SET_PED_COMPONENT_VARIATION` (6), `GET_THIS_SCRIPT_NAME` (6), `DISABLE_CONTROL_ACTION` (6), `GET_DISTANCE_BETWEEN_COORDS` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-3.654f` x4 · `0.75f` x4 · `976.0278f` x2 · `64.5337f` x2 · `115.1641f` x2 · `68.0287f` x2 · `-41.896f` x2 · `-1.348f` x2 · `0.05f` x2 · `2.5f` x2 · `176.7132f` x1 · `-1234.543f` x1 · `-2981.028f` x1 · `-42.2636f` x1 · `180.2719f` x1 · `371.1484f` x1 · `4819.47f` x1 · `-59.9884f` x1 · `-11.3927f` x1 · `-0.7271f` x1 · `0.004f` x1 · `1.0154f` x1 · `-1419.925f` x1 · `-3014.334f` x1

## Other strings

Literals whose consuming native was not classified:

`mp_m_freemode_01`, `mp_f_freemode_01`, `hood_up`, `player_one`, `tie`, `player_zero`, `tux_tie`, `player_two`, `tux_vest`, `heist_draw_1`, `vest_tie`, `ITEM_BACK`, `ITEM_MOV_CAM`, `pilot_suit`, `open_jacket`, `heist_draw_0`, `hood_down`, `luxe_draw_0`, `luxe_draw_2`, `loose_tie`, `loose_bowtie`, `sweat_vest`, `WARD_STAR`, `ITEM_SELECT`, `ITEM_SAVED`, `luxe2_draw_1`, `apart_draw_15`, `luxe2_draw_0`, `bowtie`, `outfit_only`

---

Source: `decompiled_scripts/wardrobe_sp.c`
