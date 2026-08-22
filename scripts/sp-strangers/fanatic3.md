# fanatic3.c

SP strangers and freaks script. 5 anim dicts; 16 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 50,447 |
| Functions | 555 (88 unique, 467 shared) |
| Unique lines | 5,257 (10.4% of file) |

## Assets

**Animation dictionaries** (5) - `rcmfanatic3`, `rcmfanatic3leadinoutef_3_mcs_1`, `rcmfanatic1out_of_breath`, `rcmfanatic1maryann_stretchidle_b`, `FEMALE_FAST_RUNNER`

**Animations** (11) - `rcmfanatic3leadinoutef_3_mcs_1`, `rcmfanatic3`, `leadout_ef_3_mcs_maryann`, `ef_3_rcm_action_maryann`, `Fra_outofbreath_intro`, `ef_3_rcm_loop_maryann`, `binoculars`, `base`, `rcmfanatic1maryann_stretchidle_b`, `idle_e`, `KNEEL_IDLE_A`

**Models and props** (16) - `a_f_y_runner_01`, `a_m_y_musclbeac_02`, `a_f_m_ktown_02`, `s_m_m_dockwork_01`, `ig_maryann`, `scorcher`, `a_m_y_beachvesp_01`, `baller`, `prop_binoc_01`, `a_m_y_hiker_01`, `patriot`, `a_c_retriever`, `prop_beach_towel_01`, `prop_energy_drink`, `prop_freeweight_01`, `prop_freeweight_02`

**Sounds** (3) - `FANATIC_MIX_SCENE`, `CHECKPOINT_NORMAL`, `HUD_MINI_GAME_SOUNDSET`

**Text labels** (8) - `FAN3AUD`, `FRANKLIN`, `MARYANN`, `FAN3DOGOWNER`, `FATIC3`, `NULL`, `FATIC3_15`, `FATIC3_12`

**Waypoint recordings** (10) - `fan3_pedJog`, `Fan3_pedBike`, `Fan3_baddriver`, `Fan3_RollingStart`, `fan3_ownerroute`, `fan3_dogroute`, `Fan3_pedBikePanic`, `Fan3_pedBikePrep`, `fanatic3_assist`, `Fan3_jetskiRoute`

**Vehicle recordings** (1) - `Fan3_MaryAnnBikeJump`

**Relationship groups** (1) - `Buddy`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (153), `GET_HUD_COLOUR` (41), `GET_ENTITY_COORDS` (33), `GET_GAME_TIMER` (25), `GET_DISTANCE_BETWEEN_COORDS` (21), `SET_CHECKPOINT_RGBA` (19), `SET_CHECKPOINT_RGBA2` (19), `WAIT` (18), `SET_ENTITY_COORDS` (18), `SET_ENTITY_HEADING` (18), `CREATE_CHECKPOINT` (17), `CLEAR_PED_TASKS` (15), `PLAYER_ID` (15), `GET_IS_WAYPOINT_RECORDING_LOADED` (15), `OPEN_SEQUENCE_TASK` (14), `CLOSE_SEQUENCE_TASK` (14), `DOES_ENTITY_EXIST` (14), `REQUEST_MODEL` (14), `TASK_PERFORM_SEQUENCE` (13), `CLEAR_SEQUENCE_TASK` (13), `SET_MODEL_AS_NO_LONGER_NEEDED` (12), `GET_VEHICLE_PED_IS_IN` (12), `HAS_MODEL_LOADED` (12), `DELETE_CHECKPOINT` (11), `TRIGGER_MUSIC_EVENT` (11), `TASK_ENTER_VEHICLE` (11), `REQUEST_WAYPOINT_RECORDING` (11), `ROUND` (10), `TASK_SMART_FLEE_PED` (10), `IS_PED_IN_VEHICLE` (10)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`3.2f` x17 · `2.4f` x12 · `0.5f` x9 · `1.6f` x8 · `1.2f` x7 · `0.1f` x6 · `104.65f` x5 · `7003.12f` x5 · `6.43f` x5 · `1.7f` x5 · `0.7f` x4 · `0.9f` x3 · `1.5f` x3 · `-191.0984f` x3 · `6550.964f` x3 · `10.0973f` x3 · `-199.4099f` x3 · `6542.312f` x3 · `11.09729f` x3 · `-226.3857f` x3 · `6498.877f` x3 · `9.2147f` x3 · `-173.1313f` x3 · `6595.771f` x3

## Other strings

Literals whose consuming native was not classified:

`Fan3_pedBike`, `scorcher`, `MotionState_Run`, `MISSION_FAILED reason=FAILED_BIKE_DESTROYED`, `FANATIC2_STOP`, `player`, `iBinocStage = 2`, `patriot`, `Mary_Ann`, `Franklin`, `MISSION_FAILED reason=FAILED_GENERIC`, `MISSION_FAILED reason=FAILED_OUT_OF_TIME`, `MISSION_FAILED reason=FAILED_LOST_RACE`, `MISSION_FAILED reason=FAILED_WOMAN_DIED`, `MISSION_FAILED reason=FAILED_WOMAN_HURT`, `MISSION_FAILED reason=FAILED_WOMAN_SCARED`, `MISSION_FAILED reason=FAILED_LEFT_AREA`, `FATIC3_15`, `FAN3_DOG`, `FAN3_DSCARE`, `iBinocStage = 3`, `FAN3_JOGCH2B`, `FAN3_JOGCH2A`, `FAN3_JOGCH3`, `FAN3_SWIMWIN`, `FAN3_SWIMLOS`, `FAN3_RUNTO`, `*** Clearing Mary Ann tasks (ma_pDoToBikeTask())`, `fDist is`, `Setting fMoveRatio to`

---

Source: `decompiled_scripts/fanatic3.c`
