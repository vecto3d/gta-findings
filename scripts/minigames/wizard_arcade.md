# wizard_arcade.c

Minigames script.

| | |
|---|---|
| Category | Minigames |
| Total lines | 105,073 |
| Functions | 822 (190 unique, 632 shared) |
| Unique lines | 14,223 (13.5% of file) |

## Assets

**Texture dicts** (19) - `MPWizardsSleeveBackgrounds12`, `MPWizardsSleeveBackgrounds34`, `MPWizardsSleeveCharacters`, `MPWizardsSleeveEnemies1a`, `MPWizardsSleeveEnemies1b`, `MPWizardsSleeveEnemies2`, `MPWizardsSleeveEnemies3a`, `MPWizardsSleeveEnemies3b`, `MPWizardsSleeveEnemies4a`, `MPWizardsSleeveEnemies4b`, `MPWizardsSleeveFacade`, `MPWizardsSleeveGrog`, `MPWizardsSleeveHUDAndScreen`, `MPWizardsSleeveHUDAndScreen2`, `MPWizardsSleeveIntro`, `MPWizardsSleeveIntroMenu`, `MPWizardsSleeveItemsAndFX`, `MPWizardsSleeveThog12`, `MPWizardsSleeveThog3NPC`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`GET_GAME_TIMER` (245), `TIMESTEP` (113), `GET_RANDOM_FLOAT_IN_RANGE` (60), `ABSF` (49), `GET_RANDOM_INT_IN_RANGE` (28), `SET_CONTROL_SHAKE` (25), `SIN` (23), `IS_CONTROL_JUST_PRESSED` (23), `ROUND` (22), `TRIGGER_MUSIC_EVENT` (19), `REQUEST_STREAMED_TEXTURE_DICT` (19), `HAS_STREAMED_TEXTURE_DICT_LOADED` (19), `SET_STREAMED_TEXTURE_DICT_AS_NO_LONGER_NEEDED` (19), `IS_CONTROL_PRESSED` (13), `SET_BIT` (9), `GET_FRAME_TIME` (8), `FLOOR` (8), `TO_FLOAT` (8), `PLAYER_ID` (4), `IS_USING_KEYBOARD_AND_MOUSE` (4), `GET_DISABLED_CONTROL_NORMAL` (3), `GET_NETWORK_TIME` (3), `NETWORK_IS_GAME_IN_PROGRESS` (2), `IS_DISABLED_CONTROL_PRESSED` (2), `GET_HASH_KEY` (1), `SET_BINK_MOVIE` (1), `PLAY_BINK_MOVIE` (1), `SET_BINK_SHOULD_SKIP` (1), `SET_BINK_MOVIE_AUDIO_FRONTEND` (1), `GET_PLAYER_INDEX` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.8f` x9 · `0.4f` x8 · `1.1f` x7 · `0.6f` x5 · `0.3f` x5 · `0.75f` x5 · `1.2f` x4 · `0.45f` x4 · `0.5f` x3 · `1.25f` x2 · `-0.65f` x1 · `0.65f` x1 · `0.9f` x1 · `0.35f` x1

## Other strings

Literals whose consuming native was not classified:

`MPWizardsSleeveItemsAndFX`, `MPWizardsSleeveHUDAndScreen`, `fx_player-enemy_shadow`, `hud_numbers_`, `MPWizardsSleeveEnemies1b`, `MPWizardsSleeveIntroMenu`, `MPWizardsSleeveBackgrounds34`, `hurt`, `MPWizardsSleeveEnemies4b`, `MPWizardsSleeveEnemies2`, `attack`, `climb1-in air`, `kill`, `MPWizardsSleeveIntro`, `ARCADE_WR_THEME_START`, `MPWizardsSleeveEnemies1a`, `MPWizardsSleeveEnemies3a`, `idle`, `Screen_Position`, `ARCADE_WR_FOREST_START`, `ARCADE_WR_SWAMP_START`, `ARCADE_WR_LABRYNTH_START`, `ARCADE_WR_CASTLE_START`, `DLC_HEIST3/H3_ArcMac_Wiz_01`, `DLC_HEIST3/H3_ArcMac_Wiz_02`, `DEG_GAME_QUIT`, `ARCADE_WR_STOP`, `meter_fill_hp`, `MPWizardsSleeveBackgrounds12`

---

Source: `decompiled_scripts/wizard_arcade.c`
