# ob_jukebox.c

Object brains script. 1 anim dicts; 3 models.

| | |
|---|---|
| Category | Object brains |
| Total lines | 10,693 |
| Functions | 261 (65 unique, 196 shared) |
| Unique lines | 2,107 (19.7% of file) |

## Assets

**Animation dictionaries** (1) - `anim@amb@clubhouse@jukebox@`

**Animations** (4) - `EXIT`, `INSERT_COINS`, `IDLE`, `SELECT_TRACK`

**Models and props** (3) - `bkr_prop_clubhouse_jukebox_01a`, `ch_prop_arcade_jukebox_01a`, `xm3_prop_xm3_jukebox_01a`

**Sounds** (7) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `dlc_ch_arcade_music_volume`, `ArcadeRadioVolumeDucking`, `NAV_UP_DOWN`, `ERROR`, `SELECT`, `BACK`

**Text labels** (4) - `IDLE`, `ENTER`, `NULL`, `EXIT`

**Hashed names** (1) - `ob_jukebox`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (49), `CLEAR_BIT` (41), `PLAYER_PED_ID` (33), `SET_BIT` (19), `ENABLE_CONTROL_ACTION` (11), `SET_STATIC_EMITTER_ENABLED` (9), `SET_EMITTER_RADIO_STATION` (9), `IS_CONTROL_PRESSED` (8), `GET_CLOUD_TIME_AS_INT` (7), `IS_ENTITY_PLAYING_ANIM` (7), `DISABLE_CONTROL_ACTION` (6), `IS_ENTITY_DEAD` (6), `PLAY_SOUND_FRONTEND` (5), `GET_HASH_KEY` (4), `GET_ENTITY_HEADING` (4), `NETWORK_IS_GAME_IN_PROGRESS` (4), `REQUEST_ANIM_DICT` (3), `GET_CLOSEST_OBJECT_OF_TYPE` (3), `GET_ENTITY_COORDS` (3), `GET_ENTITY_ROTATION` (3), `NETWORK_CAN_SPEND_MONEY` (3), `GET_SYNCHRONIZED_SCENE_PHASE` (3), `IS_USING_CURSOR` (3), `SET_AUDIO_SCENE_VARIABLE` (2), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (2), `HAS_ANIM_DICT_LOADED` (2), `DOES_ENTITY_EXIST` (2), `IS_STRING_NULL_OR_EMPTY` (2), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (2), `GET_ROOM_KEY_FROM_ENTITY` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.6f` x3 · `1.5f` x3 · `0.96f` x2 · `-0.12f` x1 · `-0.0315f` x1 · `0.25f` x1 · `0.05f` x1 · `0.125f` x1 · `0.1f` x1 · `0.82f` x1 · `0.55f` x1 · `0.8f` x1 · `-1.5f` x1

## Other strings

Literals whose consuming native was not classified:

`HIDDEN_RADIO_BIKER_CLASSIC_ROCK`, `JBOX_NO_MONEY`, `JBOX_CANC_PUR`, `ITEM_SELECT`, `ITEM_BACK`, `HIDDEN_RADIO_BIKER_MODERN_ROCK`, `HIDDEN_RADIO_BIKER_HIP_HOP`, `HIDDEN_RADIO_BIKER_PUNK`, `HIDDEN_RADIO_37_MOTOMAMI`, `HIDDEN_RADIO_34_DLC_HEI4_KULT`, `HIDDEN_RADIO_THE_LAB`, `HIDDEN_RADIO_FLYLO`, `HIDDEN_RADIO_IFRUIT`, `HIDDEN_RADIO_MLR`, `HIDDEN_RADIO_12_REGGAE`, `HIDDEN_RADIO_17_FUNK`, `HIDDEN_RADIO_06_COUNTRY`, `HIDDEN_RADIO_15_MOTOWN`, `RADIO_36_AUDIOPLAYER`, `SE_xm3_dlc_int_03_xm3_radioemitter_office`, `SE_xm3_dlc_int_03_xm3_radioemitter_main_area`, `DLC_H3_Arcade_Main_Area_Music_Emitter`, `DLC_H3_Arcade_Planning_Room_Radio_Emitter`, `SE_bkr_biker_dlc_int_02_REC`, `SE_bkr_biker_dlc_int_02_GRG`, `SE_bkr_biker_dlc_int_01_BAR`, `SE_bkr_biker_dlc_int_01_GRG`, `SE_bkr_biker_dlc_int_01_REC`, `JBOX_MENU_T`, `JBOX_M_OFF`

---

Source: `decompiled_scripts/ob_jukebox.c`
