# am_mp_yacht.c

MP ambient script. 25 anim dicts; 17 models; 6 scaleforms; 4 particle effects.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 408,787 |
| Functions | 7,148 (286 unique, 6,862 shared) |
| Unique lines | 22,316 (5.5% of file) |

## Assets

**Animation dictionaries** (25) - `anim@apt_trans@hinge_l`, `anim@apt_trans@hinge_r`, `ANIM@AMB@YACHT@CAPTAIN@`, `anim@amb@yacht@jacuzzi@standing@male@variation_01@`, `anim@amb@yacht@jacuzzi@standing@male@variation_02@`, `ANIM@APT_TRANS@BUZZER`, `anim@amb@yacht@jacuzzi@standing@female@variation_01@`, `anim@amb@yacht@jacuzzi@standing@female@variation_02@`, `anim@amb@yacht@jacuzzi@seated@male@variation_01@`, `anim@amb@yacht@jacuzzi@seated@male@variation_02@`, `anim@amb@yacht@jacuzzi@seated@male@variation_03@`, `anim@amb@yacht@jacuzzi@seated@male@variation_04@`, `anim@amb@yacht@jacuzzi@seated@male@variation_05@`, `anim@amb@yacht@jacuzzi@seated@female@variation_01@`, `anim@amb@yacht@jacuzzi@seated@female@variation_02@`, `anim@amb@yacht@jacuzzi@seated@female@variation_03@`, `anim@amb@yacht@jacuzzi@seated@female@variation_04@`, `anim@amb@yacht@jacuzzi@seated@female@variation_05@`, `anim@amb@yacht@rail@standing@female@variant_01@`, `anim@amb@yacht@rail@standing@male@variant_01@`, `anim@amb@yacht@bow@female@variation_01@`, `anim@amb@yacht@bow@male@variation_01@`, `veh@boat@jetski@front@base`, `veh@boat@speed@fds@base`, `veh@boat@predator@ds@base`

**Animations** (6) - `ext_door`, `anim@apt_trans@hinge_l`, `anim@apt_trans@hinge_r`, `ext_player`, `ANIM@AMB@YACHT@CAPTAIN@`, `idle`

**Models and props** (17) - `apa_prop_ap_port_text`, `apa_prop_ap_starb_text`, `apa_prop_ap_stern_text`, `prop_dummy_car`, `PROP_YACHT_HEI_WOH`, `prop_ld_keypad_01b`, `apa_prop_cs_plastic_cup_01`, `PROP_HEI_Y_0b`, `PROP_HEI_Y_2b`, `PROP_HEI_I_3b2`, `PROP_HEI_E_3`, `PROP_HEI_E_0`, `PROP_HEI_E_2`, `mp_m_boatstaff_01`, `PROP_GAR_HEI_WOH`, `PROP_YACHT`, `PROP_HEI_E_1`

**Audio banks** (1) - `DLC_APARTMENT/APT_Yacht_01`

**Sounds** (31) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `DLC_APT_YACHT_DOOR_SOUNDS`, `ERROR`, `SELECT`, `HUD_FREEMODE_SOUNDSET`, `DLC_Apt_Yacht_Ambient_Soundset`, `PUSH`, `NAV_UP_DOWN`, `LIMIT`, `GTAO_APT_DOOR_DOWNSTAIRS_GLASS_SOUNDS`, `Deck`, `DOOR_BUZZ`, `MP_PLAYER_APARTMENT`, `GTAO_Hot_Tub_Sounds`, `CLOSED`, `MP_POSITIONED_RADIO_MUTE_SCENE`, `ExitWater`, `GTAO_Hot_Tub_PED_INSIDE_WATER`, `PED_INSIDE_WATER`, `Engine`, `Hot_Tub_Loop`, `GTAO_Yacht_SoundSet`, `CANCEL`, `Closed`, `DOOR_BUZZ_ONESHOT_MASTER`, `WOODEN_DOOR_OPEN_NO_HANDLE_AT`, `Clothes_On`, `Clothes_Off`, `Moor_SEASHARK_Engine`, `Moor_Boat_Engine`, `BACK`

**Scaleform movies** (6) - `STRING`, `SET_YACHT_NAME`, `YACHT_NAME`, `YACHT_NAME_STERN`, `YACHT_GAMERNAME`, `SET_MISSION_INFO`

**Particle effects** (4) - `scr_apartment_mp`, `size`, `scr_apa_jacuzzi_wade`, `scr_apa_jacuzzi_steam`

**Text labels** (7) - `RAIN`, `THUNDER`, `EXTRASUNNY`, `FOGGY`, `STRING`, `NULL`, `BUMP`

**Interiors and entity sets** (8) - `ac_mpapa_yacht`, `h4_islandx_yacht_01_int`, `h4_islandx_yacht_02_int`, `h4_islandx_yacht_03_int`, `sf_yacht_01_int`, `sf_yacht_02_int`, `apa_mpapa_yacht`, `YachtRm_Bridge`

**Scripts launched** (3) - `am_mp_property_int`, `appmpjoblistnew`, `appjipmp`

**Hashed names** (2) - `apa_mpapa_yachtexterior`, `YachtRm_Bridge`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (304), `PLAYER_PED_ID` (281), `CLEAR_BIT` (163), `DISABLE_CONTROL_ACTION` (120), `SET_BIT` (117), `DOES_ENTITY_EXIST` (69), `PLAY_SOUND_FRONTEND` (34), `GET_ENTITY_COORDS` (33), `PLAY_PED_AMBIENT_SPEECH_NATIVE` (33), `NET_TO_ENT` (24), `GET_ENTITY_MODEL` (24), `SET_PED_COMPONENT_VARIATION` (24), `GET_HASH_KEY` (23), `CLEAR_HELP` (22), `GET_NETWORK_TIME` (22), `SET_PED_PRELOAD_VARIATION_DATA` (22), `FREEZE_ENTITY_POSITION` (21), `IS_PED_INJURED` (21), `GET_RANDOM_INT_IN_RANGE` (21), `GET_PLAYER_PED` (20), `SET_ENTITY_VISIBLE` (19), `GET_SYNCHRONIZED_SCENE_PHASE` (19), `GET_ENTITY_HEADING` (19), `SET_ENTITY_ROTATION` (18), `DOES_CAM_EXIST` (17), `ABSF` (17), `IS_ENTITY_DEAD` (17), `GET_FILENAME_FOR_AUDIO_CONVERSATION` (16), `SET_PED_CONFIG_FLAG` (15), `INT_TO_PLAYERINDEX` (14)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x10 · `-1.5f` x9 · `0.75f` x7 · `1.5f` x7 · `0.99f` x7 · `0.25f` x6 · `0.05f` x5 · `0.26f` x4 · `-935.1886f` x4 · `-378.4521f` x4 · `0.1f` x3 · `0.02f` x2 · `2.6f` x2 · `0.369f` x2 · `0.8f` x2 · `38.8713f` x2 · `39.8713f` x2 · `9.8f` x2 · `0.9375f` x2 · `24.91597f` x2 · `-0.25f` x1 · `-70.0027f` x1 · `7.9032f` x1 · `7.362f` x1

## Other strings

Literals whose consuming native was not classified:

`YACHT_GSY`, `DEFAULT_SCRIPTED_CAMERA`, `MPYACHT_LEAN`, `enter`, `YachtRm_Bridge`, `YACHT_MOVE_BLK`, `MPYACHT_UNLEAN`, `CUST_YACHT_WH`, `CUST_YAC_MISO`, `HAND_SHAKE`, `ext_door`, `port_text`, `starb_text`, `stern_text`, `chain`, `alt_chain`, `mp_f_freemode_01`, `PPA_GENYACHT0`, `PPA_GEN1`, `PPA_BEAST0`, `PPA_BEAST1`, `PPA_CONTRA3`, `idle_d_prop_cigar`, `idle_e_prop_cup`, `apa_mp_apa_yacht_door`, `apa_mp_apa_yacht_door2`, `MPJAC_UNLEAN`, `MPJAC_EXIT`, `MPJAC_LEAN`, `MPJAC_SIT`

---

Source: `decompiled_scripts/am_mp_yacht.c`
