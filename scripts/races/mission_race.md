# mission_race.c

Races script. 1 anim dicts; 9 models; 4 scaleforms.

| | |
|---|---|
| Category | Races |
| Total lines | 33,040 |
| Functions | 614 (121 unique, 493 shared) |
| Unique lines | 8,265 (25.0% of file) |

## Assets

**Animation dictionaries** (1) - `random@street_race`

**Animations** (4) - `_grid_girl_end`, `grid_girl_race_start`, `grid_girl_a`, `grid_girl_b`

**Models and props** (9) - `a_m_y_jetski_01`, `a_f_y_genhot_01`, `a_m_m_socenlat_01`, `a_m_y_hipster_02`, `a_m_y_eastsa_01`, `a_m_y_motox_02`, `a_m_y_motox_01`, `prop_dumpster_02a`, `baller`

**Audio banks** (1) - `HUD_321_GO`

**Sounds** (22) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `SEA_RACE_DURING_RACE`, `STREET_RACE_DURING_RACE`, `RACE_INTRO_GENERIC`, `LEADER_BOARD`, `ROAD_RACE_SOUNDSET`, `Short_Transition_Out`, `HUD_MINI_GAME_SOUNDSET`, `YES`, `NO`, `KISS`, `MEDAL_UP`, `RACE_PLACED`, `HUD_AWARDS`, `Hit_In`, `Short_Transition_In`, `SEA_RACES_OUTRO`, `STREET_RACE_OUTRO`, `DISTANT_RACERS`, `CHECKPOINT_NORMAL`, `UNDER_WATER_COME_UP`

**Scaleform movies** (4) - `MIDSIZED_MESSAGE`, `SHOW_SHARD_MIDSIZED_MESSAGE`, `BM_LAP_STR`, `SHARD_ANIM_OUT`

**Texture dicts** (3) - `MPHUD`, `SPROffroad`, `SHARED`

**Text labels** (16) - `STR1AUD`, `NULL`, `SLOSSANTOS`, `CITYCIRCUIT`, `AIRPORTR`, `FREEWAY`, `VERSPUCCI`, `NORTHCOAST`, `SOUTHCOAST`, `CANYON`, `LOSSANTOS`, `BM_LAP`, `HAO1`, `GIRL1`, `GIRL2`, `FRANKLIN`

**Scenarios** (2) - `DRIVE`, `WORLD_HUMAN_SMOKING`

**Vehicle mods** (15) - `airbus`, `benson`, `biff`, `coach`, `firetruk`, `flatbed`, `mule`, `mule2`, `packer`, `pounder`, `rubble`, `tiptruck`, `tiptruck2`, `tourbus`, `trash`

**Hashed names** (4) - `MONSTER`, `DUBSTA3`, `MARSHALL`, `huntley`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (104), `GET_GAME_TIMER` (73), `GET_ENTITY_COORDS` (31), `DOES_ENTITY_EXIST` (28), `PLAYER_ID` (26), `DOES_CAM_EXIST` (26), `SET_BIT` (26), `LEADERBOARDS2_READ_GET_ROW_DATA_INT` (25), `CREATE_CAMERA_WITH_PARAMS` (22), `WAIT` (19), `DESTROY_CAM` (18), `SET_VEHICLE_MODEL_IS_SUPPRESSED` (17), `GET_HASH_KEY` (16), `IS_VEHICLE_STUCK_TIMER_UP` (16), `IS_PLAYER_PLAYING` (15), `GET_ENTITY_MODEL` (15), `SHAKE_CAM` (15), `SET_ENTITY_COORDS` (14), `IS_PLAYER_ONLINE` (14), `PLAY_SOUND_FRONTEND` (13), `OPEN_SEQUENCE_TASK` (13), `CLOSE_SEQUENCE_TASK` (13), `TASK_PERFORM_SEQUENCE` (13), `GET_NUM_VEHICLE_MODS` (13), `IS_CAM_INTERPOLATING` (13), `SET_CAM_ACTIVE_WITH_INTERP` (13), `LEADERBOARDS2_READ_GET_ROW_DATA_INFO` (13), `LEADERBOARDS2_READ_GET_ROW_DATA_FLOAT` (13), `GET_DISTANCE_BETWEEN_COORDS` (13), `CLEAR_SEQUENCE_TASK` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x12 · `0.3f` x8 · `0.1f` x5 · `1.2f` x4 · `9.5f` x4 · `25.3742f` x3 · `2.3f` x2 · `0.25f` x2 · `1.5f` x1 · `0.8f` x1 · `380.1007f` x1 · `-3498.078f` x1 · `-29.3627f` x1 · `0.165f` x1 · `-1051.519f` x1 · `-1147.217f` x1 · `1.0868f` x1 · `303.3337f` x1 · `0.4f` x1 · `8.5f` x1 · `1.333f` x1 · `-1080.728f` x1 · `454.4489f` x1 · `76.54124f` x1

## Other strings

Literals whose consuming native was not classified:

`HAND_SHAKE`, `StreetRace`, `SeaRace`, `bati`, `RADIO_16_SILVERLAKE`, `OffroadRace`, `RACES_RHELP`, `TIMER_CHALLTIME`, `DEFAULT_SCRIPTED_CAMERA`, `sentinel`, `seashark`, `baller`, `FRANKLIN_NORMAL`, `banshee`, `ruffian`, `prairie`, `airtug`, `MinigameTransitionIn`, `HUD_INPUT43`, `SCLB_PROFILE`, `GameType`, `Location`, `Type`, `MGCR_1`, `MGCR_2`, `MGCR_4`, `MGCR_5`, `MGCR_6`, `MGSR_1`

---

Source: `decompiled_scripts/mission_race.c`
