# hao1.c

SP strangers and freaks script. 2 anim dicts; 8 models; 4 scaleforms.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 60,228 |
| Functions | 778 (119 unique, 659 shared) |
| Unique lines | 6,043 (10.0% of file) |

## Assets

**Animation dictionaries** (2) - `special_ped@hao@base`, `random@street_race`

**Animations** (7) - `special_ped@hao@base`, `hao_base`, `grid_girl_race_start`, `grid_girl_a`, `grid_girl_b`, `hao_leadin`, `hao_base_penumbra`

**Models and props** (8) - `a_m_y_jetski_01`, `a_m_m_socenlat_01`, `a_m_y_hipster_02`, `a_m_y_eastsa_01`, `a_m_y_motox_02`, `a_m_y_motox_01`, `a_f_y_genhot_01`, `prop_npc_phone`

**Audio banks** (1) - `HUD_321_GO`

**Sounds** (10) - `STREET_RACE_DURING_RACE`, `STREET_RACE_OUTRO`, `DISTANT_RACERS`, `ROAD_RACE_SOUNDSET`, `CHECKPOINT_NORMAL`, `HUD_MINI_GAME_SOUNDSET`, `SEA_RACE_DURING_RACE`, `UNDER_WATER_COME_UP`, `Short_Transition_Out`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Scaleform movies** (4) - `MIDSIZED_MESSAGE`, `SHOW_SHARD_MIDSIZED_MESSAGE`, `BM_LAP_STR`, `SHARD_ANIM_OUT`

**Text labels** (9) - `HAO1AU`, `STR1AUD`, `FRANKLIN`, `NULL`, `BM_LAP`, `GIRL1`, `GIRL2`, `HAO1`, `HAO`

**Scenarios** (1) - `DRIVE`

**Vehicle mods** (15) - `airbus`, `benson`, `biff`, `coach`, `firetruk`, `flatbed`, `mule`, `mule2`, `packer`, `pounder`, `rubble`, `tiptruck`, `tiptruck2`, `tourbus`, `trash`

**Stats** (3) - `sp0_special_ability`, `sp1_special_ability`, `sp2_special_ability`

**Hashed names** (4) - `MONSTER`, `MARSHALL`, `huntley`, `DUBSTA3`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (118), `GET_GAME_TIMER` (68), `DOES_ENTITY_EXIST` (28), `GET_ENTITY_COORDS` (24), `PLAYER_ID` (21), `SET_VEHICLE_MOD` (21), `SET_VEHICLE_MODEL_IS_SUPPRESSED` (18), `IS_VEHICLE_STUCK_TIMER_UP` (16), `CREATE_CAMERA_WITH_PARAMS` (16), `IS_PED_IN_VEHICLE` (14), `SET_BIT` (14), `DOES_CAM_EXIST` (14), `GET_DISTANCE_BETWEEN_COORDS` (13), `GET_NUM_VEHICLE_MODS` (13), `IS_PLAYER_PLAYING` (12), `DESTROY_CAM` (12), `SHAKE_CAM` (12), `WAIT` (11), `GET_ENTITY_MODEL` (11), `SET_ENTITY_HEADING` (11), `IS_ENTITY_DEAD` (10), `SET_ENTITY_COORDS` (10), `OPEN_SEQUENCE_TASK` (9), `CLOSE_SEQUENCE_TASK` (9), `TASK_PERFORM_SEQUENCE` (9), `WAYPOINT_RECORDING_GET_COORD` (9), `SET_PED_INTO_VEHICLE` (9), `SET_CAM_ACTIVE_WITH_INTERP` (9), `SET_PED_CONFIG_FLAG` (9), `PRELOAD_VEHICLE_MOD` (9)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x14 · `0.1f` x7 · `0.3f` x5 · `1.2f` x4 · `9.5f` x4 · `2.3f` x3 · `-29.86f` x2 · `-1833.06f` x2 · `25.37f` x2 · `234.16f` x2 · `25.3742f` x2 · `380.1007f` x1 · `-3498.078f` x1 · `-29.3627f` x1 · `0.33f` x1 · `0.25f` x1 · `0.7f` x1 · `2.4f` x1 · `-168.4269f` x1 · `-1582.631f` x1 · `33.9665f` x1 · `1.5f` x1 · `0.8f` x1 · `0.57f` x1

## Other strings

Literals whose consuming native was not classified:

`HAND_SHAKE`, `RACES_RHELP`, `bati`, `FRANKLIN_NORMAL`, `TIMER_CHALLTIME`, `DEFAULT_SCRIPTED_CAMERA`, `sentinel`, `buffalo`, `banshee`, `ruffian`, `prairie`, `BIKE_BACK`, `CAR_BACK`, `SEA_BACK`, `TIM_POSIT`, `TIM_CHECKPOIN`, `TIM_DISTANCE`, `FMMC_LENGTHM`, `TIMER_TIME_RCE`, `SEA_RACE_DURING_RACE_NPC_GENERAL`, `STREET_RACE_NPC_GENERAL`, `BLIP_CPOINT`, `Race start`, `STR1_GIRL2`, `INTRO_STREAM`, `ROAD_RACE_SOUNDSET`, `ROAD_VIBRATION_SHAKE`, `airtug`, `feltzer2`, `dominator`

---

Source: `decompiled_scripts/hao1.c`
