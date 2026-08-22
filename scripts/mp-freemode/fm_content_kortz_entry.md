# fm_content_kortz_entry.c

MP freemode script. 20 anim dicts; 10 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 528,252 |
| Functions | 11,515 (818 unique, 10,697 shared) |
| Unique lines | 22,212 (4.2% of file) |

## Assets

**Animation dictionaries** (20) - `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@heeled@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@door_trans@hinge_l@`, `anim@scripted@heist@ig6_explosive_plant@male@`, `anim@scripted@freemode@ig3_hold_up_phone@male@`, `anim@gangops@facility@servers@bodysearch@`, `anim@scripted@player@freemode@ig6_stash_entry@door_trans@hinge_l@`, `anim_heist@hs3f@ig12_change_clothes@`, `anim@door_trans@gates@hinge_r@`, `anim@heists@ornate_bank@thermal_charge`, `anim@scripted@avi5@fib_finale_busted@heeled@`, `anim@scripted@avi5@fib_finale_busted@male@`, `amb@prop_human_seat_chair@female@arms_folded@exit`, `amb@prop_human_seat_chair@male@generic@exit`, `amb@prop_human_seat_chair@female@arms_folded@base`, `amb@prop_human_seat_chair@male@generic@base`, `anim@scripted@heist@ig13_jailor_key_turn@generic@male@`, `anim@scripted@tycoon@bt1@ig3_lckp_alt@male@`, `anim@scripted@freemode@bounty_ig_plant_bomb_tower@heeled@`, `anim@scripted@freemode@bounty_ig_plant_bomb_tower@male@`

**Animations** (3) - `cover_eyes_loop`, `cover_eyes_exit`, `cover_eyes_intro`

**Models and props** (10) - `v_ilev_rc_door2`, `s_m_m_security_01`, `v_ilev_garageliftdoor`, `g_m_m_genthug_01`, `prop_phone_ing`, `s_m_m_warehouse_01`, `s_f_m_warehouse_01`, `s_m_y_westsec_01`, `s_m_y_westsec_02`, `s_m_m_subcrew_01`

**Audio banks** (1) - `ALARM_KLAXON_04`

**Sounds** (9) - `Barge_Door`, `dlc_h4_Prep_FC_Sounds`, `Clothes_Swap`, `GTAO_Change_Outfit_Sounds`, `Drone_Scan_Complete`, `DLC_24-2_Penthouse_Robbery_Sounds`, `Scan_Progress`, `Kick_Door_Metal`, `GTAO_XM3_FRM_IG6_STASH_ENTRY_Door_Breach_Kick`

**Texture dicts** (2) - `helicopterhud`, `hud_outline`

**Decorators** (1) - `FMCVehicle`

**Vehicle mods** (1) - `terbyte`

**Hashed names** (2) - `apa_mp_h_stn_chairarm_12`, `apa_mp_h_stn_chairstool_12`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (115), `SET_PED_COMPONENT_VARIATION` (28), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (22), `NET_TO_ENT` (20), `SET_BIT` (20), `GET_ENTITY_COORDS` (18), `TO_FLOAT` (17), `SET_ENTITY_VISIBLE` (15), `IS_STRING_NULL_OR_EMPTY` (14), `DOES_ENTITY_EXIST` (13), `NETWORK_GET_PLAYER_INDEX` (12), `GET_PLAYER_WANTED_LEVEL` (11), `DISABLE_CONTROL_ACTION` (11), `REGISTER_ENTITY_FOR_CUTSCENE` (11), `REMOVE_ANIM_DICT` (10), `DOES_BLIP_EXIST` (9), `SET_PED_PROP_INDEX` (8), `SET_PED_COMBAT_ATTRIBUTES` (8), `GET_DISTANCE_BETWEEN_COORDS` (7), `IS_ENTITY_PLAYING_ANIM` (7), `CLEAR_BIT` (7), `PLAYER_PED_ID` (6), `IS_ENTITY_AT_COORD` (6), `GET_HASH_KEY` (6), `GET_SYNCHRONIZED_SCENE_PHASE` (6), `SET_ENTITY_COORDS` (6), `NET_TO_PED` (6), `IS_ENTITY_VISIBLE` (6), `CREATE_MODEL_HIDE` (5), `REMOVE_MODEL_HIDE` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-999.561f` x4 · `139.3308f` x4 · `-48.85f` x4 · `-52.65f` x4 · `748.711f` x2 · `-999.409f` x2 · `-45.823f` x2 · `0.8f` x2 · `-47.38f` x2 · `-47.375f` x2 · `-776.3242f` x2 · `611.2659f` x2 · `-775.6423f` x2 · `610.6493f` x2 · `-2294.979f` x2 · `-47.76f` x2 · `0.99f` x2 · `0.04f` x2 · `559.998f` x2 · `-2697.623f` x2 · `564.111f` x2 · `-2706.633f` x2 · `-49.224f` x2 · `566.96f` x2

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `ibs`, `int`, `typ`, `sprt`, `hclr`, `scl`, `rot`, `bsa`, `rad`, `MP261_DELIVERING_START`, `MP261_MED_INTENSITY`, `MP261_GUNFIGHT`, `MP261_DELIVERING`, `MP261_VEHICLE_ACTION`, `blp`, `veh`, `Bounty_Female_Heels`, `Bounty_Male`, `Bounty_Female_Flats`, `tun_prep_grab_midd_ig3`, `MP261_SUSPENSE`, `charge_cam_left`, `charge_player1`, `KEKC_OBJ_STEAL`

---

Source: `decompiled_scripts/fm_content_kortz_entry.c`
