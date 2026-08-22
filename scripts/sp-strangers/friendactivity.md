# friendactivity.c

SP strangers and freaks script. 7 anim dicts; 2 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 123,468 |
| Functions | 1,081 (311 unique, 770 shared) |
| Unique lines | 16,568 (13.4% of file) |

## Assets

**Animation dictionaries** (7) - `random@arrests`, `friends@frm@ig_1`, `friends@frf@ig_1`, `friends@frt@ig_1`, `friends@frl@ig_1`, `friends@frj@ig_1`, `friends@fra@ig_1`

**Animations** (3) - `random@arrests`, `idle_2_hands_up`, `kneeling_arrest_idle`

**Models and props** (2) - `p_amb_phone_01`, `s_m_m_autoshop_02`

**Audio banks** (1) - `TIME_LAPSE`

**Sounds** (2) - `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Speech contexts** (2) - `SHOOT`, `KILLED_ALL`

**Text labels** (16) - `NULL`, `FRIENDS`, `BAD`, `DRUNK`, `P3RSEUS`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `LAMAR`, `JIMMY`, `AMANDA`, `ANAUD`, `KRYST4L`, `07KZF345`, `N4M4ST3`, `81TDS937`

**Decorators** (1) - `BlockFriendGrab`

**Relationship groups** (1) - `player`

**Scripts launched** (2) - `friends_controller`, `launcher_tennis`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (315), `IS_PED_INJURED` (138), `IS_PED_IN_ANY_VEHICLE` (65), `DOES_ENTITY_EXIST` (64), `CLEAR_PED_TASKS` (55), `GET_VEHICLE_PED_IS_IN` (50), `GET_ENTITY_COORDS` (39), `SET_BIT` (32), `GET_GAME_TIMER` (31), `IS_PED_GROUP_MEMBER` (28), `IS_VEHICLE_DRIVEABLE` (26), `SET_PED_CONFIG_FLAG` (22), `IS_PED_IN_VEHICLE` (22), `SET_PED_COMBAT_ATTRIBUTES` (22), `GET_RANDOM_INT_IN_RANGE` (21), `TIMERA` (20), `PLAYER_ID` (19), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (19), `SET_ENTITY_COORDS` (19), `DOES_CAM_EXIST` (19), `DOES_BLIP_EXIST` (18), `REMOVE_PED_FROM_GROUP` (18), `TASK_LEAVE_ANY_VEHICLE` (16), `TASK_FOLLOW_NAV_MESH_TO_COORD` (16), `IS_ENTITY_AT_COORD` (16), `DESTROY_CAM` (15), `SET_CAM_FOV` (15), `OPEN_SEQUENCE_TASK` (14), `CLOSE_SEQUENCE_TASK` (14), `TASK_PERFORM_SEQUENCE` (14)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x18 · `0.5f` x17 · `1.5f` x5 · `12.5f` x4 · `-1.5f` x2 · `-2145.486f` x1 · `3018.294f` x1 · `31.81f` x1 · `397.2f` x1 · `-716.2f` x1 · `29.9f` x1 · `-9.3f` x1 · `-1411.5f` x1 · `-200.6f` x1 · `47.8f` x1 · `-3.8f` x1 · `19.7f` x1 · `298.9f` x1 · `200.8f` x1 · `-7.6f` x1 · `161.6f` x1 · `121.9946f` x1 · `-1292.546f` x1 · `29.2792f` x1

## Other strings

Literals whose consuming native was not classified:

`FaFM_CAAA`, `DEFAULT_SCRIPTED_CAMERA`, `sanchez`, `issi2`, `speedo`, `asea`, `FR_HV_HORN`, `FR_H_WAIT`, `FR_GETBACK`, `impatient_idle_a`, `impatient_idle_b`, `tribike`, `sentinel2`, `asterope`, `FR_H_PKUP`, `FR_H_DROPOFF0`, `FR_H_DROPOFF1`, `FR_H_DROPOFF2`, `FR_GETBACK2`, `FR_H_ACTIV1`, `FR_H_ACTIV2`, `FR_H_BUD_SW`, `HAND_SHAKE`, `Cin`, `Glf`, `Str`, `Tns`, `Drt`

---

Source: `decompiled_scripts/friendactivity.c`
