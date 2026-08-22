# fm_content_possessed_animals.c

MP freemode script. 5 anim dicts; 10 models; 1 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 465,692 |
| Functions | 9,350 (110 unique, 9,240 shared) |
| Unique lines | 2,811 (0.6% of file) |

## Assets

**Animation dictionaries** (5) - `creatures@boar@amb@world_boar_grazing@idle_a`, `creatures@cougar@amb@world_cougar_rest@idle_a`, `creatures@coyote@amb@world_coyote_howl@idle_a`, `creatures@deer@amb@world_deer_grazing@idle_a`, `creatures@pug@amb@world_dog_sitting@idle_a`

**Models and props** (10) - `a_c_boar_02`, `a_c_mtlion_02`, `a_c_coyote_02`, `a_c_deer_02`, `a_c_pug_02`, `a_c_boar`, `a_c_mtlion`, `a_c_coyote`, `a_c_deer`, `a_c_pug`

**Audio banks** (1) - `DLC_MP2023_1/DLC_MP2023_1_HW`

**Particle effects** (1) - `scr_srr_hal`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_CONFIG_FLAG` (12), `SET_PED_COMBAT_ATTRIBUTES` (9), `NET_TO_PED` (4), `DOES_ENTITY_EXIST` (4), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (3), `IS_PED_IN_ANY_VEHICLE` (3), `DOES_PARTICLE_FX_LOOPED_EXIST` (3), `PLAYER_ID` (3), `GET_ENTITY_COORDS` (3), `SET_PED_RESET_FLAG` (3), `SET_ENTITY_HEALTH` (2), `NETWORK_HASH_FROM_PLAYER_HANDLE` (2), `IS_STRING_NULL_OR_EMPTY` (2), `USE_PARTICLE_FX_ASSET` (2), `STOP_PARTICLE_FX_LOOPED` (2), `SET_COMBAT_FLOAT` (2), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (2), `PARTICIPANT_ID_TO_INT` (2), `PLAYER_PED_ID` (2), `REMOVE_NAMED_PTFX_ASSET` (1), `RELEASE_NAMED_SCRIPT_AUDIO_BANK` (1), `START_NETWORKED_PARTICLE_FX_NON_LOOPED_ON_ENTITY` (1), `TO_FLOAT` (1), `GET_ENTITY_HEALTH` (1), `GET_PLAYER_PED` (1), `NETWORK_IS_PLAYER_ACTIVE` (1), `IS_PED_SWIMMING` (1), `NETWORK_FADE_OUT_ENTITY` (1), `GET_GROUND_Z_FOR_3D_COORD` (1), `GET_ENTITY_HEADING` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x1

## Other strings

Literals whose consuming native was not classified:

`Possessed_Animal_Sounds`, `idle_a`, `H23_PA_STOP_MUSIC`, `VULKAN_LOCK_ON_RED`, `VULKAN_LOCK_ON_AMBER`, `SUM22_RE_PA`, `H23_PA_START_MUSIC`, `H23_PA_TRANSFORM_MUSIC`, `Spawn_FE`, `Despawn_FE`, `Boar_Spawn_In_World`, `MtLion_Spawn_In_World`, `Coyote_Spawn_In_World`, `Deer_Spawn_In_World`, `Pug_Spawn_In_World`, `Despawn_In_World`, `scr_srr_hal_appear_smoke_boar`, `scr_srr_hal_appear_smoke_mtlion`, `scr_srr_hal_appear_smoke_coyote`, `scr_srr_hal_appear_smoke_deer`, `scr_srr_hal_appear_smoke_pug`, `idle_c`, `scr_srr_hal_smoke_boar`, `scr_srr_hal_smoke_mtlion`, `scr_srr_hal_smoke_coyote`, `scr_srr_hal_smoke_deer`, `scr_srr_hal_smoke_pug`, `oppressor2`

---

Source: `decompiled_scripts/fm_content_possessed_animals.c`
