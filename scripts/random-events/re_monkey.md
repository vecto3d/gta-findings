# re_monkey.c

Random events script. 1 anim dicts; 5 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 5,443 |
| Functions | 160 (26 unique, 134 shared) |
| Unique lines | 721 (13.2% of file) |

## Assets

**Animation dictionaries** (1) - `switch@franklin@lamar_tagging_wall`

**Models and props** (5) - `u_m_m_streetart_01`, `prop_paints_can02`, `prop_paint_brush05`, `prop_paint_spray01b`, `prop_cs_spray_can`

**Text labels** (1) - `NULL`

**Relationship groups** (1) - `player`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (18), `DOES_ENTITY_EXIST` (7), `GET_ENTITY_COORDS` (6), `IS_ENTITY_PLAYING_ANIM` (5), `TASK_PLAY_ANIM` (4), `GET_GAME_TIMER` (4), `CREATE_OBJECT` (4), `FREEZE_ENTITY_POSITION` (3), `GET_ENTITY_ANIM_CURRENT_TIME` (3), `TO_FLOAT` (3), `SET_ENTITY_COORDS_NO_OFFSET` (3), `SET_ENTITY_ROTATION` (3), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (2), `SET_GAMEPLAY_CAM_RELATIVE_PITCH` (2), `DO_SCREEN_FADE_IN` (2), `OPEN_SEQUENCE_TASK` (2), `CLOSE_SEQUENCE_TASK` (2), `TASK_PERFORM_SEQUENCE` (2), `CLEAR_SEQUENCE_TASK` (2), `SET_PED_FLEE_ATTRIBUTES` (2), `TASK_SMART_FLEE_PED` (2), `VDIST2` (2), `DETACH_ENTITY` (2), `IS_ENTITY_IN_ANGLED_AREA` (2), `GET_ENTITY_MODEL` (2), `HAS_FORCE_CLEANUP_OCCURRED` (1), `WAIT` (1), `IS_WORLD_POINT_WITHIN_BRAIN_ACTIVATION_RANGE` (1), `IS_PED_IN_ANY_VEHICLE` (1), `IS_PED_IN_ANY_HELI` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`46.02f` x4 · `0.161f` x2 · `-335.66f` x2 · `-95.24f` x2 · `46.16f` x2 · `-336.04f` x2 · `-94.9f` x2 · `-336.34f` x2 · `-95.66f` x2 · `-347.4067f` x1 · `-93.5801f` x1 · `44.6639f` x1 · `306.0178f` x1 · `0.349f` x1 · `0.2f` x1 · `-334.4651f` x1 · `-93.42171f` x1 · `48.57328f` x1 · `-332.2641f` x1 · `-82.78552f` x1 · `45.8103f` x1 · `-329.1134f` x1 · `-83.87273f` x1 · `45.79989f` x1

## Other strings

Literals whose consuming native was not classified:

`player_zero`, `player_one`, `player_two`, `scr_lamgraff_paint_spray`, `lamar_tagging_wall_loop_lamar`, `lamar_tagging_wall_exit_lamar`, `lamar_tagging_exit_loop_lamar`

---

Source: `decompiled_scripts/re_monkey.c`
