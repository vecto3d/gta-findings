# gunslinger_arcade.c

Minigames script. 17 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 102,948 |
| Functions | 974 (324 unique, 650 shared) |
| Unique lines | 12,810 (12.4% of file) |

## Assets

**Models and props** (17) - `PROP_CACTUS_02`, `PROP_CACTUS_03`, `PROP_CACTUS_04`, `PROP_CACTUS_05`, `PROP_CACTUS_06`, `PROP_CACTUS_07`, `PROP_CACTUS_08`, `PROP_CACTUS_09`, `PROP_BUSH_SMALL`, `PROP_BUSH_LARGE`, `PROP_ROCK_SMALL`, `PROP_ROCK_LARGE`, `PROP_STACKED_CRATES_01`, `PROP_STACKED_CRATES_02`, `PROP_BARRELS`, `PROP_TNT_CRATE_STATE_01`, `PROP_TNT_CRATE_STATE_0`

**Audio banks** (1) - `DLC_HEIST3/H3_ArcMac_BR2`

**Sounds** (4) - `Screen_Position`, `dlc_ch_am_br_in_menus_scene`, `dlc_ch_am_br_in_gameplay_scene`, `dlc_ch_badlands_revenge_powerup_active_scene`

**Text labels** (9) - `LVL0`, `LVL01`, `LVL02`, `LVL03`, `LVL04`, `NULL`, `LVL05`, `UNKNOWN`, `LEADERBOARDS`

## Native vocabulary

Most-called natives inside the code unique to this script:

`GET_GAME_TIMER` (63), `PARTICIPANT_ID_TO_INT` (48), `ARE_STRINGS_EQUAL` (34), `ROUND` (27), `SET_BIT` (27), `TO_FLOAT` (24), `PLAYER_ID` (19), `REQUEST_STREAMED_TEXTURE_DICT` (16), `HAS_STREAMED_TEXTURE_DICT_LOADED` (16), `FLOOR` (13), `GET_FRAME_TIME` (13), `IS_DISABLED_CONTROL_JUST_PRESSED` (9), `IS_CONTROL_JUST_PRESSED` (8), `CLEAR_BIT` (7), `IS_USING_KEYBOARD_AND_MOUSE` (7), `IS_DISABLED_CONTROL_PRESSED` (6), `GET_NETWORK_TIME` (6), `GET_DISABLED_CONTROL_NORMAL` (6), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (5), `IS_STRING_NULL_OR_EMPTY` (5), `SET_VARIABLE_ON_SOUND` (4), `LOG10` (4), `PLAYER_PED_ID` (4), `GET_RANDOM_INT_IN_RANGE` (3), `ABSF` (3), `SET_CONTROL_SHAKE` (3), `NETWORK_IS_PARTICIPANT_ACTIVE` (3), `STOP_AUDIO_SCENE` (3), `START_AUDIO_SCENE` (3), `SQRT` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x39 · `193.75f` x14 · `551.25f` x6 · `533.25f` x6 · `938.625f` x4 · `152.5f` x3 · `788.125f` x3 · `486.375f` x2 · `634.5f` x2 · `540.375f` x2 · `462.875f` x1 · `675.75f` x1 · `469.75f` x1 · `846.625f` x1 · `1062.375f` x1 · `854.125f` x1 · `1057.75f` x1 · `1231.87f` x1 · `1446.875f` x1 · `1238.625f` x1 · `655.25f` x1 · `868.5f` x1 · `663.625f` x1 · `863.625f` x1

## Other strings

Literals whose consuming native was not classified:

`DLC_H3_ArcMac_BR2_Player_Sounds`, `DLC_H3_ArcMac_BR2_Player_Speech_Sounds`, `NUMERICAL_DOLLAR`, `DLC_H3_ArcMac_BR2_Animal_Sounds`, `DLC_H3_ArcMac_BR2_Hostage_Sounds`, `DLC_H3_ArcMac_BR2_Frontend_Sounds`, `DLC_H3_ArcMac_BR2_Bullet_Sounds`, `SCORE_TEXT_WIN_GRAPHIC_RED`, `SCORE_TEXT_WIN_GRAPHIC_BLUE`, `canyon4`, `DLC_H3_ArcMac_BR2_Enemy_Sounds`, `DLC_H3_ArcMac_BR2_Pickup_Sounds`, `SCORE_TEXT_DOLLAR_Y`, `damage1`, `mountain-small1`, `rocks`, `DEG_GAME_QUIT`, `GRAVEYARD_COFFIN_01`, `LEVEL_01_DESERT_CLOUDS_TILE`, `mountains`, `mountain-small2`, `LEVEL_03_FOREST_ROCKS`, `WOODENSTRUCTURE`, `LEVEL_04_GOLDMINE_ROCK`, `damage2`, `_COMPLETED`, `Death`, `DLC_H3_ArcMac_BR2_Explosion_Sounds`, `fence-small`, `canyon1`

---

Source: `decompiled_scripts/gunslinger_arcade.c`
