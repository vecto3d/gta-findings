# me_tracey1.c

Races script. 1 anim dicts; 1 models.

| | |
|---|---|
| Category | Races |
| Total lines | 52,046 |
| Functions | 598 (89 unique, 509 shared) |
| Unique lines | 4,625 (8.9% of file) |

## Assets

**Animation dictionaries** (1) - `missmichael_event@tracy`

**Animations** (6) - `react_intro`, `react_loop`, `missmichael_event@tracy`, `base`, `nervous_loop`, `breakout`

**Models and props** (1) - `a_m_o_acult_01`

**Sounds** (3) - `M_E_TRACEY_FOCUS_CAM`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Text labels** (29) - `MET1AUD`, `MET1KSTKRED`, `MET1KSTKBLU`, `MET1ABANDON`, `TRACEY`, `DEFAULT`, `MET1ESCAPE`, `NULL`, `NONE`, `MET1TRASCARE`, `MET1TCAR`, `MET1LBTRAC`, `EXTRASUNNY`, `MET1LBSTALK`, `MET1CPSTALK`, `MET1TOOLATE`, `MET1`, `MICHAEL`, `MET1INITDRV`, `MET1WAIT`, `MET1WANT`, `MET1CHASE`, `MET1GETBKT`, `MET1DLT`, `MET1HOME`, `MET1HOTEL`, `MET1TRAKILL`, `MET1TWRECK`, `MET1STUCK`

**Relationship groups** (1) - `FRIENDLIES`

**Vehicle mods** (16) - `issi2`, `ISSI2`, `bus`, `coach`, `mixer`, `mixer2`, `rubble`, `tiptruck2`, `tiptruck`, `scrap`, `biff`, `packer`, `phantom`, `benson`, `trash`, `pounder`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (141), `GET_GAME_TIMER` (122), `IS_PED_IN_VEHICLE` (48), `GET_RANDOM_INT_IN_RANGE` (18), `SET_VEHICLE_MODEL_IS_SUPPRESSED` (18), `CLEAR_PRINTS` (17), `GET_ENTITY_COORDS` (15), `IS_PED_IN_ANY_VEHICLE` (13), `PLAYER_ID` (12), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (11), `DOES_BLIP_EXIST` (11), `GET_PLAYER_WANTED_LEVEL` (10), `SET_PED_COMPONENT_VARIATION` (10), `CLEAR_PED_TASKS` (10), `WAIT` (10), `OPEN_SEQUENCE_TASK` (9), `CLOSE_SEQUENCE_TASK` (9), `CLEAR_AREA_OF_VEHICLES` (9), `TASK_PERFORM_SEQUENCE` (8), `GET_PROFILE_SETTING` (8), `SET_PED_CONFIG_FLAG` (8), `REQUEST_ANIM_DICT` (7), `TASK_PLAY_ANIM` (7), `SET_BLIP_NAME_FROM_TEXT_FILE` (7), `REQUEST_MODEL` (7), `SET_MODEL_AS_NO_LONGER_NEEDED` (7), `IS_ENTITY_IN_ANGLED_AREA` (6), `CLEAR_SEQUENCE_TASK` (6), `TASK_LOOK_AT_COORD` (6), `SET_ENTITY_COORDS` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x5 · `181.2331f` x5 · `-33.9939f` x5 · `67.2522f` x5 · `0.25f` x3 · `99.6208f` x3 · `-21.0027f` x3 · `67.0114f` x3 · `0.75f` x2 · `48.4f` x2 · `2.5f` x2 · `255.3f` x2 · `3.5f` x2 · `4.5f` x2 · `1.5f` x1 · `3.2f` x1 · `-3.2f` x1 · `-0.5f` x1 · `-1.5f` x1 · `-820.1358f` x1 · `176.9053f` x1 · `70.6086f` x1 · `-820.2315f` x1 · `176.7027f` x1

## Other strings

Literals whose consuming native was not classified:

`MET1_MESS`, `Stalker`, `MET1_TNOGOF`, `MET1_GETHIM`, `MET1_BASH`, `MET1_STOP`, `MET1_LOCX`, `Stalker appears (CP2)`, `DEFAULT_SCRIPTED_CAMERA`, `player`, `MET1_THERUN`, `MET1_STWR`, `BLIP_FRIEND`, `BLIP_ENEMY`, `MET1_TRCOPS`, `MET1_TENDb`, `M_E_TRACEY_STALKERS_CAR_GROUP`, `MET1_NOTGO`, `MET1_FAIL`, `MET1_ATHOME`, `CamPushInNeutral`, `MET1_SEES`, `Met Tracey (CP2)`, `MET1_GETIN`, `MET1_PACE`, `rcmme_tracey1`, `tailgater`, `M_DD`, `MET1_LOC1`, `MET1_CHAT1`

---

Source: `decompiled_scripts/me_tracey1.c`
