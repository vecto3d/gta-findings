# startup.c

System and infrastructure script. 6 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 13,545 |
| Functions | 77 (44 unique, 33 shared) |
| Unique lines | 7,744 (57.2% of file) |

## Assets

**Models and props** (6) - `PROP_ARY_VAL`, `PROP_`, `PROP_DRINKS`, `PROP_SMOKES`, `PROP_STRIPPERS`, `PROP_NAMEDVEHS`

**Text labels** (10) - `CLOTHES`, `CARMODS`, `BGSAVEINT`, `PROPLIB`, `NULL`, `MPATMLOGVAL`, `MPATMLOGSCRS`, `MPATMLOGACT`, `MPATMLOGDAT`, `UID`

**Interiors and entity sets** (61) - `vbca_tunnel1`, `vbca_tunnel2`, `vbca_tunnel3`, `vbca_tunnel4`, `vbca_tunnel5`, `v_31_tun_01`, `v_31_newtunnel1`, `v_31_newtun5`, `v_31_newtun4b`, `v_31_newtun3`, `v_31_newtun2`, `sm20_tun4`, `sm20_tun3`, `sm20_tun2`, `sm20_tun1`, `sc1_rd_inttunshort`, `sc1_rd_inttun3b_end`, `sc1_rd_inttun3b`, `sc1_rd_inttun3`, `sc1_rd_inttun2b_end`, `sc1_rd_inttun2b`, `sc1_rd_inttun2`, `sc1_rd_inttun1`, `kt1_04_roadtunnel_int`, `kt1_03_carpark_int`, `id2_21_a_tun5`, `id2_21_a_tun4`, `id2_21_a_tun3`, `id2_21_a_tun2`, `id2_21_a_tun1`, `id1_11_tunnel8_int`, `id1_11_tunnel7_int`, `id1_11_tunnel6_int`, `id1_11_tunnel5_int`, `id1_11_tunnel4_int`, `id1_11_tunnel3_int`, `id1_11_tunnel2_int`, `id1_11_tunnel1_int`, `dt1_rd1_tun3`, `dt1_rd1_tun2`, `dt1_rd1_tun`, `cs4_rwayb_tunnelint`, `cs3_03railtunnel_int4`, `cs3_03railtunnel_int3`, `cs3_03railtunnel_int2`, `cs3_03railtunnel_int1`, `cs2_roadsb_tunnel_03`, `cs2_roadsb_tunnel_02`, `cs2_roadsb_tunnel_01`, `cs1_14brailway6`, `cs1_14brailway5`, `cs1_14brailway4`, `cs1_14brailway3`, `cs1_14brailway2`, `cs1_14brailway1`, `cs1_12_tunnel03_int`, `cs1_12_tunnel02_int`, `cs1_12_tunnel01_int`, `ch1_roadsdint_tun2`, `ch1_roadsdint_tun1` ...

**Stats** (3) - `content_hanger_veh`, `content_marina_veh`, `content_heli_veh`

**Scripts launched** (2) - `standard_global_init`, `standard_global_reg`

## Native vocabulary

Most-called natives inside the code unique to this script:

`REGISTER_INT_TO_SAVE` (145), `REGISTER_INT64_TO_SAVE` (65), `GET_INTERIOR_AT_COORDS_WITH_TYPE` (61), `STOP_SAVE_ARRAY` (58), `START_SAVE_ARRAY_WITH_SIZE` (56), `REGISTER_BOOL_TO_SAVE` (35), `REGISTER_EFFECT_FOR_REPLAY_EDITOR` (10), `REGISTER_FLOAT_TO_SAVE` (9), `START_SAVE_STRUCT_WITH_SIZE` (8), `STOP_SAVE_STRUCT` (6), `REQUEST_SCRIPT_WITH_NAME_HASH` (6), `SET_BIT` (5), `WAIT` (4), `REGISTER_ENUM_TO_SAVE` (4), `REGISTER_TEXT_LABEL_63_TO_SAVE` (3), `REGISTER_TEXT_LABEL_15_TO_SAVE` (3), `STAT_GET_INT` (3), `SET_PLAYER_IS_IN_ANIMAL_FORM` (2), `REMOVE_IPL` (2), `SET_SCRIPT_WITH_NAME_HASH_AS_NO_LONGER_NEEDED` (2), `START_SAVE_DATA` (2), `STOP_SAVE_DATA` (2), `REGISTER_TEXT_LABEL_31_TO_SAVE` (2), `HAS_SCRIPT_WITH_NAME_HASH_LOADED` (2), `START_NEW_SCRIPT_WITH_NAME_HASH` (2), `NETWORK_SET_SCRIPT_IS_SAFE_FOR_NETWORK_GAME` (1), `SET_PLAYER_IS_IN_DIRECTOR_MODE` (1), `IS_COMMANDLINE_END_USER_BENCHMARK` (1), `LANDING_SCREEN_STARTED_END_USER_BENCHMARK` (1), `COMMIT_TO_LOADINGSCREEN_SELCTION` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-1718.51f` x2 · `-1680.49f` x1 · `-929.44f` x1 · `-0.462531f` x1 · `-1562.04f` x1 · `-876.91f` x1 · `-0.471913f` x1 · `-1429.65f` x1 · `-823.211f` x1 · `-0.432763f` x1 · `-1316.9f` x1 · `-843.515f` x1 · `1.43639f` x1 · `-1249.67f` x1 · `-896.27f` x1 · `0.293292f` x1 · `-38.9818f` x1 · `-570.534f` x1 · `28.4812f` x1 · `481.908f` x1 · `-577.602f` x1 · `2.41908f` x1 · `1029.02f` x1 · `-260.955f` x1

## Other strings

Literals whose consuming native was not classified:

`64_`, `_10`, `_11`, `_12`, `_13`, `standard_global_reg`, `MP_BOUNTY_SAVED`, `CompDraw`, `CompTex`, `PropID`, `PropTex`, `CAR_HIDDEN`, `B_A_V_BS_ID`, `CHECKPOINT_NORMAL`, `CHECKPOINT_MISSED`, `CHECKPOINT_PERFECT`, `prologue_DistantLights`, `prologue_LODLights`, `standard_global_init`, `fSaveVersion`

---

Source: `decompiled_scripts/startup.c`
