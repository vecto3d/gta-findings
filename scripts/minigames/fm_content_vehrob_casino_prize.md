# fm_content_vehrob_casino_prize.c

Minigames script. 11 anim dicts; 14 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 546,336 |
| Functions | 11,118 (528 unique, 10,590 shared) |
| Unique lines | 20,391 (3.7% of file) |

## Assets

**Animation dictionaries** (11) - `anim@door_trans@hinge_l@`, `anim@door_trans@elevator@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@heeled@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@scripted@freemode@ig13_mop_floor@heeled@`, `anim@scripted@freemode@ig13_mop_floor@male@`, `anim_heist@hs3f@ig6_push_button@`, `anim@heists@keycard@`, `anim@heists@keypad@`, `anim@scripted@ulp_missions@computerhack@male@`, `clipset@anim_heist@hs3f@ig1_rappel@male`

**Models and props** (14) - `ch_prop_ch_service_door_02b`, `v_ilev_garageliftdoor`, `prop_bin_08open`, `prop_bin_08a`, `prop_rub_binbag_sd_01`, `prop_rub_binbag_03b`, `prop_rub_binbag_01b`, `ch_prop_ch_room_trolly_01a`, `v_ind_ss_clothrack`, `v_corp_banktrolley`, `s_m_y_casino_01`, `g_m_m_casrn_01`, `ch_prop_ch_service_door_01a`, `ch_prop_ch_service_door_02a`

**Audio banks** (5) - `DLC_MPHEIST/HEIST_USE_KEYPAD`, `SCRIPT/ALARM_KLAXON_05`, `LIFTS`, `DLC_CHRISTMAS2017/XM_Silo_Laser_Hack`, `DLC_23_2/DLC_23_2_Freemode_1`

**Sounds** (16) - `dlc_xm_silo_laser_hack_sounds`, `Control`, `Blue_Target_Explode`, `moveSpeed`, `GTAO_Script_Doors_Sounds`, `Garage_Door_Open`, `GTAO_Script_Doors_Faded_Screen_Sounds`, `Hit_Mirror`, `Pass`, `Pass_Remote`, `Fail`, `Fail_Remote`, `Red_Target_Explode`, `Node_Release`, `Generic_Door_Limit`, `Generic_Door_Push`

**Speech contexts** (1) - `S_M_M_BOUNCER_01_BLACK_FULL_01`

**Texture dicts** (17) - `MPBeamHack`, `MPBeamHackFG`, `MPBeamHack_lvl0`, `pass`, `MPBeamhack`, `MPBeamhackFG`, `fail`, `mirror_base`, `mirror_shadow`, `Node_Shatter_BG_60`, `Firewall_Shatter_BG_58`, `mirror_highlight`, `mirror_white`, `border`, `Beam_Glow_Tapered`, `beam_middle`, `beam_top`

**Text labels** (14) - `HACK`, `60UBQ864`, `29KLD135`, `88SPG626`, `EXTRASUNNY`, `HACKOBJ1`, `HACKOBJ2`, `HACKOBJ3`, `HACKOBJ5`, `HACKOBJ7`, `BEAM_TRT`, `BEAM_LVT`, `BEAM_LV`, `XM4R4AU`

**Timecycle modifiers** (3) - `Casino_Lightsoff`, `DRUG_gas_huffin`, `DLC_mp2023_02_casino_rob`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (117), `SET_PED_COMPONENT_VARIATION` (103), `TO_FLOAT` (32), `SET_BIT` (30), `DISABLE_CONTROL_ACTION` (18), `ROUND` (15), `DRAW_SPRITE` (15), `IS_STRING_NULL_OR_EMPTY` (13), `CREATE_MODEL_HIDE` (11), `REMOVE_MODEL_HIDE` (11), `DOES_ENTITY_EXIST` (10), `PLAY_SOUND_FRONTEND` (10), `CLEAR_BIT` (10), `NET_TO_ENT` (9), `NETWORK_GET_PLAYER_INDEX` (9), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (8), `GET_ENTITY_COORDS` (8), `GET_FRAME_TIME` (8), `GET_NETWORK_TIME` (8), `SET_ENTITY_VISIBLE` (7), `IS_ENTITY_DEAD` (7), `PLAYER_PED_ID` (7), `PLAYER_ID` (7), `ABSI` (7), `IS_ENTITY_IN_ANGLED_AREA` (6), `SET_PED_PROP_INDEX` (6), `GET_RANDOM_INT_IN_RANGE` (6), `REQUEST_SCRIPT_AUDIO_BANK` (6), `RELEASE_NAMED_SCRIPT_AUDIO_BANK` (6), `DOES_BLIP_EXIST` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x23 · `2543.51f` x10 · `-248.7282f` x10 · `-61.3736f` x10 · `1.75f` x8 · `0.25f` x6 · `2492.938f` x6 · `-270.0593f` x6 · `-40.12289f` x6 · `0.075f` x5 · `0.064f` x5 · `0.4f` x4 · `0.401f` x4 · `0.693f` x4 · `828.663f` x4 · `-46.829f` x4 · `-59.72299f` x2 · `1.5f` x2 · `-49.99995f` x2 · `0.8f` x2 · `1.8f` x2 · `0.99f` x2 · `0.061f` x2 · `0.086f` x2

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `ibs`, `head`, `int`, `typ`, `sprt`, `hclr`, `scl`, `rot`, `bsa`, `MP232_SUSPENSE`, `MP232_MED_INTENSITY`, `enter`, `exit`, `VRPC_MASK_1`, `blp`, `veh`, `rad`, `DLC_23_2_Robbery_Casino_Finale_Sounds`, `VRPS_HLP_8`, `AZ_H3_Casino_Alarm_Zone_02_Interior`, `DLC_23_2_Casino_Floor_Muffled_Emitter_01`, `VRPC_OBJ_22`, `BEAM_P`, `MAX_NUM_SCENARIOS`, `grp`

---

Source: `decompiled_scripts/fm_content_vehrob_casino_prize.c`
