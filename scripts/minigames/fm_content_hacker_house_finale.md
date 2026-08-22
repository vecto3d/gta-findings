# fm_content_hacker_house_finale.c

Minigames script. 21 anim dicts; 8 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 517,924 |
| Functions | 10,861 (401 unique, 10,460 shared) |
| Unique lines | 13,584 (2.6% of file) |

## Assets

**Animation dictionaries** (21) - `amb@world_human_stand_impatient@male@no_sign@idle_a`, `anim@scripted@freemode@ig6_plant_device@heeled@`, `anim@scripted@freemode@ig6_plant_device@male@`, `anim@scripted@freemode@bounty_ig_plant_bomb_tower@heeled@`, `anim@scripted@freemode@bounty_ig_plant_bomb_tower@male@`, `anim@scripted@player@mission@tun_prep_plant_ig1@heeled@`, `anim@scripted@player@mission@tun_prep_plant_ig1@male@`, `anim@scripted@freemode@ig3_hold_up_phone@female@`, `anim@scripted@freemode@ig3_hold_up_phone@male@`, `anim@scripted@freemode@ig4_cabinet_smash@heeled@`, `anim@scripted@freemode@ig4_cabinet_smash@male@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@heeled@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `AMB@WORLD_HUMAN_STAND_MOBILE@FEMALE@TEXT@ENTER`, `AMB@WORLD_HUMAN_STAND_MOBILE@MALE@TEXT@ENTER`, `AMB@WORLD_HUMAN_STAND_MOBILE@FEMALE@TEXT@EXIT`, `AMB@WORLD_HUMAN_STAND_MOBILE@MALE@TEXT@EXIT`, `anim@door_trans@hinge_r@`, `anim@scripted@ulp_missions@garageopen@heeled@`, `anim@scripted@ulp_missions@garageopen@male@`, `anim@door_trans@elevator@`

**Models and props** (8) - `s_m_m_highsec_01`, `imp_prop_impex_gate_sm_15`, `s_m_m_movprem_01`, `sf_prop_sf_door_apt_l_01a`, `sf_prop_sf_door_apt_r_01a`, `ch_prop_ch_utility_door_01a`, `prop_phone_ing`, `prop_amb_phone`

**Audio banks** (2) - `DLC_HEI4/DLC_HEI4_FH_MG`, `DLC_HEIST3/Fingerprint_Match`

**Sounds** (33) - `Window_Clear`, `DLC_24-2_Fine_Art_Finale_Door_Vol_Boost_Scene`, `PICKUP_DEFAULT`, `HUD_FRONTEND_STANDARD_PICKUPS_SOUNDSET`, `DLC_24-2_Penthouse_Robbery_Sounds`, `Scramble_Countdown_High`, `Scramble_Countdown_Low`, `Processing`, `Print_Appears`, `Hack_Failed`, `GTAO_Script_Doors_Sounds`, `Scramble_Countdown_MED`, `Window_Draw`, `Target_Match`, `No_Match`, `Print_Shuffle`, `Scramble_Countdown_Med`, `Alarm_Timer`, `Ctrl`, `Generic_Door_Limit`, `Generic_Door_Push`, `Open_Hatch`, `Opened`, `DLC_24-2_Penthouse_Robbery_Bookcase_Door_Sounds`, `OPENED`, `DOOR_GARAGE_SMALL`, `Collect_Tiki_Package`, `EMP_Attach`, `Hack_Success`, `Print_Match`, `Print_Not_Match`, `Pattern_Shift`, `Pattern_Scramble`

**Texture dicts** (19) - `MPFClone_Retro`, `MPFClone_Retro_BACKGROUND`, `MPFClone_Retro_LIFE`, `MPFClone_Retro_LOADING`, `MPFClone_Retro_MESSAGES`, `MPFClone_Retro_CORRECT`, `MPFClone_Retro_NUMBERS`, `MPFClone_Retro_SCRAMBLER`, `MPHackingGame`, `MPHackingGameBG`, `MPHackingGameWin`, `MPHackingGameWin1`, `MPHackingGameWin2`, `MPHackingGameWin2_1`, `MPHackingGameWin2_2`, `MPHackingGameWin2_3`, `MPHackingGameWin3`, `MPHackingGameoverlay`, `MPHackingGameoverlay1`

**Text labels** (10) - `LIFTS`, `OPENING`, `24GCG512`, `08SBS693`, `21CLS413`, `87SAR125`, `04YSS925`, `M4RSH4LL`, `NUMBER`, `EXTRASUNNY`

**Timecycle modifiers** (1) - `Casino_Lightsoff`

**Scripts launched** (1) - `CircuitBlockHack`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (92), `SET_BIT` (63), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (34), `PLAY_SOUND_FRONTEND` (33), `NET_TO_ENT` (29), `DISABLE_CONTROL_ACTION` (26), `CLEAR_BIT` (22), `TO_FLOAT` (16), `REQUEST_STREAMED_TEXTURE_DICT` (15), `HAS_STREAMED_TEXTURE_DICT_LOADED` (15), `GET_ENTITY_COORDS` (12), `SET_STREAMED_TEXTURE_DICT_AS_NO_LONGER_NEEDED` (11), `SET_PED_CONFIG_FLAG` (10), `SET_PED_COMPONENT_VARIATION` (9), `IS_ENTITY_IN_ANGLED_AREA` (8), `FREEZE_ENTITY_POSITION` (7), `IS_ENTITY_VISIBLE` (7), `SET_ENTITY_VISIBLE` (7), `NETWORK_GET_PLAYER_INDEX` (6), `GET_RANDOM_INT_IN_RANGE` (6), `REQUEST_SCRIPT_AUDIO_BANK` (6), `HIDE_HUD_COMPONENT_THIS_FRAME` (6), `CLEAR_PED_TASKS` (6), `IS_STRING_NULL_OR_EMPTY` (6), `PLAYER_ID` (5), `FLOOR` (5), `SET_PED_COMBAT_ATTRIBUTES` (5), `GET_ENTITY_HEADING` (5), `CEIL` (4), `STOP_SOUND` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x13 · `-91.40005f` x8 · `1.5f` x5 · `0.75f` x3 · `-89.40005f` x3 · `-1113.235f` x3 · `-59.78449f` x3 · `-1113.24f` x3 · `-57.59947f` x3 · `-89.38877f` x3 · `0.516f` x2 · `-1113.314f` x2 · `-58.778f` x2 · `-89.995f` x2 · `-1113.306f` x2 · `-58.692f` x2 · `-89.65f` x2 · `-1414.345f` x2 · `-477.138f` x2 · `32.413f` x2 · `-1117.065f` x1 · `-68.47617f` x1 · `-1116.996f` x1 · `-56.79237f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `mphackinggame`, `rot`, `ibs`, `bsa`, `typ`, `PH_OT_ENTPEN0`, `sprt`, `hclr`, `scl`, `PH_OT_ENTMRM0`, `veh`, `rad`, `grp`, `MAX_NUM_SCENARIOS`, `blp`, `swift`, `conada`, `buzzard2`, `maverick`, `frogger`, `supervolito2`, `PH_IL_EMPC`

---

Source: `decompiled_scripts/fm_content_hacker_house_finale.c`
