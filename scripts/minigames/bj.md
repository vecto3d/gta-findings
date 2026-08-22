# bj.c

Minigames script. 8 anim dicts; 6 models; 10 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 26,036 |
| Functions | 554 (103 unique, 451 shared) |
| Unique lines | 6,878 (26.4% of file) |

## Assets

**Animation dictionaries** (8) - `skydive@freefall`, `skydive@parachute@chute`, `skydive@parachute@`, `veh@helicopter@rps@base`, `amb@world_human_hiker_standing@male@idle_a`, `amb@world_human_muscle_flex@arms_at_side@base`, `oddjobs@basejump@`, `skydive@base`

**Animations** (12) - `oddjobs@basejump@`, `Heli_door_loop`, `Heli_jump`, `ped_a_intro`, `ped_a_loop`, `ped_a_exit`, `amb@world_human_hiker_standing@male@idle_a`, `idle_a`, `amb@world_human_muscle_flex@arms_at_side@base`, `base`, `playidles_cold`, `blow_hands`

**Models and props** (6) - `s_m_y_pilot_01`, `a_m_y_beach_01`, `trflat`, `a_m_y_hippy_01`, `a_m_m_genfat_02`, `s_m_m_trucker_01`

**Audio banks** (2) - `generic_failed`, `OFFMISSION_WASTED`

**Sounds** (22) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `WastedSounds`, `BASEJUMPS_PREP_FOR_JUMP_ON_FOOT`, `BASEJUMPS_PREP_FOR_JUMP_MOTO`, `BASEJUMPS_SOUNDS`, `ScreenFlash`, `NO`, `DEATH_SCENE`, `LEADERBOARD_SCENE`, `HUD_MINI_GAME_SOUNDSET`, `BASEJUMPS_OPEN_PARACHUTE`, `Helicopter_Wind_Idle`, `Helicopter_Wind`, `MissionFailedSounds`, `YES`, `Bed`, `TextHit`, `BASE_JUMP_PASSED`, `HUD_AWARDS`, `CHECKPOINT_NORMAL`, `CHECKPOINT_MISSED`, `BASEJUMPS_SKYDIVE`

**Scaleform movies** (10) - `CLEAR_ALL_SLOTS`, `TRANSITION_UP`, `SET_DATA_SLOT`, `SHOW_CENTERED_MP_MESSAGE_LARGE`, `STRING`, `SET_CLEAR_SPACE`, `SET_DATA_SLOT_EMPTY`, `DRAW_INSTRUCTIONAL_BUTTONS`, `SET_BACKGROUND_COLOUR`, `instructional_buttons`

**Texture dicts** (2) - `basejumping`, `Arrow_Pointer`

**Text labels** (8) - `OJBJAUD`, `NULL`, `EX3MERC1`, `MICHAEL`, `TREVOR`, `FRANKLIN`, `EXT1HELIPILOT`, `BJUMP`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (215), `DOES_ENTITY_EXIST` (76), `IS_ENTITY_DEAD` (54), `IS_PED_INJURED` (45), `DISABLE_CONTROL_ACTION` (39), `SET_BIT` (34), `GET_ENTITY_COORDS` (30), `PLAYER_ID` (28), `SET_PED_COMPONENT_VARIATION` (26), `CLEAR_HELP` (20), `SET_ENTITY_COORDS` (20), `TO_FLOAT` (18), `DELETE_VEHICLE` (17), `GET_PED_PARACHUTE_STATE` (16), `SET_ENTITY_HEADING` (15), `IS_SCREEN_FADED_OUT` (14), `CLEAR_PED_TASKS` (14), `DOES_BLIP_EXIST` (14), `IS_PED_IN_ANY_VEHICLE` (13), `FREEZE_ENTITY_POSITION` (13), `IS_CONTROL_PRESSED` (13), `CLEAR_BIT` (13), `CEIL` (13), `WAIT` (12), `BEGIN_SCALEFORM_MOVIE_METHOD` (12), `IS_SCREEN_FADING_OUT` (11), `RENDER_SCRIPT_CAMS` (11), `REQUEST_ANIM_DICT` (11), `GET_PED_IN_VEHICLE_SEAT` (11), `REMOVE_BLIP` (11)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x16 · `1.2f` x12 · `-97.4239f` x6 · `0.7f` x5 · `-832.271f` x4 · `-1525.112f` x4 · `-1187.833f` x4 · `-1876.646f` x4 · `1.5f` x4 · `-129.031f` x3 · `-726.381f` x3 · `-38.185f` x3 · `-465.801f` x3 · `1.12046f` x3 · `-0.317773f` x3 · `1.3385f` x3 · `0.2f` x3 · `0.006f` x3 · `0.25f` x3 · `-1.4f` x3 · `1.1f` x2 · `0.001f` x2 · `0.04f` x2 · `-74.9632f` x1

## Other strings

Literals whose consuming native was not classified:

`BJ_CONTINUE`, `BJ_RETRY`, `BJ_BLIP_TGT`, `HUD_INPUT68`, `BJ_BLIP_CHK`, `BJ_VEHHELP`, `OJBJ_START`, `OJBJ_JUMPED`, `OJBJ_LANDED`, `OJBJ_STOP`, `HUD_INPUT53`, `FMMC_COR_SCLB5`, `FMMC_COR_SCLB6`, `SCLB_C_RANK`, `blazer`, `freight`, `DisableFlightMusic`, `Chassis`, `SCLB_PROFILE`, `BJ_SC_ALLG_RWD`, `BJUMP_01`, `BJUMP_02`, `BJUMP_03`, `BJUMP_04`, `BJUMP_05`, `BJUMP_06`, `BJUMP_07`, `BJUMP_08`, `BJUMP_09`, `BJUMP_10`

---

Source: `decompiled_scripts/bj.c`
