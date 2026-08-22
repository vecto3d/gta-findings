# am_mp_car_meet_property.c

Properties and venues script. 4 anim dicts; 14 models; 5 scaleforms; 2 particle effects.

| | |
|---|---|
| Category | Properties and venues |
| Total lines | 665,682 |
| Functions | 10,281 (520 unique, 9,761 shared) |
| Unique lines | 39,460 (5.9% of file) |

## Assets

**Animation dictionaries** (4) - `ANIM@SCRIPTED@CARMEET@TUN_MEET_IG7_SANDBOX_CAR@`, `ANIM@SCRIPTED@CARMEET@TUN_MEET_IG1_MIMI@`, `ANIM@SCRIPTED@CARMEET@TUN_MEET_IG2_RACE@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`

**Animations** (2) - `BASE_mimi`, `BASE`

**Models and props** (14) - `a_m_y_carclub_01`, `ch_prop_ch_side_panel02`, `hei_prop_hei_securitypanel`, `prop_vend_soda_02`, `prop_tool_box_04`, `prop_cs_cardbox_01`, `prop_vend_soda_01`, `sf_prop_sf_vend_drink_01a`, `prop_toolchest_03`, `mt_car_meet_private_ticket`, `ig_mimi`, `prop_npc_phone`, `s_m_m_raceorg_01`, `prop_tr_flag_01a`

**Audio banks** (2) - `DLC_TUNER/DLC_Tuner_Collectibles`, `DLC_TUNER/DLC_Tuner_Car_Meet_Test_Area`

**Sounds** (10) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `NAV_UP_DOWN`, `SELECT`, `BACK`, `GTAO_Tuner_Meet_Car_Meet_Space_Scene`, `HUD_FREEMODE_SOUNDSET`, `ERROR`, `Exit_Engine_Blips`, `Lowrider_Super_Mod_Garage_Sounds`, `CANCEL`

**Scaleform movies** (5) - `SET_VEHICLE_INFOR_AND_STATS`, `FM_TWO_STRINGS`, `SET_PLAYER_NAME`, `SET_CREW_NAME`, `CLEAR_ALL`

**Particle effects** (2) - `scr_tn_meet`, `scr_tn_meet_sandbox_burnout_smoke`

**Texture dicts** (4) - `MPCarHUD`, `MPCarHUD2`, `MPCarHUD3`, `MPCarHUD4`

**Text labels** (50) - `BRSCRWTEX`, `NULL`, `67NQH763`, `02ZLN386`, `69TPF037`, `23WKN123`, `26LFV544`, `07LWB585`, `05SBZ255`, `03PTF712`, `68KWK927`, `84TFX949`, `01FYK005`, `47CYL696`, `29DBU105`, `53AYE372`, `MOODYMAN`, `60HSW264`, `B3NNY`, `09AIO297`, `ONDASP0T`, `LSC2`, `62CSB145`, `D481TCH`, `ANCESTOR`, `MADRA20`, `42OYK235`, `L1BERTY`, `46IQG452`, `88SOU906`, `69AHH012`, `88TNX911`, `07BQV306`, `65GRZ071`, `86CVG072`, `09RMJ931`, `68FTY342`, `24SAN574`, `STRING`, `24VDD860`, `OFF`, `69YWO799`, `62EBS542`, `01KQX761`, `68HYO893`, `62JDZ684`, `06NZQ185`, `15HBW365`, `BUMP`, `LSC`

**Vehicle mods** (1) - `oppressor2`

**Scripts launched** (4) - `appinternet`, `appmpjoblistnew`, `appjipmp`, `am_mp_smpl_interior_int`

**Hashed names** (7) - `prop_amb_phone`, `prop_fnclink_09b`, `tr_prop_tr_meet_coll_01`, `prop_bin_01a`, `sm_Prop_Smug_Wall_Radio_01`, `vfx_tun_sandbox_burnout_start`, `vfx_tun_sandbox_burnout_stop`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (471), `PLAYER_ID` (309), `PLAYER_PED_ID` (211), `CLEAR_BIT` (135), `DOES_ENTITY_EXIST` (85), `GET_RANDOM_INT_IN_RANGE` (49), `DISABLE_CONTROL_ACTION` (48), `GET_ENTITY_COORDS` (36), `GET_VEHICLE_PED_IS_IN` (33), `GET_ENTITY_MODEL` (31), `SET_PED_COMPONENT_VARIATION` (26), `ENABLE_CONTROL_ACTION` (26), `GET_PLAYER_PED` (25), `IS_PED_IN_ANY_VEHICLE` (24), `GET_HASH_KEY` (23), `SET_STATIC_EMITTER_ENABLED` (23), `IS_CONTROL_PRESSED` (23), `SET_ENTITY_VISIBLE` (20), `IS_STRING_NULL_OR_EMPTY` (20), `SET_PED_CONFIG_FLAG` (20), `PLAY_SOUND_FRONTEND` (20), `GET_SCRIPT_TASK_STATUS` (20), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (18), `IS_CONTROL_JUST_PRESSED` (18), `IS_SCREEN_FADED_IN` (18), `SET_MODEL_AS_NO_LONGER_NEEDED` (17), `REQUEST_STREAMED_TEXTURE_DICT` (17), `HAS_STREAMED_TEXTURE_DICT_LOADED` (17), `SET_ENTITY_CAN_BE_DAMAGED` (16), `GET_DISTANCE_BETWEEN_COORDS` (16)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x12 · `0.7f` x8 · `1113.211f` x5 · `1.5f` x5 · `3.5f` x3 · `0.75f` x3 · `0.4f` x2 · `-25.362f` x2 · `-2216.521f` x2 · `1133.307f` x2 · `-22.93f` x2 · `-2145.316f` x2 · `1154.36f` x2 · `-25.37168f` x2 · `-2171.298f` x2 · `1153.914f` x2 · `-22.62207f` x2 · `10.5f` x2 · `-2173.773f` x2 · `1155.338f` x2 · `-25.37202f` x2 · `-2141.982f` x2 · `1154.061f` x2 · `-22.62123f` x2

## Other strings

Literals whose consuming native was not classified:

`RADIO_36_AUDIOPLAYER`, `MENU_GENERAL_NEGATIVE`, `coquette4`, `TUNER_AP_MIX3_PARTD`, `mamba`, `asbo`, `sultan2`, `banshee2`, `sultanrs`, `jester3`, `buccaneer2`, `peyote2`, `cheburek`, `cheetah2`, `club`, `comet5`, `deviant`, `dominator3`, `elegy`, `ellie`, `hustler`, `faction3`, `kanjo`, `komoda`, `gauntlet5`, `gb200`, `elegy2`, `issi7`, `italigto`, `hellion`

---

Source: `decompiled_scripts/am_mp_car_meet_property.c`
