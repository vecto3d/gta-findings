# chop.c

Ambient world script. 17 anim dicts; 9 models; 2 particle effects.

| | |
|---|---|
| Category | Ambient world |
| Total lines | 9,682 |
| Functions | 192 (103 unique, 89 shared) |
| Unique lines | 6,886 (71.1% of file) |

## Assets

**Animation dictionaries** (17) - `creatures@rottweiler@tricks@`, `creatures@rottweiler@move`, `misschop_vehicleenter_exit`, `creatures@rottweiler@amb@sleep_in_kennel@`, `creatures@rottweiler@amb@world_dog_barking@enter`, `creatures@rottweiler@amb@world_dog_barking@exit`, `creatures@rottweiler@in_vehicle@std_car`, `creatures@rottweiler@amb@world_dog_barking@idle_a`, `creatures@rottweiler@melee@streamed_taunts@`, `creatures@rottweiler@indication@`, `creatures@rottweiler@in_vehicle@4x4`, `creatures@rottweiler@in_vehicle@van`, `creatures@rottweiler@in_vehicle@low_car`, `creatures@rottweiler@amb@world_dog_barking@base`, `creatures@rottweiler@amb@world_dog_sitting@enter`, `creatures@rottweiler@amb@world_dog_sitting@idle_a`, `creatures@rottweiler@amb@world_dog_sitting@exit`

**Animations** (44) - `creatures@rottweiler@tricks@`, `creatures@rottweiler@move`, `enter`, `sit`, `exit`, `shunt_from_back`, `idle_a`, `sit_enter`, `sit_loop`, `sit_exit`, `fetch_pickup`, `fetch_drop`, `creatures@rottweiler@amb@sleep_in_kennel@`, `creatures@rottweiler@amb@world_dog_barking@enter`, `creatures@rottweiler@amb@world_dog_barking@idle_a`, `creatures@rottweiler@amb@world_dog_barking@exit`, `beg_loop`, `paw_right_loop`, `get_out`, `sleep_in_kennel`, `exit_kennel`, `base`, `beg_enter`, `beg_exit`, `paw_right_enter`, `paw_right_exit`, `petting_chop`, `petting_franklin`, `dump_enter`, `dump_loop`, `dump_exit`, `pee_right_enter`, `pee_right_idle`, `pee_right_exit`, `pee_left_enter`, `pee_left_idle`, `pee_left_exit`, `creatures@rottweiler@in_vehicle@std_car`, `creatures@rottweiler@indication@`, `get_in`, `bark`, `misschop_vehicleenter_exit`, `idle_c`, `idle_b`

**Models and props** (9) - `prop_big_shit_02`, `prop_streetlight_01`, `a_c_retriever`, `a_c_rottweiler`, `a_c_boar`, `a_c_coyote`, `a_c_deer`, `a_c_mtlion`, `a_c_pig`

**Sounds** (2) - `PICKUP_WEAPON_BALL`, `HUD_FRONTEND_WEAPONS_PICKUPS_SOUNDSET`

**Particle effects** (2) - `ent_anim_dog_peeing`, `ent_anim_dog_poo`

**Text labels** (9) - `PLAYFUL`, `WHINE`, `BARK`, `AGITATED`, `NULL`, `SNARL`, `GROWL`, `FRANKLIN`, `CHOP`

**Relationship groups** (1) - `rel_group_chop`

**Stats** (1) - `sp_chop_walk_done`

**Scripts launched** (2) - `sh_intro_f_hills`, `martin1`

**Hashed names** (3) - `bifta`, `monster`, `marshall`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (175), `GET_GAME_TIMER` (77), `TASK_PLAY_ANIM` (54), `REQUEST_ANIM_DICT` (36), `GET_ENTITY_COORDS` (33), `DISABLE_CONTROL_ACTION` (33), `HAS_ANIM_DICT_LOADED` (32), `IS_PED_IN_ANY_VEHICLE` (32), `REMOVE_ANIM_DICT` (27), `SET_PED_CONFIG_FLAG` (20), `CLEAR_PED_TASKS` (18), `IS_PLAYER_SWITCH_IN_PROGRESS` (17), `GET_DISTANCE_BETWEEN_COORDS` (14), `GET_RANDOM_INT_IN_RANGE` (14), `IS_PED_IN_GROUP` (14), `IS_HELP_MESSAGE_BEING_DISPLAYED` (13), `SET_BIT` (13), `IS_VEHICLE_DOOR_DAMAGED` (13), `OPEN_SEQUENCE_TASK` (12), `CLOSE_SEQUENCE_TASK` (12), `TASK_PERFORM_SEQUENCE` (12), `CLEAR_SEQUENCE_TASK` (12), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (12), `GET_VEHICLE_PED_IS_IN` (12), `REMOVE_PED_FROM_GROUP` (11), `TASK_TURN_PED_TO_FACE_ENTITY` (10), `PLAYER_ID` (10), `IS_PED_SITTING_IN_ANY_VEHICLE` (10), `IS_DISABLED_CONTROL_JUST_PRESSED` (10), `WAIT` (9)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x7 · `0.98f` x4 · `0.1f` x4 · `2.5f` x3 · `0.9f` x3 · `0.99f` x3 · `0.3f` x2 · `0.5f` x2 · `-0.32f` x2 · `-0.04f` x2 · `1.5f` x2 · `154.0731f` x1 · `765.5721f` x1 · `209.6901f` x1 · `-268.139f` x1 · `415.2881f` x1 · `109.7258f` x1 · `314.4171f` x1 · `965.207f` x1 · `208.4024f` x1 · `-0.15f` x1 · `-0.2f` x1 · `-0.5f` x1 · `-0.1f` x1

## Other strings

Literals whose consuming native was not classified:

`CHOP_RETURN1`, `CHOP_H_INTRO`, `CHOP_H_INTRO_KM`, `std_ds_open_door_for_chop`, `seat_pside_f`, `CHOP_H_WHIS`, `CHOP_CANT`, `CHOP_WALK`, `DisableBarks`, `_KM`, `CHOP_H_HOME_KM`, `CHOP_H_HOME`, `CHOP_H_NO_AD_KM`, `CHOP_H_NO_AD`, `CHOP_H_HUNT`, `CHOP_H_BALL`, `CHOP_H_NOVEH`, `CHOP_H_CAR`, `CHOP_H_BIKE`, `coach`, `CHOP_H_HAPPY`, `CHOP_H_WAIT_`, `CHOP_H_WAIT_0`, `CHOP_H_WAIT_1`, `CHOP_H_WAIT_2`, `CHOP_H_WAIT_3`, `CHOP_H_WAIT_4`, `CHOP_H_WALK_0`, `CHOP_H_WALK_1`, `CHOP_H_WALK_2`

---

Source: `decompiled_scripts/chop.c`
