# fm_content_vehrob_task.c

MP freemode script. 12 anim dicts; 13 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 518,822 |
| Functions | 10,665 (390 unique, 10,275 shared) |
| Unique lines | 16,637 (3.2% of file) |

## Assets

**Animation dictionaries** (12) - `anim@scripted@ulp_missions@garageopen@heeled@`, `anim@scripted@ulp_missions@garageopen@male@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@heeled@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@door_trans@hinge_r@`, `anim@scripted@hs4f@ig14_open_car_trunk@male@`, `anim@scripted@hs4f@ig14_open_car_trunk@heeled@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@heeled@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@male@`, `anim@scripted@freemode@ig4_stash_weapons@male@`, `anim@scripted@freemode@ig4_stash_weapons@heeled@`, `anim@door_trans@hinge_l@`

**Models and props** (13) - `imp_prop_impexp_carrack`, `imp_prop_impexp_postlift`, `imp_prop_impexp_postlift_up`, `v_ilev_roc_door3`, `v_ilev_roc_door2`, `s_m_y_fireman_01`, `prop_damdoor_01`, `s_m_m_movalien_01`, `g_m_y_ballaeast_01`, `g_f_importexport_01`, `g_m_importexport_01`, `imp_prop_covered_vehicle_01a`, `imp_prop_covered_vehicle_02a`

**Audio banks** (3) - `SCRIPT/ALARM_BELL_01`, `SCRIPT/ALARM_BELL_03`, `SCRIPT/ALARM_KLAXON_04`

**Sounds** (8) - `PICK_UP`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `Barge_Door`, `dlc_h4_Prep_FC_Sounds`, `Garage_Door_Open`, `GTAO_Script_Doors_Faded_Screen_Sounds`, `Metal_Door_Push`, `GTAO_Script_Doors_Sounds`

**Text labels** (20) - `XM4R1AU`, `XM4R2AU`, `XM4R3AU`, `XM4R4AU`, `XM4R5AU`, `86FPM269`, `NULL`, `05SBF291`, `21CMM287`, `91REB503`, `SALV23_FLOW_TCK0`, `68KWK927`, `15HBW365`, `00EUT645`, `00VTH379`, `42DWP748`, `60JFL965`, `00QSV659`, `21PBL328`, `83KYU186`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (91), `SET_BIT` (30), `GET_PLAYER_WANTED_LEVEL` (21), `SET_PED_COMPONENT_VARIATION` (14), `DISABLE_CONTROL_ACTION` (9), `DOES_ENTITY_EXIST` (9), `GET_RANDOM_INT_IN_RANGE` (7), `CLEAR_HELP` (6), `CLEAR_PED_TASKS` (6), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (6), `NET_TO_ENT` (6), `GET_ENTITY_COORDS` (6), `SET_ENTITY_ROTATION` (6), `REQUEST_SCRIPT_AUDIO_BANK` (5), `SET_CURRENT_PED_WEAPON` (5), `FREEZE_ENTITY_POSITION` (5), `PLAY_SOUND_FRONTEND` (5), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (5), `NETWORK_HAS_CONTROL_OF_ENTITY` (4), `GET_CURRENT_PED_WEAPON` (4), `IS_ENTITY_PLAYING_ANIM` (4), `IS_SYNCHRONIZED_SCENE_RUNNING` (4), `IS_STRING_NULL_OR_EMPTY` (4), `SET_PED_DEFAULT_COMPONENT_VARIATION` (4), `SET_ENTITY_INVINCIBLE` (4), `PLAYER_ID` (4), `CREATE_MODEL_HIDE` (4), `REMOVE_MODEL_HIDE` (4), `SET_ENTITY_COORDS_NO_OFFSET` (4), `SET_ENTITY_QUATERNION` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-40.647f` x6 · `976.9506f` x4 · `-2996.619f` x4 · `-39.499f` x2 · `786.3f` x2 · `-3002.4f` x2 · `-67.3f` x2 · `0.99f` x2 · `0.3f` x2 · `977.6381f` x2 · `-3006.258f` x2 · `972.101f` x2 · `-3012.313f` x2 · `967.029f` x1 · `-3006.72f` x1 · `-39.503f` x1 · `960.665f` x1 · `-2999.207f` x1 · `844.1f` x1 · `-3006.1f` x1 · `-42.5f` x1 · `0.1f` x1 · `-0.8f` x1 · `1385.258f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `granger2`, `typ`, `ibs`, `r300`, `monstrociti`, `buffalo4`, `greenwood`, `baller5`, `ALARMS_SOUNDSET`, `scl`, `sprt`, `hclr`, `bsa`, `veh`, `rot`, `rad`, `VRT_BMT_STRT1`, `VRT_BMT_STRT2`, `grp`, `MAX_NUM_SCENARIOS`, `blp`, `manchez`, `IZ_reh_dlc_int_04_sum2_INT4_BasementRm`

---

Source: `decompiled_scripts/fm_content_vehrob_task.c`
