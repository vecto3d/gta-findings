# fm_impromptu_dm_controler.c

MP freemode script. 12 models; 5 scaleforms; 7 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 743,529 |
| Functions | 13,050 (730 unique, 12,320 shared) |
| Unique lines | 42,580 (5.7% of file) |

## Assets

**Models and props** (12) - `prop_tyre_spike_01`, `prop_ld_toilet_01`, `xs_prop_arena_spikes_01a`, `xs_prop_arena_spikes_01a_sf`, `Set_Crowd_C`, `Set_Crowd_A`, `Set_Crowd_B`, `Set_Crowd_D`, `Set_Team_Band_A`, `Set_Team_Band_B`, `Set_Team_Band_C`, `Set_Team_Band_D`

**Audio banks** (5) - `DLC_AWXM2018/Arena_Traps`, `dlc_awxm2018/aw_ptb_01`, `DLC_AWXM2018/AW_PTB_01`, `DLC_VINEWOOD/KOTH`, `DLC_AIRRACES/AIR_RACE_01`

**Sounds** (61) - `DLC_AW_Frontend_Sounds`, `MP_CELEB_SCREEN_ARENA_SCENE`, `Go_Kart_Death_Match_Soundset`, `MP_CELEB_SCREEN_SCENE`, `dlc_vw_koth_Sounds`, `MP_LEADERBOARD_SCENE`, `DLC_AW_Machine_Gun_Ammo_Counter_Sounds`, `MP_POSITIONED_RADIO_MUTE_SCENE`, `DLC_AW_PTB_Sounds`, `HUD_MINI_GAME_SOUNDSET`, `MP_DM_GENERAL_SCENE`, `DLC_SR_TR_General_Sounds`, `3_2_1`, `Deathmatch_Sounds`, `Start`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `Recharging_Loop`, `Zone_Held`, `Bomb_Countdown`, `MP_JOB_CHANGE_RADIO_MUTE`, `DLC_AW_Arena_Lobby_Veh_Select_To_VIP_Transition_Scene`, `DLC_AW_Arena_Lobby_Veh_Select_To_Arena_Transition_Scene`, `Countdown_3`, `Countdown_2`, `Countdown_1`, `Screen_Flash_Start`, `Finish_Win`, `Finish_Default`, `Out_of_Bounds_Explode`, `Time`, `Fire_Powerup_Amped`, `30_Secs_Remaining`, `20_Secs_Remaining`, `10_Secs_Countdown`, `Powerup_Block_Loop`, `5S`, `Fire_Loop`, `DLC_IE_VV_Gun_Player_Sounds`, `Out_Of_Ammo`, `Ctrl`, `Bomb_Passed`, `Bomb_Collected`, `snowball_kill`, `DLC_23_2_SPL_SNOWBALL_SOUNDS`, `Zone_Captured`, `Zone_Captured_Remote`, `Zone_Lost`, `Zone_Contested`, `DLC_AW_PTB_General_Scene`, `Gokart_Adversary_In_Gameplay_Scene`, `PowerupShard_Attract_Loop`, `Empty_Fire_Fail`, `Recharged`, `Weapon_Force_Change_Smoke`, `Countdown_GO`, `GO`, `Airhorn`, `DLC_TG_Running_Back_Sounds` ...

**Scaleform movies** (5) - `ADD_TEAM`, `SET_MESSAGE`, `POWER_PLAY_GENERIC`, `ADD_ICON`, `SET_ICON_TIMER`

**Particle effects** (7) - `scr_ie_vv`, `scr_bike_adversary`, `scr_ie_vv_muzzle_flash`, `scr_as_trans`, `scr_xt_trip`, `core_snow`, `scr_adversary_gunsmith_weap_change`

**Text labels** (9) - `OFF`, `SUMMARY`, `DMATCH`, `FMMC`, `FMMC_PLYLOAD`, `WINNER`, `NULL`, `FVTEE`, `NUMBER`

**Interiors and entity sets** (2) - `Arena_Room`, `xs_x18_int_01`

**Vehicle mods** (1) - `rhino`

**Scripts launched** (1) - `appinternet`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (290), `PLAYER_ID` (155), `CLEAR_BIT` (81), `TO_FLOAT` (78), `GET_PLAYER_TEAM` (76), `PLAYER_PED_ID` (76), `INT_TO_PARTICIPANTINDEX` (70), `DOES_ENTITY_EXIST` (63), `IS_PED_IN_ANY_VEHICLE` (58), `ROUND` (54), `GET_NETWORK_TIME` (49), `NETWORK_IS_PARTICIPANT_ACTIVE` (45), `NETWORK_GET_PLAYER_INDEX` (42), `PLAY_SOUND_FRONTEND` (40), `GET_PLAYER_PED` (38), `GET_VEHICLE_PED_IS_IN` (36), `GET_ENTITY_COORDS` (36), `INT_TO_PLAYERINDEX` (34), `LEADERBOARDS_WRITE_ADD_COLUMN` (30), `NETWORK_PLAYER_ID_TO_INT` (28), `NETWORK_IS_PLAYER_ACTIVE` (26), `GET_EVENT_DATA` (25), `IS_ENTITY_DEAD` (24), `IS_PED_INJURED` (24), `IS_STRING_NULL_OR_EMPTY` (23), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (21), `GET_TIME_DIFFERENCE` (21), `DRAW_MARKER` (20), `NETWORK_IS_GAME_IN_PROGRESS` (19), `VMAG` (19)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x9 · `-9999.9f` x6 · `9999.9f` x6 · `0.6f` x6 · `0.1f` x5 · `0.8f` x5 · `0.7f` x4 · `1.2f` x4 · `0.05f` x4 · `1.32f` x4 · `1.5f` x2 · `0.001f` x2 · `2943.765f` x2 · `-3859.625f` x2 · `151.1007f` x2 · `0.72f` x2 · `2.5f` x2 · `0.01f` x2 · `-323.1f` x1 · `-1970.9f` x1 · `2947.73f` x1 · `-3860.622f` x1 · `142.6144f` x1 · `2948.968f` x1

## Other strings

Literals whose consuming native was not classified:

`BK_RUN_OVER`, `MP_job_load`, `Mission`, `SeasonId`, `GB_WORK_OVER`, `CrossLine`, `AllowScoreAndRadio`, `BM_ONE_DM`, `BIGM_BOSSVBOSSORBQ`, `TIMER_TIME`, `DEFAULT_SCRIPTED_CAMERA`, `DeathFailMPIn`, `MinigameTransitionIn`, `AM_BRU_BOX`, `DM_ONE_FAR`, `DPAD_VIEW`, `DM_VOICE_TDM`, `DM_VOICE_FFA`, `PTB_AVDPLYR`, `service_earn_jobs`, `MPHud`, `HUD_TARG`, `service_spend_cash_drop`, `rallytruck`, `MP_DM_START_ALL`, `dmVars.rgFM_DEATHMATCH`, `STRAP_STRK2`, `STRAP_STRK1`, `WantedMusicDisabled`, `DisableFlightMusic`

---

Source: `decompiled_scripts/fm_impromptu_dm_controler.c`
