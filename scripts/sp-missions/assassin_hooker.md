# assassin_hooker.c

SP missions script. 11 anim dicts; 11 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 24,145 |
| Functions | 516 (87 unique, 429 shared) |
| Unique lines | 4,324 (17.9% of file) |

## Assets

**Animation dictionaries** (11) - `oddjobs@assassinate@vice@call`, `mini@hookers_spvanilla`, `ODDJOBS@ASSASSINATE@VICE@SEX`, `ODDJOBS@assassinate@vice@incar`, `ODDJOBS@assassinate@old_lady`, `move_m@casual@d`, `ODDJOBS@ASSASSINATE@VICE@HOOKER`, `ODDJOBS@ASSASSINATE@VICE@PARK`, `ODDJOBS@ASSASSINATE@VICE@IDLE`, `ODDJOBS@ASSASSINATE@VICE@DEALER`, `amb@world_human_prostitute@hooker@idle_a`

**Animations** (30) - `ODDJOBS@ASSASSINATE@VICE@SEX`, `frontseat_carsex_loop_f`, `ODDJOBS@assassinate@vice@incar`, `frontseat_carsex_loop_m`, `FrontSeat_CarSex_Normal_Outro_m`, `idle_wait`, `frontseat_carsex_intro_m`, `ODDJOBS@ASSASSINATE@VICE@HOOKER`, `idle_outro`, `idle_reject`, `passenger_KO_female_m`, `reject_outro`, `frontseat_carsex_intro_f`, `FrontSeat_CarSex_Normal_Outro_f`, `frontseat_carsex_base_m`, `frontseat_carsex_base_f`, `idle_b`, `frontseat_carsex_outro_m`, `frontseat_carsex_outro_f`, `idle_a`, `ODDJOBS@ASSASSINATE@VICE@DEALER`, `hooker_a`, `passenger_KO_female_f`, `oddjobs@assassinate@vice@call`, `ass_call_vice_p1`, `amb@world_human_prostitute@hooker@idle_a`, `argue_a`, `argue_b`, `hooker_c`, `base`

**Models and props** (11) - `s_f_y_hooker_02`, `p_phonebox_01b_s`, `a_f_m_beach_01`, `prop_phonebox_01b`, `a_f_y_soucent_03`, `a_f_y_scdressy_01`, `ruiner`, `a_m_m_soucent_04`, `a_m_m_business_01`, `s_f_y_hooker_03`, `a_m_y_genstreet_02`

**Text labels** (6) - `OJASAUD`, `FRANKLIN`, `LESTER`, `COP`, `NULL`, `INVESTOR`

**Waypoint recordings** (9) - `OJAShk_103`, `OJAShk_104`, `OJAShk_101`, `OJAShk_102`, `OJASbs_102`, `OJASbs01`, `OJASbs02`, `OJASbs03`, `OJASbs04`

**Relationship groups** (2) - `Target`, `TargetGroup`

**Vehicle mods** (1) - `peyote`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (113), `IS_PED_INJURED` (71), `DOES_ENTITY_EXIST` (67), `IS_ENTITY_DEAD` (54), `TASK_PLAY_ANIM` (41), `IS_VEHICLE_DRIVEABLE` (28), `IS_ENTITY_PLAYING_ANIM` (24), `PLAYER_ID` (22), `SET_PED_COMPONENT_VARIATION` (20), `CLEAR_SEQUENCE_TASK` (19), `GET_SCRIPT_TASK_STATUS` (19), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (19), `GET_ENTITY_COORDS` (18), `TIMERB` (14), `TASK_LOOK_AT_ENTITY` (14), `SET_PED_COMBAT_ATTRIBUTES` (14), `DELETE_PED` (14), `TASK_SMART_FLEE_PED` (13), `IS_PED_IN_ANY_VEHICLE` (12), `WAIT` (12), `IS_SCRIPTED_CONVERSATION_ONGOING` (11), `OPEN_SEQUENCE_TASK` (11), `CLOSE_SEQUENCE_TASK` (11), `TASK_PERFORM_SEQUENCE` (11), `SETTIMERA` (11), `SET_PED_KEEP_TASK` (11), `CLEAR_PED_TASKS` (10), `IS_PED_FACING_PED` (10), `REMOVE_BLIP` (10), `CREATE_PED` (10)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x5 · `214.4495f` x5 · `-852.8672f` x5 · `0.2f` x4 · `29.3496f` x4 · `17.6777f` x3 · `-1708.148f` x3 · `-463.2923f` x3 · `245.8158f` x3 · `-706.106f` x2 · `-1708.865f` x2 · `-512.576f` x2 · `-1842.173f` x2 · `0.9f` x2 · `0.5f` x2 · `0.1f` x2 · `-598.1845f` x2 · `-1790.477f` x2 · `22.612f` x2 · `-607.262f` x2 · `-1800.9f` x2 · `22.3211f` x2 · `-690.763f` x2 · `-1607.467f` x2

## Other strings

Literals whose consuming native was not classified:

`player`, `ASS_HK_COMP`, `ASS_BS_COMP`, `ASS_ML_COMP`, `ASS_HK_COPS`, `OJAS_VICOM`, `ASS3_RADIO_PASS`, `ASS_hk`, `ASS_HK_WAIT`, `OJAShk_HELP`, `ASS_HK_WAIT2`, `ASS3_COPS`, `OJAShk_101`, `OJAShk_103`, `ASS_HK_RT`, `OJAShk_FIRST`, `ASS3_FAIL`, `OJAhkHOOKER`, `ASS_HK_LOST`, `KerbCrawler`, `ruiner`, `OJAShk_REG`, `OJAShk_TALK`, `OJAShk_TALK2`, `OJAShk_TALK3`, `OJAShk_HELP_3`, `FrontSeat_CarSex_Normal_Outro_m`, `OJAShk_LEAVE`, `OJAShk_LEAVE_1`, `OJAShk_SEX`

---

Source: `decompiled_scripts/assassin_hooker.c`
