# thelastone.c

SP missions script. 1 anim dicts; 22 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 47,890 |
| Functions | 526 (71 unique, 455 shared) |
| Unique lines | 2,953 (6.2% of file) |

## Assets

**Animation dictionaries** (1) - `rcmlastone1`

**Animations** (9) - `hunter_leadout`, `hunter_idle`, `hunter_idle_action`, `hunter_idle_look`, `tlo_leap_out`, `leadout_sas_3_rcm_sas`, `sas_idle_sit`, `rcmlastone1`, `idle_action_01`

**Models and props** (22) - `ig_hunter`, `prop_crate_07a`, `a_c_mtlion`, `ig_orleans`, `prop_big_shit_02`, `a_c_boar`, `a_c_chickenhawk`, `a_c_chimp`, `a_c_chop`, `a_c_cormorant`, `a_c_cow`, `a_c_coyote`, `a_c_crow`, `a_c_deer`, `a_c_hen`, `a_c_pig`, `a_c_pigeon`, `a_c_rat`, `a_c_retriever`, `a_c_rhesus`, `a_c_rottweiler`, `a_c_seagull`

**Audio banks** (3) - `SCRIPT\SAS_BANK_01`, `SCRIPT\SAS_BANK_02`, `SAS_BANK_03`

**Sounds** (6) - `SASQUATCH_01_SOUNDSET`, `SASQUATCH_MIX`, `WOUNDED`, `ALERT`, `RUNNING`, `COUGH`

**Text labels** (7) - `SAS1AUD`, `FRANKLIN`, `ORLEANS`, `HUNTER`, `NULL`, `EMPTY`, `SAS1`

**Scenarios** (2) - `WORLD_HUMAN_HIKER`, `WORLD_MOUNTAIN_LION_WANDER`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (91), `GET_GAME_TIMER` (43), `WAIT` (20), `GET_ENTITY_COORDS` (19), `DOES_ENTITY_EXIST` (14), `REQUEST_MODEL` (13), `HAS_SOUND_FINISHED` (12), `TASK_PLAY_ANIM` (12), `CLEAR_AREA` (10), `IS_PED_IN_ANY_VEHICLE` (10), `HAS_MODEL_LOADED` (9), `SET_ENTITY_HEALTH` (8), `REPLAY_RECORD_BACK_FOR_TIME` (8), `HAS_PED_GOT_WEAPON` (8), `SET_PED_COMPONENT_VARIATION` (7), `SET_MODEL_AS_NO_LONGER_NEEDED` (7), `HAS_ANIM_DICT_LOADED` (7), `REQUEST_ANIM_DICT` (7), `PLAYER_ID` (7), `SET_ENTITY_COORDS` (6), `PLAY_SOUND_FROM_ENTITY` (6), `IS_ENTITY_DEAD` (6), `DOES_BLIP_EXIST` (6), `SET_BLIP_ALPHA` (6), `REGISTER_ENTITY_FOR_CUTSCENE` (5), `CLEAR_PRINTS` (5), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (5), `CREATE_PED` (5), `SET_PED_CAN_BE_TARGETTED` (5), `GIVE_WEAPON_TO_PED` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-36.1791f` x2 · `0.2f` x2 · `1.5f` x2 · `-1536.6f` x1 · `4543.7f` x1 · `45.5f` x1 · `-1538.2f` x1 · `4536.2f` x1 · `48.6f` x1 · `0.5f` x1 · `0.81f` x1 · `0.733f` x1 · `-1541.965f` x1 · `4692.725f` x1 · `44.0651f` x1 · `-1518.762f` x1 · `4540.353f` x1 · `44.5008f` x1 · `95.2894f` x1 · `0.9f` x1 · `0.6f` x1 · `-1295.844f` x1 · `4641.988f` x1 · `105.3325f` x1

## Other strings

Literals whose consuming native was not classified:

`sas_2_rcm_t7`, `SF_TheLastOne`, `AZ_DISTANT_SASQUATCH`, `sas_1_rcm_concat`, `Orleans`, `SAS1_LEADOUT`, `dune`, `Kill Sasquatch`, `SAS1_START1`, `player`, `Franklin`, `Hunter`, `CamPushInNeutral`, `rcmlastone1`, `rcmlastone2leadinout`, `SAS1_X0`, `SAS1_X1`, `SAS1_X6`, `Chase`, `SAS1_C1`, `SAS1_H0`, `SAS1_CHASE1b`, `SAS1_CHASE3`, `SAS1_C2`, `SAS1_CHASE2`, `SAS1_MISS`, `Force cleanup [TERMINATING]`, `SAS1_RUNS`, `Hunnter dead`, `SAS1_LO`

---

Source: `decompiled_scripts/thelastone.c`
