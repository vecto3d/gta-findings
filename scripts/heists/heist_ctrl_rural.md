# heist_ctrl_rural.c

Heists script. 1 anim dicts; 1 models; 1 particle effects.

| | |
|---|---|
| Category | Heists |
| Total lines | 16,389 |
| Functions | 316 (7 unique, 309 shared) |
| Unique lines | 863 (5.3% of file) |

## Assets

**Animation dictionaries** (1) - `MISSHEISTPALETOSCORE1LEADINOUT`

**Animations** (4) - `MISSHEISTPALETOSCORE1LEADINOUT`, `TRV_PUKING_LEADOUT`, `TRV_UPPERBODY_LeadOut_FPS`, `TRV_UPPERBODY_LEADOUT`

**Models and props** (1) - `player_two`

**Audio banks** (1) - `Taxi_vomit`

**Sounds** (1) - `PS_1_TREVOR_PUKING`

**Particle effects** (1) - `SCR_TREV_PUKE`

**Text labels** (15) - `LESTER`, `TREVOR`, `MICHAEL`, `NULL`, `BOARD3`, `RHFAUD`, `CRWAUD`, `RHP1`, `RHP8`, `RHFP11`, `RHP10B`, `RHP5`, `RHP6`, `RHP7`, `RBS1AUD`

**Scripts launched** (1) - `rural_bank_heist`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DISABLE_CONTROL_ACTION` (30), `SET_BIT` (22), `PLAYER_PED_ID` (22), `SET_CUTSCENE_PED_COMPONENT_VARIATION` (21), `DOES_ENTITY_EXIST` (18), `CLEAR_BIT` (15), `IS_ENTITY_DEAD` (13), `REGISTER_ENTITY_FOR_CUTSCENE` (9), `GET_ENTITY_INDEX_OF_REGISTERED_ENTITY` (8), `PLAYER_ID` (7), `SET_ENTITY_VISIBLE` (6), `SET_PED_CONFIG_FLAG` (6), `REMOVE_CUTSCENE` (5), `GET_PED_INDEX_FROM_ENTITY_INDEX` (5), `GET_GAME_TIMER` (5), `CAN_SET_EXIT_STATE_FOR_REGISTERED_ENTITY` (4), `DELETE_PED` (4), `START_PARTICLE_FX_LOOPED_ON_PED_BONE` (4), `CAN_REQUEST_ASSETS_FOR_CUTSCENE_ENTITY` (3), `SET_CUTSCENE_PED_PROP_VARIATION` (3), `SET_PED_PATHS_IN_AREA` (3), `SET_MAX_WANTED_LEVEL` (3), `SET_ENTITY_AS_MISSION_ENTITY` (3), `SET_PLAYER_CONTROL` (3), `IS_ENTITY_PLAYING_ANIM` (3), `GET_FOLLOW_PED_CAM_VIEW_MODE` (2), `IS_CUTSCENE_PLAYING` (2), `WAIT` (2), `DOES_CAM_EXIST` (2), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x3 · `-1.5f` x2 · `1398.167f` x1 · `3605.438f` x1 · `39.6443f` x1 · `-8.2882f` x1 · `126.8884f` x1 · `1398.198f` x1 · `3605.6f` x1 · `37.9419f` x1 · `194.2789f` x1 · `1397.884f` x1 · `3594.627f` x1 · `33.9271f` x1 · `1396.911f` x1 · `3603.942f` x1 · `38.925f` x1 · `1394.511f` x1 · `3607.037f` x1 · `36.94191f` x1 · `7.5f` x1 · `7.75f` x1 · `6.75f` x1

## Other strings

Literals whose consuming native was not classified:

`player_two`, `player_zero`, `Trevor`, `RBHS_MCS_3`, `Michael`, `RBHS_MSC_3_P3`, `HEIST_PALETO`, `CRW_GM`, `CRW_NR`, `CRW_DJ`, `CRW_PM`, `CRM_PM`, `CRM_CH`, `H_TD_TOWN`, `H_TD_ALAR`, `H_TD_COPS`, `H_TD_CREW`, `H_TD_MILI`, `RBS1_VOMIT`

---

Source: `decompiled_scripts/heist_ctrl_rural.c`
