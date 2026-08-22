# am_mp_boardroom_seating.c

Seating and sitting script. 38 anim dicts.

| | |
|---|---|
| Category | Seating and sitting |
| Total lines | 417,197 |
| Functions | 7,427 (79 unique, 7,348 shared) |
| Unique lines | 13,892 (3.3% of file) |

## Assets

**Animation dictionaries** (38) - `anim@amb@clubhouse@boardroom@crew@female@var_a@base@`, `anim@amb@clubhouse@boardroom@crew@female@var_a@base_l@`, `anim@amb@clubhouse@boardroom@crew@female@var_a@base_r@`, `anim@amb@clubhouse@boardroom@crew@female@var_b@base@`, `anim@amb@clubhouse@boardroom@crew@female@var_b@base_l@`, `anim@amb@clubhouse@boardroom@crew@female@var_b@base_r@`, `anim@amb@clubhouse@boardroom@crew@female@var_c@base@`, `anim@amb@clubhouse@boardroom@crew@female@var_c@base_l@`, `anim@amb@clubhouse@boardroom@crew@female@var_c@base_r@`, `anim@amb@clubhouse@boardroom@crew@male@var_a@base@`, `anim@amb@clubhouse@boardroom@crew@male@var_a@base_l@`, `anim@amb@clubhouse@boardroom@crew@male@var_a@base_r@`, `anim@amb@clubhouse@boardroom@crew@male@var_b@base@`, `anim@amb@clubhouse@boardroom@crew@male@var_b@base_l@`, `anim@amb@clubhouse@boardroom@crew@male@var_b@base_r@`, `anim@amb@clubhouse@boardroom@crew@male@var_c@base@`, `anim@amb@clubhouse@boardroom@crew@male@var_c@base_l@`, `anim@amb@clubhouse@boardroom@crew@male@var_c@base_r@`, `anim@amb@office@boardroom@boss@female@`, `anim@amb@office@boardroom@crew@female@var_a@base@`, `anim@amb@office@boardroom@crew@female@var_a@base_l@`, `anim@amb@office@boardroom@crew@female@var_a@base_r@`, `anim@amb@office@boardroom@crew@female@var_b@base@`, `anim@amb@office@boardroom@crew@female@var_b@base_l@`, `anim@amb@office@boardroom@crew@female@var_b@base_r@`, `anim@amb@office@boardroom@crew@female@var_c@base@`, `anim@amb@office@boardroom@crew@female@var_c@base_l@`, `anim@amb@office@boardroom@crew@female@var_c@base_r@`, `anim@amb@office@boardroom@boss@male@`, `anim@amb@office@boardroom@crew@male@var_a@base@`, `anim@amb@office@boardroom@crew@male@var_a@base_l@`, `anim@amb@office@boardroom@crew@male@var_a@base_r@`, `anim@amb@office@boardroom@crew@male@var_b@base@`, `anim@amb@office@boardroom@crew@male@var_b@base_l@`, `anim@amb@office@boardroom@crew@male@var_b@base_r@`, `anim@amb@office@boardroom@crew@male@var_c@base@`, `anim@amb@office@boardroom@crew@male@var_c@base_l@`, `anim@amb@office@boardroom@crew@male@var_c@base_r@`

**Text labels** (1) - `NULL`

**Hashed names** (4) - `bkr_prop_clubhouse_chair_01`, `tr_Prop_Tr_Chair_01a`, `M25_2_PROP_M52_DiningChair_01a`, `vw_prop_vw_offchair_01`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (53), `NET_TO_OBJ` (46), `REMOVE_ANIM_DICT` (39), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (16), `NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE` (16), `GET_ENTITY_COORDS` (13), `CLEAR_BIT` (13), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (11), `NETWORK_START_SYNCHRONISED_SCENE` (10), `IS_PED_INJURED` (10), `NETWORK_CREATE_SYNCHRONISED_SCENE` (10), `GET_ENTITY_ROTATION` (10), `SET_BIT` (9), `TASK_CLEAR_LOOK_AT` (7), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (5), `REQUEST_ANIM_DICT` (5), `HAS_ANIM_DICT_LOADED` (5), `IS_USING_KEYBOARD_AND_MOUSE` (4), `NETWORK_DOES_NETWORK_ID_EXIST` (4), `GET_HASH_KEY` (4), `CLEAR_HELP` (4), `NETWORK_REQUEST_CONTROL_OF_NETWORK_ID` (4), `GET_SYNCHRONIZED_SCENE_PHASE` (4), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (4), `NETWORK_IS_GAME_IN_PROGRESS` (3), `GET_ANIM_INITIAL_OFFSET_POSITION` (3), `GET_ANIM_INITIAL_OFFSET_ROTATION` (3), `SET_ENTITY_COORDS_NO_OFFSET` (3), `IS_PED_HEADTRACKING_ENTITY` (3), `GET_PLAYER_PED` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x3 · `1563.378f` x1 · `388.8997f` x1 · `-54.2859f` x1 · `0.17f` x1 · `0.02f` x1

## Other strings

Literals whose consuming native was not classified:

`base`, `base_chair`, `enter_chair`, `MPJAC_NO_SIT`, `enter`, `idle_a`, `idle_a_chair`, `exit`, `exit_chair`, `idle_d`, `idle_d_chair`, `idle_e`, `idle_e_chair`, `idle_b`, `idle_b_chair`, `idle_c`, `idle_c_chair`, `exit_seat`, `exit_seat_chair`, `MPOFSEAT_PCEXIT`, `FHQ_BR_TV_PC`, `MPOFSEAT_EX_PCC`, `packed_mp_veh_mod_idx_7_v106`, `MPJAC_SIT`, `enter_b`, `enter_b_chair`, `MPOFSEAT_EXIT`, `FHQ_BR_TV`, `MPOFSEAT_EXIT_C`, `exit_b`

---

Source: `decompiled_scripts/am_mp_boardroom_seating.c`
