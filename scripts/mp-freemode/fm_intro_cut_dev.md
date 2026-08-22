# fm_intro_cut_dev.c

MP freemode script. 7 anim dicts; 14 models; 9 scaleforms; 2 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 11,221 |
| Functions | 232 (91 unique, 141 shared) |
| Unique lines | 5,648 (50.3% of file) |

## Assets

**Animation dictionaries** (7) - `mp_intro_seq@`, `mp_intro_seq@ig_1_lamar_drive_radio`, `amb@world_human_leaning@male@wall@back@foot_up@idle_a`, `amb@world_human_hang_out_street@male_a@base`, `mp_intro_seq@ig_1_lamar_drive_female`, `mp_intro_seq@ig_1_lamar_drive_male`, `MP_INTRO_SEQ@`

**Animations** (14) - `mp_intro_seq@ig_1_lamar_drive_female`, `mp_intro_seq@ig_1_lamar_drive_male`, `ig_1_lamar_drive_female_fem`, `ig_1_lamar_drive_male_male`, `amb@world_human_leaning@male@wall@back@foot_up@idle_a`, `idle_a`, `amb@world_human_hang_out_street@male_a@base`, `base`, `ig_1_lamar_drive_female_lamar`, `ig_1_lamar_drive_male_lamar`, `mp_intro_seq@ig_1_lamar_drive_radio`, `mp_intro_ig_1_p2`, `MP_INTRO_SEQ@`, `MP_Mech_Fix`

**Models and props** (14) - `g_m_y_mexgoon_02`, `p_cs_mp_jet_01_s`, `cheetah`, `ig_lamardavis`, `mp_m_freemode_01`, `mp_f_freemode_01`, `entityxf`, `monroe`, `feltzer2`, `frogger`, `cs_lamardavis`, `s_m_y_xmech_02`, `asterope`, `sentinel`

**Sounds** (2) - `MP_INTRO_RACE_SCENE`, `MP_INTRO_LAMAR_DRIVE_SCENE`

**Scaleform movies** (9) - `STRING`, `SET_BIG_LOGO_VISIBLE`, `OPENING_CREDITS`, `GTAV_ONLINE`, `HIDE`, `SHOW_CREDIT_BLOCK`, `ADD_NAMES_TO_CREDIT_BLOCK`, `ADD_ROLE_TO_CREDIT_BLOCK`, `SETUP_CREDIT_BLOCK`

**Particle effects** (2) - `scr_mp_plane_landing_tyre_smoke`, `scr_mp_intro_plane_exhaust`

**Text labels** (5) - `LAMAR`, `CONTRAILS`, `FMINTRO`, `NULL`, `EXTRASUNNY`

**Vehicle recordings** (3) - `FM_Intro_uber`, `FMINTRO`, `FMIntro`

**Interiors and entity sets** (1) - `hei_dlc_garage_high_new`

**Scripts launched** (1) - `fm_intro`

**Hashed names** (2) - `GtaMloRoom001`, `ss1_rd1_03`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (132), `SET_PED_COMPONENT_VARIATION` (96), `PLAYER_PED_ID` (77), `CLEAR_PED_PROP` (72), `DOES_ENTITY_EXIST` (63), `CLEAR_BIT` (50), `IS_ENTITY_DEAD` (45), `SET_VEHICLE_MOD` (45), `IS_VEHICLE_DRIVEABLE` (38), `HAS_MODEL_LOADED` (29), `SET_MODEL_AS_NO_LONGER_NEEDED` (29), `PRELOAD_VEHICLE_MOD` (29), `SET_ENTITY_VISIBLE` (25), `PLAYER_ID` (23), `REQUEST_MODEL` (23), `IS_CUTSCENE_PLAYING` (22), `GET_CUTSCENE_TIME` (21), `IS_PED_INJURED` (19), `SET_SYNCHRONIZED_SCENE_PHASE` (19), `TASK_SYNCHRONIZED_SCENE` (17), `FREEZE_ENTITY_POSITION` (16), `GET_CURRENT_LANGUAGE` (16), `NETWORK_OVERRIDE_CLOCK_TIME` (15), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (15), `CREATE_SYNCHRONIZED_SCENE` (15), `SET_ENTITY_COORDS` (14), `REGISTER_ENTITY_FOR_CUTSCENE` (14), `ATTACH_SYNCHRONIZED_SCENE_TO_ENTITY` (14), `SET_CAM_PARAMS` (13), `TASK_ENTER_VEHICLE` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.3f` x52 · `0.16f` x44 · `-1038.78f` x13 · `-2732.61f` x13 · `19.08f` x13 · `95.9455f` x8 · `-2237.39f` x5 · `-333.52f` x5 · `12.47f` x5 · `0.0572f` x5 · `184.1746f` x5 · `-0.5186f` x4 · `0.8056f` x4 · `2.2245f` x4 · `0.5533f` x4 · `-0.4552f` x4 · `-0.4977f` x4 · `0.5449f` x4 · `33.3479f` x4 · `-200.8225f` x4 · `302.9014f` x4 · `0.7306f` x3 · `40.033f` x3 · `-195.2f` x3

## Other strings

Literals whose consuming native was not classified:

`FM_1AU`, `left`, `right`, `animdir`, `producer`, `vpcre`, `execpro`, `FM_LAM2`, `FM_LAM1`, `HUD_COLOUR_FRIENDLY`, `MP_Female_Character`, `HUD_COLOUR_NET_PLAYER1`, `HUD_COLOUR_NET_PLAYER2`, `visdes`, `qasup`, `artdir`, `asstecdir`, `HUD_COLOUR_NET_PLAYER3`, `senprog`, `socclub`, `concre`, `MP_Male_Character`, `FM_INTRO_DRIVE_END`, `feltzer2`, `monroe`, `cheetah`, `FM_Intro_uber`, `techdir`, `assartdir`

---

Source: `decompiled_scripts/fm_intro_cut_dev.c`
