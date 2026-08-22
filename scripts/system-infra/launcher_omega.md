# launcher_omega.c

System and infrastructure script. 1 models; 3 scaleforms.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 12,090 |
| Functions | 295 (10 unique, 285 shared) |
| Unique lines | 497 (4.1% of file) |

## Assets

**Models and props** (1) - `prop_cs_walkie_talkie`

**Sounds** (2) - `IDLE_BEEP`, `EPSILONISM_04_SOUNDSET`

**Scaleform movies** (3) - `SET_COLOUR`, `SET_DISTANCE`, `digiscanner`

**Text labels** (3) - `SCRAPAU`, `OMEGA`, `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (9), `DOES_ENTITY_EXIST` (8), `PLAYER_PED_ID` (8), `GET_GAME_TIMER` (6), `TERMINATE_THIS_THREAD` (4), `WAIT` (3), `BEGIN_SCALEFORM_MOVIE_METHOD` (2), `END_SCALEFORM_MOVIE_METHOD` (2), `SET_MODEL_AS_NO_LONGER_NEEDED` (2), `IS_NAMED_RENDERTARGET_REGISTERED` (2), `GET_WEAPONTYPE_MODEL` (2), `REQUEST_MODEL` (2), `SET_ALL_VEHICLE_GENERATORS_ACTIVE_IN_AREA` (2), `GET_ENTITY_COORDS` (2), `CREATE_OBJECT` (2), `ATTACH_ENTITY_TO_ENTITY` (2), `GET_PED_BONE_INDEX` (2), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_FLOAT` (1), `GET_STANDARD_BLIP_ENUM_ID` (1), `GET_WAYPOINT_BLIP_ENUM_ID` (1), `SET_THIS_IS_A_TRIGGER_SCRIPT` (1), `HAS_FORCE_CLEANUP_OCCURRED` (1), `IS_WORLD_POINT_WITHIN_BRAIN_ACTIVATION_RANGE` (1), `CLEAR_AREA` (1), `PLAY_SOUND_FROM_COORD` (1), `SET_TEXT_RENDER_ID` (1), `DRAW_SCALEFORM_MOVIE` (1), `REQUEST_SCALEFORM_MOVIE` (1), `HAS_SCALEFORM_MOVIE_LOADED` (1), `REGISTER_NAMED_RENDERTARGET` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`2468.51f` x4 · `3437.39f` x4 · `49.9f` x2 · `2314.546f` x2 · `2576.33f` x2 · `44.7f` x2 · `2326.446f` x2 · `2579.608f` x2 · `47.6645f` x2 · `2319.443f` x1 · `2583.588f` x1 · `46.7663f` x1 · `2321.252f` x1 · `2578.851f` x1 · `46.7f` x1 · `0.09f` x1 · `0.072f` x1 · `-0.006f` x1 · `0.1f` x1 · `0.08f` x1 · `162.72f` x1 · `5.4f` x1 · `1.8f` x1

## Other strings

Literals whose consuming native was not classified:

`SCRIPT TERMINATED`, `digiscanner`, `SCRAP_1_AMB`, `SCRAP_2_AMB`, `OMEGA LAUNCHER RC`, `Force cleanup [TERMINATING]`, `Relinquishing candidate id...`, `Player out of range [TERMINATING]`, `Created initial scene`, `dune2`, `SCRAP_2_RCM`, `rcmrc_omega_2`, `omega_idle_looking_around`, `rcmrc_omega_1`, `omega_idle_geiger_counter`, `start conversation`, `conversation ended`, `pause conversation`, `unpause conversation`, `SCRIPT TERMINATING: Cleaning up entities in Launcher`, `SCRIPT TERMINATING: Ending off-mission cutscene request`, `SCRAP_1_RCM`

---

Source: `decompiled_scripts/launcher_omega.c`
