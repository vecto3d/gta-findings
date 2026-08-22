# re_arrests.c

Random events script. 12 developer state labels recovered; 4 anim dicts; 9 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 8,606 |
| Functions | 207 (35 unique, 172 shared) |
| Unique lines | 2,459 (28.6% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`copChasesCriminal` · `copChasesCriminal TIMERA() < 2000` · `criminal_thanks 8` · `criminal_thanks 9` · `criminal_thanks 0` · `criminal_thanks 1` · `criminal_thanks 2` · `criminal_thanks 3` · `criminal_thanks 4` · `criminal_thanks 7` · `criminal_thanks 5` · `criminal_thanks 6`

## Assets

**Animation dictionaries** (4) - `MOVE_M@BAIL_BOND_TAZERED`, `MOVE_M@BAIL_BOND_NOT_TAZERED`, `RANDOM@ARRESTS`, `RANDOM@ARRESTS@BUSTED`

**Animations** (10) - `kneeling_arrest_idle`, `kneeling_arrest_get_up`, `enter`, `exit`, `radio_chatter`, `radio_exit`, `Thanks_Male_05`, `kneeling_arrest_escape`, `idle_2_hands_up`, `radio_enter`

**Models and props** (9) - `prop_ld_binbag_01`, `s_m_y_ranger_01`, `s_f_y_cop_01`, `s_m_y_cop_01`, `S_M_Y_RANGER_01_WHITE_FULL_01`, `A_M_M_HillBilly_02_WHITE_MINI_02`, `a_m_m_hillbilly_02`, `G_M_M_ArmGoon_01_White_Armenian_MINI_01`, `g_m_m_armgoon_01`

**Text labels** (6) - `REARRAU`, `NULL`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `COP`

**Relationship groups** (2) - `RE_ARREST_COP`, `RE_ARREST_CRIM`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (80), `IS_PED_INJURED` (65), `GET_ENTITY_COORDS` (31), `IS_ENTITY_AT_ENTITY` (23), `SET_PED_KEEP_TASK` (22), `GET_GAME_TIMER` (22), `OPEN_SEQUENCE_TASK` (21), `CLOSE_SEQUENCE_TASK` (21), `TASK_PERFORM_SEQUENCE` (21), `CLEAR_SEQUENCE_TASK` (21), `DOES_BLIP_EXIST` (21), `TASK_PLAY_ANIM` (18), `GET_SCRIPT_TASK_STATUS` (17), `PLAYER_ID` (16), `CLEAR_PED_TASKS` (16), `IS_VEHICLE_DRIVEABLE` (15), `DRAW_DEBUG_TEXT_2D` (12), `TASK_SMART_FLEE_PED` (12), `IS_ENTITY_PLAYING_ANIM` (12), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (12), `IS_ENTITY_DEAD` (11), `DOES_ENTITY_EXIST` (11), `SET_RELATIONSHIP_BETWEEN_GROUPS` (10), `WAIT` (9), `TASK_LOOK_AT_ENTITY` (8), `IS_ENTITY_TOUCHING_ENTITY` (8), `SET_PED_COMBAT_ATTRIBUTES` (8), `TASK_GO_TO_ENTITY` (7), `IS_PED_RAGDOLL` (7), `REMOVE_BLIP` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.02f` x12 · `0.1f` x12 · `0.5f` x5 · `3.5f` x4 · `2411.32f` x2 · `4958.76f` x2 · `45.19f` x2 · `2551.038f` x2 · `4708.613f` x2 · `32.6775f` x2 · `2536.979f` x2 · `5022.179f` x2 · `43.8519f` x2 · `0.01f` x2 · `0.25f` x2 · `-1.5f` x2 · `36.9446f` x2 · `2.5f` x2 · `-0.5f` x2 · `194.75f` x2 · `1.5f` x1 · `0.75f` x1 · `2528.563f` x1 · `2639.115f` x1

## Other strings

Literals whose consuming native was not classified:

`REARR_PLEAVE`, `REARR_PRA2`, `REARR_CRAND`, `REARR_CRAND2`, `FIRING_PATTERN_FULL_AUTO`, `REARR_PWTF`, `REARR_PRAND`, `REARR_PRAD3`, `REARR_PTHANK`, `REARR_PHELP`, `MotionState_Run`, `player`, `REARR_PCUFF`, `REARR_INCAR`, `radio_enter`, `radio_chatter`, `radio_exit`, `generic_radio_enter`, `generic_radio_chatter`, `generic_radio_exit`, `REARR_PRAD1`, `REARR_PRAD2`, `idle_a`, `idle_b`, `idle_c`, `pranger`, `REARR_PORUN`, `bulldozer`, `vehicle_weapon_tank`, `REARR_PSTOP`

---

Source: `decompiled_scripts/re_arrests.c`
