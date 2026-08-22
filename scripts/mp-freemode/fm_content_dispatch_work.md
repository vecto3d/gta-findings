# fm_content_dispatch_work.c

MP freemode script. 8 anim dicts; 9 models; 6 scaleforms; 1 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 528,724 |
| Functions | 11,345 (730 unique, 10,615 shared) |
| Unique lines | 25,457 (4.8% of file) |

## Assets

**Animation dictionaries** (8) - `anim@scripted@cayo@ig2_defuse_radar@male@`, `anim@scripted@robbery@tun_prep_uni_ig1_couple@`, `amb@code_human_cower@male@idle_a`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@heeled@`, `anim@scripted@cbr5@ig1_cctv_tape_pull@heeled@`, `anim@scripted@cbr5@ig1_cctv_tape_pull@male@`, `anim@door_trans@hinge_l@`

**Models and props** (9) - `prop_inout_tray_02`, `prop_off_phone_01`, `v_res_officeboxfile01`, `prop_ghettoblast_02`, `prop_table_03b_chr`, `prop_rub_table_01`, `ch_prop_ch_corridor_door_derelict`, `Prop_CH_Casino_Accs_01`, `s_m_m_prisguard_01`

**Sounds** (9) - `DLC_24-1_Dispatch_Bomb_Disposal_Sounds`, `Ctrl`, `Countdown`, `GTAO_Speed_Convoy_Soundset`, `PICKUP_DEFAULT`, `HUD_FRONTEND_STANDARD_PICKUPS_SOUNDSET`, `Barge_Door`, `dlc_h4_Prep_FC_Sounds`, `Detonation`

**Scaleform movies** (6) - `GENERIC_INSTRUCTIONAL_BUTTONS`, `SET_DATA_SLOT`, `CLEAR_ALL`, `TOGGLE_MOUSE_BUTTONS`, `SET_MAX_WIDTH`, `DRAW_INSTRUCTIONAL_BUTTONS`

**Particle effects** (1) - `scr_srr_oper_airstrike`

**Texture dicts** (2) - `helicopterhud`, `hud_outline`

**Text labels** (6) - `S24VAUD`, `X25VNAU`, `X24VAU`, `NULL`, `DISPATCH`, `MISSION`

**Timecycle modifiers** (1) - `MP_Arcade_Derelict`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (106), `PLAYER_ID` (76), `DISABLE_CONTROL_ACTION` (45), `SET_BIT` (44), `SET_PED_COMPONENT_VARIATION` (41), `DOES_ENTITY_EXIST` (35), `GET_ENTITY_COORDS` (20), `SET_PED_COMBAT_ATTRIBUTES` (19), `SET_PED_CONFIG_FLAG` (18), `GET_RANDOM_INT_IN_RANGE` (17), `PLAYER_PED_ID` (15), `GET_RANDOM_FLOAT_IN_RANGE` (12), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (11), `NET_TO_ENT` (11), `IS_PED_IN_ANY_VEHICLE` (11), `VMAG` (11), `HIDE_HUD_COMPONENT_THIS_FRAME` (10), `GET_PED_IN_VEHICLE_SEAT` (8), `GET_ENTITY_MODEL` (8), `TO_FLOAT` (8), `CLEAR_PED_TASKS` (8), `SET_ENTITY_HEALTH` (8), `PLAY_SOUND_FROM_COORD` (8), `IS_STRING_NULL_OR_EMPTY` (8), `GET_DISTANCE_BETWEEN_COORDS` (7), `IS_ENTITY_DEAD` (7), `GET_ENTITY_HEADING` (7), `GET_ID_OF_THIS_THREAD` (7), `VDIST` (7), `IS_VEHICLE_SEAT_FREE` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x4 · `0.3f` x4 · `-47.6f` x4 · `0.04f` x2 · `-0.15f` x2 · `2725.549f` x2 · `-376.104f` x2 · `-47.616f` x2 · `2726.387f` x2 · `-375.752f` x2 · `-48.38f` x2 · `2727.172f` x2 · `-376.326f` x2 · `2726.505f` x2 · `-376.486f` x2 · `2725.849f` x2 · `-375.884f` x2 · `-47.601f` x2 · `2729.483f` x2 · `-377.353f` x2 · `-46.882f` x2 · `0.5f` x2 · `1.777778f` x2 · `1848.997f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `sabregt2`, `num`, `landstalker2`, `head`, `int`, `XM4_VINCENT`, `baller`, `emperor`, `faction2`, `BTDW_BM_TS`, `typ`, `sprt`, `hclr`, `scl`, `virgo2`, `tornado5`, `bsa`, `rad`, `ibs`, `sultan3`, `buffalo4`, `DWBOMB_HLP_QT`, `buccaneer2`, `peyote3`, `manana2`, `chino2`, `blp`

---

Source: `decompiled_scripts/fm_content_dispatch_work.c`
