# stripclub_mp.c

Properties and venues script. 73 anim dicts; 5 models.

| | |
|---|---|
| Category | Properties and venues |
| Total lines | 120,735 |
| Functions | 1,213 (503 unique, 710 shared) |
| Unique lines | 14,346 (11.9% of file) |

## Assets

**Animation dictionaries** (73) - `anim@heists@humane_labs@finale@strip_club`, `facials@gen_female@variations@happy`, `mini@strip_club@leaning@enter`, `mini@strip_club@leaning@exit`, `mini@strip_club@leaning@toss`, `mini@strip_club@leaning@toss_many`, `mini@strip_club@leaning@base`, `mini@strip_club@lap_dance_2g@ld_2g_decline`, `mini@strip_club@lap_dance@ld_girl_a_decline`, `mini@strip_club@lap_dance_2g@ld_2g_accept`, `mini@strip_club@lap_dance@ld_girl_a_accept`, `mini@strip_club@lap_dance_2g@ld_2g_wait`, `mini@strip_club@lap_dance@ld_girl_a_wait`, `mini@strip_club@lap_dance_2g@ld_2g_reach`, `mini@strip_club@lap_dance@ld_reach`, `mini@strip_club@lap_dance_2g@ld_2g_exit`, `mini@strip_club@lap_dance@ld_girl_a_decline_alt`, `mini@strip_club@lap_dance@ld_girl_a_exit`, `mini@strip_club@lap_dance_2g@ld_2g_p1`, `mini@strip_club@lap_dance@ld_girl_a_song_a_p1`, `mini@strip_club@lap_dance_2g@ld_2g_p2`, `mini@strip_club@lap_dance@ld_girl_a_song_a_p2`, `mini@strip_club@lap_dance_2g@ld_2g_p3`, `mini@strip_club@lap_dance@ld_girl_a_song_a_p3`, `mini@strip_club@lap_dance_2g@ld_2g_intro`, `mini@strip_club@lap_dance@ld_girl_a_intro`, `mini@strip_club@lap_dance_2g@ld_2g_approach`, `mini@strip_club@lap_dance@ld_girl_a_approach`, `mini@strip_club@idles@bouncer@go_away`, `mini@strip_club@idles@bouncer@base`, `mini@strip_club@idles@bouncer@idle_a`, `mini@strip_club@idles@bouncer@idle_b`, `mini@strip_club@idles@bouncer@idle_c`, `mini@strip_club@pole_dance@stage_exit`, `mini@strip_club@pole_dance@stage_enter`, `mini@strip_club@pole_dance@pole_exit`, `mini@strip_club@pole_dance@pole_enter`, `mini@strip_club@pole_dance@Pole_C_2_PrvD_A`, `mini@strip_club@pole_dance@Pole_C_2_PrvD_B`, `mini@strip_club@pole_dance@Pole_C_2_PrvD_C`, `mini@strip_club@pole_dance@pole_c_2_stage`, `mini@strip_club@pole_dance@pole_b_2_stage`, `mini@strip_club@pole_dance@pole_a_2_stage`, `mini@strip_club@pole_dance@stage_2_pole_c`, `mini@strip_club@pole_dance@stage_2_pole_b`, `mini@strip_club@pole_dance@stage_2_pole_a`, `mini@strip_club@pole_dance@pole_dance1`, `mini@strip_club@pole_dance@pole_dance2`, `mini@strip_club@pole_dance@pole_dance3`, `mini@strip_club@idles@stripper`, `mini@strip_club@idles@bouncer@side_exit`, `mini@strip_club@idles@bouncer@side_enter`, `mini@strip_club@idles@bouncer@stop`, `mini@strip_club@idles@dj@idle_01`, `mini@strip_club@idles@dj@idle_02`, `mini@strip_club@idles@dj@idle_03`, `mini@strip_club@idles@dj@idle_04`, `mini@strip_club@idles@dj@idle_05`, `mini@strip_club@private_dance@exit`, `mini@strip_club@private_dance@part1` ...

**Animations** (10) - `anim@heists@humane_labs@finale@strip_club`, `facials@gen_female@variations@happy`, `mood_happy_1`, `ld_girl_a_exit_no_touch_m`, `idle_a_whiskey`, `idle_a_shot_glass`, `ped_a_celebrate_intro`, `ped_b_celebrate_intro`, `ped_a_celebrate_loop`, `ped_b_celebrate_loop`

**Models and props** (5) - `s_m_m_bouncer_01`, `prop_anim_cash_note_b`, `s_f_y_bartender_01`, `a_m_y_hipster_01`, `p_whiskey_bottle_s`

**Audio banks** (1) - `STRIP_CLUB`

**Sounds** (2) - `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Speech contexts** (2) - `MALE_STRIP_DJ_WHITE`, `S_M_M_BOUNCER_LATINO_FULL_01`

**Text labels** (5) - `SCAUD`, `NULL`, `TREVOR`, `MICHAEL`, `FRANKLIN`

**Decorators** (2) - `XP_Blocker`, `Skill_Blocker`

**Relationship groups** (1) - `stripClubRelGroup`

**Doors** (3) - `prop_strip_door_01`, `v_ilev_door_orangesolid`, `prop_magenta_door`

**Scripts launched** (4) - `stripperhome`, `stripclub_drinking`, `maintransition`, `appinternet`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (295), `REMOVE_ANIM_DICT` (79), `IS_PED_INJURED` (77), `DOES_ENTITY_EXIST` (72), `REQUEST_ANIM_DICT` (72), `GET_ENTITY_COORDS` (56), `TASK_PLAY_ANIM` (54), `GET_SCRIPT_TASK_STATUS` (51), `IS_ENTITY_PLAYING_ANIM` (49), `PLAYER_ID` (47), `GET_GAME_TIMER` (46), `PARTICIPANT_ID_TO_INT` (35), `NETWORK_HAS_CONTROL_OF_ENTITY` (35), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (29), `DOES_CAM_EXIST` (29), `HAS_ANIM_DICT_LOADED` (27), `IS_ENTITY_DEAD` (26), `VDIST2` (23), `GET_ENTITY_ANIM_CURRENT_TIME` (22), `FLOOR` (20), `IS_SYNCHRONIZED_SCENE_RUNNING` (20), `DISABLE_CONTROL_ACTION` (18), `SET_ENTITY_COORDS` (16), `GET_SYNCHRONIZED_SCENE_PHASE` (16), `GET_RANDOM_INT_IN_RANGE` (16), `TASK_FOLLOW_NAV_MESH_TO_COORD` (15), `CLEAR_AREA_OF_PEDS` (15), `SET_BIT` (14), `SET_MODEL_AS_NO_LONGER_NEEDED` (14), `SET_PLAYER_CONTROL` (13)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x12 · `0.7f` x11 · `0.95f` x11 · `1.5f` x10 · `28.27f` x10 · `0.25f` x7 · `0.05f` x6 · `0.99f` x5 · `28.02f` x5 · `0.985f` x5 · `28.26f` x5 · `114.64f` x4 · `-1290.34f` x4 · `29.68f` x4 · `111.0366f` x4 · `-1282.915f` x4 · `26.26278f` x4 · `114.7872f` x4 · `-1289.966f` x4 · `29.26099f` x4 · `27.77f` x4 · `0.15f` x4 · `-13.594f` x3 · `27.261f` x3

## Other strings

Literals whose consuming native was not classified:

`DEFAULT_SCRIPTED_CAMERA`, `SCLUB_OFFR_HELP`, `SCLUB_NO_MONEY`, `SCLUB_LEAN_HELP`, `SCLUB_RAIL_HELP`, `SCLUB_RAIL_HEL2`, `SCLUB_LEAVHELP`, `SCLUB_LIK2_SP2`, `SCLUB_LIK2_SP1`, `SCLUB_LIKE_SP2`, `SCLUB_LIKE_SP1`, `SCLUB_LIK2_MP`, `SCLUB_LIKE_MP`, `SCLUB_BSAW_HELP`, `HAND_SHAKE`, `SCLUB_RAIL_HEL3`, `Bouncer`, `Bouncer2`, `base`, `SCLUB_DNCE_HLM2`, `SCLUB_DNCE_HLM3`, `SCLUB_DNCE_HLMP`, `SCLUB_MORE_HEL4`, `SCLUB_MORE_HEL2`, `SCLUB_MORE_HEL3`, `SCLUB_MORE_HELP`, `SCLUB_MOR2_HEL2`, `SCLUB_MOR2_HELP`, `SCLUB_MLT_HLP`, `SC_OFFER`

---

Source: `decompiled_scripts/stripclub_mp.c`
