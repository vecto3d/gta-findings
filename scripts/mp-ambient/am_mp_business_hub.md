# am_mp_business_hub.c

MP ambient script. 8 anim dicts; 39 models; 2 scaleforms.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 446,622 |
| Functions | 8,088 (312 unique, 7,776 shared) |
| Unique lines | 30,139 (6.7% of file) |

## Assets

**Animation dictionaries** (8) - `anim@amb@warehouse@laptop@`, `anim@apt_trans@elevator`, `amb@world_human_leaning@male@wall@back@mobile@idle_a`, `anim@amb@office@boss@male@`, `amb@prop_human_seat_chair_drink_beer@male@idle_a`, `amb@prop_human_seat_chair@male@elbows_on_knees@base`, `amb@prop_human_seat_chair@male@left_elbow_on_knee@idle_a`, `amb@prop_human_seat_computer@male@base`

**Models and props** (39) - `ba_prop_battle_crates_rifles_02a`, `ba_prop_battle_crates_pistols_01a`, `ba_prop_battle_crates_rifles_01a`, `ba_prop_battle_crates_wpn_mix_01a`, `ba_prop_battle_crates_rifles_04a`, `ba_prop_battle_crates_rifles_03a`, `ba_prop_battle_crates_sam_01a`, `ba_prop_battle_crate_med_bc`, `sm_prop_smug_crate_m_medical`, `sm_prop_smug_crate_m_bones`, `ba_prop_battle_crate_closed_bc`, `ba_prop_battle_crate_wlife_bc`, `sm_prop_smug_crate_m_jewellery`, `ba_prop_battle_crate_gems_bc`, `ba_prop_battle_crate_art_02_bc`, `sm_prop_smug_crate_m_hazard`, `sm_prop_smug_crate_m_tobacco`, `ba_prop_battle_crate_tob_bc`, `sm_prop_smug_crate_m_antiques`, `ba_prop_battle_crate_biohazard_bc`, `ba_prop_door_elevator_1l`, `ba_prop_door_elevator_1r`, `ba_prop_battle_fakeid_boxpp_01a`, `ba_prop_battle_fakeid_boxdl_01a`, `s_m_y_waretech_01`, `hei_prop_hei_securitypanel`, `gr_prop_gr_rsply_crate04b`, `prop_beer_bottle`, `prop_npc_phone`, `PROP_OFFG_SL`, `speedo4`, `ba_prop_battle_club_chair_01`, `Prop_Screen_Nightclub`, `ba_prop_battle_club_computer_01`, `ba_prop_battle_coke_doll_bigbox`, `ba_prop_battle_meth_bigbag_01a`, `ba_prop_battle_weed_bigbag_01a`, `ba_prop_battle_moneypack_02a`, `prop_tv_flat_01`

**Sounds** (13) - `MP_PROPERTIES_ELEVATOR_DOORS`, `HUD_FREEMODE_SOUNDSET`, `DLC_Ba_NightClub_Garage_Scene`, `SELECT`, `CANCEL`, `NAV_UP_DOWN`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `FAKE_ARRIVE`, `BUTTON`, `OPENING`, `OPENED`, `CLOSED`, `CLOSING`

**Speech contexts** (3) - `BTL_YOHAN`, `GENERIC_HI`, `BYE_WORK`

**Scaleform movies** (2) - `SET_VEHICLE_INFOR_AND_STATS`, `FM_TWO_STRINGS`

**Texture dicts** (4) - `MPCarHUD`, `MPCarHUD2`, `MPCarHUD3`, `MPCarHUD4`

**Text labels** (8) - `NULL`, `GALAXY`, `GEFAGNIS`, `OMEGA`, `TECHNOLOGIE`, `PARADISE`, `IDLES`, `ENTER`

**Decorators** (2) - `Player_Hacker_Truck`, `Player_Vehicle`

**Vehicle mods** (3) - `terbyte`, `oppressor2`, `speedo4`

**Scripts launched** (4) - `business_hub_garage_seats`, `appBusinessHub`, `appmpjoblistnew`, `appjipmp`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (246), `CLEAR_BIT` (163), `SET_BIT` (159), `PLAYER_PED_ID` (150), `DOES_ENTITY_EXIST` (70), `NET_TO_VEH` (47), `SET_PED_COMPONENT_VARIATION` (45), `NETWORK_IS_ACTIVITY_SESSION` (28), `DISABLE_CONTROL_ACTION` (23), `GET_SCRIPT_TASK_STATUS` (23), `GET_PLAYER_PED` (22), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (21), `IS_SCREEN_FADED_OUT` (21), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (20), `SET_INPUT_EXCLUSIVE` (20), `GET_ENTITY_COORDS` (20), `SET_VEHICLE_DOORS_LOCKED_FOR_PLAYER` (19), `SET_PED_CONFIG_FLAG` (19), `IS_ENTITY_DEAD` (17), `IS_CONTROL_PRESSED` (17), `ABSF` (17), `FREEZE_ENTITY_POSITION` (17), `SET_VEHICLE_DOORS_LOCKED_FOR_ALL_PLAYERS` (16), `SET_MODEL_AS_NO_LONGER_NEEDED` (15), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (14), `IS_PED_IN_VEHICLE` (14), `GET_RANDOM_INT_IN_RANGE` (14), `SET_DONT_ALLOW_PLAYER_TO_ENTER_VEHICLE_IF_LOCKED_FOR_PLAYER` (13), `IS_STRING_NULL_OR_EMPTY` (13), `NETWORK_REQUEST_CONTROL_OF_NETWORK_ID` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x18 · `0.15f` x9 · `-3016.199f` x6 · `-79.0482f` x6 · `-3025.446f` x6 · `-79.0447f` x6 · `0.7f` x6 · `0.75f` x3 · `-1506.849f` x3 · `-1508.406f` x3 · `-1508.404f` x3 · `-1506.851f` x3 · `7.5f` x2 · `-78.3193f` x2 · `-4.0321f` x2 · `-80.6973f` x2 · `-11.3149f` x2 · `-80.0591f` x2 · `-10.5756f` x2 · `-69.4434f` x2 · `47.0993f` x2 · `-83.2073f` x2 · `0.25f` x2 · `-3031.1f` x2

## Other strings

Literals whose consuming native was not classified:

`MP_PROP_CAR1`, `club_computer`, `speedo4`, `idle_a`, `se_ba_int_02_ba_workshop_radio`, `CLUB_PH_WARN_T`, `HUB_PC_BLCK2`, `BUNK_PC_BLCK2`, `BUNK_PC_BLCK_M`, `BUNK_PC_BLCK3`, `HUB_PC_BLCK`, `terbyte`, `BB_YES`, `BB_NO`, `VEH_REP_WARN`, `MP_BHUB_GAR2`, `MP_BHUB_GAR3`, `MP_BHUB_GAR1`, `MP_MAN_VEH_S`, `BB_BACK`, `MP_PROP_CAR0`, `Int_02_Room1`, `mule4`, `pounder2`, `CLUB_PH_HELP_3`, `CLUB_PH_HELP_4`, `CLUB_PH_HELP_5`, `base`

---

Source: `decompiled_scripts/am_mp_business_hub.c`
