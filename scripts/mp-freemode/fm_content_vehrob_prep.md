# fm_content_vehrob_prep.c

MP freemode script. 28 anim dicts; 28 models; 6 scaleforms.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 543,163 |
| Functions | 11,572 (846 unique, 10,726 shared) |
| Unique lines | 32,482 (6.0% of file) |

## Assets

**Animation dictionaries** (28) - `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@heeled@`, `anim@door_trans@hinge_l@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@male@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@heeled@`, `anim@mugging@victim@toss_ped@`, `anim@scripted@heist@ig2_hand_lever@male@`, `anim@gangops@hanger@fuse_box@`, `anim@amb@warehouse@laptop@`, `anim@scripted@freemode@ig11_valve_turn@male@`, `anim@scripted@freemode@ig11_valve_turn@heeled@`, `weapons@projectile@sticky_bomb`, `amb@code_human_cower@male@idle_a`, `anim@scripted@freemode@ig7_open_riot_van_positive@heeled@`, `anim@scripted@freemode@ig7_open_riot_van_positive@male@`, `anim@scripted@freemode@ig8_open_riot_van_negative@heeled@`, `anim@scripted@freemode@ig8_open_riot_van_negative@male@`, `anim@scripted@heist@ig9_control_tower@male@`, `anim_heist@arcade_property@arcade_safe_open@female@`, `anim_heist@arcade_property@arcade_safe_open@male@`, `anim@heists@keypad@`, `ANIM_HEIST@HS3F@IG6_PUSH_BUTTON@FEMALE@`, `ANIM_HEIST@HS3F@IG6_PUSH_BUTTON@MALE@`, `anim@heists@keycard@`, `anim@scripted@player@mission@trn_ig2_empty@heeled@`, `anim@scripted@player@mission@trn_ig2_empty@male@`, `anim@scripted@ulp_missions@garageopen@heeled@`, `anim@scripted@ulp_missions@garageopen@male@`

**Animations** (2) - `anim@mugging@victim@toss_ped@`, `throw_object_left_pocket_male`

**Models and props** (28) - `s_m_m_security_01`, `ex_prop_ex_laptop_01a`, `v_res_fh_crateclosed`, `prop_cabinet_02b`, `v_res_d_lampa`, `v_res_mlaundry`, `prop_plant_int_03a`, `v_16_ap_mid_pants5`, `v_16_ap_mid_pants4`, `xs_prop_arena_planning_rt_01`, `prop_flattruck_01b`, `prop_laptop_01a`, `prop_tanktrailer_01a`, `v_ilev_rc_door2`, `hei_prop_hei_keypad_02`, `xs_prop_arena_screen_tv_01`, `prop_tv_flat_01`, `v_ilev_vag_door`, `xs_prop_x18_garagedoor01`, `xs_prop_x18_garagedoor02`, `v_ilev_mm_doorw`, `bkr_prop_fakeid_table`, `prop_flare_01`, `prop_off_chair_04b`, `v_corp_filecabtall`, `s_m_m_subcrew_01`, `ig_mechanic_01`, `u_m_m_juggernaut_03`

**Audio banks** (8) - `SCRIPT/ALARM_KLAXON_04`, `DLC_CM2022/CM2022_GENERIC_01`, `DLC_HEIST3/ARCADE_GENERAL_02`, `DLC_MPHEIST/HEIST_USE_KEYPAD`, `DLC_23_2/DLC_23_2_Freemode_1`, `DLC_HEI4/DLC_HEI4_Prep_FC`, `SCRIPT/ALARM_KLAXON_05`, `DLC_HEI4/DLC_HEI4_V_MG`

**Sounds** (32) - `Barge_Door`, `dlc_h4_Prep_FC_Sounds`, `Garage_Door_Open`, `GTAO_Script_Doors_Faded_Screen_Sounds`, `Disconnect_Wire`, `Minigame_Failure`, `DLC_H4_Voltage_Hack_Scene`, `DLC_Sum20_Door_Hack_Scene`, `PICK_UP`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `PlayRate`, `UsageVersion`, `Attach`, `GTAO_Tracker_Plant_Sounds`, `PICKUP_DEFAULT`, `HUD_FRONTEND_STANDARD_PICKUPS_SOUNDSET`, `Press`, `DLC_SECURITY_BUTTON_PRESS_SOUNDS`, `DLC_CH_HEIST_KEYCARD_INSYNC_SUCCESS_AT`, `Fail_Bink`, `Loading_Bink`, `Main_Screen_Draw`, `OS_Draw`, `All_Connected_Correct`, `All_Connected_Incorrect`, `Minigame_Success`, `Success_Bink`, `Background_loop`, `Timebar`, `Voltage_Current`, `Voltage_Target`, `Glitch`

**Scaleform movies** (6) - `SHOW_STATIC`, `SET_SCROLL_TEXT`, `DISPLAY_SCROLL_TEXT`, `SET_TEXT`, `CLEAR_SCROLL_TEXT`, `BREAKING_NEWS`

**Texture dicts** (2) - `MPIsland_Voltage`, `MPIsland_Voltage_BG`

**Text labels** (26) - `ENTER`, `XM4R2AU`, `XM4R3AU`, `XM4R4AU`, `XM4R5AU`, `22QUM874`, `LOOP`, `STRING`, `XM4R1AU`, `INVALID`, `46TIG879`, `09OAD578`, `65PHL337`, `10TAM322`, `26LNL592`, `EXIT`, `HBMB`, `BMBL`, `BZBT`, `FWAR`, `TGTM`, `WRCK`, `CRNG`, `HCTM`, `GMST`, `NULL`

**Timecycle modifiers** (3) - `DRUG_gas_huffin`, `spectator1`, `DLC_mp2023_02_maze_rob`

**Interiors and entity sets** (1) - `Arena_Mod_Rm`

**Hashed names** (7) - `m23_1_prop_m31_controlpanel_01a`, `m23_1_prop_m31_controlpanel_02a`, `m23_1_prop_m31_controlpanel_03a`, `hei_prop_wall_alarm_off`, `hei_prop_wall_alarm_on`, `prop_tanktrailer_01a`, `m23_2_prop_m32_jammer_01a`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (126), `SET_BIT` (49), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (46), `GET_RANDOM_INT_IN_RANGE` (36), `SET_PED_COMPONENT_VARIATION` (31), `NET_TO_ENT` (28), `NET_TO_OBJ` (26), `GET_ENTITY_COORDS` (24), `CREATE_MODEL_HIDE` (20), `REMOVE_MODEL_HIDE` (20), `PLAY_SOUND_FRONTEND` (19), `TO_FLOAT` (16), `DOES_ENTITY_EXIST` (15), `DISABLE_CONTROL_ACTION` (14), `RELEASE_NAMED_SCRIPT_AUDIO_BANK` (13), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (12), `ROUND` (12), `FREEZE_ENTITY_POSITION` (11), `GET_PLAYER_WANTED_LEVEL` (11), `NET_TO_PED` (11), `IS_STRING_NULL_OR_EMPTY` (11), `USE_PARTICLE_FX_ASSET` (10), `GET_HASH_KEY` (9), `GET_ENTITY_FORWARD_VECTOR` (9), `SET_ENTITY_VISIBLE` (9), `REQUEST_SCRIPT_AUDIO_BANK` (9), `BEGIN_SCALEFORM_MOVIE_METHOD` (9), `END_SCALEFORM_MOVIE_METHOD` (9), `SET_PED_COMBAT_ATTRIBUTES` (9), `GET_DISTANCE_BETWEEN_COORDS` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x12 · `-89.6f` x6 · `1048.348f` x6 · `-3100.666f` x6 · `-39.2f` x6 · `-0.5f` x5 · `-992.827f` x4 · `-1.5f` x4 · `1.5f` x3 · `0.4f` x3 · `0.1f` x2 · `-0.25f` x2 · `339.201f` x2 · `-1004.043f` x2 · `-99.416f` x2 · `348.593f` x2 · `-100.197f` x2 · `345.366f` x2 · `-100.208f` x2 · `350.583f` x2 · `-994.424f` x2 · `-100.171f` x2 · `350.369f` x2 · `-997.683f` x2

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `MP232_SUSPENSE`, `head`, `typ`, `ibs`, `int`, `MPIsland_Voltage_BG`, `rot`, `polmav`, `sprt`, `hclr`, `scl`, `MP232_DELIVERING_START`, `MP232_DELIVERING`, `MP232_GUNFIGHT`, `conada`, `MPIsland_Voltage`, `bsa`, `rad`, `name`, `**INVALID**`, `MP232_VEHICLE_ACTION`, `result_text`, `tun_prep_grab_midd_ig3`, `MP232_MED_INTENSITY`, `ALARMS_SOUNDSET`, `blp`

---

Source: `decompiled_scripts/fm_content_vehrob_prep.c`
