# taxi_gotyounow.c

Jobs script. 5 developer state labels recovered; 12 anim dicts; 4 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 15,183 |
| Functions | 437 (50 unique, 387 shared) |
| Unique lines | 2,271 (15.0% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`GYN_CS_END` · `Player INSIDE of vehicle` · `Player OUTSIDE of vehicle` · `Player INSIDE of vehicle adjusted` · `Player OUTSIDE of vehicle adjusted`

## Assets

**Animation dictionaries** (12) - `misscommon@response`, `oddjobs@taxi@gyn@`, `melee@unarmed@streamed_taunts`, `amb@world_human_hang_out_street@male_a@enter`, `amb@world_human_hang_out_street@male_a@base`, `amb@world_human_hang_out_street@male_a@idle_a`, `amb@world_human_hang_out_street@female_arm_side@enter`, `amb@world_human_hang_out_street@female_arm_side@base`, `amb@world_human_hang_out_street@female_arm_side@idle_a`, `amb@world_human_hang_out_street@female_arm_side@exit`, `amb@world_human_hang_out_street@male_a@exit`, `move_strafe_melee_unarmed`

**Animations** (10) - `oddjobs@towingcome_here`, `misscommon@response`, `come_here_idle_a`, `come_here_idle_c`, `gestures@m@standing@casual`, `gesture_nod_yes_hard`, `give_me_a_break`, `damn`, `oddjobs@taxi@gyn@`, `idle_b_ped`

**Models and props** (4) - `prop_skid_chair_02`, `prop_rub_couch03`, `g_m_y_mexgoon_03`, `a_f_y_eastsa_03`

**Audio banks** (1) - `SCRIPT\TREVOR_2_BIKER_RINGTONE`

**Sounds** (7) - `TAXI_GOT_U_NOW`, `Biker_Ring_Tone`, `TREVOR_2_SOUNDS`, `CHECKPOINT_UNDER_THE_BRIDGE`, `HUD_MINI_GAME_SOUNDSET`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Speech contexts** (1) - `TaxiLiz`

**Text labels** (4) - `NULL`, `TAXI_OBJ_GYN`, `OJTXAUD`, `SNAKEYES`

**Scenarios** (1) - `WORLD_HUMAN_STAND_MOBILE`

**Waypoint recordings** (1) - `taxi_oj_gyn`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (45), `IS_ENTITY_DEAD` (31), `IS_PED_INJURED` (31), `IS_VEHICLE_DRIVEABLE` (15), `REMOVE_ANIM_DICT` (11), `REQUEST_ANIM_DICT` (11), `HAS_ANIM_DICT_LOADED` (9), `DOES_ENTITY_EXIST` (8), `IS_PED_IN_ANY_VEHICLE` (8), `CLEAR_SEQUENCE_TASK` (8), `OPEN_SEQUENCE_TASK` (8), `TASK_TURN_PED_TO_FACE_ENTITY` (8), `CLOSE_SEQUENCE_TASK` (8), `TASK_PERFORM_SEQUENCE` (8), `GET_ENTITY_HEALTH` (8), `GET_ENTITY_COORDS` (8), `SET_PED_COMPONENT_VARIATION` (7), `PLAYER_ID` (7), `TASK_LOOK_AT_ENTITY` (7), `GET_SCRIPT_TASK_STATUS` (7), `REMOVE_BLIP` (6), `CLEAR_PED_TASKS_IMMEDIATELY` (6), `DOES_BLIP_EXIST` (6), `SET_PED_CONFIG_FLAG` (5), `DRAW_DEBUG_TEXT_2D` (5), `DOES_CAM_EXIST` (5), `DESTROY_CAM` (5), `SET_PLAYER_CONTROL` (4), `SET_PED_KEEP_TASK` (4), `GET_GAME_TIMER` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x6 · `0.5f` x5 · `0.75f` x2 · `0.2f` x2 · `196.3547f` x1 · `3.5f` x1 · `-612.6458f` x1 · `-777.7148f` x1 · `24.27f` x1 · `-608.3197f` x1 · `-775.0622f` x1 · `24.0547f` x1 · `-589.0419f` x1 · `-775.1888f` x1 · `24.0172f` x1 · `0.3f` x1 · `8.25f` x1 · `114.629f` x1 · `-1.6f` x1 · `27.1498f` x1 · `-1246.523f` x1 · `28.4013f` x1 · `297.629f` x1

## Other strings

Literals whose consuming native was not classified:

`TAXI_FAIL`, `TAXI_OBJ_FAIL`, `TAXI_OBJ_F_SPT`, `Taxi Not Driveable`, `TAXI_OBJ_F_SPK`, `_shot1`, `_noDri2`, `_noDri1`, `TAXI_SC_KO`, `Player abandoned passenger`, `_aband2`, `_aband1`, `move_strafe_melee_unarmed`, `txm9_figt1`, `Didn't lose police in time.`, `Taxi Is Flipped`, `Stayed stopped for too long.`, `Passenger injured.`, `TAXI_ASSETS_STREAMED - Loading A_M_M_Farmer_01`, `TAXI_ASSETS_STREAMED - Loading shared assets`, `TRS_STREAMING`, ` TRS_SPAWN_CAR `, ` TRS_CUTSCENE_02 `, ` TRS_SEND_TO_STORE `, ` TRS_WAIT_1ST_STOP `, ` TRS_POLICE_ESCAPED `, ` TRS_ESCAPE_POLICE `, ` TRS_TIE_UP_LOSE_ENDS `, ` TRS_REGULAR_PAYMENT `, ` TRS_ELIMATE_ALL_ENEMIES `

---

Source: `decompiled_scripts/taxi_gotyounow.c`
