# localpopulator.c

Ambient world script. 1 developer state labels recovered; 7 anim dicts; 9 models.

| | |
|---|---|
| Category | Ambient world |
| Total lines | 12,689 |
| Functions | 150 (25 unique, 125 shared) |
| Unique lines | 3,184 (25.1% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`LPOP_STATE_CLEANUP`

## Assets

**Animation dictionaries** (7) - `anim@amb@carmeet@checkout_engine@male_a@idles`, `amb@world_human_window_shop@male@idle_a`, `anim@amb@carmeet@checkout_car@female_b@idles`, `anim@heists@prison_heiststation@cop_reactions`, `anim@amb@carmeet@take_photos@female_b@idles`, `amb@world_human_hang_out_street@male_b@idle_a`, `amb@world_human_seat_wall@male@hands_by_sides@idle_a`

**Animations** (2) - `anim@amb@carmeet@checkout_engine@male_a@idles`, `idle_a`

**Models and props** (9) - `a_m_y_carclub_01`, `a_f_y_carclub_01`, `prop_amb_phone`, `imp_prop_covered_vehicle_03a`, `imp_prop_covered_vehicle_01a`, `imp_prop_covered_vehicle_04a`, `imp_prop_covered_vehicle_05a`, `imp_prop_covered_vehicle_06a`, `imp_prop_covered_vehicle_02a`

**Audio banks** (1) - `DLC_TUNER/DLC_Tuner_Car_Meet_Test_Area`

**Sounds** (1) - `MP_POSITIONED_RADIO_MUTE_SCENE`

**Text labels** (29) - `OFF`, `43MLR467`, `42OTM958`, `42PHO918`, `63ADH761`, `47RNO136`, `56RAF112`, `66PJT141`, `40AJF699`, `82YLM383`, `69TJS608`, `03QMA772`, `45MCA163`, `43QZA094`, `82BPG904`, `61OEN493`, `00BUC112`, `42YAG396`, `80QDM423`, `89AXX718`, `46ODB296`, `01OWK692`, `83NGU235`, `02HJE974`, `61KDG752`, `65TLM709`, `03SVZ064`, `01PMT053`, `81QBV287`

**Scripts launched** (2) - `fm_mission_creator`, `fm_mission_controller_2020`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (492), `SET_BIT` (29), `SET_VEHICLE_LIGHTS` (23), `SET_PED_PROP_INDEX` (20), `SET_VEHICLE_DOOR_OPEN` (16), `SET_VEHICLE_DOOR_CONTROL` (16), `GET_FRAME_COUNT` (8), `SET_STATIC_EMITTER_ENABLED` (8), `DOES_ENTITY_EXIST` (6), `SET_EMITTER_RADIO_STATION` (5), `REQUEST_ANIM_DICT` (5), `HAS_ANIM_DICT_LOADED` (5), `TASK_PLAY_ANIM` (5), `LINK_STATIC_EMITTER_TO_ENTITY` (5), `WAIT` (4), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (4), `IS_ENTITY_A_VEHICLE` (3), `GET_VEHICLE_INDEX_FROM_ENTITY_INDEX` (3), `FREEZE_ENTITY_POSITION` (3), `SET_PED_FLEE_ATTRIBUTES` (3), `SET_AMBIENT_ZONE_STATE` (2), `SET_RADIO_TO_STATION_NAME` (2), `IS_ENTITY_A_PED` (2), `GET_PED_INDEX_FROM_ENTITY_INDEX` (2), `NETWORK_SET_SCRIPT_IS_SAFE_FOR_NETWORK_GAME` (1), `DRAW_DEBUG_TEXT_2D` (1), `DELETE_ENTITY` (1), `TERMINATE_THIS_THREAD` (1), `RELEASE_NAMED_SCRIPT_AUDIO_BANK` (1), `SET_AUDIO_FLAG` (1)

## Other strings

Literals whose consuming native was not classified:

`RADIO_36_AUDIOPLAYER`, `WORLD_HUMAN_HANG_OUT_STREET`, `WORLD_HUMAN_SMOKING`, `browse_a`, `WORLD_HUMAN_AA_COFFEE`, `fr36`, `sabregt2`, `manana2`, `moonbeam2`, `remus`, `SE_tr_tuner_car_meet_Meet_rm_Music_01`, `SE_tr_tuner_car_meet_Meet_rm_Music_02`, `SE_tr_tuner_car_meet_Meet_rm_Music_03`, `SE_tr_tuner_car_meet_Meet_rm_Music_04`, `SE_tr_tuner_car_meet_Meet_rm_Music_05`, `idle_a`, `jester4`, `dominator8`, `TUNER_AP_MIX3_PARTC`, `WORLD_HUMAN_STAND_MOBILE`, `WORLD_HUMAN_INSPECT_STAND`, `WORLD_HUMAN_SMOKING_POT`, `xm3_prop_xm3_cover_veh_02a`, `AllowScoreAndRadio`, `SE_tr_tuner_car_meet_Main_rm_Vehicle_Noise_01`, `SE_tr_tuner_car_meet_Main_rm_Vehicle_Noise_02`, `SE_tr_tuner_car_meet_Meet_rm_Music_Takeover`, `AZ_tr_tuner_car_meet_Meet_BG`, `AZ_tr_tuner_car_meet_Meet_BG_2`, `drunk_idle`

---

Source: `decompiled_scripts/localpopulator.c`
