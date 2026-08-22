# creator.c

Creators script. 2 models; 6 scaleforms.

| | |
|---|---|
| Category | Creators |
| Total lines | 184,634 |
| Functions | 1,786 (184 unique, 1,602 shared) |
| Unique lines | 17,840 (9.7% of file) |

## Assets

**Models and props** (2) - `p_rLB3vwrESvRP3-uC9BEQ`, `a_m_y_stlat_01`

**Sounds** (8) - `CREATOR_SCENES_AMBIENCE`, `SELECT`, `HUD_DEATHMATCH_SOUNDSET`, `NAV_UP_DOWN`, `ERROR`, `BACK`, `EDIT`, `DELETE`

**Scaleform movies** (6) - `SET_DATA_SLOT`, `MP_MISSION_DETAILS_CARD`, `PM_PLAYERS_V`, `NUMBER`, `DISPLAY_VIEW`, `SET_TITLE`

**Texture dicts** (1) - `CommonMenuTU`

**Text labels** (12) - `HIDE`, `STRING`, `NUMBER`, `FMMC_DATE2`, `NULL`, `FMMC_PLYLOAD`, `CLEAR`, `HUD_CLOUDUP`, `MP_SPINLOADING`, `FMMC_DOWNLOAD`, `SURVIVAL`, `DEATHMATCH`

**Scripts launched** (3) - `FM_Main_Menu`, `fm_main_menu`, `fm_mission_creator`

**Hashed names** (1) - `HIDE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_INT` (69), `COPY_SCRIPT_STRUCT` (63), `PLAYER_PED_ID` (42), `PLAYER_ID` (41), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (38), `DATAFILE_GET_FILE_DICT` (36), `GET_HASH_KEY` (36), `SET_BIT` (33), `IS_STRING_NULL_OR_EMPTY` (28), `ARE_STRINGS_EQUAL` (28), `DATAFILE_DELETE` (27), `ADD_TEXT_COMPONENT_SUBSTRING_TEXT_LABEL` (26), `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME` (25), `SET_PLAYER_CONTROL` (20), `CLEAR_BIT` (18), `ADD_TEXT_COMPONENT_INTEGER` (17), `GET_GAME_TIMER` (16), `DATADICT_GET_TYPE` (15), `UGC_GET_CONTENT_ID` (14), `SET_WARNING_MESSAGE_WITH_HEADER` (14), `DATADICT_GET_DICT` (13), `GET_HUD_COLOUR` (13), `UGC_GET_CONTENT_CATEGORY` (12), `UGC_GET_CONTENT_NAME` (12), `UGC_GET_CONTENT_USER_ID` (11), `GET_RENDERED_CHARACTER_HEIGHT` (11), `UGC_GET_ROOT_CONTENT_ID` (10), `IS_CONTROL_JUST_PRESSED` (10), `SET_PED_AMMO` (9), `ADD_TEXT_COMPONENT_FLOAT` (9)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.00138888f` x27 · `0.5f` x14 · `-0.05f` x9 · `0.35f` x9 · `0.00277776f` x5 · `0.165f` x2 · `0.225f` x2 · `0.59722f` x2 · `0.00390625f` x2 · `0.00416664f` x2 · `0.19f` x2 · `-273.5f` x1 · `-1911.6f` x1 · `0.034722f` x1 · `0.7f` x1 · `0.6f` x1 · `0.75f` x1 · `0.0175f` x1 · `0.035f` x1 · `-0.0755f` x1

## Other strings

Literals whose consuming native was not classified:

`type`, `subtype`, `FMMC_ENDPUBF`, `STUNT_RACE`, `CommonMenu`, `optbs`, `cam`, `RACE_LAND`, `CUSTOM_MISSION`, `mission`, `gen`, `FMMC_ENDMTYPES`, `Gradient_Bgd`, `min`, `num`, `rank`, `FMMC_DOWNLOAD`, `CREATE4O_0_4`, `PM_QUIT_WARN19`, `CREATEMEN_LD`, `FMMC_ALERT`, `HUD_TUTOR`, `FMMC_LSTU`, `FMMC_DATE`, `CM_ITEM_COUNT`, `h2h`, `trntype`, `tnum`, `charcon`, `FMMC_CLOUDDWNT`

---

Source: `decompiled_scripts/creator.c`
