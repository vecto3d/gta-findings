# fm_hideout_controler.c

MP freemode script. 113 models; 5 scaleforms.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 179,821 |
| Functions | 2,286 (187 unique, 2,099 shared) |
| Unique lines | 36,887 (20.5% of file) |

## Assets

**Models and props** (113) - `g_m_y_mexgoon_01`, `g_m_y_lost_01`, `g_m_y_famca_01`, `a_m_m_hillbilly_02`, `g_m_y_salvagoon_01`, `ch_prop_track_ch_straight_bar_m`, `g_m_y_mexgoon_02`, `g_m_y_ballaorig_01`, `g_m_y_korean_02`, `g_m_m_armgoon_01`, `g_m_m_chigoon_01`, `s_m_y_blackops_01`, `a_m_o_acult_02`, `ch_prop_track_ch_straight_bar_s_s`, `ch_prop_track_ch_straight_bar_s`, `ch_prop_track_ch_bend_bar_l_out`, `ch_prop_track_ch_bend_bar_l_b`, `ch_prop_track_ch_bend_bar_m_out`, `ch_prop_track_ch_bend_bar_m_in`, `imp_prop_impexp_bblock_qp3`, `bkr_prop_biker_bblock_qp2`, `bkr_prop_biker_bblock_qp`, `bkr_prop_biker_bblock_hump_01`, `bkr_prop_biker_bblock_hump_02`, `s_m_y_cop_01`, `s_m_y_swat_01`, `s_m_y_marine_03`, `s_m_m_highsec_01`, `s_m_m_armoured_01`, `s_m_m_prisguard_01`, `s_m_m_security_01`, `s_m_y_prisoner_01`, `g_m_y_azteca_01`, `ba_prop_track_straight_lm`, `ch_prop_track_pit_stop_01`, `ba_prop_track_bend_l_b`, `ch_prop_track_ch_bend_bar_45d`, `ch_prop_track_ch_bend_45`, `ch_prop_track_ch_bend_bar_135`, `ch_prop_track_ch_bend_135`, `bkr_prop_biker_tube_xxs`, `bkr_prop_biker_tube_xs`, `bkr_prop_biker_tube_s`, `bkr_prop_biker_tube_m`, `bkr_prop_biker_tube_l`, `bkr_prop_biker_tube_crn`, `bkr_prop_biker_tube_crn2`, `bkr_prop_biker_tube_cross`, `bkr_prop_biker_tube_gap_01`, `bkr_prop_biker_tube_gap_02`, `bkr_prop_biker_tube_gap_03`, `ba_prop_battle_tube_fn_01`, `ba_prop_battle_tube_fn_02`, `ba_prop_battle_tube_fn_03`, `ba_prop_battle_tube_fn_04`, `ba_prop_battle_tube_fn_05`, `ba_prop_battle_track_exshort`, `ba_prop_battle_track_short`, `bkr_prop_biker_jump_s`, `bkr_prop_biker_jump_m` ...

**Sounds** (5) - `MP_CELEB_SCREEN_SCENE`, `MP_WAVE_COMPLETE`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`

**Scaleform movies** (5) - `STRING`, `ADD_STAT_NUMERIC_TO_WALL`, `ADD_BACKGROUND_TO_WALL`, `ADD_REP_POINTS_AND_RANK_BAR_TO_WALL`, `CREATE_STAT_WALL`

**Text labels** (4) - `left`, `right`, `SUMMARY`, `NULL`

**Decorators** (9) - `MPBitset`, `Creator_Trailer`, `Player_Vehicle`, `Not_Allow_As_Saved_Veh`, `RespawnVeh`, `Heist_Veh_ID`, `MC_ChasePedID`, `MC_EntityID`, `EnableVehLuxeActs`

**Vehicle mods** (5) - `cargobob4`, `mule`, `trailerlarge`, `bombushka`, `deluxo`

## Native vocabulary

Most-called natives inside the code unique to this script:

`ROUND` (354), `TO_FLOAT` (354), `PLAYER_ID` (214), `SET_BIT` (90), `PLAYER_PED_ID` (60), `SET_VEHICLE_EXTRA` (49), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (39), `GET_ENTITY_MODEL` (37), `PARTICIPANT_ID_TO_INT` (29), `DECOR_EXIST_ON` (29), `SET_VEHICLE_COLOURS` (27), `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME` (27), `DOES_ENTITY_EXIST` (25), `BEGIN_TEXT_COMMAND_SCALEFORM_STRING` (24), `END_TEXT_COMMAND_SCALEFORM_STRING` (24), `NET_TO_PED` (23), `CLEAR_BIT` (22), `NET_TO_VEH` (21), `DECOR_SET_INT` (21), `SUPPRESS_CRIME_THIS_FRAME` (21), `DECOR_IS_REGISTERED_AS_TYPE` (20), `BEGIN_SCALEFORM_MOVIE_METHOD` (18), `END_SCALEFORM_MOVIE_METHOD` (18), `GET_RANDOM_INT_IN_RANGE` (16), `PARTICIPANT_ID` (15), `NETWORK_IS_GAME_IN_PROGRESS` (14), `GET_WEAPONTYPE_GROUP` (14), `GET_PLAYER_PED_SCRIPT_INDEX` (13), `DECOR_GET_INT` (12), `GET_RANDOM_FLOAT_IN_RANGE` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x7 · `1.5f` x5 · `0.1f` x4 · `2.5f` x3 · `0.5f` x2 · `-475.1f` x2 · `-1686.1f` x2 · `28.103f` x2 · `0.046f` x1 · `0.6f` x1 · `0.4f` x1 · `0.2f` x1 · `0.65f` x1 · `-0.5f` x1 · `-0.4f` x1 · `3.5f` x1 · `0.15f` x1

## Other strings

Literals whose consuming native was not classified:

`singleplayer_overlays`, `hairOverlay`, `GROUP_SHOTGUN`, `GROUP_PISTOL`, `GROUP_SMG`, `GROUP_MG`, `GROUP_RIFLE`, `mp_g_m_pros_01`, `titan`, `submersible`, `submersible2`, `phantom2`, `dune4`, `CELEB_POINT_BLANK`, `CELEB_HEADSHOTS`, `CELEB_TOTAL_KILLS`, `GHO_WARN`, `mp_m_freemode_01`, `outfit_only`, `AM_GA_PICKUPS`, `boxville5`, `sum_prop_track_ac_straight_bar_s_s`, `sum_prop_track_ac_straight_bar_s`, `sum_prop_track_ac_bend_bar_m_out`, `sum_prop_track_ac_bend_bar_m_in`, `sum_prop_track_ac_bend_bar_l_out`, `sum_prop_track_ac_bend_bar_l_b`, `stt_prop_hoop_tyre_01a`, `stt_prop_stunt_wideramp`, `mule`

---

Source: `decompiled_scripts/fm_hideout_controler.c`
