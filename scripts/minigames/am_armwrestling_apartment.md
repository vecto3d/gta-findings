# am_armwrestling_apartment.c

Minigames script. 2 anim dicts; 2 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 71,738 |
| Functions | 944 (99 unique, 845 shared) |
| Unique lines | 4,657 (6.5% of file) |

## Assets

**Animation dictionaries** (2) - `anim@amb@clubhouse@mini@arm_wrestling@`, `mini@arm_wrestling`

**Animations** (4) - `mini@arm_wrestling`, `anim@amb@clubhouse@mini@arm_wrestling@`, `cancel_neutral_ped_a`, `cancel_neutral_ped_b`

**Models and props** (2) - `prop_arm_wrestle_01`, `proair_hoc_puck`

**Sounds** (12) - `MP_CELEB_SCREEN_SCENE`, `HUD_MINI_GAME_SOUNDSET`, `3_2_1_NON_RACE`, `ARM_WRESTLING_WOOD_CREEK_MASTER`, `ARM_WRESTLING_ARM_IMPACT_MASTER`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `ArmWrestlingIntensity`, `WIN`, `LOSER`, `HUD_AWARDS`, `GO_NON_RACE`

**Text labels** (4) - `SUMMARY`, `UNKNOWN`, `NULL`, `WINNER`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (85), `GET_GAME_TIMER` (60), `ARE_STRINGS_EQUAL` (39), `GET_TASK_MOVE_NETWORK_STATE` (39), `PLAYER_ID` (36), `IS_TASK_MOVE_NETWORK_ACTIVE` (32), `PARTICIPANT_ID_TO_INT` (32), `INT_TO_PARTICIPANTINDEX` (23), `DOES_CAM_EXIST` (20), `NETWORK_GET_PLAYER_INDEX` (20), `CLEAR_HELP` (16), `SET_TASK_MOVE_NETWORK_SIGNAL_FLOAT` (15), `SET_BIT` (15), `IS_PED_INJURED` (14), `DOES_ENTITY_EXIST` (13), `IS_TASK_MOVE_NETWORK_READY_FOR_TRANSITION` (13), `REQUEST_TASK_MOVE_NETWORK_STATE_TRANSITION` (13), `GET_TASK_MOVE_NETWORK_EVENT` (12), `TO_FLOAT` (12), `IS_ENTITY_DEAD` (11), `CLEAR_BIT` (11), `_SEND_TU_SCRIPT_EVENT_NEW` (10), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (9), `IS_PAUSE_MENU_ACTIVE` (9), `GET_PLAYER_PED` (8), `RENDER_SCRIPT_CAMS` (8), `TASK_PLAY_ANIM` (8), `CREATE_CAMERA_WITH_PARAMS` (7), `SET_CAM_FOV` (7), `PLAY_SOUND_FRONTEND` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x9 · `0.0094f` x4 · `-0.8117f` x2 · `-0.124f` x2 · `0.717f` x2 · `1.0567f` x2 · `1.3191f` x2 · `0.2f` x2 · `0.533f` x2 · `1.5073f` x1 · `1.6429f` x1 · `-1.2622f` x1 · `-0.4479f` x1 · `1.4163f` x1 · `1.8001f` x1 · `0.3026f` x1 · `-0.1936f` x1 · `-0.7299f` x1 · `0.3842f` x1 · `22.6468f` x1 · `0.05f` x1 · `0.4f` x1 · `3.75f` x1 · `0.25f` x1

## Other strings

Literals whose consuming native was not classified:

`Running`, `Phase`, `Win`, `Loss`, `StandIdle`, `WinFinished`, `LossFinished`, `Wobble`, `Intro`, `mpply_armwrestling_total_wins`, `ARMMP_END_QT`, `CancelNeutral`, `ARMMP_TERM_LEFT`, `ARMMP_WAIT_RM`, `mpply_armwrestling_total_match`, `ARMMP_TUT_1`, `ARMMP_SC_WIN`, `MP_Celeb_Preload_Fade`, `DeathFailMPIn`, `MinigameEndNeutral`, `ARMMP_WRESTLE`, `proair_hoc_puck`, `ARM_MP`, `ARM_WRESTLING_CROWD_MASTER`, `ref_intro`, `arm_wrestling_sweep_paired_a_rev4`, `arm_wrestling_sweep_paired_b_rev4`, `aw_ig_intro_alt1_cam`, `DEFAULT_ANIMATED_CAMERA`, `ARMMP_HOW_TO_12`

---

Source: `decompiled_scripts/am_armwrestling_apartment.c`
