# docks_prep1.c

Heists script. 2 anim dicts; 15 models; 2 particle effects.

| | |
|---|---|
| Category | Heists |
| Total lines | 19,797 |
| Functions | 342 (35 unique, 307 shared) |
| Unique lines | 3,607 (18.2% of file) |

## Assets

**Animation dictionaries** (2) - `REACTION@MALE_STAND@BIG_VARIATIONS@IDLE_B`, `cellphone@str`

**Animations** (9) - `MISSHEISTDOCKSPREP1HOLD_CELLPHONE`, `HOLD_CELLPHONE`, `cellphone_call_listen_c`, `react_big_variations_g`, `react_big_variations_i`, `react_big_variations_f`, `ig_1_stealth_button`, `ig_1_button`, `react_big_variations_h`

**Models and props** (15) - `prop_sub_cover_01`, `prop_tarp_strap`, `s_m_m_security_01`, `s_m_m_dockwork_01`, `submersible`, `prop_ld_test_01`, `prop_sub_release`, `packer`, `armytrailer`, `p_amb_phone_01`, `prop_dock_crane_02_ld`, `prop_dock_crane_02_cab`, `prop_dock_crane_02_hook`, `bison`, `ig_floyd`

**Sounds** (6) - `DOCKS_HEIST_PREP_1_SOUNDSET`, `SUB_RELEASE`, `SUB_SPLASH`, `DOCKS_HEIST_PREP_1_SUB_SWING`, `DOCKS_HEIST_PREP_1_SUB_TILT`, `DOCKS_HEIST_PREP_1_CABLE_SNAP`

**Particle effects** (2) - `flow`, `scr_pls_sub_water_drips`

**Text labels** (10) - `CONSTRUCTION2`, `DHP1AUD`, `SOL1AUD`, `FLOYD`, `TREVOR`, `MICHAEL`, `FRANKLIN`, `NULL`, `EXTRASUNNY`, `DOCKP1`

**Waypoint recordings** (1) - `docksprep1`

**Relationship groups** (2) - `REL_BUDDY`, `rel_dock`

**Hashed names** (1) - `V_FakeBoatPO1SH2A`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (155), `GET_GAME_TIMER` (48), `DOES_ENTITY_EXIST` (45), `GET_ENTITY_COORDS` (35), `PLAYER_ID` (27), `DOES_BLIP_EXIST` (26), `TASK_PLAY_ANIM` (22), `IS_ENTITY_IN_ANGLED_AREA` (20), `CLEAR_SEQUENCE_TASK` (19), `SET_BIT` (19), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (17), `REMOVE_BLIP` (16), `CLEAR_PED_TASKS` (16), `IS_PED_IN_VEHICLE` (16), `GET_VEHICLE_PED_IS_IN` (15), `FREEZE_ENTITY_POSITION` (15), `CLEAR_BIT` (15), `SET_CAM_PARAMS` (14), `IS_PED_IN_ANY_VEHICLE` (13), `HAS_PED_RECEIVED_EVENT` (13), `OPEN_SEQUENCE_TASK` (13), `CLOSE_SEQUENCE_TASK` (13), `TASK_PERFORM_SEQUENCE` (13), `ATTACH_ENTITY_TO_ENTITY` (13), `IS_PED_INJURED` (12), `GET_DISTANCE_BETWEEN_COORDS` (12), `CREATE_OBJECT` (12), `TASK_FOLLOW_NAV_MESH_TO_COORD` (12), `CREATE_VEHICLE` (11), `SET_VEHICLE_IS_CONSIDERED_BY_PLAYER` (11)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`8.31909f` x20 · `0.5f` x14 · `0.25f` x13 · `-1.5f` x12 · `0.1f` x8 · `324.7653f` x7 · `-2974.495f` x7 · `1240.513f` x6 · `-2880.356f` x6 · `2.10339f` x6 · `1240.559f` x6 · `-3057.271f` x6 · `17.4f` x6 · `29.45f` x6 · `1228.775f` x6 · `-2923.852f` x6 · `1.5f` x6 · `1260.692f` x4 · `-3008.286f` x4 · `23.73365f` x4 · `1260.896f` x4 · `-3006.556f` x4 · `23.4213f` x4 · `1229.557f` x4

## Other strings

Literals whose consuming native was not classified:

`PO1_08_sub_waterplane`, `LOSE_WANTED`, `DHP1_BUD`, `submersible`, `armytrailer`, `sub_cover`, `Floyd`, `packer`, `bison`, `player`, `MORE_SEATS`, `PORT_OF_LS_PREP_1`, `DKP1_BTN`, `OnlyAllowScriptTriggerPoliceScanner`, `GROUP_MELEE`, `SOL1_ARM2`, `SOL1_PAN2`, `DHP1_WHSE`, `DHP1_PARK`, `DHP1_START`, `DHP1_FAIL`, `VEHICLE_POLICE_PURSUIT`, `LOSE_WANTED_LEVEL`, `dkp1_tk1`, `DKP1_SUBBK`, `DKP1_SUBTURN`, `SUB_HELP`, `DockHeist_truck`, `submarine`, `Trevor`

---

Source: `decompiled_scripts/docks_prep1.c`
