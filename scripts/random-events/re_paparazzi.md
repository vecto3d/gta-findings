# re_paparazzi.c

Random events script. 8 anim dicts; 7 models; 1 particle effects.

| | |
|---|---|
| Category | Random events |
| Total lines | 12,669 |
| Functions | 299 (72 unique, 227 shared) |
| Unique lines | 4,932 (38.9% of file) |

## Assets

**Animation dictionaries** (8) - `random@paparazzi@pap_anims`, `random@paparazzi@peek`, `random@paparazzi@trans`, `random@paparazzi@wait`, `random@escape_paparazzi@standing@`, `veh@std@ps@idle_panic`, `veh@low@front_ps@idle_panic`, `random@escape_paparazzi@incar@`

**Animations** (18) - `random@paparazzi@wait`, `sit`, `grip`, `random@paparazzi@pap_anims`, `wait_c`, `wait_a`, `wait_b`, `VEH@STD@PS@IDLE_PANIC`, `VEH@LOW@FRONT_PS@IDLE_PANIC`, `random@paparazzi@peek`, `pap_idle_a`, `pap_idle_b`, `base`, `random@paparazzi@trans`, `base_pap`, `left_peek_a`, `trans_left_to_wait`, `trans_right_to_wait`

**Models and props** (7) - `a_m_y_genstreet_02`, `prop_pap_camera_01`, `cavalcade2`, `vader`, `prop_ld_test_01`, `a_f_y_bevhills_03`, `surano`

**Audio banks** (1) - `Distant_Camera_Flash`

**Sounds** (4) - `CAMERA_FLASH_SOUNDSET`, `SHUTTER_FLASH`, `SHUTTER`, `FLASH`

**Speech contexts** (1) - `LACEY`

**Particle effects** (1) - `scr_rcpap1_camera`

**Text labels** (14) - `PAPARAZZO`, `PAP2ESCAPE`, `PAP1ESCAPE`, `FRANKLIN`, `MICHAEL`, `TREVOR`, `NULL`, `REPAPAU`, `PAP3ESCAPE`, `PAP2`, `PAP3`, `PAP4`, `LACEY`, `ESCPAP`

**Scenarios** (2) - `WORLD_HUMAN_SMOKING`, `WORLD_VEHICLE_DRIVE_SOLO`

**Relationship groups** (1) - `CELEBRITY`

**Vehicle mods** (3) - `cavalcade2`, `vader`, `surano`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_PED_INJURED` (112), `PLAYER_PED_ID` (98), `DOES_ENTITY_EXIST` (76), `GET_GAME_TIMER` (61), `DOES_BLIP_EXIST` (48), `IS_VEHICLE_DRIVEABLE` (45), `GET_ENTITY_COORDS` (42), `VDIST2` (34), `IS_PED_IN_VEHICLE` (34), `REMOVE_BLIP` (34), `TASK_PLAY_ANIM` (28), `CLEAR_PED_TASKS` (22), `GET_SCRIPT_TASK_STATUS` (22), `IS_ENTITY_PLAYING_ANIM` (20), `VDIST` (18), `IS_PED_IN_ANY_VEHICLE` (17), `PLAYER_ID` (16), `IS_ENTITY_OCCLUDED` (16), `SETTIMERA` (16), `IS_ENTITY_AT_COORD` (15), `TASK_FOLLOW_NAV_MESH_TO_COORD` (14), `REQUEST_ANIM_DICT` (13), `HAS_ANIM_DICT_LOADED` (13), `SET_PED_COMBAT_ATTRIBUTES` (12), `TIMERA` (12), `GET_RANDOM_INT_IN_RANGE` (11), `GET_VEHICLE_PED_IS_IN` (11), `IS_ENTITY_IN_ANGLED_AREA` (9), `TASK_VEHICLE_MISSION` (9), `SET_PED_FLEE_ATTRIBUTES` (9)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x13 · `93.8361f` x7 · `92.1704f` x7 · `246.1673f` x7 · `0.99f` x5 · `0.9f` x4 · `0.5f` x4 · `2.5f` x4 · `0.75f` x3 · `0.95f` x3 · `93.3633f` x2 · `82.5239f` x2 · `276.3459f` x2 · `188.5935f` x2 · `675.8706f` x2 · `227.8598f` x2 · `30.5f` x2 · `22.5f` x2 · `265.408f` x2 · `151.2875f` x2 · `103.5673f` x2 · `217.1033f` x2 · `245.9477f` x2 · `72.661f` x2

## Other strings

Literals whose consuming native was not classified:

`cavalcade2`, `REPAP_THK`, `left_`, `MAG_2_ESCAPE_PAP_GET_CAR`, `REPAP_CALL1`, `vader`, `base_pap`, `pap_idle_a`, `pap_idle_b`, `MAG_2_PAPARAZZI_GROUP`, `idle_a`, `idle_b`, `idle_c`, `idle_d`, `idle_e`, `EP_PAPBLIP`, `REPAP_GUP`, `player`, `REPAP_TAKE2T`, `REPAP_TAKE2M`, `REPAP_HOME2`, `REPAP_HOME3`, `REPAP_HOME4`, `REPAP_NOBAN`, `MAG_2_ESCAPE_PAP_TAKE_ACTRESS_HOME`, `right_`, `REPAP_PRT`, `MAG_2_ESCAPE_PAP_CHASE`, `RE_EP`, `REPAP_CHAT`

---

Source: `decompiled_scripts/re_paparazzi.c`
