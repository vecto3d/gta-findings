# exile2.c

SP missions script. 12 anim dicts; 6 models; 5 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 143,986 |
| Functions | 1,163 (195 unique, 968 shared) |
| Unique lines | 18,491 (12.8% of file) |

## Assets

**Animation dictionaries** (12) - `missexile2`, `CREATURES@ROTTWEILER@MELEE@STREAMED_TAUNTS@`, `missexile2ig_5`, `missexile2deer_crash`, `CREATURES@ROTTWEILER@MELEE@STREAMED_CORE@`, `missswitch`, `missexile2switch`, `move_ped_crouched`, `Wpn_AssaultRifle_WeaponHoldingCrouched`, `move_ped_crouched_strafing`, `missfra0_chop_find`, `shake_cam_all@`

**Animations** (44) - `missexile2`, `CREATURES@ROTTWEILER@MELEE@STREAMED_CORE@`, `attack`, `CREATURES@ROTTWEILER@MELEE@STREAMED_TAUNTS@`, `taunt_01`, `fra_0_ig_1_chop_growl`, `missexile2switch`, `fra0_ig_12_chop_waiting_a`, `chop_swim_across`, `ig_4_switch_trev_to_franklin_fra`, `Chop_Sit_In_Frogger_RDS`, `chop_sit_in_baller_ps`, `missexile2ig_5`, `missswitch`, `fra0_ig_14_chop_sniff_fwds`, `chop_get_in_frogger_rds`, `BARK_SEQ`, `bark`, `enter_crouch_a`, `crouching_idle_a`, `FranklinWaveToHelicopter`, `getout_car_stumble_bryce`, `getout_car_stumble_jeff`, `getout_car_stumble_andre`, `missexile2deer_crash`, `deer_crash`, `IG_3_SWITCH_TREV_to_FRA_AND_ONEILLS_TREV`, `in_car_driver`, `in_car_passenger`, `in_car_backseater`, `IG_3_SWITCH_TREV_to_FRA_AND_ONEILLS_MIC`, `take_down_bad_guy_chop`, `CHOP_SNIFF_SEQ`, `CHOP_WHINE`, `CHOP_LICKS_MOUTH`, `CHOP_PANT`, `GROWL`, `SNARL`, `ex02_heli_sniper_idle_michael`, `ex02_heli_switch_chop_run_franklin`, `ex02_heli_switch_chop_run_chop`, `take_down_bad_guy_victim`, `enter_crouch_b`, `crouching_idle_b`

**Models and props** (6) - `a_c_deer`, `a_m_m_hillbilly_02`, `radi`, `sabregt`, `A_M_M_HillBilly_01_WHITE_MINI_02`, `ig_orleans`

**Audio banks** (7) - `EXILE_2_01`, `CHOP_CAM_A_01`, `CHOP_CAM_A_02`, `CHOP_CAM_B_01`, `CHOP_CAM_B_02`, `CHOP_CAM_C_01`, `CHOP_CAM_C_02`

**Sounds** (28) - `EXILE_2_SNIPE_STAGE_THERMAL`, `EXILE_2_SOUNDS`, `EXILE_2_KILL_ENEMY_FRANKLIN`, `EXILE_2_KILL_ENEMY_MICHAEL`, `EXILE_2_KILL_ENEMY_CHOP`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `EXILE_2_FOCUS_CAM`, `Hit_Out`, `EXILE_2_FOLLOW_CAR`, `EXILE_2_FOLLOW_CAR_PHONE`, `EXILE_2_HELI_PICK_UP`, `EXILE_2_SNIPE_STAGE`, `Fire_Missile_Loop`, `EXILE_2_RPG_CUTSCENE`, `EXILE_2_FLY_HELI`, `EXILE_2_HELI_IN_POSITION_CUTSCENE`, `EXILE_2_GO_TO_CRASH_SITE`, `EXILE_2_GO_TO_HELI`, `EXILE_2_CRASH_CUTSCENE`, `Fire_RPG_On_Foot`, `Short_Transition_In`, `Fire_RPG`, `Missile_Warning_Sound`, `EXILE_2_GANG_CAR_FIRE`, `1st_Person_Transition`, `CHOP_CAM_A`, `CHOP_CAM_B`, `CHOP_CAM_C`

**Particle effects** (5) - `scr_ex2_rpg_trail`, `scr_ex2_jeep_engine_fire`, `scr_ex2_car_impact`, `scr_ex2_car_slide`, `scr_ex2_chop_trail`

**Text labels** (7) - `TM44AUD`, `FS_help_1`, `FS_GOD2b`, `22LJK483`, `NULL`, `FS_GOD_3`, `FORSNIP`

**Waypoint recordings** (4) - `exile2_0`, `exile2_2`, `exile2_3`, `exile2_1`

**Vehicle recordings** (3) - `lkexcile2_chase`, `lkexile2`, `lkexcile2`

**Relationship groups** (3) - `players group`, `enemy group`, `animal_group`

**Timecycle modifiers** (1) - `chop`

**Interiors and entity sets** (2) - `ch1_roadsdint_tun2`, `ch1_roadsdint_tun1`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (503), `GET_ENTITY_COORDS` (261), `HAS_MODEL_LOADED` (115), `IS_ENTITY_AT_COORD` (113), `REQUEST_MODEL` (111), `DOES_ENTITY_EXIST` (108), `IS_PED_INJURED` (106), `HAS_VEHICLE_RECORDING_BEEN_LOADED` (103), `CLEAR_SEQUENCE_TASK` (95), `OPEN_SEQUENCE_TASK` (95), `CLOSE_SEQUENCE_TASK` (95), `TASK_PERFORM_SEQUENCE` (91), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (79), `REQUEST_VEHICLE_RECORDING` (78), `GET_DISTANCE_BETWEEN_COORDS` (77), `GET_GAME_TIMER` (74), `IS_VEHICLE_DRIVEABLE` (71), `REMOVE_VEHICLE_RECORDING` (69), `TASK_FOLLOW_NAV_MESH_TO_COORD` (64), `PLAYER_ID` (62), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (54), `TASK_TURN_PED_TO_FACE_ENTITY` (52), `SET_MODEL_AS_NO_LONGER_NEEDED` (51), `DOES_BLIP_EXIST` (45), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (43), `TASK_PLAY_ANIM` (43), `SET_ENTITY_PROOFS` (42), `REMOVE_BLIP` (42), `ABSF` (41), `IS_PLAYER_SWITCH_IN_PROGRESS` (40)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x95 · `2.5f` x78 · `1.5f` x49 · `0.25f` x48 · `1.8f` x48 · `0.1f` x44 · `0.2f` x27 · `-0.1f` x17 · `0.3f` x15 · `0.01f` x12 · `-1878.672f` x9 · `4479.327f` x9 · `25.4878f` x9 · `-1541.694f` x9 · `4476.719f` x9 · `17.715f` x9 · `-1683.497f` x8 · `4454.595f` x8 · `1.566f` x8 · `0.15f` x8 · `-0.2f` x8 · `40.5f` x8 · `-1542.6f` x8 · `4480.2f` x8

## Other strings

Literals whose consuming native was not classified:

`TM44_chop4`, `michael`, `trevor`, `missexile2`, `sabregt`, `chop_get_in_frogger_rds`, `move_ped_crouched_strafing`, `move_ped_crouched`, `radi`, `DEFAULT_SCRIPTED_CAMERA`, `franklin`, `TM44_chop2`, `player`, `FS_FAIL_0`, `FS_TREVDEAD`, `FS_HELIDEAD`, `FS_MICHDEAD`, `FS_FRANDEAD`, `FS_CHOP_DEAD`, `TM44_TWT`, `ROAD_VIBRATION_SHAKE`, `Wpn_AssaultRifle_WeaponHoldingCrouched`, `CAR_CRASH_OFF_CLIFF_STREAM`, `EXILE_2_SOUNDS`, `FS_FAIL_10`, `TM44_WATER`, `TM44_DWATER`, `TM44_GWOOD`, `TM44_DEADR`, `oneil`

---

Source: `decompiled_scripts/exile2.c`
