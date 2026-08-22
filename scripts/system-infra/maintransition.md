# maintransition.c

System and infrastructure script. 9 anim dicts; 41 models; 31 scaleforms.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 378,623 |
| Functions | 4,804 (1,596 unique, 3,208 shared) |
| Unique lines | 157,021 (41.5% of file) |

## Assets

**Animation dictionaries** (9) - `mp_character_creation@lineup@male_a`, `mp_character_creation@lineup@male_b`, `mp_character_creation@lineup@female_b`, `mp_character_creation@lineup@female_a`, `mp_character_creation@customise@male_a`, `mp_character_creation@customise@female_a`, `MP_HEAD_IK_OVERRIDE`, `move_m@generic`, `MP_WEAPON_DROP`

**Animations** (20) - `Loop`, `Intro`, `low_to_high`, `mp_m_freemode_01`, `DROP_LOOP`, `Profile_L_Intro`, `Profile_R_Intro`, `Loop_raised`, `Profile_L_Loop`, `Profile_R_Loop`, `react_light`, `Profile_L_Outro`, `Profile_R_Outro`, `loop`, `high_to_low`, `loop_raised`, `MP_HEAD_IK_OVERRIDE`, `MP_CREATOR_HEADIK`, `DROP_OUTRO`, `DROP_INTRO`

**Models and props** (41) - `prop_police_id_board`, `prop_police_id_text`, `prop_police_id_text_02`, `SET_DATA_SLOT`, `p_parachute_s`, `ex_prop_crate_oegg`, `ex_prop_crate_minig`, `ex_prop_crate_xldiam`, `ex_prop_crate_shide`, `ex_prop_crate_freel`, `ex_prop_crate_watch`, `frogger`, `prop_map_door_01`, `mp_m_freemode_01`, `W_ME_KNIFE_01`, `W_PI_Stungun`, `W_PI_Pistol`, `W_SB_SMG`, `W_SR_SniperRifle`, `W_AR_CarbineRifle`, `W_AR_DLC_SpecialCarbine`, `W_AR_DLC_SNSPISTOL`, `W_SG_PumpShotgun`, `W_Ex_GrenadeFrag`, `W_Ex_PE`, `W_R_GrenadeLauncher`, `W_MG_CombatMG`, `W_SG_AssaultShotgun`, `W_PI_AppPistol`, `W_LR_RPG`, `W_SR_HeavySniper`, `W_AR_AdvancedRifle`, `W_SB_MicroSMG`, `W_AR_AssaultRifle`, `W_MG_MG`, `W_SG_SAWNOFF`, `W_MG_Minigun`, `W_PI_CombatPistol`, `W_Ex_GrenadeSmoke`, `W_AM_Jerrycan`, `W_EX_Molotov`

**Audio banks** (2) - `DLC_GTAO/MUGSHOT_ROOM`, `Mugshot_Character_Creator`

**Sounds** (17) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `SELECT`, `NAV_LEFT_RIGHT`, `MP_MENU_SCENE`, `CANCEL`, `CONTINUOUS_SLIDER`, `SWITCH_TO_MP_SCENE`, `MUGSHOT_CHARACTER_CREATION_SOUNDS`, `MP_GLOBAL_SCENE`, `FBI_3_TORTURE_ZOOM`, `MP_POST_MATCH_TRANSITION_SCENE`, `NAV_UP_DOWN`, `Take_Picture`, `Lights_On`, `GTAO_MUGSHOT_ROOM_SOUNDS`, `Zoom_Out`, `Zoom_In`

**Speech contexts** (1) - `NO_VOICE`

**Scaleform movies** (31) - `SET_DATA_SLOT_EMPTY`, `SET_DATA_SLOT`, `SET_COLUMN_TITLE`, `DISPLAY_DATA_SLOT`, `SHOW_PHOTO_FRAME`, `SHOW_PHOTO_BORDER`, `OPEN_SHUTTER`, `SET_COLUMN_HIGHLIGHT`, `LOCK_MOUSE_SUPPORT`, `REMOVE`, `FADE_BAR_OUT`, `instructional_buttons`, `SAVING_FOOTER`, `SET_HEADER_TITLE`, `HUD_LOCKED`, `HUD_NOCLOUD`, `MENU_SHIFT_DEPTH`, `SET_HIGHLIGHT`, `LOCK_RIGHTMOUSE_CLICK`, `DIGITAL_CAMERA`, `SHOW_REMAINING_PHOTOS`, `SET_REMAINING_PHOTOS`, `CLOSE_SHUTTER`, `SHOW_COLUMN`, `SET_COLUMN_CAN_JUMP`, `SET_COLUMN_FOCUS`, `STRING`, `SET_DESCRIPTION`, `INIT_COLUMN_SCROLL`, `SET_BOARD`, `CLEAR_WEAPONS`

**Texture dicts** (5) - `MPEntry`, `MPOverview`, `MPWeaponsCommon`, `MPWeaponsGang0`, `MPWeaponsGang1`

**Text labels** (200) - `NONE`, `HARDY`, `OFF`, `XMAS`, `EXTRASUNNY`, `NULL`, `FCR2`, `DIABLOUS2`, `COMET3`, `AIRBUS`, `AIRTUG`, `AMBULANCE`, `ARMYTANKER`, `ARMYTAILER`, `ASEA2`, `BAGGER`, `BALLER`, `BALETRAILER`, `BARRACKS2`, `BENSON`, `BIFF`, `BISON2`, `BJXL`, `BLAZER2`, `BLIMP`, `BLISTA`, `BOATTRAILER`, `BOXVILLE`, `BOXVILLE2`, `BOXVILLE3`, `BOXVILLE4`, `BTYPE`, `BUCCANEER`, `BULLDOZER`, `BURRITO`, `BURRITO2`, `BURRITO3`, `BURRITO4`, `BURRITO5`, `BUS`, `BUZZARD2`, `CADDY`, `CADDY2`, `CAMPER`, `CARGOBOB`, `CARGOBOB2`, `CARGOBOB3`, `CARGOPLANE`, `CUTTER`, `DINGHY`, `DINGHY2`, `DLOADER`, `DOCKTRAILER`, `DOCKTUG`, `DUBSTA`, `DUBSTA2`, `DUMP`, `DUNE2`, `EMPEROR`, `EMPEROR2` ...

**Decorators** (2) - `MPBitset`, `Not_Allow_As_Saved_Veh`

**Interiors and entity sets** (1) - `v_mugshot`

**Doors** (1) - `prop_map_door_01`

**Vehicle mods** (9) - `mamba`, `bodhi2`, `chino`, `voltic`, `buccaneer`, `buccaneer2`, `chino2`, `faction`, `faction2`

**Stats** (38) - `profile_stats_last_flush`, `xbox360`, `ps3`, `xboxone`, `ps4`, `sp0_total_cash`, `sp1_total_cash`, `sp2_total_cash`, `sp0_special_ability_unlocked`, `sp1_special_ability_unlocked`, `sp2_special_ability_unlocked`, `sp0_dist_running`, `sp1_dist_running`, `sp2_dist_running`, `sp0_unarmed_hits`, `sp1_unarmed_hits`, `sp2_unarmed_hits`, `sp0_number_near_miss`, `sp1_number_near_miss`, `sp2_number_near_miss`, `sp0_plane_landings`, `sp1_plane_landings`, `sp2_plane_landings`, `sp0_dist_walk_st`, `sp1_dist_walk_st`, `sp2_dist_walk_st`, `sp0_kills_stealth`, `sp1_kills_stealth`, `sp2_kills_stealth`, `sp0_hits_mission`, `sp0_hits_peds_vehicles`, `sp1_hits_mission`, `sp1_hits_peds_vehicles`, `sp2_hits_mission`, `sp2_hits_peds_vehicles`, `sp0_parachute_current_tint`, `sp1_parachute_current_tint`, `sp2_parachute_current_tint`

**Scripts launched** (16) - `FM_maintain_cloud_header_data`, `InGameHud`, `creator`, `fm_race_creator`, `fm_deathmatch_creator`, `fm_lts_creator`, `fm_capture_creator`, `fm_survival_creator`, `basic_creator`, `freemode_creator`, `main`, `director_mode`, `ingamehud`, `startup_positioning`, `armenian3`, `trevor3`

**Hashed names** (3) - `crewLogo`, `hairOverlay`, `torsoDecal`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_SHOP_PED_APPAREL_HAVE_RESTRICTION_TAG` (2112), `PLAYER_ID` (467), `PLAYER_PED_ID` (442), `TO_FLOAT` (267), `GET_SHOP_PED_COMPONENT` (263), `ROUND` (240), `SET_BIT` (223), `REMOVE_IPL` (183), `GET_RANDOM_INT_IN_RANGE` (168), `CLEAR_BIT` (151), `IS_IPL_ACTIVE` (150), `SET_WARNING_MESSAGE_WITH_HEADER` (125), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (122), `GET_ENTITY_MODEL` (102), `PLAYSTATS_QUICKFIX_TOOL` (70), `GET_SHOP_PED_PROP` (68), `IS_PED_INJURED` (67), `IS_PC_VERSION` (66), `PLAY_SOUND_FRONTEND` (60), `STAT_CLOUD_SLOT_LOAD_FAILED` (57), `NETWORK_IS_GAME_IN_PROGRESS` (52), `PAUSE_MENU_ACTIVATE_CONTEXT` (52), `SET_PED_COMPONENT_VARIATION` (50), `DOES_ENTITY_EXIST` (50), `TASK_PLAY_ANIM` (49), `IS_WEAPON_VALID` (45), `FREEZE_ENTITY_POSITION` (44), `END_SCALEFORM_MOVIE_METHOD` (44), `VMAG` (43), `IS_PAUSE_MENU_ACTIVE` (41)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x23 · `0.2f` x8 · `0.1f` x5 · `0.3f` x4 · `0.4f` x4 · `1.5f` x4 · `-1000.129f` x4 · `-98.46554f` x4 · `402.7553f` x4 · `-98.48412f` x4 · `4.2f` x4 · `0.01f` x3 · `0.7f` x3 · `-1000.622f` x3 · `36.95373f` x3 · `-0.01934f` x3 · `25.2015f` x3 · `0.8f` x3 · `7.25f` x2 · `-656.98f` x2 · `17.14f` x2 · `-1104.657f` x2 · `-1638.481f` x2 · `4.6754f` x2

## Other strings

Literals whose consuming native was not classified:

`mp_m_freemode_01`, `mp_f_freemode_01`, `HUD_CONNPROB`, `morph_suit`, `pilot_suit`, `HUD_SPRETRNFRSH`, `heist_draw_0`, `stunt_draw_2`, `stunt_draw_1`, `HUD_QUITTING`, `QFE_PROPERTY_RM`, `heist_draw_7`, `scuba_gear`, `MPTshirtAwards3`, `stunt_draw_0`, `air_draw_0`, `apart_draw_2`, `stunt_draw_4`, `HUD_SPRETURNTRY`, `heist_draw_8`, `heist_draw_6`, `combat_gear`, `silk_pyjamas`, `silk_robe`, `luxe2_draw_0`, `heist_draw_1`, `HUD_DISCON`, `heist_draw_5`, `smoking_jacket`

---

Source: `decompiled_scripts/maintransition.c`
