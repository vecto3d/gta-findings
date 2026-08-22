# am_mp_smpl_interior_ext.c

MP ambient script. 1 models.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 402,834 |
| Functions | 7,509 (511 unique, 6,998 shared) |
| Unique lines | 27,963 (6.9% of file) |

## Assets

**Models and props** (1) - `prop_boombox_01`

**Audio banks** (2) - `DLC_EXEC1/BUY_SELL`, `DLC_CHRISTMAS2017/XM_FACILITY_ENTRY_EXIT`

**Sounds** (18) - `HUD_FREEMODE_SOUNDSET`, `BACK`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `SELECT`, `NAV_UP_DOWN`, `DLC_Exec1_Buy_Sell_Sounds`, `DLC_GR_MOC_Drive_Up_Ramp_Scene`, `OK`, `CANCEL`, `EXEC1_Enter_Office_From_Heli_Scene`, `Delivery_Screen_Fade`, `Delivery_Screen_Fade_On_Foot`, `hold`, `Garage_Door_Close`, `GTAO_Script_Doors_Faded_Screen_Sounds`, `Opening_Oneshot_Override_Fade`, `DLC_25-2_Mansion_Gate_Sounds`, `EXEC1_Enter_Office_From_Heli_Fade_To_Black_Scene`

**Speech contexts** (1) - `DLC_BTL_Nightclub_Queue_SCL`

**Text labels** (2) - `NULL`, `EXHELAU`

**Decorators** (5) - `MPBitset`, `Player_Avenger`, `Player_Vehicle`, `CreatedByPegasus`, `HeliTaxi`

**Vehicle mods** (4) - `phantom3`, `hauler2`, `trailerlarge`, `stromberg`

**Scripts launched** (4) - `AM_MP_SMPL_INTERIOR_INT`, `am_mp_property_int`, `am_mp_smpl_interior_int`, `am_heli_taxi`

## Native vocabulary

Most-called natives inside the code unique to this script:

`CLEAR_BIT` (217), `SET_BIT` (155), `PLAYER_ID` (117), `PLAYER_PED_ID` (83), `DOES_ENTITY_EXIST` (70), `IS_ENTITY_DEAD` (67), `GET_ENTITY_MODEL` (64), `GET_VEHICLE_PED_IS_IN` (53), `DISABLE_CONTROL_ACTION` (36), `IS_SCREEN_FADED_OUT` (35), `SET_INPUT_EXCLUSIVE` (27), `PLAY_SOUND_FRONTEND` (25), `FREEZE_ENTITY_POSITION` (24), `GET_PLAYER_PED` (22), `IS_STRING_NULL_OR_EMPTY` (21), `DOES_CAM_EXIST` (20), `SET_WARNING_MESSAGE_WITH_HEADER` (20), `GET_ENTITY_COORDS` (19), `NETWORK_HAS_CONTROL_OF_ENTITY` (19), `GET_ENTITY_HEADING` (19), `GET_PED_IN_VEHICLE_SEAT` (18), `SET_STATIC_EMITTER_ENABLED` (18), `IS_PED_IN_ANY_VEHICLE` (16), `ENABLE_CONTROL_ACTION` (16), `INT_TO_PLAYERINDEX` (13), `SET_ENTITY_COLLISION` (13), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (13), `IS_SCREEN_FADED_IN` (13), `DO_SCREEN_FADE_OUT` (12), `CLEAR_HELP` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.75f` x9 · `2.5f` x4 · `1.6f` x3 · `1.5f` x2 · `-4.5f` x2 · `1.9f` x2 · `-6.5f` x2 · `-2.5f` x1 · `2.25f` x1 · `1.8f` x1 · `-7.5f` x1 · `6.5f` x1 · `-0.1f` x1 · `0.5f` x1

## Other strings

Literals whose consuming native was not classified:

`SE_ba_dlc_club_exterior`, `SE_h4_dlc_int_02_h4_Entrance_Doorway`, `SE_xm3_dlc_lab_radioemitter_exterior`, `AZ_DLC_XM3_LAB_EXT_01`, `HUB_FULL_C`, `AM_MP_SMPL_INTERIOR_INT`, `HAND_SHAKE`, `oppressor2`, `HIDDEN_RADIO_BIKER_CLASSIC_ROCK`, `dlc_battle_mix1_club_priv`, `dlc_battle_mix2_club_priv`, `dlc_battle_mix3_club_priv`, `dlc_battle_mix4_club_priv`, `SE_RESTAURANTS_SUNSET_13`, `MP_PROP_MENU1`, `DEFAULT_SCRIPTED_CAMERA`, `stromberg`, `HUB_FULL_W`, `HUB_VEH_S`, `kosatka`, `terbyte`, `HANGAR_NO_ENTRY`, `MP_OFFICE_DOCKB`, `MP_OFFICE_DOCKA`, `HIDDEN_RADIO_BIKER_MODERN_ROCK`, `HIDDEN_RADIO_BIKER_HIP_HOP`, `HIDDEN_RADIO_BIKER_PUNK`, `HIDDEN_RADIO_ARCADE_POP`, `HIDDEN_RADIO_ARCADE_DANCE`, `HIDDEN_RADIO_ARCADE_EDM`

---

Source: `decompiled_scripts/am_mp_smpl_interior_ext.c`
