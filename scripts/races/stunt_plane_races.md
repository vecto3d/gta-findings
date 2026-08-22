# stunt_plane_races.c

Races script. 10 models; 3 scaleforms.

| | |
|---|---|
| Category | Races |
| Total lines | 26,798 |
| Functions | 614 (184 unique, 430 shared) |
| Unique lines | 9,065 (33.8% of file) |

## Assets

**Models and props** (10) - `s_m_m_dockwork_01`, `a_m_y_motox_01`, `sanchez`, `s_m_m_highsec_01`, `stunt`, `hauler`, `tanker`, `jetmax`, `jet`, `a_m_y_genstreet_01`

**Audio banks** (2) - `OFFMISSION_WASTED`, `HUD_AWARDS`

**Sounds** (21) - `HUD_MINI_GAME_SOUNDSET`, `HUD_MINIGAME_SOUNDSET`, `Phone_Generic_Key_02`, `WastedSounds`, `HUD_AWARDS`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `NAV_UP_DOWN`, `QUIT_WHOOSH`, `CANCEL`, `SELECT`, `Phone_Generic_Key_03`, `DEATH_SCENE`, `ScreenFlash`, `Bed`, `TextHit`, `MEDAL_GOLD`, `MEDAL_SILVER`, `MEDAL_BRONZE`, `YES`, `NO`, `QUIT`

**Scaleform movies** (3) - `TRANSITION_OUT`, `RESET_MOVIE`, `STRING`

**Texture dicts** (7) - `MPHUD`, `SPRRaces`, `MPMedals_FEED`, `SPROffroad`, `Triathlon`, `Shared`, `PilotSchool`

**Text labels** (24) - `MPMedals_FEED`, `Feed_Medal_FlightSchool`, `HUD_MED_UNLKED`, `SPR_RETR_DES`, `NULL`, `SPRBEST`, `NUMBER`, `SPR_HELP_WARN`, `GATEMISS`, `GATEINNER`, `GATEOUTTER`, `STUNTINVERTED`, `SPR_HELP_DAMG`, `SPR_UI_PASS`, `GATEBLIPFIN`, `GATEBLIPINV`, `GATEBLIPKNF`, `GATEBLIPDEF`, `EXTRASUNNY`, `AIRPORT`, `BRIDGEBINGE`, `VINEWOOD`, `BRIDGEWORK`, `ALTITUDE`

**Scenarios** (1) - `AMMUNATION`

**Waypoint recordings** (1) - `SPR_Fluff_01`

**Vehicle recordings** (2) - `SPRStuntAF`, `SPRTaxi`

**Stats** (3) - `sp0_flying_ability`, `sp1_flying_ability`, `sp2_flying_ability`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_ENTITY_DEAD` (68), `PLAYER_PED_ID` (64), `PLAYER_ID` (34), `DOES_ENTITY_EXIST` (30), `LEADERBOARDS2_READ_GET_ROW_DATA_INT` (23), `PLAY_SOUND_FRONTEND` (19), `SET_TEXT_RIGHT_JUSTIFY` (16), `SET_PLAYER_CONTROL` (15), `CLEAR_PRINTS` (15), `GET_ENTITY_COORDS` (13), `GET_SOUND_ID` (13), `LEADERBOARDS2_READ_GET_ROW_DATA_FLOAT` (13), `DISABLE_CONTROL_ACTION` (12), `CEIL` (11), `CLEAR_HELP` (11), `LEADERBOARDS2_READ_GET_ROW_DATA_INFO` (11), `SET_VEHICLE_DOORS_LOCKED` (10), `IS_CONTROL_JUST_RELEASED` (10), `IS_PED_IN_ANY_VEHICLE` (10), `HIDE_HUD_COMPONENT_THIS_FRAME` (10), `FLOOR` (10), `LEADERBOARDS2_READ_GET_ROW_DATA_END` (10), `IS_VEHICLE_DRIVEABLE` (9), `DOES_CAM_EXIST` (9), `ANIMPOSTFX_PLAY` (9), `DOES_BLIP_EXIST` (9), `ABSF` (9), `REQUEST_STREAMED_TEXTURE_DICT` (9), `HAS_STREAMED_TEXTURE_DICT_LOADED` (9), `IS_PED_IN_VEHICLE` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x6 · `1.5f` x3 · `-943.8105f` x3 · `-3173.692f` x3 · `12.9445f` x3 · `0.3f` x3 · `34.9705f` x2 · `0.342f` x2 · `-449.6041f` x2 · `-2271.693f` x2 · `6.6086f` x2 · `267.5199f` x2 · `-2530.873f` x2 · `608.701f` x2 · `238.9111f` x2 · `-2527.712f` x2 · `609.6833f` x2 · `239.2568f` x2 · `-1552.281f` x2 · `2641.609f` x2 · `-0.8283f` x2 · `1734.802f` x1 · `3224.105f` x1 · `41.3709f` x1

## Other strings

Literals whose consuming native was not classified:

`stunt`, `Shared`, `SPRRaces`, `Con_PK`, `Con_Kni`, `Con_Miss`, `MinigameTransitionIn`, `SPR_RETR_DES`, `SPR_FAIL_GATE`, `Player`, `player_one`, `MinigameTransitionOut`, `SPR_HELP_DAMG`, `HUD_INPUT68`, `MGSP_FAIL`, `Con_PI`, `Con_Perf`, `Con_Inv`, `Con_Hit`, `Gate_Miss`, `SC_LB_EMPTY`, `MedalDot_32`, `FLY_STAT_WARN`, `SP_SPR`, `SPR_RETR_FAIL`, `MGSP_END`, `Offroad_`, `TIMER_BESTIME`, `SPR_MOVE_FAIL`

---

Source: `decompiled_scripts/stunt_plane_races.c`
