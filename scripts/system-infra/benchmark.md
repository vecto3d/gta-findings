# benchmark.c

System and infrastructure script. 8 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 102,903 |
| Functions | 582 (46 unique, 536 shared) |
| Unique lines | 1,430 (1.4% of file) |

## Assets

**Models and props** (8) - `s_m_y_cop_01`, `s_f_y_cop_01`, `g_m_m_armboss_01`, `g_m_m_armgoon_01`, `g_m_m_armlieut_01`, `s_m_y_construct_01`, `s_m_m_trucker_01`, `player_zero`

**Audio banks** (1) - `TIME_LAPSE`

**Sounds** (1) - `TOD_SHIFT_SCENE`

**Text labels** (7) - `EXTRASUNNY`, `COP`, `NULL`, `SMOG`, `RAIN`, `CLEAR`, `BMARK`

**Relationship groups** (1) - `rel_group_peds`

**Scripts launched** (1) - `director_mode`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (41), `PLAYER_ID` (21), `WAIT` (16), `GET_GAME_TIMER` (15), `SET_ENTITY_INVINCIBLE` (9), `SET_MODEL_AS_NO_LONGER_NEEDED` (7), `HAS_MODEL_LOADED` (7), `REQUEST_MODEL` (7), `IS_PED_IN_VEHICLE` (6), `RENDER_SCRIPT_CAMS` (6), `SET_VEHICLE_MOD` (6), `DOES_CAM_EXIST` (5), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (5), `GET_ENTITY_COORDS` (5), `SET_CINEMATIC_MODE_ACTIVE` (5), `TOGGLE_VEHICLE_MOD` (5), `SET_PED_CONFIG_FLAG` (5), `DISABLE_CONTROL_ACTION` (5), `SET_WEATHER_TYPE_NOW_PERSIST` (5), `TERMINATE_THIS_THREAD` (4), `CLEAR_HELP` (4), `EXPLODE_VEHICLE` (4), `FREEZE_ENTITY_POSITION` (4), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (4), `CLEAR_AREA` (4), `CREATE_VEHICLE` (4), `GET_VEHICLE_RECORDING_ID` (4), `SET_RELATIONSHIP_BETWEEN_GROUPS` (4), `UI_STARTED_END_USER_BENCHMARK` (3), `SET_GAME_PAUSED` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x2 · `-503.5369f` x1 · `261.8961f` x1 · `88.6503f` x1 · `-0.1443f` x1 · `103.3085f` x1 · `0.7f` x1 · `295.1843f` x1 · `168.9212f` x1 · `111.301f` x1 · `-43.0954f` x1 · `1.3863f` x1 · `0.05f` x1 · `0.88f` x1 · `0.6f` x1

## Other strings

Literals whose consuming native was not classified:

`BMARK_EXIT`, `pc_bench`, `player`, `player_zero`, `lazer`, `patriot`, `tanker`, `FBR_GENERIC`, `FBR_BENCHMARK`, `BMARK_FPS`, `HAND_SHAKE`, `cirrocumulus`, `DEFAULT_SPLINE_CAMERA`, `phantom`, `boxville`, `SPMG_30_STR`

---

Source: `decompiled_scripts/benchmark.c`
