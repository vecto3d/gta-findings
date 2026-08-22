# fm_survival_controller.c

MP freemode script. 28 anim dicts; 175 models; 10 scaleforms; 18 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 630,882 |
| Functions | 11,136 (880 unique, 10,256 shared) |
| Unique lines | 55,581 (8.8% of file) |

## Assets

**Animation dictionaries** (28) - `clipset@anim@ingame@move_m@zombie@core`, `clipset@anim@ingame@move_m@zombie@strafe`, `anim@fidgets@coughs`, `anim@scripted@surv@ig2_zombie_spawn@shambler@`, `anim@scripted@surv@ig2_zombie_spawn@runner@`, `anim@scripted@cayo@ig3_und_dj@male@`, `MOVE_M@DANCING@VERY_SLOW`, `MOVE_F@DANCING@VERY_SLOW`, `anim@scripted@surv@ig3_plague_summon@female@`, `anim@scripted@surv@ig3_plague_summon@male@`, `ANIM@AMB@NIGHTCLUB_ISLAND@DANCERS@CROWDDANCE_SINGLE_PROPS@`, `clipset@anim@ingame@melee@unarmed@streamed_core_zombie`, `clipset@anim@ingame@melee@unarmed@streamed_variations_zombie`, `clipset@anim@ingame@melee@unarmed@streamed_taunts_zombie`, `ANIM@SPECIAL_PEDS@ALIEN_LANDING`, `ANIM@SCRIPTED@CAYO@IG2_WAV_POS1@HEELED@`, `ANIM@SCRIPTED@CAYO@IG2_WAV_POS2@HEELED@`, `ANIM@SCRIPTED@CAYO@IG2_WAV_POS3@HEELED@`, `ANIM@SCRIPTED@CAYO@IG2_WAV_POS4@HEELED@`, `ANIM@SCRIPTED@CAYO@IG2_WAV_POS1@MALE@`, `ANIM@SCRIPTED@CAYO@IG2_WAV_POS2@MALE@`, `ANIM@SCRIPTED@CAYO@IG2_WAV_POS3@MALE@`, `ANIM@SCRIPTED@CAYO@IG2_WAV_POS4@MALE@`, `ANIM@MOVE_F@GROOVING@`, `ANIM@MOVE_M@GROOVING@`, `ANIM_GROUP_MOVE_BALLISTIC`, `MOVE_STRAFE_BALLISTIC`, `move_ballistic_2h`

**Animations** (5) - `ANIM@SPECIAL_PEDS@ALIEN_LANDING`, `anim@scripted@surv@ig2_zombie_spawn@shambler@`, `ANIM@AMB@NIGHTCLUB_ISLAND@DANCERS@CROWDDANCE_SINGLE_PROPS@`, `INTRO_A`, `INTRO_B`

**Models and props** (175) - `a_c_deer_02`, `a_c_boar_02`, `a_c_coyote_02`, `u_m_y_juggernaut_01`, `a_c_mtlion_02`, `prop_alien_egg_01`, `prop_power_cell`, `prop_container_ld_pu`, `s_m_m_highsec_01`, `a_c_pug_02`, `g_m_m_goons_01`, `ig_taostranslator`, `ig_taostranslator2`, `ig_taocheng2`, `a_m_m_salton_01`, `a_m_m_salton_02`, `s_m_y_westsec_02`, `s_m_y_casino_01`, `s_f_y_casino_01`, `a_m_y_musclbeac_01`, `ig_taocheng`, `imp_prop_ship_01a`, `gr_prop_damship_01a`, `p_spinning_anus_s`, `s_m_m_marine_01`, `a_m_y_motox_01`, `ig_popov`, `ig_g`, `ig_paper`, `a_c_chop_02`, `ig_avon`, `ig_moodyman_02`, `ig_sessanta`, `ig_drugdealer`, `ig_jimmyboston_02`, `ig_marnie`, `g_m_m_cartelguards_01`, `g_m_m_cartelguards_02`, `g_f_importexport_01`, `g_m_importexport_01`, `s_m_m_movalien_01`, `u_m_y_rsranger_01`, `u_m_y_juggernaut_02`, `u_m_y_corpse_01`, `s_m_y_westsec_01`, `g_m_m_casrn_01`, `ig_avery`, `ig_thornton`, `ig_englishdave_02`, `a_m_y_carclub_01`, `ig_lildee`, `a_f_y_business_03`, `g_m_y_korlieut_01`, `a_m_y_business_02`, `ig_miguelmadrazo`, `g_m_m_prisoners_01`, `s_m_y_cop_01`, `s_f_y_cop_01`, `s_m_y_ranger_01`, `s_f_y_ranger_01` ...

**Audio banks** (7) - `SNOW_FOOTSTEPS`, `ICE_FOOTSTEPS`, `DLC_25-1/CP_Survival_01`, `DLC_HEIST3/CASINO_HEIST_FINALE_GENERAL_01`, `DLC_24-1/YK_Survival`, `DLC_24-1/YK_Survival_02`, `DLC_MP2023_1/DLC_MP2023_1_HW`

**Sounds** (52) - `DLC_25-1_CP_Survival_Sounds`, `MP_CELEB_SCREEN_SCENE`, `DLC_24-1_YK_Survival_Sounds`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `MP_POSITIONED_RADIO_MUTE_SCENE`, `DLC_VW_AS_Sounds`, `Generation`, `DLC_25-1_CP_Mixer_Scene`, `MP_LEADERBOARD_SCENE`, `DLC_24-1_YK_Mixer_Scene`, `SELECT`, `Hit`, `RESPAWN_SOUNDSET`, `DLC_HEISTS_BIOLAB_STEAL_EMP_FLYOVER_SCENE`, `DLC_GR_CS2_General_Scene`, `Beast_Tamer_Idle`, `MP_WAVE_COMPLETE`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `Undead_Explode`, `Initial_Spawn`, `DJ_Idle`, `DJ_Spawn`, `Skeleton_Spawn`, `Beast_Tamer_Spawn_Roar`, `MP_JOB_CHANGE_RADIO_MUTE`, `Dog_Death`, `Boar_Death`, `Deer_Death`, `Undead_Death_Fire`, `Skeleton_Death`, `Beast_Tamer_Death`, `DJ_Death`, `Undead_Death`, `Animal_Vox_Death_Panther`, `Dog_Pain`, `Boar_Pain`, `Deer_Pain`, `Skeleton_Pain`, `Animal_Vox_Pain_Panther`, `Undead_Pain`, `Ship_Loop`, `dlc_ch_heist_finale_poison_gas_coughs_sounds`, `NAV_LEFT_RIGHT`, `Out_of_Bounds`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `Time`, `Health_Pickup_Loop`, `Armour_Pickup_Loop`, `Pickup_Spawn`, `Skeleton_Movement_Loop`, `Survival_Failed`

**Scaleform movies** (10) - `STRING`, `PAUSE_BEFORE_PREVIOUS_LAYOUT`, `ADD_WAVE_REACHED_TO_WALL`, `CELEB_WAVE_NUMBER`, `NUMBER`, `START_NEW_ORDER`, `END_NEW_ORDER`, `SET_ITEM_TEXT_RIGHT`, `SHOW_PLAYER_VOTE`, `DISPLAY_LOBBY_LIST_VIEW`

**Particle effects** (18) - `scr_sb_hal`, `scr_bh_hal`, `scr_gr_def`, `scr_bike_adversary`, `scr_srr_hal`, `exp_grd_bzgas_smoke`, `scr_gr_warp_in`, `scr_sum2_hal`, `scr_sb_hal_zom_dj_mc`, `scr_sb_hal_zom_deck_float`, `scr_bh_hal_zom_plg_staff`, `scr_sb_hal_zom_split_spawn`, `scr_bh_hal_zom_plg_zone`, `scr_adversary_judgement_ash`, `scr_bh_hal_zom_exp_explosion`, `scr_srr_hal_smoke_deer`, `scr_sb_hal_zom_dj_death`, `speed`

**Text labels** (10) - `NUMBER`, `SUMMARY`, `STRING`, `NULL`, `OFF`, `FMHRD`, `FMMC`, `FMMC_PLYLOAD`, `LEECHRMDR`, `FVTEE`

**Relationship groups** (2) - `rgFM_AiHate`, `rgFM_Team0`

**Timecycle modifiers** (1) - `NoPedLight`

**Interiors and entity sets** (1) - `int_carrier_hanger`

**Scripts launched** (1) - `MP_Gameplay_Menu`

**Hashed names** (1) - `BONEMASK_UPPERONLY`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (2976), `SET_BIT` (214), `PLAYER_ID` (169), `IS_POINT_IN_ANGLED_AREA` (164), `SET_PED_PROP_INDEX` (141), `DOES_ENTITY_EXIST` (110), `GET_RANDOM_INT_IN_RANGE` (105), `SET_PED_COMBAT_ATTRIBUTES` (100), `GET_ENTITY_COORDS` (87), `CLEAR_BIT` (86), `SET_PED_CONFIG_FLAG` (78), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (69), `NETWORK_IS_PARTICIPANT_ACTIVE` (64), `NET_TO_PED` (58), `INT_TO_PARTICIPANTINDEX` (57), `DOES_SHOP_PED_APPAREL_HAVE_RESTRICTION_TAG` (57), `NET_TO_VEH` (52), `NETWORK_GET_PLAYER_INDEX` (51), `GET_ENTITY_MODEL` (47), `PLAYER_PED_ID` (47), `TO_FLOAT` (40), `GET_PLAYER_PED` (37), `IS_ENTITY_DEAD` (32), `IS_PED_INJURED` (31), `ROUND` (28), `NETWORK_HAS_CONTROL_OF_ENTITY` (28), `IS_PED_IN_ANY_VEHICLE` (27), `DOES_BLIP_EXIST` (26), `NETWORK_DOES_NETWORK_ID_EXIST` (26), `SET_ENTITY_HEALTH` (26)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`3.4f` x10 · `0.25f` x10 · `1.5f` x10 · `0.03749976f` x10 · `2.6f` x7 · `0.5f` x7 · `2.4f` x6 · `0.217f` x6 · `2.8f` x5 · `3.8f` x5 · `3.5f` x4 · `2.5f` x4 · `2.2f` x4 · `10.3f` x4 · `7.2f` x3 · `6.6f` x3 · `7.6f` x3 · `1.2f` x3 · `10.6f` x3 · `1.6f` x3 · `0.4f` x3 · `11.4f` x2 · `11.8f` x2 · `5.8f` x2

## Other strings

Literals whose consuming native was not classified:

`mp_f_freemode_01`, `mp_m_freemode_01`, `mp_s_m_armoured_01`, `MP_job_load`, `CayoToxicWater`, `squaddie`, `LBD_RESTART`, `MP_Celeb_Win_Out`, `CayoUndeadDJ`, `hc_gunman`, `morph_suit`, `action_heeled_player`, `action_player`, `action_heeled_cam`, `action_cam`, `CayoToxicWaterOut`, `SurvivalAlien`, `dlc_mp_val_f_uppr0_0`, `dlc_mp_val_f_uppr0_1`, `dlc_mp_val_f_uppr0_2`, `dlc_mp_val_f_uppr0_3`, `dlc_mp_val_f_uppr0_4`, `dlc_mp_val_f_uppr0_5`, `manchez2`, `ANIM_GROUP_MOVE_BALLISTIC`, `MOVE_STRAFE_BALLISTIC`, `low2_open_check`, `SURVIVAL_TABLE`, `SC_H_EWW_H`

---

Source: `decompiled_scripts/fm_survival_controller.c`
