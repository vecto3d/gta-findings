# am_mp_mansion_art_workshop.c

Properties and venues script. 1 anim dicts; 1 models.

| | |
|---|---|
| Category | Properties and venues |
| Total lines | 498,696 |
| Functions | 8,582 (166 unique, 8,416 shared) |
| Unique lines | 17,075 (3.4% of file) |

## Assets

**Animation dictionaries** (1) - `anim@amb@warehouse@laptop@`

**Models and props** (1) - `v_res_fh_speakerdock`

**Audio banks** (1) - `DLC_HEIST3/Door_Hacking`

**Sounds** (14) - `DLC_25-2_Mansion_Basement_Scene`, `Hack_Failed`, `Cursor_Choose_Good`, `Cursor_Choose_Bad`, `Hack_Success`, `Play_Start`, `New_Line_Flash`, `Dot_Sequence_Change`, `Dot_Sequence_Choose_Flash`, `Section_Success_Window_Appears`, `Section_Success_Window_Cleared`, `Scramble_Countdown_Low`, `Scramble_Countdown_High`, `Scramble_Countdown_Med`

**Texture dicts** (13) - `MPBeamHack`, `MPHackingGame`, `MPHackingGameBG`, `MPHackingGameWin`, `MPHackingGameWin1`, `MPHackingGameWin2`, `MPHackingGameWin2_1`, `MPHackingGameWin2_2`, `MPHackingGameWin2_3`, `MPHackingGameWin3`, `MPHackingGameoverlay`, `MPHackingGameoverlay1`, `Fail`

**Text labels** (1) - `NULL`

**Interiors and entity sets** (20) - `SET_DRILLS`, `SET_GLASS_CUTTER`, `SET_HACKING`, `SET_TRACKER`, `SET_CARD`, `SET_HACKING_USB`, `SET_HAZMAT`, `SET_MAIL_SUITS`, `SET_MILITARY_WEAPONS`, `SET_STEALTH_WEAPONS`, `SET_STREET_WEAPONS`, `SET_TACTICAL`, `SET_VAULT_DOOR`, `SET_THERMITE`, `SET_MANHOLE`, `SET_CHAIR_EASEL`, `SET_CHAIR_DESK`, `SET_VAULT_HACKING_OG`, `SET_VAULT_HACKING_ANGEL`, `SET_VAULT_HACKING_HAVILAND`

**Scripts launched** (1) - `AM_MP_BOARDROOM_SEATING`

**Hashed names** (1) - `AM_MP_BOARDROOM_SEATING`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (73), `PLAYER_ID` (64), `CLEAR_BIT` (52), `PLAYER_PED_ID` (50), `DEACTIVATE_INTERIOR_ENTITY_SET` (34), `ACTIVATE_INTERIOR_ENTITY_SET` (20), `PLAY_SOUND_FRONTEND` (14), `SET_STREAMED_TEXTURE_DICT_AS_NO_LONGER_NEEDED` (11), `DOES_ENTITY_EXIST` (10), `IS_SCREEN_FADED_OUT` (9), `SET_PED_CONFIG_FLAG` (7), `IS_SCREEN_FADED_IN` (6), `GET_PLAYER_PED` (6), `IS_ENTITY_IN_ANGLED_AREA` (6), `NETWORK_IS_GAME_IN_PROGRESS` (5), `GET_HASH_KEY` (5), `GET_RANDOM_INT_IN_RANGE` (5), `IS_PED_INJURED` (5), `TO_FLOAT` (5), `DO_SCREEN_FADE_OUT` (5), `INT_TO_PARTICIPANTINDEX` (4), `HAS_SCRIPT_LOADED` (4), `SET_SCRIPT_AS_NO_LONGER_NEEDED` (4), `IS_NEW_LOAD_SCENE_ACTIVE` (4), `IS_USING_KEYBOARD_AND_MOUSE` (4), `HAS_STREAMED_TEXTURE_DICT_LOADED` (4), `REQUEST_STREAMED_TEXTURE_DICT` (4), `IS_VALID_INTERIOR` (4), `IS_INTERIOR_READY` (4), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x5 · `0.99f` x3 · `1.6f` x2 · `0.2f` x1 · `0.7f` x1 · `0.41f` x1 · `2591.384f` x1 · `5963.128f` x1 · `2591.376f` x1 · `5956.465f` x1 · `-47.032f` x1 · `1.4f` x1 · `2590.528f` x1 · `5962.179f` x1 · `-49.99994f` x1 · `2590.922f` x1 · `5961.366f` x1 · `-47.87494f` x1 · `293.2119f` x1 · `344.496f` x1 · `4876.871f` x1 · `-62.43793f` x1 · `355.2799f` x1 · `4865.131f` x1

## Other strings

Literals whose consuming native was not classified:

`mporderunlock`, `innercircle_fill`, `correct_circles`, `incorrect_circles`, `MP_1`, `inner_circles`, `Inner_Circles`, `mphackinggame`, `idle_a`, `AM_MP_BOARDROOM_SEATING`, `MANS_ART_HACK_N`, `mansion_art_workshop_seating`, `HELP_KORTZ_KPAD`, `OUN_FAIL`, `MPOrderUnlock_Decor1`, `MPBeamHack`, `DLC_Gen_Hack_Door_Minigame_Sounds`, `DLC_H3_Cas_Door_Minigame_Sounds`, `selector`, `Scrambler_BG`, `Scrambler_Fill_Segment`, `MAINTAIN_MANSION_ART_WORKSHOP_RENOVATION - Entity sets need updated`, `PERFORM_MANSION_ART_WORKSHOP_RENOVATION - Renovation complete`, `No reason given - This is bad!`, `BLIP_MP_HEIST`, `K26_PLN_BOARD`, `KEWP_BLP_2`, `SUM26_HEIST_INT`, `DLC_mp2026_01_ART_WORKSHOP_CS`, `SE_m26_1_int_art_worshop_GtaMloRoom001`

---

Source: `decompiled_scripts/am_mp_mansion_art_workshop.c`
