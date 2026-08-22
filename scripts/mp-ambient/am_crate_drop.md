# am_crate_drop.c

MP ambient script. 11 models; 2 particle effects.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 50,949 |
| Functions | 452 (62 unique, 390 shared) |
| Unique lines | 3,458 (6.8% of file) |

## Assets

**Models and props** (11) - `prop_flare_01`, `prop_drug_package`, `p_cargo_chute_s`, `P_cargo_chute_S`, `P_cargo_chute_S_deploy`, `P_cargo_chute_S_crumple`, `g_m_y_mexgoon_03`, `g_m_y_lost_03`, `g_m_y_famca_01`, `g_m_m_chigoon_01`, `a_m_m_hillbilly_02`

**Sounds** (3) - `MP_CRATE_DROP_SOUNDS`, `Crate_Beeps`, `Crate_Collect`

**Particle effects** (2) - `scr_crate_drop_beacon`, `scr_crate_drop_flare`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`NET_TO_OBJ` (77), `SET_BIT` (54), `NETWORK_DOES_NETWORK_ID_EXIST` (34), `NET_TO_PED` (34), `PARTICIPANT_ID_TO_INT` (30), `PLAYER_ID` (24), `GET_RANDOM_INT_IN_RANGE` (19), `PLAYER_PED_ID` (16), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (10), `CLEAR_BIT` (9), `GET_SOUND_ID_FROM_NETWORK_ID` (7), `DOES_BLIP_EXIST` (7), `REQUEST_MODEL` (7), `IS_NETWORK_ID_OWNED_BY_PARTICIPANT` (7), `DOES_PARTICLE_FX_LOOPED_EXIST` (6), `GIVE_DELAYED_WEAPON_TO_PED` (6), `NET_TO_VEH` (6), `HAS_MODEL_LOADED` (6), `SET_ENTITY_SHOULD_FREEZE_WAITING_ON_COLLISION` (6), `SET_BLIP_DISPLAY` (6), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (6), `GET_ENTITY_COORDS` (5), `ABSF` (5), `NETWORK_IS_GAME_IN_PROGRESS` (4), `IS_ENTITY_AT_COORD` (4), `ROUND` (4), `REMOVE_BLIP` (4), `SET_PARTICLE_FX_LOOPED_COLOUR` (4), `SET_ACTIVATE_OBJECT_PHYSICS_AS_SOON_AS_IT_IS_UNFROZEN` (4), `PREVENT_COLLECTION_OF_PORTABLE_PICKUP` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-0.2f` x3 · `0.8f` x2 · `0.18f` x2 · `0.19f` x2 · `0.84f` x2 · `0.1f` x2 · `7.5f` x2 · `0.2f` x1 · `0.35f` x1 · `0.0245f` x1 · `1.2f` x1

## Other strings

Literals whose consuming native was not classified:

`service_earn_crate_drop`, `ACD_HELP1`, `mp_m_freemode_01`, `mp_f_freemode_01`, `-StraightIntoFreemode`, `XPT_MEDIUMT`, `ACD_TCONT_CX`, `ACD_TCONT_CXWAC`, `cavalcade`, `hexer`, `baller`, `mp_g_m_pros_01`, `granger`, `jackal`, `rebel`, `ACD_TICKS`, `ACD_TSC0`, `XPT_KAIE`, `ACD_BLIPR`, `ACD_BLIPN`, `ACD_TCONT_XW`, `ACD_TCONT_CXWA`

---

Source: `decompiled_scripts/am_crate_drop.c`
