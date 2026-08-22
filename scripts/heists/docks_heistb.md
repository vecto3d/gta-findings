# docks_heistb.c

Heists script. 4 anim dicts; 20 models; 1 particle effects.

| | |
|---|---|
| Category | Heists |
| Total lines | 132,231 |
| Functions | 1,010 (94 unique, 916 shared) |
| Unique lines | 13,985 (10.6% of file) |

## Assets

**Animation dictionaries** (4) - `missdocksheist2bfinale`, `missswitch`, `missheistdocks2bcarbob_cams`, `misschinese2_barrelroll`

**Animations** (4) - `missswitch`, `mid_mission_inside_helicopter_trevor`, `missdocksheist2bfinale`, `get_in_sub`

**Models and props** (20) - `s_m_y_blackops_01`, `prop_military_pickup_01`, `a_c_sharktiger`, `dinghy`, `cargobob3`, `submersible`, `buzzard`, `prop_lev_des_barge_01`, `ig_wade`, `ig_floyd`, `a_c_fish`, `armytrailer`, `prop_pool_ball_01`, `packer`, `prop_sub_cover_01`, `s_m_m_pilot_02`, `prop_cs_fertilizer`, `lazer`, `v_res_tre_sofa_mess_c`, `s_m_m_dockwork_01`

**Audio banks** (4) - `PORT_OF_LS_2B_SUB_LIFT`, `PORT_OF_LS_2B_HELICOPTER_DOOR_SMASH`, `PORT_OF_LS_ATTACH_CARGO`, `SCRIPT\PORT_OF_LS_01_GENERAL`

**Sounds** (39) - `DOCKS_HEIST_FINALE_2B_SOUNDS`, `DH_2B_ATTACH_SUB`, `DH_2B_SEE_BOATS`, `DH_2B_GET_TO_DROP_ZONE`, `DH_2B_ESCAPE_AS_MICHAEL`, `Missile_Incoming_Miss`, `BIOTECH_HEIST_UNDERWATER_SCENE`, `DH_2B_RETURN_TO_AIRSTRIP`, `DH_2B_DRIVE_TO_AIRSTRIP`, `DH_2B_RELEASE_SUB`, `DH_2B_FIND_CONTAINER`, `DH_2B_GET_TO_SURFACE`, `DH_2B_PICK_UP_SUB_CARGO`, `DH_2B_ESCAPE_ENEMIES`, `DH_2B_SEE_PLANE`, `SWAP_POSITION`, `SwimSpeed`, `DH_2B_ENEMY_HELI_02_ARRIVES`, `DH_2B_ENEMY_HELI_01_ARRIVES`, `Missile_Incoming_Hit`, `DH_2B_SUB_PICKED_UP_SCENE`, `DH_2B_ENEMY_HELI_03_ARRIVES`, `FBI_05_RAID_FOOT_SWISH`, `FBI_05_RAID_BREATH`, `BIOTECH_HEIST_GASMASK_SCENE`, `DH_2B_CHOPPERS_APPEAR`, `DH_2B_FIGHT_CHOPPERS`, `DH_2B_ESCAPE_AS_FRANKLIN`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `DOCKS_HEIST_FINALE_2A_SUB_LAND`, `DOCKS_HEIST_FINALE_2A_SOUNDS`, `Door_Open`, `Hit_Out`, `Short_Transition_In`, `Sub_Lift`, `Attach_Cargo`, `VEHICLE_WATER_SPLASH_HEAVY_SCRIPT`, `UW_Ambience`, `UW_Rebreather`

**Particle effects** (1) - `scr_pls_sub_water_drips`

**Text labels** (10) - `D2BAUD`, `MICHAEL`, `TREVOR`, `FRANKLIN`, `WADE`, `STABALISE`, `MERRYWEATHER1`, `FLOYD`, `NULL`, `DOCKH2B`

**Scenarios** (6) - `WORLD_HUMAN_STAND_IMPATIENT`, `WORLD_HUMAN_CLIPBOARD`, `WORLD_HUMAN_GUARD_STAND`, `WORLD_FISH_FLEE`, `WORLD_HUMAN_BINOCULARS`, `WORLD_SHARK_SWIM`

**Vehicle recordings** (1) - `DHF2`

**Relationship groups** (3) - `player`, `BUDDIES`, `ENEMIES`

**Vehicle mods** (1) - `taxi`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_VEHICLE_DRIVEABLE` (410), `IS_PED_INJURED` (327), `PLAYER_PED_ID` (298), `DOES_ENTITY_EXIST` (247), `GET_GAME_TIMER` (114), `GET_ENTITY_COORDS` (105), `SET_PED_CONFIG_FLAG` (68), `CLEAR_PRINTS` (65), `DOES_BLIP_EXIST` (63), `REQUEST_MODEL` (61), `FREEZE_ENTITY_POSITION` (60), `SET_MODEL_AS_NO_LONGER_NEEDED` (57), `GET_SCRIPT_TASK_STATUS` (55), `SET_PED_INTO_VEHICLE` (51), `IS_AUDIO_SCENE_ACTIVE` (48), `HAS_MODEL_LOADED` (48), `GET_DISTANCE_BETWEEN_COORDS` (46), `TASK_DRIVE_BY` (43), `SET_ENTITY_COORDS` (38), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (38), `DISABLE_CONTROL_ACTION` (37), `IS_PED_IN_VEHICLE` (36), `STOP_AUDIO_SCENE` (36), `PLAYER_ID` (33), `DELETE_PED` (32), `IS_PED_IN_ANY_VEHICLE` (31), `CLEAR_HELP` (31), `REQUEST_VEHICLE_ASSET` (30), `WAIT` (30), `SET_ENTITY_HEADING` (30)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x33 · `40.0871f` x9 · `1754.472f` x8 · `3283.072f` x8 · `40.0925f` x8 · `0.25f` x8 · `1750.633f` x8 · `3285.028f` x8 · `-833.074f` x8 · `6397.145f` x8 · `-10.1586f` x8 · `29.25f` x8 · `78.25f` x8 · `-1.7f` x7 · `-1388.26f` x7 · `6160.88f` x7 · `0.34f` x7 · `0.5f` x5 · `-1309.16f` x5 · `6145.46f` x5 · `2.36f` x5 · `3264.86f` x5 · `41.22f` x5 · `1738.64f` x5

## Other strings

Literals whose consuming native was not classified:

`dinghy`, `cargobob3`, `submersible`, `buzzard`, `tailgater`, `DROPPED THE SUB`, `DS2_SWITCHS`, `lazer`, `DS2_FLYGB`, `DS2_GRAP_HELP1`, `player`, `DS2_S2MH`, `DS2_REL_WRONG`, `packer`, `armytrailer`, `DS2_SUBBLIP`, `DS2_FLYGI`, `DS2_GRAP_HELP2`, `DS2_GIPOSFSUB`, `buffalo`, `LSDH_2B_MCS_1`, `Trevor`, `Franklin`, `DS2A_CHOP`, `DS2A_SBOATS`, `DS2A_P6g`, `DS2A_P6f`, `DS2A_SPLANE`, `DS2_S2FH`, `DS2_SWITCHS2`

---

Source: `decompiled_scripts/docks_heistb.c`
