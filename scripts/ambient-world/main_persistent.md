# main_persistent.c

Ambient world script. 12 anim dicts; 11 models.

| | |
|---|---|
| Category | Ambient world |
| Total lines | 435,690 |
| Functions | 8,144 (357 unique, 7,787 shared) |
| Unique lines | 27,441 (6.3% of file) |

## Assets

**Animation dictionaries** (12) - `M@MP_PLA`, `NMALE@K`, `ALE@FAC`, `IM@MP`, `E@THUM`, `FE@R`, `M@MP_F`, `T@INTRO`, `DIC@ST`, `AMB@ME`, `EEL@IDLE_A`, `ANDING@KN`

**Models and props** (11) - `a_c_rottweiler`, `a_c_rabbit_01`, `a_c_boar`, `a_c_deer`, `a_c_mtlion`, `cs_hunter`, `a_m_y_hiker_01`, `a_f_y_hippie_01`, `a_m_m_hillbilly_01`, `mp_m_freemode_01`, `P_MUSIC`

**Sounds** (12) - `DLC_HEIST_POST_CELEB_SCREEN_FADE_BLACK_SCENE`, `DLC_HEIST_POST_STATS_SCREEN_FADE_WHITE_SCENE`, `DLC_HEIST_CELEB_STATS_SCENE`, `MP_BLUR_PRE_CELEB_SCREEN_SCENE`, `DLC_HEIST_POST_CELEB_STATS_PACIFIC_SCENE`, `DLC_HEIST_POST_CELEB_STATS_PRISON_SCENE`, `DLC_HEIST_POST_CELEB_STATS_SERIES_A_SCENE`, `DLC_HEIST_POST_CELEB_STATS_FLEECA_SCENE`, `DLC_HEIST_POST_CELEB_STATS_HUMANE_SCENE`, `MP_POST_MATCH_TRANSITION_SCENE`, `Text_Arrive_Tone`, `Phone_SoundSet_Default`

**Texture dicts** (2) - `MPArenaLobby`, `bg_texture`

**Text labels** (59) - `MISSION`, `AWARD`, `CHAR_SOCIAL_CLUB`, `HEIST5`, `AVI`, `BAIL`, `CHICKEN`, `FINALE`, `ANI`, `CONTENT_TICK`, `SETUP`, `MANSION`, `EXTRASUNNY`, `ARS`, `BEA`, `AST`, `CHAR_ROCKSTAR`, `NULL`, `MARSTON_TICK2`, `CONTENT_NEW_SC`, `COUPON`, `COUP_STR`, `ASUN`, `CHA`, `CTIN`, `HUN`, `KORTZ`, `CAT`, `DOG`, `MFH`, `DISPATCH`, `SELL`, `CELL_EMAIL_EVENT`, `OWE`, `HALL`, `SIC`, `HALLO`, `NUCKL`, `TCELE`, `BRATIO`, `UCK`, `UNCH`, `ATIONM`, `ELEBR`, `LEBRATI`, `ONMAL`, `THU`, `MOV`, `OLL`, `ATRO`, `COMB`, `FORM`, `RANS`, `ASQUA`, `UNAFFILIATED`, `MCKENZIE`, `PIZZA`, `PREP`, `SALVAGE`

**Scenarios** (2) - `MP_POLICE`, `LOST_BIKERS`

**Decorators** (1) - `PYV_Yacht`

**Relationship groups** (3) - `RELGROUPHASH_FAMILY_M`, `RELGROUPHASH_FAMILY_F`, `RELGROUPHASH_FAMILY_T`

**Interiors and entity sets** (1) - `v_lesters`

**Vehicle mods** (4) - `cavalcade`, `daemon`, `police3`, `sentinel2`

**Stats** (3) - `sp0_total_cash`, `sp1_total_cash`, `sp2_total_cash`

**Scripts launched** (26) - `error_listener`, `drunk_controller`, `social_controller`, `cellphone_controller`, `dialogue_handler`, `shop_controller`, `selector`, `InGameHud`, `context_controller`, `stats_controller`, `achievement_controller`, `building_controller`, `startup_positioning`, `stripclub`, `stripclub_mp`, `drunk`, `initial`, `director_mode`, `fake_interiors`, `emergencycalllauncher`, `net_cloud_mission_loader`, `FMMC_Launcher`, `freemode_clearGlobals`, `am_doors`, `AM_MP_PROPERTY_INT`, `main`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (148), `PLAYER_PED_ID` (132), `SET_BIT` (55), `CLEAR_BIT` (44), `GET_NETWORK_TIME` (35), `GET_ENTITY_COORDS` (34), `GET_EVENT_DATA` (34), `IS_ENTITY_DEAD` (33), `REQUEST_SCRIPT` (32), `REMOVE_IPL` (31), `GET_GAME_TIMER` (29), `NETWORK_IS_GAME_IN_PROGRESS` (26), `DOES_ENTITY_EXIST` (23), `NETWORK_ARE_HANDLES_THE_SAME` (22), `NETWORK_EARN_FROM_AMBIENT_JOB` (20), `VMAG` (19), `IS_AUDIO_SCENE_ACTIVE` (19), `HIDE_HUD_COMPONENT_THIS_FRAME` (19), `SET_PED_COMBAT_ATTRIBUTES` (18), `DATADICT_SET_BOOL` (17), `NETWORK_IS_ACTIVITY_SESSION` (16), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (15), `IS_PED_INJURED` (15), `START_NEW_SCRIPT` (15), `GET_RANDOM_FLOAT_IN_RANGE` (14), `NETWORK_SESSION_GET_HOST_AIM_PREFERENCE` (14), `HAS_SCRIPT_LOADED` (13), `VDIST2` (12), `NETWORK_GET_NP_UNAVAILABLE_REASON` (12), `ENABLE_DISPATCH_SERVICE` (11)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x8 · `0.3f` x2 · `0.2f` x2 · `0.4751f` x2 · `0.5249f` x2 · `115.9314f` x1 · `-1290.483f` x1 · `27.94359f` x1 · `3122.315f` x1 · `5549.007f` x1 · `188.4373f` x1 · `3.5f` x1 · `1.75f` x1 · `99999.9f` x1 · `1274.724f` x1 · `-1713.83f` x1 · `53.7715f` x1

## Other strings

Literals whose consuming native was not classified:

`money_earn_jobs`, `AllowRadioOverScreenFade`, `AllowCutsceneOverScreenFade`, `money_spent_job_activity`, `MISSION_GOON`, `VEH_ROBBERY`, `player_zero`, `player_one`, `player_two`, `money_spent_property_util`, `HACKER_DEN_ROBBERY`, `mpply_non_cheater_cash`, `trev_steps`, `tailgater`, `HEIST_CELEB_STRIP_CLUB`, `HEIST_CELEB_APARTMENT`, `HEIST_STATS_SCREEN_STOP_PREP`, `mp_m_freemode_01`, `player`, `GUARD_DOG`, `cougar`, `WILD_ANIMAL`, `service_earn_ambient_job_plane_takedown`, `service_earn_ambient_job_distract_cops`, `service_earn_job_bonus`, `service_earn_bend_job`, `service_earn_jobs`, `service_earn_boss`, `service_earn_goon`

---

Source: `decompiled_scripts/main_persistent.c`
