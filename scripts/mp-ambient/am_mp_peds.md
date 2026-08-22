# am_mp_peds.c

MP ambient script. 21 anim dicts; 170 models.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 140,503 |
| Functions | 2,177 (416 unique, 1,761 shared) |
| Unique lines | 23,504 (16.7% of file) |

## Assets

**Animation dictionaries** (21) - `anim@amb@nightclub@djs@switch@smun_djset_switchover@`, `anim@amb@nightclub@djs@switch@dixn_djset_switchover@`, `anim@amb@nightclub@djs@switch@tale_djset_switchover@`, `anim@amb@nightclub@djs@switch@bmad_djset_switchover@`, `anim@scripted@nightclub@dj@switch@keinemuzik_djset_switchover@`, `anim@scripted@nightclub@dj@switch@moodyman_djset_switchover@`, `anim@scripted@nightclub@dj@switch@palmstrax_djset_switchover@`, `MOVE_M@CLIPBOARD`, `ANIM@AMB@INSPECT@STAND@MALE_A@BASE`, `ANIM@AMB@INSPECT@STAND@MALE_A@IDLES`, `AMB@WORLD_HUMAN_MOBILE_FILM_SHOCKING@MALE@ENTER`, `AMB@WORLD_HUMAN_MOBILE_FILM_SHOCKING@MALE@BASE`, `AMB@WORLD_HUMAN_MOBILE_FILM_SHOCKING@MALE@IDLE_A`, `AMB@WORLD_HUMAN_MOBILE_FILM_SHOCKING@MALE@EXIT`, `AMB@WORLD_HUMAN_MOBILE_FILM_SHOCKING@FEMALE@ENTER`, `AMB@WORLD_HUMAN_MOBILE_FILM_SHOCKING@FEMALE@BASE`, `AMB@WORLD_HUMAN_MOBILE_FILM_SHOCKING@FEMALE@IDLE_A`, `AMB@WORLD_HUMAN_MOBILE_FILM_SHOCKING@FEMALE@EXIT`, `amb@world_human_clipboard@male@base`, `amb@world_human_clipboard@male@idle_a`, `amb@world_human_clipboard@male@idle_b`

**Models and props** (170) - `prop_amb_phone`, `prop_npc_phone`, `vw_prop_vw_offchair_03`, `prop_cs_ciggy_01`, `p_cs_joint_01`, `ba_prop_battle_headphones_dj`, `prop_amb_beer_bottle`, `prop_pencil_01`, `p_amb_clipboard_01`, `prop_cs_paper_cup`, `prop_cs_mouse_01`, `prop_off_chair_04_s`, `prop_cs_beer_bot_01`, `prop_keyboard_01b`, `a_m_y_clubcust_01`, `a_m_y_clubcust_02`, `a_m_y_clubcust_03`, `g_m_m_casrn_01`, `g_m_y_strpunk_02`, `g_f_y_lost_01`, `a_f_y_business_01`, `g_m_y_ballaorig_01`, `p_tumbler_01_s`, `apa_prop_cs_plastic_cup_01`, `p_cs_shot_glass_2_s`, `prop_ld_can_01`, `A_M_Y_Ktown_01_Korean_FULL_01`, `A_F_Y_Vinewood_03_Chinese_MINI_01`, `A_F_Y_EastSA_03_Latino_MINI_01`, `S_M_M_AUTOSHOP_01_WHITE_01`, `prop_bar_stool_01`, `sf_prop_sf_headphones_dj`, `hei_prop_heist_off_chair`, `sf_prop_sf_s_mixer_02a`, `sf_prop_sf_s_mixer_02b`, `sf_prop_sf_drum_stick_01a`, `prop_mug_01`, `prop_cs_wrench`, `p_amb_coffeecup_01`, `a_f_y_clubcust_01`, `a_f_y_clubcust_02`, `a_f_y_clubcust_03`, `a_f_y_beach_01`, `s_m_m_studioassist_02`, `a_m_y_smartcaspat_01`, `g_m_m_korboss_01`, `prop_beer_logger`, `p_wine_glass_s`, `ba_prop_battle_vape_01`, `ex_prop_offchair_exec_04`, `prop_notepad_01`, `sf_prop_sf_tablet_01a`, `S_M_M_GENERICSECURITY_01_WHITE_MINI_02`, `S_M_M_GENERICSECURITY_01_BLACK_MINI_01`, `S_M_M_GENERICSECURITY_01_LATINO_MINI_01`, `G_M_Y_Korean_01_Korean_MINI_02`, `A_M_M_FatLatin_01_Latino_FULL_01`, `A_M_Y_Vinewood_03_Latino_MINI_01`, `A_F_M_Bodybuild_01_Black_FULL_01`, `A_M_Y_GenStreet_02_Latino_FULL_01` ...

**Audio banks** (1) - `DLC_BATTLE/BTL_CLUB_OPEN_TRANSITION_CROWD`

**Text labels** (18) - `BUMP`, `IDLE`, `LOITER`, `TUMSAUD`, `GREET`, `BYE`, `HS4BPAU`, `HOWSITGOING`, `NULL`, `HS4PAAU`, `FOREVER`, `X24LAAU`, `S24JAUD`, `FXIGAUD`, `HS4PIAU`, `HAO`, `BENNY`, `SECUROMECH`

## Native vocabulary

Most-called natives inside the code unique to this script:

`GET_RANDOM_INT_IN_RANGE` (148), `PLAYER_ID` (111), `IS_STRING_NULL_OR_EMPTY` (97), `DOES_ENTITY_EXIST` (44), `SET_ENTITY_VISIBLE` (36), `PLAYER_PED_ID` (34), `GET_ENTITY_COORDS` (30), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (20), `NETWORK_GET_ENTITY_FROM_NETWORK_ID` (19), `FREEZE_ENTITY_POSITION` (19), `GET_DISTANCE_BETWEEN_COORDS` (15), `GET_CLOUD_TIME_AS_INT` (15), `IS_ENTITY_VISIBLE` (14), `CLEAR_PED_TASKS` (14), `SET_ENTITY_ALPHA` (13), `IS_SYNCHRONIZED_SCENE_RUNNING` (13), `GET_SYNCHRONIZED_SCENE_PHASE` (12), `GET_PED_INDEX_FROM_ENTITY_INDEX` (12), `IS_MODEL_VALID` (12), `IS_ENTITY_IN_ANGLED_AREA` (12), `REMOVE_ANIM_DICT` (11), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (11), `SET_PED_PROP_INDEX` (11), `PLAY_FACIAL_ANIM` (10), `TO_FLOAT` (10), `IS_ENTITY_DEAD` (10), `GET_ANIM_DURATION` (9), `FLOOR` (9), `ARE_STRINGS_EQUAL` (9), `NETWORK_IS_IN_MP_CUTSCENE` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x4 · `0.1f` x2 · `0.8f` x2 · `0.95f` x1

## Other strings

Literals whose consuming native was not classified:

`GENERIC_HI`, `GENERIC_BYE`, `GENERIC_HOWSITGOING`, `GENERIC_HOWS_IT_GOING`, `IDLE_OTHER_PLAYER`, `BYE_OTHER_PLAYER`, `BYE_OWNER`, `GREET_OTHER_PLAYER`, `HOWSITGOING_OTHER_PLAYER`, `TRAVEL_WHERE_TO`, `HOWSITGOING_OWNER`, `GENERIC_YES`, `IDLE_OWNER`, `SM25_RAF`, `GREET_OWNER`, `BUMP_OTHER_PLAYER`, `ex_p_ex_tumbler_01_s`, `xm3_prop_xm3_pipette_01a`, `h4_prop_h4_engine_fusebox_01a`, `XM4_CHAT_IDLE`, `HS4PA_PS_54`, `GENERAL_CHAT`, `LOITER_FACTORY_OWNED`, `SUM25_JUNKYARD_DONE`, `SUM25_CASINO_ASSASSIN_DONE`, `SUM25_LOCKUP_INT_DONE`, `SUM25_ESCORT_FLATBED_DONE`, `SUM25_LEFT_FOR_DEAD_DONE`, `SUM25_CLEAR_COMPETITOR_DONE`, `IDLE_CAYO_BACKUP_USED`

---

Source: `decompiled_scripts/am_mp_peds.c`
