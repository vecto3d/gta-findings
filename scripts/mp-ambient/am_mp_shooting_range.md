# am_mp_shooting_range.c

MP ambient script. 13 models; 6 scaleforms.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 407,868 |
| Functions | 7,045 (194 unique, 6,851 shared) |
| Unique lines | 16,986 (4.2% of file) |

## Assets

**Animations** (3) - `idle`, `move_m@generic`, `move_f@generic`

**Models and props** (13) - `gr_prop_gr_target_01a`, `gr_prop_gr_target_01b`, `prop_golf_ball`, `prop_target_ora_purp_01`, `hei_heist_apart2_door`, `gr_prop_gr_target_04c`, `gr_prop_gr_target_05c`, `gr_prop_gr_target_04d`, `gr_prop_gr_target_05d`, `gr_prop_gr_target_04a`, `gr_prop_gr_target_05a`, `gr_prop_gr_target_04b`, `gr_prop_gr_target_05b`

**Audio banks** (1) - `TARGET_PRACTICE`

**Sounds** (19) - `HUD_MINI_GAME_SOUNDSET`, `MP_CELEB_SCREEN_SCENE`, `DLC_GR_Bunker_Shooting_Range_Sounds`, `10_SEC_WARNING`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `3_2_1`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `SELECT`, `NAV_UP_DOWN`, `DLC_GR_Bunker_Shooting_Range_Scene`, `GO`, `TIMER_STOP`, `Target_Hit_Head_Black`, `Target_Hit_Head_Red`, `Target_Hit_Body_Black`, `Target_Hit_Body_Red`, `Target_Activate`, `Target_Deactivate`

**Scaleform movies** (6) - `SET_MESSAGE`, `MP_BIG_MESSAGE_FREEMODE`, `RESET_MOVIE`, `STRING`, `NUMBER`, `COUNTDOWN`

**Text labels** (5) - `SUMMARY`, `MULTIPLIER`, `NULL`, `WINNER`, `NUMBER`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (114), `PLAYER_ID` (113), `DISABLE_CONTROL_ACTION` (92), `SET_BIT` (41), `DOES_ENTITY_EXIST` (28), `CLEAR_BIT` (27), `GET_PLAYER_NAME` (18), `PLAY_SOUND_FRONTEND` (16), `CLEAR_HELP` (16), `IS_PED_INJURED` (14), `IS_CONTROL_JUST_PRESSED` (14), `IS_ENTITY_IN_ANGLED_AREA` (14), `SET_PLAYER_CONTROL` (11), `IS_PLAYER_CONTROL_ON` (10), `NETWORK_IS_PLAYER_A_PARTICIPANT` (10), `INT_TO_PLAYERINDEX` (9), `GET_SCRIPT_TASK_STATUS` (9), `SET_PED_CONFIG_FLAG` (9), `SET_PED_AMMO` (9), `TO_FLOAT` (8), `GET_AMMO_IN_PED_WEAPON` (8), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (7), `IS_DISABLED_CONTROL_JUST_PRESSED` (7), `STOP_AUDIO_SCENE` (7), `HAS_PED_GOT_WEAPON` (7), `GIVE_WEAPON_TO_PED` (7), `SET_SCRIPT_GFX_DRAW_ORDER` (6), `ARE_STRINGS_EQUAL` (6), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (6), `GET_PLAYER_PED` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x7 · `0.73333f` x5 · `892.3961f` x4 · `-3162.772f` x4 · `-94.38293f` x4 · `889.5731f` x4 · `-3195.06f` x4 · `-98.97154f` x4 · `0.01f` x2 · `1.5f` x2 · `0.44f` x2 · `-1.5f` x2 · `0.178f` x2 · `0.25f` x1 · `1.75f` x1 · `-0.25f` x1 · `0.13f` x1 · `-0.41f` x1 · `0.14f` x1 · `-2.85f` x1 · `-0.26f` x1 · `0.7866f` x1 · `2.2904f` x1 · `0.7608f` x1

## Other strings

Literals whose consuming native was not classified:

`IB_QUIT`, `**Invalid**`, `MP_SR_IN_USE`, `CELEBRATION_WINNER`, `MP_SR_HELP_3`, `MP_SR_HELP_4`, `MP_SR_HELP_5`, `MP_SR_HELP_1`, `MP_SR_HELP_2`, `MP_SR_START_SP`, `MP_SR_START_MP`, `MP_SR_SUM_I_2`, `MP_SR_SUM_I_3`, `MP_SR_SUM_I_4`, `MP_SR_SUM_T_7`, `MP_Celeb_Preload_Fade`, `DeathFailMPIn`, `MinigameEndNeutral`, `MP_SR_MENU_2`, `ITEM_SELECT`, `MP_SR_SCORE`, `MP_SR_REWARD_3`, `MP_SR_REWARD_2`, `MP_SR_REWARD_1`, `AMMO_REWARD`, `MP_SR_RENO`, `SNK_MNU`, `MP_SR_SUM_I_1`, `MP_SR_SUM_T_8`, `MP_SR_QUIT`

---

Source: `decompiled_scripts/am_mp_shooting_range.c`
