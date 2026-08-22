# re_securityvan.c

Random events script. 3 developer state labels recovered; 2 anim dicts; 4 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 10,560 |
| Functions | 247 (54 unique, 193 shared) |
| Unique lines | 3,752 (35.5% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`PLAYER HAS PROJECTILE WEAPON` · `PLAYER IS BEHIND VAN` · `PLAYER IS CLOSE TO VAN`

## Assets

**Animation dictionaries** (2) - `random@security_van`, `weapons@holster_1h`

**Animations** (9) - `random@security_van`, `sec_case_into_van_calm`, `weapons@holster_1h`, `holster`, `sec_hand_override`, `sec_case_into_van_panic`, `driver_idle`, `driver_exit_panic`, `driver_exit_calm`

**Models and props** (4) - `s_m_y_cop_01`, `s_f_y_cop_01`, `prop_security_case_01`, `s_m_m_armoured_01`

**Sounds** (2) - `DOORS_BLOWN`, `RE_SECURITY_VAN_SOUNDSET`

**Text labels** (8) - `SECVANGUY1`, `COP`, `NULL`, `RESECAU`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `SECVANGUY2`

**Relationship groups** (1) - `Security_guards`

**Hashed names** (1) - `ENDS_IN_WALK`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (200), `IS_PED_INJURED` (171), `GET_ENTITY_COORDS` (113), `DOES_ENTITY_EXIST` (56), `IS_VEHICLE_DRIVEABLE` (53), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (35), `VDIST` (31), `IS_ENTITY_DEAD` (30), `GET_GAME_TIMER` (28), `IS_EXPLOSION_IN_SPHERE` (24), `VDIST2` (23), `DOES_BLIP_EXIST` (23), `IS_EXPLOSION_IN_AREA` (23), `IS_PED_IN_VEHICLE` (22), `PLAYER_ID` (22), `DOES_PICKUP_EXIST` (22), `IS_VEHICLE_SEAT_FREE` (18), `CLEAR_PED_TASKS` (17), `IS_SYNCHRONIZED_SCENE_RUNNING` (16), `IS_ENTITY_OCCLUDED` (14), `SET_PED_COMBAT_ATTRIBUTES` (14), `IS_PED_ARMED` (13), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (13), `IS_ENTITY_AT_ENTITY` (13), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (13), `IS_ENTITY_ATTACHED_TO_ENTITY` (12), `GET_PICKUP_COORDS` (11), `REMOVE_BLIP` (11), `IS_PED_IN_ANY_VEHICLE` (11), `OPEN_SEQUENCE_TASK` (11)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x12 · `1.5f` x9 · `0.1f` x7 · `0.5f` x6 · `0.75f` x4 · `0.3f` x3 · `1.2195f` x3 · `1.2f` x2 · `0.09f` x2 · `4.5f` x2 · `1.55f` x2 · `-3.44f` x2 · `-13.44f` x2 · `2.3f` x2 · `2.7f` x2 · `-3.25f` x2 · `-2.7f` x2 · `-337.3338f` x1 · `-1460.373f` x1 · `29.5668f` x1 · `-588.4711f` x1 · `-866.9462f` x1 · `25.3292f` x1 · `22.76f` x1

## Other strings

Literals whose consuming native was not classified:

`player`, `stockade`, `move_injured_generic`, `SV_DOORHELP1`, `SV_DOORHELP2`, `sec_idle`, `FIRING_PATTERN_FULL_AUTO`, `van_case_into_van_calm`, `RESEC_WARN`, `sec_case_into_van_calm`, `RE_SV`, `SV_VANHELP1`, `RESEC_COPS`, `SCRIPTED_SCANNER_REPORT_SEC_TRUCK_01`, `SCRIPTED_SCANNER_REPORT_SEC_TRUCK_02`, `SCRIPTED_SCANNER_REPORT_SEC_TRUCK_03`, `sec_walk_calm`, `sec_walk_panic`, `RESEC_SHT1`, `RESEC_SHT2`, `sec_case_into_van_panic`, `RESEC_REC`, `van_case_into_van_panic`, `RESEC_FFLEE`, `RESEC_CAR1`, `RESEC_CAR2`, `RESEC_CAR3`, `RESEC_CAR4`, `RESEC_ATT1`, `RESEC_ENT1`

---

Source: `decompiled_scripts/re_securityvan.c`
