# ob_sofa_michael.c

Object brains script. 1 anim dicts; 2 models; 5 particle effects.

| | |
|---|---|
| Category | Object brains |
| Total lines | 4,271 |
| Functions | 91 (14 unique, 77 shared) |
| Unique lines | 1,091 (25.5% of file) |

## Assets

**Animation dictionaries** (1) - `safe@michael@ig_3`

**Animations** (13) - `base_michael`, `tv_enter_michael`, `tv_base_michael`, `tv_exit_michael`, `tv_base_remote`, `enter_michael`, `tv_idle_a_michael`, `cigar_enter_michael`, `cigar_idle_a_michael`, `cigar_idle_b_michael`, `cigar_interrupt_michael`, `cigar_exit_michael`, `exit_michael`

**Models and props** (2) - `prop_cigar_03`, `prop_cs_remote_01`

**Sounds** (2) - `TV_MICHAELS_HOUSE`, `MICHAEL_SAFEHOUSE_ACTIVITIES_SCENE`

**Particle effects** (5) - `scr_sh_cig_exhale_mouth`, `scr_sh_cig_exhale_nose`, `scr_sh_lighter_sparks`, `scr_sh_lighter_flame`, `scr_sh_cig_smoke`

**Text labels** (1) - `NULL`

**Stats** (2) - `num_sh_sofa_used`, `num_sh_sofa_smoked`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (47), `PLAY_SYNCHRONIZED_ENTITY_ANIM` (24), `GET_SYNCHRONIZED_SCENE_PHASE` (21), `TASK_SYNCHRONIZED_SCENE` (20), `CREATE_SYNCHRONIZED_SCENE` (17), `DOES_CAM_EXIST` (12), `IS_SYNCHRONIZED_SCENE_HOLD_LAST_FRAME` (12), `SET_SYNCHRONIZED_SCENE_HOLD_LAST_FRAME` (12), `HIDE_HUD_AND_RADAR_THIS_FRAME` (10), `DISABLE_CONTROL_ACTION` (10), `IS_AUDIO_SCENE_ACTIVE` (9), `CLEAR_HELP` (8), `SET_CAM_ACTIVE` (8), `IS_SYNCHRONIZED_SCENE_RUNNING` (8), `START_PARTICLE_FX_NON_LOOPED_ON_PED_BONE` (8), `PLAYER_ID` (7), `GET_FOLLOW_PED_CAM_VIEW_MODE` (7), `SET_CAM_PARAMS` (6), `SET_SYNCHRONIZED_SCENE_LOOPED` (6), `ENABLE_MOVIE_SUBTITLES` (5), `STOP_AUDIO_SCENE` (5), `IS_CAM_ACTIVE` (4), `SHAKE_CAM` (4), `SET_TV_PLAYER_WATCHING_THIS_FRAME` (4), `START_AUDIO_SCENE` (4), `IS_CONTROL_JUST_PRESSED` (4), `SET_PLAYER_CLOTH_PACKAGE_INDEX` (3), `SET_PLAYER_CONTROL` (3), `ALLOW_ALTERNATIVE_SCRIPT_CONTROLS_LAYOUT` (3), `STAT_GET_INT` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.2f` x4 · `0.5f` x4 · `0.01f` x4 · `0.8f` x3 · `0.05f` x2 · `0.95f` x2 · `-804.05f` x1 · `173.54f` x1 · `72.17f` x1 · `1.02f` x1 · `-52.4f` x1 · `0.163f` x1 · `-804.5928f` x1 · `173.1801f` x1 · `71.68436f` x1 · `0.590625f` x1 · `0.7f` x1 · `0.27f` x1 · `0.275f` x1 · `0.45f` x1 · `0.346f` x1 · `0.35f` x1

## Other strings

Literals whose consuming native was not classified:

`TV_HLP4`, `TV_HLP3`, `base_remote`, `tv_base_remote`, `TV_HLP0`, `HAND_SHAKE`, `tv_enter_remote`, `tv_exit_remote`, `TV_HLP1`, `TV_HLP2`, `FAM_WEAPDIS`, `SOFA ACTIVITY`, `tv_idle_a_remote`, `cigar_enter_cigar`, `cigar_enter_lighter`, `cigar_idle_a_cigar`, `cigar_idle_a_lighter`, `cigar_idle_b_cigar`, `cigar_idle_b_lighter`, `cigar_idle_a_michael`, `cigar_idle_b_michael`, `cigar_interrupt_cigar`, `cigar_interrupt_lighter`, `cigar_exit_cigar`, `cigar_exit_lighter`, `exit_michael`, `WalkInterruptible`

---

Source: `decompiled_scripts/ob_sofa_michael.c`
