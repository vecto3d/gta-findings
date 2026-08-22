# re_yetarian.c

Random events script. 2 anim dicts; 6 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 8,763 |
| Functions | 171 (19 unique, 152 shared) |
| Unique lines | 1,028 (11.7% of file) |

## Assets

**Animation dictionaries** (2) - `cellphone@`, `cellphone@str`

**Animations** (7) - `cellphone@str`, `cellphone@`, `cellphone_call_out`, `cellphone_call_listen_b`, `cellphone_call_listen_f`, `cellphone_call_listen_no_a`, `cellphone_call_listen_d`

**Models and props** (6) - `baller2`, `tailgater`, `bjxl`, `p_amb_phone_01`, `g_m_m_armgoon_01`, `g_m_y_armgoon_02`

**Text labels** (5) - `FIGHT`, `NULL`, `FRANKLIN`, `MICHAEL`, `SIMEON`

**Scenarios** (2) - `DEALERSHIP`, `PROP_HUMAN_SEAT_CHAIR`

**Waypoint recordings** (1) - `reyetarian_simeonoffice`

**Relationship groups** (3) - `GoonGroup`, `PlayerGroup`, `YetarianGroup`

**Doors** (1) - `v_ilev_fib_door1`

**Hashed names** (1) - `rm_showroom`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (50), `GET_ENTITY_COORDS` (26), `GET_DISTANCE_BETWEEN_COORDS` (10), `TASK_PLAY_ANIM` (10), `OPEN_SEQUENCE_TASK` (9), `CLOSE_SEQUENCE_TASK` (9), `TASK_LOOK_AT_ENTITY` (8), `TASK_PERFORM_SEQUENCE` (7), `CLEAR_SEQUENCE_TASK` (7), `GET_SCRIPT_TASK_STATUS` (6), `DOES_ENTITY_EXIST` (6), `HAS_MODEL_LOADED` (6), `SET_RELATIONSHIP_BETWEEN_GROUPS` (6), `REQUEST_MODEL` (6), `SET_PED_COMBAT_ATTRIBUTES` (4), `CLEAR_PED_TASKS` (4), `TASK_SMART_FLEE_PED` (4), `REMOVE_NAVMESH_BLOCKING_OBJECT` (4), `IS_POSITION_OCCUPIED` (4), `IS_ENTITY_IN_ANGLED_AREA` (4), `SET_ENTITY_VISIBLE` (4), `FREEZE_ENTITY_POSITION` (4), `SET_ENTITY_CAN_BE_DAMAGED` (4), `GIVE_WEAPON_TO_PED` (4), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (3), `SET_PED_RELATIONSHIP_GROUP_HASH` (3), `TASK_TURN_PED_TO_FACE_ENTITY` (3), `REMOVE_RELATIONSHIP_GROUP` (3), `DOES_BLIP_EXIST` (3), `REMOVE_BLIP` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-69.62395f` x3 · `-1087.37f` x3 · `24.59833f` x3 · `-11.27861f` x3 · `-1108.28f` x3 · `34.17205f` x3 · `47.5f` x3 · `25.42f` x3 · `4.5f` x2 · `-51.0518f` x2 · `-1104.685f` x2 · `25.2975f` x2 · `-29.9812f` x2 · `-1094.079f` x2 · `27.5686f` x2 · `-61.01321f` x2 · `-1093.393f` x2 · `25.75297f` x2 · `-38.59683f` x2 · `-1109.284f` x2 · `25.68742f` x2 · `-37.34785f` x1 · `-1102.022f` x1 · `25.42232f` x1

## Other strings

Literals whose consuming native was not classified:

`player`, `RE9_SPOTTED`, `RE_YETA_SNIP`, `YETARIAN_GOON`, `bjxl`, `tailgater`, `baller2`, `REYE_AU`, `RE_YETA_EXT`, `RE_YETAM`, `object`, `SCRIPTED_SCANNER_REPORT_SIMEON_01`, `RE_YETAF`, `DEFAULT_ACTION`, `RE_YETA_MIKE`, `RE_YETA_FRAN`

---

Source: `decompiled_scripts/re_yetarian.c`
