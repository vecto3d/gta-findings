# gb_biker_contraband_sell.c

MP gang ops script. 4 anim dicts; 52 models; 5 particle effects.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 178,563 |
| Functions | 2,407 (476 unique, 1,931 shared) |
| Unique lines | 24,102 (13.5% of file) |

## Assets

**Animation dictionaries** (4) - `move_m@bag`, `veh@drivebystd_ds_grenades`, `veh@drivebystd_ps_grenades`, `anim@MP_FIREWORKS`

**Animations** (3) - `P_cargo_chute_S`, `P_cargo_chute_S_crumple`, `P_cargo_chute_S_deploy`

**Models and props** (52) - `s_m_m_ciasec_01`, `s_m_y_construct_01`, `a_f_y_runner_01`, `g_m_m_chigoon_02`, `g_m_m_armgoon_01`, `a_m_y_busicas_01`, `a_m_y_hipster_01`, `a_m_y_runner_02`, `a_m_o_tramp_01`, `a_f_y_business_04`, `a_m_y_business_03`, `g_m_y_korean_01`, `g_m_y_strpunk_01`, `a_m_y_hippy_01`, `a_m_m_hillbilly_02`, `g_m_m_chiboss_01`, `g_m_m_armboss_01`, `g_m_y_azteca_01`, `a_m_m_soucent_04`, `a_m_y_beachvesp_01`, `a_m_y_beach_03`, `s_m_y_robber_01`, `g_m_m_korboss_01`, `g_m_y_salvagoon_01`, `g_m_y_ballaorig_01`, `a_m_y_beach_02`, `a_m_y_vinewood_01`, `a_f_y_bevhills_02`, `a_f_y_eastsa_03`, `prop_box_wood01a`, `prop_drug_package`, `g_m_m_mexboss_01`, `g_f_y_vagos_01`, `g_m_y_mexgoon_02`, `g_m_y_salvaboss_01`, `g_m_y_famca_01`, `a_f_y_hippie_01`, `a_m_y_musclbeac_01`, `prop_box_wood04a`, `prop_cardbordbox_03a`, `prop_cs_duffel_01`, `prop_makeup_trail_01_cr`, `prop_conc_blocks01a`, `PROP_HUMAN_BUM_BIN`, `hei_prop_heist_binbag`, `prop_cs_box_clothes`, `ex_prop_adv_case_sm`, `ex_prop_adv_case_sm_flash`, `a_m_m_hillbilly_01`, `prop_fnclink_03gate1`, `prop_cs_heist_bag_01`, `a_f_y_fitness_01`

**Sounds** (11) - `5s`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `Drop_Zone_Alarm`, `Boss_Message_Orange`, `GTAO_Biker_FM_Soundset`, `Altitude_Warning_Loop`, `DLC_Exec_Fly_Low_Sounds`, `Parachute_Land`, `DLC_Exec_Air_Drop_Sounds`, `Crates_Blipped`, `GTAO_Biker_Modes_Soundset`

**Speech contexts** (1) - `A_M_Y_Hippy_01_white_FULL_01`

**Particle effects** (5) - `scr_lowrider`, `scr_bike_contraband`, `scr_bike_truck_weed_smoke_cabin`, `smoke_fade`, `scr_lowrider_flare`

**Text labels** (3) - `NULL`, `LJT`, `BPLESAU`

**Decorators** (5) - `MPBitset`, `Not_Allow_As_Saved_Veh`, `ContrabandOwner`, `ContrabandDeliveryType`, `ExportVehicle`

**Doors** (1) - `prop_fnclink_03gate1`

**Hashed names** (2) - `CREATE_PROP`, `RELEASE_PROP`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (130), `PLAYER_PED_ID` (83), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (69), `SET_BIT` (62), `NET_TO_VEH` (55), `DOES_ENTITY_EXIST` (50), `PARTICIPANT_ID_TO_INT` (46), `DOES_BLIP_EXIST` (41), `IS_ENTITY_DEAD` (38), `NET_TO_PED` (36), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (34), `NET_TO_OBJ` (33), `NET_TO_ENT` (30), `GET_ENTITY_COORDS` (30), `PARTICIPANT_ID` (26), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (25), `IS_NETWORK_ID_OWNED_BY_PARTICIPANT` (24), `SET_PED_COMBAT_ATTRIBUTES` (23), `ROUND` (22), `CLEAR_BIT` (21), `SET_PED_CONFIG_FLAG` (21), `GET_RANDOM_INT_IN_RANGE` (20), `GET_SCRIPT_TASK_STATUS` (20), `TO_FLOAT` (19), `SET_BLIP_ROUTE` (18), `INT_TO_PLAYERINDEX` (17), `REMOVE_BLIP` (16), `NETWORK_DOES_NETWORK_ID_EXIST` (15), `GET_PLAYER_PED` (14), `SET_ENTITY_INVINCIBLE` (14)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x6 · `0.25f` x4 · `1.2f` x2 · `-0.2f` x2 · `0.3f` x2 · `0.1f` x2 · `-3.4f` x2 · `1.4f` x2 · `2.1f` x2 · `210.93f` x2 · `-2022.58f` x2 · `17.65f` x2 · `299.9f` x2 · `0.7f` x2 · `-1256.457f` x1 · `-2150.702f` x1 · `12.9248f` x1 · `-1.55f` x1 · `0.05f` x1 · `0.8f` x1 · `0.18f` x1 · `0.19f` x1 · `-1.4f` x1 · `0.55f` x1

## Other strings

Literals whose consuming native was not classified:

`WORLD_HUMAN_SMOKING`, `WORLD_HUMAN_SMOKING_POT`, `WORLD_HUMAN_STAND_MOBILE`, `WORLD_HUMAN_HANG_OUT_STREET`, `rebel`, `WORLD_HUMAN_PICNIC`, `BYCB_CLY_LSC0`, `SBCONTRA_DROP`, `WORLD_HUMAN_JOG_STANDING`, `BIKER_TOOLOW`, `SB_SELL_BMRBB`, `WORLD_HUMAN_DRINKING`, `DisableFlightMusic`, `WantedMusicDisabled`, `FM_COUNTDOWN_30S_FIRA`, `SCONTRA_HLP11`, `WORLD_HUMAN_CLIPBOARD`, `SBIKER_LAND`, `BSELL_PRODHELD`, `SBCONTRA_HLPD`, `SBCONTRA_DROPP`, `SBIKERP_NWBY`, `BK_SELL_TXTM_1`, `FM_COUNTDOWN_30S`, `FM_COUNTDOWN_30S_KILL`, `WORLD_HUMAN_BINOCULARS`, `bagger`, `SCONTRA_HLP8`, `SBIKERT_HREAR`, `HUD_ATTEMPTS`

---

Source: `decompiled_scripts/gb_biker_contraband_sell.c`
