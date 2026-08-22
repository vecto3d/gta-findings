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


## Read notes

`ob_mp_shower_med.c` is 2,424 unique lines, but most of it is a **dispatch table,
not mechanics**. The bulk resolves which shower door prop to grab for the property
the player is standing in, by testing a room hash and then calling
`GET_CLOSEST_OBJECT_OF_TYPE` at hardcoded coordinates.

Door models it selects between: `p_mp_showerdoor_s`, `apa_p_mp_h_showerdoor_s`,
`ex_p_mp_h_showerdoor_s`, `xs_prop_arena_showerdoor_s`. Room keys include
`Apart_Bathroom_Room` and `Apart_Spare_Bath_Rm`.

The interaction itself is the ordinary synchronised-scene pattern documented in
[beds](beds.md), with two differences worth noting:

- Blend-in is `1000.0` — effectively instant, because the player is already in place
  behind a closed door rather than walking in. Blend-out is `-8.0`.
- Phase thresholds for the stage transitions are **read from globals** rather than
  written as literals, so several scripts share one set of timings.

So there is no new technique here. If you want a shower, copy the bed and replace
the location lookup with your own.
