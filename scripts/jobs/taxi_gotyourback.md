# taxi_gotyourback.c

Jobs script. 2 anim dicts; 6 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 15,097 |
| Functions | 435 (89 unique, 346 shared) |
| Unique lines | 3,535 (23.4% of file) |

## Assets

**Animation dictionaries** (2) - `random@countryside_gang_fight`, `oddjobs@taxi@argument`

**Animations** (25) - `oddjobs@taxi@argument`, `oddjobs@towingcome_here`, `come_here_idle_c`, `gestures@m@standing@casual`, `gesture_nod_yes_hard`, `come_here_idle_a`, `idle_a_biker_a`, `idle_a_biker_b`, `idle_a_biker_c`, `hooker_outro_biker_d`, `hooker_outro_hooker_a`, `hooker_outro_hooker_b`, `bridge_biker_d`, `bridge_hooker_a`, `bridge_hooker_b`, `stand_off_biker_a`, `stand_off_biker_b`, `stand_off_biker_c`, `stand_off_passenger`, `hooker_loop_b_biker_d`, `hooker_loop_b_hooker_a`, `hooker_loop_b_hooker_b`, `hooker_loop_a_biker_d`, `hooker_loop_a_hooker_a`, `hooker_loop_a_hooker_b`

**Models and props** (6) - `g_m_y_lost_01`, `a_m_m_farmer_01`, `prop_box_wood04a`, `prop_cardbordbox_03a`, `prop_barrel_exp_01a`, `s_f_y_hooker_01`

**Sounds** (4) - `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `CHECKPOINT_UNDER_THE_BRIDGE`, `HUD_MINI_GAME_SOUNDSET`

**Speech contexts** (5) - `TaxiBruce`, `TaxiDom`, `TaxiGangM`, `TaxiGangGirl2`, `TaxiGangGirl1`

**Text labels** (3) - `COP`, `NULL`, `OJTXAUD`

**Relationship groups** (1) - `TAXI_Pursuers`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_PED_INJURED` (71), `GET_GAME_TIMER` (42), `IS_ENTITY_DEAD` (41), `TASK_SYNCHRONIZED_SCENE` (24), `PLAYER_PED_ID` (19), `SET_PED_COMPONENT_VARIATION` (19), `IS_VEHICLE_DRIVEABLE` (18), `PLAYER_ID` (17), `SET_PED_COMBAT_ATTRIBUTES` (17), `DOES_BLIP_EXIST` (15), `GET_PLAYER_INDEX` (15), `SET_RELATIONSHIP_BETWEEN_GROUPS` (13), `GIVE_WEAPON_TO_PED` (13), `HAS_MODEL_LOADED` (12), `SET_BIT` (12), `REQUEST_MODEL` (11), `GET_SCRIPT_TASK_STATUS` (11), `SET_MODEL_AS_NO_LONGER_NEEDED` (10), `REMOVE_BLIP` (9), `DOES_CAM_EXIST` (9), `RENDER_SCRIPT_CAMS` (9), `GET_PLAYER_WANTED_LEVEL` (9), `DOES_ENTITY_EXIST` (8), `ARE_STRINGS_EQUAL` (8), `IS_SYNCHRONIZED_SCENE_RUNNING` (8), `CREATE_SYNCHRONIZED_SCENE` (8), `CLEAR_SEQUENCE_TASK` (7), `OPEN_SEQUENCE_TASK` (7), `CLOSE_SEQUENCE_TASK` (7), `TASK_PERFORM_SEQUENCE` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x7 · `4.79f` x3 · `0.1f` x2 · `7.5f` x2 · `1.5f` x2 · `299.3585f` x2 · `-3204.905f` x2 · `4.7214f` x2 · `204.8445f` x2 · `-3333.998f` x2 · `4.795367f` x2 · `212.67f` x2 · `-3328.77f` x2 · `204.8248f` x2 · `-3328.631f` x2 · `4.7915f` x2 · `214.2505f` x2 · `-3314.673f` x2 · `4.7883f` x2 · `220.7266f` x2 · `-3320.001f` x2 · `5.2749f` x2 · `195.16f` x1 · `-3282.54f` x1

## Other strings

Literals whose consuming native was not classified:

`txm12_deal1_7`, `TAXI_FAIL`, `TAXI_OBJ_FAIL`, `TAXI_OBJ_F_SPT`, `Taxi Not Driveable`, `TAXI_OBJ_F_SPK`, `_shot1`, `_noDri2`, `_noDri1`, `You had a dead body in your back seat.`, `player`, `gburrito`, `hexer`, `TAXI_SC_BN_12`, `Player abandoned passenger`, `_aband2`, `_aband1`, `TAXI_VIEW`, `MotionState_Sprint`, `CamPushInNeutral`, `FIRING_PATTERN_FULL_AUTO`, `TAXI_OBJ_POL`, `TAXI_ASSETS_STREAMED - Loading A_M_M_Farmer_01`, `TAXI_ASSETS_STREAMED - Loading shared assets`, `TRS_STREAMING`, ` TRS_FINDING_LOCATION `, ` TRS_SPAWNING `, ` TRS_SPAWN_CAR `, ` TRS_MANAGE_PICKUP `, ` TRS_PASSENGER_ENTER `

---

Source: `decompiled_scripts/taxi_gotyourback.c`
