# fm_content_club_management.c

MP freemode script. 5 anim dicts; 3 models; 2 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 509,618 |
| Functions | 10,668 (398 unique, 10,270 shared) |
| Unique lines | 13,544 (2.7% of file) |

## Assets

**Animation dictionaries** (5) - `anim@door_trans@hinge_l@`, `weapons@projectile@sticky_bomb`, `anim@GangOps@Morgue@Office@Laptop@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@heeled@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@male@`

**Models and props** (3) - `bkr_prop_clubhouse_laptop_01a`, `hei_prop_hst_usb_drive`, `ch_prop_ch_casino_shutter01x`

**Audio banks** (1) - `SCRIPT/ALARM_KLAXON_04`

**Sounds** (10) - `dlc_h4_Prep_FC_Sounds`, `Barge_Door`, `DLC_SECURITY_TAIL_AND_DESTROY_Sounds`, `Barge_Door_Metal`, `Explosion_Internal`, `Attach`, `GTAO_Bomb_Plant_Sounds`, `Explosion_External`, `PICKUP_DEFAULT`, `HUD_FRONTEND_STANDARD_PICKUPS_SOUNDSET`

**Particle effects** (2) - `scr_tn_tr`, `scr_tn_tr_door_smoke`

**Text labels** (2) - `SM2TOAU`, `28CTZ635`

**Timecycle modifiers** (1) - `DLC_mpSum2_Basement_Entity3`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (112), `SET_PED_COMPONENT_VARIATION` (23), `NET_TO_ENT` (16), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (11), `GET_SYNCHRONIZED_SCENE_PHASE` (10), `IS_STRING_NULL_OR_EMPTY` (10), `SET_BIT` (9), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (9), `PLAYER_PED_ID` (8), `DISABLE_CONTROL_ACTION` (7), `GET_ENTITY_COORDS` (6), `CLEAR_PED_TASKS` (6), `GET_RANDOM_INT_IN_RANGE` (5), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (5), `IS_SYNCHRONIZED_SCENE_RUNNING` (5), `PLAY_SOUND_FRONTEND` (4), `SET_PED_CONFIG_FLAG` (4), `INT_TO_PARTICIPANTINDEX` (4), `GET_CURRENT_PED_WEAPON` (4), `SET_CURRENT_PED_WEAPON` (4), `HIDE_HUD_COMPONENT_THIS_FRAME` (4), `DOES_ENTITY_EXIST` (3), `NETWORK_GET_PLAYER_INDEX` (3), `NETWORK_IS_PARTICIPANT_ACTIVE` (3), `PLAY_SOUND_FROM_COORD` (3), `GET_ENTITY_MODEL` (3), `IS_ENTITY_PLAYING_ANIM` (3), `SET_ENTITY_VISIBLE` (3), `SHAKE_GAMEPLAY_CAM` (3), `REQUEST_SCRIPT_AUDIO_BANK` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.6f` x2 · `0.99f` x2 · `0.5f` x2 · `0.4f` x2 · `0.25f` x1 · `0.377f` x1 · `0.12f` x1 · `0.152f` x1 · `0.26f` x1 · `-0.5f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `typ`, `ibs`, `sprt`, `hclr`, `scl`, `bsa`, `rad`, `name`, `MPSUM2_NCLUB_MED_INTENSITY`, `MPSUM2_NCLUB_SUSPENSE`, `blp`, `veh`, `rot`, `FMCOT_GOTO`, `MAX_NUM_SCENARIOS`, `grp`, `fcr2`, `BTL_TONY`, `GTAO_Security_Cameras_Sounds`, `MPSUM2_NCLUB_DELIVERING_START`, `MPSUM2_NCLUB_DELIVERING`, `BBOT_LOSECOPS`

---

Source: `decompiled_scripts/fm_content_club_management.c`
