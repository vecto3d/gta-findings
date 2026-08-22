# lester1.c

SP missions script. 2 developer state labels recovered; 8 anim dicts; 23 models; 14 scaleforms.

| | |
|---|---|
| Category | SP missions |
| Total lines | 126,743 |
| Functions | 902 (95 unique, 807 shared) |
| Unique lines | 9,383 (7.4% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`WAITING FOR: cutscene` · `WAITING FOR: bTVTurnedOn`

## Assets

**Animation dictionaries** (8) - `amb@prop_human_seat_computer@male@base`, `AMB@PROP_HUMAN_SEAT_COMPUTER@MALE@IDLE_B`, `AMB@WORLD_HUMAN_STAND_IMPATIENT@MALE@No_Sign@base`, `AMB@WORLD_HUMAN_STAND_IMPATIENT@MALE@No_Sign@idle_a`, `MOVE_P_M_ZERO_RUCKSACK`, `amb@world_human_drinking@coffee@male@idle_a`, `misslester1b`, `MissLester1ALeadInOut`

**Animations** (79) - `idle_b`, `base`, `idle_a`, `AMB@WORLD_HUMAN_STAND_IMPATIENT@MALE@No_Sign@base`, `AMB@WORLD_HUMAN_STAND_IMPATIENT@MALE@No_Sign@idle_a`, `air_guitar_01_exitloop_c`, `air_guitar_01_exitloop_d`, `idle_c`, `amb@prop_human_seat_computer@male@base`, `air_guitar_01_exitloop_boss`, `air_guitar_01_exitloop_a`, `air_guitar_01_exitloop_b`, `AMB@PROP_HUMAN_SEAT_COMPUTER@MALE@IDLE_B`, `IDLE_E`, `misslester1b`, `watchtv`, `idle_to_sit_pedb`, `idle_to_sit_peda`, `idle_standing_pedb`, `idle_standing_peda`, `idle_sitting_pedb`, `idle_sitting_peda`, `MissLester1ALeadInOut`, `Lester_1_INT_LeadIn_loop_Lester`, `air_guitar_01_boss`, `air_guitar_01_a`, `air_guitar_01_b`, `air_guitar_01_c`, `air_guitar_01_d`, `air_guitar_02_boss`, `air_guitar_02_a`, `air_guitar_02_b`, `air_guitar_02_c`, `air_guitar_02_d`, `air_guitar_02_exit_boss`, `air_guitar_02_exit_a`, `air_guitar_02_exit_b`, `air_guitar_02_exit_c`, `air_guitar_02_exit_d`, `boardroom_intro_jaynorris`, `boardroom_intro_m_a`, `boardroom_intro_m_b`, `boardroom_intro_m_f`, `boardroom_intro_f_b`, `boardroom_intro_f_c`, `boardroom_intro_m_e`, `boardroom_react_m_e`, `boardroom_react_f_b`, `boardroom_react_f_c`, `boardroom_into_exit_jaynorris`, `boardroom_into_exit_m_a`, `boardroom_into_exit_m_b`, `boardroom_into_exit_m_f`, `boardroom_into_exit_f_b`, `boardroom_into_exit_f_c`, `boardroom_into_exit_m_e`, `boardroom_exitloop_jaynorris`, `boardroom_exitloop_m_a`, `boardroom_exitloop_m_b`, `boardroom_exitloop_m_f` ...

**Models and props** (23) - `prop_off_chair_01`, `prop_cs_remote_01`, `prop_monitor_01c`, `ig_jay_norris`, `prop_paper_ball`, `prop_monitor_01d`, `prop_hacky_sack_01`, `p_michael_backpack_s`, `prop_phone_ing`, `prop_monitor_li`, `v_ilev_fib_door2`, `v_ilev_fb_sl_door01`, `prop_security_case_01`, `prop_cub_door_lifeblurb`, `ig_lestercrest`, `prop_wheelchair_01_s`, `ig_lifeinvad_01`, `a_m_y_hipster_01`, `a_f_y_hipster_01`, `a_f_y_hipster_04`, `prop_cs_paper_cup`, `prop_cs_milk_01`, `cs_lifeinvad_01`

**Audio banks** (1) - `Lester1A_01`

**Sounds** (21) - `LESTER1A_SOUNDS`, `FINDING_VIRUS`, `State`, `LESTER_1A_FOLLOW_PROGRAMMER`, `LESTER_1A_RIG_EXPLOSIVE`, `LESTER_1A_DRIVE_TO_LIFEINVADER`, `LESTER_1A_DRIVE_TO_STORE`, `LESTER_1A_LEAVE_OFFICE`, `LESTER_1A_POPUP_MINIGAME`, `TracksPlaying`, `LESTER_1A_BUY_CLOTHES`, `CLOSE_WINDOW`, `LESTER_1A_AFTER_EXPLOSION`, `Remote_Ring`, `Phone_SoundSet_Michael`, `Answer_Phone`, `Lester1B_Sounds`, `OPEN_WINDOW`, `COMPUTERS_MOUSE_CLICK`, `Virus_Eradicated`, `UNLOCK_DOOR`

**Scaleform movies** (14) - `PLAY_SCAN_ANIM`, `ADD_PROGRAM`, `OPEN_ANTIVIRUS`, `SET_SNAP_SPEED`, `SHOW_STATIC`, `OPEN_POPUP`, `LAST_POPUP_CLOSED`, `SET_CURSOR`, `MOVE_CURSOR`, `SET_INPUT_EVENT`, `SET_DATA_SLOT`, `RUN_PROGRAM`, `SET_SCAN_BAR`, `CLOSE_POPUP`

**Text labels** (23) - `LS1AAUD`, `EXTRASUNNY`, `LIFEINVADERM1`, `MICHAEL`, `COMPUTERS`, `JAYNORRIS`, `DONTPLAY`, `DRUMMING`, `AIRDRUMMER`, `LESTER`, `LIFEINVADERF3`, `LIFEINVADERM3`, `NULL`, `LEST1`, `NONE`, `FIND_NEWS`, `SHOPASSISTANT`, `PROTOTYPE`, `GUITAR`, `PIANO`, `AIRPIANIST`, `AIRROCKING`, `LIENGINEER2`

**Scenarios** (1) - `PROP_HUMAN_SEAT_COMPUTER`

**Relationship groups** (2) - `Family`, `REL_FREIND`

**Interiors and entity sets** (3) - `v_lesters`, `v_faceoffice`, `v_michael`

**Hashed names** (2) - `ENDS_IN_WALK`, `ENDS_IN_RUN`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (332), `DOES_ENTITY_EXIST` (128), `TASK_SYNCHRONIZED_SCENE` (83), `IS_PED_INJURED` (61), `GET_GAME_TIMER` (58), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (49), `CLEAR_PED_TASKS` (38), `IS_ENTITY_IN_ANGLED_AREA` (32), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (32), `CREATE_PED` (32), `PLAYER_ID` (31), `FREEZE_ENTITY_POSITION` (30), `BEGIN_SCALEFORM_MOVIE_METHOD` (30), `END_SCALEFORM_MOVIE_METHOD` (28), `HAS_ANIM_DICT_LOADED` (28), `CREATE_SYNCHRONIZED_SCENE` (28), `DISABLE_CONTROL_ACTION` (27), `GET_ENTITY_COORDS` (26), `GET_CLOSEST_OBJECT_OF_TYPE` (26), `DELETE_PED` (24), `IS_ENTITY_PLAYING_ANIM` (23), `IS_AMBIENT_SPEECH_PLAYING` (23), `HAS_MODEL_LOADED` (23), `GET_ENTITY_ANIM_CURRENT_TIME` (22), `DOES_OBJECT_OF_TYPE_EXIST_AT_COORDS` (21), `SET_ENTITY_COORDS` (21), `CLEAR_HELP` (21), `DOES_BLIP_EXIST` (20), `SET_BIT` (20), `CLEAR_BIT` (19)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x41 · `43.02f` x35 · `43.0211f` x15 · `0.1f` x14 · `48.29568f` x13 · `-238.2421f` x13 · `-1057.518f` x13 · `11.8125f` x12 · `-1060.174f` x10 · `-245.2477f` x10 · `43.6942f` x10 · `43.41f` x8 · `-1045.07f` x7 · `-229.78f` x7 · `43.02128f` x6 · `-1067.002f` x6 · `-239.245f` x6 · `43.021f` x6 · `27.75f` x6 · `-804.4475f` x5 · `172.7937f` x5 · `72.34801f` x5 · `-1060.36f` x5 · `-1083.87f` x5

## Other strings

Literals whose consuming native was not classified:

`Michael`, `MotionState_Walk`, `MOVE_P_M_ZERO_RUCKSACK`, `LIEngineer`, `POPUP_MUSIC_RND`, `LOSE_WANTED`, `SE_MICHAELS_HOUSE_RADIO`, `Life_invader_Engineer`, `Lester1A_Qub3d`, `LifeInvad_Chair`, `player`, `Lester1A_01`, `misslester1b`, `AZL_LESTERS_DOGS`, `POPUP_MUSIC_02`, `POPUP_MUSIC_03`, `POPUP_MUSIC_04`, `POPUP_MUSIC_05`, `POPUP_MUSIC_06`, `MORE_SEATS`, `HAND_SHAKE`, `POPUP_MUSIC_01`, `SAFEHOUSE_MICHAEL_SIT_SOFA`, `Lester`, `MissLester1ALeadInOut`, `air_guitar_01_exitloop_chair_d`, `Lester1B`, `LES1A_TXT1`, `LES1A_TXT2`, `GENERIC_BYE`

---

Source: `decompiled_scripts/lester1.c`
