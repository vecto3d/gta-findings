# mg_race_to_point.c

Races script. 2 scaleforms.

| | |
|---|---|
| Category | Races |
| Total lines | 21,274 |
| Functions | 622 (48 unique, 574 shared) |
| Unique lines | 2,357 (11.1% of file) |

## Assets

**Sounds** (8) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `SELECT`, `NAV_UP_DOWN`, `NAV_LEFT_RIGHT`, `CHECKPOINT_NORMAL`, `HUD_MINI_GAME_SOUNDSET`, `CANCEL`, `BACK`

**Scaleform movies** (2) - `MP_MENU_GLARE`, `SET_DATA_SLOT`

**Text labels** (1) - `NULL`

**Scripts launched** (1) - `mg_race_to_point`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (59), `DISABLE_CONTROL_ACTION` (29), `PARTICIPANT_ID_TO_INT` (26), `SET_BIT` (24), `CLEAR_BIT` (16), `PLAYER_PED_ID` (13), `GET_DISTANCE_BETWEEN_COORDS` (12), `PLAY_SOUND_FRONTEND` (12), `ROUND` (12), `IS_USING_KEYBOARD_AND_MOUSE` (10), `GET_PLAYER_TEAM` (9), `INT_TO_PARTICIPANTINDEX` (7), `NETWORK_GET_PLAYER_INDEX` (7), `DOES_BLIP_EXIST` (7), `NETWORK_IS_GAME_IN_PROGRESS` (6), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (6), `GET_PLAYER_PED` (6), `SET_INPUT_EXCLUSIVE` (6), `NETWORK_GET_INSTANCE_ID_OF_THIS_SCRIPT` (5), `GET_ENTITY_COORDS` (5), `IS_WAYPOINT_ACTIVE` (5), `SET_MINIMAP_BLOCK_WAYPOINT` (5), `IS_ENTITY_AT_COORD` (5), `IS_CONTROL_PRESSED` (5), `NETWORK_IS_PARTICIPANT_ACTIVE` (4), `SET_USER_RADIO_CONTROL_ENABLED` (4), `REMOVE_BLIP` (4), `DELETE_CHECKPOINT` (4), `IS_DISABLED_CONTROL_PRESSED` (4), `SPAWNPOINTS_CANCEL_SEARCH` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`7.5f` x5 · `0.05f` x2 · `-1836.619f` x1 · `-1262.522f` x1 · `-42.18043f` x1 · `-1664.868f` x1 · `-1060.219f` x1 · `119.5007f` x1 · `1.2f` x1

## Other strings

Literals whose consuming native was not classified:

`R2P_CTRL_INV`, `R2P_MENU_EXI`, `R2P_MENU_DE0S`, `R2P_MENU_DEST`, `R2P_MENU_DE`, `R2P_MENU_DE0`, `R2P_MENU_LAU`, `R2P_CTRL_SEL`, `R2P_CTRL_NXT`, `R2P_MENU_BAC`, `R2P_MENU`, `mg_race_to_point`, `R2P_WARNH`, `R2P_MENU_DE99F`, `R2P_MENU_SCT`, `R2P_MENU_SC`, `R2P_MENU_STT`, `SPEC_PAUSE`, `service_spend_impromptu_race_fee`, `RaceToPoint`, `R2P_DQBIG`, `R2P_DQSTR`, `service_earn_jobs`, `XPT_MEDIUMT`, `R2P_IWSTR`, `mpply_race_2_point_wins`, `R2P_ILSTR`, `R2P_PWTIC`, `mpply_race_2_point_lost`, `-StraightIntoFreemode`

---

Source: `decompiled_scripts/mg_race_to_point.c`
