# am_rollercoaster.c

Minigames script. 1 anim dicts; 2 models; 1 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 9,693 |
| Functions | 247 (57 unique, 190 shared) |
| Unique lines | 2,227 (23.0% of file) |

## Assets

**Animation dictionaries** (1) - `anim@mp_rollarcoaster`

**Animations** (6) - `hands_up_enter_player_one`, `hands_up_enter_player_two`, `hands_up_exit_player_one`, `hands_up_exit_player_two`, `hands_up_idle_a_player_one`, `hands_up_idle_a_player_two`

**Models and props** (2) - `ind_prop_dlc_roller_car`, `ind_prop_dlc_roller_car_02`

**Sounds** (4) - `DLC_IND_ROLLERCOASTER_SOUNDS`, `Bar_Unlock_And_Raise`, `Ride_Stop`, `Bar_Lower_And_Lock`

**Scaleform movies** (1) - `instructional_buttons`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PARTICIPANT_ID_TO_INT` (87), `PLAYER_PED_ID` (52), `CLEAR_BIT` (35), `SET_BIT` (35), `PLAYER_ID` (22), `IS_ENTITY_PLAYING_ANIM` (15), `_SEND_TU_SCRIPT_EVENT_NEW` (7), `GET_EVENT_DATA` (7), `GET_CONTROL_INSTRUCTIONAL_BUTTONS_STRING` (6), `IS_ENTITY_AT_COORD` (5), `TASK_PLAY_ANIM` (5), `NETWORK_IS_PARTICIPANT_ACTIVE` (4), `INT_TO_PARTICIPANTINDEX` (4), `STOP_STREAM` (4), `IS_HELP_MESSAGE_BEING_DISPLAYED` (4), `PLAY_SOUND_FROM_ENTITY` (4), `NETWORK_CREATE_SYNCHRONISED_SCENE` (4), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (4), `NETWORK_START_SYNCHRONISED_SCENE` (4), `NETWORK_ALLOW_REMOTE_ATTACHMENT_MODIFICATION` (4), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (3), `GET_PLAYER_PED` (3), `PLAY_ENTITY_ANIM` (3), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (3), `GET_SYNCHRONIZED_SCENE_PHASE` (3), `SET_SCALEFORM_MOVIE_AS_NO_LONGER_NEEDED` (3), `ATTACH_ENTITY_TO_ENTITY` (3), `GET_NETWORK_TIME_ACCURATE` (3), `GET_ENTITY_ANIM_CURRENT_TIME` (3), `REQUEST_MODEL` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.3f` x5 · `139.96f` x5 · `0.99f` x5 · `1.5f` x2 · `0.2f` x2 · `-1645.555f` x1 · `-1123.872f` x1 · `17.3436f` x1 · `-1649.667f` x1 · `-1129.053f` x1 · `17.3438f` x1 · `332.318f` x1 · `-1659.01f` x1 · `-1143.129f` x1 · `17.4192f` x1 · `-1622.154f` x1 · `-1089.806f` x1 · `4.336f` x1 · `57.5266f` x1 · `-1652.717f` x1 · `-1089.217f` x1 · `12.1492f` x1 · `229.3511f` x1

## Other strings

Literals whose consuming native was not classified:

`one`, `two`, `AMRC_CINEMATIC`, `AMRC_CHANGEVIEW`, `DLC_IND_ROLLERCOASTER_SOUNDS`, `AMRC_TIMER`, `sanchez`, `AMRC_ENTER`, `service_spend_fairground`, `rollercoaster`, `AMRC_HELPTEXT`, `safety_bar_exit_roller_car`, `safety_bar_exit_player_`, `exit_player_`, `hands_up_enter_player_`, `hands_up_idle_a_player_`, `hands_up_exit_player_`, `safety_bar_grip_move_a_player_`, `AMRC_SCRM_L`, `AMRC_SCRM_R`, `AMRC_HANDSLOWER`, `AMRC_HANDSRAISE`, `safety_bar_enter_roller_car`, `safety_bar_enter_player_`, `Player_Ride`, `Ambient_Ride`, `enter_player_`, `idle_a_player_`, `ind_prop_dlc_roller_car`, `ind_prop_dlc_roller_car_02`

---

Source: `decompiled_scripts/am_rollercoaster.c`
