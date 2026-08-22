# Door system

`ADD_DOOR_TO_SYSTEM` — **1493 call sites**. Also `am_doors.c` (104K).

The door system handles locking, auto-open ranges and network sync, so it is
worth using instead of hand-rolling door locks.

## Registered gate and door models

`prop_gar_door_03_ld`, `prop_com_gar_door_01`, `prop_hw1_03_gardoor_01`,
`prop_facgate_01`, `prop_facgate_01b`, `prop_lrggate_01_l`, `prop_lrggate_01_r`,
`prop_arm_gate_l`, `prop_bh1_03_gate_l`, `prop_bh1_03_gate_r`,
`prop_bh1_48_gate_1`, `prop_fnclink_03gate5`, `prop_abat_slide`,
`hei_prop_hei_bankdoor_new`.

Related sound set `GTAO_Script_Doors_Faded_Screen_Sounds` (4497 uses) and
`MP_PROPERTIES_ELEVATOR_DOORS` (592).

Vehicle door locking is separate: `SET_VEHICLE_DOORS_LOCKED_FOR_ALL_PLAYERS`
(18680), `SET_VEHICLE_DOORS_LOCKED` (13103),
`SET_VEHICLE_DOORS_LOCKED_FOR_PLAYER` (5955).
