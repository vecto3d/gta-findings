# Native reference

Part of the [GTA V decompiled script findings](README.md).

## Decorators — entity state that survives ownership migration

`DECOR_EXIST_ON` (23399), `DECOR_GET_INT` (16133), `DECOR_SET_INT` (5671),
`DECOR_GET_BOOL` (1589), `DECOR_SET_BOOL` (1285), `DECOR_REGISTER` (115).

Named decorators worth knowing: `MPBitset` (9814), `Player_Vehicle` (5764),
`Veh_Modded_By_Player` (2301), `PV_Slot` (2282), `IgnoredByQuickSave` (2051),
`Not_Allow_As_Saved_Veh` (1810), `ContrabandOwner` (1775), `Player_Thruster`
(1592), `MLJ` (1536), `ExportVehicle` (1507), `Creator_Trailer` (1285),
`bombdec` / `bombowner` (1178 / 1135), `Player_Hacker_Truck` (1114).

FiveM has state bags now, but decorators still work and are how vanilla marks
personal vehicles and ownership.

## Doors

`ADD_DOOR_TO_SYSTEM` — 1493 call sites. Gate and door models registered:
`prop_gar_door_03_ld`, `prop_com_gar_door_01`, `prop_hw1_03_gardoor_01`,
`prop_facgate_01` / `_01b`, `prop_lrggate_01_l` / `_r`, `prop_arm_gate_l`,
`prop_bh1_03_gate_l` / `_r`, `prop_bh1_48_gate_1`, `prop_fnclink_03gate5`,
`prop_abat_slide`, `hei_prop_hei_bankdoor_new`.

The door system handles locking, auto-open ranges and network sync — worth using
instead of hand-rolling door locks.

## Interior entity sets

`ENABLE_INTERIOR_PROP` names, used to swap interior contents at runtime:

`shutter_closed` (126), `SET_ACCESS_BLOCKER` (30), `SET_VAULT_DOOR_OPEN` /
`_CLOSED` (26 each), `SET_MOD_BLOCKER`, `SET_GAR_PODIUM_BLOCKER`,
`SET_GAR_MOD_BLOCKER`, `SET_ARMORY_BLOCKER` (26 each), `VIP_XMAS_DECS` (20),
`SET_PET_DOG` / `SET_PET_CAT` (18 each), `entity_set_tint_options`,
`entity_set_office`, `entity_set_light_option_1`, `SET_ELEV_STD`,
`SET_GAR_AI_TABLETS_01`–`03`, `SET_BASE_AI_TABLETS_01`–`03`.

This is how property upgrades and decorations are toggled without loading a
different interior.

## Relationship groups

`ENEMIES` (29), `rgh_traffic` (19), `Player Group` (19), `BUDDIES` (13),
`TAXI_Passenger` (10), `players group` (7), `enemy group` (7),
`instructorRelGroup` (6), `TOWBUDDIES` (6), `FRIENDLIES` (6),
`rgFM_AiHatedByCopsAndMercs` (5), `RamageGrp` (5), `PassiveGrp` (5),
`rgFM_AiHatePlyrLikeAllAi` (4).

The `rgFM_*` names show how freemode AI hostility is modelled.

## Timecycle modifiers

`spectator1` (225) through `spectator10`, `CAMERA_secuirity_FUZZ` (114) and
`CAMERA_secuirity` (97) — note the misspelling by R*, which must be reproduced
exactly. Also `mp_x17dlc_int_02_vehicle_avenger_camera`, `mp_bkr_ware02_upgrade`
/ `03_upgrade`, `INT_smshop_inMOD`, `Yacht_Mission_ThunderRain`,
`DLC_mp2023_02_Maze_Shad`.

The security-camera pair is what gives CCTV its look.

## Pickups

Most-referenced: `pickup_weapon_advancedrifle` (399), `pickup_health_standard`
(324), `pickup_weapon_grenade` (302), `pickup_armour_standard` (280),
`pickup_weapon_rpg` (274), `pickup_weapon_pistol` (250),
`pickup_vehicle_custom_script` (245), `pickup_custom_script` (226),
`pickup_vehicle_health_standard` (219), `pickup_ammo_pistol` (201),
`pickup_vehicle_health_standard_low_glow` (189).

`pickup_custom_script` and `pickup_vehicle_custom_script` are the generic
script-defined pickups — use these for custom collectibles rather than
repurposing a weapon pickup.

## Explosions, weapons, cutscenes

- `ADD_EXPLOSION` (562), `ADD_OWNED_EXPLOSION` (66), `START_SCRIPT_FIRE` (17).
- Weapon hashes, most referenced: `weapon_unarmed` (9679) — used constantly to
  stash the equipped weapon during an interaction, exactly as the vending
  machine does — then `weapon_pistol` (8008), `weapon_carbinerifle` (5015),
  `weapon_assaultrifle` (4455), `weapon_smg` (4386), `weapon_heavysniper` (4156).
- 246 distinct cutscenes requested via `REQUEST_CUTSCENE`.

## IPLs

Most-toggled: `ch_cutscene_casino` (496), `smboat` (146), `hei_carrier` and
`hei_carrier_LODLights` (140), `farmint` / `farmint_cap` (140),
`CS1_02_cf_onmission1`–`4` (140 each), `facelobby` / `facelobbyfake` (138),
`hei_bi_hw1_13_door` (137), `gr_Heist_Yacht2_enginrm` (137).

Useful when a script needs a map piece that is not loaded by default.

---

## Task vocabulary

Most-used `TASK_*` natives, which is effectively R* AI vocabulary:

`TASK_LEAVE_ANY_VEHICLE` (16340), `TASK_SYNCHRONIZED_SCENE` (7998),
`TASK_PLAY_ANIM` (7642), `TASK_PERFORM_SEQUENCE` (3239),
`TASK_GO_STRAIGHT_TO_COORD` (3023), `TASK_FOLLOW_NAV_MESH_TO_COORD` (2990),
`TASK_LOOK_AT_ENTITY` (2343), `TASK_ENTER_VEHICLE` (2125),
`TASK_HELI_MISSION` (1849), `TASK_PLAY_ANIM_ADVANCED` (1463),
`TASK_START_SCENARIO_IN_PLACE` (1071), `TASK_COMBAT_PED` (1021),
`TASK_VEHICLE_FOLLOW_WAYPOINT_RECORDING` (992), `TASK_CLEAR_LOOK_AT` (973),
`TASK_SMART_FLEE_PED` (954), `TASK_TURN_PED_TO_FACE_ENTITY` (901),
`TASK_COMBAT_HATED_TARGETS_AROUND_PED` (844), `TASK_ACHIEVE_HEADING` (733),
`TASK_GO_TO_COORD_ANY_MEANS` (681), `TASK_VEHICLE_DRIVE_TO_COORD` (659),
`TASK_BOAT_MISSION` (614), `TASK_PLANE_MISSION` (563),
`TASK_SMART_FLEE_COORD` (507), `TASK_PLANE_TAXI` (504),
`TASK_VEHICLE_TEMP_ACTION` (496), `TASK_WANDER_STANDARD` (374).

`TASK_PERFORM_SEQUENCE` at 3239 is notable — R* chains tasks into sequences
rather than driving each one from script state.

## Pre-authored paths

- **154 distinct waypoint recordings** (`REQUEST_WAYPOINT_RECORDING`) — named
  vehicle routes, e.g. `ARM2`, `ARM2_FIRE`, `AccomMarching01`, `BB_JEW_1`.
  Driven with `TASK_VEHICLE_FOLLOW_WAYPOINT_RECORDING` (992 uses).
- **146 distinct vehicle recordings** (`REQUEST_VEHICLE_RECORDING`) — full
  playback of a recorded drive, used for scripted traffic and chases.

Both are shipped game data, so a FiveM script can play them back without
authoring anything.

## Ped natives, by call count

`SET_PED_COMPONENT_VARIATION` (104718), `SET_PED_CONFIG_FLAG` (37034),
`SET_PED_CAN_SWITCH_WEAPON` (16305), `SET_PED_CAN_BE_KNOCKED_OFF_VEHICLE`
(14255), `SET_PED_RESET_FLAG` (10314), `SET_PED_COMBAT_ATTRIBUTES` (8092),
`SET_PED_PROP_INDEX` (6843), `SET_PED_STEALTH_MOVEMENT` (5544),
`SET_PED_MAX_MOVE_BLEND_RATIO` (5014), `SET_PED_DEFAULT_COMPONENT_VARIATION`
(3606), `SET_PED_INTO_VEHICLE` (3302), `SET_PED_KEEP_TASK` (2306),
`SET_PED_HEAD_BLEND_DATA` (2226), `SET_PED_CAN_BE_TARGETTED` (1903).

## Vehicle natives, by call count

`SET_VEHICLE_DOORS_LOCKED_FOR_ALL_PLAYERS` (18680), `SET_VEHICLE_MOD` (14049),
`SET_VEHICLE_DISABLE_TOWING` (13475), `SET_VEHICLE_ON_GROUND_PROPERLY` (13114),
`SET_VEHICLE_DOORS_LOCKED` (13103), `SET_VEHICLE_COLOURS` (12628),
`SET_VEHICLE_EXTRA` (10442), `SET_VEHICLE_EXTRA_COLOURS` (10106),
`SET_VEHICLE_ENGINE_ON` (9028), `SET_VEHICLE_WEAPON_RESTRICTED_AMMO` (7174),
`SET_VEHICLE_DOORS_LOCKED_FOR_PLAYER` (5955), `SET_VEHICLE_MOD_KIT` (4078).

## Namespace weighting

`PLAYER` (2.76M), `MISC` (1.42M), `ENTITY` (1.36M), `FILES` (1.20M),
`PED` (1.14M), `SYSTEM` (736K), `VEHICLE` (699K), `PAD` (691K),
`NETWORK` (582K), `HUD` (367K), `GRAPHICS` (194K), `TASK` (188K),
`STREAMING` (188K), `CAM` (186K), `OBJECT` (127K), `AUDIO` (124K),
`DATAFILE` (105K), `STATS` (80K), `DECORATOR` (69K), `SCRIPT` (56K).
