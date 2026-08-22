# re_crashrescue.c

Random events script. 7 anim dicts; 3 models; 1 particle effects.

| | |
|---|---|
| Category | Random events |
| Total lines | 37,513 |
| Functions | 339 (32 unique, 307 shared) |
| Unique lines | 1,948 (5.2% of file) |

## Assets

**Animation dictionaries** (7) - `RANDOM@CRASH_RESCUE@WOUNDED@BASE`, `RANDOM@CRASH_RESCUE@HELP_VICTIM_UP`, `random@crash_rescue@dead_ped`, `RANDOM@CRASH_RESCUE@CAR_DEATH@LOW_CAR`, `RANDOM@CRASH_RESCUE@CAR_DEATH@STD_CAR`, `RANDOM@CRASH_RESCUE@CAR_DEATH@VAN`, `random@crash_rescue@get_victim_to_friend`

**Animations** (9) - `helping_friend_idle_friend`, `HELPING_VICTIM_TO_FEET_PLAYER`, `HELPING_VICTIM_TO_FEET_VICTIM`, `idle_intro`, `helping_friend_inside_victim`, `helping_friend_inside_friend`, `BASE`, `dead_ped`, `LOOP`

**Models and props** (3) - `prop_skid_chair_01`, `a_m_m_eastsa_02`, `ig_talina`

**Sounds** (2) - `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Particle effects** (1) - `scr_recrash_rescue_fire`

**Text labels** (7) - `RECRAAU`, `NULL`, `TALINA`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `FEED_CREW_U`

**Relationship groups** (1) - `player`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (69), `GET_GAME_TIMER` (27), `IS_PED_INJURED` (17), `GET_VEHICLE_PED_IS_IN` (10), `IS_PED_IN_ANY_VEHICLE` (9), `DOES_BLIP_EXIST` (9), `REQUEST_ANIM_DICT` (8), `PLAYER_ID` (8), `HAS_ANIM_DICT_LOADED` (7), `GET_ENTITY_COORDS` (7), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (6), `CLEAR_PED_TASKS` (6), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (6), `WAIT` (6), `GET_SYNCHRONIZED_SCENE_PHASE` (6), `SET_ENTITY_COORDS` (6), `SET_ENTITY_HEADING` (6), `SET_BIT` (6), `TASK_SYNCHRONIZED_SCENE` (5), `DOES_ENTITY_EXIST` (5), `GET_ENTITY_MODEL` (5), `SET_PED_CONFIG_FLAG` (5), `REQUEST_MODEL` (4), `HAS_MODEL_LOADED` (4), `CREATE_PED` (4), `GET_PLAYER_GROUP` (4), `REMOVE_BLIP` (4), `IS_ENTITY_AT_ENTITY` (4), `IS_VEHICLE_SEAT_FREE` (4), `SET_PED_KEEP_TASK` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x8 · `1728.778f` x3 · `3851.287f` x3 · `33.7826f` x3 · `1935.53f` x3 · `6291.888f` x3 · `41.144f` x3 · `2.5f` x3 · `0.25f` x2 · `0.5f` x2 · `33.813f` x2 · `3847.646f` x2 · `1731.052f` x2 · `-28.44f` x2 · `33.7286f` x2 · `3850.767f` x2 · `1729.311f` x2 · `1.25f` x2 · `211.7722f` x1 · `0.196f` x1 · `0.99f` x1 · `1738.655f` x1 · `3836.227f` x1 · `33.879f` x1

## Other strings

Literals whose consuming native was not classified:

`DEFAULT_ANIMATED_CAMERA`, `MotionState_Idle`, `HELPING_VICTIM_TO_FEET_PLAYER`, `HELPING_VICTIM_TO_FEET_VICTIM`, `wound_sheet`, `CrashSafehouse`, `MOVE_INJURED_GENERIC`, `RECRA_APPR`, `RECRA_VDIE2`, `RECRA_VDIE`, `RECRA_MDIE2`, `RECRA_MDIE`, `RECRA_FDIE2`, `RECRA_FDIE`, `RECRA_TDIE2`, `RECRA_TDIE`, `RECRA_CHAT3M`, `RECRA_CHAT3F`, `RECRA_CHAT3T`, `RECRA_CHAT4`, `RECRA_CHAT4M`, `RECRA_CHAT4F`, `RECRA_CHAT4T`, `RECRA_CHAT5`, `RECRA_CHAT5M`, `RECRA_CHAT5F`, `RECRA_CHAT5T`, `RECRA_CHAT6`, `RECRA_CHAT6M`, `RECRA_CHAT6F`

---

Source: `decompiled_scripts/re_crashrescue.c`
