# Vending machine

**Source:** `ob_vend1.c`, `ob_vend2.c` (1.6M each, mostly shared boilerplate)
**Status:** ported as `od_vending`

Buy a drink from a machine. The most completely traced mechanic in these notes.

## Flow

1. Stash weapon to `weapon_unarmed` and hide it, clear stealth movement,
   `CLEAR_AREA_OF_PROJECTILES` radius 3.
2. `TASK_LOOK_AT_ENTITY` 2000 ms, then `TASK_GO_STRAIGHT_TO_COORD` to offset
   `{0, -0.97, 0.05}` from the machine, forced to the machine heading, 0.1
   tolerance. This alignment is why the vanilla animation never looks off-centre.
3. Wait for `GET_SCRIPT_TASK_STATUS(script_task_go_straight_to_coord) == 7`.
4. `PLYR_BUY_DRINK_PT1` (flag 1310720) — can created at **0.31** and attached to
   bone **28422**; chains to PT2 at 0.98.
5. `PLYR_BUY_DRINK_PT2` (flag 1048576) then `PLYR_BUY_DRINK_PT3` (flag 1048624).
6. Can released at **0.306 of PT3**: `DETACH_ENTITY`, then
   `APPLY_FORCE_TO_ENTITY(can, 1, {6.0, 10.0, 2.0}, ...)` which is the throw,
   then `SET_OBJECT_AS_NO_LONGER_NEEDED`. It is never deleted on success.
7. Abort path deletes only if `IS_ENTITY_A_MISSION_ENTITY`, and always detaches
   first.

Timeouts: 2500 ms for the walk, 15000 ms per animation. Interrupt check is
damaged-by-any ped/vehicle/object followed by `CLEAR_ENTITY_LAST_DAMAGE_ENTITY`.
Early cancel uses `STOP_ANIM_TASK(..., -1.5)`, a blend-out rather than a hard cut.

Audio bank `VENDING_MACHINE`. Help labels `VENDHLP` and `VENDCSH`.

## Models

Machines: `prop_vend_soda_01`, `prop_vend_soda_02`, `prop_vend_water_01`,
`prop_vend_coffe_01`, `prop_vend_snak_01`, `prop_vend_fags_01`,
`prop_vend_condom_01`, `sf_prop_sf_vend_drink_01a` (needs a higher stand offset,
`{0, -0.97, 1.0}`).

Cans, the complete set: `prop_ld_can_01b`, `prop_ecola_can`,
`sf_prop_sf_can_01a`. Also usable: `prop_energy_drink`, `p_amb_coffeecup_01`,
`prop_cs_paper_cup`.

## Gotchas

- An attached entity will not delete. Detach first, always.
- The soda machines share models, so brand cannot be derived from the model.
- Only `PLYR_BUY_DRINK_PT1/2/3` exist in the entire game. There is no alternate
  button-press clip.

Tunables: `vending_machine_sprunk_can_cost`, `shop_sprunk_can_cost`,
`sprunk_health_replenish_multiplier`, `po_coupon_sprunk` (free-drink coupons).
