# fm_deathmatch_controler.c

MP freemode script. 28 models; 5 scaleforms; 9 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 758,527 |
| Functions | 13,579 (964 unique, 12,615 shared) |
| Unique lines | 49,837 (6.6% of file) |

## Assets

**Models and props** (28) - `prop_container_ld_pu`, `prop_tyre_spike_01`, `prop_ld_toilet_01`, `prop_ic_cp_bag`, `g_m_y_lost_02`, `g_m_y_mexgoon_02`, `g_m_y_ballaorig_01`, `g_m_y_korean_01`, `prop_arena_icon_flag_white`, `prop_arena_icon_flag_yellow`, `prop_arena_icon_flag_purple`, `prop_arena_icon_flag_green`, `prop_arena_icon_flag_pink`, `prop_arena_icon_flag_red`, `Set_Crowd_A`, `Set_Crowd_B`, `Set_Crowd_C`, `Set_Crowd_D`, `Set_Team_Band_A`, `Set_Team_Band_B`, `Set_Team_Band_C`, `Set_Team_Band_D`, `xs_prop_arena_pit_fire_01a`, `xs_prop_arena_pit_fire_02a`, `xs_prop_arena_pit_fire_03a`, `xs_prop_arena_pit_fire_04a`, `xs_prop_arena_spikes_01a`, `xs_prop_arena_spikes_01a_sf`

**Audio banks** (8) - `DLC_AWXM2018/AJ_Interrupts`, `DLC_AWXM2018/AV_Interrupts`, `DLC_AWXM2018/AW_PTB_01`, `DLC_VINEWOOD/KOTH`, `DLC_AIRRACES/AIR_RACE_01`, `DLC_MP2023_1/DLC_MP2023_1_HW`, `DLC_AWXM2018/Arena_Traps`, `dlc_awxm2018/aw_ptb_01`

**Sounds** (68) - `DLC_AW_Frontend_Sounds`, `Go_Kart_Death_Match_Soundset`, `MP_CELEB_SCREEN_ARENA_SCENE`, `MP_CELEB_SCREEN_SCENE`, `dlc_vw_koth_Sounds`, `MP_LEADERBOARD_SCENE`, `DLC_AW_Machine_Gun_Ammo_Counter_Sounds`, `dlc_aw_arena_speech_ducking_scene`, `HUD_MINI_GAME_SOUNDSET`, `MP_POSITIONED_RADIO_MUTE_SCENE`, `DLC_AW_PTB_Sounds`, `DLC_SR_TR_General_Sounds`, `3_2_1`, `MP_DM_GENERAL_SCENE`, `Deathmatch_Sounds`, `dlc_aw_arena_turret_scene`, `Countdown_3`, `Countdown_2`, `Countdown_1`, `Start`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `MP_JOB_CHANGE_RADIO_MUTE`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `Recharging_Loop`, `Zone_Held`, `Bomb_Countdown`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `DLC_AW_PTB_General_Scene`, `Gokart_Adversary_In_Gameplay_Scene`, `DLC_AW_Arena_Lobby_Veh_Select_To_VIP_Transition_Scene`, `DLC_AW_Arena_Lobby_Veh_Select_To_Arena_Transition_Scene`, `Weapon_Force_Change_Smoke`, `Countdown_GO`, `GO`, `Airhorn`, `DLC_TG_Running_Back_Sounds`, `ERROR`, `DPAD_WEAPON_SCROLL`, `Focus`, `DLC_AW_Trap_Controller_Sounds`, `LAND_BASED_VEHICLE_FAKE_REVS`, `30_Secs_Remaining`, `20_Secs_Remaining`, `10_Secs_Countdown`, `Finish_Win`, `Finish_Default`, `Out_of_Bounds_Explode`, `Time`, `PowerupShard_Attract_Loop`, `5S`, `Fire_Powerup_Amped`, `Out_Of_Ammo`, `Empty_Fire_Fail`, `Recharged`, `Powerup_Block_Loop`, `Screen_Flash_Start`, `Ctrl`, `Bomb_Passed`, `Bomb_Collected` ...

**Scaleform movies** (5) - `SET_MESSAGE`, `ADD_TEAM`, `POWER_PLAY_GENERIC`, `ADD_ICON`, `SET_ICON_TIMER`

**Particle effects** (9) - `scr_ie_vv`, `scr_bike_adversary`, `scr_as_trans`, `scr_xt_trip`, `scr_ie_vv_muzzle_flash`, `scr_adversary_gunsmith_weap_change`, `exp_xs_mine_slick`, `scr_tn_exp_mine_slick_nodecal`, `core_snow`

**Text labels** (16) - `CLOUDS`, `OFF`, `SUMMARY`, `DMATCH`, `FMMC`, `SMOG`, `OVERCAST`, `FMMC_PLYLOAD`, `WINNER`, `NUMBER`, `NULL`, `HALLOWEEN`, `EXTRASUNNY`, `CLEAR`, `ARANNAU`, `FVTEE`

**Decorators** (1) - `MPBitset`

**Interiors and entity sets** (2) - `Arena_Room`, `xs_x18_int_01`

**Vehicle mods** (2) - `mule`, `rhino`

**Scripts launched** (4) - `AM_MP_RC_VEHICLE`, `fm_deathmatch_controler`, `fm_race_controler`, `appinternet`

**Hashed names** (2) - `xs_x18intvip_vip_light_dummy`, `AM_MP_RC_VEHICLE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (402), `CLEAR_BIT` (143), `PLAYER_ID` (138), `PLAYER_PED_ID` (132), `DOES_ENTITY_EXIST` (122), `TO_FLOAT` (105), `INT_TO_PARTICIPANTINDEX` (89), `GET_PLAYER_TEAM` (82), `IS_PED_IN_ANY_VEHICLE` (64), `ROUND` (62), `NETWORK_IS_PARTICIPANT_ACTIVE` (61), `NETWORK_GET_PLAYER_INDEX` (56), `SET_VEHICLE_EXTRA` (49), `GET_ENTITY_COORDS` (47), `GET_VEHICLE_PED_IS_IN` (46), `PLAY_SOUND_FRONTEND` (44), `SET_PED_COMBAT_ATTRIBUTES` (42), `GET_PLAYER_PED` (40), `IS_ENTITY_DEAD` (38), `IS_PED_INJURED` (38), `INT_TO_PLAYERINDEX` (36), `GET_ENTITY_MODEL` (35), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (32), `LEADERBOARDS_WRITE_ADD_COLUMN` (30), `GET_RANDOM_INT_IN_RANGE` (28), `HAS_MODEL_LOADED` (28), `NETWORK_PLAYER_ID_TO_INT` (28), `REQUEST_MODEL` (28), `IS_VEHICLE_DRIVEABLE` (26), `NETWORK_IS_PLAYER_ACTIVE` (26)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x13 · `0.7f` x8 · `0.1f` x8 · `0.8f` x7 · `0.6f` x7 · `0.75f` x7 · `1.2f` x6 · `-0.75f` x6 · `-9999.9f` x6 · `9999.9f` x6 · `0.05f` x4 · `1.32f` x4 · `1.25f` x3 · `2800.957f` x2 · `-3930.407f` x2 · `180.493f` x2 · `-323.1f` x2 · `-1970.9f` x2 · `6.5f` x2 · `0.001f` x2 · `0.25f` x2 · `0.72f` x2 · `2.5f` x2 · `1.5f` x2

## Other strings

Literals whose consuming native was not classified:

`BK_RUN_OVER`, `MP_job_load`, `CrossLine`, `Mission`, `SeasonId`, `GB_WORK_OVER`, `TIMER_TIME`, `AM_BRU_BOX`, `AllowScoreAndRadio`, `BM_ONE_DM`, `BIGM_BOSSVBOSSORBQ`, `HUD_TARG`, `DPAD_VIEW`, `DM_VOICE_TDM`, `DM_VOICE_FFA`, `DEFAULT_SCRIPTED_CAMERA`, `DeathFailMPIn`, `MPHud`, `DM_ONE_FAR`, `PTB_AVDPLYR`, `MinigameTransitionIn`, `service_earn_jobs`, `Al_Interrupt`, `Al_Excited`, `ARENA_ANNOUNCE1`, `ARENA_JOCK`, `ARENA_ANNOUNCE3`, `BVB_MYLV`

---

Source: `decompiled_scripts/fm_deathmatch_controler.c`
