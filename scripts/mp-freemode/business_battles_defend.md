# business_battles_defend.c

MP freemode script. 3 anim dicts; 47 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 503,057 |
| Functions | 9,133 (412 unique, 8,721 shared) |
| Unique lines | 33,430 (6.6% of file) |

## Assets

**Animation dictionaries** (3) - `veh@helicopter@ps@idle_panic`, `mini@strip_club@lap_dance@ld_girl_a_song_a_p1`, `mini@strip_club@idles@dj@idle_01`

**Models and props** (47) - `s_m_m_security_01`, `s_m_m_bouncer_01`, `g_m_y_mexgoon_02`, `g_m_y_ballaorig_01`, `a_m_y_vinewood_03`, `s_m_m_ciasec_01`, `a_m_m_eastsa_02`, `a_m_m_malibu_01`, `a_m_y_hipster_03`, `a_m_y_vinewood_02`, `a_m_y_vinewood_01`, `a_m_y_hipster_01`, `a_f_y_bevhills_03`, `a_m_y_eastsa_01`, `a_m_m_hillbilly_02`, `ba_prop_battle_amb_phone`, `ba_prop_battle_wallet_pickup`, `ba_prop_battle_handbag`, `ba_prop_battle_vinyl_case`, `g_m_y_azteca_01`, `g_m_y_salvagoon_01`, `g_m_y_famca_01`, `g_m_y_ballaeast_01`, `a_m_y_beach_03`, `a_m_y_beach_01`, `a_f_y_juggalo_01`, `a_f_y_beach_01`, `s_m_y_robber_01`, `a_f_y_hipster_01`, `a_f_y_soucent_03`, `a_f_y_hipster_04`, `prop_boombox_01`, `s_m_y_cop_01`, `s_f_y_cop_01`, `s_m_y_swat_01`, `s_m_m_fiboffice_01`, `s_m_y_sheriff_01`, `s_f_y_sheriff_01`, `s_m_y_ranger_01`, `s_f_y_ranger_01`, `s_m_m_armoured_01`, `s_m_y_pilot_01`, `s_m_m_fibsec_01`, `prop_barrier_work05`, `prop_speaker_07`, `ba_prop_battle_dj_stand`, `ex_prop_adv_case_sm_02`

**Text labels** (4) - `COP`, `INVALID`, `NULL`, `2867813078`

**Decorators** (2) - `MPBitset`, `Not_Allow_As_Saved_Veh`

**Relationship groups** (1) - `relDefendPlayer`

**Hashed names** (12) - `A_M_M_EastSA_02_Latino_PVG`, `A_M_M_Malibu_01_White_PVG`, `A_M_Y_Hipster_03_White_PVG`, `A_M_Y_Vinewood_01_Black_PVG`, `A_F_Y_Hipster_01_White_PVG`, `A_F_Y_SouCent_03_Latino_PVG`, `A_F_Y_BevHills_04_White_PVG`, `A_F_Y_Hipster_04_White_PVG`, `A_M_Y_Vinewood_02_White_PVG`, `A_M_Y_Hipster_01_White_PVG`, `A_F_Y_BevHills_03_White_PVG`, `A_M_Y_EastSA_01_Latino_PVG`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (186), `PLAYER_ID` (175), `PLAYER_PED_ID` (161), `PARTICIPANT_ID_TO_INT` (135), `IS_ENTITY_IN_ANGLED_AREA` (56), `SET_BIT` (53), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (44), `GET_ENTITY_COORDS` (41), `NET_TO_VEH` (39), `DOES_BLIP_EXIST` (32), `GET_SCRIPT_TASK_STATUS` (31), `IS_PED_INJURED` (30), `IS_PED_IN_ANY_VEHICLE` (29), `IS_PED_IN_ANY_HELI` (25), `SET_PED_PROP_INDEX` (24), `DOES_ENTITY_EXIST` (23), `SET_PED_COMBAT_ATTRIBUTES` (23), `REMOVE_BLIP` (23), `VDIST2` (22), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (22), `GET_VEHICLE_PED_IS_IN` (18), `SET_RELATIONSHIP_BETWEEN_GROUPS` (18), `GET_HASH_KEY` (17), `NET_TO_ENT` (13), `NET_TO_OBJ` (13), `GET_RANDOM_FLOAT_IN_RANGE` (13), `GET_PED_IN_VEHICLE_SEAT` (12), `TO_FLOAT` (12), `VMAG` (11), `INT_TO_PARTICIPANTINDEX` (10)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`299.9f` x6 · `0.25f` x4 · `463.111f` x2 · `-718.3305f` x2 · `21.57948f` x2 · `-1107.226f` x2 · `50.35242f` x2 · `-1001.877f` x2 · `23.53138f` x2 · `81.95901f` x2 · `275.2757f` x2 · `104.3376f` x2 · `785.7111f` x2 · `-2380.751f` x2 · `16.50024f` x2 · `-1066.236f` x2 · `-2087.427f` x2 · `8.297785f` x2 · `-286.9138f` x2 · `-2496.054f` x2 · `4.414141f` x2 · `-1356.295f` x2 · `-961.3669f` x2 · `-892.5924f` x2

## Other strings

Literals whose consuming native was not classified:

`bmx`, `seashark`, `emperor`, `granger`, `police4`, `manana`, `BB_HT_PR_HLP0`, `polmav`, `sanchez`, `BB_HT_CF_HLP2`, `ld_girl_a_song_a_p1_f`, `idle_01`, `sit`, `supervolito`, `speedo`, `BTL_DELIVERING_START`, `BTL_SILENT`, `BTL_MED_INTENSITY_START`, `BTL_MED_INTENSITY`, `BTL_GUNFIGHT`, `BTL_DELIVERING`, `BTL_MUSIC_STOP`, `BTL_FAIL`, `PROVOKE_TRESPASS`, `buccaneer`, `tornado2`, `phoenix`, `peyote`, `seasparrow`, `bodhi2`

---

Source: `decompiled_scripts/business_battles_defend.c`
