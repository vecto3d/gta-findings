# am_armwrestling.c

Minigames script. 1 anim dicts; 2 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 137,128 |
| Functions | 1,523 (93 unique, 1,430 shared) |
| Unique lines | 5,311 (3.9% of file) |

## Assets

**Animation dictionaries** (1) - `mini@arm_wrestling`

**Animations** (16) - `mini@arm_wrestling`, `stand_idle_a_face`, `stand_idle_b_face`, `idle`, `nuetral_idle_a_face`, `nuetral_idle_b_face`, `idle_to_nuetral_a_face`, `idle_to_nuetral_b_face`, `expression_idle_a_face`, `expression_idle_b_face`, `win_a_ped_a_face`, `win_b_ped_a_face`, `win_b_ped_b_face`, `win_a_ped_b_face`, `move_m@generic`, `move_f@generic`

**Models and props** (2) - `prop_arm_wrestle_01`, `proair_hoc_puck`

**Audio banks** (1) - `HUD_AWARDS`

**Sounds** (13) - `MP_CELEB_SCREEN_SCENE`, `HUD_MINI_GAME_SOUNDSET`, `3_2_1_NON_RACE`, `ARM_WRESTLING_ARM_IMPACT_MASTER`, `LOSER`, `HUD_AWARDS`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `ARM_WRESTLING_WOOD_CREEK_MASTER`, `ARM_WRESTLING_WHOOSH_MASTER`, `ArmWrestlingIntensity`, `WIN`, `GO_NON_RACE`

**Text labels** (3) - `SUMMARY`, `NULL`, `WINNER`

**Decorators** (1) - `MPBitset`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (142), `GET_GAME_TIMER` (53), `PLAYER_ID` (48), `IS_TASK_MOVE_NETWORK_ACTIVE` (45), `SET_CAM_FOV` (41), `CREATE_CAMERA_WITH_PARAMS` (40), `ATTACH_CAM_TO_ENTITY` (36), `ARE_STRINGS_EQUAL` (32), `GET_TASK_MOVE_NETWORK_STATE` (32), `POINT_CAM_AT_ENTITY` (32), `IS_PED_INJURED` (30), `CLEAR_HELP` (23), `IS_ENTITY_DEAD` (21), `DOES_ENTITY_EXIST` (20), `NETWORK_GET_PLAYER_INDEX` (19), `RENDER_SCRIPT_CAMS` (19), `INT_TO_PARTICIPANTINDEX` (18), `IS_TASK_MOVE_NETWORK_READY_FOR_TRANSITION` (16), `REQUEST_TASK_MOVE_NETWORK_STATE_TRANSITION` (16), `SET_TASK_MOVE_NETWORK_SIGNAL_FLOAT` (16), `TASK_PLAY_ANIM` (16), `TO_FLOAT` (14), `DOES_CAM_EXIST` (12), `GET_TASK_MOVE_NETWORK_EVENT` (10), `PLAY_SOUND_FRONTEND` (9), `SET_BIT` (9), `IS_PAUSE_MENU_ACTIVE` (9), `_SEND_TU_SCRIPT_EVENT_NEW` (8), `POINT_CAM_AT_PED_BONE` (8), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`30.5f` x16 · `0.0094f` x10 · `0.5f` x8 · `-0.8117f` x6 · `-0.124f` x6 · `0.717f` x6 · `1.5073f` x4 · `1.6429f` x4 · `1.0567f` x4 · `1.3191f` x4 · `22.6468f` x4 · `-1.6043f` x4 · `0.7408f` x4 · `0.3602f` x4 · `1.2691f` x4 · `0.37f` x4 · `28.9663f` x4 · `0.245f` x3 · `1.195f` x3 · `0.533f` x2 · `3.75f` x2 · `0.25f` x2 · `0.05f` x2 · `0.3f` x2

## Other strings

Literals whose consuming native was not classified:

`Approach`, `Running`, `Phase`, `Win`, `Loss`, `WinFinished`, `LossFinished`, `ARMMP_END_QT`, `mpply_armwrestling_total_wins`, `ARMMP_WAIT_RM`, `Wobble`, `ARMMP_TERM_LEFT`, `Walk`, `aw_ig_intro_cam`, `AltWalk`, `aw_ig_intro_alt1_cam`, `DEFAULT_ANIMATED_CAMERA`, `SMALL_EXPLOSION_SHAKE`, `mpply_armwrestling_total_match`, `ARMMP_SC_WIN`, `MP_Celeb_Preload_Fade`, `DeathFailMPIn`, `MinigameEndNeutral`, `ARMMP_WRESTLE`, `ref_intro`, `arm_wrestling_sweep_paired_a_rev3`, `arm_wrestling_sweep_paired_b_rev3`, `ARMMP_WAIT_RD`, `ARMMP_HOW_TO_12`, `ARMMP_HOW_TO_2`

---

Source: `decompiled_scripts/am_armwrestling.c`
