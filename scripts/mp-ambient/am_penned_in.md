# am_penned_in.c

MP ambient script. 2 scaleforms.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 102,132 |
| Functions | 1,520 (153 unique, 1,367 shared) |
| Unique lines | 9,059 (8.9% of file) |

## Assets

**Audio banks** (1) - `HUD_MINI_GAME_SOUNDSET`

**Sounds** (16) - `MP_Player_Outside_Bubble_Scene`, `MP_Player_Inside_Bubble_Scene`, `GTAO_FM_Events_Soundset`, `HUD_MINI_GAME_SOUNDSET`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `3_2_1`, `BACK`, `EXIT`, `Event_Start_Text`, `OOB_Cancel`, `OOB_Start`, `OOB_Timer_Dynamic`, `Time`, `GO`, `RACES_RADIO_MUTE_scene`, `MP_RACE_GENERAL_SCENE`

**Scaleform movies** (2) - `SET_MESSAGE`, `NUMBER`

**Text labels** (1) - `NULL`

**Decorators** (5) - `MPBitset`, `Veh_Modded_By_Player`, `bombdec1`, `bombdec`, `bombowner`

**Relationship groups** (2) - `relPennedInPlayer`, `relPennedInAi`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PARTICIPANT_ID_TO_INT` (227), `PLAYER_PED_ID` (166), `SET_BIT` (144), `PLAYER_ID` (130), `CLEAR_BIT` (98), `IS_PED_INJURED` (41), `GET_VEHICLE_PED_IS_IN` (26), `DOES_BLIP_EXIST` (19), `SET_PED_CONFIG_FLAG` (19), `INT_TO_PARTICIPANTINDEX` (18), `IS_PED_SITTING_IN_ANY_VEHICLE` (16), `GET_CLOUD_TIME_AS_INT` (15), `TO_FLOAT` (15), `IS_VEHICLE_DRIVEABLE` (15), `DISABLE_CONTROL_ACTION` (14), `DOES_ENTITY_EXIST` (13), `STOP_AUDIO_SCENE` (12), `IS_PED_IN_ANY_VEHICLE` (12), `ARE_STRINGS_EQUAL` (12), `NETWORK_IS_PARTICIPANT_ACTIVE` (11), `GET_PLAYER_NAME` (11), `PLAY_SOUND_FRONTEND` (11), `SET_ENTITY_PROOFS` (11), `GET_ENTITY_MODEL` (11), `REMOVE_BLIP` (11), `IS_AUDIO_SCENE_ACTIVE` (11), `NET_TO_PED` (9), `NETWORK_GET_PLAYER_INDEX` (9), `NETWORK_IS_PLAYER_A_PARTICIPANT` (9), `ROUND` (9)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`2.75f` x2 · `-1.25f` x2 · `0.3f` x1

## Other strings

Literals whose consuming native was not classified:

`PEN_AREA`, `PEN_BAREA`, `pennedIn`, `PEN_EXITV`, `PEN_BIKE`, `PEN_VEHG`, `PEN_PBIKE`, `PEN_PVEHG`, `PennedInOut`, `service_earn_ambient_job_penned_in`, `AM_PENNED_IN`, `SCTV_HELI_HLP`, `CAG_NOP`, `PEN_ELM`, `CAG_VEH`, `MP_Penned_In_Vehicles_In_Bubble_Group`, `SYG_GOTOTIMER`, `chassis`, `CAG_PRES`, `SPEC_LEAVE`, `SPEC_SURE`, `CAG_BLIPS`, `PEN_PASSMD`, `PEN_MPLAY`, `PEN_START2`, `PEN_STILLP`, `BRS_BM_EXP1`, `PEN_VALVEH`, `PEN_VEH`, `rhino`

---

Source: `decompiled_scripts/am_penned_in.c`
