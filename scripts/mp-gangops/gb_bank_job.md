# gb_bank_job.c

MP gang ops script. 4 anim dicts; 12 models; 5 scaleforms.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 193,459 |
| Functions | 2,487 (203 unique, 2,284 shared) |
| Unique lines | 7,383 (3.8% of file) |

## Assets

**Animation dictionaries** (4) - `anim@heists@ornate_bank@hostages@ped_a@`, `anim@heists@ornate_bank@hostages@cashier_a@`, `anim@heists@ornate_bank@hostages@ped_e@`, `anim@heists@ornate_bank@hostages@ped_c@`

**Models and props** (12) - `s_m_y_cop_01`, `u_m_y_gunvend_01`, `a_f_y_business_02`, `s_m_y_sheriff_01`, `s_m_m_security_01`, `s_m_m_armoured_01`, `hei_prop_heist_sec_door`, `a_m_y_business_03`, `ex_prop_exec_crashedp`, `a_f_y_business_04`, `s_m_m_movalien_01`, `ba_prop_battle_bag_01b`

**Audio banks** (1) - `SCRIPT/ALARM_BELL_02`

**Sounds** (8) - `MP_CCTV_SOUNDSET`, `DLC_BTL_Bank_Job_General_Scene`, `Change_Cam`, `Bell_02`, `ALARMS_SOUNDSET`, `Background`, `Pan`, `Zoom`

**Scaleform movies** (5) - `BANK_JOB_LOGIN`, `SECURITY_CAM`, `SET_LOCATION`, `SET_DETAILS`, `SET_TIME`

**Text labels** (4) - `COP`, `NULL`, `PAIGE`, `PAIFMAU`

**Relationship groups** (1) - `COP`

**Timecycle modifiers** (2) - `CAMERA_secuirity_FUZZ`, `CAMERA_secuirity`

**Doors** (1) - `hei_prop_hei_bankdoor_new`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (69), `SET_PED_COMPONENT_VARIATION` (55), `PLAYER_PED_ID` (45), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (31), `SET_PED_SPHERE_DEFENSIVE_AREA` (28), `NET_TO_ENT` (25), `GET_SCRIPT_TASK_STATUS` (20), `IS_ENTITY_DEAD` (18), `SET_VEHICLE_DOOR_OPEN` (15), `PARTICIPANT_ID_TO_INT` (14), `PARTICIPANT_ID` (14), `NET_TO_PED` (13), `SET_PED_CONFIG_FLAG` (13), `SET_BIT` (13), `CLEAR_HELP` (10), `TRIGGER_MUSIC_EVENT` (9), `IS_ENTITY_IN_ANGLED_AREA` (9), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (8), `SET_PED_DEFAULT_COMPONENT_VARIATION` (8), `GET_ENTITY_COORDS` (8), `GET_PLAYER_WANTED_LEVEL` (8), `DOES_BLIP_EXIST` (7), `SET_ENTITY_HEALTH` (7), `GET_PED_INDEX_FROM_ENTITY_INDEX` (7), `CLEAR_BIT` (7), `SET_VEHICLE_SIREN` (6), `SET_ENTITY_CAN_BE_DAMAGED_BY_RELATIONSHIP_GROUP` (6), `SET_PED_ACCURACY` (6), `NET_TO_OBJ` (6), `IS_ENTITY_A_PED` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`106.405f` x8 · `1.5f` x3 · `259.983f` x2 · `215.247f` x2 · `259.088f` x2 · `212.806f` x2 · `258.202f` x2 · `204.101f` x2 · `260.643f` x2 · `203.205f` x2 · `0.1f` x2 · `1.8f` x2 · `0.25f` x1 · `-1222.044f` x1 · `-317.588f` x1 · `34.58566f` x1 · `-1236.875f` x1 · `-332.1597f` x1 · `40.31116f` x1 · `944.5648f` x1 · `-1831.86f` x1 · `29.1916f` x1 · `929.4858f` x1 · `-1814.017f` x1

## Other strings

Literals whose consuming native was not classified:

`hc_gunman`, `idle`, `rumpo3`, `MBBJ_HACKHELPa`, `police3`, `FIRING_PATTERN_FULL_AUTO`, `CODE_HUMAN_MEDIC_KNEEL`, `speedo`, `MBBJ_HACKHELPc`, `BK_OVER`, `sheriff`, `DisableFlightMusic`, `WantedMusicDisabled`, `BTL_MUSIC_STOP`, `MBBJ_BMT_START`, `MBBJ_HACKHELPb`, `MBBJ_HACKHELPd`, `HACK_WORK_END`, `MBBJ_DELIVER`, `MBBJ_GOTO_FB`, `MBBJ_CAM_DUM1b`, `MBBJ_CAM_DUM1a`, `BTL_FAIL`, `WORLD_HUMAN_DRUG_DEALER_HARD`, `BTL_IDLE_START`, `BTL_SUSPENSE`, `BTL_MED_INTENSITY`, `BTL_GUNFIGHT`, `BTL_VEHICLE_ACTION`, `BTL_DELIVERING`

---

Source: `decompiled_scripts/gb_bank_job.c`
