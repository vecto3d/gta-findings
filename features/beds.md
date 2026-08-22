# Beds and sleeping

**Source:** `ob_mp_bed_low.c`, `ob_mp_bed_med.c`, `ob_mp_bed_high.c`

Dict `mp_bedmid`:

- `f_getin_l_bighouse` — get in, left side
- `f_sleep_l_loop_bighouse` — sleep loop
- `f_getout_l_bighouse` — get out
- The high-end bed adds `_r` variants, so the side can match the approach

No cameras, no scaleform. The simplest object interaction in the set and the
closest thing to a direct copy of the vending machine skeleton: walk to an
offset, play enter, loop, play exit. Swap the prop attach for a fade and a sleep
timer.
