# cablecar.c

Minigames script. 4 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 35,276 |
| Functions | 305 (69 unique, 236 shared) |
| Unique lines | 2,645 (7.5% of file) |

## Assets

**Animations** (1) - `p_cablecar_s`

**Models and props** (4) - `p_cablecar_s`, `p_cablecar_s_door_l`, `p_cablecar_s_door_r`, `P_CableCar_S`

**Sounds** (9) - `CABLE_CAR_SOUNDS`, `CABLE_CAR_RIDE_DOWN_SCENE`, `CABLE_CAR_RIDE_UP_SCENE`, `DOOR_CLOSE`, `Arrive_Station`, `DOOR_OPEN`, `Running`, `Leave_Station`, `Interior_Rain`

**Text labels** (3) - `RAIN`, `THUNDER`, `NULL`

**Scripts launched** (2) - `cablecar`, `bailbond3`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (71), `GET_GAME_TIMER` (19), `ATTACH_ENTITY_TO_ENTITY` (19), `GET_ENTITY_COORDS` (15), `SET_ENTITY_COORDS` (15), `PLAY_SOUND_FROM_ENTITY` (14), `DETACH_ENTITY` (12), `TIMESTEP` (12), `IS_ENTITY_ATTACHED` (10), `WAIT` (8), `PLAYER_ID` (8), `DISABLE_CONTROL_ACTION` (8), `CLEAR_HELP` (7), `IS_ENTITY_IN_ANGLED_AREA` (6), `GET_DISTANCE_BETWEEN_COORDS` (6), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (6), `IS_AUDIO_SCENE_ACTIVE` (6), `SET_MINIMAP_FOW_REVEAL_COORDINATE` (5), `DOES_ENTITY_EXIST` (5), `CREATE_OBJECT` (5), `STREAMVOL_IS_VALID` (5), `STREAMVOL_DELETE` (5), `SET_ENTITY_VISIBLE` (4), `IS_SCREEN_FADED_OUT` (4), `IS_SPHERE_VISIBLE` (4), `GET_PLAYER_WANTED_LEVEL` (4), `SET_ENTITY_HEADING` (4), `IS_CONTROL_JUST_PRESSED` (4), `STOP_AUDIO_SCENE` (4), `GET_FINAL_RENDERED_CAM_COORD` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-0.2f` x15 · `12.25f` x2 · `2.75f` x2 · `2.63f` x2 · `-2.75f` x2 · `446.2582f` x1 · `5582.625f` x1 · `780.1892f` x1 · `446.3005f` x1 · `5560.008f` x1 · `786.9392f` x1 · `-742.3477f` x1 · `5587.019f` x1 · `40.66549f` x1 · `-742.1461f` x1 · `5602.772f` x1 · `49.8471f` x1 · `1.05f` x1 · `0.2f` x1 · `0.5f` x1 · `1.1f` x1 · `1.125f` x1

## Other strings

Literals whose consuming native was not classified:

`AZ_COUNTRYSIDE_CHILEAD_CABLE_CAR_LINE`, `_up_9`, `WAIT_CABLE`, `DEFAULT_SCRIPTED_CAMERA`, `_up_1`, `_up_3`, `_up_4`, `_up_5`, `_up_6`, `_up_8`, `_down_2`, `_down_3`, `_down_6`, `_down_8`, `_down_9`, `CAR_IN_CABLECAR`, `CABLE_WANTED`, `PLAY_CABLE`, `CABLE_CAR`, `CABLE_CAR_SOUNDS`, `PLAY_CABLE_NO_CASH`, `cablecar`, `FGND_SWTCHCAM`, `_down_1`, `_down_4`, `_down_5`, `cablecar_up`, `cablecar_down`

---

Source: `decompiled_scripts/cablecar.c`
