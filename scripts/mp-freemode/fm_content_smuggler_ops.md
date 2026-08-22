# fm_content_smuggler_ops.c

MP freemode script. 16 anim dicts; 9 models; 3 scaleforms; 5 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 532,285 |
| Functions | 11,510 (1,065 unique, 10,445 shared) |
| Unique lines | 28,901 (5.4% of file) |

## Assets

**Animation dictionaries** (16) - `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@heeled@`, `weapons@projectile@sticky_bomb`, `ANIM_HEIST@HS3F@IG12_CHANGE_CLOTHES@`, `anim@door_trans@hinge_l@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@heeled@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@male@`, `anim@amb@casino@hangout@ped_male@stand@01b@base`, `anim@scripted@freemode@ig1_open_container@heeled@`, `anim@scripted@freemode@ig1_open_container@male@`, `ANIM_GROUP_MOVE_BALLISTIC`, `MOVE_STRAFE_BALLISTIC`, `anim_heist@hs3f@ig12_change_clothes@`, `anim@scripted@player@mission@tun_bunk_ig1_hdd_server@heeled@`, `anim@scripted@player@mission@tun_bunk_ig1_hdd_server@male@`, `anim@gangops@morgue@office@laptop@`

**Models and props** (9) - `prop_cs_server_drive`, `hei_prop_carrier_defense_01`, `hei_prop_carrier_defense_02`, `prop_elecbox_10`, `hei_prop_hst_usb_drive`, `prop_drug_package`, `s_m_m_ccrew_01`, `s_m_m_ccrew_02`, `u_m_m_juggernaut_03`

**Audio banks** (2) - `DLC_MP2023_1/DLC_MP2023_1_FM`, `ALARM_KLAXON_07`

**Sounds** (15) - `DLC_sum20_Business_Battle_AC_Sounds`, `Air_Defences_Activated`, `Air_Defenses_Disabled`, `Lazer_Takeoff_Oneshot`, `Aircraft_Carrier_Raid_Sounds`, `Scope_Spot_POI`, `GTAO_Heists_HUD_Sounds`, `Attach`, `GTAO_Tracker_Plant_Sounds`, `PICK_UP`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `Barge_Door`, `dlc_h4_Prep_FC_Sounds`, `Software_Installing_Loop`, `DLC_Security_Investigations_Setup_Sounds`

**Scaleform movies** (3) - `SHOW_START_SCREEN`, `SHOW_CODE_SCREEN`, `SHOW_END_SCREEN`

**Particle effects** (5) - `scr_srr_oper`, `scr_srr_oper_airstrike`, `scr_sell`, `scr_vehicle_damage_smoke`, `damage`

**Texture dicts** (1) - `ShopUI_Title_Los_Santos_Angels`

**Text labels** (15) - `SR2CHAU`, `AIRMECH`, `STRING`, `EXTRASUNNY`, `NULL`, `07AGO419`, `28TZM398`, `91REB023`, `LSANG3LS`, `40TJH816`, `04VUQ767`, `THUNDER`, `LS4NGELS`, `03ADX850`, `60OQA895`

**Scenarios** (1) - `WORLD_HUMAN_STAND_MOBILE`

**Timecycle modifiers** (1) - `DLC_mp2023_01_Carrier_Bridge`

**Interiors and entity sets** (1) - `int_carrier_hanger`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (110), `DOES_ENTITY_EXIST` (42), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (34), `SET_PED_COMPONENT_VARIATION` (33), `SET_BIT` (31), `GET_ENTITY_COORDS` (25), `NET_TO_ENT` (21), `SET_ENTITY_VISIBLE` (20), `FREEZE_ENTITY_POSITION` (19), `SET_PED_CONFIG_FLAG` (18), `SET_ENTITY_INVINCIBLE` (17), `GET_RANDOM_INT_IN_RANGE` (17), `IS_ENTITY_DEAD` (16), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (16), `SET_PED_COMBAT_ATTRIBUTES` (16), `DISABLE_CONTROL_ACTION` (15), `CLEAR_BIT` (13), `SET_ENTITY_HEALTH` (12), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (12), `IS_STRING_NULL_OR_EMPTY` (11), `IS_ENTITY_IN_WATER` (10), `NET_TO_VEH` (10), `IS_POINT_IN_ANGLED_AREA` (10), `DOES_BLIP_EXIST` (9), `GET_SYNCHRONIZED_SCENE_PHASE` (9), `NETWORK_GET_PLAYER_INDEX` (8), `IS_ENTITY_ATTACHED` (8), `SET_ENTITY_COLLISION` (8), `SET_CUTSCENE_ENTITY_STREAMING_FLAGS` (8), `NETWORK_EXPLODE_VEHICLE` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`3.5f` x7 · `0.5f` x4 · `0.4f` x4 · `10.3f` x4 · `3059.111f` x4 · `-4794.49f` x4 · `5.077f` x4 · `0.7f` x3 · `1.25f` x3 · `0.8f` x3 · `1.2f` x2 · `2.5f` x2 · `1115.654f` x2 · `-2273.433f` x2 · `28.89841f` x2 · `1115.247f` x2 · `-2278.109f` x2 · `30.92747f` x2 · `0.25f` x2 · `0.2f` x2 · `3103.207f` x2 · `-4805.419f` x2 · `3080.537f` x2 · `-4811.319f` x2

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `Facility_Raid_Sounds`, `int`, `typ`, `ibs`, `sprt`, `hclr`, `scl`, `MP231_MED_INTENSITY`, `rot`, `bsa`, `rad`, `MP231_SUSPENSE`, `MP231_GUNFIGHT`, `MP231_DELIVERING`, `Pilot`, `mesa3`, `HS4_BACKUP1`, `Aircraft_Carrier_Raid_Sounds`, `toreador`, `blp`, `veh`, `Electric_Spark_Charge_Loop`, `rumpo`, `MP231_FAIL`

---

Source: `decompiled_scripts/fm_content_smuggler_ops.c`
