# grid_arcade_cabinet.c

Minigames script.

| | |
|---|---|
| Category | Minigames |
| Total lines | 12,521 |
| Functions | 392 (226 unique, 166 shared) |
| Unique lines | 8,558 (68.3% of file) |

## Assets

**Audio banks** (1) - `DLC_VINEWOOD/DLC_VW_AM_TW`

**Sounds** (7) - `dlc_vw_am_tw_in_gameplay_scene`, `dlc_vw_am_tw_vehicle_drivethrough_scene`, `dlc_vw_am_tw_in_menus_scene`, `Screen_Position`, `dlc_vw_am_tw_global_sounds`, `dlc_vw_am_tw_frontend_sounds`, `Frontend_Player_No_Territory_Loop`

**Texture dicts** (7) - `MPArcadeCabinetGrid`, `MPArcadeCabinetGridTiles`, `MPArcadeCabinetGridPlayerBlue`, `MPArcadeCabinetGridPlayerGreen`, `MPArcadeCabinetGridPlayerPurple`, `MPArcadeCabinetGridPlayerYellow`, `MPArcadeCabinetGridHUD`

**Text labels** (10) - `STRING`, `SCGW_PTS`, `SCGW_LBD_T`, `SCGW_R`, `SCGW`, `NULL`, `SCGW_SCORE`, `BIRDS`, `AIRPLANE`, `HELICOPTER`

## Native vocabulary

Most-called natives inside the code unique to this script:

`GET_NETWORK_TIME` (110), `SET_BIT` (48), `TO_FLOAT` (34), `SET_TEXT_COLOUR` (34), `SET_TEXT_SCALE` (28), `SET_TEXT_FONT` (28), `BEGIN_TEXT_COMMAND_DISPLAY_TEXT` (28), `END_TEXT_COMMAND_DISPLAY_TEXT` (28), `INT_TO_PARTICIPANTINDEX` (26), `NETWORK_IS_PARTICIPANT_ACTIVE` (24), `GET_RANDOM_INT_IN_RANGE` (24), `CLEAR_BIT` (21), `PLAYER_ID` (20), `SET_TEXT_CENTRE` (18), `IS_AUDIO_SCENE_ACTIVE` (16), `ROUND` (16), `ABSF` (15), `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME` (14), `STOP_AUDIO_SCENE` (11), `RELEASE_SOUND_ID` (11), `IS_USING_KEYBOARD_AND_MOUSE` (11), `IS_DISABLED_CONTROL_PRESSED` (11), `SET_TEXT_RIGHT_JUSTIFY` (10), `SET_TEXT_WRAP` (10), `STOP_SOUND` (9), `ABSI` (9), `PLAY_SOUND_FRONTEND` (9), `SET_CONTROL_SHAKE` (9), `GET_GAME_TIMER` (8), `SIN` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x46 · `0.95f` x16 · `0.001041667f` x12 · `0.003703704f` x12 · `0.185185f` x12 · `0.1481481f` x11 · `0.104167f` x11 · `0.069444f` x8 · `0.059259f` x8 · `-0.005f` x8 · `0.875f` x6 · `0.127083f` x6 · `0.00625f` x6 · `0.3125f` x6 · `0.65f` x6 · `0.02962963f` x5 · `1.1f` x4 · `0.75f` x4 · `0.025f` x4 · `0.00462963f` x4 · `0.04166683f` x4 · `0.05208333f` x4 · `0.2666667f` x4 · `0.02083333f` x4

## Other strings

Literals whose consuming native was not classified:

`MPArcadeCabinetGridHUD`, `MPArcadeCabinetGrid`, `MPArcadeCabinetGridTiles`, `UNLOCK_NAME_SHIRT3`, `FeedhitTshirt04`, `MPTshirtAwards3`, `player_trail`, `top_down_tile_1`, `Frontend_3_2_1`, `vehicle_alert`, `Ambience`, `MPArcadeCabinetGridPlayer`, `Frontend_Change_Screen`, `Frontend_Change_Letter`, `INVALID GANG`, `Win`, `Lose_Game`, `_PC`, `hud_health`, `text_gang_`, `Frontend_GO`, `text_fight`, `damage_v`, `damage_h`, `Death_Dead`, `Death_Resurrect`, `Death_Bleeps`

---

Source: `decompiled_scripts/grid_arcade_cabinet.c`
