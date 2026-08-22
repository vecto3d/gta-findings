# extreme1.c

SP missions script. 5 anim dicts; 3 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 57,673 |
| Functions | 750 (122 unique, 628 shared) |
| Unique lines | 4,851 (8.4% of file) |

## Assets

**Animation dictionaries** (5) - `rcm_extreme1`, `rcm_extreme1@heli`, `creatures@retriever@move`, `creatures@retriever@amb@world_dog_barking@enter`, `creatures@retriever@amb@world_dog_barking@exit`

**Animations** (19) - `rcm_extreme1`, `es_1_rcm_dom_upside_down_base`, `es_1_rcm_dom_upside_down_fidget_01`, `es_1_rcm_dom_upside_down_fidget_02`, `rcm_extreme1@heli`, `banter_after_win_player`, `banter_after_loss_player`, `banter_after_win_dom`, `banter_after_loss_dom`, `Heli_door_loop_l`, `Heli_door_loop`, `Heli_jump_l`, `Heli_jump`, `creatures@retriever@amb@world_dog_barking@enter`, `enter`, `idle_c`, `idle_a`, `creatures@retriever@amb@world_dog_barking@exit`, `exit`

**Models and props** (3) - `a_c_retriever`, `s_m_y_pilot_01`, `p_parachute_fallen_s`

**Sounds** (6) - `CHECKPOINT_NORMAL`, `HUD_MINI_GAME_SOUNDSET`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `WIND`, `EXTREME_01_SOUNDSET`

**Text labels** (8) - `EXT1AU`, `FRANKLIN`, `DOM`, `CLEAR`, `NULL`, `EXT1HELIPILOT`, `COLLIE`, `EXT1`

**Scenarios** (2) - `Observatory_Bikers`, `WORLD_VEHICLE_SALTON_DIRT_BIKE`

**Vehicle recordings** (1) - `Ext1_BikeRace`

**Vehicle mods** (3) - `fbi`, `firetruk`, `police`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (170), `GET_GAME_TIMER` (51), `GET_HUD_COLOUR` (26), `IS_PED_IN_VEHICLE` (25), `GET_ENTITY_COORDS` (25), `DOES_BLIP_EXIST` (20), `DOES_ENTITY_EXIST` (16), `SET_CHECKPOINT_RGBA` (15), `PLAYER_ID` (15), `SET_CHECKPOINT_RGBA2` (14), `GET_PED_PARACHUTE_STATE` (13), `TASK_LOOK_AT_ENTITY` (12), `REPLAY_RECORD_BACK_FOR_TIME` (11), `TRIGGER_MUSIC_EVENT` (10), `ROUND` (10), `SET_PED_INTO_VEHICLE` (10), `GET_DISTANCE_BETWEEN_COORDS` (10), `SET_PED_CONFIG_FLAG` (10), `SET_GAMEPLAY_CAM_RELATIVE_PITCH` (9), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (9), `SET_MODEL_AS_NO_LONGER_NEEDED` (9), `REQUEST_MODEL` (9), `HAS_MODEL_LOADED` (9), `WAIT` (8), `CLEAR_HELP` (8), `SET_BLIP_SCALE` (8), `SET_PLAYBACK_SPEED` (8), `REQUEST_ANIM_DICT` (8), `HAS_ANIM_DICT_LOADED` (8), `RENDER_SCRIPT_CAMS` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x6 · `0.7f` x4 · `0.25f` x4 · `-97.4239f` x4 · `0.15f` x3 · `231.5293f` x2 · `-53.85f` x2 · `0.8f` x2 · `2.4f` x2 · `1.2f` x2 · `0.001f` x2 · `0.84f` x2 · `-0.317773f` x2 · `0.9385f` x2 · `354.765f` x2 · `1.15f` x2 · `0.45f` x2 · `302.9516f` x2 · `1297.765f` x2 · `-189.9982f` x2 · `-188.8f` x1 · `1296.122f` x1 · `302.9238f` x1 · `216.9263f` x1

## Other strings

Literals whose consuming native was not classified:

`rcm_extreme1`, `Hudson`, `BLIP_CPOINT`, `EXTREME_01_INTRO`, `EXT1_19`, `EXTREME_01_RACE`, `EXTREME_01_JOURNEY`, `Dom`, `EXTREME1_STOP`, `BLIP_FRIEND`, `EXTREME_01_BIKE_RACE_DOM_GROUP`, `EXTREME1_BIKE`, `EXT1_16`, `DEFAULT_ANIMATED_CAMERA`, `CamPushInNeutral`, `EXT1_21`, `EXT1_14`, `EXT1_FIST`, `EXT1_06_KM`, `EXT1_06`, `SKY_DIVING_SHAKE`, `Chassis`, `DEFAULT_SCRIPTED_CAMERA`, `EXT1_MEETLZ`, `ES_1_RCM_CONCAT`, `EXT1_DOG`, `Franklin`, `Force cleanup [TERMINATING]`, `SF_RA`, `EXTREME1_FAIL`

---

Source: `decompiled_scripts/extreme1.c`
