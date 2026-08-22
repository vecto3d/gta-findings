# celebrations.c

Ambient world script. 19 models; 15 scaleforms.

| | |
|---|---|
| Category | Ambient world |
| Total lines | 440,986 |
| Functions | 7,502 (197 unique, 7,305 shared) |
| Unique lines | 22,947 (5.2% of file) |

## Assets

**Models and props** (19) - `p_cs_shot_glass_2_s`, `g_m_m_casrn_01`, `g_m_y_strpunk_02`, `g_f_y_lost_01`, `a_f_y_business_01`, `g_m_y_ballaorig_01`, `prop_cs_champ_flute`, `a_f_y_genhot_01`, `prop_cs_beer_bot_01`, `g_m_m_korboss_01`, `v_strip3`, `s_f_y_stripper_01`, `p_whiskey_bottle_s`, `v_rockclub`, `g_m_y_korlieut_01`, `s_m_m_highsec_04`, `ig_miguelmadrazo`, `V_Ilev_PH_CELLGATE`, `prop_off_chair_01`

**Audio banks** (1) - `HUD_321_GO`

**Sounds** (9) - `MP_CELEB_SCREEN_SCENE`, `MP_LEADERBOARD_SCENE`, `MP_LEADERBOARD_PP_SCENE`, `Pre_Screen_Stinger`, `DLC_HEIST_CELEB_STATS_SCENE`, `DLC_HEISTS_FINALE_SCREEN_SOUNDS`, `DLC_HEISTS_PREP_SCREEN_SOUNDS`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`

**Scaleform movies** (15) - `STRING`, `ADD_INCREMENTAL_CASH_WON_STEP`, `PAUSE`, `ADD_CASH_WON_TO_WALL`, `PAUSE_BEFORE_PREVIOUS_LAYOUT`, `ADD_REP_POINTS_AND_RANK_BAR_TO_WALL`, `ADD_JOB_POINTS_TO_WALL`, `ADD_CASH_TO_WALL`, `ADD_INCREMENTAL_CASH_ANIMATION_TO_WALL`, `CREATE_INCREMENTAL_CASH_ANIMATION`, `ADD_STAT_TO_TABLE`, `ADD_COMPLETE_MESSAGE_TO_WALL`, `SET_PAUSE_DURATION`, `MP_BIG_MESSAGE_FREEMODE`, `INSTRUCTIONAL_BUTTONS`

**Texture dicts** (3) - `CommonMenu`, `MPLeaderboard`, `MPHud`

**Text labels** (8) - `SUMMARY`, `CASH`, `left`, `right`, `WINNER`, `NULL`, `TREVOR`, `CELEB_WPLYRS`

**Timecycle modifiers** (1) - `bokeh_removebuzz`

**Scripts launched** (2) - `AM_MP_SMPL_INTERIOR_EXT`, `AM_MP_SMPL_INTERIOR_INT`

**Hashed names** (3) - `CongratsSplash`, `CongratSplash`, `forehead_blood`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_IPL_ACTIVE` (156), `PLAYER_ID` (131), `BEGIN_TEXT_COMMAND_SCALEFORM_STRING` (99), `END_TEXT_COMMAND_SCALEFORM_STRING` (99), `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME` (93), `TO_FLOAT` (89), `SET_BIT` (83), `REQUEST_IPL` (80), `REMOVE_IPL` (76), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (42), `BEGIN_SCALEFORM_MOVIE_METHOD` (39), `END_SCALEFORM_MOVIE_METHOD` (39), `DOES_ENTITY_EXIST` (29), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_BOOL` (24), `PLAYER_PED_ID` (23), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_FLOAT` (21), `SET_CUTSCENE_ENTITY_STREAMING_FLAGS` (21), `ARE_STRINGS_EQUAL` (19), `IS_SCREEN_FADED_OUT` (17), `IS_SCREEN_FADED_IN` (16), `IS_STRING_NULL_OR_EMPTY` (14), `DO_SCREEN_FADE_IN` (14), `ANIMPOSTFX_STOP` (13), `IS_AUDIO_SCENE_ACTIVE` (12), `SET_PED_COMPONENT_VARIATION` (12), `IS_SCREEN_FADING_IN` (12), `SET_GAME_PAUSES_FOR_STREAMING` (11), `CLEAR_BIT` (11), `HAS_ANIM_EVENT_FIRED` (11), `GET_HASH_KEY` (11)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x6

## Other strings

Literals whose consuming native was not classified:

`CELEB_ELITE_CH`, `MP_Celeb_Preload_Fade`, `MP_1`, `CH_END_9ST`, `HeistCelebPass`, `MP_2`, `HeistCelebPassBW`, `CELEB_COMPLETE`, `Apa_V_mp_h_01_A`, `Apa_V_mp_h_02_A`, `Apa_V_mp_h_03_A`, `Apa_V_mp_h_04_A`, `Apa_V_mp_h_05_A`, `Apa_V_mp_h_06_A`, `Apa_V_mp_h_07_A`, `Apa_V_mp_h_08_A`, `Apa_V_mp_h_01_B`, `Apa_V_mp_h_02_B`, `Apa_V_mp_h_03_B`, `Apa_V_mp_h_04_B`, `Apa_V_mp_h_05_B`, `Apa_V_mp_h_06_B`, `Apa_V_mp_h_07_B`, `Apa_V_mp_h_08_B`, `Apa_V_mp_h_01_C`, `Apa_V_mp_h_02_C`, `Apa_V_mp_h_03_C`, `Apa_V_mp_h_04_C`, `Apa_V_mp_h_05_C`

---

Source: `decompiled_scripts/celebrations.c`
