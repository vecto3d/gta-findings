# ingamehud.c

UI and menus script. 9 scaleforms.

| | |
|---|---|
| Category | UI and menus |
| Total lines | 122,000 |
| Functions | 1,256 (203 unique, 1,053 shared) |
| Unique lines | 11,919 (9.8% of file) |

## Assets

**Sounds** (3) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `SELECT`, `CANCEL`

**Scaleform movies** (9) - `SET_DATA_SLOT`, `PM_UGEN_NUM`, `PM_MULTI`, `SET_NEWS_CONTEXT`, `SET_BIGFEED_BODY_TEXT`, `SET_TITLE`, `GTAV_ONLINE`, `HIDE_ONLINE_LOGO`, `DISPLAY_VIEW`

**Texture dicts** (1) - `MPInventory`

**Text labels** (7) - `NUMBER`, `NULL`, `SAVESUCCFEED`, `SAVEFAILEDFEED`, `HUD_BADSPTIME_L`, `HUD_BADSPTIME`, `HUD_SAVDNWARN`

**Stats** (2) - `xbox360`, `ps3`

**Scripts launched** (1) - `timershud`

## Native vocabulary

Most-called natives inside the code unique to this script:

`CLEAR_BIT` (150), `SET_BIT` (140), `IS_STRING_NULL_OR_EMPTY` (92), `ACTIVITY_FEED_POST` (91), `ACTIVITY_FEED_CREATE` (91), `ACTIVITY_FEED_ACTION_START_WITH_COMMAND_LINE_ADD` (89), `ACTIVITY_FEED_ACTION_START_WITH_COMMAND_LINE` (89), `PLAYER_ID` (81), `PLAYER_PED_ID` (59), `SET_WARNING_MESSAGE_WITH_HEADER` (44), `NETWORK_IS_GAME_IN_PROGRESS` (26), `TO_FLOAT` (25), `ACTIVITY_FEED_ADD_INT_TO_CAPTION` (19), `IS_PED_INJURED` (18), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (18), `ACTIVITY_FEED_ADD_LITERAL_SUBSTRING_TO_CAPTION` (15), `STAT_LOAD_PENDING` (14), `IS_ENTITY_ATTACHED` (14), `STAT_CLOUD_SLOT_LOAD_FAILED` (13), `SET_PLAYER_INVINCIBLE` (13), `SET_PLAYER_CONTROL` (13), `SET_ENTITY_COLLISION` (13), `FREEZE_ENTITY_POSITION` (13), `PLAY_SOUND_FRONTEND` (11), `IS_SCREEN_FADED_OUT` (10), `ADD_TEXT_COMPONENT_INTEGER` (10), `NETWORK_IS_ACTIVITY_SESSION` (9), `NETWORK_PLAYER_ID_TO_INT` (9), `DO_SCREEN_FADE_IN` (9), `STAT_SLOT_IS_LOADED` (9)

## Other strings

Literals whose consuming native was not classified:

`HUD_CONNPROB`, `AF_FEEDGTAV`, `AF_FEEDGTAO`, `mpply_overall_badsport`, `HUD_RETURNSP`, `mpply_became_badsport_num`, `mpply_report_strength`, `TRAN_RETNFM`, `mpply_became_badsport_dt`, `AF_PLAY_MINI_COMB`, `AF_FEEDMINI`, `mpply_last_mp_char`, `ProgressReset`, `mpply_friendly`, `mpply_helpful`, `mpply_offensive_tagplate`, `mpply_offensive_ugc`, `mpply_vc_annoyingme`, `AF_SHUF_PROP_COMB`, `TRAN_J_FL`, `mpply_offensive_language`, `mpply_griefing`, `HUD_PERM`, `AF_PROPERTY`, `AF_MAKEOVER_COMB`, `PM_LAUNCH`, `TRAN_JOINFAIL`, `AF_PUBLISHED_JOB`, `AF_PUBLISHED_JOB_COMB`

---

Source: `decompiled_scripts/ingamehud.c`
