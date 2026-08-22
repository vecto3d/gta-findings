# am_mp_arcade_fortune_teller.c

Minigames script. 2 anim dicts; 2 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 3,811 |
| Functions | 127 (49 unique, 78 shared) |
| Unique lines | 1,398 (36.7% of file) |

## Assets

**Animation dictionaries** (2) - `ANIM_HEIST@ARCADE@FORTUNE@MALE@`, `ANIM_HEIST@ARCADE@FORTUNE@FEMALE@`

**Animations** (2) - `prop_body_loop_intro`, `prop_body_loop_outro`

**Models and props** (2) - `prop_body_loop`, `prop_mouth_loop`

**Sounds** (3) - `dlc_ch_nazar_speaks_sounds`, `fortune_bell`, `fortune_mech_loop`

**Text labels** (3) - `NULL`, `OVERCAST`, `THUNDER`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (15), `SET_BIT` (9), `GET_RANDOM_INT_IN_RANGE` (7), `DOES_ENTITY_EXIST` (4), `STOP_SOUND` (4), `RELEASE_SOUND_ID` (4), `GET_ENTITY_COORDS` (4), `IS_ENTITY_PLAYING_ANIM` (3), `GET_PLAYER_PED` (3), `NETWORK_IS_GAME_IN_PROGRESS` (2), `REMOVE_ANIM_DICT` (2), `STOP_ANIM_PLAYBACK` (2), `PLAY_ENTITY_ANIM` (2), `GET_SOUND_ID` (2), `PLAY_SOUND_FROM_COORD` (2), `GET_EVENT_DATA` (2), `PLAYER_PED_ID` (2), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (1), `CLEAR_BIT` (1), `IS_ENTITY_DEAD` (1), `GET_DISTANCE_BETWEEN_COORDS` (1), `REQUEST_ANIM_DICT` (1), `HAS_ANIM_DICT_LOADED` (1), `GET_ENTITY_ANIM_CURRENT_TIME` (1), `PLAY_ENTITY_SCRIPTED_ANIM` (1), `GET_NUMBER_OF_EVENTS` (1), `GET_EVENT_AT_INDEX` (1), `NETWORK_IS_PLAYER_A_PARTICIPANT` (1), `CLEAR_HELP` (1), `ABSI` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.125f` x4

## Other strings

Literals whose consuming native was not classified:

`HS3MN_EXIT`, `ARC_CAB_FRT_TLL_H`, `rain`, `Neutral`, `clear`, `clouds`, `snow`, `HS3MN_ATTRCT`

---

Source: `decompiled_scripts/am_mp_arcade_fortune_teller.c`
