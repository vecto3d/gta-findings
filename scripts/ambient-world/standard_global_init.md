# standard_global_init.c

Ambient world script. 200 models.

| | |
|---|---|
| Category | Ambient world |
| Total lines | 4,486 |
| Functions | 90 (49 unique, 41 shared) |
| Unique lines | 3,432 (76.5% of file) |

## Assets

**Models and props** (200) - `prop_radio_01`, `ch_prop_ch_service_trolley_01a`, `u_m_m_filmdirector`, `prop_const_fence02b`, `prop_offroad_bale03`, `prop_offroad_bale02`, `prop_offroad_bale01`, `prop_offroad_tyres02`, `prop_barier_conc_02a`, `prop_barier_conc_05c`, `prop_barier_conc_05a`, `prop_barier_conc_05b`, `prop_barier_conc_01a`, `prop_barrier_work05`, `prop_fnclink_03gate5`, `prop_fnclink_02gate3`, `prop_mb_sandblock_01`, `prop_mb_sandblock_02`, `prop_mb_sandblock_05_cr`, `prop_mb_sandblock_04`, `prop_mb_sandblock_03_cr`, `prop_mb_hesco_06`, `prop_plas_barier_01a`, `prop_barier_conc_02b`, `prop_barrier_work06a`, `prop_barrier_work04a`, `prop_fnclink_06a`, `prop_fnclink_06b`, `prop_fnclink_06c`, `prop_fnclink_06d`, `prop_fnccorgm_03a`, `prop_fnccorgm_03b`, `prop_fnccorgm_03c`, `prop_fnccorgm_02a`, `prop_fnccorgm_02b`, `prop_fnccorgm_02c`, `prop_fnccorgm_02d`, `prop_fnccorgm_02e`, `prop_const_fence03a_cr`, `prop_gate_cult_01_l`, `prop_gate_cult_01_r`, `prop_const_fence03b_cr`, `prop_const_fence02a`, `prop_const_fence01b_cr`, `prop_fncwood_16b`, `prop_fncwood_16c`, `prop_fnc_farm_01b`, `prop_fnc_farm_01c`, `prop_fnc_farm_01d`, `prop_fnc_farm_01e`, `prop_fnc_farm_01f`, `prop_hayb_st_01_cr`, `prop_haybale_03`, `prop_haybale_02`, `prop_haybale_01`, `prop_tyre_wall_01`, `prop_tyre_wall_02`, `prop_tyre_wall_03`, `prop_tyre_wall_04`, `prop_tyre_wall_05` ...

**Text labels** (118) - `NULL`, `JHFP7`, `JHFP8`, `DHP8A`, `AHP1`, `ANAUD`, `NONE`, `JHFP2`, `JHFP5`, `JHFP3`, `JHFP6`, `DHP2`, `DHP3`, `AHP2`, `AHP4`, `AHP6`, `AHP5`, `FHP1`, `FHP6`, `FHP7A`, `FHP7B`, `FHP2`, `FHP3`, `FHP8A`, `FHP8B`, `FHP4`, `AH1`, `AH2`, `ARM1`, `ARM2`, `ARM3`, `ASS1`, `ASS2`, `ASS3`, `ASS4`, `ASS5`, `CAR1`, `CAR2`, `CAR3`, `CAR4`, `CHN1`, `CHN2`, `DH1`, `DHP1`, `DHP2B`, `DH2A`, `DH2B`, `EXL1`, `EXL2`, `EXL3`, `FAM1`, `FAM2`, `FAM3`, `FAM4`, `FAM5`, `FAM6`, `FINI`, `FINA`, `FINB`, `FINC1` ...

**Decorators** (115) - `Player_Vehicle`, `PV_Slot`, `Previous_Owner`, `Sprayed_Vehicle_Decorator`, `Sprayed_Vehicle_Timer_Dec`, `Vehicle_Reward`, `Vehicle_Reward_Teams`, `Skill_Blocker`, `TargetPlayerForTeam`, `XP_Blocker`, `CrowdControlSetUp`, `Bought_Drugs`, `HeroinInPossession`, `CokeInPossession`, `WeedInPossession`, `MethInPossession`, `bombdec`, `bombdec1`, `bombowner`, `noPlateScan`, `prisonBreakBoss`, `cashondeadbody`, `MissionType`, `MatchId`, `TeamId`, `Not_Allow_As_Saved_Veh`, `Veh_Modded_By_Player`, `MPBitset`, `MC_EntityID`, `MC_ChasePedID`, `MC_TrainID`, `MC_TrainCarriage`, `MC_Team0_VehDeliveredRules`, `MC_Team1_VehDeliveredRules`, `MC_Team2_VehDeliveredRules`, `MC_Team3_VehDeliveredRules`, `FMMC_ClonedPedPart`, `MC_Prop`, `MC_FrozenByMap`, `MC_VehSeatCache`, `MC_TeamVehicle`, `AttributeDamage`, `GangBackup`, `CreatedByPegasus`, `BeforeCorona`, `Heist_Veh_ID`, `CC_iState`, `CC_iStatePrev`, `CC_iBitSet`, `CC_fInfluenceDirectThreat`, `CC_fInfluenceShouting`, `CC_iBeatdownHitsRemaining`, `CC_iBeatdownRounds`, `LUXE_MINIGAME_ACT_PROPS`, `LUXE_VEH_INSTANCE_ID`, `UsingForTimeTrial`, `EnableVehLuxeActs`, `Player_Goon`, `Player_Boss`, `Previous_Boss` ...

## Native vocabulary

Most-called natives inside the code unique to this script:

`_SET_CONTENT_PROP_TYPE` (1776), `DECOR_REGISTER` (115), `REGISTER_WORLD_POINT_SCRIPT_BRAIN` (99), `REGISTER_OBJECT_SCRIPT_BRAIN` (47), `SET_BIT` (7), `DISABLE_SCRIPT_BRAIN_SET` (4), `CLEAR_BIT` (3), `ADD_SCRIPT_TO_RANDOM_PED` (3), `ARE_STRINGS_EQUAL` (2), `ADD_HOSPITAL_RESTART` (1), `DISABLE_HOSPITAL_RESTART` (1), `ADD_POLICE_RESTART` (1), `DISABLE_POLICE_RESTART` (1), `GET_INTERIOR_AT_COORDS` (1), `TERMINATE_ALL_SCRIPTS_WITH_THIS_NAME` (1), `GET_HASH_KEY` (1), `IS_STRING_NULL_OR_EMPTY` (1), `DECOR_REGISTER_LOCK` (1), `GET_INDEX_OF_CURRENT_LEVEL` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`37.9419f` x5 · `71.2278f` x4 · `28.2688f` x3 · `-1158.687f` x3 · `-1520.819f` x3 · `9.6336f` x3 · `50.9983f` x3 · `-14.1709f` x3 · `-1445.289f` x3 · `29.6473f` x3 · `1979.554f` x3 · `3816.256f` x3 · `31.27402f` x3 · `-824.2567f` x2 · `181.3005f` x2 · `70.6578f` x2 · `1392.33f` x2 · `1141.611f` x2 · `113.4431f` x2 · `29.3953f` x2 · `97.01886f` x2 · `-1290.793f` x2 · `28.26876f` x2 · `-818.2696f` x2

## Other strings

Literals whose consuming native was not classified:

`B_FIB`, `B_BJMP`, `atm_trigger`, `hc_gunman`, `ob_tv`, `laptop_trigger`, `B_ASSA`, `B_OFFM`, `ob_telescope`, `ob_mp_bed_high`, `hc_hacker`, `hc_driver`, `finale_heist_prepC`, `ob_vend1`, `ob_drinking_shots`, `pb_prostitute`, `mp_m_freemode_01`, `mp_f_freemode_01`, `sentinel2`, `img_radar_gang_families`, `nothing`, `B_SIM`, `B_DH`, `B_OFFT`, `B_RIDE`, `ob_mp_shower_med`, `launcher_Darts`, `CHECKPOINT_NORMAL`, `CHECKPOINT_MISSED`, `CHECKPOINT_PERFECT`

---

Source: `decompiled_scripts/standard_global_init.c`
