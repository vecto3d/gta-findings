# maude_postbailbond.c

Jobs script. 1 anim dicts; 3 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 1,487 |
| Functions | 58 (14 unique, 44 shared) |
| Unique lines | 465 (31.3% of file) |

## Assets

**Animation dictionaries** (1) - `special_ped@maude@base`

**Animations** (3) - `special_ped@maude@base`, `base_chair`, `Female_Flee_Table_Left_Maude_Chair`

**Models and props** (3) - `prop_table_03b`, `prop_laptop_01a`, `prop_table_03_chr`

**Text labels** (7) - `MAUDE`, `NULL`, `BB4AUD`, `BB3AUD`, `BB2AUD`, `BB1AUD`, `MAUDEAU`

**Relationship groups** (1) - `player`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (11), `FREEZE_ENTITY_POSITION` (7), `DOES_ENTITY_EXIST` (5), `GET_GAME_TIMER` (4), `IS_ENTITY_TOUCHING_ENTITY` (4), `GET_ENTITY_COORDS` (3), `VDIST2` (3), `IS_ENTITY_PLAYING_ANIM` (3), `HAS_PED_RECEIVED_EVENT` (3), `IS_ENTITY_A_MISSION_ENTITY` (3), `SET_ENTITY_AS_MISSION_ENTITY` (3), `DOES_OBJECT_OF_TYPE_EXIST_AT_COORDS` (3), `GET_CLOSEST_OBJECT_OF_TYPE` (3), `SET_ENTITY_COORDS` (3), `SET_ENTITY_HEADING` (3), `IS_PED_INJURED` (2), `SET_PED_KEEP_TASK` (2), `STOP_PED_SPEAKING` (2), `SET_PED_CONFIG_FLAG` (2), `STOP_ENTITY_ANIM` (2), `STOP_SYNCHRONIZED_ENTITY_ANIM` (2), `HAS_FORCE_CLEANUP_OCCURRED` (1), `REQUEST_ANIM_DICT` (1), `IS_PED_FLEEING` (1), `WAIT` (1), `TASK_SMART_FLEE_PED` (1), `IS_AMBIENT_SPEECH_PLAYING` (1), `IS_AMBIENT_SPEECH_DISABLED` (1), `ARE_STRINGS_EQUAL` (1), `HAS_ENTITY_BEEN_DAMAGED_BY_ANY_PED` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`2727.4f` x1 · `4145.56f` x1 · `43.68f` x1 · `-92.17f` x1 · `2727.686f` x1 · `4145.715f` x1 · `44.08f` x1 · `2728.35f` x1 · `4145.59f` x1 · `43.3f` x1 · `-91.28f` x1

## Other strings

Literals whose consuming native was not classified:

`GENERIC_FRIGHTENED_HIGH`, `BB4_loiter`, `BB3_loiter`, `BB2_loiter`, `BB1_loiter`, `MAUDE_loiter`, `base_chair`, `Female_Flee_Table_Left_Maude_Chair`

---

Source: `decompiled_scripts/maude_postbailbond.c`
