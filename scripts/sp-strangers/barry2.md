# barry2.c

SP strangers and freaks script. 3 anim dicts; 7 models; 2 particle effects.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 52,561 |
| Functions | 645 (112 unique, 533 shared) |
| Unique lines | 4,526 (8.6% of file) |

## Assets

**Animation dictionaries** (3) - `amb@world_human_cheering@female_d`, `amb@world_human_cheering@male_d`, `special_ped@mime`

**Animations** (1) - `lead_in`

**Models and props** (7) - `prop_protest_table_01`, `prop_chair_08`, `prop_protest_sign_01`, `p_a4_sheets_s`, `a_m_m_business_01`, `a_f_m_bevhills_02`, `s_m_y_clown_01`

**Sounds** (5) - `BARRY_02_SOUNDSET`, `clown_die_wrapper`, `DrugsEffect`, `CROWD_WATCHING`, `HOORAY`

**Speech contexts** (1) - `CLOWNS`

**Particle effects** (2) - `scr_clown_appears`, `scr_clown_death`

**Text labels** (7) - `TREVOR`, `BARY2AU`, `CLOWNS`, `NUMBER`, `BARY2`, `NULL`, `BARRY`

**Relationship groups** (1) - `player`

**Scripts launched** (1) - `postRC_Barry1and2`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (128), `GET_GAME_TIMER` (78), `GET_RANDOM_INT_IN_RANGE` (31), `DOES_ENTITY_EXIST` (22), `PLAYER_ID` (19), `GET_ENTITY_COORDS` (17), `FREEZE_ENTITY_POSITION` (14), `IS_ENTITY_DEAD` (13), `SET_PED_COMBAT_ATTRIBUTES` (12), `SET_PLAYER_CONTROL` (12), `SET_ENTITY_HEADING` (12), `IS_PED_INJURED` (11), `SET_ENTITY_VISIBLE` (11), `REGISTER_ENTITY_FOR_CUTSCENE` (11), `SET_PED_COMBAT_MOVEMENT` (10), `GET_RANDOM_FLOAT_IN_RANGE` (10), `IS_ENTITY_ON_SCREEN` (8), `FLOOR` (8), `TASK_PLAY_ANIM` (8), `TRIGGER_MUSIC_EVENT` (8), `SET_AUDIO_FLAG` (8), `WAIT` (8), `IS_ENTITY_PLAYING_ANIM` (7), `GET_FRAME_TIME` (7), `HAS_PED_GOT_WEAPON` (7), `DOES_CAM_EXIST` (7), `SET_CAM_ACTIVE` (7), `ANIMPOSTFX_PLAY` (7), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (6), `GIVE_WEAPON_TO_PED` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x5 · `0.5f` x5 · `29.0923f` x4 · `0.1f` x4 · `2.5f` x3 · `0.3f` x3 · `188.1366f` x2 · `-957.7827f` x2 · `30.6514f` x2 · `-5.5067f` x2 · `92.8053f` x2 · `0.25f` x2 · `-0.7f` x2 · `-0.1f` x1 · `220.5318f` x1 · `-918.4567f` x1 · `27.53389f` x1 · `211.7581f` x1 · `-931.4215f` x1 · `39.6918f` x1 · `0.625f` x1 · `4.5f` x1 · `183.434f` x1 · `-949.1876f` x1

## Other strings

Literals whose consuming native was not classified:

`Trevor`, `RC18B_END`, `B2_PRIME`, `DRUNK_SHAKE`, `BARRY_02_SLOWMO`, `CLOWN_LAUGH`, `AllowScriptedSpeechInSlowMo`, `AllowAmbientSpeechInSlowMo`, `RC18B_START`, `FIRING_PATTERN_FULL_AUTO`, `B2_WARN`, `DEFAULT_SCRIPTED_CAMERA`, `clown_idle_`, `B2_FAIL2`, `bar_4_rcm`, `BAR_3_RCM`, `rcm_barry2`, `lead_in_loop`, `BARY2_FREAK`, `base`, `BARY2_ONEOFF`, `CLOWN_DEATH`, `BARY2_FIGHT`, `MotionState_Run`, `RC LAUNCHER: BARRY 2`, `BARY2_PREOUT`, `postRC_Barry1and2`, `extrasunny`, `rcmbarry`, `BARY2_DUPE`

---

Source: `decompiled_scripts/barry2.c`
