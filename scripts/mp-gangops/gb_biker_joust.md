# gb_biker_joust.c

MP gang ops script. 1 models; 2 scaleforms.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 89,453 |
| Functions | 1,233 (78 unique, 1,155 shared) |
| Unique lines | 3,301 (3.7% of file) |

## Assets

**Models and props** (1) - `prop_gun_case_01`

**Audio banks** (1) - `HUD_MINI_GAME_SOUNDSET`

**Sounds** (8) - `HUD_MINI_GAME_SOUNDSET`, `3_2_1`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `RACES_RADIO_MUTE_scene`, `Out_of_Bounds_Explode`, `Out_of_Bounds`, `GO`, `MP_RACE_GENERAL_SCENE`

**Scaleform movies** (2) - `SET_MESSAGE`, `NUMBER`

**Text labels** (2) - `COP`, `NULL`

**Relationship groups** (2) - `relJoust0`, `relJoust1`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DISABLE_CONTROL_ACTION` (47), `PLAYER_PED_ID` (41), `PLAYER_ID` (39), `PARTICIPANT_ID` (34), `SET_RELATIONSHIP_BETWEEN_GROUPS` (29), `PARTICIPANT_ID_TO_INT` (20), `GET_PLAYER_PED` (16), `SET_BIT` (15), `CLEAR_BIT` (14), `IS_PED_INJURED` (12), `SET_REMOTE_PLAYER_AS_GHOST` (11), `DOES_BLIP_EXIST` (10), `INT_TO_PARTICIPANTINDEX` (9), `GET_ENTITY_MODEL` (9), `IS_PED_IN_ANY_VEHICLE` (7), `REMOVE_BLIP` (6), `GET_VEHICLE_PED_IS_IN` (6), `PLAY_SOUND_FRONTEND` (6), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (6), `NETWORK_GET_PARTICIPANT_INDEX` (6), `NETWORK_IS_PLAYER_ACTIVE` (5), `CLEAR_HELP` (5), `NETWORK_IS_PLAYER_A_PARTICIPANT` (5), `NETWORK_IS_GAME_IN_PROGRESS` (4), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (4), `INT_TO_PLAYERINDEX` (4), `GET_PED_RELATIONSHIP_GROUP_HASH` (4), `IS_PED_SITTING_IN_ANY_VEHICLE` (4), `GET_PLAYER_NAME` (4), `NETWORK_GET_PLAYER_INDEX_FROM_PED` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.4f` x1

## Other strings

Literals whose consuming native was not classified:

`BK_RUN_OVER`, `JST_BLIP`, `JST_OBJ_KILL`, `JST_FBIKE`, `BIGM_JOUSTLD`, `GB_WINNER`, `BIGM_JOUSTWD`, `JST_TEAML`, `JST_HGNLNCH`, `CLUB_WORK_END`, `JST_OBKAREA`, `JST_OBJ_CHARGE`, `JST_OGOAREA`, `JST_OBIKE`, `BIGM_JOUSTDR`, `BIGM_JOUSTLT`, `BIGM_JOUSTNB`, `hydra`, `savage`, `buzzard`, `insurgent`, `valkyrie`, `GB_AMMOPICKBLIP`, `chimera`, `blazer`, `blazer2`, `blazer3`, `blazer4`, `hexer`, `BIKER_JOUST_FIGHT`

---

Source: `decompiled_scripts/gb_biker_joust.c`
