# fm_maintain_transition_players.c

MP freemode script. 13 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 53,963 |
| Functions | 762 (164 unique, 598 shared) |
| Unique lines | 6,092 (11.3% of file) |

## Assets

**Models and props** (13) - `Set_Pit_Fence_Closed`, `Set_Pit_Fence_Demolition`, `Set_Pit_Fence_Oval`, `set_pit_fence_ovala`, `set_pit_fence_ovalb`, `Set_Pit_Fence_Wall`, `set_wall_no_pit`, `set_centreline_dystopian_05`, `set_centreline_scifi_05`, `Set_CentreLine_Wasteland_05`, `Set_Turrets`, `set_turrets_scifi`, `set_turrets_wasteland`

**Sounds** (6) - `DLC_MPHEIST_LOBBY_SCENE`, `MP_LOBBY_ALLOW_SPEECH_SCENE`, `MP_LOBBY_SCENE`, `DLC_MPHEIST_TRANSITION_TO_APT_FADE_IN_RADIO_SCENE`, `DLC_MPHEIST_TRANSITION_TO_APT_FADE_OUT_AMB_SCENE`, `DLC_AW_Arena_Lobby_Bink_Playing_Scene`

**Texture dicts** (2) - `BANNER_RACE_REMIX`, `bg_texture`

**Text labels** (13) - `NULL`, `HBMB`, `BMBL`, `BZBT`, `FWAR`, `TGTM`, `WRCK`, `CRNG`, `HCTM`, `GMST`, `APOC`, `SCIFI`, `CONS`

**Interiors and entity sets** (1) - `xm_x17dlc_int_02`

**Scripts launched** (11) - `am_mp_smpl_interior_int`, `am_mp_smpl_interior_ext`, `am_mp_defunct_base`, `fake_interiors`, `emergencycalllauncher`, `net_cloud_mission_loader`, `FMMC_Launcher`, `freemode_clearGlobals`, `am_doors`, `AM_MP_PROPERTY_INT`, `base_lounge_seats`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (37), `SET_BIT` (24), `PLAYER_PED_ID` (24), `HIDE_HUD_COMPONENT_THIS_FRAME` (17), `TO_FLOAT` (15), `REQUEST_SCRIPT` (13), `CLEAR_BIT` (11), `NETWORK_IS_ACTIVITY_SESSION` (9), `IS_AUDIO_SCENE_ACTIVE` (9), `STOP_AUDIO_SCENE` (8), `SET_SCRIPT_GFX_DRAW_BEHIND_PAUSEMENU` (7), `CUSTOM_MINIMAP_SET_BLIP_OBJECT` (7), `CUSTOM_MINIMAP_CREATE_BLIP` (7), `DISPLAY_RADAR` (6), `START_AUDIO_SCENE` (6), `IS_PLAYER_SWITCH_IN_PROGRESS` (5), `IS_VALID_INTERIOR` (5), `REQUEST_STREAMED_TEXTURE_DICT` (4), `IS_TVSHOW_CURRENTLY_PLAYING` (4), `GET_ENTITY_COORDS` (4), `GET_ENTITY_HEADING` (4), `SET_ENTITY_COORDS` (3), `NETWORK_IS_GAME_IN_PROGRESS` (3), `SET_TV_CHANNEL` (3), `CUSTOM_MINIMAP_SET_ACTIVE` (3), `SET_GPS_CUSTOM_ROUTE_RENDER` (3), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (3), `START_NEW_SCRIPT` (3), `HAS_STREAMED_TEXTURE_DICT_LOADED` (3), `DRAW_SPRITE` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x6 · `95.9464f` x3 · `-194.2056f` x2 · `-1853.75f` x2 · `70.3345f` x2 · `0.4751f` x2 · `0.5249f` x2 · `-209.434f` x2 · `305.016f` x2 · `345.0041f` x1 · `4842.001f` x1 · `-59.9997f` x1 · `-10.0011f` x1 · `131.0271f` x1 · `42.6052f` x1 · `3.5688f` x1 · `7.9792f` x1 · `4.1641f` x1 · `12.5f` x1 · `-209.867f` x1 · `306.969f` x1 · `0.1f` x1

## Other strings

Literals whose consuming native was not classified:

`AW_LOBBY_MUSIC_START`, `mpply_non_cheater_cash`, `mpply_automute_message`, `mpply_started_mp`, `BANNER_RACE_FLAG`, `Xs_arena_interior`, `MPArenaLobby`, `Creator`, `BANNER_RACE_REMIX_1`, `BANNER_RACE_REMIX_2`, `BANNER_RACE_REMIX_3`, `BANNER_RACE_REMIX_4`, `BANNER_RACE_REMIX_5`, `BANNER_RACE_FLAG_2`, `am_mp_arena_garage`, `AWTV_START`, `END_OF_MOVIE_MARKER`, `LOOP_`, `ciARENA_JOB_TYPE_INVALID`, `INTR_`, `CLIP_ACTN_`, `CLIP_`, `MobileRadioInGame`, `FMMC_STARTTRAN`, `FMMC_STTRANOC`, `DEFAULT_SCRIPTED_CAMERA`, `HAND_SHAKE`, `MotionState_Walk`

---

Source: `decompiled_scripts/fm_maintain_transition_players.c`
