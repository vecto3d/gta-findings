# gb_gunrunning_defend.c

MP gang ops script. 1 anim dicts; 20 models; 1 scaleforms; 2 particle effects.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 190,207 |
| Functions | 2,629 (220 unique, 2,409 shared) |
| Unique lines | 16,229 (8.5% of file) |

## Assets

**Animation dictionaries** (1) - `P_cargo_chute_S`

**Animations** (3) - `P_cargo_chute_S`, `P_cargo_chute_S_crumple`, `P_cargo_chute_S_deploy`

**Models and props** (20) - `prop_generator_03b`, `prop_box_wood04a`, `imp_prop_adv_hdsec`, `gr_prop_gr_hdsec_deactive`, `prop_flare_01`, `prop_mb_crate_01a_set`, `s_m_y_blackops_02`, `p_cargo_chute_s`, `ex_prop_adv_case_sm`, `s_m_y_cop_01`, `s_f_y_cop_01`, `s_m_y_swat_01`, `s_m_m_fiboffice_01`, `s_m_y_sheriff_01`, `s_f_y_sheriff_01`, `s_m_y_ranger_01`, `s_f_y_ranger_01`, `s_m_m_armoured_01`, `s_m_y_pilot_01`, `s_m_m_fibsec_01`

**Audio banks** (1) - `ALARM_BELL_02`

**Sounds** (17) - `DLC_HEIST_BIOLAB_PREP_HACKING_SOUNDS`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `DLC_GR_Disarm_Bombs_Sounds`, `Exploding_Entity_Start`, `Exploding_Entity_Loop`, `Ctrl`, `Exploding_Entity_Stop`, `Bomb_Armed`, `Hack_Success`, `Pin_Movement`, `PinMovementY`, `Pin_Centred`, `Pin_Good`, `Pin_Bad`, `Parachute_Land`, `DLC_Exec_Air_Drop_Sounds`, `Bomb_Disarmed`

**Scaleform movies** (1) - `SET_CURSOR_VISIBILITY`

**Particle effects** (2) - `scr_gr_def_flare`, `scr_gr_def_package_flare`

**Texture dicts** (4) - `hackingNG`, `DHCompHi`, `DHComp`, `DHMain`

**Text labels** (5) - `COP`, `AGENT14`, `GNRCAUD`, `NULL`, `HACK`

**Relationship groups** (1) - `relDefendPlayer`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (185), `PLAYER_ID` (175), `PARTICIPANT_ID_TO_INT` (150), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (87), `PLAYER_PED_ID` (69), `NET_TO_PED` (60), `NET_TO_VEH` (58), `NET_TO_OBJ` (49), `CLEAR_BIT` (49), `GET_ENTITY_COORDS` (44), `DOES_BLIP_EXIST` (38), `IS_PED_INJURED` (31), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (26), `DOES_ENTITY_EXIST` (23), `REMOVE_BLIP` (23), `INT_TO_PLAYERINDEX` (21), `DRAW_SPRITE` (18), `SET_RELATIONSHIP_BETWEEN_GROUPS` (18), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (14), `GET_SCRIPT_TASK_STATUS` (14), `INT_TO_PARTICIPANTINDEX` (14), `VDIST2` (14), `NET_TO_ENT` (13), `IS_STRING_NULL_OR_EMPTY` (13), `STOP_SOUND` (13), `NETWORK_DOES_NETWORK_ID_EXIST` (12), `TRIGGER_MUSIC_EVENT` (12), `NETWORK_GET_PLAYER_INDEX` (12), `GET_RANDOM_FLOAT_IN_RANGE` (12), `RELEASE_SOUND_ID` (11)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.4f` x32 · `0.5f` x13 · `0.731f` x2 · `1.306f` x2 · `0.8f` x1 · `0.0245f` x1 · `-0.2f` x1 · `3.5f` x1

## Other strings

Literals whose consuming native was not classified:

`speedo`, `DGUN_DELTSM`, `DBR_LCOPS`, `DGUN_HDELPK`, `DGUN_DBUSIO`, `DGUN_FAIL`, `SCONTRA_TIMER`, `mp_g_m_pros_01`, `DGUN_ODEF1`, `DGUN_ODEF`, `DGUN_RTRVPROD`, `DGUN_RETPRO`, `DDGUN_PROD`, `DGUN_DBUSI`, `DisableFlightMusic`, `WantedMusicDisabled`, `pounder`, `rumpo3`, `valkyrie2`, `H1_HNG`, `H1_HNG_KM`, `DCONTRA_HLP1`, `mesa3`, `insurgent`, `mule3`, `DGUN_HDEF`, `GR_DELIVERING_START`, `GR_MP_MUSIC_STOP`, `chassis_dummy`, `GR_HELPSTEALTH`

---

Source: `decompiled_scripts/gb_gunrunning_defend.c`
