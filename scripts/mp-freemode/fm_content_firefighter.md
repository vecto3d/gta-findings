# fm_content_firefighter.c

MP freemode script. 11 anim dicts; 9 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 509,384 |
| Functions | 10,553 (389 unique, 10,164 shared) |
| Unique lines | 12,012 (2.4% of file) |

## Assets

**Animation dictionaries** (11) - `anim@door_trans@hinge_l@`, `anim@scripted@freemode@ig11_valve_turn@male@`, `anim@scripted@freemode@ig11_valve_turn@heeled@`, `anim@door_trans@hinge_r@`, `creatures@cat@player_action@`, `creatures@cat@step`, `anim@scripted@creatures@cat@amb@mansion@heeled@`, `anim@scripted@creatures@cat@amb@mansion@male@`, `anim@gangops@morgue@table@`, `anim@scripted@ulp_missions@garageopen@heeled@`, `anim@scripted@ulp_missions@garageopen@male@`

**Models and props** (9) - `prop_laptop_01a`, `Prop_Fire_Loop`, `prop_sec_gate_01d`, `a_f_y_gencaspat_01`, `a_m_y_gencaspat_01`, `a_m_y_busicas_01`, `a_f_y_hippie_01`, `a_m_m_hillbilly_02`, `a_f_y_business_04`

**Audio banks** (2) - `DLC_23_2/DLC_23_2_Freemode_1`, `DLC_HEIST3/CASINO_HEIST_FINALE_GENERAL_01`

**Sounds** (6) - `FireSize`, `Hud_Fire_Exitinguished`, `Garage_Door_Open`, `GTAO_Script_Doors_Faded_Screen_Sounds`, `Barge_Door`, `dlc_h4_Prep_FC_Sounds`

**Text labels** (1) - `X25DSAU`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (83), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (38), `SET_PED_COMPONENT_VARIATION` (34), `GET_ENTITY_COORDS` (25), `NET_TO_ENT` (20), `DOES_ENTITY_EXIST` (18), `SET_VEHICLE_DAMAGE` (12), `DOES_BLIP_EXIST` (11), `GET_RANDOM_INT_IN_RANGE` (11), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (11), `NET_TO_PED` (10), `SET_BIT` (8), `GET_ENTITY_HEADING` (8), `IS_ENTITY_PLAYING_ANIM` (8), `REMOVE_BLIP` (7), `DISABLE_CONTROL_ACTION` (7), `GET_ENTITY_ROTATION` (7), `GET_ENTITY_MODEL` (6), `CLEAR_PED_TASKS` (6), `IS_STRING_NULL_OR_EMPTY` (6), `SET_ENTITY_INVINCIBLE` (6), `TASK_ENTER_VEHICLE` (5), `REQUEST_SCRIPT_AUDIO_BANK` (5), `TASK_PLAY_ANIM` (5), `SET_PED_CONFIG_FLAG` (5), `FREEZE_ENTITY_POSITION` (5), `REGISTER_ENTITY_FOR_CUTSCENE` (5), `CLEAR_BIT` (4), `NETWORK_IS_PARTICIPANT_ACTIVE` (4), `GET_OBJECT_INDEX_FROM_ENTITY_INDEX` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x9 · `0.4f` x2 · `-0.5f` x2 · `172.935f` x2 · `-999.418f` x2 · `-98.971f` x2 · `-0.2f` x2 · `-0.06f` x2 · `-0.6f` x1 · `0.5f` x1 · `0.99f` x1 · `1.5f` x1 · `0.75f` x1 · `1.3f` x1 · `0.85f` x1 · `750.213f` x1 · `4184.079f` x1 · `40.12889f` x1 · `75.24f` x1 · `-3075.552f` x1 · `655.0067f` x1 · `10.5973f` x1 · `310.14f` x1 · `-1107.854f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `Building_Fire_Single_Loop`, `int`, `typ`, `bsa`, `sprt`, `hclr`, `scl`, `rot`, `rad`, `ibs`, `Tanker_Fire_Single_Loop`, `FF_SHARD_T`, `MAX_NUM_SCENARIOS`, `blp`, `grp`, `veh`, `Fire_Extinguishing_Loop`, `charge_cam_left`, `Vehicle_Fire_Loop`, `intensity`, `FF_BLP_FIRE`, `MAX_NUM_TRANSITIONS`, `fcs`

---

Source: `decompiled_scripts/fm_content_firefighter.c`
