# scroll_arcade_cabinet.c

Minigames script.

| | |
|---|---|
| Category | Minigames |
| Total lines | 12,696 |
| Functions | 384 (229 unique, 155 shared) |
| Unique lines | 8,916 (70.2% of file) |

## Assets

**Audio banks** (1) - `DLC_VINEWOOD/DLC_VW_AM_IP`

**Sounds** (13) - `Screen_Position`, `dlc_vw_am_ip_in_gameplay_scene`, `dlc_vw_am_ip_in_menus_scene`, `dlc_vw_am_ip_tank_sounds`, `dlc_vw_am_ip_frontend_sounds`, `TankSpeed`, `Tank_Engine_Loop`, `IsJumping`, `DamageLevel`, `Tank_Critical_Damage_Loop`, `dlc_vw_am_ip_enemy_sounds`, `Tank_Weapon_Lightning_Gun_Fire_Hit`, `TargetsHit`

**Texture dicts** (4) - `MPInvPersHud`, `MPInvPersMessages`, `MPInvPersMessages2`, `MpInvPersCommon`

**Text labels** (5) - `STRING`, `IAP_SCR`, `IAP`, `NULL`, `IAP_INTRO`

## Native vocabulary

Most-called natives inside the code unique to this script:

`GET_NETWORK_TIME` (67), `SET_BIT` (44), `TO_FLOAT` (26), `ROUND` (24), `ABSF` (20), `STOP_SOUND` (19), `RELEASE_SOUND_ID` (18), `SET_TEXT_COLOUR` (17), `IS_USING_KEYBOARD_AND_MOUSE` (16), `HAS_SOUND_FINISHED` (14), `IS_DISABLED_CONTROL_JUST_PRESSED` (13), `SET_VARIABLE_ON_SOUND` (13), `SIN` (12), `SET_TEXT_SCALE` (11), `SET_TEXT_FONT` (11), `BEGIN_TEXT_COMMAND_DISPLAY_TEXT` (11), `END_TEXT_COMMAND_DISPLAY_TEXT` (11), `PLAYER_ID` (10), `PLAY_SOUND_FRONTEND` (10), `SET_TEXT_RIGHT_JUSTIFY` (10), `SET_TEXT_WRAP` (10), `TIMESTEP` (9), `IS_DISABLED_CONTROL_PRESSED` (9), `GET_SOUND_ID` (8), `SET_STREAMED_TEXTURE_DICT_AS_NO_LONGER_NEEDED` (7), `FLOOR` (7), `STOP_BINK_MOVIE` (6), `RELEASE_BINK_MOVIE` (6), `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME` (6), `GET_RANDOM_FLOAT_IN_RANGE` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x33 · `0.09583333f` x8 · `0.164583f` x6 · `0.001041667f` x5 · `0.003703704f` x5 · `0.4947917f` x4 · `0.02962963f` x4 · `0.325926f` x4 · `0.25f` x3 · `-0.65f` x3 · `0.65f` x3 · `0.37f` x2 · `0.4135417f` x2 · `0.4411458f` x2 · `0.46875f` x2 · `0.695f` x2 · `151.899f` x2 · `0.1f` x2 · `0.045833f` x2 · `0.35f` x2 · `0.0075f` x2 · `-0.055f` x2 · `-0.0005f` x2 · `0.0005f` x2

## Other strings

Literals whose consuming native was not classified:

`dlc_vw_am_ip_enemy_sounds`, `MPInvPersHud`, `MPInvPersCommon`, `MpInvPersHud`, `dlc_vw_am_ip_tank_sounds`, `Enemy_Jet_Bomb_Barrel_Explode`, `Enemy_Blaster_Fire_Hit`, `UNLOCK_NAME_SHIRT3`, `FeedhitTshirt04`, `MPTshirtAwards3`, `background`, `midground_3`, `midground_2`, `midground_1`, `foreground`, `Tank_Collision`, `Tank_Destroyed`, `Frontend_Player_Death`, `pitfall`, `ledge`, `Frontend_Score_Tick_Large`, `Tank_Weapon_Change`, `IAP_PU_WAO`, `Frontend_Retry`, `_PC`, `Frontend_Score_Tick_Total`, `MpInvPersCommon`, `tank_jump`, `dlc_vw_am_ip_powerup_sounds`, `INVALID STAGE`

---

Source: `decompiled_scripts/scroll_arcade_cabinet.c`
