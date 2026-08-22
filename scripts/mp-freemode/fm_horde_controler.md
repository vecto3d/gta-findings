# fm_horde_controler.c

MP freemode script. 28 models; 10 scaleforms.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 584,844 |
| Functions | 10,122 (305 unique, 9,817 shared) |
| Unique lines | 28,882 (4.9% of file) |

## Assets

**Models and props** (28) - `a_m_m_hillbilly_02`, `SET_DATA_SLOT`, `ig_roccopelosi`, `s_f_y_cop_01`, `s_m_m_snowcop_01`, `s_m_y_cop_01`, `s_m_y_hwaycop_01`, `s_m_y_swat_01`, `s_f_y_sheriff_01`, `s_m_y_sheriff_01`, `s_m_m_prisguard_01`, `s_m_y_ranger_01`, `s_f_y_ranger_01`, `prop_arena_icon_flag_white`, `prop_arena_icon_flag_yellow`, `prop_arena_icon_flag_purple`, `prop_arena_icon_flag_green`, `prop_arena_icon_flag_pink`, `prop_arena_icon_flag_red`, `g_m_y_mexgoon_01`, `g_m_y_lost_01`, `g_m_y_ballaorig_01`, `g_m_y_famca_01`, `g_m_y_korean_02`, `g_m_y_salvagoon_01`, `g_m_m_armgoon_01`, `g_m_m_chigoon_01`, `prop_ic_cp_bag`

**Sounds** (13) - `MP_CELEB_SCREEN_SCENE`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `MP_POSITIONED_RADIO_MUTE_SCENE`, `SELECT`, `MP_LEADERBOARD_SCENE`, `Hit`, `RESPAWN_SOUNDSET`, `MP_WAVE_COMPLETE`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `MP_JOB_CHANGE_RADIO_MUTE`, `NAV_LEFT_RIGHT`, `HORDE_COOL_DOWN_TIMER`

**Scaleform movies** (10) - `STRING`, `PAUSE_BEFORE_PREVIOUS_LAYOUT`, `ADD_WAVE_REACHED_TO_WALL`, `CELEB_WAVE_NUMBER`, `START_NEW_ORDER`, `END_NEW_ORDER`, `SET_ITEM_TEXT_RIGHT`, `SHOW_PLAYER_VOTE`, `DISPLAY_LOBBY_LIST_VIEW`, `NUMBER`

**Text labels** (8) - `NUMBER`, `SUMMARY`, `STRING`, `NULL`, `FMHRD`, `FMMC`, `FMMC_PLYLOAD`, `LEECHRMDR`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (236), `PLAYER_PED_ID` (91), `PARTICIPANT_ID_TO_INT` (83), `NET_TO_PED` (75), `SET_BIT` (67), `INT_TO_PARTICIPANTINDEX` (41), `CLEAR_BIT` (40), `NETWORK_IS_PARTICIPANT_ACTIVE` (33), `DOES_ENTITY_EXIST` (31), `IS_ENTITY_DEAD` (30), `NETWORK_GET_PLAYER_INDEX` (29), `NET_TO_VEH` (27), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (27), `SET_PED_COMBAT_ATTRIBUTES` (24), `NETWORK_DOES_NETWORK_ID_EXIST` (23), `TO_FLOAT` (23), `NETWORK_GET_PLAYER_INDEX_FROM_PED` (21), `DATADICT_GET_INT` (21), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (20), `GET_PLAYER_TEAM` (16), `GET_RANDOM_INT_IN_RANGE` (14), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (14), `GET_ENTITY_COORDS` (13), `SET_ENTITY_HEALTH` (13), `GET_PLAYER_PED` (13), `BEGIN_SCALEFORM_MOVIE_METHOD` (13), `END_SCALEFORM_MOVIE_METHOD` (13), `PLAY_SOUND_FRONTEND` (12), `VMAG` (12), `GET_SCRIPT_TASK_STATUS` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.03749976f` x10 · `0.217f` x6 · `0.3f` x3 · `0.5f` x3 · `0.1f` x2 · `0.213f` x2 · `2.5f` x2 · `0.122f` x1 · `0.28f` x1 · `0.6f` x1 · `0.25f` x1 · `0.15f` x1 · `0.185f` x1 · `0.216f` x1 · `0.23f` x1 · `-86.29383f` x1 · `-759.7908f` x1 · `43.21743f` x1 · `-78.53474f` x1 · `-786.0029f` x1 · `36.35472f` x1 · `1.2f` x1 · `269.3056f` x1 · `2777.546f` x1

## Other strings

Literals whose consuming native was not classified:

`mp_s_m_armoured_01`, `MP_job_load`, `LBD_RESTART`, `SURVIVAL_TABLE`, `subtype`, `DPAD_FRIEND`, `DEFAULT_SCRIPTED_CAMERA`, `MP_Celeb_Win_Out`, `type`, `optbs`, `rad`, `CELEB_SURVIVED`, `CELEB_REACHED`, `LBD_CONT`, `FMMC_PL_STCL`, `sandking2`, `DeathFailMPIn`, `mgrk`, `mght`, `MP_SM_STOP_TRACK`, `MP_Celeb_Win`, `MP_Celeb_Lose`, `DisableFlightMusic`, `WantedMusicDisabled`, `LBD_EXT`, `HRD_WAVE1PROG`, `mp_g_m_pros_01`, `UPDATE_SLOT`, `DPAD_CREW`, `XPT_KAIE`

---

Source: `decompiled_scripts/fm_horde_controler.c`
