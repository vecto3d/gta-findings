# towing.c

Jobs script. 9 anim dicts; 16 models; 2 scaleforms.

| | |
|---|---|
| Category | Jobs |
| Total lines | 13,225 |
| Functions | 301 (50 unique, 251 shared) |
| Unique lines | 4,372 (33.1% of file) |

## Assets

**Animation dictionaries** (9) - `move_m@JOG@`, `amb@world_human_smoking@male@male_a@base`, `oddjobs@towing`, `REACTION@MALE_STAND@BIG_VARIATIONS@A`, `oddjobs@towingpleadingidle_b`, `oddjobs@towingcome_here`, `oddjobs@towingangryidle_a`, `oddjobs@towingpleadingidle_a`, `RANDOM@CAR_SLEEPING`

**Animations** (15) - `oddjobs@towing`, `Start_Engine_Loop`, `oddjobs@towingcome_here`, `come_here_idle_a`, `oddjobs@towingpleadingidle_b`, `idle_d`, `oddjobs@towingpleadingidle_a`, `idle_c`, `Start_Engine_Exit`, `m_blow_job_loop`, `f_blow_job_loop`, `RANDOM@CAR_SLEEPING`, `Sleeping_Idle`, `oddjobs@towingangryidle_a`, `idle_b`

**Models and props** (16) - `a_m_y_genstreet_02`, `a_f_m_bevhills_01`, `a_m_y_beach_03`, `a_m_m_bevhills_02`, `s_m_m_lsmetro_01`, `s_m_m_paramedic_01`, `g_m_y_salvagoon_01`, `a_m_m_tramp_01`, `a_m_y_methhead_01`, `a_m_m_tourist_01`, `a_m_m_tranvest_01`, `a_f_y_hipster_02`, `s_f_y_sweatshop_01`, `a_m_y_yoga_01`, `a_m_y_musclbeac_01`, `ambulance`

**Audio banks** (1) - `SCRIPT\TOWING_TRAIN`

**Sounds** (2) - `TOWING_ONCOMING_TRAIN_SCENE`, `TOWING_ENGINE_TURNING_MASTER`

**Scaleform movies** (2) - `SHOW_SHARD_MIDSIZED_MESSAGE`, `STRING`

**Text labels** (16) - `TOWAUD`, `FRANKLIN`, `TOWTRAINF`, `TOWBREAKM`, `TOWBREAKHIPM`, `TOWDISPATCH`, `TONYA`, `TOWABDBITCHM`, `TOWABDATTACKM`, `TOW`, `DTRSHRD`, `TOWHANDIBEGM`, `TOWTRAINM`, `TOW_TUT_04A`, `TOWT_OBJ_03Ga`, `NULL`

**Scenarios** (3) - `WORLD_HUMAN_STAND_MOBILE`, `WORLD_HUMAN_SMOKING`, `WORLD_HUMAN_STAND_IMPATIENT`

**Relationship groups** (1) - `TOWBUDDIES`

**Vehicle mods** (1) - `towtruck`

**Scripts launched** (3) - `tonya5`, `tonya4`, `tonya3`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_ENTITY_DEAD` (133), `PLAYER_PED_ID` (78), `DOES_ENTITY_EXIST` (42), `IS_VEHICLE_ATTACHED_TO_TOW_TRUCK` (22), `CLEAR_SEQUENCE_TASK` (21), `OPEN_SEQUENCE_TASK` (17), `CLOSE_SEQUENCE_TASK` (17), `TASK_PERFORM_SEQUENCE` (17), `IS_PED_IN_VEHICLE` (17), `SET_BLIP_COLOUR` (15), `DOES_BLIP_EXIST` (14), `GET_ENTITY_COORDS` (14), `REMOVE_BLIP` (13), `TASK_PLAY_ANIM` (12), `TASK_TURN_PED_TO_FACE_ENTITY` (11), `ADD_BLIP_FOR_ENTITY` (11), `TASK_LEAVE_ANY_VEHICLE` (10), `SET_VEHICLE_DAMAGE` (9), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (8), `IS_ENTITY_IN_ANGLED_AREA` (8), `SET_VEHICLE_DOORS_LOCKED` (8), `TIMERA` (8), `CREATE_PED_INSIDE_VEHICLE` (8), `TASK_SMART_FLEE_PED` (8), `SET_BLIP_ROUTE` (8), `WAIT` (8), `IS_PED_IN_ANY_VEHICLE` (7), `CLEAR_HELP` (7), `SETTIMERA` (7), `SET_BLIP_SCALE` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.7f` x7 · `0.25f` x6 · `1.5f` x3 · `27.5001f` x2 · `-640.002f` x2 · `414.1398f` x2 · `21.8557f` x2 · `-229.8159f` x2 · `408.8376f` x2 · `-1638.952f` x2 · `28.2928f` x2 · `-0.5f` x2 · `-1.5f` x2 · `226.8878f` x1 · `-2538.421f` x1 · `4.8665f` x1 · `400.2854f` x1 · `-1632.597f` x1 · `28.29278f` x1 · `7.5f` x1 · `0.2f` x1 · `-3.24f` x1 · `-62.6001f` x1 · `227.082f` x1

## Other strings

Literals whose consuming native was not classified:

`TOWILLEGALMAN2`, `TOWSEXMANLYGUY`, `TOWT_OBJ_06`, `TOW_TUT_03`, `TOWT_HELP_UH`, `TOW_GETOUT`, `TOW_GETOUT2`, `TOWT_OBJ_04`, `TOWT_OBJ_03G`, `TOW_HOM_DRG`, `TOW_PED_ANGR`, `TOWABDHANDMAN2`, `TOW_TUT_02`, `TOW_TUT_01`, `TOW_TUT_04A`, `TOW_BRK_C`, `TOW_MECH`, `TOW_MECH2`, `TOW_BRK_CONV`, `TOW_BRK_CON2`, `TOW_TRN_C1`, `tailgater`, `primo`, `intruder`, `voodoo2`, `ruiner`, `TOW_HAN_EXP2`, `TOWT_OBJ_05`, `towtruck`, `TOW_FAIL_08`

---

Source: `decompiled_scripts/towing.c`
