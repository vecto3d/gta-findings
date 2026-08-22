# fm_content_acid_lab_source.c

MP freemode script. 2 anim dicts; 35 models; 6 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 518,205 |
| Functions | 11,033 (661 unique, 10,372 shared) |
| Unique lines | 18,643 (3.6% of file) |

## Assets

**Animation dictionaries** (2) - `anim@door_trans@hinge_l@`, `anim_heist@hs3f@ig12_change_clothes@`

**Models and props** (35) - `hei_prop_carrier_cargo_01a`, `prop_elecbox_10_cr`, `prop_container_03_ld`, `prop_cons_cements01`, `sf_prop_sf_hydro_platform_01a`, `prop_mb_cargo_04b`, `prop_mb_cargo_03a`, `prop_mb_crate_01b`, `prop_air_cargo_04a`, `prop_mb_cargo_04a`, `prop_mb_cargo_02a`, `v_ilev_bl_shutter1`, `g_m_m_chigoon_02`, `s_m_m_security_01`, `s_f_y_cop_01`, `CS_OT_HDEL_B`, `CS_OT_HDEL_A`, `CS_OT_DEL_B`, `CS_OT_DEL_A`, `CS_OT_STEAL`, `CS_LOC_1`, `CS_BLIP_SPIL`, `CS_HT_SPI_WARN`, `CS_HT_HAZ`, `CS_HT_HAZ_EQ`, `CS_HT_HAZ_ME`, `CS_SPIL_TM_1`, `CS_SPIL_TM_2`, `CS_SPIL_TM_3`, `CS_TCK_HAZ`, `CS_HT_INT_HAZ`, `CS_BLIP_HAZ`, `s_m_m_hazmatworker_01`, `CS_BLIP_SUP`, `s_m_m_gentransport`

**Sounds** (6) - `Barge_Door`, `dlc_h4_Prep_FC_Sounds`, `Scope_Spot_POI`, `GTAO_Heists_HUD_Sounds`, `PICKUP_DEFAULT`, `HUD_FRONTEND_STANDARD_PICKUPS_SOUNDSET`

**Particle effects** (6) - `scr_xt_src`, `scr_xt_src_barrel_mist`, `scr_xt_src_trailer_grain_debris`, `scr_xt_src_spill_haze`, `scr_vehicle_damage_smoke`, `damage`

**Text labels** (4) - `DEFAULT_LAB_N`, `STRING`, `XM3LAAU`, `06ZFT078`

**Timecycle modifiers** (1) - `DRUG_gas_huffin`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (101), `NET_TO_ENT` (26), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (24), `SET_PED_COMPONENT_VARIATION` (21), `SET_BIT` (19), `SET_PED_COMBAT_ATTRIBUTES` (17), `GET_ENTITY_COORDS` (16), `IS_ENTITY_TOUCHING_MODEL` (14), `DOES_ENTITY_EXIST` (12), `IS_PED_IN_ANY_VEHICLE` (11), `GET_RANDOM_INT_IN_RANGE` (10), `PLAYER_ID` (10), `PARTICIPANT_ID_TO_INT` (9), `VDIST2` (8), `IS_ENTITY_VISIBLE` (7), `DOES_BLIP_EXIST` (7), `CLEAR_BIT` (7), `SET_IGNORE_NO_GPS_FLAG` (6), `REQUEST_NAMED_PTFX_ASSET` (6), `SET_ENTITY_COLLISION` (6), `SET_ENTITY_VISIBLE` (6), `GET_DISTANCE_BETWEEN_COORDS` (6), `DOES_PARTICLE_FX_LOOPED_EXIST` (6), `PLAYER_PED_ID` (6), `NETWORK_IS_PARTICIPANT_ACTIVE` (6), `SET_VEHICLE_ENGINE_ON` (6), `SET_ENTITY_HEALTH` (5), `SET_ENTITY_INVINCIBLE` (5), `HAS_NAMED_PTFX_ASSET_LOADED` (5), `USE_PARTICLE_FX_ASSET` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.8f` x3 · `0.3f` x2 · `-0.5f` x1 · `-0.8f` x1 · `2.4f` x1 · `1.7f` x1 · `0.5f` x1 · `0.4f` x1 · `-0.4f` x1 · `0.9f` x1 · `-0.015f` x1 · `-0.104f` x1 · `0.01f` x1 · `-0.022f` x1 · `-0.0475f` x1 · `-0.9f` x1 · `0.25f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `typ`, `CM22_DELIVERING`, `sprt`, `hclr`, `scl`, `bsa`, `rad`, `ibs`, `ALS_ITM_SUP`, `CM22_DELIVERING_START`, `CM22_MED_INTENSITY`, `CM22_VEHICLE_ACTION`, `mule4`, `ASO_MAD_OT_07D`, `ALS_OT_RCVR`, `CM22_GUNFIGHT`, `blp`, `veh`, `rot`, `WORLD_HUMAN_GUARD_STAND`, `ASO_OT_AL_R3_B`, `ASO_OT_AL_R3_A`, `ASO_OT_AL_R2_B`

---

Source: `decompiled_scripts/fm_content_acid_lab_source.c`
