# gb_deathmatch.c

MP gang ops script. 12 models; 12 scaleforms; 7 particle effects.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 746,665 |
| Functions | 13,164 (740 unique, 12,424 shared) |
| Unique lines | 43,187 (5.8% of file) |

## Assets

**Models and props** (12) - `prop_tyre_spike_01`, `prop_ld_toilet_01`, `xs_prop_arena_spikes_01a`, `xs_prop_arena_spikes_01a_sf`, `Set_Crowd_A`, `Set_Crowd_B`, `Set_Crowd_C`, `Set_Crowd_D`, `Set_Team_Band_A`, `Set_Team_Band_B`, `Set_Team_Band_C`, `Set_Team_Band_D`

**Audio banks** (5) - `DLC_AWXM2018/Arena_Traps`, `dlc_awxm2018/aw_ptb_01`, `DLC_AWXM2018/AW_PTB_01`, `DLC_VINEWOOD/KOTH`, `DLC_AIRRACES/AIR_RACE_01`

**Sounds** (62) - `MP_CELEB_SCREEN_ARENA_SCENE`, `DLC_AW_Frontend_Sounds`, `Go_Kart_Death_Match_Soundset`, `MP_CELEB_SCREEN_SCENE`, `dlc_vw_koth_Sounds`, `MP_LEADERBOARD_SCENE`, `DLC_AW_Machine_Gun_Ammo_Counter_Sounds`, `MP_POSITIONED_RADIO_MUTE_SCENE`, `DLC_AW_PTB_Sounds`, `HUD_MINI_GAME_SOUNDSET`, `MP_DM_GENERAL_SCENE`, `DLC_SR_TR_General_Sounds`, `3_2_1`, `MP_JOB_CHANGE_RADIO_MUTE`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `Deathmatch_Sounds`, `Start`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `Recharging_Loop`, `Zone_Held`, `Bomb_Countdown`, `Countdown_3`, `DLC_AW_Arena_Lobby_Veh_Select_To_VIP_Transition_Scene`, `DLC_AW_Arena_Lobby_Veh_Select_To_Arena_Transition_Scene`, `Countdown_2`, `Countdown_1`, `Screen_Flash_Start`, `Finish_Win`, `Finish_Default`, `Out_of_Bounds_Explode`, `Time`, `Fire_Powerup_Amped`, `Fire_Loop`, `DLC_IE_VV_Gun_Player_Sounds`, `Out_Of_Ammo`, `Empty_Fire_Fail`, `Recharged`, `dlc_aw_arena_fire_pit_taking_damage_scene`, `30_Secs_Remaining`, `20_Secs_Remaining`, `10_Secs_Countdown`, `Powerup_Block_Loop`, `5S`, `Ctrl`, `Bomb_Passed`, `Bomb_Collected`, `PowerupShard_Attract_Loop`, `snowball_kill`, `DLC_23_2_SPL_SNOWBALL_SOUNDS`, `Zone_Captured`, `Zone_Captured_Remote`, `Zone_Lost`, `Zone_Contested`, `DLC_AW_PTB_General_Scene`, `Gokart_Adversary_In_Gameplay_Scene`, `Weapon_Force_Change_Smoke`, `Countdown_GO`, `GO`, `Airhorn` ...

**Scaleform movies** (12) - `ADD_TEAM`, `SET_DATA_SLOT`, `OVERRIDE_RESPAWN_TEXT`, `SET_MESSAGE`, `POWER_PLAY_GENERIC`, `ADD_ICON`, `SET_ICON_TIMER`, `CLEAR_ALL`, `SET_MAX_WIDTH`, `TOGGLE_MOUSE_BUTTONS`, `SET_BACKGROUND_COLOUR`, `DRAW_INSTRUCTIONAL_BUTTONS`

**Particle effects** (7) - `scr_ie_vv`, `scr_bike_adversary`, `scr_ie_vv_muzzle_flash`, `scr_as_trans`, `scr_xt_trip`, `core_snow`, `scr_adversary_gunsmith_weap_change`

**Text labels** (9) - `SUMMARY`, `OFF`, `DMATCH`, `FMMC`, `WINNER`, `FMMC_PLYLOAD`, `NULL`, `FVTEE`, `NUMBER`

**Decorators** (1) - `AttributeDamage`

**Interiors and entity sets** (2) - `Arena_Room`, `xs_x18_int_01`

**Vehicle mods** (1) - `rhino`

**Scripts launched** (1) - `appinternet`

**Hashed names** (1) - `PREV`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (296), `PLAYER_ID` (160), `CLEAR_BIT` (84), `GET_PLAYER_TEAM` (76), `PLAYER_PED_ID` (73), `TO_FLOAT` (72), `INT_TO_PARTICIPANTINDEX` (70), `DOES_ENTITY_EXIST` (67), `IS_PED_IN_ANY_VEHICLE` (57), `ROUND` (49), `GET_NETWORK_TIME` (48), `NETWORK_IS_PARTICIPANT_ACTIVE` (45), `GET_PLAYER_PED` (44), `NETWORK_GET_PLAYER_INDEX` (42), `PLAY_SOUND_FRONTEND` (40), `INT_TO_PLAYERINDEX` (37), `GET_VEHICLE_PED_IS_IN` (35), `GET_ENTITY_COORDS` (35), `LEADERBOARDS_WRITE_ADD_COLUMN` (30), `NETWORK_PLAYER_ID_TO_INT` (28), `NETWORK_IS_PLAYER_ACTIVE` (28), `IS_ENTITY_DEAD` (26), `GET_EVENT_DATA` (26), `IS_PED_INJURED` (25), `IS_STRING_NULL_OR_EMPTY` (24), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (22), `GET_TIME_DIFFERENCE` (21), `NETWORK_IS_GAME_IN_PROGRESS` (21), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (21), `NETWORK_HAS_CONTROL_OF_ENTITY` (20)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x9 · `-9999.9f` x6 · `9999.9f` x6 · `0.6f` x6 · `0.1f` x5 · `0.8f` x5 · `0.7f` x4 · `1.2f` x4 · `0.05f` x4 · `1.32f` x4 · `2.5f` x2 · `0.001f` x2 · `2943.765f` x2 · `-3859.625f` x2 · `151.1007f` x2 · `0.72f` x2 · `1.5f` x2 · `0.01f` x2 · `-323.1f` x1 · `-1970.9f` x1 · `0.19f` x1 · `4.5f` x1 · `3.5f` x1 · `2947.73f` x1

## Other strings

Literals whose consuming native was not classified:

`BK_RUN_OVER`, `MP_job_load`, `Mission`, `SeasonId`, `GB_WORK_OVER`, `CrossLine`, `AllowScoreAndRadio`, `BM_ONE_DM`, `BIGM_BOSSVBOSSORBQ`, `TIMER_TIME`, `tailgater`, `DeathFailMPIn`, `MinigameTransitionIn`, `AM_BRU_BOX`, `DM_ONE_FAR`, `DPAD_VIEW`, `DM_VOICE_TDM`, `DM_VOICE_FFA`, `PTB_AVDPLYR`, `service_earn_jobs`, `DEFAULT_SCRIPTED_CAMERA`, `MPHud`, `HUD_TARG`, `MP_DM_START_ALL`, `rallytruck`, `STRAP_STRK2`, `STRAP_STRK1`, `WantedMusicDisabled`, `DisableFlightMusic`, `MinigameEndNeutral`

---

Source: `decompiled_scripts/gb_deathmatch.c`
