# Beds and sleeping

**Source:** `ob_mp_bed_low.c` (read in full), `ob_mp_bed_med.c`, `ob_mp_bed_high.c`

Dict `mp_bedmid`:

- `f_getin_l_bighouse` — get in, left side
- `f_sleep_l_loop_bighouse` — sleep loop
- `f_getout_l_bighouse` — get out
- The high-end bed adds `_r` variants, so the side can match the approach

No cameras, no scaleform. The most complete worked example of a
[synchronised-scene interaction](../reference/sync-scenes.md) in the object brains,
and the best template to copy for any enter/loop/exit prop.

## The flow

Read from `ob_mp_bed_low.c`. The outer brain only checks proximity — under 3m to
enter, and it terminates past 5m. Everything else runs in one state machine:

| State | What happens |
|---|---|
| 0 | Player in range, in the right interior, inside the angled area, facing right. Show the `SA_BED_IN` help prompt |
| 1 | On input: clear projectiles from the area, holster to `weapon_unarmed`, take player control, compute the aligned position, walk there |
| 2 | Wait for the walk task to finish, then start the get-in scene |
| 3 | Wait for the scene to actually be running |
| 4 | Wait for scene phase past `0.9`, then start the sleep loop scene |
| 5 | Mark the loop scene looping, show `SA_BED_OUT` |
| 6 | Hold. Watch for the exit control (`222`) |
| 7 | Alternate entry used when arriving mid-switch — goes straight to the exit scene |
| 8 | Exit scene started, wait for it to run |
| 9 | Scene finished: restore control, restore HUD, reset to state 0 |

## The parts worth copying

**Do not hardcode the approach offset.** State 1 asks the animation where the ped
should be, using `GET_ANIM_INITIAL_OFFSET_POSITION` and its rotation counterpart
against the scene origin, then walks there with the returned heading. This is the
right way to do it and it is covered in
[animation-alignment](../reference/animation-alignment.md).

**Three separate scenes, not one.** Get-in, loop and get-out are each their own
synchronised scene at the same origin and rotation. The loop is made to repeat with
`SET_SYNCHRONIZED_SCENE_LOOPED`. Chaining happens on phase — the get-in hands over
at `0.9`, not at `1.0`, so the blend has somewhere to go.

**Blend values differ per clip.** Get-in blends in at `4.0`, the loop at `8.0`, the
exit at `2.0`, all blending out at `-2.0`, all with flag `261`. The faster blend
into the loop is what hides the seam.

**Position validation is an angled area, not a radius.** The script tests
`IS_ENTITY_IN_ANGLED_AREA` between two corner points with a `2.0` width. A bed has a
side; a radius check would let the player enter from the wrong one.

**The bed is networked.** It uses the `NETWORK_CREATE_SYNCHRONISED_SCENE` family
rather than the local one, so other players see the animation. For FiveM this is the
variant you want.

## Porting

This is the closest thing in the corpus to a drop-in template. The skeleton is the
same as the vending machine — walk to an offset, play enter, loop, play exit — with
the prop attach swapped for a fade and a sleep timer.

Two things to keep: the phase-based chaining, and asking the animation for the
approach position. Both are what separate this from the version most servers ship.

## Related

- [object-brain-pattern](object-brain-pattern.md) — the wrapper this runs inside
- [../reference/animation-alignment](../reference/animation-alignment.md)
- [vending-machine](vending-machine.md) — same shape, verified against a running game
