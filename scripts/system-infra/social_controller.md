# social_controller.c

System and infrastructure script.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 53,407 |
| Functions | 587 (105 unique, 482 shared) |
| Unique lines | 8,321 (15.6% of file) |

## Assets

**Sounds** (2) - `OTHER_TEXT`, `HUD_AWARDS`

**Text labels** (15) - `CHAR_SOCIAL_CLUB`, `NULL`, `TEST`, `LESTER`, `CREWLEFT_TA`, `SC_PLAY_REM`, `COUPON`, `CELL_FEED_F100PC_COMP`, `CELL_FEED_BEAT_MIS_SCORE`, `CREWKICK_TA`, `CREWKICK_TI`, `CREWPROM`, `CREWDEMO`, `CELL_FEED_DRIVEN_ALL_VEH`, `CELL_FEED_RNDEV_COMP`

**Stats** (9) - `mp0_awd_50_vehicles_blownup`, `mp0_awd_vehicles_jackedr`, `mp0_awd_fmtime5starwanted`, `mp0_awd_fmmostspinsinonevehicle`, `mp0_awd_fmdrivewithoutcrash`, `mp0_awd_fmmostflipsinonevehicle`, `chop_app_used`, `car_mod_app_used`, `mp0_awd_fmfurthestwheelie`

**Scripts launched** (8) - `tuneables_processing`, `freemode`, `creator`, `fm_race_creator`, `fm_deathmatch_creator`, `fm_lts_creator`, `fm_capture_creator`, `fm_survival_creator`

**Hashed names** (75) - `uid`, `carModel`, `playerSlot`, `playerRank`, `playerGangR`, `playerGangG`, `playerGangB`, `carColour1`, `carColour2`, `carPlateBack`, `windowTint`, `bulletProofTyres`, `carEngine`, `carBrakes`, `carExhaust`, `carWheel`, `carHorn1`, `carHorn2`, `carHorn3`, `carHorn4`, `carHorn5`, `carHorn6`, `carHorn7`, `carHorn8`, `carHorn9`, `tyreSmoke`, `tyreSmokeColourRed`, `tyreSmokeColourGreen`, `tyreSmokeColourBlue`, `carHorn`, `carArmour`, `carTurbo`, `carSuspension`, `carXenonLights`, `carWheelType`, `carUnlocked`, `carColour1Unlocked`, `carColour2Unlocked`, `tyreSmokeColourEnabled`, `carEngineCount`, `carBrakesCount`, `carExhaustCount`, `carWheelCount`, `carHornCount`, `carArmourCount`, `carSuspensionCount`, `carColoursUnlocked0`, `carColoursUnlocked1`, `carColoursUnlocked2`, `carColoursUnlocked3`, `carColoursUnlocked4`, `carColoursUnlocked5`, `carPriceModifier`, `carType`, `playerGang`, `unlockBitset1`, `unlockBitset2`, `orderCount_sp0`, `orderCount_sp1`, `orderCount_sp2` ...

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (160), `GET_HASH_KEY` (101), `NETWORK_IS_GAME_IN_PROGRESS` (64), `APP_SET_BLOCK` (50), `APP_CLOSE_BLOCK` (50), `PLAYER_ID` (42), `APP_SET_APP` (29), `APP_CLOSE_APP` (29), `PRESENCE_EVENT_UPDATESTAT_INT` (24), `SC_INBOX_SET_MESSAGE_AS_READ_AT_INDEX` (21), `BEGIN_TEXT_COMMAND_THEFEED_POST` (19), `GET_GAME_TIMER` (14), `GET_PROFILE_SETTING` (14), `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME` (13), `SETTIMERA` (12), `IS_STRING_NULL_OR_EMPTY` (12), `END_TEXT_COMMAND_THEFEED_POST_TICKER` (11), `END_TEXT_COMMAND_THEFEED_POST_MESSAGETEXT` (11), `DATADICT_GET_INT` (10), `CLEAR_BIT` (10), `SC_INBOX_MESSAGE_GET_DATA_STRING` (9), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (9), `GET_FILENAME_FOR_AUDIO_CONVERSATION` (8), `GET_PLAYER_NAME` (8), `SET_COLOUR_OF_NEXT_TEXT_COMPONENT` (7), `ARE_STRINGS_EQUAL` (7), `GET_NUM_VEHICLE_MODS` (7), `GET_NETWORK_TIME` (6), `SETTIMERB` (5), `APP_GET_INT` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`660.3092f` x2 · `4977.608f` x2 · `1222.024f` x2 · `3.25f` x1

## Other strings

Literals whose consuming native was not classified:

`car`, `carType`, `carUnlocked`, `appdata`, `special`, `vehicle`, `multiplayer`, `<C>`, `~HUD_COLOUR_SOCIAL_CLUB~`, `...`, `</C>`, `carColour1`, `carColour1Unlocked`, `SPPlate`, `MPPlate`, `msg`, `dog`, `saveData`, `carModel`, `buffalo2`, `carEngineCount`, `carBrakesCount`, `carExhaustCount`, `carWheelCount`, `carHornCount`, `carArmourCount`, `carSuspensionCount`, `carHorn1`, `carHorn2`

---

Source: `decompiled_scripts/social_controller.c`
