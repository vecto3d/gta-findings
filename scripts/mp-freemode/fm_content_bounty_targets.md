# fm_content_bounty_targets.c

MP freemode script. 12 anim dicts; 38 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 531,366 |
| Functions | 11,639 (970 unique, 10,669 shared) |
| Unique lines | 28,252 (5.3% of file) |

## Assets

**Animation dictionaries** (12) - `anim@door_trans@hinge_l@`, `anim@scripted@bty1@ig3_bounty_surrender@male@`, `amb@medic@standing@kneel@enter`, `amb@medic@standing@kneel@exit`, `anim@scripted@freemode@ig1_cut_cable@heeled@`, `anim@scripted@freemode@ig1_cut_cable@male@`, `anim@scripted@freemode@tunprep_ig_grab_midd@heeled@`, `anim@scripted@freemode@tunprep_ig_grab_midd@male@`, `anim@scripted@heist@ig9_control_tower@male@`, `anim@scripted@freemode@arcade_ig_fortune_teller@heeled@`, `anim@scripted@freemode@arcade_ig_fortune_teller@male@`, `anim@scripted@player@freemode@tun_prep_ig3_grab_high@male@`

**Models and props** (38) - `g_m_m_casrn_01`, `g_m_y_strpunk_02`, `g_f_y_lost_01`, `a_f_y_business_01`, `g_m_y_ballaorig_01`, `v_ret_gc_phone`, `v_ilev_cbankvauldoor01`, `prop_streetlight_01`, `g_m_m_korboss_01`, `ch_prop_ch_entrance_door_derelict`, `ch_prop_ch_corridor_door_beam`, `prop_homeless_matress_01`, `prop_rub_monitor`, `prop_rub_binbag_03b`, `s_m_m_security_01`, `v_ilev_bank4door01`, `v_ilev_bank4door02`, `v_ilev_genbankdoor1`, `v_ilev_genbankdoor2`, `v_ilev_gb_teldr`, `hei_prop_heist_sec_door`, `v_ilev_gb_vauldr`, `v_ilev_cbankvaulgate02`, `v_ilev_gb_vaubar`, `g_m_y_korlieut_01`, `prop_cctv_cam_06a`, `bkr_prop_rt_memorial_active_01`, `bkr_prop_rt_memorial_active_02`, `bkr_prop_rt_memorial_active_03`, `bkr_prop_rt_memorial_president`, `bkr_prop_rt_memorial_vice_pres`, `bkr_prop_memorial_wall_01a`, `bkr_prop_rt_clubhouse_table`, `bkr_prop_rt_clubhouse_plan_01a`, `bkr_prop_clubhouse_blackboard_01a`, `v_ilev_vagostoiletdoor`, `s_m_y_westsec_01`, `s_m_y_westsec_02`

**Audio banks** (3) - `DLC_HEIST3/ARCADE_GENERAL_01`, `DLC_HEIST3/ARCADE_GENERAL_02`, `ALARM_KLAXON_04`

**Sounds** (6) - `Barge_Door`, `dlc_h4_Prep_FC_Sounds`, `PICKUP_DEFAULT`, `HUD_FRONTEND_STANDARD_PICKUPS_SOUNDSET`, `Background`, `MP_CCTV_SOUNDSET`

**Text labels** (6) - `S24JAUD`, `BNTYHNTR`, `ENTER`, `LOOP`, `EXIT`, `BAIL`

**Decorators** (4) - `Player_Bounty_Transporter`, `Player_Owned_Veh`, `MPBitset`, `Previous_Owner`

**Relationship groups** (1) - `COP`

**Timecycle modifiers** (1) - `MissileOutOfRange`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (117), `PLAYER_ID` (81), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (30), `NET_TO_ENT` (29), `SET_VEHICLE_DAMAGE` (29), `GET_ENTITY_COORDS` (23), `SET_VEHICLE_COLOURS` (20), `SET_VEHICLE_EXTRA_COLOURS` (20), `SET_PED_CONFIG_FLAG` (19), `SET_BIT` (17), `DOES_ENTITY_EXIST` (17), `SET_ENTITY_HEALTH` (14), `GET_RANDOM_FLOAT_IN_RANGE` (13), `REMOVE_MODEL_HIDE` (11), `IS_ENTITY_DEAD` (11), `GET_RANDOM_INT_IN_RANGE` (11), `VMAG` (11), `CREATE_MODEL_HIDE` (10), `SET_PED_COMBAT_ATTRIBUTES` (9), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (9), `VDIST` (8), `CLEAR_PED_TASKS` (7), `SET_ENTITY_INVINCIBLE` (7), `SET_STATIC_EMITTER_ENABLED` (7), `GET_ID_OF_THIS_THREAD` (7), `CLEAR_BIT` (6), `GET_PLAYER_WANTED_LEVEL` (6), `NET_TO_VEH` (6), `FREEZE_ENTITY_POSITION` (6), `SET_ENTITY_VISIBLE` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x16 · `0.1f` x11 · `-0.5f` x10 · `-1.5f` x3 · `-105.5628f` x2 · `6470.032f` x2 · `31.4823f` x2 · `-104.6049f` x2 · `6473.444f` x2 · `31.7953f` x2 · `-1209.988f` x2 · `-314.897f` x2 · `36.745f` x2 · `-2.5f` x2 · `-3.5f` x2 · `0.4f` x2 · `0.5f` x2 · `2736.766f` x2 · `-377.547f` x2 · `2721.151f` x2 · `-378.839f` x2 · `-49.97f` x2 · `2725.918f` x2 · `-372.197f` x2

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `ibs`, `int`, `typ`, `sprt`, `hclr`, `scl`, `S24_JENETTE`, `BT_TCK_DESTRR`, `BT_TCK_DESTRL`, `rot`, `bsa`, `CODE_HUMAN_MEDIC_KNEEL`, `baller`, `peyote3`, `buccaneer2`, `blp`, `veh`, `rad`, `MP241_FAIL`, `MP241_STOP_MUSIC`, `MP241_SUSPENSE`, `MP241_DELIVERING`, `MAX_NUM_SCENARIOS`, `grp`

---

Source: `decompiled_scripts/fm_content_bounty_targets.c`
