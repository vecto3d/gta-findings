# golf_ai_foursome.c

Minigames script. 1 anim dicts; 8 models; 2 particle effects.

| | |
|---|---|
| Category | Minigames |
| Total lines | 8,891 |
| Functions | 348 (140 unique, 208 shared) |
| Unique lines | 4,083 (45.9% of file) |

## Assets

**Animation dictionaries** (1) - `move_m@golfer@`

**Animations** (6) - `mini@golfai`, `putt_approach_no_ball`, `iron_swing_action`, `putt_action`, `wedge_swing_action`, `wood_swing_action`

**Models and props** (8) - `a_m_y_golfer_01`, `prop_golf_ball`, `prop_golf_putter_01`, `prop_golf_pitcher_01`, `prop_golf_wood_01`, `prop_golf_iron_01`, `a_f_y_golfer_01`, `caddy`

**Audio banks** (1) - `GOLF_I`

**Sounds** (4) - `GOLF_BALL_IMPACT_FLAG_MASTER`, `GOLF_BALL_CUP_MISS_MASTER`, `GOLF_BALL_IN_WATER_MASTER`, `GOLF_FORWARD_SWING_HARD_MASTER`

**Particle effects** (2) - `scr_golf_landing_water`, `scr_golf_ball_trail`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_ENTITY_EXIST` (43), `GET_ENTITY_COORDS` (31), `IS_ENTITY_DEAD` (27), `IS_ENTITY_PLAYING_ANIM` (20), `CLEAR_PED_TASKS` (17), `VDIST2` (16), `SET_ENTITY_COORDS` (16), `PLAYER_PED_ID` (14), `ABSF` (13), `GET_ENTITY_ANIM_CURRENT_TIME` (13), `TASK_PLAY_ANIM` (13), `GET_SCRIPT_TASK_STATUS` (12), `GET_RANDOM_FLOAT_IN_RANGE` (9), `IS_PED_INJURED` (8), `SET_ENTITY_HEADING` (8), `SET_ENTITY_ANIM_SPEED` (8), `GET_GROUND_Z_FOR_3D_COORD` (7), `SET_ENTITY_RECORDS_COLLISIONS` (7), `TASK_FOLLOW_NAV_MESH_TO_COORD` (6), `OPEN_SEQUENCE_TASK` (6), `CLOSE_SEQUENCE_TASK` (6), `TASK_PERFORM_SEQUENCE` (6), `CLEAR_SEQUENCE_TASK` (6), `PLAY_SOUND_FROM_ENTITY` (6), `TASK_TURN_PED_TO_FACE_COORD` (5), `GET_LAST_MATERIAL_HIT_BY_ENTITY` (5), `DRAW_DEBUG_LINE` (5), `SET_VEHICLE_AS_NO_LONGER_NEEDED` (4), `TASK_ENTER_VEHICLE` (4), `GET_ENTITY_VELOCITY` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x8 · `2.96f` x2 · `0.3f` x2 · `0.1601f` x2 · `0.975f` x2 · `0.6f` x2 · `0.8f` x2 · `-1241.802f` x1 · `107.3439f` x1 · `55.7186f` x1 · `342.8433f` x1 · `-1243.465f` x1 · `104.3183f` x1 · `55.5857f` x1 · `306.093f` x1 · `-1257.234f` x1 · `94.0251f` x1 · `54.784f` x1 · `240.9284f` x1 · `2.5f` x1 · `9.5f` x1 · `0.2f` x1 · `0.5f` x1 · `0.05f` x1

## Other strings

Literals whose consuming native was not classified:

`GOLF_SWING_TEE_IRON_MASTER`, `GOLF_SWING_CHIP_PERFECT_MASTER`, `GOLF_SWING_CHIP_MASTER`, `Idle`, `_High`, `caddy`, `scr_golf_landing_thick_grass`, `scr_golf_hit_branches`, `scr_golf_landing_bunker`, `react_`, `nuetral_01`, `Wood_`, `Iron_`, `Wedge_`, `Putt_`, `Swing_`, `Wood_swing_action`, `Iron_swing_action`, `Wedge_swing_action`, `Putt_action`, `scr_golf_strike_fairway`, `scr_golf_strike_fairway_bad`, `scr_golf_strike_thick_grass`, `scr_golf_strike_bunker`, `scr_golf_tee_perfect`, `GOLF_SWING_GRASS_LIGHT_MASTER`, `GOLF_SWING_GRASS_PERFECT_MASTER`, `GOLF_SWING_GRASS_MASTER`, `GOLF_SWING_TEE_LIGHT_MASTER`, `GOLF_SWING_TEE_PERFECT_MASTER`

---

Source: `decompiled_scripts/golf_ai_foursome.c`
