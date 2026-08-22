# ob_sofa_franklin.c

Object brains script. 1 anim dicts; 5 models; 5 particle effects.

| | |
|---|---|
| Category | Object brains |
| Total lines | 4,617 |
| Functions | 120 (13 unique, 107 shared) |
| Unique lines | 1,103 (23.9% of file) |

## Assets

**Animation dictionaries** (1) - `safe@franklin@ig_13`

**Animations** (12) - `base`, `tv_enter`, `tv_base`, `tv_exit`, `exit`, `enter`, `tv_idle_a`, `blunt_enter`, `blunt_idle_a`, `blunt_idle_b`, `blunt_interrupt`, `blunt_exit`

**Models and props** (5) - `p_cs_joint_01`, `prop_bong_01`, `prop_mr_raspberry_01`, `p_w_grass_gls_s`, `prop_cs_remote_01`

**Sounds** (2) - `TV_FRANKLINS_HOUSE_SOCEN`, `FRANKLIN_SAFEHOUSE_ACTIVITIES_SCENE`

**Particle effects** (5) - `scr_sh_cig_exhale_nose`, `scr_sh_cig_exhale_mouth`, `scr_sh_lighter_sparks`, `scr_sh_lighter_flame`, `scr_sh_cig_smoke`

**Text labels** (1) - `NULL`

**Stats** (3) - `num_sh_sofa_smoked`, `num_sh_tv_watched`, `num_sh_sofa_used`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (52), `PLAY_SYNCHRONIZED_ENTITY_ANIM` (23), `GET_SYNCHRONIZED_SCENE_PHASE` (22), `TASK_SYNCHRONIZED_SCENE` (21), `CREATE_SYNCHRONIZED_SCENE` (18), `IS_SYNCHRONIZED_SCENE_HOLD_LAST_FRAME` (14), `SET_SYNCHRONIZED_SCENE_HOLD_LAST_FRAME` (14), `HIDE_HUD_AND_RADAR_THIS_FRAME` (11), `DISABLE_CONTROL_ACTION` (11), `CLEAR_HELP` (9), `PLAYER_ID` (9), `IS_AUDIO_SCENE_ACTIVE` (8), `IS_SYNCHRONIZED_SCENE_RUNNING` (8), `START_PARTICLE_FX_NON_LOOPED_ON_PED_BONE` (7), `SET_CAM_PARAMS` (7), `SET_SYNCHRONIZED_SCENE_LOOPED` (6), `IS_CONTROL_JUST_PRESSED` (5), `STOP_AUDIO_SCENE` (4), `START_AUDIO_SCENE` (4), `SET_PLAYER_CONTROL` (4), `SHAKE_CAM` (4), `FIND_ANIM_EVENT_PHASE` (4), `ENABLE_MOVIE_SUBTITLES` (3), `STAT_GET_INT` (3), `STAT_SET_INT` (3), `SET_TV_PLAYER_WATCHING_THIS_FRAME` (3), `REACTIVATE_NAMED_WORLD_BRAINS_WAITING_TILL_OUT_OF_RANGE` (2), `SHUTDOWN_PC_SCRIPTED_CONTROLS` (2), `IS_PLAYER_WANTED_LEVEL_GREATER` (2), `IS_PED_INJURED` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.2f` x5 · `0.45f` x3 · `0.05f` x2 · `0.5f` x2 · `0.25f` x1 · `0.255f` x1 · `0.346f` x1 · `-0.09f` x1 · `0.82f` x1 · `0.876f` x1 · `0.42f` x1 · `0.7f` x1 · `0.48f` x1 · `0.27f` x1 · `0.278f` x1 · `0.6f` x1 · `0.9f` x1 · `0.55f` x1 · `0.95f` x1

## Other strings

Literals whose consuming native was not classified:

`TV_HLP3`, `TV_HLP4`, `TV_HLP0`, `HAND_SHAKE`, `base_remote`, `tv_enter_remote`, `tv_base_remote`, `tv_exit_remote`, `chop`, `WalkInterruptible`, `TV_HLP1`, `TV_HLP2`, `SOFA ACTIVITY`, `tv_idle_a_remote`, `blunt_enter_joint`, `blunt_enter_lighter`, `blunt_idle_a_joint`, `blunt_idle_a_lighter`, `blunt_idle_b_joint`, `blunt_idle_b_lighter`, `blunt_idle_a`, `blunt_idle_b`, `blunt_interrupt_joint`, `blunt_interrupt_lighter`, `blunt_exit_joint`, `blunt_exit_lighter`, `exit`, `exit_drunk`

---

Source: `decompiled_scripts/ob_sofa_franklin.c`
