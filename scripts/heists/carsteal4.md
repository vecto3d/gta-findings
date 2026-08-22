# carsteal4.c

Heists script. 4 anim dicts; 8 models; 5 particle effects.

| | |
|---|---|
| Category | Heists |
| Total lines | 127,670 |
| Functions | 977 (90 unique, 887 shared) |
| Unique lines | 9,106 (7.1% of file) |

## Assets

**Animation dictionaries** (4) - `veh@truck@ps@base`, `FACIALS@P_M_ONE@BASE`, `shake_cam_all@`, `map_objects`

**Animations** (22) - `packer_idle_base_trevor`, `sit`, `franklin_asleep`, `car_5_ig_6_car`, `die`, `ig_1_base`, `ig_10_switch_franklin`, `ig_1_idle_b`, `ig_8_part_01_exit`, `ig_8_part_01_exit_door`, `ig_8_part_02_loop`, `ig_8_part_03_jump`, `ig_8_part_03_jump_alt_trailer`, `car_5_ig_4`, `car_5_ig_6`, `waitloop_lamar`, `entercar_lamar`, `entercar_cardoor`, `packer_idle_1_trevor`, `packer_idle_2_trevor`, `packer_idle_3_trevor`, `packer_idle_4_trevor`

**Models and props** (8) - `prop_tyre_spike_01`, `s_m_y_sheriff_01`, `ig_molly`, `a_m_y_business_02`, `A_F_Y_Vinewood_02`, `ig_8_part_01_exit_cam`, `ig_8_part_02_loop_cam`, `ig_8_part_03_jump_cam`

**Audio banks** (6) - `CAR_STEAL_4`, `CAR_THEFT_FINALE`, `JWL_HEIST_CAR_SMASHES_BIG`, `Crane`, `Crane_Impact_Sweeteners`, `Crane_Stress`

**Sounds** (27) - `CAR_4_FIRST_PERSON_MUTES_SCENE`, `CAR_4_COPS_ARRIVE`, `CAR_4_FOCUS_ON_TRUCK`, `CAR_4_FOCUS_ON_FRANKLIN`, `CAR_4_SPIKES_CAM_SCENE`, `CAR_4_DEFEND_THE_TRUCK`, `CAR_4_GET_TO_PALETO`, `CAR_4_REVERSE_OFF_TRUCK`, `CAR_4_TAKE_CAR_TO_TRANSPORTER`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `CAR_THEFT_DB5_ESCAPE`, `CAR_4_FOLLOW_TRUCK`, `CAR_STEAL_4_SOUNDSET`, `Hit_Out`, `FRANKLIN_GUN_MASTER`, `JB700_GUN_PLAYER_MASTER`, `spikes`, `tyre`, `CAR_STEAL_4_RAMP_SCRAPE`, `Destroy_Cop_Car`, `JEWEL_HEIST_SOUNDS`, `out`, `SHORT_PLAYER_SWITCH_SOUND_SET`, `Short_Transition_In`, `CAR_STEAL_4_BURNOUT`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`

**Particle effects** (5) - `scr_carsteal4_trailer_scrape`, `scr_carsteal4_tyre_spikes`, `scr_carsteal5_tyre_spiked`, `scr_carsteal5_car_muzzle_flash`, `scr_carsteal4_wheel_burnout`

**Text labels** (10) - `CST7AUD`, `MOLLY`, `FRANKLIN`, `TREVOR`, `LAMAR`, `NULL`, `EXTRASUNNY`, `MICHAEL`, `665LDI37`, `H4HEIST`

**Scenarios** (3) - `WORLD_VEHICLE_POLICE_BIKE`, `WORLD_VEHICLE_POLICE_CAR`, `WORLD_VEHICLE_POLICE_NEXT_TO_CAR`

**Relationship groups** (1) - `player`

**Vehicle mods** (17) - `jb700`, `packer`, `phantom`, `hauler`, `pounder`, `scrap`, `mixer`, `flatbed`, `trailersmall`, `boattrailer`, `tr2`, `tr3`, `tr4`, `trailerlogs`, `trailers`, `trailers2`, `trailers3`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (246), `GET_ENTITY_COORDS` (156), `IS_ENTITY_DEAD` (131), `DOES_ENTITY_EXIST` (108), `GET_GAME_TIMER` (99), `PLAYER_ID` (96), `IS_PED_INJURED` (96), `IS_VEHICLE_DRIVEABLE` (95), `VDIST2` (83), `DISABLE_CONTROL_ACTION` (40), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (39), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (37), `FREEZE_ENTITY_POSITION` (36), `DOES_BLIP_EXIST` (36), `IS_PED_IN_VEHICLE` (33), `SET_MODEL_AS_NO_LONGER_NEEDED` (32), `SET_PED_INTO_VEHICLE` (26), `IS_AUDIO_SCENE_ACTIVE` (26), `REMOVE_ANIM_DICT` (25), `GET_RANDOM_INT_IN_RANGE` (24), `SET_ENTITY_COORDS` (22), `SET_VEHICLE_IS_CONSIDERED_BY_PLAYER` (21), `WAIT` (21), `ENABLE_DISPATCH_SERVICE` (20), `SET_ENTITY_HEADING` (19), `SET_PLAYER_CONTROL` (19), `IS_PED_SITTING_IN_VEHICLE` (19), `REQUEST_ANIM_DICT` (18), `IS_PLAYER_WANTED_LEVEL_GREATER` (17), `IS_VEHICLE_ATTACHED_TO_TRAILER` (16)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.001f` x22 · `0.5f` x7 · `1542.97f` x5 · `6481.625f` x5 · `21.582f` x5 · `4.1723f` x5 · `-2.3128f` x5 · `12.1723f` x5 · `3.3128f` x5 · `-0.25f` x4 · `0.05f` x4 · `2.5f` x4 · `1.15f` x4 · `231.4902f` x3 · `0.191836f` x3 · `-9.89637f` x3 · `0.27933f` x3 · `1547.081f` x3 · `6406.139f` x3 · `0.7764f` x3 · `1650.053f` x3 · `6498.229f` x3 · `-0.025f` x3 · `-0.3f` x3

## Other strings

Literals whose consuming native was not classified:

`CST7_CHAT1`, `CST7_CHAT1b`, `Franklin`, `CST7_UNHOOK`, `CST7_DRIVE2B`, `CST7_LINEUP2`, `CST7_TREVHI`, `CST7_MEET`, `CH_GETBACKCAR`, `CST7_WALK2`, `CH_GETBACK`, `CH_FRANHELP`, `seat_pside_f`, `CST7_DMG`, `CST7_MOLLY`, `CST7_MOLLY1`, `CAR_5_EXT`, `Lamar`, `CST7_CDONE`, `CST7_FIN01`, `CST7_FIN01B`, `CST7_WALK1`, `CST7_MORE`, `CH_SHOTHELP`, `CST7_BUTTON`, `CST7_HOOKED`, `CST7_DRIVE2C`, `CST7_DRIVE2D`, `CST7_DRIVE2F`, `CST7_DRIV2Fb`

---

Source: `decompiled_scripts/carsteal4.c`
