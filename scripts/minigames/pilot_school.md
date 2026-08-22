# pilot_school.c

Minigames script. 2 anim dicts; 4 models; 7 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 126,724 |
| Functions | 1,180 (366 unique, 814 shared) |
| Unique lines | 16,671 (13.2% of file) |

## Assets

**Animation dictionaries** (2) - `veh@helicopter@rps@base`, `oddjobs@basejump@`

**Animations** (3) - `oddjobs@basejump@`, `Heli_jump`, `Heli_door_loop`

**Models and props** (4) - `prop_parapack_01`, `phantom`, `trflat`, `s_m_m_pilot_02`

**Audio banks** (3) - `HUD_321_GO`, `OFFMISSION_WASTED`, `SCRIPT\DRUG_TRAFFIC_AIR`

**Sounds** (16) - `HUD_MINI_GAME_SOUNDSET`, `HUD_AWARDS`, `WastedSounds`, `DEATH_SCENE`, `NAV_UP_DOWN`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `MEDAL_GOLD`, `MEDAL_SILVER`, `MEDAL_BRONZE`, `FLIGHT_SCHOOL_LESSON_PASSED`, `ScreenFlash`, `Bed`, `TextHit`, `QUIT_WHOOSH`, `YES`, `NO`

**Scaleform movies** (7) - `TRANSITION_OUT`, `RESET_MOVIE`, `STRING`, `MP_MEDAL_FREEMODE`, `TV_FRAME`, `mission_quit`, `COUNTDOWN`

**Texture dicts** (5) - `pilotSchool`, `PS_Menu`, `MPMedals_FEED`, `Shared`, `FlightSchool_Logo_256`

**Text labels** (13) - `MGPSAUD`, `NUMBER`, `MPMedals_FEED`, `Feed_Medal_FlightSchool`, `HUD_MED_UNLKED`, `PERCENTAGE`, `PSCHOOL`, `PS_BLPMTARG`, `DEAD`, `PSER_SUCCESS`, `NULL`, `EXTRASUNNY`, `PS_sFINISH`

**Scenarios** (1) - `WORLD_VEHICLE_DRIVE_SOLO`

**Waypoint recordings** (1) - `ps_trucktarget_cw`

**Vehicle recordings** (1) - `PilotSchool`

**Timecycle modifiers** (1) - `scanline_cam`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (267), `CLEAR_HELP` (61), `IS_ENTITY_DEAD` (60), `PLAYER_ID` (54), `DISABLE_CONTROL_ACTION` (51), `GET_GAME_TIMER` (50), `IS_PED_INJURED` (44), `DOES_ENTITY_EXIST` (43), `GET_ENTITY_COORDS` (41), `CLEAR_PRINTS` (37), `ABSF` (36), `WAIT` (29), `IS_VEHICLE_DRIVEABLE` (28), `FLOOR` (26), `SET_PLAYER_CONTROL` (25), `ROUND` (24), `GET_RANDOM_INT_IN_RANGE` (23), `RENDER_SCRIPT_CAMS` (22), `DOES_CAM_EXIST` (22), `FREEZE_ENTITY_POSITION` (20), `HAS_VEHICLE_RECORDING_BEEN_LOADED` (20), `GET_DISTANCE_BETWEEN_COORDS` (18), `GET_ENTITY_SPEED` (18), `SET_PED_COMPONENT_VARIATION` (18), `DESTROY_CAM` (17), `SET_MODEL_AS_NO_LONGER_NEEDED` (16), `PLAY_SOUND_FRONTEND` (15), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (15), `SET_ENTITY_COORDS` (14), `SET_MINIMAP_COMPONENT` (14)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x13 · `0.3f` x11 · `1.2f` x7 · `-1637.295f` x6 · `-2732.104f` x6 · `17.4674f` x6 · `0.342f` x5 · `-97.4239f` x4 · `1.1f` x4 · `-1618.14f` x4 · `-2980.828f` x4 · `17.4172f` x4 · `-1506.49f` x4 · `62.0109f` x4 · `0.7071f` x3 · `328.5558f` x3 · `59.7732f` x3 · `-1090.401f` x3 · `-3326.039f` x3 · `1.5f` x3 · `-2177.86f` x3 · `4408.885f` x3 · `59.1266f` x3 · `-1777.395f` x3

## Other strings

Literals whose consuming native was not classified:

`pilotSchool`, `PS_LOOP`, `PS_INVERT`, `stunt`, `PS_LAND`, `PS_KNIFE`, `MGPS_STOP`, `PS_HSR`, `PS_INTER`, `PS_TAXI`, `PS_TAKEOFF`, `PS_TAKEOFF_8`, `MinigameTransitionIn`, `PS_HOC`, `FlightSchool_Bronze_128`, `HUD_INPUT68`, `MGPS_START`, `PS_POC`, `PS_LAND_7`, `PS_POMT`, `PS_LAND_6`, `PS_TAXI_8`, `SC_LB_EMPTY`, `FlightSchool_Gold_128`, `FlightSchool_Silver_128`, `PS_POT`, `PS_LAND_5`, `PS_FLYLOW`, `PSBARREL_E`, `PS_KNIFEOBJ`

---

Source: `decompiled_scripts/pilot_school.c`
