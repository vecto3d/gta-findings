# fm_content_vehrob_police.c

MP freemode script. 17 anim dicts; 37 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 563,427 |
| Functions | 11,045 (579 unique, 10,466 shared) |
| Unique lines | 25,287 (4.5% of file) |

## Assets

**Animation dictionaries** (17) - `ANIM@SCRIPTED@SUBMARINE@VEHICLE_TRANS@MOONPOOL`, `anim@apt_trans@hinge_l`, `ANIM@SCRIPTED@CAYO@IG2_DEFUSE_RADAR@MALE@`, `ANIM@SCRIPTED@SUBMARINE@VEHICLE_TRANS@HELIPAD`, `anim@amb@casino@valet@intro@`, `ANIM@SCRIPTED@HEIST@IG13_JAILOR_KEY_TURN@MALE@`, `anim@amb@warehouse@laptop@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@heeled@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@scripted@freemode@ig5_collect_weapons@male@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@heeled@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@male@`, `ANIM@SCRIPTED@CAYO@IG2_DEFUSE_RADAR@HEELED@`, `ANIM@SCRIPTED@SUBMARINE@IG26_SUBMARINE_ENTER@HEELED@`, `ANIM@SCRIPTED@SUBMARINE@IG26_SUBMARINE_ENTER@MALE@`, `ANIM@SCRIPTED@SUBMARINE@IG_27_SUBMARINE_DOOR@HEELED@`, `ANIM@SCRIPTED@SUBMARINE@IG_27_SUBMARINE_DOOR@MALE@`

**Models and props** (37) - `g_m_y_ballaorig_01`, `g_m_y_mexgoon_02`, `v_ilev_ph_cellgate`, `g_m_y_korean_02`, `g_m_y_korean_01`, `hei_prop_station_gate`, `prop_vend_soda_02`, `g_f_y_vagos_01`, `PROP_BLOCK_1`, `PROP_BLOCK_2`, `prop_monitor_01a`, `prop_off_chair_03`, `v_ilev_leath_chr`, `g_m_y_korlieut_01`, `prop_box_wood04a`, `prop_pallet_pile_01`, `prop_box_wood01a`, `prop_box_wood03a`, `prop_watercrate_01`, `prop_mb_crate_01a`, `sm_prop_smug_hgrdoors_03`, `sm_prop_smug_hgrdoors_light_a`, `sm_prop_smug_hgrdoors_light_b`, `sm_prop_smug_hgrdoors_light_c`, `sm_prop_smug_hgrground_01`, `PROP_NO_PVMOD`, `PROP_NO_WORK`, `PROP_BLOCK_TRAIL`, `v_ilev_gtdoor02`, `v_ilev_rc_door2`, `v_ilev_ph_door01`, `v_ilev_ph_door002`, `v_ilev_arm_secdoor`, `v_ilev_gtdoor`, `m23_2_prop_m32_greenlight_01a`, `s_m_m_cop_01`, `imp_prop_impexp_boxpile_02`

**Sounds** (2) - `Pickup_Keys`, `DAX_2_3_Sounds`

**Speech contexts** (1) - `XM4_CONTACT`

**Text labels** (14) - `CLEAR`, `09OAD578`, `XM4R2AU`, `22QUM874`, `66UFV929`, `00HVO073`, `00EUT645`, `00VTH379`, `42DWP748`, `60JFL965`, `00QSV659`, `21PBL328`, `83KYU186`, `86FPM269`

**Decorators** (4) - `Player_Vehicle`, `Veh_Modded_By_Player`, `MPBitset`, `PV_Slot`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (104), `PLAYER_ID` (96), `SET_BIT` (65), `SET_PED_CONFIG_FLAG` (35), `DOES_ENTITY_EXIST` (32), `CLEAR_BIT` (25), `GET_ENTITY_MODEL` (24), `REQUEST_MODEL` (23), `HAS_MODEL_LOADED` (22), `IS_PAUSE_MENU_ACTIVE` (21), `PLAYER_PED_ID` (19), `IS_HELP_MESSAGE_BEING_DISPLAYED` (18), `IS_STRING_NULL_OR_EMPTY` (16), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (15), `SET_ENTITY_INVINCIBLE` (15), `SET_PED_COMPONENT_VARIATION` (15), `IS_PED_IN_ANY_VEHICLE` (14), `REQUEST_ANIM_DICT` (14), `VMAG` (13), `HAS_ANIM_DICT_LOADED` (13), `GET_ENTITY_COORDS` (13), `NETWORK_DOES_NETWORK_ID_EXIST` (13), `GET_RANDOM_INT_IN_RANGE` (12), `SET_ENTITY_VISIBLE` (12), `GET_RANDOM_FLOAT_IN_RANGE` (12), `IS_MODEL_VALID` (11), `GET_ROOM_KEY_FROM_ENTITY` (11), `GET_PLAYER_WANTED_LEVEL` (11), `DISABLE_CONTROL_ACTION` (10), `NET_TO_PED` (10)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`25.0644f` x4 · `0.5f` x4 · `435.452f` x3 · `-986.742f` x3 · `30.642f` x3 · `0.01f` x2 · `460.8343f` x2 · `-989.0701f` x2 · `24.8236f` x2 · `459.714f` x2 · `-988.745f` x2 · `23.916f` x2 · `447.2203f` x2 · `-973.2429f` x2 · `29.6861f` x2 · `461.8065f` x2 · `-997.6583f` x2 · `464.5701f` x2 · `-992.6641f` x2 · `2.5f` x1 · `467.021f` x1 · `-1014.515f` x1 · `23.77f` x1 · `488.755f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `MP_PROP_IVD_VEH`, `int`, `ibs`, `WORLD_HUMAN_STAND_IMPATIENT`, `sprt`, `hclr`, `scl`, `rot`, `bsa`, `typ`, `name`, `WORLD_HUMAN_HANG_OUT_STREET`, `avisa`, `MP_PROP_IVD_VEH4`, `kuruma`, `fugitive`, `baller`, `buccaneer2`, `blp`, `veh`, `rad`, `speedo4`, `kosatka`, `stromberg`

---

Source: `decompiled_scripts/fm_content_vehrob_police.c`
