# fm_content_helitours_work.c

MP freemode script. 1 anim dicts; 119 models; 3 scaleforms.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 517,715 |
| Functions | 11,038 (631 unique, 10,407 shared) |
| Unique lines | 18,970 (3.7% of file) |

## Assets

**Animation dictionaries** (1) - `amb@code_human_cower@male@idle_a`

**Models and props** (119) - `sf_prop_ap_port_text`, `sf_prop_ap_starb_text`, `sf_prop_ap_stern_text`, `set_crane_tint`, `set_lighting_tint_props`, `set_modarea`, `set_tint_shell`, `set_bedroom_blinds_open`, `set_bedroom_clutter`, `set_bedroom_modern`, `set_bedroom_tint`, `set_floor_1`, `set_floor_decal_7`, `set_lighting_hangar_a`, `set_lighting_wall_neutral`, `set_lighting_wall_tint05`, `set_office_modern`, `set_pent_arcade_modern`, `set_pent_bar_party_1`, `set_pent_bar_party_after`, `set_pent_clutter_01`, `set_pent_spa_bar_open`, `set_pent_tint_shell`, `set_pent_clutter_02`, `set_pent_clutter_03`, `set_pent_dealer`, `set_pent_media_bar_open`, `Set_Pent_Pattern_03`, `set_plan_setup`, `set_int_mod2_b_tint`, `set_int_mod2_b1`, `set_car_lift_01_up`, `set_car_lift_02_up`, `set_mechanic_upgrade`, `set_safe_upgrade`, `set_tint_b`, `s_m_m_ciasec_01`, `s_m_y_swat_01`, `s_m_y_uscg_01`, `a_m_y_business_01`, `s_m_m_highsec_01`, `set_floor_2`, `set_floor_decal_9`, `set_lighting_hangar_c`, `set_lighting_wall_tint09`, `set_office_traditional`, `set_up`, `v_fib03_door_light`, `v_fib03_set_ah3a`, `set_plan_garage`, `set_plan_pre_setup`, `set_plan_no_bed`, `set_plan_wall`, `set_int_mod_shell_def`, `set_bench_clutter`, `set_int_mod_booth_combo`, `set_mod1_style_01`, `set_office_standard`, `set_int_mod_trophy_bobby`, `set_int_mod_trophy_career` ...

**Sounds** (5) - `DLC_MP2023_1_Small_And_Agile_Sounds`, `Delivery_Success`, `Deliver_Parcel`, `Hook_Detach`, `DLC_IE_Steal_Cargobob_Sounds`

**Scaleform movies** (3) - `SET_YACHT_NAME`, `YACHT_NAME`, `YACHT_NAME_STERN`

**Text labels** (3) - `S25RAU`, `S25RHAU`, `NULL`

**Interiors and entity sets** (43) - `entity_set_tint_options`, `set_tint_shell`, `set_crane_tint`, `set_modarea`, `set_lighting_tint_props`, `set_car_lift_02_up`, `set_mechanic_upgrade`, `set_safe_upgrade`, `set_tint_b`, `set_car_lift_01_up`, `set_floor_1`, `set_bedroom_tint`, `set_floor_decal_7`, `set_floor_2`, `set_floor_decal_9`, `set_pent_arcade_modern`, `set_pent_bar_party_1`, `set_pent_bar_party_after`, `Set_Pent_Pattern_03`, `set_pent_spa_bar_open`, `set_pent_tint_shell`, `decorative_02`, `furnishings_02`, `lower_walls_default`, `mod_booth`, `mural_09`, `no_gun_locker`, `walls_01`, `entity_set_style_5`, `set_int_mod_shell_def`, `set_mod1_style_01`, `set_int_mod_booth_combo`, `set_office_standard`, `int_03_ba_bikemod`, `int_03_ba_design_02`, `int_03_ba_drone`, `int_03_ba_light_rig9`, `int_03_ba_tint`, `set_pent_clutter_01`, `set_pent_clutter_02`, `set_pent_clutter_03`, `set_pent_dealer`, `set_pent_media_bar_open`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (118), `SET_INTERIOR_ENTITY_SET_TINT_INDEX` (57), `SET_BIT` (34), `DOES_ENTITY_EXIST` (26), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (25), `SET_PED_COMBAT_ATTRIBUTES` (15), `SET_TINT_INDEX_CLOSEST_BUILDING_OF_TYPE` (14), `GET_ENTITY_COORDS` (11), `SET_PED_PROP_INDEX` (11), `NET_TO_VEH` (11), `NET_TO_ENT` (10), `CLEAR_AREA` (9), `GET_PED_IN_VEHICLE_SEAT` (7), `SET_ENTITY_ROTATION` (7), `NETWORK_DOES_NETWORK_ID_EXIST` (7), `SET_ENTITY_HEALTH` (6), `GET_DISTANCE_BETWEEN_COORDS` (6), `GET_ENTITY_MODEL` (6), `NETWORK_HAS_CONTROL_OF_ENTITY` (6), `SET_PED_COMPONENT_VARIATION` (5), `GET_DISPLAY_NAME_FROM_VEHICLE_MODEL` (5), `CLEAR_BIT` (5), `SET_BOAT_ANCHOR` (5), `DISABLE_CONTROL_ACTION` (5), `CLEAR_PED_TASKS` (5), `NET_TO_OBJ` (5), `IS_PED_IN_ANY_VEHICLE` (5), `NET_TO_PED` (5), `SET_PED_CONFIG_FLAG` (4), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`523.038f` x11 · `4750.548f` x11 · `-67.6263f` x11 · `0.5f` x4 · `0.35f` x3 · `10.91115f` x2 · `7.97511f` x2 · `0.2f` x1 · `2.5f` x1 · `514.8364f` x1 · `4750.546f` x1 · `-69.3338f` x1 · `514.8749f` x1 · `4748.106f` x1 · `-70.0003f` x1 · `513.3058f` x1 · `4750.429f` x1 · `-68.265f` x1 · `-0.2f` x1 · `0.395f` x1 · `0.315f` x1 · `0.4f` x1 · `0.7f` x1 · `0.75f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `typ`, `ibs`, `sprt`, `scl`, `hclr`, `rad`, `bsa`, `rot`, `entity_set_style_1`, `MP251_DELIVERING`, `entity_set_style_2`, `entity_set_style_3`, `entity_set_style_4`, `entity_set_style_5`, `entity_set_tint_options`, `MP251_SUSPENSE`, `MP251_MED_INTENSITY`, `HTT_SHRD_TS`, `entity_set_office`, `veh`, `blp`, `grp`, `chassis_dummy`

---

Source: `decompiled_scripts/fm_content_helitours_work.c`
