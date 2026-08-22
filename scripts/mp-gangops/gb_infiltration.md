# gb_infiltration.c

MP gang ops script. 1 anim dicts; 12 models.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 482,813 |
| Functions | 8,811 (212 unique, 8,599 shared) |
| Unique lines | 16,403 (3.4% of file) |

## Assets

**Animation dictionaries** (1) - `anim@GangOps@Morgue@Office@Laptop@`

**Models and props** (12) - `s_m_m_highsec_01`, `s_m_m_security_01`, `g_m_y_mexgoon_01`, `a_m_y_business_03`, `prop_laptop_01a`, `g_m_y_famfor_01`, `prop_jyard_block_01a`, `prop_cctv_cam_06a`, `prop_cctv_cam_01a`, `g_m_y_famca_01`, `g_m_m_mexboss_01`, `hei_prop_hst_usb_drive`

**Text labels** (9) - `COP`, `STRING`, `NULL`, `HACK`, `PAIFMAU`, `PAIGE`, `ENTER`, `IDLE`, `EXIT`

**Interiors and entity sets** (1) - `v_faceoffice`

**Scripts launched** (1) - `am_mp_smpl_interior_int`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PARTICIPANT_ID_TO_INT` (45), `PLAYER_PED_ID` (42), `PLAYER_ID` (39), `SET_RELATIONSHIP_BETWEEN_GROUPS` (36), `PARTICIPANT_ID` (29), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (27), `CLEAR_BIT` (20), `DOES_BLIP_EXIST` (16), `SET_BIT` (15), `DOES_ENTITY_EXIST` (14), `GET_ENTITY_COORDS` (14), `CLEAR_HELP` (13), `NET_TO_ENT` (12), `NETWORK_DOES_NETWORK_ID_EXIST` (9), `HAS_SOUND_FINISHED` (9), `STOP_SOUND` (9), `RELEASE_SOUND_ID` (9), `TRIGGER_MUSIC_EVENT` (7), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (6), `SET_MODEL_AS_NO_LONGER_NEEDED` (6), `SET_BLIP_COLOUR` (6), `IS_STRING_NULL_OR_EMPTY` (6), `SET_BLIP_SCALE` (6), `GET_PLAYER_INDEX` (6), `NETWORK_HAS_CONTROL_OF_ENTITY` (6), `IS_PED_IN_ANY_VEHICLE` (5), `NETWORK_GET_PLAYER_INDEX_FROM_PED` (5), `SET_RADAR_ZOOM_PRECISE` (5), `SHOW_HEIGHT_ON_BLIP` (5), `GIVE_WEAPON_TO_PED` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.75f` x3 · `-1043.996f` x2 · `-216.0204f` x2 · `35.81622f` x2 · `-1071.679f` x2 · `-234.7674f` x2 · `45.58804f` x2 · `-1078.781f` x2 · `-252.7799f` x2 · `36.7633f` x2 · `1.25f` x2 · `0.4f` x1 · `-1034.07f` x1 · `-223.1364f` x1 · `36.01436f` x1 · `-1098.649f` x1 · `-270.2388f` x1 · `55.67468f` x1 · `-1069.61f` x1 · `-246.327f` x1 · `43.0211f` x1 · `-1063.274f` x1 · `-243.3052f` x1 · `40.33648f` x1

## Other strings

Literals whose consuming native was not classified:

`WORLD_HUMAN_GUARD_STAND`, `WORLD_HUMAN_SMOKING`, `WORLD_HUMAN_HANG_OUT_STREET`, `BB_IN_BMT_02`, `BB_IN_OBJ_041`, `WORLD_HUMAN_STAND_MOBILE_UPRIGHT`, `BTL_FAIL`, `BTL_MUSIC_STOP`, `DisableFlightMusic`, `WantedMusicDisabled`, `HACK_WORK_END`, `MBB_TARGET`, `BB_IN_BMT_00`, `BB_IN_BMT_01`, `BB_IN_BMS_040`, `BB_IN_BMS_041`, `BB_IN_OBJ_01`, `BB_IN_OBJ_02`, `BB_IN_OBJ_030`, `BB_IN_OBJ_031`, `oracle`, `buccaneer`, `superd`, `emperor`, `stalion`, `WORLD_HUMAN_CLIPBOARD`, `WORLD_HUMAN_WINDOW_SHOP_BROWSE`, `WORLD_HUMAN_STAND_MOBILE`, `WORLD_HUMAN_DRINKING`, `BTL_IDLE_START`

---

Source: `decompiled_scripts/gb_infiltration.c`
