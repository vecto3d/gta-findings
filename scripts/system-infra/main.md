# main.c

System and infrastructure script. 30 models; 5 scaleforms.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 174,765 |
| Functions | 2,022 (572 unique, 1,450 shared) |
| Unique lines | 41,326 (23.6% of file) |

## Assets

**Models and props** (30) - `a_m_m_paparazzi_01`, `a_f_y_beach_01`, `a_m_y_business_02`, `a_m_m_eastsa_02`, `u_m_m_jewelthief`, `g_m_m_chigoon_02`, `a_f_y_genhot_01`, `g_m_y_mexgoon_03`, `a_m_m_farmer_01`, `a_m_y_skater_02`, `a_m_y_soucent_04`, `a_f_y_bevhills_03`, `a_m_y_business_01`, `towtruck`, `cuban800`, `dune`, `stretch`, `superd`, `stunt`, `pony2`, `benson`, `SET_SOFT_KEYS`, `g_m_y_ballaorig_01`, `g_m_y_korean_01`, `g_m_y_mexgoon_02`, `prop_forsale_dyn_01`, `vader`, `player_zero`, `PROP_OFFG`, `PROP_OFFG_SHOP`

**Audio banks** (2) - `TAKINGS`, `HUD_PROPERTY`

**Sounds** (13) - `ON`, `UNDER_THE_BRIDGE`, `HUD_AWARDS`, `REPLAY_SCREEN_SCENE`, `LOOP`, `OFF`, `NOIR_FILTER_SOUNDS`, `Hang_Up`, `HUD_PROPERTY_SOUNDSET`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `Menu_Accept`, `Phone_SoundSet_Default`

**Scaleform movies** (5) - `SET_DATA_SLOT`, `CELL_CONDFON`, `MIDSIZED_MESSAGE`, `SHOW_SHARD_MIDSIZED_MESSAGE`, `SHARD_ANIM_OUT`

**Text labels** (6) - `NULL`, `DUMMY`, `OFF`, `FMMC_DOWNLOAD`, `PROPR`, `REMINDER_CM`

**Decorators** (5) - `Not_Allow_As_Saved_Veh`, `Player_Vehicle`, `Player_Truck`, `Player_Avenger`, `Player_Hacker_Truck`

**Vehicle mods** (6) - `pony2`, `benson`, `gauntlet`, `bjxl`, `submersible`, `chernobog`

**Stats** (39) - `sp_unlock_exclus_content`, `sp0_weap_dlc_unlock_0`, `sp1_weap_dlc_unlock_0`, `sp2_weap_dlc_unlock_0`, `sp0_cars_exploded`, `sp1_cars_exploded`, `sp2_cars_exploded`, `sp0_shots`, `sp1_shots`, `sp2_shots`, `sp0_busted`, `sp1_busted`, `sp2_busted`, `sp0_deaths`, `sp1_deaths`, `sp2_deaths`, `sp0_dist_heli`, `sp1_dist_heli`, `sp2_dist_heli`, `sp0_dist_plane`, `sp1_dist_plane`, `sp2_dist_plane`, `sp0_dist_car`, `sp1_dist_car`, `sp2_dist_car`, `sp0_dist_bike`, `sp1_dist_bike`, `sp2_dist_bike`, `sp0_dist_bicycle`, `sp1_dist_bicycle`, `sp2_dist_bicycle`, `sp0_dist_walking`, `sp1_dist_walking`, `sp2_dist_walking`, `sp0_dist_running`, `sp1_dist_running`, `sp2_dist_running`, `fl_co_jh2a`, `fl_co_jh2b`

**Scripts launched** (51) - `net_cloud_mission_loader`, `wardrobe_sp`, `mission_triggerer_a`, `mission_triggerer_b`, `mission_triggerer_c`, `mission_triggerer_d`, `appmpjoblistnew`, `ambient_Sonar`, `controller_Towing`, `mission_repeat_controller`, `respawn_controller`, `code_controller`, `player_controller_b`, `family_scene_f0`, `country_race_controller`, `initial`, `startup_positioning`, `am_mp_property_int`, `golf`, `launcher_basejumpheli`, `launcher_basejumppack`, `launcher_golf`, `launcher_hunting_ambient`, `launcher_offroadracing`, `launcher_racing`, `launcher_rampage`, `launcher_pilotschool`, `launcher_range`, `launcher_stunts`, `launcher_tennis`, `launcher_triathlon`, `launcher_yoga`, `launcher_darts`, `cablecar`, `photographymonkey`, `photographywildlife`, `ambient_solomon`, `controller_races`, `randomchar_controller`, `ambient_ufos`, `bootycallhandler`, `save_anywhere`, `replay_controller`, `comms_controller`, `flow_help`, `animal_controller`, `autosave_controller`, `ambientblimp`, `friends_controller`, `pi_menu`, `director_mode`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (213), `PLAYER_ID` (147), `GET_GAME_TIMER` (111), `SET_BIT` (88), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (59), `CLEAR_BIT` (55), `SET_PED_COMPONENT_VARIATION` (46), `IS_PED_INJURED` (35), `IS_STRING_NULL_OR_EMPTY` (35), `SET_MODEL_AS_NO_LONGER_NEEDED` (33), `REQUEST_MODEL` (33), `GET_ENTITY_COORDS` (32), `HAS_MODEL_LOADED` (32), `DOES_ENTITY_EXIST` (31), `GET_RANDOM_INT_IN_RANGE` (28), `IS_ENTITY_DEAD` (24), `NETWORK_IS_GAME_IN_PROGRESS` (24), `IS_PLAYER_PLAYING` (23), `TO_FLOAT` (22), `WAIT` (21), `STAT_GET_FLOAT` (21), `IS_VEHICLE_DRIVEABLE` (19), `GET_HASH_KEY` (18), `CREATE_PED` (17), `STAT_GET_INT` (16), `STAT_SET_INT` (16), `SET_VEHICLE_MODEL_IS_SUPPRESSED` (15), `IS_PLAYER_SWITCH_IN_PROGRESS` (14), `RECORD_GREATEST_MOMENT` (14), `REQUEST_SCRIPT` (14)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`2136.133f` x5 · `4780.563f` x5 · `39.9702f` x5 · `0.5f` x4 · `1175.7f` x2 · `2639.3f` x2 · `38.1f` x2 · `90.5877f` x2 · `163.5411f` x2 · `-1085.279f` x2 · `-2970.573f` x2 · `12.9457f` x2 · `0.975f` x1 · `22.8f` x1 · `878.2869f` x1 · `-194.9633f` x1 · `77.59733f` x1 · `931.6304f` x1 · `-147.0559f` x1 · `74.05599f` x1 · `401.6467f` x1 · `-1633.308f` x1 · `29.25f` x1 · `-128.47f` x1

## Other strings

Literals whose consuming native was not classified:

`PROPR_HELP_MANH`, `mpply_plat_up_lb_check`, `HELP_DCK`, `hc_gunman`, `error`, `ProductId`, `Oscar`, `family_scene_f0`, `player_zero`, `vader`, `cuban800`, `ps3`, `xbox360`, `DeathFailOut`, `hc_hacker`, `hc_driver`, `CHAR_DEFAULT`, `<C>`, `</C>`, `net_cloud_mission_loader`, `CELL_219`, `stretch`, `superd`, `stunt`, `pony2`, `benson`, `Trevor`, `PROPERTY_PURCHASE_MEDIUM`, `DEFAULT_SCRIPTED_CAMERA`, `dune`

---

Source: `decompiled_scripts/main.c`
