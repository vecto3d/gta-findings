# extreme2.c

SP missions script. 3 anim dicts; 5 models; 3 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 114,333 |
| Functions | 892 (82 unique, 810 shared) |
| Unique lines | 3,081 (2.7% of file) |

## Assets

**Animation dictionaries** (3) - `rcmextreme2`, `rcmextreme2atv`, `rcmjosh1@impatient`

**Animations** (13) - `rcmextreme2atv`, `rcmextreme2`, `rcmjosh1@impatient`, `idle_b`, `banter_franklin`, `banter_dom`, `enter`, `exit`, `leadin`, `idle_a`, `idle_d`, `idle_c`, `idle_e`

**Models and props** (5) - `a_c_retriever`, `s_m_m_security_01`, `s_m_m_pilot_01`, `prop_ld_test_01`, `exile1_lightrig`

**Audio banks** (2) - `SCRIPT\CARGO_PLANE_PH`, `SCRIPT\CARGO_PLANE_PH_B`

**Sounds** (5) - `INOUT`, `EXTREME_02_DRIVE_TO_PLANE`, `Scraping_Ramp`, `EXTREME_02_SOUNDSET`, `PLAYER_AT_SPEED_FREEFALL_MASTER`

**Particle effects** (3) - `scr_rcext2_ramp_scrape`, `scr_extrm2_moving_cloud`, `scr_rcext2_cargo_smoke`

**Text labels** (6) - `EXT2AU`, `FRANKLIN`, `DOM`, `NULL`, `CLOUDS`, `EXT2`

**Scenarios** (1) - `LSA_Planes`

**Vehicle recordings** (4) - `Ext2_DomIntoAirport`, `Ext2_CargoTakeOff`, `Ext2_AirportVeh`, `Ext2_CargoFlight`

**Hashed names** (1) - `V_FakeCargoPlaneClimb`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (132), `GET_GAME_TIMER` (23), `GET_ENTITY_COORDS` (22), `REQUEST_MODEL` (16), `HAS_MODEL_LOADED` (16), `DOES_ENTITY_EXIST` (14), `SET_MODEL_AS_NO_LONGER_NEEDED` (14), `TRIGGER_MUSIC_EVENT` (12), `IS_PED_IN_VEHICLE` (11), `DOES_PARTICLE_FX_LOOPED_EXIST` (11), `WAIT` (10), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (9), `TASK_PLAY_ANIM` (9), `CLEAR_HELP` (8), `STOP_PARTICLE_FX_LOOPED` (8), `DOES_BLIP_EXIST` (8), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (8), `GET_OFFSET_FROM_ENTITY_GIVEN_WORLD_COORDS` (8), `IS_PED_IN_ANY_VEHICLE` (8), `SET_VEHICLE_IS_CONSIDERED_BY_PLAYER` (7), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (7), `REMOVE_VEHICLE_RECORDING` (7), `SET_VEHICLE_ENGINE_ON` (7), `SET_VEHICLE_MODEL_IS_SUPPRESSED` (7), `CLEAR_PRINTS` (6), `START_PLAYBACK_RECORDED_VEHICLE` (6), `REPLAY_RECORD_BACK_FOR_TIME` (6), `SET_CAM_PARAMS` (6), `SET_PED_INTO_VEHICLE` (6), `GET_VEHICLE_RECORDING_ID` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`288.2311f` x2 · `-1.5f` x2 · `0.5f` x2 · `0.25f` x2 · `14.2f` x2 · `-1389.5f` x2 · `-2218.5f` x2 · `-6.45f` x2 · `273.2345f` x1 · `0.7f` x1 · `2.3f` x1 · `1.05f` x1 · `0.99f` x1 · `-0.25f` x1 · `171.4f` x1 · `31.5f` x1 · `2368.111f` x1 · `4503.167f` x1 · `29.5964f` x1 · `145.6766f` x1 · `3661.602f` x1 · `30.4832f` x1 · `260.1765f` x1 · `-1359.8f` x1

## Other strings

Literals whose consuming native was not classified:

`Dom`, `EXTREME_02_SKYDIVE`, `EXTREME_02_INSIDE_PLANE`, `DOM_Flatbed_truck`, `EXTREME_02_OPEN_PARACHUTE`, `EXTREME_02_DRIVE_UP_RAMP`, `EXTREME_02_PLANE_TAKEOFF_CUTSCENE`, `EXTREME_02_FOCUS_ON_PLANE`, `EXTREME_02_DRIVE_TO_PLANE`, `EXTREME2_STOP`, `Force cleanup [TERMINATING]`, `EXTREME2_RESTART2`, `rcmextreme2`, `DEFAULT_SCRIPTED_CAMERA`, `EXTREME_02_SOUNDSET`, `EXT2_02`, `EXTREME2_PARA`, `es_2_rcm_concat`, `Franklin_Quad`, `EXT2_JUMPOFF`, `EXT2_TRICKS`, `EXTREME2_JUMP`, `SF_Extreme2`, `EXTREME2_FAIL`, `EXT2_F1`, `EXT2_F3`, `EXT2_F2`, `EXT2_F5`, `EXT2_F7`, `EXT2_F8`

---

Source: `decompiled_scripts/extreme2.c`
