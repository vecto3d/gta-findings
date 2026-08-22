# ob_telescope.c

Object brains script. 2 developer state labels recovered; 1 anim dicts; 4 models; 1 scaleforms.

| | |
|---|---|
| Category | Object brains |
| Total lines | 78,485 |
| Functions | 405 (24 unique, 381 shared) |
| Unique lines | 1,462 (1.9% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`SCOPE FALLEN` · `SCOPE UPRIGHT`

## Assets

**Animation dictionaries** (1) - `MINI@TELESCOPE`

**Models and props** (4) - `xs_prop_arena_telescope_01`, `prop_telescope_01`, `prop_telescope`, `ex_prop_office_louvres`

**Audio banks** (1) - `TELESCOPES`

**Sounds** (8) - `Turn`, `Turn_Limit`, `velocity`, `Insert_Coin`, `Timer`, `Zoom`, `Zoom_Limit`, `10_Seconds`

**Scaleform movies** (1) - `observatory_scope`

**Text labels** (7) - `TELEHOME`, `TELEUSE`, `TELECSH`, `TELEHLP`, `TELEHLP2`, `NULL`, `IDLE`

**Timecycle modifiers** (1) - `telescope`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (63), `PLAYER_ID` (28), `GET_ENTITY_MODEL` (17), `HAS_SOUND_FINISHED` (15), `STOP_SOUND` (15), `GET_ENTITY_COORDS` (11), `PLAY_SOUND_FROM_ENTITY` (11), `IS_USING_KEYBOARD_AND_MOUSE` (11), `DOES_ENTITY_EXIST` (9), `TO_FLOAT` (9), `GET_GAME_TIMER` (8), `IS_ENTITY_AT_COORD` (8), `GET_SOUND_ID` (8), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (7), `GET_SCRIPT_TASK_STATUS` (7), `IS_ENTITY_IN_ANGLED_AREA` (6), `SET_PLAYER_CONTROL` (5), `SET_CURRENT_PED_WEAPON` (5), `SHUTDOWN_PC_SCRIPTED_CONTROLS` (5), `GET_CONTROL_NORMAL` (4), `WAIT` (4), `CLEAR_PED_TASKS` (4), `REQUEST_ANIM_DICT` (4), `HAS_ANIM_DICT_LOADED` (4), `CLEAR_HELP` (4), `GET_INTERIOR_FROM_ENTITY` (4), `GET_FOLLOW_PED_CAM_VIEW_MODE` (4), `NETWORK_IS_GAME_IN_PROGRESS` (4), `GET_ENTITY_ROTATION` (4), `IS_PED_INJURED` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`14.53664f` x6 · `529.3154f` x6 · `173.6282f` x6 · `12.65681f` x6 · `528.8023f` x6 · `175.8782f` x6 · `0.1f` x5 · `0.02f` x4 · `0.5f` x4 · `0.96f` x3 · `-0.03f` x2 · `0.05f` x2 · `-0.78f` x1 · `0.2f` x1 · `1.14f` x1 · `-0.4f` x1 · `1.5f` x1

## Other strings

Literals whose consuming native was not classified:

`PUBLIC_ENTER_FRONT`, `PUBLIC_IDLE`, `PUBLIC_EXIT_FRONT`, `UPRIGHT_ENTER_FRONT`, `UPRIGHT_IDLE`, `UPRIGHT_EXIT_FRONT`, `ENTER_FRONT`, `EXIT_FRONT`, `MotionState_Aiming`, `Ob_Telescope`, `service_spend_arena_spectator_box`, `service_spend_telescope`, `DEFAULT_SCRIPTED_CAMERA`, `TELESCOPE_High_End`, `TELESCOPE_COIN_OP`, `TELESCOPE_DOMESTIC`

---

Source: `decompiled_scripts/ob_telescope.c`
