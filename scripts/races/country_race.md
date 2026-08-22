# country_race.c

Races script. 7 models; 5 scaleforms.

| | |
|---|---|
| Category | Races |
| Total lines | 20,010 |
| Functions | 382 (86 unique, 296 shared) |
| Unique lines | 5,029 (25.1% of file) |

## Assets

**Models and props** (7) - `gauntlet`, `a_m_y_motox_02`, `a_f_y_tourist_01`, `a_f_y_tourist_02`, `a_m_m_tourist_01`, `a_m_m_hillbilly_02`, `a_m_y_motox_01`

**Audio banks** (2) - `TIME_LAPSE`, `HUD_321_GO`

**Sounds** (20) - `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `TOD_SHIFT_SCENE`, `STREET_RACE_OUTRO`, `1st_Person_Transition`, `HUD_MINI_GAME_SOUNDSET`, `RACE_INTRO_GENERIC`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `Short_Transition_Out`, `STREET_RACE_DURING_RACE`, `CHECKPOINT_NORMAL`, `YES`, `NO`, `Hit_In`, `Short_Transition_In`, `MEDAL_UP`, `RACE_PLACED`, `HUD_AWARDS`, `DISTANT_RACERS`, `ROAD_RACE_SOUNDSET`, `TIME_LAPSE_MASTER`

**Scaleform movies** (5) - `SET_MESSAGE`, `MIDSIZED_MESSAGE`, `SHOW_SHARD_MIDSIZED_MESSAGE`, `BM_LAP_STR`, `SHARD_ANIM_OUT`

**Text labels** (14) - `CRACESTUCK`, `CRACEFAIL1`, `CRACEBTIME`, `CRACERES`, `NULL`, `CRACEFAIL`, `CRACEP`, `CRACETRACK`, `CRACETIME`, `CRACECONT`, `CRACERET`, `CRACEQUIT`, `CRACEBLIP`, `BM_LAP`

**Scenarios** (4) - `WORLD_VEHICLE_BIKER`, `DRIVE`, `WORLD_VEHICLE_DRIVE_SOLO`, `WORLD_VEHICLE_DRIVE_PASSENGERS`

**Relationship groups** (3) - `ENEMIES`, `BUDDIES`, `RACERS`

**Hashed names** (4) - `MONSTER`, `MARSHALL`, `huntley`, `DUBSTA3`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (73), `GET_GAME_TIMER` (45), `GET_ENTITY_COORDS` (25), `SET_PED_COMPONENT_VARIATION` (25), `GET_PLAYERS_LAST_VEHICLE` (21), `GET_VEHICLE_PED_IS_IN` (21), `PLAY_SOUND_FRONTEND` (19), `DOES_ENTITY_EXIST` (16), `WAIT` (14), `ANIMPOSTFX_PLAY` (13), `CREATE_CAMERA_WITH_PARAMS` (12), `IS_VEHICLE_STUCK_TIMER_UP` (12), `SET_RELATIONSHIP_BETWEEN_GROUPS` (12), `SETTIMERA` (11), `TIMERA` (11), `PLAYER_ID` (11), `HAS_MODEL_LOADED` (10), `SHAKE_CAM` (10), `GET_RANDOM_INT_IN_RANGE` (10), `GET_ENTITY_MODEL` (9), `WAYPOINT_RECORDING_GET_COORD` (9), `DISABLE_CONTROL_ACTION` (8), `REQUEST_MODEL` (8), `SET_PED_INTO_VEHICLE` (8), `SET_CAM_ACTIVE_WITH_INTERP` (8), `VDIST2` (8), `SET_SCENARIO_TYPE_ENABLED` (8), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (7), `SET_GAMEPLAY_CAM_RELATIVE_PITCH` (7), `IS_SPHERE_VISIBLE` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.3f` x6 · `0.5f` x6 · `9.5f` x4 · `1954.776f` x3 · `47.0701f` x3 · `-0.0416f` x3 · `-158.4057f` x3 · `0.0478f` x3 · `1.2f` x3 · `3149.146f` x2 · `4.9054f` x2 · `52.4461f` x2 · `1971.382f` x2 · `3108.135f` x2 · `47.2013f` x2 · `53.1639f` x2 · `53.3742f` x2 · `1953.31f` x2 · `3139.005f` x2 · `48.1762f` x2 · `0.0276f` x2 · `0.0002f` x2 · `0.1f` x2 · `2565.207f` x2

## Other strings

Literals whose consuming native was not classified:

`HAND_SHAKE`, `gauntlet`, `dominator2`, `player`, `gauntlet2`, `buffalo3`, `stalion2`, `RADIO_01_CLASS_ROCK`, `MinigameEndMichael`, `MinigameEndFranklin`, `MinigameEndTrevor`, `MinigameTransitionIn`, `CamPushInNeutral`, `MinigameTransitionOut`, `STREET_RACE_NPC_GENERAL`, `3_2_1`, `CNTDWN_GO`, `STOCK_RACE_INTRO`, `ROAD_RACE_SOUNDSET`, `DEFAULT_SCRIPTED_CAMERA`, `ROAD_VIBRATION_SHAKE`, `BLIP_CPOINT`, `TIMER_CHALLTIME`, `vigero`, `sabregt`, `phoenix`, `Stage Setup`, `Race`, `Complete`

---

Source: `decompiled_scripts/country_race.c`
