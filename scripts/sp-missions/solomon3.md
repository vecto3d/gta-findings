# solomon3.c

SP missions script. 6 anim dicts; 22 models; 4 scaleforms; 6 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 29,365 |
| Functions | 452 (72 unique, 380 shared) |
| Unique lines | 10,151 (34.6% of file) |

## Assets

**Animation dictionaries** (6) - `misssolomon_3`, `move_f@film_reel_arms`, `missheist_agency3aig_lift_waitped_a`, `misstrevor4`, `Misssolomon_3`, `amb@world_human_clipboard@male@base`

**Animations** (17) - `misssolomon_3`, `missheist_agency3aig_lift_waitped_a`, `molly_escapes_car_mol`, `misstrevor4`, `move_f@film_reel_arms`, `run`, `MISSSOLOMON_3`, `molly_death`, `dive_clear_goon1`, `dive_clear_goon2`, `idle_b`, `idle_a`, `idle_c`, `plyr_roll_left`, `_action`, `_react_to_death`, `_start_loop`

**Models and props** (22) - `s_m_y_cop_01`, `s_m_y_airworker`, `rapidgt`, `jet`, `ig_molly`, `prop_jet_bloodsplat_01`, `police3`, `cogcabrio`, `s_m_m_gentransport`, `s_m_y_fireman_01`, `shamal`, `prop_cs_film_reel_01`, `p_amb_clipboard_01`, `surano`, `carbonizzare`, `blista`, `oracle2`, `baller2`, `maverick`, `bison`, `tanker`, `firetruk`

**Audio banks** (5) - `SCRIPT\Trv_4_747_Tanker_Explosion`, `SCRIPT\Trv_4_747_Cop_Cars`, `Trv_4_747`, `SCRIPT\Trv_4_747_Plane_Explosion`, `SCRIPT\TV_Monitors`

**Sounds** (29) - `SOL_3_CHOPPER_CAM`, `SOL_3_CAR_JET_ENGINE`, `SOL_3_LOSE_COPS`, `SOL_3_LOSE_COPS_VEHICLE`, `SOL_3_LOSE_COPS_PLANE`, `SOL_3_ENGINE_DEATH_SCENE`, `SOL_3_DRIVE_TO_AIRPORT`, `SOL_3_MAIN_CHASE`, `SOL_3_EVENT_TANKER_CRASH`, `SOL_3_ARRIVE_AT_HANGAR`, `SOL_3_ON_FOOT_CHASE`, `SOL_3_HELI_TAKEOFF`, `SOL_3_PLANE_ON_FIRE`, `SOL_3_EVENT_JET_LANDING`, `SOL_3_EVENT_PLANE_TAXIING_EXPLOSION`, `Trevor_4_747_Carsplosion`, `Trevor_4_747_Flying_Car`, `Trevor_4_747_Jet_Engine`, `Trevor_4_747_Man_Sucked_In`, `PICK_UP`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `Trevor_4_747_Tanker_Horn`, `Trevor_4_747_Tanker_Explosion`, `TREVOR_4_MAIN_CHASE`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `Trevor_4_747_Molly_Open_Doors`, `Trevor_4_747_Loud_Fire`, `Trevor_4_747_TV`

**Speech contexts** (3) - `T1M4_BBAA`, `AIRPORTANNO`, `SPEECH_PARAMS_FORCE_FRONTEND`

**Scaleform movies** (4) - `SET_SCROLL_TEXT`, `DISPLAY_SCROLL_TEXT`, `BREAKING_NEWS`, `SET_TEXT`

**Particle effects** (6) - `scr_trev4_747_engine_heathaze`, `scr_trev4_747_exhaust_plane_misfire`, `scr_trev4_trailer_fire`, `scr_trev4_747_engine_damage`, `scr_trev4_747_blood_impact`, `scr_trev4_747_engine_debris`

**Texture dicts** (10) - `digitalOverlay`, `nscanline1`, `nscuzz1`, `nscuzz2`, `nscuzz3`, `Static1`, `Static2`, `Static3`, `Static4`, `Static5`

**Text labels** (10) - `T1M4AUD`, `MICHAEL`, `MOLLY`, `EXTRASUNNY`, `SOL3COP`, `TREV4`, `COP`, `NULL`, `SURROUNDED`, `TREV4POLICE3`

**Waypoint recordings** (2) - `Trev4_5`, `BB_MOLLY_2`

**Vehicle recordings** (3) - `BB_Chase`, `BB_CHASE`, `BB_AIChase`

**Relationship groups** (2) - `player`, `SecGuards`

**Interiors and entity sets** (1) - `V_60_HangerRm`

**Doors** (1) - `v_ilev_ss_door5_r`

**Vehicle mods** (3) - `rapidgt`, `surano`, `carbonizzare`

**Hashed names** (1) - `ENDS_IN_RUN`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_ENTITY_EXIST` (389), `PLAYER_PED_ID` (241), `IS_VEHICLE_DRIVEABLE` (179), `IS_PED_INJURED` (124), `GET_TIME_POSITION_IN_RECORDING` (115), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (87), `REQUEST_MODEL` (75), `HAS_MODEL_LOADED` (73), `SET_MODEL_AS_NO_LONGER_NEEDED` (63), `GET_GAME_TIMER` (51), `IS_AUDIO_SCENE_ACTIVE` (48), `GET_ENTITY_COORDS` (46), `PLAYER_ID` (43), `SET_VEHICLE_AS_NO_LONGER_NEEDED` (40), `SET_PED_AS_NO_LONGER_NEEDED` (40), `SET_PED_KEEP_TASK` (39), `CREATE_VEHICLE` (38), `DELETE_PED` (37), `STOP_AUDIO_SCENE` (36), `SET_PLAYBACK_SPEED` (36), `REMOVE_VEHICLE_RECORDING` (35), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (34), `DELETE_VEHICLE` (33), `IS_PED_IN_ANY_VEHICLE` (32), `STOP_PLAYBACK_RECORDED_VEHICLE` (32), `IS_MESSAGE_BEING_DISPLAYED` (31), `IS_ENTITY_DEAD` (30), `IS_SUBTITLE_PREFERENCE_SWITCHED_ON` (30), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_FLOAT` (26), `REQUEST_VEHICLE_RECORDING` (24)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x26 · `1.8f` x17 · `12.9451f` x14 · `12.945f` x8 · `1.5f` x6 · `13.4f` x5 · `1.7f` x5 · `-1037.398f` x4 · `-491.6539f` x4 · `35.5545f` x4 · `-952.1345f` x4 · `-2990.269f` x4 · `240.7726f` x4 · `-918.6263f` x4 · `-2926.631f` x4 · `12.9666f` x4 · `43.1705f` x4 · `34.66404f` x4 · `12.9445f` x4 · `-1042.5f` x3 · `-1019.5f` x3 · `-946.4231f` x3 · `-2979.826f` x3 · `12.9264f` x3

## Other strings

Literals whose consuming native was not classified:

`jet`, `TRV4_FAIL1`, `police3`, `rapidgt`, `cogcabrio`, `Michael`, `SOL_3_POLICE_CARS_Group`, `BB_Chase`, `surano`, `carbonizzare`, `TRV4_CHASE`, `shamal`, `blista`, `HangerWorker`, `maverick`, `bison`, `DEFAULT_SCRIPTED_CAMERA`, `player`, `TRV4_START_RT`, `M_LegalTrouble`, `PoliceScannerDisabled`, `TRV4_AIRPORT_ENTERED`, `firetruk`, `polmav`, `airtug`, `TRV4_FOOT_CHASE_RT`, `TRV4_EVADE_RT`, `TRV4_HELP3`, `TRV4_FAIL`, `TRV4_LOSE_COPS`

---

Source: `decompiled_scripts/solomon3.c`
