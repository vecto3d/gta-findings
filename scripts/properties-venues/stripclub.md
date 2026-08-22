# stripclub.c

Properties and venues script. 74 anim dicts; 6 models.

| | |
|---|---|
| Category | Properties and venues |
| Total lines | 110,583 |
| Functions | 1,095 (457 unique, 638 shared) |
| Unique lines | 13,363 (12.1% of file) |

## Assets

**Animation dictionaries** (74) - `facials@gen_female@variations@happy`, `mini@strip_club@idles@bouncer@base`, `mini@strip_club@idles@bouncer@idle_a`, `mini@strip_club@idles@bouncer@idle_b`, `mini@strip_club@idles@bouncer@idle_c`, `mini@strip_club@pole_dance@stage_enter`, `mini@strip_club@pole_dance@pole_exit`, `mini@strip_club@pole_dance@pole_enter`, `mini@strip_club@pole_dance@Pole_C_2_PrvD_A`, `mini@strip_club@pole_dance@Pole_C_2_PrvD_B`, `mini@strip_club@pole_dance@Pole_C_2_PrvD_C`, `mini@strip_club@pole_dance@pole_c_2_stage`, `mini@strip_club@pole_dance@pole_b_2_stage`, `mini@strip_club@pole_dance@pole_a_2_stage`, `mini@strip_club@pole_dance@stage_2_pole_c`, `mini@strip_club@pole_dance@stage_2_pole_b`, `mini@strip_club@pole_dance@stage_2_pole_a`, `mini@strip_club@pole_dance@pole_dance1`, `mini@strip_club@pole_dance@pole_dance2`, `mini@strip_club@pole_dance@pole_dance3`, `mini@strip_club@drink@one`, `mini@strip_club@drink@two`, `mini@strip_club@drink@three`, `mini@strip_club@drink@four`, `mini@strip_club@drink@idle_a`, `anim@mini@yacht@bar@drink@one`, `anim@mini@yacht@bar@drink@two`, `anim@mini@yacht@bar@drink@three`, `anim@mini@yacht@bar@drink@four`, `anim@mini@yacht@bar@drink@idle_a`, `mini@strip_club@leaning@enter`, `mini@strip_club@leaning@exit`, `mini@strip_club@leaning@toss`, `mini@strip_club@leaning@toss_many`, `mini@strip_club@leaning@base`, `mini@strip_club@idles@bouncer@go_away`, `mini@strip_club@idles@bouncer@side_exit`, `mini@strip_club@idles@bouncer@side_enter`, `mini@strip_club@idles@bouncer@stop`, `mini@strip_club@lap_dance_2g@ld_2g_approach`, `mini@strip_club@lap_dance@ld_girl_a_approach`, `mini@strip_club@lap_dance_2g@ld_2g_p1`, `mini@strip_club@lap_dance@ld_girl_a_song_a_p1`, `mini@strip_club@lap_dance_2g@ld_2g_p2`, `mini@strip_club@lap_dance@ld_girl_a_song_a_p2`, `mini@strip_club@idles@dj@idle_01`, `mini@strip_club@idles@dj@idle_02`, `mini@strip_club@idles@dj@idle_03`, `mini@strip_club@idles@dj@idle_04`, `mini@strip_club@idles@dj@idle_05`, `mini@strip_club@private_dance@exit`, `mini@strip_club@private_dance@part1`, `mini@strip_club@private_dance@part2`, `mini@strip_club@private_dance@part3`, `mini@strip_club@wade@`, `mini@strip_club@pole_dance@stage_exit`, `mini@strip_club@idles@stripper`, `mini@strip_club@throwout_d@`, `mini@strip_club@lap_dance_2g@ld_2g_intro`, `mini@strip_club@lap_dance@ld_girl_a_intro` ...

**Animations** (5) - `facials@gen_female@variations@happy`, `mood_happy_1`, `idle_a_whiskey`, `idle_a_shot_glass`, `ld_girl_a_exit_no_touch_m`

**Models and props** (6) - `s_m_m_bouncer_01`, `prop_anim_cash_note_b`, `s_f_y_bartender_01`, `a_m_y_hipster_01`, `ig_wade`, `p_whiskey_bottle_s`

**Audio banks** (1) - `STRIP_CLUB`

**Sounds** (2) - `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Speech contexts** (2) - `MALE_STRIP_DJ_WHITE`, `S_M_M_BOUNCER_LATINO_FULL_01`

**Text labels** (7) - `SCAUD`, `TREVOR`, `MICHAEL`, `FRANKLIN`, `LAMAR`, `JIMMY`, `NULL`

**Decorators** (2) - `XP_Blocker`, `Skill_Blocker`

**Relationship groups** (1) - `stripClubRelGroup`

**Doors** (3) - `v_ilev_door_orangesolid`, `prop_strip_door_01`, `prop_magenta_door`

**Scripts launched** (4) - `sclub_front_bouncer`, `stripperhome`, `stripclub_drinking`, `maintransition`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (275), `DOES_ENTITY_EXIST` (94), `IS_PED_INJURED` (79), `REMOVE_ANIM_DICT` (79), `REQUEST_ANIM_DICT` (72), `GET_ENTITY_COORDS` (62), `TASK_PLAY_ANIM` (59), `IS_ENTITY_PLAYING_ANIM` (55), `GET_SCRIPT_TASK_STATUS` (50), `GET_GAME_TIMER` (47), `PLAYER_ID` (37), `IS_ENTITY_DEAD` (33), `HAS_ANIM_DICT_LOADED` (31), `VDIST2` (27), `FLOOR` (24), `DOES_CAM_EXIST` (24), `GET_ENTITY_ANIM_CURRENT_TIME` (23), `SET_ENTITY_COORDS` (23), `IS_SYNCHRONIZED_SCENE_RUNNING` (22), `DISABLE_CONTROL_ACTION` (20), `TASK_FOLLOW_NAV_MESH_TO_COORD` (17), `GET_RANDOM_INT_IN_RANGE` (17), `GET_SYNCHRONIZED_SCENE_PHASE` (17), `IS_PED_MODEL` (16), `TASK_LOOK_AT_ENTITY` (15), `SET_MODEL_AS_NO_LONGER_NEEDED` (15), `CLEAR_PED_TASKS_IMMEDIATELY` (14), `REQUEST_MODEL` (13), `NETWORK_HAS_CONTROL_OF_ENTITY` (13), `SET_PLAYER_CONTROL` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.7f` x11 · `0.95f` x11 · `0.5f` x11 · `0.25f` x9 · `1.5f` x9 · `0.05f` x6 · `0.99f` x5 · `28.27f` x5 · `1.05f` x5 · `0.985f` x5 · `28.02f` x4 · `28.26f` x4 · `27.77f` x4 · `114.64f` x4 · `-1290.34f` x4 · `29.68f` x4 · `27.46f` x3 · `127.5f` x3 · `-1314.6f` x3 · `-13.594f` x3 · `128.7f` x2 · `-1298.22f` x2 · `29.31f` x2 · `0.84f` x2

## Other strings

Literals whose consuming native was not classified:

`SCLUB_OFFR_HELP`, `SCLUB_LEAVHELP`, `DEFAULT_SCRIPTED_CAMERA`, `SCLUB_NO_MONEY`, `SCLUB_LEAN_HELP`, `SCLUB_RAIL_HELP`, `SCLUB_RAIL_HEL2`, `SCLUB_LIK2_SP2`, `SCLUB_LIK2_SP1`, `SCLUB_LIKE_SP2`, `SCLUB_LIKE_SP1`, `SCLUB_LIK2_MP`, `SCLUB_LIKE_MP`, `SCLUB_RAIL_HEL3`, `SCLUB_BSAW_HELP`, `base`, `csb_stripper_01`, `csb_stripper_02`, `SCLUB_MLT_HLP`, `SC_OFFER`, `STRIP_DANCING_MP`, `SCLUB_DNCE_HEL2`, `SCLUB_DNCE_HEL3`, `SCLUB_DNCE_HELP`, `SCLUB_MORE_HELP`, `SCLUB_MORE_HEL2`, `SCLUB_MORE_HEL3`, `SCLUB_MORE_HEL4`

---

Source: `decompiled_scripts/stripclub.c`
