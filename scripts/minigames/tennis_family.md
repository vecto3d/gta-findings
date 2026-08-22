# tennis_family.c

Minigames script. 4 anim dicts; 3 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 10,401 |
| Functions | 343 (51 unique, 292 shared) |
| Unique lines | 3,754 (36.1% of file) |

## Assets

**Animation dictionaries** (4) - `mini@tennis`, `mini@tennis@female`, `weapons@tennis@male`, `mini@triathlon`

**Animations** (7) - `mini@tennis`, `idle`, `idle_2_serve`, `serve`, `ready_2_idle`, `mini@tennis@female`, `idle_2_ready`

**Models and props** (3) - `prop_tennis_rack_01b`, `prop_tennis_ball`, `prop_vb_34_tencrt_lighting`

**Audio banks** (2) - `SCRIPT\Tennis`, `SCRIPT\TENNIS_VER2_A`

**Sounds** (6) - `TENNIS_PLYR_SERVE_MASTER`, `TENNIS_PLYR_SMASH_MASTER`, `TENNIS_AMB_SMASH_MASTER`, `TENNIS_NPC_SMASH_MASTER`, `TENNIS_AMB_SERVE_MASTER`, `TENNIS_NPC_SERVE_MASTER`

**Text labels** (1) - `NULL`

**Scripts launched** (1) - `tennis`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_PED_INJURED` (31), `PLAYER_PED_ID` (18), `VDIST2` (18), `DOES_ENTITY_EXIST` (16), `GET_GAME_TIMER` (12), `GET_HEADING_FROM_VECTOR_2D` (9), `PLAYER_ID` (9), `GET_RANDOM_FLOAT_IN_RANGE` (9), `GET_ENTITY_COORDS` (9), `PLAY_SOUND_FROM_ENTITY` (9), `IS_ENTITY_DEAD` (8), `SET_CONTROL_SHAKE` (8), `SET_ENTITY_HEADING` (7), `GET_SCRIPT_TASK_STATUS` (7), `ABSF` (7), `DETACH_ENTITY` (6), `SET_ENTITY_VISIBLE` (6), `SET_PED_COMPONENT_VARIATION` (6), `IS_TENNIS_MODE` (6), `TASK_PLAY_ANIM` (6), `IS_CONTROL_JUST_PRESSED` (6), `SET_PED_WEAPON_MOVEMENT_CLIPSET` (5), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (5), `SET_ENTITY_COORDS` (5), `IS_ENTITY_PLAYING_ANIM` (5), `IS_TASK_MOVE_NETWORK_ACTIVE` (5), `ARE_STRINGS_EQUAL` (5), `GET_TASK_MOVE_NETWORK_STATE` (5), `GET_RANDOM_INT_IN_RANGE` (5), `HAS_MODEL_LOADED` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x7 · `0.5f` x5 · `1.5f` x4 · `26.75f` x4 · `0.75f` x3 · `0.2f` x2 · `0.3f` x2 · `0.1f` x2 · `0.88f` x2 · `0.4f` x1 · `0.01f` x1 · `0.65f` x1 · `0.33f` x1 · `0.66f` x1 · `-769.058f` x1 · `165.294f` x1 · `66.474f` x1 · `-1171.28f` x1 · `-1599.59f` x1 · `3.34f` x1 · `487.5186f` x1 · `-217.7697f` x1 · `52.7864f` x1 · `-49.912f` x1

## Other strings

Literals whose consuming native was not classified:

`running`, `TennisServeSet`, `Intro`, `Idle1`, `player`, `TENN_WANTED`, `DISMISS_MICHAEL`, `GENERIC_CURSE_HIGH`, `GENERIC_INSULT_MALE`, `GENERIC_INSULT_MED`, `AMANDA_NORMAL`, `serve`, `react_ball_out`, `react_ball_out_lt`, `TennisServeSetWithIntro`, `ForcedStopDirection`, `IdleStarted`, `Idle3`, `Idle4`, `Speed`

---

Source: `decompiled_scripts/tennis_family.c`
