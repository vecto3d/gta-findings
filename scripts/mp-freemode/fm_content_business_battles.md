# fm_content_business_battles.c

MP freemode script. 2 anim dicts; 8 models; 25 scaleforms.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 524,180 |
| Functions | 10,311 (386 unique, 9,925 shared) |
| Unique lines | 24,642 (4.7% of file) |

## Assets

**Animation dictionaries** (2) - `anim@GangOps@Morgue@Office@Laptop@`, `anim@heists@keypad@`

**Animations** (1) - `idle_a`

**Models and props** (8) - `ba_prop_battle_drug_package_02`, `ba_prop_battle_rsply_crate_gr_02a`, `xs_prop_arena_crate_01a`, `ba_prop_battle_bag_01a`, `ba_prop_battle_case_sm_03`, `ch_prop_ch_casino_shutter01x`, `prop_sec_gate_01d`, `s_m_m_scientist_01`

**Audio banks** (1) - `ALARM_KLAXON_07`

**Sounds** (25) - `HACKING_MOVE_CURSOR`, `HACKING_CLICK_BAD`, `DLC_sum20_Business_Battle_AC_Sounds`, `HACKING_FAILURE`, `HACKING_COUNTDOWN_IP_FIND`, `HACKING_COUNTDOWN_CRACK_PASS`, `Hack_Success`, `MP_PROPERTIES_ELEVATOR_DOORS`, `HACKING_CLICK_GOOD`, `DLC_Sum20_Door_Hack_Scene`, `Air_Defences_Activated`, `Hack_Fail`, `door_unlocked`, `dlc_sum20_factory_raid_sounds`, `OPENING`, `OPENED`, `HACKING_CLICK`, `DLC_GR_Steal_Railguns_Sounds`, `HACKING_SUCCESS`, `unlocked_bleep`, `HACKING_DOOR_UNLOCK_SOUNDS`, `collect_part`, `DLC_sum20_BB_Captured_Sounds`, `06`, `Air_Defenses_Disabled`

**Scaleform movies** (25) - `SET_COLUMN_SPEED`, `SET_INPUT_EVENT`, `SET_LIVES`, `SET_INPUT_EVENT_SELECT`, `CLOSE_APP`, `SET_SPEED`, `OPEN_APP`, `SET_IP_OUTCOME`, `SET_ROULETTE_OUTCOME`, `SET_INPUT_EVENT_BACK`, `RUN_PROGRAM`, `SET_ROULETTE_WORD`, `LOSTIP`, `LOSEBRUTE`, `SET_COUNTDOWN`, `SET_CURSOR`, `ADD_PROGRAM`, `EXIT`, `WINIP`, `RESET_ROULETTE`, `STOP_ROULETTE`, `WINBRUTE`, `SHOW_MAP`, `OPEN_DOWNLOAD`, `MOVE_CURSOR`

**Text labels** (36) - `HACKOBJ5`, `TRYDL`, `ACCESSD`, `HACKOBJ2`, `HACKOBJ3`, `TRYBRUTE`, `TRYHACK`, `HACKOBJ7`, `IDLE`, `HACKOBJ1`, `STRING`, `ENTER`, `EXIT`, `00FOD803`, `89YEM976`, `61ZFY108`, `05IWX071`, `44VPO421`, `09LQC819`, `85IZD653`, `64OYG966`, `63PUP188`, `47ZPV805`, `53686974`, `53544453`, `41727365`, `54697473`, `HACK`, `44OGG425`, `09ALB692`, `43PCT649`, `66RAI976`, `53RYN511`, `89STV802`, `20SKL158`, `44TOR049`

**Decorators** (3) - `MPBitset`, `BBCarrier`, `FMCVehicle`

**Interiors and entity sets** (2) - `v_foundry`, `int_carrier_hanger`

**Doors** (5) - `prop_ron_door_01`, `v_ilev_staffdoor`, `v_ilev_rc_door3_l`, `v_ilev_rc_door3_r`, `v_ilev_rc_door1`

**Hashed names** (3) - `foundrymainrm`, `foudhighrm`, `foundrydogleg`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (84), `IS_CONTROL_JUST_PRESSED` (74), `SET_BIT` (71), `CALL_SCALEFORM_MOVIE_METHOD_WITH_NUMBER` (54), `TO_FLOAT` (52), `PLAY_SOUND_FRONTEND` (43), `GET_GAME_TIMER` (38), `BEGIN_SCALEFORM_MOVIE_METHOD` (30), `DOOR_SYSTEM_GET_DOOR_STATE` (22), `PLAYER_ID` (21), `CLEAR_BIT` (21), `HAS_SOUND_FINISHED` (18), `END_SCALEFORM_MOVIE_METHOD` (17), `STOP_SOUND` (17), `RELEASE_SOUND_ID` (16), `GET_RANDOM_INT_IN_RANGE` (15), `IS_SCALEFORM_MOVIE_METHOD_RETURN_VALUE_READY` (15), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (14), `ABSF` (13), `END_SCALEFORM_MOVIE_METHOD_RETURN_VALUE` (13), `CALL_SCALEFORM_MOVIE_METHOD` (13), `DOOR_SYSTEM_FIND_EXISTING_DOOR` (11), `GET_SOUND_ID` (11), `IS_USING_KEYBOARD_AND_MOUSE` (11), `IS_POINT_IN_ANGLED_AREA` (10), `IS_PAUSE_MENU_ACTIVE` (10), `ADD_DOOR_TO_SYSTEM` (9), `CLEAR_HELP` (9), `DOES_ENTITY_EXIST` (8), `PLAYER_PED_ID` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`27.159f` x8 · `0.5f` x8 · `10.3f` x4 · `31.17f` x4 · `33.161f` x4 · `0.2f` x4 · `3103.207f` x2 · `-4805.419f` x2 · `3080.537f` x2 · `-4811.319f` x2 · `29.5f` x2 · `3098.5f` x2 · `-4791.1f` x2 · `6.6f` x2 · `3100.8f` x2 · `5.5f` x2 · `3098.3f` x2 · `-4748.5f` x2 · `2.55f` x2 · `3105.6f` x2 · `-4775.6f` x2 · `9.25f` x2 · `3.5f` x2 · `22.25f` x2

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `lazer`, `rot`, `bsa`, `ibs`, `mesa3`, `FMBB_STOVER_T`, `sprt`, `hclr`, `scl`, `veh`, `rad`, `typ`, `BBOT_LOSECOPS`, `SUM20_BB_FAIL`, `H_EXIT_PROMPT`, `MAX_NUM_SCENARIOS`, `blp`, `grp`, `wp_wt_raypistol_t0_v0`, `ACA_HT_BLIP_N`, `ACA_HT_BLIP_D`, `BBH_ATCAP1`

---

Source: `decompiled_scripts/fm_content_business_battles.c`
