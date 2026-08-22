# fm_content_drug_lab_work.c

MP freemode script. 14 anim dicts; 11 models; 16 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 521,770 |
| Functions | 11,143 (745 unique, 10,398 shared) |
| Unique lines | 21,709 (4.2% of file) |

## Assets

**Animation dictionaries** (14) - `get_up@standard`, `missfam5_blackout`, `move_m@drunk@a`, `anim@GangOps@Hanger@FUSE_BOX@`, `move_m@drunk@verydrunk`, `anim@scripted@freemode@ufo_invasion@ufo_float@male@`, `anim@scripted@player@freemode@ig4_chem_pour@heeled@`, `anim@scripted@player@freemode@ig4_chem_pour@male@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@apt_trans@garage`, `ANIM@SCRIPTED@PLAYER@FREEMODE@TUN_PREP_GRAB_MIDD_IG3@HEELED@`, `ANIM@SCRIPTED@PLAYER@FREEMODE@TUN_PREP_GRAB_MIDD_IG3@MALE@`, `anim@mp_player_intmenu@key_fob@`, `missmic2@franklin_beckon`

**Animations** (5) - `get_up@standard`, `front`, `SWITCH_ON_BOX`, `anim@scripted@freemode@ufo_invasion@ufo_float@male@`, `react_upperbody`

**Models and props** (11) - `prop_gascyl_04a`, `ba_prop_battle_drug_package_02`, `bkr_prop_clubhouse_laptop_01a`, `s_m_m_movalien_01`, `w_ch_jerrycan`, `prop_tv_stand_01`, `s_m_m_chemsec_01`, `s_m_m_gentransport`, `s_m_m_security_01`, `s_m_y_grip_01`, `g_m_m_chemwork_01`

**Audio banks** (6) - `DLC_CM2022/CM2022_FREEMODE_01`, `BARRY_01_ALIEN_A`, `BARRY_01_ALIEN_B`, `BARRY_01_ALIEN_C`, `DLC_MPSUM2/MPSUM2_Generic`, `TAXI_VOMIT`

**Sounds** (16) - `DAX_1_4_Mixscenes_White_Fade`, `DLC_CM2022_DRUG_TRIP_SPRINKLERS_SCENE`, `GTAO_Script_Doors_Faded_Screen_Sounds`, `dlc_xm_stealavg_sounds`, `Garage_Door_Close`, `Garage_Door_Open`, `generator_on_loop`, `handle_up`, `MIND_CONTROL`, `BARRY_01_SOUNDSET`, `FAMILY_5_YOGA_ON_DRUGS`, `FAMILY_5_WAKE_UP_VOMIT`, `DRUGS_VOMIT`, `FAMILY_5_SOUNDS`, `Install_On_Vehicle`, `GTAO_Bomb_Plant_Sounds`

**Speech contexts** (6) - `CLOWNS`, `SPEECH_PARAMS_FORCE_SHOUTED_CLEAR`, `ALIENS`, `CLOWN_DEATH`, `ALIEN_DEATH`, `A_M_O_GenStreet_01_White_FULL_01`

**Particle effects** (16) - `scr_xt_phone`, `scr_rcbarry1`, `scr_rcbarry2`, `scr_bike_business`, `scr_xt_trip`, `scr_family5`, `scr_xt_phone_duster_spray`, `scr_bike_meth_propylene_pour`, `scr_alien_impact`, `scr_alien_charging`, `scr_xt_trip_clown_death`, `scr_xt_phone_irrigation_spray`, `scr_trev_puke`, `scr_xt_phone_wreck_smoke`, `scr_xt_phone_phos_smoke`, `damage`

**Text labels** (13) - `XM3DXAU`, `13ALB800`, `UNLOCK_GOPOSOUT`, `K1FFL0M `, `01KSW928`, `ALIENS`, `CLOWNS`, `26NLN474`, `23QQN289`, `CLOTHES_UNLOCK`, `83ISJ316`, `TW1NPN3S`, `28HXN290`

**Relationship groups** (2) - `DAVORGROUPALLENEMIES`, `DAVORGROUP`

**Interiors and entity sets** (1) - `v_31_tun_swap`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (112), `SET_BIT` (44), `NET_TO_ENT` (27), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (25), `SET_PED_COMBAT_ATTRIBUTES` (22), `SET_PED_COMPONENT_VARIATION` (19), `GET_ENTITY_COORDS` (18), `DOES_ENTITY_EXIST` (17), `DOES_PARTICLE_FX_LOOPED_EXIST` (14), `CLEAR_BIT` (13), `PLAYER_PED_ID` (11), `GET_PLAYER_PED` (11), `USE_PARTICLE_FX_ASSET` (10), `REQUEST_NAMED_PTFX_ASSET` (9), `HAS_NAMED_PTFX_ASSET_LOADED` (9), `CLEAR_PED_TASKS` (9), `NETWORK_IS_PARTICIPANT_ACTIVE` (9), `GET_RANDOM_INT_IN_RANGE` (8), `SET_PED_PROP_INDEX` (8), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (8), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (8), `GET_PED_RELATIONSHIP_GROUP_HASH` (8), `SET_RELATIONSHIP_BETWEEN_GROUPS` (8), `DOES_BLIP_EXIST` (8), `DISABLE_CONTROL_ACTION` (8), `RELEASE_NAMED_SCRIPT_AUDIO_BANK` (7), `ANIMPOSTFX_STOP` (7), `REQUEST_SCRIPT_AUDIO_BANK` (7), `IS_ENTITY_PLAYING_ANIM` (7), `SET_ENTITY_COLLISION` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x5 · `1048.937f` x4 · `-39.362f` x4 · `0.5f` x4 · `-1.5f` x3 · `1045.252f` x2 · `-3194.845f` x2 · `-38.359f` x2 · `-3199.855f` x2 · `-3199.368f` x2 · `-0.01f` x2 · `-0.45f` x2 · `0.125f` x2 · `0.353f` x2 · `0.3f` x2 · `-3.5f` x2 · `0.6f` x1 · `0.99f` x1 · `0.4f` x1 · `1.2f` x1 · `-0.15f` x1 · `-0.35f` x1 · `0.7f` x1 · `2.5f` x1

## Other strings

Literals whose consuming native was not classified:

`xm3_prop_xm3_weed_set_02c`, `pos`, `xm3_prop_xm3_weed_set_01c`, `num`, `xm3_prop_xm3_weed_set_02a`, `head`, `xm3_prop_xm3_weed_set_01a`, `int`, `DrugsDrivingOut`, `xm3_prop_xm3_weed_set_02b`, `typ`, `ibs`, `xm3_prop_xm3_weed_set_01b`, `sprt`, `hclr`, `scl`, `rot`, `bsa`, `rad`, `DMT_flight`, `XM3_DAX`, `CM22_VEHICLE_ACTION`, `CM22_DELIVERING_START`, `faction2`, `sabregt2`, `blp`, `veh`

---

Source: `decompiled_scripts/fm_content_drug_lab_work.c`
