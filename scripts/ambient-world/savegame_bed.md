# savegame_bed.c

Ambient world script. 6 anim dicts; 10 models.

| | |
|---|---|
| Category | Ambient world |
| Total lines | 95,662 |
| Functions | 451 (20 unique, 431 shared) |
| Unique lines | 1,331 (1.4% of file) |

## Assets

**Animation dictionaries** (6) - `SAVEM_Default@`, `SAVEBighouse@`, `SAVECountryside@`, `SAVEVeniceB@`, `SAVEF_Default@`, `SAVECouch@`

**Models and props** (10) - `v_michael_g_kitche`, `v_michael_1_wc`, `v_57_bathrm`, `v_57_kitchrm`, `V_TrailerRm`, `V_TrailerToiletRm`, `V_TrailerTIDYRm`, `V_TrailerToiletTIDYRm`, `V_TrailTRASHRm`, `V_TraiToiletTRASHRm`

**Text labels** (1) - `NULL`

**Stats** (3) - `sp0_kills_since_safehouse_visit`, `sp1_kills_since_safehouse_visit`, `sp2_kills_since_safehouse_visit`

**Scripts launched** (1) - `context_controller`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (57), `IS_PED_INJURED` (11), `IS_ENTITY_IN_ANGLED_AREA` (11), `PLAYER_ID` (9), `GET_ENTITY_COORDS` (7), `GET_CAM_VIEW_MODE_FOR_CONTEXT` (7), `GET_CAM_ACTIVE_VIEW_MODE_CONTEXT` (7), `DOES_CAM_EXIST` (6), `CLEAR_PED_BLOOD_DAMAGE_BY_ZONE` (6), `IS_VEHICLE_DRIVEABLE` (5), `SET_CAM_ACTIVE` (5), `RENDER_SCRIPT_CAMS` (5), `GET_DISTANCE_BETWEEN_COORDS` (4), `SET_PLAYER_CONTROL` (4), `SET_ENTITY_PROOFS` (4), `CREATE_SYNCHRONIZED_SCENE` (4), `TASK_SYNCHRONIZED_SCENE` (4), `SETTIMERA` (4), `IS_SYNCHRONIZED_SCENE_RUNNING` (4), `GET_SYNCHRONIZED_SCENE_PHASE` (4), `ADD_TO_CLOCK_TIME` (4), `GET_ENTITY_MODEL` (3), `SET_BIT` (3), `IS_IPL_ACTIVE` (3), `STAT_SET_INT` (3), `DOES_ENTITY_EXIST` (3), `SET_ENTITY_AS_MISSION_ENTITY` (3), `CLEAR_AREA` (3), `SET_SYNCHRONIZED_SCENE_HOLD_LAST_FRAME` (3), `CREATE_CAM` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`7.4375f` x2 · `-816.7371f` x1 · `179.976f` x1 · `75.30324f` x1 · `-814.2743f` x1 · `180.9501f` x1 · `78.54263f` x1 · `0.342038f` x1 · `521.9959f` x1 · `169.4297f` x1 · `-0.790193f` x1 · `524.3142f` x1 · `171.6991f` x1 · `-1150.28f` x1 · `-1513.459f` x1 · `9.321099f` x1 · `-1148.496f` x1 · `-1512.256f` x1 · `11.28705f` x1 · `4.375f` x1 · `-1.5f` x1 · `0.78f` x1

## Other strings

Literals whose consuming native was not classified:

`Alarm_Clocks_Bell`, `DEFAULT_ANIMATED_CAMERA`, `_CAM`, `T_GetOut_countryside`, `SAVE_TRIG`, `SCRIPT\Alarm_Clocks`, `kitchen`, `bedroom`, `TrevorsTrailer`, `TrevorsTrailerTidy`, `TrevorsTrailerTrash`, `rm_lounge`, `rm_bathroom`, `strp3off`, `Alarm_Clocks_Cowbell`, `Alarm_Clocks_Electronic`, `chop`, `M_GetIn_L`, `M_GetOut_L`, `M_GetOut_L_Loop`, `M_GetIn_R`, `M_GetOut_R`, `M_GetOut_R_Loop`, `F_GetIn_R`, `F_GetOut_R`, `F_GetOut_R_Loop`, `F_GetIn_l_bighouse`, `F_GetOut_l_bighouse`, `F_GetOut_l_Loop_bighouse`, `F_GetIn_r_bighouse`

---

Source: `decompiled_scripts/savegame_bed.c`
