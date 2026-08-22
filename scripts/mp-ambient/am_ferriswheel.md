# am_ferriswheel.c

MP ambient script. 1 anim dicts; 2 models; 1 scaleforms.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 9,779 |
| Functions | 210 (61 unique, 149 shared) |
| Unique lines | 1,794 (18.3% of file) |

## Assets

**Animation dictionaries** (1) - `anim@mp_ferris_wheel`

**Models and props** (2) - `prop_ld_ferris_wheel`, `prop_ferris_car_01`

**Audio banks** (2) - `SCRIPT\FERRIS_WHALE_01`, `SCRIPT\FERRIS_WHALE_02`

**Sounds** (7) - `FAIRGROUND_RIDES_FERRIS_WHALE`, `FAIRGROUND_RIDES_FERRIS_WHALE_ALTERNATIVE_VIEW`, `THE_FERRIS_WHALE_SOUNDSET`, `SLOW_SQUEAK`, `GENERATOR`, `CARRIAGE`, `HEIGHT`

**Scaleform movies** (1) - `instructional_buttons`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PARTICIPANT_ID_TO_INT` (83), `PLAYER_PED_ID` (55), `CLEAR_BIT` (37), `SET_BIT` (31), `PLAYER_ID` (24), `GET_EVENT_DATA` (10), `_SEND_TU_SCRIPT_EVENT_NEW` (9), `IS_AUDIO_SCENE_ACTIVE` (9), `IS_ENTITY_AT_COORD` (7), `STOP_AUDIO_SCENE` (7), `IS_CONTROL_JUST_PRESSED` (6), `GET_ENTITY_COORDS` (6), `DOES_CAM_EXIST` (6), `GET_CONTROL_NORMAL` (6), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (5), `CLEAR_HELP` (5), `IS_NEW_LOAD_SCENE_ACTIVE` (4), `GET_PLAYER_PED` (4), `SET_ENTITY_COORDS` (4), `NETWORK_ALLOW_REMOTE_ATTACHMENT_MODIFICATION` (4), `GET_SOUND_ID` (4), `PLAY_SOUND_FROM_ENTITY` (4), `INT_TO_PARTICIPANTINDEX` (3), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (3), `IS_PED_IN_ANY_VEHICLE` (3), `NETWORK_CREATE_SYNCHRONISED_SCENE` (3), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (3), `NETWORK_START_SYNCHRONISED_SCENE` (3), `DETACH_ENTITY` (3), `SET_ENTITY_LOD_DIST` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`12.6973f` x9 · `-1661.95f` x5 · `-1127.011f` x5 · `0.5f` x4 · `0.1f` x3 · `-1666.711f` x2 · `-1127.518f` x2 · `0.2f` x2 · `-0.25f` x2 · `-1645.555f` x1 · `-1123.872f` x1 · `17.3436f` x1 · `-1662.01f` x1 · `-1126.869f` x1 · `-1666.383f` x1 · `-1126.286f` x1 · `98.6981f` x1 · `0.99f` x1 · `15.3f` x1 · `-15.3f` x1

## Other strings

Literals whose consuming native was not classified:

`one`, `two`, `MISSFINALE_C2IG_5`, `AMFW_WAIT_OFF`, `AMFW_WAIT`, `AMFW_ENTER`, `AMFW_GET_OUT`, `AMFW_GET_IN`, `AMFW_GET_IN_P`, `AMFW_CAR_FULL`, `ferris_finale_Anim`, `exit_player_`, `enter_player_`, `idle_a_player_`, `AMFW_BTNCV`, `AMFW_BTNEX`, `DEFAULT_SCRIPTED_CAMERA`, `service_spend_fairground`, `fairgroundHub`

---

Source: `decompiled_scripts/am_ferriswheel.c`
