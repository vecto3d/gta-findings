# re_rescuehostage.c

Random events script. 1 anim dicts; 6 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 6,419 |
| Functions | 173 (24 unique, 149 shared) |
| Unique lines | 1,341 (20.9% of file) |

## Assets

**Animation dictionaries** (1) - `RANDOM@RESCUE_HOSTAGE`

**Animations** (10) - `girl_villian_shot`, `bystander_bystander_angry`, `bystander_villian_shot`, `bystander_helping_girl_loop`, `girl_helping_girl_loop`, `girl_girl_shot`, `villian_girl_shot`, `villian_struggle_loop`, `girl_struggle_loop`, `bystander_taking_cover`

**Models and props** (6) - `s_f_y_cop_01`, `s_m_y_cop_01`, `a_m_m_hillbilly_02`, `a_m_m_business_01`, `a_f_m_tourist_01`, `A_F_M_BEVHILLS_02_WHITE_FULL_02`

**Text labels** (6) - `RERHOAU`, `NULL`, `WHIMPER`, `MICHAEL`, `FRANKLIN`, `TREVOR`

**Relationship groups** (2) - `re_rescuehostage relManager`, `re_rescuehostage relBadGuy`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (60), `IS_PED_INJURED` (44), `SET_PED_KEEP_TASK` (18), `PLAYER_ID` (17), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (13), `SET_PED_CAN_RAGDOLL` (10), `SET_ENTITY_HEALTH` (10), `GET_ENTITY_COORDS` (10), `GET_GAME_TIMER` (9), `TASK_SMART_FLEE_COORD` (9), `SET_PED_AS_NO_LONGER_NEEDED` (9), `TASK_SYNCHRONIZED_SCENE` (9), `GET_ENTITY_MODEL` (9), `GET_VEHICLE_PED_IS_IN` (9), `GET_SYNCHRONIZED_SCENE_PHASE` (7), `SET_RELATIONSHIP_BETWEEN_GROUPS` (7), `SET_PED_COMBAT_ATTRIBUTES` (7), `DOES_BLIP_EXIST` (6), `IS_PED_RAGDOLL` (6), `GET_PED_BONE_COORDS` (6), `IS_SYNCHRONIZED_SCENE_RUNNING` (5), `SETTIMERA` (5), `CREATE_SYNCHRONIZED_SCENE` (5), `SET_PED_RELATIONSHIP_GROUP_HASH` (5), `IS_ENTITY_IN_ANGLED_AREA` (5), `CAN_PED_SEE_HATED_PED` (5), `IS_ENTITY_AT_ENTITY` (5), `TASK_SMART_FLEE_PED` (5), `WAIT` (4), `IS_VEHICLE_DRIVEABLE` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x5 · `0.5f` x4 · `31.64024f` x4 · `6405.058f` x4 · `-98.41389f` x4 · `-91.30704f` x3 · `6391.854f` x3 · `30.6403f` x3 · `-102.5595f` x3 · `6403.103f` x3 · `32.45444f` x3 · `8.5f` x3 · `0.1f` x2 · `-104.982f` x1 · `6408.737f` x1 · `30.4905f` x1 · `-90.68654f` x1 · `6411.883f` x1 · `36.00729f` x1 · `-103.86f` x1 · `6398.848f` x1 · `30.19453f` x1 · `-91.56341f` x1 · `6391.747f` x1

## Other strings

Literals whose consuming native was not classified:

`FUNC BOOL HAS_PLAYER_AGGROED_PED\n`, `RERHO_THANK`, `WAVELOAD_PAIN_FEMALE`, `	aggroReason = EAggro_ShotNear\n`, `RERHO_BLAME`, `RERHO_BLAME_3`, `GENERIC_SHOCKED_HIGH`, `RERHO_NOGUN`, `RERHO_CONS`, `ambulance`, `RERHO_SAINT`, `RERHO_HELP`, `RERHO_RANT`, `RERHO_SCREAM`, `police`, `pranger`, `sheriff`, `sheriff2`, `bulldozer`, `	aggroReason = EAggro_Attacked\n`, `	aggro Ped knows player is pointing gun\n`, `		lockOnTimer = `, `		time since not LockedOn = `, `			aggroReason = EAggro_HostileOrEnemy\n`, `			aggroReason = EAggro_Danger\n`, `RERHO_DIE`, `RHCriminal`, `RHHostage`, `RHBystander`

---

Source: `decompiled_scripts/re_rescuehostage.c`
