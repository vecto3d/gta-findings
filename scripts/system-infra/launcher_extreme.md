# launcher_extreme.c

System and infrastructure script. 1 anim dicts; 1 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 12,318 |
| Functions | 297 (10 unique, 287 shared) |
| Unique lines | 537 (4.4% of file) |

## Assets

**Animation dictionaries** (1) - `rcmextreme3`

**Models and props** (1) - `a_c_retriever`

**Audio banks** (3) - `EXTREME_04_DOM_A`, `EXTREME_04_DOM_B`, `EXTREME_04_DOM_C`

**Sounds** (2) - `DOM_BREATHING`, `EXTREME_03_SOUNDSET`

**Text labels** (4) - `DOM`, `NULL`, `EXT2AU`, `EXT3AUD`

**Scenarios** (1) - `WORLD_VEHICLE_SALTON_DIRT_BIKE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (11), `DOES_ENTITY_EXIST` (6), `SET_VEHICLE_DOORS_LOCKED` (5), `TERMINATE_THIS_THREAD` (4), `REQUEST_MODEL` (4), `SET_MODEL_AS_NO_LONGER_NEEDED` (4), `SET_PED_CONFIG_FLAG` (4), `REQUEST_SCRIPT_AUDIO_BANK` (3), `SET_VEHICLE_COLOUR_COMBINATION` (3), `SET_VEHICLE_DIRT_LEVEL` (3), `WAIT` (2), `ADD_SCENARIO_BLOCKING_AREA` (2), `SET_SCENARIO_TYPE_ENABLED` (2), `HAS_SOUND_FINISHED` (2), `STOP_SOUND` (2), `GET_VEHICLE_PED_IS_IN` (2), `SET_PED_COMPONENT_VARIATION` (2), `REMOVE_SCENARIO_BLOCKING_AREA` (2), `GET_STANDARD_BLIP_ENUM_ID` (1), `GET_WAYPOINT_BLIP_ENUM_ID` (1), `GET_SOUND_ID` (1), `SET_THIS_IS_A_TRIGGER_SCRIPT` (1), `HAS_FORCE_CLEANUP_OCCURRED` (1), `IS_WORLD_POINT_WITHIN_BRAIN_ACTIVATION_RANGE` (1), `CLEAR_AREA` (1), `IS_ANY_SPEECH_PLAYING` (1), `PLAY_SOUND_FROM_ENTITY` (1), `IS_ENTITY_AT_COORD` (1), `GET_ENTITY_COORDS` (1), `IS_ENTITY_IN_ANGLED_AREA` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-2760.05f` x2 · `-954.5357f` x1 · `-2760.553f` x1 · `11.91636f` x1 · `-947.6847f` x1 · `-2749.719f` x1 · `15.63161f` x1 · `-63.8f` x1 · `-809.5f` x1 · `321.8f` x1 · `-954.19f` x1 · `14.64f` x1 · `-31.79f` x1 · `-954.2f` x1 · `14.04f` x1

## Other strings

Literals whose consuming native was not classified:

`SCRIPT TERMINATED`, `EXTREME LAUNCHER RC`, `idle_a`, `idle_c`, `Force cleanup [TERMINATING]`, `Relinquishing candidate id...`, `Player out of range [TERMINATING]`, `EXT2_AMB`, `EXT_AMB`, `TOPMAZE_HELP`, `Player below mission start location so displaying help text TOPMAZE_HELP`, `Special launching Extreme 2`, `Created initial scene`, `ES_4_RCM_P1`, `rcmextreme4`, `ES_3_RCM`, `rcmextreme3`, `idle_calm`, `fidget_02`, `blazer`, `flatbed`, `es_2_rcm_concat`, `rcmextreme2`, `sitting_idle`, `loop_punching`, `ES_1_RCM_P1`, `rcm_extreme1`, `Dom`, `SCRIPT TERMINATING: Cleaning up entities in Launcher`, `SCRIPT TERMINATING: Ending off-mission cutscene request`

---

Source: `decompiled_scripts/launcher_extreme.c`
