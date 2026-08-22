# am_mp_property_ext.c

Properties and venues script. 5 anim dicts; 118 models.

| | |
|---|---|
| Category | Properties and venues |
| Total lines | 413,364 |
| Functions | 6,990 (294 unique, 6,696 shared) |
| Unique lines | 39,981 (9.7% of file) |

## Assets

**Animation dictionaries** (5) - `anim@apt_trans@hinge_l`, `mp_doorbell`, `ANIM@APT_TRANS@BUZZER`, `anim@apt_trans@hinge_r`, `anim@apt_trans@garage`

**Models and props** (118) - `prop_forsale_dyn_01`, `prop_ss1_mpint_garage`, `v_ilev_csr_garagedoor`, `prop_dummy_car`, `prop_barrier_work06a`, `PROP_GAR_HEI_WOH`, `PROP_APT_HEI_WOH`, `PROP_OFF_HEI_WOH`, `hei_prop_bh1_08_hdoor`, `prop_bh1_44_door_01r`, `prop_sm1_11_doorl`, `prop_kt1_10_mpdoor_r`, `prop_fnclink_02gate3`, `prop_ql_revolving_door`, `prop_cons_plank`, `PROP_OFF_M_11`, `PROP_OFF_M_13`, `PROP_HEI_E_3`, `prop_bh1_44_door_01l`, `prop_sm1_11_doorr`, `prop_ss1_05_mp_door`, `prop_kt1_10_mpdoor_l`, `prop_kt1_06_door_r`, `ex_prop_door_maze2_ent_r`, `PROP_OFFGS_M_11`, `PROP_OFFG_M_11`, `PROP_CLU_M_11`, `PROP_HEI_E_0b`, `PROP_OFFGS_M_13`, `PROP_OFFG_M_13`, `PROP_CLU_M_13`, `PROP_HEI_E_2b`, `PROP_HEI_I_3b3`, `PROP_HEI_I_CL2`, `PROP_HEI_I_3b1`, `PROP_OFF_M_2`, `PROP_OFFG_SHOPb`, `PROP_OFF_M_3`, `PROP_HEI_E_0`, `PROP_HEI_E_2`, `PROP_OFFG_SHOP`, `apa_prop_ss1_mpint_door_l`, `apa_prop_ss1_mpint_door_r`, `apa_prop_ss1_mpint_garage2`, `hei_prop_dt1_20_mp_gar2`, `hei_prop_sm_14_mp_gar2`, `hei_prop_bh1_09_mp_gar2`, `prop_bh1_08_mp_gar`, `prop_ss1_08_mp_door_l`, `prop_sm1_11_garaged`, `hei_prop_sync_door_06`, `ex_prop_door_lowbank_ent_r`, `ex_prop_door_lowbank_roof`, `ex_prop_door_maze2_rf_l`, `ex_prop_door_arcad_ent_l`, `ex_prop_door_arcad_roof_r`, `ex_prop_door_maze2_roof`, `prop_forsale_dyn_02`, `PROP_BLOCK_1`, `PROP_BLOCK_2` ...

**Audio banks** (1) - `DLC_IMPORTEXPORT/GARAGE_ELEVATOR`

**Sounds** (38) - `HUD_FREEMODE_SOUNDSET`, `DLC_Biker_Clubhouse_Enter_In_Vehicle_Scene`, `DLC_MPHEIST_DRIVE_INTO_GARAGE_SCENE`, `DLC_IE_Garage_Elevator_Enter_Scene`, `SELECT`, `EXEC1_Enter_Office_From_Ground_Scene`, `EXEC1_Enter_Office_From_Roof_Scene`, `PUSH`, `LIMIT`, `GTAO_APT_DOOR_ROOF_METAL_SOUNDS`, `GTAO_APT_DOOR_DOWNSTAIRS_GLASS_SOUNDS`, `DLC_IE_Garage_Elevator_Sounds`, `DOOR_Intercom_MASTER`, `DOOR_BUZZ`, `MP_PLAYER_APARTMENT`, `GTAO_APT_DOOR_DOWNSTAIRS_WOOD_SOUNDS`, `GTAO_APT_DOOR_DOWNSTAIRS_GENERIC_SOUNDS`, `EXEC1_Enter_Office_From_Heli_Scene`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `CANCEL`, `hold`, `GTAO_Script_Doors_Sounds`, `NAV_UP_DOWN`, `Click_Fail`, `WEB_NAVIGATION_SOUNDS_PHONE`, `DOOR_BUZZ_ONESHOT_MASTER`, `WOODEN_DOOR_OPEN_NO_HANDLE_AT`, `EXEC1_Enter_Office_From_Heli_Fade_To_Black_Scene`, `OK`, `GARAGE_DOOR_SCRIPTED_CLOSE`, `Engine_Revs`, `DLC_HEISTS_GENERIC_SOUNDS`, `Elevator_Doors_Opening_Loop`, `Garage_Door_Open_Loop`, `Elevator_Doors_Closing_Loop`, `Garage_Door_Close_Loop`, `Speech_Going_Up`, `GARAGE_DOOR_SCRIPTED_OPEN`

**Text labels** (11) - `PROP3RDDIS`, `BRSHETPROSUB1`, `NULL`, `NONE`, `BRSCRWTEX`, `BRDISPROP2B1`, `BRDISPROPB1`, `BRSHETMAK`, `BRSHETPRSA`, `EXHELAU`, `PROPNOTRANS`

**Decorators** (7) - `MPBitset`, `Player_Vehicle`, `Heist_Veh_ID`, `CreatedByPegasus`, `HeliTaxi`, `Veh_Modded_By_Player`, `PV_Slot`

**Interiors and entity sets** (1) - `hei_dt1_02_carpark`

**Vehicle mods** (1) - `granger`

**Scripts launched** (4) - `am_mp_property_int`, `appmpjoblistnew`, `appjipmp`, `am_heli_taxi`

**Hashed names** (1) - `S_M_M_HighSec_01`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (302), `SET_BIT` (256), `CLEAR_BIT` (178), `GET_HASH_KEY` (84), `DOES_ENTITY_EXIST` (80), `PLAYER_ID` (77), `GET_VEHICLE_PED_IS_IN` (67), `GET_ENTITY_MODEL` (66), `TO_FLOAT` (55), `GET_GAME_TIMER` (54), `IS_PED_IN_ANY_VEHICLE` (45), `IS_VEHICLE_DRIVEABLE` (45), `IS_ENTITY_DEAD` (35), `PLAY_SOUND_FRONTEND` (34), `GET_PED_IN_VEHICLE_SEAT` (34), `GET_ENTITY_COORDS` (33), `NETWORK_HAS_CONTROL_OF_ENTITY` (33), `IS_HELP_MESSAGE_BEING_DISPLAYED` (32), `FREEZE_ENTITY_POSITION` (32), `SET_ENTITY_ROTATION` (29), `IS_PED_INJURED` (28), `GET_SCRIPT_TASK_STATUS` (26), `CEIL` (24), `IS_PAUSE_MENU_ACTIVE` (23), `SET_ENTITY_VISIBLE` (21), `GET_ENTITY_HEADING` (21), `IS_SCREEN_FADED_OUT` (20), `DOES_CAM_EXIST` (19), `SET_ENTITY_COORDS_NO_OFFSET` (19), `SET_ENTITY_COORDS` (18)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x16 · `0.153f` x6 · `2.25f` x4 · `0.02f` x4 · `-935.1886f` x4 · `-378.4521f` x4 · `1.6f` x3 · `0.25f` x3 · `-145.7487f` x3 · `-580.9215f` x3 · `31.6066f` x3 · `-935.04f` x3 · `-378.36f` x3 · `39.18f` x3 · `-931.625f` x2 · `-385.063f` x2 · `37.763f` x2 · `-1295.462f` x2 · `453.962f` x2 · `96.359f` x2 · `0.1f` x2 · `0.2f` x2 · `1.5f` x2 · `3.5f` x2

## Other strings

Literals whose consuming native was not classified:

`MP_PROP_IVD_VEH`, `DEFAULT_SCRIPTED_CAMERA`, `BB_SELECT`, `BB_BACK`, `MP_REP_PROP_1`, `HAND_SHAKE`, `CUST_GAR_MISO`, `CUST_APT_MISO`, `CUST_OFF_MISO`, `CUST_CLU_MISO`, `-StraightIntoFreemode`, `CUST_GAR_WH`, `CUST_APT_WH`, `CUST_OFF_WH`, `CUST_CLU_WH`, `MP_PROP_IVD_VEH4`, `granger`, `PR_`, `OFFGS_M_ORG`, `PIM_DNAME`, `apa_p_mp_door_02`, `oppressor2`, `CUST_GAR_FULL`, `CUST_PROP_W`, `PPA_GEN0`, `PPA_GEN1`, `PPA_BEAST0`, `PPA_BEAST1`, `PPA_CONTRA0`

---

Source: `decompiled_scripts/am_mp_property_ext.c`
