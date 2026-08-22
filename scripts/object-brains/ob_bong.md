# ob_bong.c

Object brains script. 2 anim dicts; 19 models; 4 particle effects.

| | |
|---|---|
| Category | Object brains |
| Total lines | 96,873 |
| Functions | 490 (25 unique, 465 shared) |
| Unique lines | 1,377 (1.4% of file) |

## Assets

**Animation dictionaries** (2) - `move_m@drunk@slightlydrunk`, `mp_safehousebong@`

**Models and props** (19) - `prop_bong_01`, `p_wine_glass_s`, `p_tumbler_02_s1`, `p_tumbler_cs2_s`, `p_tumbler_cs2_s_trev`, `prop_radio_01`, `prop_mr_raspberry_01`, `p_w_grass_gls_s`, `prop_cs_beer_bot_01`, `prop_rolled_sock_02`, `p_cs_joint_01`, `p_cs_lighter_01`, `ig_8_huff_gas_cam`, `ig_7_howcouldisayno_cam`, `ig_7_ifuwanttodothat_cam`, `ig_7_lookatu_cam`, `ig_7_smelllikeasea_cam`, `ig_2_wheatgrassdrink_cam`, `prop_cigar_03`

**Audio banks** (2) - `SAFEHOUSE_FRANKLIN_USE_BONG`, `SAFEHOUSE_MICHAEL_USE_BONG`

**Sounds** (2) - `FRANKLIN_SAFEHOUSE_ACTIVITIES_SCENE`, `MICHAEL_SAFEHOUSE_ACTIVITIES_SCENE`

**Particle effects** (4) - `scr_sh_lighter_flame`, `scr_sh_lighter_sparks`, `scr_sh_bong_smoke`, `inhale`

**Text labels** (1) - `NULL`

**Stats** (1) - `num_sh_bong_smoked`

**Scripts launched** (1) - `family5`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (49), `PLAYER_ID` (15), `DOES_ENTITY_EXIST` (11), `HIDE_HUD_AND_RADAR_THIS_FRAME` (9), `DISABLE_CONTROL_ACTION` (9), `IS_ENTITY_ATTACHED` (8), `FREEZE_ENTITY_POSITION` (8), `PLAY_SYNCHRONIZED_ENTITY_ANIM` (8), `IS_AUDIO_SCENE_ACTIVE` (6), `STOP_AUDIO_SCENE` (6), `CLEAR_HELP` (5), `SET_PLAYER_CONTROL` (5), `IS_SYNCHRONIZED_SCENE_RUNNING` (5), `CREATE_SYNCHRONIZED_SCENE` (4), `TASK_SYNCHRONIZED_SCENE` (4), `GET_SYNCHRONIZED_SCENE_PHASE` (4), `FIND_ANIM_EVENT_PHASE` (4), `GET_ENTITY_HEADING` (4), `IS_PED_INJURED` (3), `IS_ENTITY_DEAD` (3), `RENDER_SCRIPT_CAMS` (3), `CLEAR_PED_TASKS` (3), `NETWORK_IS_GAME_IN_PROGRESS` (2), `HAS_FORCE_CLEANUP_OCCURRED` (2), `GET_ENTITY_MODEL` (2), `GET_CLOSEST_OBJECT_OF_TYPE` (2), `IS_PED_HEADING_TOWARDS_POSITION` (2), `GET_ENTITY_COORDS` (2), `IS_PLAYER_FREE_AIMING` (2), `IS_PLAYER_TARGETTING_ANYTHING` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.2f` x3 · `0.25f` x2 · `0.06f` x2 · `-0.025f` x2 · `0.13f` x2 · `0.95f` x1

## Other strings

Literals whose consuming native was not classified:

`SA_BONG2`, `HAND_SHAKE`, `enter_cap`, `ScriptEvent`, `WalkInterruptible`, `chop`, `bong_lighter`, `lighter_short`, `FAM_WEAPDIS`, `FRANKLIN_SAFEHOUSE_ACTIVITIES_SCENE`, `MICHAEL_SAFEHOUSE_ACTIVITIES_SCENE`, `DEFAULT_ANIMATED_CAMERA`, `idle`, `lighter_exit`, `exit_bottle`, `exit_sober_bot`, `exit_moderately_drunk_bot`, `exit_slightly_drunk_bot`, `exit_drunk_bot`, `drinking_wine_exit_bottle`, `bong_cam`, `short_cam`, `enter_cam`, `enter_bottle`, `enter_bot`, `drinking_wine_bottle`, `bong_FRA`, `exit_FRA`, `bong_bong`, `michael_short`

---

Source: `decompiled_scripts/ob_bong.c`
