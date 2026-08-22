# Coordinate transforms

**Source:** `am_mp_arcade_claw_crane.c` (2,598 unique lines), `cablecar.c`,
`ob_vend1.c`, read from unique code.

Two natives that are inverses of each other. Almost everyone knows the first. The
second is the one that removes trigonometry from a script.

## World position from a local offset

    GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS(entity, x, y, z)

"Where is a point one metre in front of this thing." Used everywhere — the vending
machine stand position is this call with a `-0.97` Y offset.

## Local offset from a world position

    GET_OFFSET_FROM_ENTITY_GIVEN_WORLD_COORDS(entity, x, y, z)

The inverse: "where is this world point, expressed in the entity's own space." The
claw crane uses it to work out where a prize sits relative to the cabinet, so the claw
can be driven in cabinet-local axes regardless of how the cabinet is rotated in the
world.

This is the call that replaces manual rotation maths. Any time you would otherwise
subtract two positions and rotate the result by an entity heading, this does it
correctly, including pitch and roll.

Useful whenever something must behave in an object frame rather than the world frame:

- is the player on the left or right side of this vehicle
- is a point inside this object footprint
- drive a moving part along an object own axes
- work out which face of a prop was approached

## Riding a moving thing

`cablecar.c` shows the companion pattern. It calls `ATTACH_ENTITY_TO_ENTITY` 19
times, `DETACH_ENTITY` 12, and guards with `IS_ENTITY_ATTACHED` 10 — passengers and
props are attached to the car, never repositioned per frame to follow it.

It scales its own motion by `TIMESTEP` and validates the player is aboard with
`IS_ENTITY_IN_ANGLED_AREA` rather than a radius, the same boarding check the
[beds](../features/beds.md) use.

**Attach, do not chase.** Chasing a moving parent per frame always jitters, because
your update and the parent update are one frame apart.

The claw crane also carries its own soundset, `dlc_ch_claw_crane_sounds`, played
positionally with `PLAY_SOUND_FROM_COORD`.

## Related

- [animation-alignment](animation-alignment.md)
- [../features/minigames-toolkit](../features/minigames-toolkit.md)
