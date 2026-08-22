# Shower

**Source:** `ob_mp_shower_med.c` (2.0M)

Dicts `ANIM@MP_YACHT@SHOWER@MALE@` and `@FEMALE@`:

- `male_shower_enter_into_idle`
- `male_shower_idle_a` through `_d`
- `Male_Shower_Exit_To_Idle`, `Male_Shower_Exit_To_Idle_PROP_DOOR`
- Female set uses `shower_enter_into_idle`, `shower_idle_a`/`_b`,
  `shower_Exit_To_Idle`, `Shower_Exit_To_Idle_PROP_DOOR`

Also `mp_safehouseshower@male@`. Prop `p_mp_showerdoor_s`.

The most camera-heavy `ob_*` script: 4 `CREATE_CAMERA` and 13 `SET_CAM_PARAMS`
calls drive a slow pan. Budget real time for the camera work if porting.
