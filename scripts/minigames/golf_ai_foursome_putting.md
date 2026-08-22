# golf_ai_foursome_putting.c

Minigames script. 1 anim dicts; 6 models; 2 particle effects.

| | |
|---|---|
| Category | Minigames |
| Total lines | 8,150 |
| Functions | 319 (114 unique, 205 shared) |
| Unique lines | 3,387 (41.6% of file) |

## Assets

**Animation dictionaries** (1) - `move_m@golfer@`

**Animations** (6) - `mini@golfai`, `putt_approach_no_ball`, `iron_swing_action`, `putt_action`, `wedge_swing_action`, `wood_swing_action`

**Models and props** (6) - `prop_golf_ball`, `a_m_y_golfer_01`, `caddy`, `a_f_y_golfer_01`, `prop_golf_putter_01`, `prop_golf_pitcher_01`

**Sounds** (4) - `GOLF_BALL_IMPACT_FLAG_MASTER`, `GOLF_BALL_CUP_MISS_MASTER`, `GOLF_BALL_IN_WATER_MASTER`, `GOLF_FORWARD_SWING_HARD_MASTER`

**Particle effects** (2) - `scr_golf_landing_water`, `scr_golf_ball_trail`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_ENTITY_EXIST` (31), `GET_ENTITY_COORDS` (28), `IS_ENTITY_PLAYING_ANIM` (20), `IS_ENTITY_DEAD` (13), `ABSF` (13), `GET_ENTITY_ANIM_CURRENT_TIME` (13), `TASK_PLAY_ANIM` (13), `CLEAR_PED_TASKS` (12), `SET_ENTITY_COORDS` (12), `VDIST2` (11), `GET_RANDOM_FLOAT_IN_RANGE` (9), `GET_SCRIPT_TASK_STATUS` (9), `SET_ENTITY_ANIM_SPEED` (8), `SET_ENTITY_RECORDS_COLLISIONS` (7), `GET_GROUND_Z_FOR_3D_COORD` (7), `OPEN_SEQUENCE_TASK` (6), `CLOSE_SEQUENCE_TASK` (6), `TASK_PERFORM_SEQUENCE` (6), `CLEAR_SEQUENCE_TASK` (6), `PLAY_SOUND_FROM_ENTITY` (6), `PLAYER_PED_ID` (5), `IS_PED_INJURED` (5), `TASK_FOLLOW_NAV_MESH_TO_COORD` (5), `GET_LAST_MATERIAL_HIT_BY_ENTITY` (5), `DRAW_DEBUG_LINE` (5), `SET_ENTITY_HEADING` (5), `IS_SPHERE_VISIBLE` (4), `GET_ENTITY_VELOCITY` (4), `COS` (4), `SET_ENTITY_ANIM_CURRENT_TIME` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x7 · `2.96f` x2 · `0.3f` x2 · `0.1601f` x2 · `0.975f` x2 · `0.6f` x2 · `0.8f` x2 · `2.5f` x1 · `9.5f` x1 · `0.2f` x1 · `0.5f` x1 · `0.05f` x1 · `0.95f` x1 · `0.01f` x1 · `0.15f` x1 · `1.25f` x1 · `0.35f` x1 · `0.999f` x1 · `1.5f` x1

## Other strings

Literals whose consuming native was not classified:

`GOLF_SWING_TEE_IRON_MASTER`, `GOLF_SWING_CHIP_PERFECT_MASTER`, `GOLF_SWING_CHIP_MASTER`, `Idle`, `_High`, `scr_golf_landing_thick_grass`, `scr_golf_hit_branches`, `scr_golf_landing_bunker`, `react_`, `nuetral_01`, `Wood_`, `Iron_`, `Wedge_`, `Putt_`, `Swing_`, `Wood_swing_action`, `Iron_swing_action`, `Wedge_swing_action`, `Putt_action`, `scr_golf_strike_fairway`, `scr_golf_strike_fairway_bad`, `scr_golf_strike_thick_grass`, `scr_golf_strike_bunker`, `scr_golf_tee_perfect`, `GOLF_SWING_GRASS_LIGHT_MASTER`, `GOLF_SWING_GRASS_PERFECT_MASTER`, `GOLF_SWING_GRASS_MASTER`, `GOLF_SWING_TEE_LIGHT_MASTER`, `GOLF_SWING_TEE_PERFECT_MASTER`, `GOLF_SWING_TEE_MASTER`

---

Source: `decompiled_scripts/golf_ai_foursome_putting.c`
