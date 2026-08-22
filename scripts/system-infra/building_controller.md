# building_controller.c

System and infrastructure script. 45 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 11,827 |
| Functions | 142 (42 unique, 100 shared) |
| Unique lines | 3,609 (30.5% of file) |

## Assets

**Models and props** (45) - `prop_gate_docks_ld`, `prop_sec_barrier_ld_01a`, `prop_com_gar_door_01`, `prop_facgate_01`, `prop_sm1_11_doorr`, `prop_bh1_44_door_01r`, `prop_yaught_chair_01`, `xm_prop_x17dlc_rep_sign_01a`, `xm_prop_base_cabinet_door_01`, `prop_gate_military_01`, `prop_ss1_mpint_door_l`, `prop_ss1_mpint_door_r`, `prop_ss1_mpint_garage`, `prop_kt1_10_mpdoor_l`, `prop_kt1_10_mpdoor_r`, `prop_sm1_11_doorl`, `prop_parasol_01`, `prop_lrggate_02_ld`, `prop_gate_cult_01_l`, `prop_gate_cult_01_r`, `prop_hw1_03_gardoor_01`, `prop_ch_025c_g_door_01`, `prop_facgate_07b`, `prop_lrggate_01c_l`, `prop_lrggate_01c_r`, `prop_facgate_01b`, `prop_sc1_12_door`, `prop_dt1_20_mp_door_l`, `prop_dt1_20_mp_door_r`, `prop_dt1_20_mp_gar`, `prop_sm_14_mp_gar`, `prop_bh1_09_mp_l`, `prop_bh1_09_mp_r`, `prop_bh1_09_mp_gar`, `prop_bh1_08_mp_gar`, `p_cut_door_01`, `p_cut_door_03`, `prop_sm_10_mp_door`, `prop_sm1_11_garaged`, `prop_bh1_44_door_01l`, `prop_ss1_05_mp_door`, `prop_ss1_08_mp_door_l`, `prop_ss1_08_mp_door_r`, `prop_kt1_06_door_l`, `prop_kt1_06_door_r`

**Text labels** (1) - `NULL`

**Interiors and entity sets** (3) - `M23_1_dlc_int_02_M23_1`, `m23_2_dlc_int_garage`, `v_chopshop`

**Scripts launched** (1) - `extreme2`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_IPL_ACTIVE` (264), `REMOVE_IPL` (169), `REQUEST_IPL` (121), `PLAYER_PED_ID` (99), `CLEAR_BIT` (88), `SET_BIT` (60), `PLAYER_ID` (16), `GET_ENTITY_COORDS` (16), `DOOR_SYSTEM_SET_DOOR_STATE` (12), `IS_NEW_LOAD_SCENE_ACTIVE` (10), `DOES_ENTITY_EXIST` (10), `IS_DOOR_REGISTERED_WITH_SYSTEM` (10), `ADD_EXTENDED_PICKUP_PROBE_AREA` (9), `DOOR_SYSTEM_SET_OPEN_RATIO` (8), `GET_DISTANCE_BETWEEN_COORDS` (8), `TIMESTEP` (8), `VDIST2` (8), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (7), `NETWORK_IS_GAME_IN_PROGRESS` (5), `CREATE_MODEL_HIDE` (5), `IS_ENTITY_IN_ANGLED_AREA` (5), `ADD_DOOR_TO_SYSTEM` (4), `DOOR_SYSTEM_SET_HOLD_OPEN` (4), `IS_POINT_IN_ANGLED_AREA` (4), `NETWORK_IS_ACTIVITY_SESSION` (3), `IS_PLAYER_SWITCH_IN_PROGRESS` (3), `GET_PLAYER_SWITCH_STATE` (3), `REMOVE_DOOR_FROM_SYSTEM` (3), `GET_INTERIOR_AT_COORDS_WITH_TYPE` (3), `GET_HASH_KEY` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x6 · `480.4354f` x3 · `-1317.91f` x3 · `29.5957f` x3 · `313.54f` x2 · `86.14f` x2 · `31.61f` x2 · `34.98f` x2 · `39.81f` x2 · `38.37f` x2 · `44.04f` x2 · `42.61f` x2 · `64.84f` x2 · `64.02f` x2 · `-627.34f` x2 · `61.29f` x2 · `-862.99f` x2 · `21.09f` x2 · `-763.9f` x2 · `28.19f` x2 · `2222.883f` x1 · `5612.299f` x1 · `55.291f` x1 · `15.325f` x1

## Other strings

Literals whose consuming native was not classified:

`xm_siloentranceclosed_x17`, `xm_hatches_terrain`, `xm3_warehouse_grnd`, `AZ_MUSIC_MALIBU_08`, `xm_hatch_closed`, `xm_bunkerentrance_door`, `h4_ClubPoster_KeineMusik`, `h4_ClubPoster_MoodyMann`, `h4_ClubPoster_PalmsTraxx`, `tr_tuner_shop_burton`, `tr_tuner_shop_mesa`, `tr_tuner_shop_mission`, `tr_tuner_shop_rancho`, `tr_tuner_shop_strawberry`, `tr_tuner_meetup`, `tr_tuner_race_line`, `sf_musicrooftop`, `sf_phones`, `sf_franklin`, `sf_mansionroof`, `hei_showroom_closed`, `hei_showroom_open`, `hei_showroom_open_props`, `xm3_warehouse`, `xm3_doc_sign`, `xm3_stash_cams`, `m23_2_acp_collision_fixes_01`, `m23_2_acp_collision_fixes_02`, `xs_arena_banners_ipl`, `hei_dlc_windows_casino`

---

Source: `decompiled_scripts/building_controller.c`
