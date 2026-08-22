# camhedz_arcade.c

Minigames script. 2 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 105,907 |
| Functions | 1,077 (411 unique, 666 shared) |
| Unique lines | 17,235 (16.3% of file) |

## Assets

**Models and props** (2) - `PROP_BARRELS`, `PROP_CACTUS_07`

**Audio banks** (2) - `DLC_TUNER/DLC_Tuner_AM_CH`, `DLC_TUNER/DLC_Tuner_AM_CH_Dir_Vocal`

**Sounds** (5) - `Screen_Position`, `GlitchLevel`, `DLC_Tuner_AM_ch_in_menus_scene`, `DLC_Tuner_AM_ch_in_gameplay_scene`, `DLC_Tuner_AM_ch_powerup_active_scene`

**Text labels** (20) - `LEADERBOARD`, `PLAY`, `STAR`, `START`, `SCORE`, `ACCURACY`, `NULL`, `UNKNOWN`, `DOT`, `CITY`, `SCRAPYARD`, `ASYLUM`, `THEMEPARK`, `REDCIRCLE`, `OUCH1`, `FENCE`, `AMMO4`, `AMMO3`, `AMMO2`, `HEXAGON`

## Native vocabulary

Most-called natives inside the code unique to this script:

`ARE_STRINGS_EQUAL` (65), `GET_GAME_TIMER` (56), `PARTICIPANT_ID_TO_INT` (44), `ROUND` (43), `IS_DISABLED_CONTROL_JUST_PRESSED` (42), `TO_FLOAT` (35), `TIMESTEP` (31), `GET_RANDOM_FLOAT_IN_RANGE` (25), `SET_BIT` (22), `FLOOR` (20), `GET_RANDOM_INT_IN_RANGE` (19), `SET_VARIABLE_ON_SOUND` (17), `ABSF` (15), `PLAYER_ID` (14), `GET_FRAME_TIME` (14), `IS_USING_KEYBOARD_AND_MOUSE` (11), `IS_STRING_NULL_OR_EMPTY` (10), `GET_NETWORK_TIME` (9), `CLEAR_BIT` (9), `GET_DISABLED_CONTROL_NORMAL` (8), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (6), `GET_SOUND_ID` (6), `PLAY_SOUND_FRONTEND` (6), `RELEASE_SOUND_ID` (6), `PLAYER_PED_ID` (6), `IS_DISABLED_CONTROL_PRESSED` (5), `SET_CONTROL_SHAKE` (5), `NETWORK_IS_GAME_IN_PROGRESS` (4), `SQRT` (4), `CEIL` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x11 · `0.25f` x10 · `193.75f` x7 · `927.5f` x6 · `1.5f` x6 · `0.45f` x2 · `0.05f` x2 · `458.25f` x2 · `0.55f` x1 · `0.65f` x1 · `0.35f` x1 · `0.9f` x1 · `0.8f` x1 · `0.7f` x1 · `0.4f` x1 · `0.3f` x1 · `486.375f` x1 · `1247.625f` x1 · `99.9f` x1 · `825.5f` x1 · `890.375f` x1 · `577.125f` x1 · `637.125f` x1 · `0.2f` x1

## Other strings

Literals whose consuming native was not classified:

`DLC_TUNER_AM_CH_Director_VO_Sounds`, `DLC_Tuner_AM_CH_Frontend_Sounds`, `DLC_Tuner_AM_CH_Player_Weapon_Sounds`, `DLC_Tuner_AM_CH_Enemy_Sounds`, `DLC_TUNER_AM_CH_Enemy_Sounds`, `DLC_TUNER_AM_CH_Bearsy_Sounds`, `DLC_Tuner_AM_CH_Player_Speech_Sounds`, `DLC_Tuner_AM_CH_Bullet_Sounds`, `MPCamhedzVHSFont`, `Death`, `DLC_TUNER_AM_CH_Hostage_Sounds`, `FINAL_BOSS_BEARSY_FOREGROUND_ATTACKING_01`, `DLC_Tuner_AM_CH_Player_Sounds`, `Pain`, `LEVEL_02_SCRAPYARD_ROCKS`, `LEVEL_01_CITY_BUILDING_01`, `damage_fx_overlay_001`, `Attack_Success`, `Attack`, `Hurt`, `DLC_Tuner_AM_CH_Pickup_Sounds`, `FONT_`, `DEG_GAME_QUIT`, `_COMPLETED`, `CAMHEDZ_TITLE_SCREEN_CHARACTER`, `MPCamhedzTitles`, `MPCamhedzBearsy_Projectile_Bone`, `LEVEL_0`, `ARCADE_CamH_PLAYER_HIT`, `THROWING_FIREBOTTLE_SMALL`

---

Source: `decompiled_scripts/camhedz_arcade.c`
