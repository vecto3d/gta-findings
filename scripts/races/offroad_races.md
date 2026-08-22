# offroad_races.c

Races script. 2 anim dicts; 7 models; 1 scaleforms.

| | |
|---|---|
| Category | Races |
| Total lines | 119,330 |
| Functions | 967 (204 unique, 763 shared) |
| Unique lines | 11,451 (9.6% of file) |

## Assets

**Animation dictionaries** (2) - `MINI@RACING@QUAD@`, `MINI@RACING@BIKE@`

**Animations** (6) - `MINI@RACING@QUAD@`, `celebrate_c`, `MINI@RACING@BIKE@`, `offroad_outro_mic`, `offroad_outro_fra`, `offroad_outro_trv`

**Models and props** (7) - `a_m_y_genstreet_01`, `a_m_y_motox_01`, `a_m_y_motox_02`, `sanchez`, `mesa`, `prop_fncwood_14c`, `prop_fncwood_14e`

**Audio banks** (1) - `CROWD_CHEER`

**Sounds** (13) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `YES`, `RACE_INTRO_GENERIC`, `HUD_MINI_GAME_SOUNDSET`, `OFFROAD_RACES_OUTRO_SCENE`, `QUIT_WHOOSH`, `OFFROAD_RACES_DURING_RACE`, `NO`, `CROWD_CHEER_MASTER`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `RACE_PLACED`, `HUD_AWARDS`

**Scaleform movies** (1) - `SET_TITLE`

**Texture dicts** (5) - `SPROffroad`, `MPHUD`, `SPRRaces`, `Triathlon`, `Shared`

**Text labels** (22) - `SPR_EXIT_WARN`, `TREVOR`, `MICHAEL`, `FRANKLIN`, `NULL`, `SPR_EXIT_FAIL`, `SPR_HELP_WARN`, `SPR_HELP_DAMG`, `SPR_RETR_DES`, `OFF_OPP`, `GATEBLIP`, `GATEBLIPDEF`, `MALE1`, `MALE2`, `MALE3`, `ORRAUD`, `CANYONCLIFFS`, `RIDGERUN`, `MINEWARD`, `VALLEYTRAIL`, `LAKESIDE`, `ECOFRIENDLY`

**Scenarios** (3) - `QUARRY`, `WORLD_VEHICLE_DRIVE_SOLO`, `WORLD_VEHICLE_BICYCLE_MOUNTAIN`

**Waypoint recordings** (7) - `orr_canyoncliffs_finish`, `orr_ridgerun_finish`, `orr_valleytrail_finish`, `orr_lakesidesplash_finish`, `orr_ecofriendly_finish`, `orr_minewardspiral_finish`, `OR_Post_7`

**Vehicle mods** (2) - `mesa`, `sanchez`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (228), `IS_ENTITY_DEAD` (196), `SET_ENTITY_COORDS` (70), `SET_ENTITY_HEADING` (66), `DOES_CAM_EXIST` (61), `CREATE_CAMERA_WITH_PARAMS` (55), `DOES_ENTITY_EXIST` (47), `PLAYER_ID` (44), `DISABLE_CONTROL_ACTION` (41), `SET_VEHICLE_ON_GROUND_PROPERLY` (37), `IS_PED_IN_ANY_VEHICLE` (34), `GET_ENTITY_MODEL` (33), `DOES_BLIP_EXIST` (28), `GET_NUMBER_OF_VEHICLE_COLOURS` (26), `LEADERBOARDS2_READ_GET_ROW_DATA_INT` (25), `GET_VEHICLE_PED_IS_IN` (25), `SET_PLAYER_CONTROL` (23), `GET_ENTITY_COORDS` (22), `SET_ENTITY_AS_MISSION_ENTITY` (21), `CLEAR_PRINTS` (20), `GET_PLAYERS_LAST_VEHICLE` (20), `IS_PED_IN_VEHICLE` (19), `CLEAR_HELP` (18), `SET_PED_INTO_VEHICLE` (16), `LEADERBOARDS_WRITE_ADD_COLUMN` (16), `SET_BLIP_DISPLAY` (15), `HAS_ENTITY_BEEN_DAMAGED_BY_WEAPON` (14), `REQUEST_WAYPOINT_RECORDING` (14), `GET_VEHICLE_COLOUR_COMBINATION` (14), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (13)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x6 · `40.1711f` x6 · `0.5f` x4 · `2242.488f` x4 · `39.9908f` x4 · `41.6574f` x4 · `44.5242f` x4 · `0.2f` x3 · `0.1f` x3 · `-225.98f` x3 · `4224.74f` x3 · `44.36f` x3 · `80.2f` x3 · `1602.54f` x3 · `3837.21f` x3 · `33.72f` x3 · `308.94f` x3 · `20.89f` x3 · `-0.2f` x2 · `0.95f` x2 · `-1943.822f` x2 · `4462.286f` x2 · `-229.0783f` x2 · `4227.072f` x2

## Other strings

Literals whose consuming native was not classified:

`Racer`, `sanchez`, `SPR_HELP_DIST`, `blazer`, `Offroad_`, `CS2_06_TriAf02`, `RADIO_01_CLASS_ROCK`, `OffroadRace`, `MICHAEL_NORMAL`, `TREVOR_NORMAL`, `FRANKLIN_NORMAL`, `MinigameTransitionIn`, `SPR_EXIT_WARN`, `mesa`, `player_one`, `SPR_CONT2`, `SPR_UI_RETRY`, `MinigameTransitionOut`, `CRASH_GENERIC`, `bjxl`, `StreetRace`, `blazer2`, `HUD_INPUT68`, `SPR_HELP_DAMG`, `SeaRace`, `Player`, `OFF_ROAD_RADIO_ROCK_LIST`, `OR_RACE_01`, `OR_RACE_02`, `OR_RACE_03`

---

Source: `decompiled_scripts/offroad_races.c`
