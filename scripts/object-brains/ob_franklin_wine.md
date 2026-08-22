# ob_franklin_wine.c

Object brains script. 2 anim dicts; 10 models.

| | |
|---|---|
| Category | Object brains |
| Total lines | 96,487 |
| Functions | 468 (12 unique, 456 shared) |
| Unique lines | 920 (1.0% of file) |

## Assets

**Animation dictionaries** (2) - `MP_SAFEHOUSEWINE@`, `safe@franklin@ig_11`

**Models and props** (10) - `prop_wine_bot_01`, `prop_bong_01`, `p_cs_joint_01`, `prop_mr_raspberry_01`, `p_w_grass_gls_s`, `p_tumbler_02_s1`, `p_tumbler_cs2_s`, `p_tumbler_cs2_s_trev`, `p_wine_glass_s`, `prop_radio_01`

**Sounds** (1) - `FRANKLIN_SAFEHOUSE_ACTIVITIES_SCENE`

**Text labels** (1) - `NULL`

**Stats** (1) - `num_sh_wine_drank`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (39), `PLAYER_ID` (10), `PLAY_SYNCHRONIZED_ENTITY_ANIM` (10), `DISABLE_CONTROL_ACTION` (10), `CREATE_SYNCHRONIZED_SCENE` (8), `HIDE_HUD_AND_RADAR_THIS_FRAME` (8), `GET_SYNCHRONIZED_SCENE_PHASE` (6), `CLEAR_HELP` (5), `DOES_ENTITY_EXIST` (5), `SET_SYNCHRONIZED_SCENE_HOLD_LAST_FRAME` (5), `DOES_ENTITY_HAVE_DRAWABLE` (4), `DOES_CAM_EXIST` (4), `SET_SYNCHRONIZED_SCENE_PHASE` (4), `GET_ENTITY_HEADING` (4), `TASK_SYNCHRONIZED_SCENE` (4), `SET_ENTITY_COLLISION` (4), `IS_PED_INJURED` (3), `IS_ENTITY_IN_ANGLED_AREA` (3), `PLAY_ENTITY_ANIM` (3), `DESTROY_CAM` (3), `FREEZE_ENTITY_POSITION` (3), `GET_FOLLOW_PED_CAM_VIEW_MODE` (3), `SET_PLAYER_CONTROL` (3), `FORCE_ENTITY_AI_AND_ANIMATION_UPDATE` (3), `IS_AUDIO_SCENE_ACTIVE` (2), `REACTIVATE_NAMED_WORLD_BRAINS_WAITING_TILL_OUT_OF_RANGE` (2), `NETWORK_IS_GAME_IN_PROGRESS` (2), `HAS_FORCE_CLEANUP_OCCURRED` (2), `GET_ENTITY_MODEL` (2), `IS_ENTITY_ATTACHED` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x3 · `0.99f` x3 · `0.2f` x1 · `0.25f` x1

## Other strings

Literals whose consuming native was not classified:

`drink_1_cap`, `drink_3_cap`, `drink_4_cap`, `drink_2_cap`, `drink_2_bottle`, `drink_4_bottle`, `first_shot_bot`, `chop`, `drinking_wine_bottle`, `drink_3_bottle`, `drink_5_bottle`, `third_shot_bot`, `fourth_shot_bot`, `fifth_shot_bot`, `drink_5_cap`, `drinking_wine`, `drinking_wine_glass`, `drinking_wine_exit_glass`, `drinking_wine_exit_bottle`, `SA_WINE`, `DEFAULT_ANIMATED_CAMERA`, `HAND_SHAKE`, `WalkInterruptible`, `second_shot_bot`

---

Source: `decompiled_scripts/ob_franklin_wine.c`
