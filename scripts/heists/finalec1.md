# finalec1.c

Heists script. 3 anim dicts; 7 models.

| | |
|---|---|
| Category | Heists |
| Total lines | 126,385 |
| Functions | 1,056 (188 unique, 868 shared) |
| Unique lines | 10,715 (8.5% of file) |

## Assets

**Animation dictionaries** (3) - `veh@bike@police@front@base`, `missfinale_c1@leadin@fin_mcs_1`, `MISSFINALE_C1@LAMAR_WAIT`

**Animations** (7) - `trevor_waiting_impatient_a`, `PHONE_OUTRO`, `veh@bike@police@front@base`, `still`, `_leadin_idle_trevor`, `_leadin_idle_michael`, `PHONE_LOOP`

**Models and props** (7) - `prop_gas_tank_02a`, `s_m_y_swat_01`, `s_m_y_blackops_01`, `prop_barrel_exp_01a`, `prop_npc_phone`, `prop_box_wood03a`, `prop_wheelchair_01_s`

**Sounds** (11) - `FINALE_SHOOTOUT_FIRST_WAVE`, `FINALE_GET_TO_FOUNDRY`, `FINALE_ENEMIES_ARRIVE_ONESHOT`, `FINALE_ENTER_FOUNDRY`, `FINALE_WAIT_FOR_AMBUSH`, `FINALE_GET_TO_LAMAR`, `FINALE_SHOOTOUT_WITH_LAMAR`, `FINALE_SAVE_TREVOR`, `FINALE_GET_TO_EXIT`, `FINALE_SHOOTOUT_OUTSIDE`, `FINALE_HELICOPTER_ARRIVES`

**Text labels** (88) - `FINC1AU`, `FRANKLIN`, `REDMIST`, `LAMAR`, `MICHAEL`, `TREVOR`, `NULL`, `FINC`, `FIBSEARCH1`, `FIBSEARCH2`, `FIBSEARCH3`, `FIBSEARCH4`, `FIBSEARCH5`, `FIBSEARCH6`, `FIBSEARCH7`, `FIBCWALK1`, `FIBCWALK2`, `FIBTCORN1`, `FIBTCORN2`, `FIBTCORN3`, `ATTTREVGRND1`, `ATTTREVGRND2`, `ATTTREVGRND3`, `ATTTREVGRND4`, `ATTTREVGRND5`, `ATTTREVGRND6`, `ATTTREVGRND7`, `ATTTREVCAT1`, `ATTTREVCAT2`, `ATTTREVFIN1`, `ATTTREVFIN2`, `ATTTREVFIN3`, `ATTTREVFIN4`, `ATTTREVFIN5`, `ATTTREVFIN6`, `ATTTREVFIN7`, `FIBREINF1`, `FIBREINF2`, `FIBREINF3`, `FIBOUTSIDE1`, `FIBOUTSIDE2`, `FIBOUTSIDE3`, `MERCINSIDE1`, `MERCINSIDE2`, `MERCINSIDE3`, `FIBLAMIN1`, `FIBLAMIN2`, `FIBLAMINRE1`, `FIBLAMINRE2`, `FIBLAM1`, `FIBLAM2`, `FIBLAM3`, `FIBLAM4`, `FIBLAM5`, `FIBLAMRE1`, `FIBLAMRE2`, `FIBLAMRE3`, `FIBLAMRE4`, `FIBLAMRE5`, `FIBLAMINF1` ...

**Relationship groups** (4) - `player`, `IgnoreGroup`, `FIB group`, `Merc group`

**Vehicle mods** (1) - `bagger`

**Stats** (6) - `sp0_special_ability`, `sp0_special_ability_unlocked`, `sp1_special_ability`, `sp1_special_ability_unlocked`, `sp2_special_ability`, `sp2_special_ability_unlocked`

**Hashed names** (1) - `foundrymainrm`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (216), `DOES_ENTITY_EXIST` (71), `IS_PED_INJURED` (70), `GET_GAME_TIMER` (33), `WAIT` (30), `GET_RANDOM_INT_IN_RANGE` (28), `DOES_BLIP_EXIST` (27), `PLAYER_ID` (25), `IS_MESSAGE_BEING_DISPLAYED` (24), `REGISTER_ENTITY_FOR_CUTSCENE` (23), `CAN_SET_EXIT_STATE_FOR_REGISTERED_ENTITY` (21), `TRIGGER_MUSIC_EVENT` (20), `REMOVE_BLIP` (20), `IS_VEHICLE_DRIVEABLE` (16), `REPLAY_RECORD_BACK_FOR_TIME` (16), `SET_ENTITY_HEADING` (16), `SET_PED_CONFIG_FLAG` (16), `DELETE_PED` (15), `CLEAR_SEQUENCE_TASK` (15), `IS_ENTITY_AT_COORD` (14), `SET_ENTITY_ONLY_DAMAGED_BY_PLAYER` (14), `OPEN_SEQUENCE_TASK` (14), `CLOSE_SEQUENCE_TASK` (14), `TASK_PERFORM_SEQUENCE` (14), `TASK_PUT_PED_DIRECTLY_INTO_COVER` (13), `GET_SCRIPT_TASK_STATUS` (13), `REMOVE_ENTITY_FROM_AUDIO_MIX_GROUP` (12), `SET_ENTITY_COORDS` (12), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (12), `IS_SCREEN_FADED_OUT` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x5 · `-2.5f` x4 · `42.8439f` x4 · `0.2f` x3 · `1092.61f` x2 · `-1998.99f` x2 · `31.37f` x2 · `30.01f` x2 · `323.6474f` x2 · `31.31f` x2 · `30.0447f` x2 · `30.0244f` x2 · `30.0444f` x2 · `5.5f` x2 · `1088.607f` x2 · `-2014.471f` x2 · `1105.919f` x2 · `-2026.294f` x2 · `1114.171f` x2 · `-2022.271f` x2 · `39.2828f` x2 · `1111.402f` x2 · `-2019.724f` x2 · `34.4867f` x2

## Other strings

Literals whose consuming native was not classified:

`Franklin`, `player`, `FIRING_PATTERN_FULL_AUTO`, `FIN1_START`, `Michael`, `Trevor`, `Franklin_Bike`, `Michaels_car`, `Trevors_car`, `FINALE_BUDDY_Group`, `FINALE_GET_TO_FOUNDRY`, `Lester`, `bagger`, `BulletTime`, `BulletTimeOut`, `DrivingFocus`, `DrivingFocusOut`, `REDMISTOut`, `FIN1_FAIL`, `FIRING_PATTERN_BURST_FIRE`, `sovereign`, `invalid!`, `FINC1_FBANT`, `FINC1_ATT_T`, `FINC1_ATT_M`, `FIN1_SHOOTOUT_3`, `FINC1_HELPF`, `FINC1_LHELP2`, `FINC1_LHELP`

---

Source: `decompiled_scripts/finalec1.c`
