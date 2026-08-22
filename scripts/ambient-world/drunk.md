# drunk.c

Ambient world script. 13 anim dicts.

| | |
|---|---|
| Category | Ambient world |
| Total lines | 5,666 |
| Functions | 187 (47 unique, 140 shared) |
| Unique lines | 2,534 (44.7% of file) |

## Assets

**Animation dictionaries** (13) - `SAVECountryside@`, `MOVE_M@DRUNK@TRANSITIONS`, `FACIALS@GEN_MALE@BASE`, `FACIALS@GEN_FEMALE@BASE`, `SAVEM_Default@`, `SWITCH@FRANKLIN@BED`, `SAVEBighouse@`, `SAVEVeniceB@`, `SAVECouch@`, `move_ped_strafing_firstperson@drunk`, `FACIALS@P_M_ZERO@BASE`, `FACIALS@P_M_ONE@BASE`, `FACIALS@P_M_TWO@BASE`

**Speech contexts** (4) - `AMANDA_DRUNK`, `LAMAR_DRUNK`, `AMANDA_NORMAL`, `LAMAR_NORMAL`

**Text labels** (5) - `NULL`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `PRSAUD`

**Stats** (3) - `sp0_sp_num_times_drunk`, `sp1_sp_num_times_drunk`, `sp2_sp_num_times_drunk`

**Scripts launched** (1) - `appemail`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (65), `TIMERA` (26), `PLAYER_ID` (24), `IS_STRING_NULL_OR_EMPTY` (18), `IS_ENTITY_DEAD` (16), `WAIT` (14), `NETWORK_IS_GAME_IN_PROGRESS` (13), `APPLY_PED_DAMAGE_PACK` (10), `IS_PED_IN_ANY_VEHICLE` (10), `IS_PED_INJURED` (7), `GET_VEHICLE_PED_IS_IN` (7), `DOES_ENTITY_EXIST` (6), `CLEAR_AREA` (6), `SET_PED_RESET_FLAG` (6), `SETTIMERA` (5), `IS_SCREEN_FADED_OUT` (5), `SET_GAME_PAUSED` (5), `REQUEST_ANIM_DICT` (5), `GET_FOLLOW_PED_CAM_VIEW_MODE` (5), `GET_DISTANCE_BETWEEN_COORDS` (5), `REMOVE_ANIM_DICT` (5), `GET_SCRIPT_TASK_STATUS` (5), `GET_ENTITY_COORDS` (5), `IS_PED_SITTING_IN_ANY_VEHICLE` (5), `GET_PED_IN_VEHICLE_SEAT` (5), `DO_SCREEN_FADE_OUT` (4), `SET_ENTITY_COORDS` (4), `GET_GAME_TIMER` (4), `SET_GAMEPLAY_CAM_RELATIVE_PITCH` (4), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-1.5f` x4 · `1.5f` x1 · `0.75f` x1 · `0.25f` x1

## Other strings

Literals whose consuming native was not classified:

`MotionState_Idle`, `POST_STONED`, `MotionState_Walk`, `DWC_MICHAEL_mansion`, `M_GetOut_R`, `M_GetOut_R_CAM`, `DWC_MICHAEL_trailer`, `M_GetOut_countryside`, `M_GetOut_countryside_CAM`, `DWC_FRANKLIN_city`, `Sleep_GetUp_RubEyes`, `Sleep_GetUp_RubEyes_CAM`, `DWC_FRANKLIN_hills`, `F_GetOut_r_bighouse`, `F_GetOut_r_bighouse_CAM`, `DWC_TREVOR_trailer`, `T_GetOut_countryside`, `T_GetOut_countryside_CAM`, `DWC_TREVOR_beach`, `T_GetOut_r_veniceB`, `T_GetOut_r_veniceB_CAM`, `DWC_TREVOR_stripclub`, `T_GetOut_couch`, `T_GetOut_couch_CAM`, `DEFAULT_ANIMATED_CAMERA`, `WalkInterruptible`, `ForceBlendout`, `HOSPITAL_0`, `HOSPITAL_1`, `HOSPITAL_2`

---

Source: `decompiled_scripts/drunk.c`
