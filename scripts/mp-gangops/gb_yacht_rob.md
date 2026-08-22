# gb_yacht_rob.c

MP gang ops script.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 165,546 |
| Functions | 2,157 (134 unique, 2,023 shared) |
| Unique lines | 4,448 (2.7% of file) |

## Assets

**Audio banks** (1) - `DLC_APARTMENT/APT_Yacht_01`

**Sounds** (6) - `MP_POSITIONED_RADIO_MUTE_SCENE`, `Horn`, `DLC_Apt_Yacht_Ambient_Soundset`, `GTAO_Magnate_Yacht_Attack_Soundset`, `Enemy_Capture_Start`, `Team_Capture_Start`

**Text labels** (1) - `NULL`

**Decorators** (2) - `MPBitset`, `Not_Allow_As_Saved_Veh`

**Scripts launched** (2) - `am_mp_property_int`, `am_mp_yacht`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (171), `SET_BIT` (59), `PARTICIPANT_ID_TO_INT` (50), `NET_TO_VEH` (44), `PREPARE_MUSIC_EVENT` (26), `TRIGGER_MUSIC_EVENT` (16), `CLEAR_HELP` (15), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (14), `CLEAR_BIT` (13), `INT_TO_PARTICIPANTINDEX` (12), `PLAYER_PED_ID` (12), `GET_CLOUD_TIME_AS_INT` (11), `SET_AUDIO_FLAG` (10), `NETWORK_IS_PARTICIPANT_ACTIVE` (8), `NETWORK_GET_PLAYER_INDEX` (6), `IS_ENTITY_IN_ANGLED_AREA` (6), `DOES_BLIP_EXIST` (6), `GET_PLAYER_PED` (5), `NETWORK_DOES_NETWORK_ID_EXIST` (5), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (5), `IS_ENTITY_DEAD` (5), `NETWORK_IS_PLAYER_ACTIVE` (5), `DECOR_SET_INT` (4), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (4), `SET_MODEL_AS_NO_LONGER_NEEDED` (4), `DECOR_IS_REGISTERED_AS_TYPE` (4), `SET_BLIP_NAME_FROM_TEXT_FILE` (4), `SET_BLIP_PRIORITY` (4), `CANCEL_MUSIC_EVENT` (3), `INT_TO_PLAYERINDEX` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`10.5f` x2 · `1.25f` x1 · `1.5f` x1

## Other strings

Literals whose consuming native was not classified:

`APT_YA_STOP`, `GB_WORK_OVER`, `APT_YA_STOP_LEAVE`, `APT_COUNTDOWN_30S_KILL`, `APT_YA_ACTION`, `APT_COUNTDOWN_30S`, `APT_FADE_IN_RADIO`, `WantedMusicDisabled`, `DisableFlightMusic`, `APT_YA_DEFENDING`, `APT_YA_ATTACK`, `GB_WINNER`, `APT_YA_START_DEFEND`, `APT_YA_START_ATTACK`, `GB_YA_OT0`, `GB_YA_OT1`, `GB_WORK_END`, `GB_YA_HP6`, `GB_YA_BMT0`, `APT_PRE_COUNTDOWN_STOP`, `AllowScoreAndRadio`, `GB_YA_TCK0`, `GB_YA_TCK1`, `GB_YA_HUD2`, `GB_YA_HUD0`, `GB_YA_BN2`, `GB_YA_BN3`, `GB_YA_BN0`, `GB_YA_BN1`, `GB_INTTXT_YA`

---

Source: `decompiled_scripts/gb_yacht_rob.c`
