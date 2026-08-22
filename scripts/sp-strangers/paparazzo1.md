# paparazzo1.c

SP strangers and freaks script. 3 anim dicts; 9 models; 1 particle effects.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 59,750 |
| Functions | 696 (130 unique, 566 shared) |
| Unique lines | 10,789 (18.1% of file) |

## Assets

**Animation dictionaries** (3) - `rcmpaparazzo1ig_4`, `clipset@rcmpaparazzo1ig_1_ds`, `clipset@rcmpaparazzo1ig_1_ps`

**Animations** (16) - `idle`, `cam_pos_hand_override`, `dialog_pap`, `gesture_behind_left_pap`, `gesture_behind_right_pap`, `hurry_up_left_pap`, `hurry_up_right_pap`, `rcmpaparazzo1ig_4`, `miranda_shooting_up`, `lookatcam_intro_pap`, `lookatcam_outro_pap`, `lookatcam_loop_pap`, `pap_idle_action_01`, `pap_idle_action_02`, `pap_idle_01`, `pap_idle_02`

**Models and props** (9) - `prop_traffic_01a`, `prop_pap_camera_01`, `prop_flash_unit`, `a_m_m_bevhills_02`, `u_f_m_miranda`, `s_m_m_highsec_01`, `u_m_y_paparazzi`, `u_m_m_rivalpap`, `prop_syringe_01`

**Audio banks** (1) - `PAPARAZZO_01_A`

**Sounds** (4) - `PAPARAZZO_01_CHASE`, `PAPARAZZO_01_INTRO`, `CAMERA`, `SWING`

**Particle effects** (1) - `scr_rcpap1_camera`

**Text labels** (10) - `NULL`, `PAP1AUD`, `OFF`, `PAP1_09`, `PAP1_05`, `PAP1_03`, `BEVERLY`, `FRANKLIN`, `PAP1`, `PAP2AUD`

**Scenarios** (1) - `ATTRACT_PAP`

**Vehicle recordings** (3) - `Pap1PV`, `Pap1RP`, `pap1RP`

**Relationship groups** (2) - `rgh_traffic`, `ENEMIES`

**Vehicle mods** (4) - `bus`, `coach`, `mule`, `mule2`

**Stats** (1) - `sp1_special_ability`

**Hashed names** (1) - `HELDDOWN`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (218), `GET_GAME_TIMER` (109), `IS_ENTITY_PLAYING_ANIM` (90), `GET_ENTITY_COORDS` (69), `DOES_ENTITY_EXIST` (67), `TASK_PLAY_ANIM` (53), `PLAYER_ID` (43), `IS_PED_SITTING_IN_VEHICLE` (38), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (36), `SET_MODEL_AS_NO_LONGER_NEEDED` (35), `IS_PED_SITTING_IN_ANY_VEHICLE` (31), `GET_RANDOM_INT_IN_RANGE` (29), `REQUEST_MODEL` (27), `STOP_PLAYBACK_RECORDED_VEHICLE` (25), `IS_VEHICLE_DRIVEABLE` (25), `HAS_MODEL_LOADED` (25), `REMOVE_VEHICLE_RECORDING` (21), `STOP_ANIM_TASK` (21), `IS_PED_RAGDOLL` (19), `TASK_LOOK_AT_ENTITY` (19), `WAIT` (18), `SET_PED_CONFIG_FLAG` (18), `HAS_ENTITY_ANIM_FINISHED` (18), `ABSF` (17), `SET_PED_FLEE_ATTRIBUTES` (16), `TASK_CLEAR_LOOK_AT` (15), `SET_PED_KEEP_TASK` (15), `IS_PED_HEADTRACKING_PED` (15), `IS_PED_GETTING_INTO_A_VEHICLE` (15), `SET_PLAYBACK_SPEED` (14)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.93f` x17 · `0.25f` x11 · `0.6f` x9 · `0.5f` x9 · `1.25f` x6 · `0.7f` x6 · `2.5f` x6 · `0.21f` x3 · `1.5f` x3 · `0.3f` x3 · `6.5f` x3 · `1.2f` x3 · `0.2f` x3 · `-162.4299f` x3 · `279.9136f` x3 · `92.71819f` x3 · `-190.0199f` x3 · `260.1082f` x3 · `-131.572f` x3 · `285.8091f` x3 · `-116.8204f` x3 · `261.0066f` x3 · `101.0282f` x3 · `-206.292f` x3

## Other strings

Literals whose consuming native was not classified:

`rapidgt2`, `jackal`, `rocoto`, `PAP1_CRASH`, `tornado`, `f620`, `waive_comeback_f`, `PAP1_PPW1`, `sweep_low`, `sweep_med`, `sweep_high`, `ninef2`, `buffalo`, `PAP1_IG5`, `PAP1_H1`, `PAP1_HITPED`, `PAP1_PUNCH`, `baller`, `serrano`, `player`, `pcj`, `polmav`, `PAP1_RIVAL`, `AllowScoreAndRadio`, `PAP1_09`, `Paparazzo1RivalPap`, `PAP1_03`, `PAP1_H2_KM`, `PAP1_H2`, `PAP1_05`

---

Source: `decompiled_scripts/paparazzo1.c`
