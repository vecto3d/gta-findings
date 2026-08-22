# re_burials.c

Random events script. 1 anim dicts; 6 models; 1 particle effects.

| | |
|---|---|
| Category | Random events |
| Total lines | 9,336 |
| Functions | 224 (36 unique, 188 shared) |
| Unique lines | 2,888 (30.9% of file) |

## Assets

**Animation dictionaries** (1) - `random@burial`

**Animations** (7) - `random@burial`, `a_burial`, `a_burial_stop`, `b_burial`, `untie_ped`, `untie_player`, `c_burial`

**Models and props** (6) - `p_arm_bind_cut_s`, `prop_ld_shovel`, `s_m_m_highsec_01`, `granger`, `a_m_m_salton_01`, `u_f_y_mistress`

**Audio banks** (1) - `ROPE_CUT`

**Sounds** (4) - `ROPE_CUT`, `ROPE_CUT_SOUNDSET`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Speech contexts** (3) - `A_M_M_HillBilly_02_WHITE_MINI_03`, `A_M_M_HillBilly_02_WHITE_MINI_02`, `KIDNAPPEDFEMALE`

**Particle effects** (1) - `scr_burial_dirt`

**Text labels** (7) - `REBU2AU`, `NULL`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `KIDNAPPER2`, `KIDNAPPER1`

**Scenarios** (1) - `WORLD_HUMAN_HANG_OUT_STREET`

**Relationship groups** (2) - `rghKidnappers`, `rghVictim`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (154), `IS_PED_INJURED` (78), `GET_GAME_TIMER` (42), `DOES_ENTITY_EXIST` (30), `WAIT` (28), `GET_PLAYERS_LAST_VEHICLE` (28), `DOES_BLIP_EXIST` (26), `SET_PED_KEEP_TASK` (25), `IS_ENTITY_DEAD` (19), `IS_ENTITY_AT_ENTITY` (17), `IS_ENTITY_AT_COORD` (16), `REQUEST_MODEL` (15), `GET_ENTITY_ANIM_CURRENT_TIME` (15), `IS_PED_IN_ANY_VEHICLE` (14), `OPEN_SEQUENCE_TASK` (14), `CLOSE_SEQUENCE_TASK` (14), `TASK_PERFORM_SEQUENCE` (14), `CLEAR_SEQUENCE_TASK` (14), `REMOVE_BLIP` (13), `GET_RANDOM_INT_IN_RANGE` (13), `IS_PED_IN_GROUP` (12), `PLAYER_ID` (12), `GET_SCRIPT_TASK_STATUS` (12), `DETACH_ENTITY` (10), `IS_VEHICLE_DRIVEABLE` (10), `TASK_TURN_PED_TO_FACE_ENTITY` (10), `IS_ENTITY_ATTACHED` (9), `SET_PED_COMPONENT_VARIATION` (9), `GET_VEHICLE_PED_IS_IN` (9), `CLEAR_PED_TASKS` (9)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`194.3872f` x7 · `6833.941f` x7 · `62.4419f` x7 · `131.3547f` x7 · `6845.673f` x7 · `15.4613f` x7 · `36.9375f` x7 · `1.5f` x4 · `0.355f` x4 · `0.5f` x4 · `-133.841f` x3 · `-38.5734f` x3 · `-126.2403f` x3 · `-29.194f` x3 · `-0.5f` x2 · `0.25f` x2 · `1.2f` x2 · `-0.95f` x2 · `2.75f` x2 · `281.9148f` x1 · `6816.345f` x1 · `4.3197f` x1 · `48.3924f` x1 · `6885.921f` x1

## Other strings

Literals whose consuming native was not classified:

`player`, `REBU2_HPF`, `REBU2_ATT`, `FIRING_PATTERN_FULL_AUTO`, `REBU2_PD`, `RE6_BOTH_DEAD_OS`, `rhino`, `REBU2_CRAZY`, `GENERIC_WAR_CRY`, `GENERIC_SHOCKED_HIGH`, `REBU2_WV`, `REBU2_CULT`, `REBU2_NEAR`, `b_burial_legstie`, `b_burial_wristtie`, `RE6_END`, `REBU2_BACK`, `REBU2_LV2`, `REBU2_UNS1`, `REBU2_UNS2`, `REBU2_GETOUT`, `REBU2_JACK`, `REBU2_SHOOT`, `RE6_START`, `RE_BU`, `granger`, `RE6_BOTH_DEAD`, `REBU2_DOOR0`, `REBU2_DOOR1`, `REBU2_DOOR2`

---

Source: `decompiled_scripts/re_burials.c`
