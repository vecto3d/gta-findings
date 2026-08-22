# act_cinema.c

Properties and venues script. 1 models.

| | |
|---|---|
| Category | Properties and venues |
| Total lines | 131,423 |
| Functions | 1,413 (51 unique, 1,362 shared) |
| Unique lines | 2,545 (1.9% of file) |

## Assets

**Models and props** (1) - `v_ilev_cin_screen`

**Sounds** (4) - `LEAVE_CINEMA`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `SELECT`, `BACK`

**Text labels** (17) - `NULL`, `NOCIN`, `TIMCINMULTI`, `TIMCIN`, `CASHCIN1`, `CASHCIN2`, `CASHCIN3`, `CASHCIN`, `ACTCIN`, `SHOP_JUGG_NONE`, `THEMOVIETH`, `ACTCIN1`, `ACTCIN1F`, `ACTCIN2`, `ACTCIN2F`, `ACTCIN3`, `ACTCIN3F`

**Scenarios** (3) - `Cinema_Textile`, `Cinema_Morningwood`, `Cinema_Downtown`

**Scripts launched** (1) - `act_cinema`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (57), `PLAYER_PED_ID` (47), `NETWORK_IS_GAME_IN_PROGRESS` (21), `CLEAR_BIT` (18), `SET_BIT` (16), `IS_PED_INJURED` (15), `PARTICIPANT_ID_TO_INT` (12), `CLEAR_HELP` (10), `DO_SCREEN_FADE_IN` (10), `SET_ENTITY_COORDS` (8), `FREEZE_ENTITY_POSITION` (8), `SET_ENTITY_HEADING` (8), `SET_TV_CHANNEL` (7), `SET_PLAYER_CONTROL` (6), `SHOW_HUD_COMPONENT_THIS_FRAME` (6), `INT_TO_PARTICIPANTINDEX` (6), `DOES_SCENARIO_GROUP_EXIST` (6), `IS_SCENARIO_GROUP_ENABLED` (6), `SET_SCENARIO_GROUP_ENABLED` (6), `DOES_ENTITY_EXIST` (5), `NETWORK_GET_PLAYER_INDEX` (5), `IS_ENTITY_IN_ANGLED_AREA` (5), `IS_AUDIO_SCENE_ACTIVE` (4), `SET_CURRENT_PED_WEAPON` (4), `DISABLE_PED_PAIN_AUDIO` (4), `DISABLE_CONTROL_ACTION` (4), `DO_SCREEN_FADE_OUT` (4), `IS_SCREEN_FADED_OUT` (4), `SET_STORE_ENABLED` (4), `IS_CONTROL_JUST_PRESSED` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x6 · `1.25f` x2 · `394.368f` x1 · `-711.8287f` x1 · `28.2877f` x1 · `283.7833f` x1 · `200.428f` x1 · `103.3739f` x1 · `-1422.673f` x1 · `-214.3225f` x1 · `45.9932f` x1 · `-0.0375f` x1 · `0.7375f` x1 · `0.19f` x1 · `393.7827f` x1 · `-707.9201f` x1 · `27.78378f` x1 · `393.7906f` x1 · `-715.7693f` x1 · `31.28595f` x1 · `2.25f` x1 · `284.2725f` x1 · `199.158f` x1 · `103.2739f` x1

## Other strings

Literals whose consuming native was not classified:

`cinscreen`, `MP_CIN_WANT`, `END_OF_MOVIE_MARKER`, `DEFAULT_SCRIPTED_CAMERA`, `PL_CINEMA_CARTOON`, `PL_CINEMA_MULTIPLAYER`, `PL_CINEMA_MULTIPLAYER_NO_MELTDOWN`, `CINEMA_DOWNTOWN`, `CINEMA_VINEWOOD`, `CINEMA_MORNINGWOOD`, `service_spend_cinema`, `MP_CIN_KICK`, `MP_CIN_TICKIN`, `MP_CIN_TICKOUT`, `TXM_EXIT`, `INPUTGROUP_LOOK`, `HUD_INPUT91`, `HAND_SHAKE`, `PL_CINEMA_ARTHOUSE`, `PL_CINEMA_ACTION`, `CASHCIN2_JPN`

---

Source: `decompiled_scripts/act_cinema.c`
