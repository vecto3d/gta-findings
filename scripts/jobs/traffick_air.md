# traffick_air.c

Jobs script. 3 anim dicts; 12 models; 8 scaleforms; 7 particle effects.

| | |
|---|---|
| Category | Jobs |
| Total lines | 22,338 |
| Functions | 400 (142 unique, 258 shared) |
| Unique lines | 9,414 (42.1% of file) |

## Assets

**Animation dictionaries** (3) - `oddjobs@arms_traffic@`, `p_cargo_chute_s`, `oddjobs@towingcome_here`

**Animations** (6) - `oddjobs@towingcome_here`, `come_here_idle_a`, `BOMB_TAIL_OPEN_UP`, `oddjobs@arms_traffic@`, `p_cargo_chute_s_deploy`, `p_cargo_chute_s`

**Models and props** (12) - `prop_gazebo_01`, `a_m_y_genstreet_01`, `prop_drop_armscrate_01b`, `p_cargo_chute_s`, `prop_ld_bomb_anim`, `prop_box_wood01a`, `prop_ld_bomb_01`, `g_m_m_mexboss_01`, `g_m_y_salvagoon_03`, `a_m_m_hillbilly_01`, `prop_cratepile_07a`, `prop_sacktruck_02a`

**Audio banks** (3) - `SCRIPT\DRUG_TRAFFIC_AIR`, `SCRIPT\TARGET_PRACTICE`, `SCRIPT\DRUG_TRAFFIC_AIR_PANIC`

**Sounds** (11) - `SIREN_SCENE`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `BAY_DOOR_SCENE`, `Altitude_Warning`, `EXILE_1`, `Intensity`, `DRUG_TRAFFIC_AIR_SCREAMS`, `CONFIRM_BEEP`, `HUD_MINI_GAME_SOUNDSET`, `DRUG_TRAFFIC_AIR_BOMB_DROP_ERROR_MASTER`

**Scaleform movies** (8) - `SET_CLEAR_SPACE`, `SET_MAX_WIDTH`, `SET_DATA_SLOT_EMPTY`, `TOGGLE_MOUSE_BUTTONS`, `SET_DATA_SLOT`, `DRAW_INSTRUCTIONAL_BUTTONS`, `SET_BACKGROUND_COLOUR`, `instructional_buttons`

**Particle effects** (7) - `scr_drug_grd_plane_exp`, `scr_ojdg4_train_fire`, `scr_drug_grd_train_exp`, `scr_ojdg4_water_exp`, `scr_ojdg4_boat_exp`, `scr_ojdg4_boat_wreck_fire`, `scr_drug_traffic_flare_L`

**Texture dicts** (10) - `digitalOverlay`, `nscanline1`, `nscuzz1`, `nscuzz2`, `nscuzz3`, `Static1`, `Static2`, `Static3`, `Static4`, `Static5`

**Text labels** (7) - `ARMSAUD`, `OSCAR`, `TREVOR`, `NULL`, `NUMBER`, `DTRFAIR`, `DTRSHRD`

**Vehicle recordings** (4) - `CarpetBombNew`, `AirTaxiCut`, `carpetbombtruck`, `carpetbombplane`

**Relationship groups** (2) - `ENEMIES`, `relRivalRunners`

**Stats** (1) - `num_trafficking_completed`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_ENTITY_DEAD` (109), `PLAYER_PED_ID` (94), `GET_ENTITY_COORDS` (56), `DOES_ENTITY_EXIST` (47), `TRIGGER_MUSIC_EVENT` (45), `DOES_BLIP_EXIST` (40), `GET_RANDOM_INT_IN_RANGE` (28), `IS_PED_INJURED` (25), `ADD_EXPLOSION` (25), `REMOVE_BLIP` (24), `GET_GAME_TIMER` (23), `CREATE_PED` (23), `REQUEST_MODEL` (20), `SET_ENTITY_VISIBLE` (19), `CREATE_VEHICLE` (18), `WAIT` (17), `SET_BLIP_COLOUR` (17), `SET_ENTITY_LOD_DIST` (17), `CREATE_PED_INSIDE_VEHICLE` (17), `CLEAR_HELP` (16), `RENDER_SCRIPT_CAMS` (16), `GET_TRAIN_CARRIAGE` (16), `START_PARTICLE_FX_NON_LOOPED_AT_COORD` (15), `ADD_BLIP_FOR_ENTITY` (14), `CLEAR_PRINTS` (12), `SET_BLIP_SCALE` (12), `SET_ENTITY_COLLISION` (12), `DESTROY_CAM` (11), `DOES_CAM_EXIST` (11), `IS_STRING_NULL_OR_EMPTY` (10)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x43 · `0.2f` x6 · `90.72f` x5 · `1.5f` x4 · `0.75f` x4 · `0.39f` x4 · `0.4f` x3 · `39.5341f` x3 · `-0.16f` x3 · `2035.914f` x2 · `4765.766f` x2 · `40.0606f` x2 · `40.0605f` x2 · `4760.453f` x2 · `2030.663f` x2 · `2164.038f` x2 · `4825.627f` x2 · `35.61375f` x2 · `1899.278f` x2 · `4697.752f` x2 · `49.08641f` x2 · `1120.428f` x2 · `3016.568f` x2 · `40.1836f` x2

## Other strings

Literals whose consuming native was not classified:

`cuban800`, `DTRFAIR_OBJCF`, `bison`, `DRUG_TRAFFIC_AIR_BAY_DOOR_OPEN_MASTER`, `barracks`, `player`, `HAND_SHAKE`, `CarpetBombNew`, `PlaneGraveyardGround`, `NEW_TYPE1_05`, `baller`, `DTRFAIR_OBJ`, `DTRFAIR_OBJB`, `Generic_Alarms_Siren`, `OJDA4_TRAIN_HIT`, `CamPushInNeutral`, `DTRFAIR_TGT`, `DTRFAIR_DRP`, `DTRSHRD_03`, `BoatDepot`, `NEW_TYPE1_02`, `NEW_TYPE1_03`, `NEW_TYPE1_06`, `NEW_TYPE1_07`, `NEW_TYPE1_08`, `NEW_TYPE1_09`, `OJDA_STOP`, `DTRFAIR_FAIL_05`, `DTRSHRD_ART`, `DTRFAIR_UI05D`

---

Source: `decompiled_scripts/traffick_air.c`
