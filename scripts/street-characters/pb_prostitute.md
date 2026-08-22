# pb_prostitute.c

Street characters script. 10 anim dicts; 3 models.

| | |
|---|---|
| Category | Street characters |
| Total lines | 19,120 |
| Functions | 567 (261 unique, 306 shared) |
| Unique lines | 8,246 (43.1% of file) |

## Assets

**Animation dictionaries** (10) - `anim@mini@prostitutes@sex@veh_vstr@`, `mini@prostitutes@sexnorm_veh_first_person`, `mini@prostitutes@sexnorm_veh`, `mini@prostitutes@sexlow_veh_first_person`, `mini@prostitutes@sexlow_veh`, `mini@hookers_spcrackhead`, `mini@hookers_spcokehead`, `mini@hookers_spfrench`, `mini@hookers_spvanilla`, `clipset@veh@low@ps@female@base`

**Models and props** (3) - `prop_to_sit_alt_prostitute`, `prop_to_sit_male`, `prop_to_sit_prostitute`

**Audio banks** (2) - `SCRIPT\HUD_321_GO`, `PROSTITUTE_BLOWJOB`

**Sounds** (3) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `SELECT`, `NAV_UP_DOWN`

**Speech contexts** (29) - `SPEECH_PARAMS_FORCE_SHOUTED_CLEAR`, `SEX_GENERIC`, `HOOKER_DECLINED_TREVOR`, `HOOKER_DECLINED`, `SOLICIT_MICHAEL`, `SOLICIT_MICHAEL_RETURN`, `SOLICIT_FRANKLIN`, `SOLICIT_FRANKLIN_RETURN`, `SOLICIT_TREVOR`, `SOLICIT_TREVOR_RETURN`, `HOOKER_LEAVES_ANGRY`, `HOOKER_STORY_REVULSION_RESP`, `HOOKER_STORY_SARCASTIC_RESP`, `HOOKER_STORY_SYMPATHETIC_RESP`, `HOOKER_DECLINE_SERVICE`, `SEX_FINISHED`, `HOOKER_HAD_ENOUGH`, `SEX_CLIMAX`, `SPEECH_PARAMS_FORCE_NORMAL_CLEAR`, `SEX_ORAL`, `SEX_ORAL_FEM`, `SEX_GENERIC_FEM`, `HOOKER_OFFER_SERVICE`, `HOOKER_OFFER_AGAIN`, `HOOKER_SECLUDED`, `HOOKER_REQUEST`, `HOOKER_CAR_INCORRECT`, `APOLOGY_NO_TROUBLE`, `SPEECH_PARAMS_FORCE_SHOUTED_CRITICAL`

**Text labels** (4) - `NULL`, `MICHAEL`, `FRANKLIN`, `TREVOR`

**Scenarios** (6) - `base`, `WORLD_HUMAN_PROSTITUTE_HIGH_CLASS`, `amb@world_human_prostitute@crackhooker@base`, `amb@world_human_prostitute@cokehead@base`, `amb@world_human_prostitute@french@base`, `amb@world_human_prostitute@hooker@base`

**Relationship groups** (1) - `ProstituteInPlay`

**Scripts launched** (2) - `carwash1`, `carwash2`

**Hashed names** (17) - `SABRE_CAG`, `MINI_PROSTITUTE_LOW_RESTRICTED_PASSENGER`, `MINI_PROSTITUTE_LOW_RESTRICTED_NOAMBIENT_PASSENGER`, `MINI_PROSTITUTE_LOW_LOWRIDER_PASSENGER`, `MINI_PROSTITUTE_LOW_LOWRIDER2_PASSENGER`, `MINI_PROSTITUTE_LOW_INFERNUS2_PASSENGER`, `MINI_PROSTITUTE_LOW_SC1_PASSENGER`, `MINI_PROSTITUTE_LOW_TEZERACT_PASSENGER`, `MINI_PROSTITUTE_LOW_DOMINATOR3_PASSENGER`, `MINI_PROSTITUTE_LOW_ITALIGTO_PASSENGER`, `MINI_PROSTITUTE_LOW_RESTRICTED_SCHLAGEN_PASSENGER`, `MINI_PROSTITUTE_LOW_NEO_PASSENGER`, `MINI_PROSTITUTE_LOW_PEYOTE2_PASSENGER`, `MINI_PROSTITUTE_LOW_ZR350_PASSENGER`, `MINI_PROSTITUTE_LOW_IGNUS_PASSENGER`, `MINI_PROSTITUTE_LOW_ZENO_PASSENGER`, `MINI_PROSTITUTE_LOW_PASSENGER`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (228), `PLAYER_ID` (47), `GET_VEHICLE_PED_IS_IN` (47), `IS_VEHICLE_DRIVEABLE` (41), `IS_ENTITY_DEAD` (39), `GET_ENTITY_COORDS` (35), `IS_PED_INJURED` (34), `NETWORK_HAS_CONTROL_OF_ENTITY` (32), `IS_PED_IN_ANY_VEHICLE` (32), `DOES_ENTITY_EXIST` (29), `DISABLE_CONTROL_ACTION` (28), `TASK_PLAY_ANIM` (27), `PLAY_PED_AMBIENT_SPEECH_NATIVE` (27), `GET_ENTITY_MODEL` (24), `GET_SCRIPT_TASK_STATUS` (22), `IS_ANY_SPEECH_PLAYING` (22), `VDIST` (21), `GET_VEHICLE_LAYOUT_HASH` (20), `NETWORK_REQUEST_CONTROL_OF_ENTITY` (18), `IS_PED_IN_VEHICLE` (18), `CLEAR_PED_TASKS` (18), `GET_HASH_KEY` (18), `GET_GAME_TIMER` (17), `SET_PED_IN_VEHICLE_CONTEXT` (16), `CLEAR_SEQUENCE_TASK` (15), `TASK_CLEAR_LOOK_AT` (15), `VDIST2` (14), `IS_ENTITY_PLAYING_ANIM` (14), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (13), `GET_RANDOM_INT_IN_RANGE` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.7f` x29 · `-0.7f` x16 · `0.2f` x7 · `0.5f` x3 · `0.1f` x3 · `-1.5f` x2 · `0.25f` x2 · `-0.1f` x2 · `0.65f` x1 · `0.916f` x1 · `0.05f` x1 · `0.9f` x1 · `-5.5f` x1 · `1.4f` x1 · `1.5f` x1 · `1.2f` x1 · `-3.7f` x1 · `-0.05f` x1 · `0.95f` x1 · `0.15f` x1 · `491.76f` x1 · `-515.73f` x1 · `29.51f` x1 · `-1453.385f` x1

## Other strings

Literals whose consuming native was not classified:

`PROSTITUTES_SOLICIT_SCENE`, `EXIT - OTHER VEHICLE DEAD`, `EXIT - OTHER ped INJURED`, `PROSTITUTES_BJ_SPEECH_SCENE`, `EXIT - OTHER OUT OF THE VEHICLE`, `PROS_CAM_TOG`, `PROS_CAM_OC`, `PROSTITUTES_SEX_SCENE`, `windscreen`, `PROS_ACCEPT`, `PROS_NO_MONEY`, `PROSTITUTES_BJ_SCENE`, `DEFAULT_SCRIPTED_CAMERA`, `PROS_DOLLAR`, `pbproau`, `PROSTITUTE_GROUP`, `LAYOUT_STD_ISSI3`, `fagaloa`, `PROS_RESPONSE`, `UPRO N/A`, `PROSTITUTES_DRIVE_SCENE`, `PROSTITUTES_PARKED_SCENE`, `feltzer3`, `PIM_HHIDCR`, `prostitute couldn't get into the car`, `PROS_CAR`, `taxi`, `Moving to PROSTITUTE_INIT_INIT`, `Prostitutes`, `prostitute SCRIPT SHOULD EXIT - PLAYER ON MISSION`

---

Source: `decompiled_scripts/pb_prostitute.c`
