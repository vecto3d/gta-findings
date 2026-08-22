# hunting2.c

Jobs script. 9 anim dicts; 4 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 51,814 |
| Functions | 585 (106 unique, 479 shared) |
| Unique lines | 5,569 (10.7% of file) |

## Assets

**Animation dictionaries** (9) - `rcmhunting2`, `creatures@deer@amb@world_deer_grazing@enter`, `creatures@deer@amb@world_deer_grazing@idle_a`, `creatures@deer@amb@world_deer_grazing@exit`, `creatures@deer@amb@world_deer_grazing@base`, `facials@p_m_one@variations@elkcall`, `gestures@m@standing@casual`, `amb@world_human_guard_patrol@male@idle_a`, `oddjobs@hunter`

**Animations** (19) - `creatures@deer@amb@world_deer_grazing@idle_a`, `creatures@deer@amb@world_deer_grazing@base`, `base`, `idle_b`, `creatures@deer@amb@world_deer_grazing@enter`, `enter`, `creatures@deer@amb@world_deer_grazing@exit`, `exit`, `idle_a`, `idle_c`, `facials@p_m_one@variations@elkcall`, `mood_elkcal_1`, `gestures@m@standing@casual`, `gesture_point`, `amb@world_human_guard_patrol@male@idle_a`, `oddjobs@hunter`, `point_fwd`, `rcmhunting2`, `_idle_loop`

**Models and props** (4) - `a_c_deer`, `a_c_mtlion`, `a_c_boar`, `p_cletus_necklace_s`

**Audio banks** (3) - `SCRIPT\HUNTING_2_ELK_CALLS`, `SCRIPT\HUNTING_2_ELK_VOCALS`, `SCRIPT\HUNTING_MAIN_A`

**Sounds** (9) - `HUNTING_02_SETTINGS`, `ELK_PAIN_MASTER`, `ELK_BREY_MASTER`, `Concentration`, `HUNTING_02_TRAFFIC_SCENE`, `AMBIENT_HUNTING_MIX`, `PLAYER_CALLS_ELK_MASTER`, `Heart_Breathing`, `Breathing`

**Speech contexts** (1) - `TREVOR_NORMAL`

**Texture dicts** (1) - `Hunting`

**Text labels** (6) - `TREVOR`, `CLETUS`, `NULL`, `HT2AUD`, `HT_BAC`, `HUNT2`

**Scenarios** (1) - `WORLD_MOUNTAIN_LION_WANDER`

**Decorators** (1) - `doe_elk`

**Waypoint recordings** (3) - `HT2_CLE_0_1`, `HT2_CLE_1_2`, `HT2_CLE_2_3`

**Relationship groups** (2) - `FRIENDLIES`, `Elk Group`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (138), `GET_GAME_TIMER` (97), `DOES_ENTITY_EXIST` (34), `GET_RANDOM_INT_IN_RANGE` (34), `GET_ENTITY_COORDS` (33), `TASK_PLAY_ANIM` (22), `SET_SCENARIO_PED_DENSITY_MULTIPLIER_THIS_FRAME` (20), `CLEAR_PED_TASKS` (19), `SET_VEHICLE_DENSITY_MULTIPLIER_THIS_FRAME` (18), `PLAY_SOUND_FROM_ENTITY` (17), `DOES_BLIP_EXIST` (15), `ADD_NAVMESH_BLOCKING_OBJECT` (14), `CLEAR_HELP` (13), `SET_PED_CAN_USE_AUTO_CONVERSATION_LOOKAT` (13), `IS_PED_INJURED` (12), `GET_SCRIPT_TASK_STATUS` (12), `TASK_LOOK_AT_ENTITY` (12), `PLAYER_ID` (12), `IS_SCREEN_FADED_OUT` (11), `TASK_FOLLOW_NAV_MESH_TO_COORD` (11), `CLEAR_PRINTS` (10), `TASK_CLEAR_LOOK_AT` (10), `GET_RANDOM_FLOAT_IN_RANGE` (10), `GET_DISTANCE_BETWEEN_COORDS` (9), `REQUEST_ANIM_DICT` (9), `SETTIMERA` (9), `TIMERA` (8), `IS_AUDIO_SCENE_ACTIVE` (7), `IS_ENTITY_DEAD` (7), `SET_PED_KEEP_TASK` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x13 · `0.5f` x5 · `-605.36f` x2 · `5856.549f` x2 · `22.7741f` x2 · `0.1f` x1 · `359.9f` x1 · `0.75f` x1 · `-641.6511f` x1 · `5846.579f` x1 · `20.3501f` x1 · `-642.212f` x1 · `5851.602f` x1 · `19.9536f` x1 · `-627.1213f` x1 · `5833.185f` x1 · `22.5278f` x1 · `-636.4395f` x1 · `5829.735f` x1 · `22.0155f` x1 · `-607.6405f` x1 · `5834.451f` x1 · `24.6594f` x1 · `-594.2007f` x1

## Other strings

Literals whose consuming native was not classified:

`HT_BAC`, `HT_OBJ`, `HT_CALL`, `AMMO_SNIPER`, `HT_TXTMSG`, `HT_PHOTO`, `HT_NOGOOD`, `HT_MISS`, `player`, `Cletus`, `HT2_SPOOK`, `HT_CUT`, `HT_FAIL4A`, `HT_FAIL4`, `HT_WGUN`, `HT_BADREC`, `HT_HEARD`, `Player has done third elk`, `Player has done second elk`, `Player has done first elk`, `Mocap Intro Done`, `HT_FOLLOW`, `HUN_2_MCS_1`, `Cletus_Gun`, `Trevors_Weapon`, `MotionState_Walk`, `GROUP_SNIPER`, `HT2_WHISTLE2`, `HT_PAIR`, `HT2_SHDOE`

---

Source: `decompiled_scripts/hunting2.c`
