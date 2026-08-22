# rural_bank_heist.c

Heists script. 19 anim dicts; 53 models; 5 particle effects.

| | |
|---|---|
| Category | Heists |
| Total lines | 132,840 |
| Functions | 1,090 (247 unique, 843 shared) |
| Unique lines | 17,481 (13.2% of file) |

## Assets

**Animation dictionaries** (19) - `move_f@scared`, `ANIM_GROUP_MOVE_BALLISTIC`, `MISSCOMMON@VAN_PUT_ON_MASKS`, `MISSHeistPaletoScore2`, `MOVE_STRAFE_BALLISTIC`, `MissHeistPaletoPinned`, `move_ballistic_2h`, `missheistpaletoscore2mcs_2_p5`, `missheistpaletoscore2mcs_2_p6`, `missheistpaletoscore2switch_bulldozer`, `missheistpaletoscore2chopper_crash`, `missheistpaletoscore2mcs_2_pt1`, `missheistpaletoscore2ig_8`, `missheistpaletoscore2ig_8_p2`, `missheistpaletoscore2`, `missheistpaletoscoreextra`, `MISSHeistBank_Bulldozer`, `missheistbank_bulldozer`, `MissHeistPaletoScore1`

**Animations** (69) - `missheistpaletoscore2mcs_2_pt1`, `MissHeistPaletoPinned`, `MISSCOMMON@VAN_PUT_ON_MASKS`, `missheistpaletoscore2mcs_2_p5`, `intimidate_loop_2_trevor`, `intimidate_loop_1_trevor`, `missheistpaletoscore2mcs_2_p6`, `pinned_against_wall_pro_buddy`, `missheistpaletoscore2ig_8_p2`, `PUT_ON_MASK_DS`, `PUT_ON_MASK_RDS`, `PUT_ON_MASK_RPS`, `intimidate_intro_trevor`, `intimidate_transition_trevor`, `MISSHeistBank_Bulldozer`, `MISSHeistPaletoScore2`, `pinned_against_wall_noob_buddy`, `missheistpaletoscore2`, `missheistpaletoscore2ig_8`, `end_loop_F`, `end_loop_M1`, `end_loop_M2`, `end_loop_M3`, `end_loop_M4`, `missheistpaletoscoreextra`, `factory_manager`, `Shovel_Idle_Trevor`, `Shovel_Idle_Michael`, `Dump_Exit_Michael`, `Dump_Exit_Trevor`, `pinned_against_wall_intro_COP`, `pinned_against_wall_pro_COP`, `pinned_against_wall_pro_loop_COP`, `pinned_against_wall_intro_buddy`, `pinned_against_wall_pro_loop_buddy`, `holdup_heavyarmour_crew`, `holdup_heavyarmour_player0`, `Exit_Van_ToBank_Gunman`, `Exit_Van_ToBank_Player2`, `AI_Loop_Player2_Bag`, `AI_Loop_Player2_Strap`, `Walk_In_Bank_Intro_Player2`, `Start_Loop_Player2`, `start_loop_F`, `start_loop_M1`, `start_loop_M2`, `start_loop_M3`, `start_loop_M4`, `Walk_In_Bank_Intro_Gunman`, `Start_Loop_A_Gunman`, `walk_in_bank_player2`, `walk_in_bank_gunman`, `walk_in_bank_F`, `walk_in_bank_M1`, `walk_in_bank_M2`, `walk_in_bank_M3`, `walk_in_bank_M4`, `intimidate_end_loop_trevor`, `burn_door_intro_gunman`, `burn_door_intro_Mask` ...

**Models and props** (53) - `s_m_y_marine_03`, `v_ilev_bank4door01`, `v_ilev_bank4door02`, `a_c_hen`, `s_f_y_factory_01`, `s_m_y_genericmarine_01_black_mini_01`, `prop_fncwood_01b`, `p_ld_heist_bag_s_1`, `bulldozer`, `barracks`, `a_m_m_business_01`, `v_ilev_cbankcountdoor01`, `rhino`, `washington`, `v_ilev_cf_officedoor`, `crusader`, `s_f_m_maid_01`, `prop_welding_mask_01_s`, `polmav`, `s_f_y_airhostess_01`, `v_ilev_cbankvaulgate01`, `a_m_y_business_02`, `prop_tool_blowtorch`, `p_csh_strap_01_s`, `prop_table_03_chr`, `prop_cigar_01`, `prop_facgate_03_l`, `prop_facgate_03_r`, `cargobob`, `prop_fncwood_01a`, `squalo`, `burrito3`, `prop_fnclink_04f`, `prop_arm_gate_l`, `A_M_Y_Business_02_WHITE_FULL_01`, `s_m_y_sheriff_01`, `s_m_y_swat_01`, `S_M_Y_Cop_01_WHITE_FULL_01`, `prop_fnclink_03gate1`, `prop_fnclink_03gate4`, `prop_cs_heist_bag_02`, `IG_4_P6_A1`, `riot`, `blazer`, `v_ilev_cbankvaulgate02`, `P_Novel_01_S`, `p_novel_01_s`, `freight`, `freightcont1`, `freightcont2`, `freightgrain`, `tankercar`, `freightcar`

**Audio banks** (13) - `PS2A_Jeep_Skids`, `PS2A_Gas_Station_Explosion_L`, `PS2A_Gas_Station_Explosion_R`, `PS2A_Enter_Bank`, `PS2A_Enter_Bank_2`, `Test_Pain`, `PS2A_Drive_Bulldozer`, `carBUlldzoer`, `PS2A_GAS_STATION_EXPLOSION_L`, `PS2A_GAS_STATION_EXPLOSION_R`, `PALETO_BAY_SCORE_ALARM`, `TIME_LAPSE`, `PS2A_CHICKEN_FACTORY`

**Sounds** (41) - `PS_2A_SHOOTOUT_START`, `PS_2A_GO_TO_FACTORY`, `PS_2A_SHOOTOUT_YARD_FLYING_TANK`, `PS_2A_ENTER_GARDENS`, `PS_2A_TRAIN_ARRIVES`, `PS2A_DISTANT_TRAIN_HORNS_MASTER`, `PS_2A_SHOOTOUT_YARD`, `PS_2A_CAR_RAMS_BUDDY`, `PS_2A_SHOOTOUT_ALLEY`, `PS_2A_SHOOTOUT_STREET_CREW_DIES`, `PS_2A_SHOOTOUT_STREET_MAIN`, `PS_2A_SHOOT_FENCE_1`, `PS_2A_DRIVE_TO_PALETO`, `PS_2A_SHOOTOUT_WAREHOUSE`, `PS_2A_SHOOTOUT_FACTORY`, `PS_2A_TANK_ARRIVES`, `PS_2A_DRIVE_BULLDOZER`, `PS_2A_SWITCH_TO_FRANKLIN`, `TEST_SCREAM_SHORT`, `PS_2A_SHOOTOUT_STREET_ARMY_HELI`, `PS_2A_SHOOTOUT_SWAT_VANS`, `PS_2A_HELI_CRASH`, `PS_2A_GAS_STATION_RAYFIRE`, `PS_2A_SHOOTOUT_HELI_ARRIVES`, `PS_2A_REVERSE_TO_ENTRANCE`, `PS_2A_ENTER_BANK`, `PS_2A_KICK_DOOR_OPEN`, `PS_2A_GO_TO_SAFE`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `PS2A_TRACTOR_THRU_CHAIN_LINK_MASTER`, `DiggerRevOneShot`, `BulldozerDefault`, `TEST_SCREAM_LONG`, `Gas_Station_Explosion`, `RURAL_BANK_HEIST_FINALE_SOUNDS`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `PS2A_MONEY_LOST`, `PALETO_SCORE_2A_BANK_SS`, `PS2A_WELDTORCH_MASTER`

**Particle effects** (5) - `scr_paleto_banknotes`, `scr_paleto_roof_impact`, `scr_paleto_heli_plume`, `scr_paleto_doorway_smoke`, `cs_paleto_blowtorch`

**Text labels** (56) - `RBH2AUD`, `TREVOR`, `MICHAEL`, `FRANKLIN`, `ALLCREWLEFT`, `DARYL`, `GUSTAVO`, `CHEF`, `PACKIE`, `COP`, `GETBCKDZ`, `BLEWHEIST`, `NORM`, `VANDIED`, `CBRAM`, `LEFTREVOR`, `FETCHCREW`, `GETINVAN`, `GETBACKIN`, `MASK`, `LEFTCREW`, `GETCHICK`, `DOZERLOST`, `TREVORLEFT`, `DOZER`, `LOSTMT`, `LOUDCOP2`, `LOSINGB`, `PARKVAN`, `WHIMPER`, `EXTRASUNNY`, `GETRAIL2`, `GETTRAIN`, `NULL`, `GETRAIL`, `DOZERDEST`, `RBHDZESC`, `CREWDIED`, `LEFTMIKE`, `MIKELEFT`, `RBHCOP`, `ARMY1`, `SWTMCH`, `RBHSTREET`, `CBSTG2`, `RBHMAID`, `GETTOMO`, `GETTOMO2`, `FENCE2`, `CHOPPER3`, `HOLDOFF`, `ABANDONHEIST`, `GOINSIDE`, `GETAWAYDEST`, `GETTOPIER`, `BANKH1`

**Waypoint recordings** (10) - `RBHGdnMichael`, `RBHGdnCrew`, `RBHMaid`, `RBHChkFrank`, `RBHFRANKBOAT`, `RBHArmySec1`, `RBHContSt1`, `RBHContSt2`, `RBHChckFct1`, `RBHchkTrevor`

**Vehicle recordings** (25) - `RBHdzCop`, `RBHStreet`, `RBHInitial`, `RBHArmySt`, `RBHPoolCops`, `RBHEnemyTank`, `RBHINitial`, `Dozer`, `ChopBank`, `RBHChin`, `RBHFlyover`, `CBRAM`, `CBCops`, `RBHDZESC`, `CBSwat`, `RBHThirdTank`, `RBHNewTank`, `ChargingTrucks`, `RBHdzTank`, `RBHChinDrop`, `RBHArmyST`, `RBHChinLand`, `CBRam`, `dozer`, `CBSWat`

**Relationship groups** (2) - `DUMMY`, `COPS`

**Interiors and entity sets** (1) - `V_factory4`

**Doors** (6) - `v_ilev_staffdoor`, `v_ilev_cbankcountdoor01`, `prop_arm_gate_l`, `prop_fnclink_03gate1`, `prop_fnclink_03gate4`, `v_ilev_cbankvaulgate02`

**Vehicle mods** (2) - `burrito`, `burrito3`

**Stats** (12) - `sp0_kills_cop`, `sp1_kills_cop`, `sp2_kills_cop`, `sp0_cars_cops_exploded`, `sp1_cars_cops_exploded`, `sp2_cars_cops_exploded`, `sp0_helis_exploded`, `sp1_helis_exploded`, `sp2_helis_exploded`, `sp0_kills_swat`, `sp1_kills_swat`, `sp2_kills_swat`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (509), `IS_PED_INJURED` (323), `IS_ENTITY_DEAD` (249), `DOES_ENTITY_EXIST` (171), `REQUEST_MODEL` (107), `SET_MODEL_AS_NO_LONGER_NEEDED` (103), `SET_PED_SPHERE_DEFENSIVE_AREA` (103), `GET_ENTITY_COORDS` (97), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (92), `GET_GAME_TIMER` (91), `HAS_MODEL_LOADED` (84), `SET_ENTITY_ONLY_DAMAGED_BY_PLAYER` (72), `CREATE_PED` (71), `TASK_SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (71), `SET_PED_COMBAT_ATTRIBUTES` (68), `IS_ENTITY_IN_ANGLED_AREA` (61), `REQUEST_VEHICLE_RECORDING` (61), `PLAYER_ID` (60), `OPEN_SEQUENCE_TASK` (60), `CLOSE_SEQUENCE_TASK` (60), `TASK_PERFORM_SEQUENCE` (60), `CLEAR_SEQUENCE_TASK` (60), `SET_ENTITY_COORDS` (58), `TASK_COMBAT_HATED_TARGETS_AROUND_PED` (57), `SET_ENTITY_HEADING` (57), `DELETE_PED` (54), `SET_PED_CONFIG_FLAG` (50), `HAS_VEHICLE_RECORDING_BEEN_LOADED` (50), `REMOVE_VEHICLE_RECORDING` (49), `SET_CUTSCENE_PED_COMPONENT_VARIATION` (49)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x65 · `2.5f` x37 · `0.25f` x30 · `30.2062f` x26 · `1.5f` x22 · `-109.622f` x21 · `6467.932f` x21 · `30.712f` x21 · `30.025f` x20 · `1.25f` x19 · `30.2064f` x14 · `30.6267f` x12 · `31.985f` x10 · `-157.594f` x10 · `6153.396f` x10 · `-152.772f` x10 · `6459.589f` x10 · `31.0824f` x10 · `-105.414f` x10 · `6474.93f` x10 · `2.1f` x9 · `0.6f` x9 · `30.63f` x9 · `30.4902f` x8

## Other strings

Literals whose consuming native was not classified:

`FIRING_PATTERN_FULL_AUTO`, `Michael`, `Trevor`, `Franklin`, `crusader`, `rhino`, `Lester`, `RBHdzCop`, `ANIM_GROUP_MOVE_BALLISTIC`, `sheriff`, `missheistpaletoscore2mcs_2_pt1`, `riot`, `RBHStreet`, `barracks`, `PS_2A_BUDDY_GROUP`, `washington`, `cargobob`, `polmav`, `player_two`, `burrito3`, `hc_gunman`, `WAVELOAD_PAIN_FEMALE`, `player_zero`, `RBH_Truck`, `PALETO_BAY_SCORE_ALARM`, `bulldozer`, `FIRING_PATTERN_BURST_FIRE`, `gunman_selection_1`, `Sherrif1`, `PALETO_BAY_SCORE_CHICKEN_FACTORY_ALARM`

---

Source: `decompiled_scripts/rural_bank_heist.c`
