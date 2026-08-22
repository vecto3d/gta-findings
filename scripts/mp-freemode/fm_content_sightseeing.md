# fm_content_sightseeing.c

MP freemode script. 3 anim dicts; 1 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 486,861 |
| Functions | 9,597 (139 unique, 9,458 shared) |
| Unique lines | 7,889 (1.6% of file) |

## Assets

**Animation dictionaries** (3) - `anim@scripted@freemode@ufo_invasion@ufo_float@heeled@`, `anim@scripted@freemode@ufo_invasion@ufo_float@male@`, `get_up@standard`

**Animations** (2) - `get_up@standard`, `front`

**Models and props** (1) - `imp_prop_ship_01a`

**Sounds** (1) - `06`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`VDIST` (15), `SET_PED_COMPONENT_VARIATION` (11), `SET_BIT` (10), `GET_RANDOM_INT_IN_RANGE` (7), `DOES_ENTITY_EXIST` (5), `FREEZE_ENTITY_POSITION` (4), `TASK_PLAY_ANIM` (4), `SET_GLOBAL_RADIO_SIGNAL_LEVEL` (4), `PARTICIPANT_ID_TO_INT` (3), `NETWORK_EARN_SIGHTSEEING_REWARD` (3), `CLEAR_BIT` (3), `FORCE_LIGHTNING_FLASH` (3), `GET_GAME_TIMER` (3), `IS_ENTITY_PLAYING_ANIM` (3), `NETWORK_IS_GAME_IN_PROGRESS` (2), `NETWORK_HASH_FROM_PLAYER_HANDLE` (2), `GET_PED_PARACHUTE_STATE` (2), `IS_ENTITY_ATTACHED` (2), `IS_THIS_MODEL_A_HELI` (2), `NETWORK_IS_PARTICIPANT_ACTIVE` (2), `SET_LOCAL_PLAYER_AS_GHOST` (2), `NETWORK_IS_PLAYER_A_PARTICIPANT` (2), `NETWORK_GET_NUM_PARTICIPANTS` (2), `PLAYER_ID` (2), `DRAW_LIGHT_WITH_RANGE` (2), `SET_ENTITY_ANIM_CURRENT_TIME` (2), `GET_ENTITY_ANIM_CURRENT_TIME` (2), `GET_SHOP_PED_COMPONENT` (2), `IS_ENTITY_IN_AIR` (2), `GET_ENTITY_HEIGHT_ABOVE_GROUND` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`7.5f` x2 · `-417.2874f` x1 · `1153.371f` x1 · `324.8797f` x1 · `1665.834f` x1 · `-27.82096f` x1 · `195.4185f` x1 · `753.8437f` x1 · `1185.914f` x1 · `349.2628f` x1 · `741.0407f` x1 · `1189.907f` x1 · `321.3976f` x1 · `-2302.882f` x1 · `217.9447f` x1 · `166.6017f` x1 · `2500.601f` x1 · `-383.8451f` x1 · `92.9257f` x1 · `-75.08682f` x1 · `-819.0153f` x1 · `325.1753f` x1 · `44.43108f` x1 · `213.2493f` x1

## Other strings

Literals whose consuming native was not classified:

`Sight_Seeing_Sounds`, `oppressor2`, `MAX_NUM_TRANSITIONS`, `sPedLocal.sPed[iLoop].iNumTriggers`, `MAX_NUM_PED_TRIGGERS`, `CHAR_DEFAULT`, `VULKAN_LOCK_ON_RED`, `VULKAN_LOCK_ON_AMBER`, `RESS_HT_1`, `RESS_HT_2`, `RESS_HT_3`, `RE_SS_TXTA1`, `RE_SS_TXTA2`, `RE_SS_TXTA3`, `RE_SS_TXTB1`, `RE_SS_TXTB2`, `RE_SS_TXTB3`, `data.MovingDoor.MovingDoors`, `MAX_NUM_EVENT_LOCATION_BLIPS`, `data.Interior.iCount`, `MAX_NUM_MISSION_INTERIORS`, `data.MissionEntity.iCount`, `MAX_NUM_MISSION_ENTITIES`, `data.Ped.iCount`, `MAX_NUM_PEDS`, `data.Ped.Group GET_NUM_PED_GROUPS()`, `MAX_NUM_PED_GROUPS`, `data.TakePhotos.Photos.iPhotoCount`, `MAX_NUM_TAKE_PHOTOGRAPHS`, `data.Patrol.iCount`

---

Source: `decompiled_scripts/fm_content_sightseeing.c`
