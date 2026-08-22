# Cash register smash

**Source:** `ob_cashregister.c` (11K, ~170 lines)

The smallest useful script in the object set, and a different pattern from the
rest — reactive, not interactive. No animation at all.

1. Polls `HAS_OBJECT_BEEN_BROKEN` on the register prop.
2. On break, spawns cash using `GET_SAFE_PICKUP_COORDS` so it never lands inside
   geometry.

Singleplayer drops 70–120 as `pickup_money_med_bag` with model
`prop_money_bag_01`. Multiplayer drops 50–100 scaled by a global multiplier,
using `prop_cash_pile_01`.

Good store-robbery flavour with almost no code.
