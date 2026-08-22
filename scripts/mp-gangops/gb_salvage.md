# gb_salvage.c

MP gang ops script. 3 models; 1 particle effects.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 480,342 |
| Functions | 8,621 (107 unique, 8,514 shared) |
| Unique lines | 16,474 (3.4% of file) |

## Assets

**Models and props** (3) - `hei_prop_carrier_crate_01a`, `seashark`, `prop_flare_01b`

**Sounds** (6) - `Boss_Message_Orange`, `GTAO_Boss_Goons_FM_Soundset`, `Flare`, `DLC_Exec_Salvage_Sounds`, `5s`, `MP_MISSION_COUNTDOWN_SOUNDSET`

**Particle effects** (1) - `scr_heist_biolab_flare_underwater`

**Text labels** (2) - `NULL`, `CHECKPOINT`

**Vehicle mods** (1) - `seashark`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (36), `PLAYER_PED_ID` (34), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (19), `DOES_BLIP_EXIST` (18), `PARTICIPANT_ID_TO_INT` (16), `GET_PLAYER_PED` (15), `GET_ENTITY_COORDS` (13), `SET_BIT` (12), `VDIST` (10), `REMOVE_BLIP` (10), `NETWORK_DOES_NETWORK_ID_EXIST` (9), `DOES_ENTITY_EXIST` (7), `SET_AUDIO_FLAG` (6), `TRIGGER_MUSIC_EVENT` (6), `NET_TO_VEH` (5), `INT_TO_PARTICIPANTINDEX` (4), `DELETE_CHECKPOINT` (4), `IS_PED_IN_ANY_VEHICLE` (4), `HAS_MODEL_LOADED` (3), `REQUEST_MODEL` (3), `HAS_SOUND_FINISHED` (3), `SET_BLIP_ALPHA` (3), `GET_DISTANCE_BETWEEN_COORDS` (3), `GET_VEHICLE_PED_IS_IN` (3), `ADD_BLIP_FOR_COORD` (3), `SET_BLIP_SCALE` (3), `SET_BLIP_SPRITE` (3), `SET_BLIP_NAME_FROM_TEXT_FILE` (3), `SET_BLIP_PRIORITY` (3), `GET_HUD_COLOUR` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`2.5f` x2 · `0.1f` x1 · `0.11f` x1

## Other strings

Literals whose consuming native was not classified:

`GB_CHAL_OVER`, `seashark`, `GB_SAL_HELP1`, `DisableFlightMusic`, `WantedMusicDisabled`, `SALVAGE_STOP_MUSIC`, `APT_COUNTDOWN_30S`, `GB_SAL_HELP2`, `scr_biolab_heist`, `PIM_MAGM101`, `GBTER_BIGBSLFTC`, `GBTER_BIG_BSLFT`, `GB_GOONLEFTb`, `YachtRm_Bridge`, `GBM_IN_APRT`, `GB_BIGM_SAL_T`, `GB_SAL_HELP5`, `GB_SAL_SETUP`, `APT_COUNTDOWN_30S_KILL`, `GB_SAL_HELP4`, `GB_SAL_HELP6`, `GB_SAL_CASHPICK`, `service_earn_salvage_checkpoint_collection`, `AM_CP_COLLECTION`, `BLIP_REBREATHE`, `GB_SAL_HELP1b`, `CPC_BLIP`, `GB_CHAL_END`, `SALVAGE_START_MUSIC`, `GB_SAL_GO1b`

---

Source: `decompiled_scripts/gb_salvage.c`
