# Vending machine deep dive

Part of the [GTA V decompiled script findings](README.md).

## Deep dive: vending machine (`ob_vend1.c`) — PORTED

Built as `od_vending` for the odessa server. Full flow as shipped by R*:

1. Stash weapon to unarmed and hide it, clear stealth movement,
   `CLEAR_AREA_OF_PROJECTILES` radius 3.
2. `TASK_LOOK_AT_ENTITY` 2000 ms + `TASK_GO_STRAIGHT_TO_COORD` to offset
   `{0, -0.97, 0.05}` from the machine, **forced to the machine's own heading**,
   0.1 tolerance. This alignment is why the vanilla anim never looks off-centre.
3. Wait for `GET_SCRIPT_TASK_STATUS(script_task_go_straight_to_coord) == 7`.
4. `PLYR_BUY_DRINK_PT1` (flag 1310720) — can created at **0.31** and attached to
   bone **28422**; chains to PT2 at 0.98.
5. `PLYR_BUY_DRINK_PT2` (flag 1048576) → `PLYR_BUY_DRINK_PT3` (flag 1048624).
6. Can released at **0.306 of PT3**: `DETACH_ENTITY`, then
   `APPLY_FORCE_TO_ENTITY(can, 1, {6.0, 10.0, 2.0}, ...)` — the throw — then
   `SET_OBJECT_AS_NO_LONGER_NEEDED`. **It is never deleted on success.**
7. Abort path deletes only if `IS_ENTITY_A_MISSION_ENTITY`, and **always
   detaches first**.

Timeouts: 2500 ms for the walk, 15000 ms per anim. Interrupt check is
damaged-by-any ped/vehicle/object, followed by `CLEAR_ENTITY_LAST_DAMAGE_ENTITY`.
Audio bank `VENDING_MACHINE`. Help labels `VENDHLP` / `VENDCSH`.
Early cancel uses `STOP_ANIM_TASK(..., -1.5)` — a blend-out, not a hard stop.

Machine models: `prop_vend_soda_01/02`, `prop_vend_water_01`,
`prop_vend_coffe_01`, `prop_vend_snak_01`, `prop_vend_fags_01`,
`prop_vend_condom_01`, `sf_prop_sf_vend_drink_01a` (needs a higher offset:
stand `{0,-0.97,1.0}`).

Can props (the complete set — only these exist): `prop_ld_can_01b`,
`prop_ecola_can`, `sf_prop_sf_can_01a`. Also `prop_energy_drink`,
`p_amb_coffeecup_01`, `prop_cs_paper_cup`.

**Gotchas learned the hard way:**
- An attached entity will not delete. Detach first, always.
- The soda machines share models, so which brand a machine is cannot be derived
  from the model — use a menu.
- Only `PLYR_BUY_DRINK_PT1/2/3` exist in the whole game. There is no alternate
  button-press animation; the hand path is authored data, not script-aimed.

Related tunables: `vending_machine_sprunk_can_cost`, `shop_sprunk_can_cost`,
`property_sprunk_can_cost`, `sprunk_health_replenish_multiplier`,
`po_coupon_sprunk` (free-drink coupons).

## Next candidates, ranked by reuse of the vending skeleton

1. **Beds** (`ob_mp_bed_*`) — no cameras, no scaleform. Enter → loop → exit.
2. **Cash register** (`ob_cashregister`) — tiny, reactive rather than
   interactive, different pattern.
3. **Telescope** (`ob_telescope`) — adds camera + FOV zoom + timecycle modifier +
   2 scaleforms. Sound sets `TELESCOPE_COIN_OP` / `_HIGH_END` / `_DOMESTIC`;
   the coin-op is a paid interaction.
4. **Jukebox** (`ob_jukebox`) — scaleform track menu, disabled controls.
5. **Shower** (`ob_mp_shower_med`) — 4 cameras, 13 `SET_CAM_PARAMS`. Most work.
