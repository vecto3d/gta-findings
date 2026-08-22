# re_accident.c

Random events script. 1 anim dicts; 7 models; 3 particle effects.

| | |
|---|---|
| Category | Random events |
| Total lines | 8,516 |
| Functions | 219 (22 unique, 197 shared) |
| Unique lines | 1,679 (19.7% of file) |

## Assets

**Animation dictionaries** (1) - `re@construction`

**Animations** (4) - `re@construction`, `idle_panic`, `idle_c`, `Out_Of_Breath`

**Models and props** (7) - `prop_ld_pipe_single_01`, `s_m_m_dockwork_01`, `p_amb_phone_01`, `prop_pipe_stack_01`, `prop_generator_01a`, `utillitruck2`, `bulldozer`

**Audio banks** (1) - `CONSTRUCTION_ACCIDENT_1`

**Sounds** (7) - `CONSTRUCTION_ACCIDENT_1_SOUNDS`, `WEAKEN`, `WIND`, `CABLE_SNAPS`, `PIPES_LAND`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Speech contexts** (1) - `S_M_Y_GENERICWORKER_01_WHITE_01`

**Particle effects** (3) - `scr_sparking_generator`, `scr_reconstruct_pipefall_debris`, `scr_reconstruct_pipe_impact`

**Text labels** (3) - `CONACAU`, `NULL`, `DEFAULT`

**Scenarios** (1) - `WORLD_HUMAN_PICNIC`

**Vehicle mods** (1) - `utillitruck2`

## Native vocabulary

Most-called natives inside the code unique to this script:

`GET_GAME_TIMER` (46), `PLAYER_PED_ID` (36), `DOES_BLIP_EXIST` (32), `IS_PED_INJURED` (27), `FREEZE_ENTITY_POSITION` (26), `IS_ENTITY_DEAD` (23), `DOES_ENTITY_EXIST` (20), `REMOVE_BLIP` (17), `WAIT` (14), `IS_PED_IN_ANY_VEHICLE` (12), `CREATE_OBJECT_NO_OFFSET` (11), `IS_ENTITY_AT_COORD` (10), `GET_PLAYERS_LAST_VEHICLE` (10), `SHAKE_CAM` (10), `SET_ENTITY_ROTATION` (10), `IS_VEHICLE_DRIVEABLE` (8), `CREATE_CAM_WITH_PARAMS` (8), `SET_ENTITY_PROOFS` (7), `BREAK_OBJECT_FRAGMENT_CHILD` (7), `SET_VEHICLE_EXTRA` (7), `TRIGGER_MUSIC_EVENT` (6), `RENDER_SCRIPT_CAMS` (6), `SET_PLAYER_CONTROL` (6), `PLAYER_ID` (6), `APPLY_FORCE_TO_ENTITY` (6), `DOES_CAM_EXIST` (5), `DESTROY_CAM` (5), `EXPLODE_VEHICLE` (5), `GET_BLIP_ALPHA` (5), `SET_BLIP_ALPHA` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.3f` x6 · `0.4f` x3 · `0.5f` x3 · `0.25f` x3 · `-460.3019f` x3 · `-870.3607f` x3 · `21.89325f` x3 · `-508.4859f` x3 · `-981.1199f` x3 · `27.32087f` x3 · `36.5625f` x3 · `1.5f` x3 · `-477.2774f` x3 · `-990.0638f` x3 · `23.5497f` x3 · `-473.1686f` x2 · `-984.6405f` x2 · `22.487f` x2 · `-539.4481f` x2 · `-962.3162f` x2 · `22.4918f` x2 · `-476.3904f` x2 · `-986.836f` x2 · `22.5569f` x2

## Other strings

Literals whose consuming native was not classified:

`HAND_SHAKE`, `DEFAULT_SCRIPTED_CAMERA`, `empty`, `bulldozer`, `RE14A_FAIL`, `CONAC_DIE`, `RE_CA`, `Gun_Nuzzle`, `RECONACWorker`, `CONAC_CHAT`, `CONAC_HELP`, `CONAC_HELP2`, `CONAC_HELP3`, `CONAC_HURRY`, `CONAC_FREE`, `CONAC_BOOM`, `CONAC_AAAH`, `RE14A_SAFE`, `CONAC_THANK`, `RE14A_START`, `CONAC_SCREAM`, `CamPushInNeutral`, `RE14A_PIPES`, `utillitruck2`

---

Source: `decompiled_scripts/re_accident.c`
