# gb_contraband_sell.c

MP gang ops script. 32 models; 2 particle effects.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 194,435 |
| Functions | 2,785 (379 unique, 2,406 shared) |
| Unique lines | 18,746 (9.6% of file) |

## Assets

**Animations** (3) - `P_cargo_chute_S`, `P_cargo_chute_S_crumple`, `P_cargo_chute_S_deploy`

**Models and props** (32) - `g_m_m_armgoon_01`, `g_m_y_korean_01`, `g_m_y_mexgoon_02`, `g_m_y_lost_01`, `g_f_y_lost_01`, `g_m_y_azteca_01`, `g_m_m_chigoon_02`, `s_m_y_blackops_01`, `g_m_m_mexboss_01`, `g_m_m_armboss_01`, `s_m_y_cop_01`, `s_f_y_cop_01`, `s_m_y_swat_01`, `s_m_m_fiboffice_01`, `s_m_y_sheriff_01`, `s_f_y_sheriff_01`, `s_m_y_ranger_01`, `s_f_y_ranger_01`, `s_m_m_armoured_01`, `s_m_y_pilot_01`, `s_m_y_marine_03`, `s_m_y_marine_01`, `s_m_y_marine_02`, `s_m_m_marine_01`, `s_m_m_marine_02`, `a_m_y_beach_03`, `a_m_y_busicas_01`, `g_m_y_strpunk_01`, `ex_prop_adv_case_sm`, `ex_prop_adv_case_sm_flash`, `prop_drug_package`, `prop_fnclink_03gate1`

**Sounds** (16) - `DLC_Exec_Jammer_Sounds`, `DLC_Exec_Air_Drop_Sounds`, `5s`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `Drop_Package`, `Drop_Zone_Alarm`, `Charge_Full`, `Active`, `Active_Empty`, `Charging`, `Altitude_Warning_Loop`, `DLC_Exec_Fly_Low_Sounds`, `Crates_Blipped`, `GTAO_Magnate_Boss_Modes_Soundset`, `DLC_Exec_Land_Multiple_Sounds`, `Parachute_Land`

**Particle effects** (2) - `scr_lowrider`, `scr_lowrider_flare`

**Text labels** (3) - `NULL`, `EXCALAU`, `ARMYAUD`

**Decorators** (4) - `MPBitset`, `ContrabandOwner`, `ContrabandDeliveryType`, `ExportVehicle`

**Doors** (1) - `prop_fnclink_03gate1`

## Native vocabulary

Most-called natives inside the code unique to this script:

`NET_TO_VEH` (110), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (108), `PLAYER_ID` (72), `PLAYER_PED_ID` (71), `NET_TO_PED` (70), `SET_BIT` (69), `GET_ENTITY_COORDS` (42), `DOES_ENTITY_EXIST` (39), `PARTICIPANT_ID_TO_INT` (30), `IS_ENTITY_DEAD` (30), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (28), `DOES_BLIP_EXIST` (28), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (25), `SET_PED_COMBAT_ATTRIBUTES` (23), `NET_TO_ENT` (22), `CLEAR_BIT` (21), `GET_RANDOM_INT_IN_RANGE` (21), `IS_NETWORK_ID_OWNED_BY_PARTICIPANT` (21), `PARTICIPANT_ID` (20), `GET_SCRIPT_TASK_STATUS` (20), `TO_FLOAT` (20), `NET_TO_OBJ` (19), `SET_ENTITY_INVINCIBLE` (16), `GET_DISTANCE_BETWEEN_COORDS` (14), `NETWORK_DOES_NETWORK_ID_EXIST` (13), `IS_PED_INJURED` (13), `CLEAR_HELP` (12), `GET_PLAYER_WANTED_LEVEL` (11), `REMOVE_BLIP` (11), `PLAY_SOUND_FRONTEND` (10)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`299.9f` x3 · `-2.27f` x2 · `-0.66f` x2 · `-0.2f` x2 · `210.93f` x2 · `-2022.58f` x2 · `17.65f` x2 · `-5.2f` x1 · `5.2f` x1 · `-1256.457f` x1 · `-2150.702f` x1 · `12.9248f` x1 · `0.08f` x1 · `0.7f` x1 · `0.8f` x1 · `0.18f` x1 · `0.19f` x1 · `1.5f` x1 · `0.0245f` x1 · `0.2f` x1

## Other strings

Literals whose consuming native was not classified:

`BYCB_CLY_LSC0`, `buzzard`, `SCONTRA_HLP14`, `SCONTRA_CDROP`, `SCONTRA_TIMER`, `SCONTRA_RJAM`, `SCONTRA_HLP11`, `SCONTRA_VEH_LC`, `SCONTRA_HLP10`, `ARMY_ANN1`, `gburrito`, `huntley`, `SCONTRA_HLP8`, `seashark`, `SCONT_GOHP`, `SCONTRA_HLP12`, `SCONTRA_REPAIR`, `DCONTRA_BLP`, `SCONTRA_AIRCAE`, `SCONTRA_DROP_B`, `SCONTRA_DEF`, `SCONTRA_TXT_4`, `SCONTRA_TXT_19`, `SCONTRA_TXT_18`, `SCONTRA_TXT_13`, `SCONTRA_TXT_11`, `SCONTRA_TXT_10`, `SCONTRA_TXT_12`, `SCONTRA_TXT_14`, `SCONTRA_TXT_15`

---

Source: `decompiled_scripts/gb_contraband_sell.c`
