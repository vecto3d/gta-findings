# finale_heist_prepd.c

Heists script. 2 anim dicts; 13 models.

| | |
|---|---|
| Category | Heists |
| Total lines | 114,472 |
| Functions | 780 (38 unique, 742 shared) |
| Unique lines | 2,733 (2.4% of file) |

## Assets

**Animation dictionaries** (2) - `missbigscoreprep`, `missbigscoreprepd`

**Animations** (4) - `missbigscoreprepd`, `pull_level_michael`, `missbigscoreprep`, `idle_a`

**Models and props** (13) - `s_m_y_construct_01`, `freightcar`, `freightcont2`, `freight`, `skylift`, `freightcont1`, `freightgrain`, `tankercar`, `prop_ld_rail_01`, `prop_ld_rail_02`, `freighttrailer`, `phantom`, `p_rail_controller_s`

**Audio banks** (2) - `BIG_SCORE_PREP_D`, `BIG_SCORE_PREP_D_01`

**Sounds** (9) - `BS_P_D_STEALTH`, `BS_P_D_SWITCH_TRACKS`, `TRAIN_PICK_UP_IMPACT_MASTER`, `BS_P_D_FLY_CHOPPER`, `BS_P_D_TRAIN_ARRIVES`, `ELECTRO_MAGNET_DRONE_MASTER`, `TRAIN_PICK_UP_MASTER`, `TRAIN_SWITCH_TRACKS_MASTER`, `HELI_TURNING_MASTER`

**Text labels** (23) - `TREVOR`, `MICHAEL`, `BSPRP`, `FAILGUARD`, `SOL1AUD`, `FRANKLIN`, `FAILHELI`, `GOTOBOX`, `GETENGINE`, `MAGNETON`, `MAGNETOFF`, `TAKEFLATBED`, `NULL`, `FAILTRAIN`, `NOFLIP`, `TAKEENGINE2`, `TAKEENGINE`, `GETCARRIAGE`, `CONSTRUCTION1`, `CONSTRUCTION2`, `FLIPSWITCH`, `KILLGUARDS`, `BSPREP`

**Scenarios** (1) - `WORLD_HUMAN_SMOKING`

**Vehicle recordings** (2) - `BsPrepHeli`, `BSPrepheli`

**Relationship groups** (2) - `RAILWAY`, `player`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (76), `IS_ENTITY_DEAD` (47), `HAS_MODEL_LOADED` (37), `REQUEST_MODEL` (37), `GET_TRAIN_CARRIAGE` (28), `GET_ENTITY_ROTATION` (23), `FREEZE_ENTITY_POSITION` (22), `DOES_ENTITY_EXIST` (21), `WAIT` (17), `GET_ENTITY_COORDS` (17), `GET_ENTITY_HEADING` (16), `PLAYER_ID` (15), `IS_PED_INJURED` (15), `IS_ENTITY_AT_ENTITY` (14), `CREATE_VEHICLE` (14), `TRIGGER_MUSIC_EVENT` (13), `REPLAY_RECORD_BACK_FOR_TIME` (13), `CLEAR_PRINTS` (11), `CLEAR_HELP` (11), `IS_AUDIO_SCENE_ACTIVE` (11), `SET_TRAIN_CRUISE_SPEED` (11), `SET_TRAIN_SPEED` (11), `SETTIMERA` (11), `IS_HELP_MESSAGE_BEING_DISPLAYED` (11), `PLAY_SOUND_FROM_ENTITY` (11), `SET_ENTITY_HEADING` (11), `SET_ENTITY_COORDS_NO_OFFSET` (11), `REMOVE_BLIP` (10), `DOES_BLIP_EXIST` (9), `SET_ENTITY_COORDS` (9)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`6.1f` x20 · `2644.029f` x7 · `2974.48f` x7 · `39.5441f` x7 · `0.1f` x6 · `-1.2f` x4 · `2628.908f` x3 · `2947.625f` x3 · `0.5f` x3 · `2631.992f` x3 · `2934.091f` x3 · `43.69f` x3 · `2624.928f` x3 · `2947.425f` x3 · `39.31967f` x3 · `2628.115f` x3 · `2924.567f` x3 · `39.4265f` x3 · `154.8777f` x3 · `2595.124f` x2 · `2807.558f` x2 · `30.7274f` x2 · `2649.778f` x2 · `2988.829f` x2

## Other strings

Literals whose consuming native was not classified:

`freightcar`, `BSD_GETINCHOP`, `BSPD_TRUCKDEAD`, `DEFAULT_SCRIPTED_CAMERA`, `freight`, `freightcont1`, `freightcont2`, `freightgrain`, `tankercar`, `FHPRD_RESTART_2`, `skylift`, `FHPRD_FAIL`, `BSPD_CREWDEAD`, `BSPRP_TAKET`, `missbigscoreprepd`, `FHPRD_STOP`, `BSPRP_FLATGO`, `MotionState_Run`, `player`, `FHPRD_SIDINGS`, `M_SDTRCK`, `SOL1_COPSIN2`, `BSPD_ABANDON`, `CMN_TDIED`, `CMN_MDIED`, `STAGE_WAIT_FOR_TRAIN`, `BSPRP_TAKEM`, `control_panel_loop_panel`, `STAGE_FLY_AWAY_WITH_CARRIAGE`, `BSPRP_MUNHK`

---

Source: `decompiled_scripts/finale_heist_prepd.c`
