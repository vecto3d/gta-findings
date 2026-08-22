# director_mode.c

SP missions script. 200 anim dicts; 200 models; 7 scaleforms; 3 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 172,706 |
| Functions | 1,524 (380 unique, 1,144 shared) |
| Unique lines | 32,509 (18.8% of file) |

## Assets

**Animation dictionaries** (200) - `anim@mp_player_intcelebrationmale@rock`, `anim@heists@team_respawn@variations@variation_a`, `anim@heists@team_respawn@variations@variation_b`, `anim@heists@team_respawn@variations@variation_c`, `anim@heists@team_respawn@variations@variation_d`, `anim@heists@team_respawn@variations@variation_e`, `anim@heists@team_respawn@variations@variation_f`, `anim@heists@team_respawn@variations@variation_g`, `anim@heists@team_respawn@pacific`, `anim@scripted@player@freemode@drugged_respawn@`, `director@character_select_intro@female`, `director@character_select_intro@male`, `anim@mp_player_intcelebrationmale@wank`, `anim@mp_player_intcelebrationmale@salute`, `anim@heists@team_respawn@fleeca`, `anim@mp_freemode_return@m@idle`, `anim@mp_freemode_return@f@idle`, `facials@creatures@retriever@bark`, `facials@creatures@pug@bark`, `ANIM_GROUP_MOVE_BALLISTIC`, `amb@code_human_in_car_mp_actions@smoke@std@ps@base`, `amb@code_human_in_car_mp_actions@smoke@bodhi@rps@base`, `amb@code_human_in_car_mp_actions@smoke@std@ds@base`, `amb@code_human_in_car_mp_actions@dance@std@ps@base`, `amb@code_human_in_car_mp_actions@dance@bodhi@rds@base`, `amb@code_human_in_car_mp_actions@dance@std@ds@base`, `anim@mp_player_intcelebrationmale@bro_love`, `anim@mp_player_intcelebrationmale@finger`, `anim@mp_player_intcelebrationfemale@finger`, `anim@mp_player_intupperrock`, `anim@mp_player_intuppersalute`, `anim@mp_player_intcelebrationmale@smoke_flick`, `anim@mp_player_intupperraining_cash`, `mp_player_inteat@burger`, `anim@mp_player_intupperface_palm`, `anim@mp_player_intupperjazz_hands`, `anim@mp_player_intuppernose_pick`, `anim@mp_player_intupperwave`, `anim@mp_player_intupperair_guitar`, `anim@mp_player_intuppersurrender`, `anim@mp_player_intuppershush`, `anim@mp_player_intupperphotography`, `anim@mp_player_intupperdj`, `anim@mp_player_intupperair_synth`, `anim@mp_player_intupperno_way`, `anim@mp_player_intupperchin_brush`, `anim@mp_player_intupperchicken_taunt`, `anim@mp_player_intupperpeace`, `anim@mp_player_intupperfinger_kiss`, `anim@mp_player_intupperyou_loco`, `anim@mp_player_intuppercry_baby`, `anim@mp_player_intuppercut_throat`, `anim@mp_player_intupperkarate_chops`, `anim@mp_player_intuppershadow_boxing`, `anim@mp_player_intupperthe_woogie`, `anim@mp_player_intupperstinker`, `anim@mp_player_intupperair_drums`, `anim@mp_player_intuppercall_me`, `anim@mp_player_intuppercoin_roll_and_toss`, `anim@mp_player_intupperbang_bang` ...

**Animations** (2) - `director@character_select_intro@male`, `director@character_select_intro@female`

**Models and props** (200) - `ig_orleans`, `prop_cs_ciggy_01`, `ig_maude`, `ig_chrisformage`, `u_f_o_moviestar`, `ig_tracydisanto`, `ig_jimmydisanto`, `u_m_y_mani`, `a_c_hen`, `u_m_m_griff_01`, `u_m_y_imporage`, `ig_mrs_thornhill`, `ig_amandatownley`, `ig_tanisha`, `s_m_m_movalien_01`, `ig_stretch`, `ig_davenorton`, `ig_stevehains`, `u_m_y_hippie_01`, `ig_beverly`, `ig_brad`, `ig_lamardavis`, `ig_patricia`, `ig_wade`, `s_m_y_mime`, `u_f_y_comjane`, `u_m_y_militarybum`, `u_m_o_finguru_01`, `s_m_y_fireman_01`, `s_m_y_factory_01`, `a_c_chickenhawk`, `a_c_cormorant`, `a_c_crow`, `a_c_seagull`, `a_c_pigeon`, `a_f_m_fatcult_01`, `a_f_m_fatbla_01`, `s_m_y_chef_01`, `a_m_m_genfat_01`, `a_f_m_fatwhite_01`, `ig_devin`, `ig_drfriedlander`, `ig_fabien`, `ig_floyd`, `ig_lazlow`, `ig_lestercrest`, `ig_nervousron`, `ig_siemonyetarian`, `ig_solomon`, `ig_taocheng`, `u_m_y_zombie_01`, `u_m_m_jesus_01`, `s_m_m_strpreach_01`, `u_m_y_baygor`, `u_m_y_pogo_01`, `a_f_y_business_03`, `u_m_y_rsranger_01`, `a_c_boar`, `a_c_cat_01`, `a_c_cow` ...

**Audio banks** (1) - `DLC_GTAO/SNACKS`

**Sounds** (24) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `SELECT`, `DLC_Dmod_Prop_Editor_Sounds`, `BACK`, `Place_Prop_Fail`, `NAV_LEFT_RIGHT`, `NAV_UP_DOWN`, `Director_Mode_No_Cars_Scene`, `Cycle_Item`, `TOGGLE_ON`, `Save_Scene`, `Delete_Placed_Prop`, `PropSize`, `Rotate_Loop`, `Move_Loop`, `Elevation_Loop`, `Load_Scene`, `Select_Placed_Prop`, `Prop_Drop_Water`, `Prop_Drop_Land`, `Place_Prop_Success`, `Reset_Prop_Position`, `CANCEL`, `WAYPOINT_SET`

**Speech contexts** (5) - `DROWNING`, `SPEECH_PARAMS_FORCE_FRONTEND`, `WAVELOAD_PAIN_MICHAEL`, `WAVELOAD_PAIN_FRANKLIN`, `WAVELOAD_PAIN_TREVOR`

**Scaleform movies** (7) - `SET_TEXT_POINT_SIZE`, `SET_DIRECTOR_MODE_TEXT`, `SET_TEXT`, `SET_BACKGROUND_IMAGE`, `CommonMenu`, `Gradient_Bgd`, `TEXTFIELD`

**Particle effects** (3) - `scr_mp_creator`, `scr_mp_splash`, `scr_mp_dust_cloud`

**Text labels** (45) - `ENTER`, `EXIT`, `BARK`, `PREV`, `ERROR`, `CALL`, `EXCITED`, `NULL`, `CLEAR`, `CLOUDS`, `OVERCAST`, `EXTRASUNNY`, `XMAS`, `SMOG`, `RAIN`, `THUNDER`, `CASTMNU`, `SETTMNU`, `FOGGY`, `FMMC`, `BOAR`, `CAT`, `COW`, `COYOTE`, `DEER`, `HUSKY`, `MTLION`, `ROAR`, `PIG`, `RABBIT`, `RETRIEVER`, `ROTTWEILER`, `SHEPHERD`, `CHICKENHAWK`, `SCREECH`, `CORMORANT`, `CROW`, `FLIGHT`, `HEN`, `SQUAWK`, `PIGEON`, `COO`, `SEAGULL`, `DOLPHIN`, `SASQUATCH`

**Relationship groups** (1) - `player`

**Interiors and entity sets** (1) - `milo_replay`

**Stats** (31) - `sp0_special_ability`, `sp1_special_ability`, `sp2_special_ability`, `_NGPSTAT_INT`, `_MP_NGPSTAT_INT`, `_LRPSTAT_INT`, `_APAPSTAT_INT`, `_LR2PSTAT_INT`, `_BIKEPSTAT_INT`, `_IMPEXPPSTAT_INT`, `_GUNRPSTAT_INT`, `_NGDLCPSTAT_INT`, `_MP_NGDLCPSTAT_INT`, `_DLCSMUGCHARPSTAT_INT`, `_GANGOPSPSTAT_INT`, `_BUSINESSBATPSTAT_INT`, `_ARENAWARSPSTAT_INT`, `_CASINOPSTAT_INT`, `_CASINOHSTPSTAT_INT`, `_SU20PSTAT_INT`, `_HISLANDPSTAT_INT`, `_TUNERPSTAT_INT`, `_FIXERPSTAT_INT`, `_DLC12022PSTAT_INT`, `_DLC22022PSTAT_INT`, `_DLC12023PSTAT_INT`, `_DLC22023PSTAT_INT`, `_DLC12024PSTAT_INT`, `_DLC22024PSTAT_INT`, `_DLC22025PSTAT_INT`, `_DLC12026PSTAT_INT`

**Scripts launched** (2) - `autosave_controller`, `appcamera`

**Hashed names** (15) - `CLEAR`, `CLOUDS`, `OVERCAST`, `HAZY`, `XMAS`, `SMOG`, `FOGGY`, `RAIN`, `THUNDER`, `TALINA_PVG`, `PAIGE_PVG`, `FEMALE_LOST_BLACK_PVG`, `FEMALE_LOST_WHITE_PVG`, `S_M_M_PARAMEDIC_01_BLACK_PVG`, `S_M_M_PARAMEDIC_01_WHITE_PVG`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (770), `DISABLE_CONTROL_ACTION` (178), `GET_ENTITY_MODEL` (98), `GET_PED_DRAWABLE_VARIATION` (94), `PLAYER_ID` (93), `ROUND` (89), `TO_FLOAT` (88), `GET_GAME_TIMER` (86), `PLAY_SOUND_FRONTEND` (81), `SET_PED_COMPONENT_VARIATION` (80), `GET_ENTITY_COORDS` (68), `IS_PED_INJURED` (62), `DOES_ENTITY_EXIST` (58), `GET_PED_TEXTURE_VARIATION` (43), `PACKED_STAT_GET_INT_STAT_INDEX` (34), `WAIT` (33), `VDIST2` (33), `SET_BIT` (33), `ARE_STRINGS_EQUAL` (32), `IS_DISABLED_CONTROL_PRESSED` (29), `GET_PACKED_NG_INT_STAT_KEY` (28), `DOES_CAM_EXIST` (27), `IS_ENTITY_DEAD` (27), `GET_GROUND_Z_FOR_3D_COORD` (26), `IS_PED_IN_ANY_VEHICLE` (26), `SET_GAME_PAUSED` (26), `SET_INPUT_EXCLUSIVE` (26), `SET_ENTITY_COORDS` (24), `GET_HASH_KEY` (21), `GET_RENDERING_CAM` (20)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`2.5f` x403 · `2.1f` x376 · `2.75f` x21 · `3.5f` x18 · `1.5f` x16 · `1.3f` x14 · `0.5f` x13 · `0.2f` x13 · `-0.05f` x13 · `1.2f` x13 · `1.6f` x11 · `8.9f` x11 · `0.1f` x10 · `3.75f` x10 · `0.3f` x9 · `0.8f` x9 · `0.6f` x8 · `0.7f` x8 · `1.4f` x8 · `0.15f` x8 · `4.5f` x7 · `3.3f` x7 · `2.25f` x7 · `-0.1f` x6

## Other strings

Literals whose consuming native was not classified:

`multiplayer_overlays`, `idle_a`, `NO_LABEL`, `enter`, `exit`, `hairOverlay`, `IDLE_A`, `torsoDecal`, `mp_m_freemode_01`, `mp_f_freemode_01`, `player_one`, `player_two`, `player_zero`, `ent_anim_cig_smoke`, `ent_anim_cig_exhale_mth`, `ent_anim_cig_exhale_nse`, `not_in_use`, `crewLogo`, `CM_EWARN`, `RemovePropMenuHelp`, `CM_RES_`, `CM_DISABLEDE1`, `rock`, `exit_trailer_male_gang`, `stt_prop_hoop_small_01`, `hc_gunman`, `GENERIC_SHOCKED_MED`, `Mask_SFX`, `MC_SR_PROP_01`, `MC_SR_PROP_02`

---

Source: `decompiled_scripts/director_mode.c`
