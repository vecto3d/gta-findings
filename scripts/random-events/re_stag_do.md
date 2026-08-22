# re_stag_do.c

Random events script. 2 anim dicts; 8 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 9,310 |
| Functions | 220 (21 unique, 199 shared) |
| Unique lines | 2,367 (25.4% of file) |

## Assets

**Animation dictionaries** (2) - `re@stag_do@`, `re@stag_do@idle_a`

**Animations** (5) - `re@stag_do@`, `untie_ped`, `untie_player`, `re@stag_do@idle_a`, `idle_a_ped`

**Models and props** (8) - `ig_bestmen`, `ig_bride`, `washington`, `u_m_y_staggrm_01`, `prop_stag_do_rope`, `baller2`, `primo`, `superd`

**Audio banks** (1) - `ROPE_CUT`

**Sounds** (7) - `HUD_MINI_GAME_SOUNDSET`, `10_SEC_WARNING`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `TIMER_STOP`, `ROPE_CUT`, `ROPE_CUT_SOUNDSET`

**Speech contexts** (1) - `GROOM`

**Text labels** (6) - `NULL`, `BESTMAN`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `GROOM`

**Relationship groups** (1) - `player`

**Vehicle mods** (1) - `superd`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (131), `IS_PED_INJURED` (61), `IS_ENTITY_DEAD` (35), `GET_PLAYERS_LAST_VEHICLE` (33), `IS_PED_IN_ANY_VEHICLE` (26), `DOES_BLIP_EXIST` (26), `WAIT` (20), `IS_ENTITY_AT_ENTITY` (20), `DISABLE_CONTROL_ACTION` (16), `PLAY_SOUND_FRONTEND` (16), `IS_PED_IN_VEHICLE` (14), `PLAYER_ID` (13), `REMOVE_BLIP` (12), `GET_VEHICLE_PED_IS_IN` (12), `TASK_LOOK_AT_ENTITY` (12), `OPEN_SEQUENCE_TASK` (12), `CLOSE_SEQUENCE_TASK` (12), `TASK_PERFORM_SEQUENCE` (12), `SET_PED_COMPONENT_VARIATION` (12), `CLEAR_SEQUENCE_TASK` (11), `GET_ENTITY_COORDS` (10), `GET_ENTITY_MODEL` (10), `IS_PED_IN_GROUP` (9), `GET_SCRIPT_TASK_STATUS` (9), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (9), `TASK_SMART_FLEE_PED` (8), `IS_ENTITY_AT_COORD` (8), `REQUEST_MODEL` (8), `HAS_MODEL_LOADED` (8), `DOES_ENTITY_EXIST` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x6 · `10.5f` x4 · `13.5f` x3 · `-2202.747f` x3 · `4299.008f` x3 · `47.4293f` x3 · `-330.36f` x3 · `-0.037031f` x2 · `29.00143f` x2 · `6154.03f` x2 · `-935.57f` x2 · `2767.616f` x2 · `24.448f` x2 · `24.4289f` x2 · `101.6406f` x2 · `455.1994f` x2 · `-2007.751f` x2 · `31.8f` x2 · `-2002.008f` x1 · `455.58f` x1 · `101.0381f` x1 · `-2009.761f` x1 · `453.2027f` x1 · `105.9135f` x1

## Other strings

Literals whose consuming native was not classified:

`stagdau`, `stagd_stress`, `superd`, `stagdwrcar`, `rhino`, `Groom`, `Groomsman`, `Bride`, `Father_of_the_bride`, `stagd_nogood`, `DEFAULT_SCRIPTED_CAMERA`, `HAND_SHAKE`, `CamPushInNeutral`, `stagd_bump1`, `stagd_greet2`, `RE_SDRM`, `sdrm_mcs_2`, `stagd_police`, `towtruck`, `towtruck2`, `stagd_comeba`, `stagd_nobest`, `SDRM_Car`, `stagd_nogood_1`, `stagd_nogood_2`, `stagd_chape_1`, `stagd_chape_3`, `stagd_tailM`, `stagd_tailF`, `stagd_tailT`

---

Source: `decompiled_scripts/re_stag_do.c`
