# luxe_veh_activity.c

Vehicles script. 6 anim dicts; 7 models; 7 particle effects.

| | |
|---|---|
| Category | Vehicles |
| Total lines | 78,784 |
| Functions | 413 (71 unique, 342 shared) |
| Unique lines | 3,118 (4.0% of file) |

## Assets

**Animation dictionaries** (6) - `ANIM@MP_PLAYER_INTVEH@PLANE@LUXOR2@REAR_BACK@DRINK@`, `ANIM@MP_PLAYER_INTVEH@PLANE@LUXOR2@REAR_FRONT@DRINK@`, `ANIM@MP_PLAYER_INTVEH@HELICOPTER@SWIFT2@RDS@DRINK@`, `ANIM@MP_PLAYER_INTVEH@HELICOPTER@SWIFT2@RPS@DRINK@`, `ANIM@MP_PLAYER_INTVEH@PLANE@LUXOR2@REAR_BACK@SMOKE@`, `ANIM@MP_PLAYER_INTVEH@PLANE@LUXOR2@REAR_FRONT@SMOKE@`

**Models and props** (7) - `lux_prop_champ_01_luxe`, `lux_prop_cigar_01_luxe`, `lux_prop_lighter_luxe`, `lux_p_champ_flute_s`, `lux_p_pour_champagne_luxe`, `lux_prop_champ_flute_luxe`, `ex_prop_ashtray_luxe_02`

**Audio banks** (2) - `DLC_LUXE/LUXE_DRINK_CHAMPAGNE`, `DLC_LUXE/LUXE_SMOKE_CIGAR`

**Particle effects** (7) - `scr_mp_cig_plane`, `light_intensity`, `smoke_fade`, `ent_anim_lighter_sparks_plane`, `ent_anim_cig_smoke_plane`, `ent_anim_cig_exhale_mth_plane`, `ent_anim_lighter_flame_plane`

**Text labels** (1) - `NULL`

**Decorators** (2) - `Mansion_Spawned_Heli`, `LUXE_VEH_INSTANCE_ID`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (73), `PLAYER_ID` (71), `DOES_ENTITY_EXIST` (49), `NET_TO_ENT` (40), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (39), `CLEAR_BIT` (25), `CLEAR_HELP` (25), `GET_ENTITY_MODEL` (24), `SET_ENTITY_VISIBLE` (23), `NET_TO_OBJ` (23), `DISABLE_CONTROL_ACTION` (15), `ARE_STRINGS_EQUAL` (13), `GET_SYNCHRONIZED_SCENE_PHASE` (12), `IS_ENTITY_DEAD` (11), `SET_PED_CURRENT_WEAPON_VISIBLE` (11), `SET_PARTICLE_FX_LOOPED_EVOLUTION` (11), `NETWORK_DOES_NETWORK_ID_EXIST` (11), `SET_BIT` (10), `CREATE_OBJECT_NO_OFFSET` (10), `SET_ENTITY_COLLISION` (10), `SET_ENTITY_INVINCIBLE` (10), `GET_ENTITY_BONE_INDEX_BY_NAME` (10), `SET_NETWORK_ID_CAN_MIGRATE` (10), `GET_ANIM_INITIAL_OFFSET_POSITION` (10), `GET_ANIM_INITIAL_OFFSET_ROTATION` (10), `GET_NUM_RESERVED_MISSION_OBJECTS` (9), `HAS_ANIM_EVENT_FIRED` (9), `RESERVE_NETWORK_MISSION_OBJECTS` (7), `DOES_PARTICLE_FX_LOOPED_EXIST` (7), `IS_ENTITY_VISIBLE` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x15 · `0.06f` x3 · `0.04f` x3 · `-1.5f` x2 · `0.99f` x2 · `0.004f` x2 · `-0.025f` x1 · `0.13f` x1 · `1.5f` x1

## Other strings

Literals whose consuming native was not classified:

`swift2`, `seat_dside_r`, `LUX_VEH_ACT_1ST`, `LUX_ACT_1ST_SW`, `seat_pside_r`, `POD_CHAM_WEB`, `seat_pside_r1`, `seat_pside_r2`, `POD_CHAM_CIGAR`, `lux_prop_champ_01_luxe`, `seat_dside_r1`, `seat_pside_r3`, `POD_CIGAR`, `POD_WEB`, `LUX_ACT_BAIL`, `VFX_Emitter`, `lux_prop_cigar_01_luxe`, `seat_dside_f`, `seat_pside_f`, `luxor2`, `nimbus`, `HELP_PASSIVE`, `POD_UNKNOWN`, `lux_prop_lighter_luxe`, `lux_p_champ_flute_s`, `lux_p_pour_champagne_luxe`, `supervolito`, `supervolito2`, `volatus`, `avenger`

---

Source: `decompiled_scripts/luxe_veh_activity.c`
