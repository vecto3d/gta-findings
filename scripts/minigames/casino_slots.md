# casino_slots.c

Minigames script. 2 anim dicts; 5 models; 5 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 15,840 |
| Functions | 380 (90 unique, 290 shared) |
| Unique lines | 6,088 (38.4% of file) |

## Assets

**Animation dictionaries** (2) - `anim_casino_a@amb@casino@games@slots@female`, `anim_casino_a@amb@casino@games@slots@male`

**Models and props** (5) - `vw_Prop_Casino_Slot_0`, `vw_prop_casino_slot_0`, `vw_Prop_vw_slot_wheel_0`, `Vw_prop_casino_slot_0`, `vw_prop_vw_slot_wheel_0`

**Sounds** (18) - `dlc_vw_casino_slot_machines_playing`, `dlc_vw_table_games_frontend_sounds`, `no_win`, `small_win`, `big_win`, `jackpot`, `place_bet`, `place_max_bet`, `spinning`, `start_spin`, `wheel_stop_clunk`, `wheel_stop_on_prize`, `welcome_stinger`, `spin_wheel`, `spin_wheel_win`, `DLC_VW_CONTINUE`, `DLC_VW_RULES`, `attract_loop`

**Scaleform movies** (5) - `SLOT_MACHINE`, `SET_LAST_WIN`, `SET_MESSAGE`, `SET_BET`, `SET_THEME`

**Text labels** (2) - `PREV`, `NULL`

**Hashed names** (3) - `win cutoff`, `loss cutoff`, `time cutoff`

## Native vocabulary

Most-called natives inside the code unique to this script:

`CLEAR_BIT` (118), `PLAYER_ID` (100), `SET_BIT` (69), `PLAYER_PED_ID` (58), `DOES_ENTITY_EXIST` (36), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (20), `SET_ENTITY_ROTATION` (20), `GET_RANDOM_INT_IN_RANGE` (18), `HAS_ANIM_EVENT_FIRED` (18), `PLAY_SOUND_FROM_COORD` (14), `PLAY_SOUND_FROM_ENTITY` (13), `GET_PLAYER_PED` (13), `GET_HASH_KEY` (12), `GET_ENTITY_COORDS` (12), `SET_ENTITY_COORDS` (12), `SET_INPUT_EXCLUSIVE` (10), `TO_FLOAT` (9), `GET_CAM_VIEW_MODE_FOR_CONTEXT` (9), `IS_CONTROL_JUST_RELEASED` (9), `IS_HELP_MESSAGE_BEING_DISPLAYED` (9), `DISABLE_CONTROL_ACTION` (8), `IS_DISABLED_CONTROL_JUST_RELEASED` (8), `DELETE_OBJECT` (8), `FLOOR` (7), `IS_CONTROL_JUST_PRESSED` (7), `IS_PLAYER_SWITCH_IN_PROGRESS` (6), `TIMESTEP` (6), `FORCE_ROOM_FOR_ENTITY` (6), `GET_INTERIOR_FROM_ENTITY` (6), `GET_ROOM_KEY_FROM_ENTITY` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.047f` x6 · `0.906f` x6 · `0.99f` x4 · `22.5f` x4 · `-1.5f` x3 · `-0.4f` x3 · `0.2f` x2 · `0.24f` x2 · `0.01f` x2 · `0.0579063f` x2 · `-0.256112f` x2 · `-0.197113f` x2 · `0.0289372f` x2 · `-1.85613f` x2 · `2.75002f` x2 · `-0.6f` x2 · `1.25f` x2 · `-0.12f` x2 · `1.6f` x2 · `-0.115f` x2 · `0.005f` x2 · `0.125f` x2 · `0.401f` x1 · `0.09f` x1

## Other strings

Literals whose consuming native was not classified:

`CAS_MG_MEMB2`, `CAS_MG_CTIME`, `CAS_MG_CBAN`, `SLOTS_FAILTR`, `AMMO_PISTOL`, `AMMO_SMG`, `AMMO_SHOTGUN`, `AMMO_RIFLE`, `SLOTS_USED`, `machine_0`, `SLOTS_NOMON`, `standard`, `win`, `lose`, `SLOTS_REGBAN`, `CAS_MG_NOCHIPS1`, `CAS_MG_LOWCHIPS1`, `SLOTS_ENTERB`, `SLOTS_EXIT`, `start_spin`, `SLOT MACHINE RP`, `CLO_VWM_DECL_27`, `CLO_VWF_DECL_27`, `CLO_VWM_DECL_28`, `CLO_VWF_DECL_28`, `CLO_VWM_DECL_33`, `CLO_VWF_DECL_33`, `CLO_VWM_DECL_34`

---

Source: `decompiled_scripts/casino_slots.c`
