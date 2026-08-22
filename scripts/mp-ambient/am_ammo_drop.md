# am_ammo_drop.c

MP ambient script. 1 anim dicts; 4 models; 1 particle effects.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 5,930 |
| Functions | 159 (32 unique, 127 shared) |
| Unique lines | 1,161 (19.6% of file) |

## Assets

**Animation dictionaries** (1) - `P_cargo_chute_S`

**Animations** (3) - `P_cargo_chute_S`, `P_cargo_chute_S_crumple`, `P_cargo_chute_S_deploy`

**Models and props** (4) - `p_cargo_chute_s`, `s_m_m_pilot_02`, `prop_box_ammo02a`, `ex_prop_adv_case_sm`

**Sounds** (3) - `Crate_Underwater`, `Crate_Beeps`, `MP_CRATE_DROP_SOUNDS`

**Particle effects** (1) - `scr_crate_drop_beacon`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`NET_TO_OBJ` (61), `SET_BIT` (26), `NETWORK_DOES_NETWORK_ID_EXIST` (25), `NET_TO_VEH` (18), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (12), `GET_SOUND_ID_FROM_NETWORK_ID` (11), `PARTICIPANT_ID_TO_INT` (9), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (7), `NET_TO_PED` (7), `PLAYER_PED_ID` (6), `PLAYER_ID` (5), `GET_ENTITY_COORDS` (5), `REQUEST_MODEL` (5), `HAS_MODEL_LOADED` (5), `SET_DISABLE_BREAKING` (4), `IS_HELP_MESSAGE_BEING_DISPLAYED` (4), `SET_ENTITY_SHOULD_FREEZE_WAITING_ON_COLLISION` (4), `DOES_BLIP_EXIST` (3), `HAS_OBJECT_BEEN_BROKEN` (3), `DOES_PARTICLE_FX_LOOPED_EXIST` (3), `ACTIVATE_PHYSICS` (3), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (3), `IS_NETWORK_ID_OWNED_BY_PARTICIPANT` (3), `SET_ACTIVATE_OBJECT_PHYSICS_AS_SOON_AS_IT_IS_UNFROZEN` (3), `IS_ENTITY_ATTACHED` (2), `DETACH_ENTITY` (2), `CLEAR_BIT` (2), `GET_ENTITY_SUBMERGED_LEVEL` (2), `SET_VARIABLE_ON_SOUND` (2), `RESERVE_NETWORK_MISSION_PEDS` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x3 · `0.9f` x2 · `0.1f` x2 · `1.5f` x1 · `0.2f` x1 · `0.8f` x1 · `0.18f` x1 · `0.19f` x1 · `0.7f` x1 · `0.0245f` x1 · `1.2f` x1 · `0.25f` x1 · `-0.2f` x1

## Other strings

Literals whose consuming native was not classified:

`cuban800`, `AMD_HELP3`, `AMD_HELP1`, `AMD_BLIPN`, `AMD_HELP2`, `BALD_HELP1`, `BALD_HELP2`, `BALD_HELP3`, `AMD_BLIPBALL`, `FM_Pilot_Ammo`, `CT_AUD`, `MPCT_AMOinc`

---

Source: `decompiled_scripts/am_ammo_drop.c`
