# Animated props and their collision

**Source:** `ob_abatdoor.c` (117 unique lines, read in full)

A small script that solves a problem most people hit the first time they animate a
map object: **the visual moves and the collision does not.**

## The problem

`PLAY_ENTITY_ANIM` moves what you see. The physics shape stays where the object was
authored. Animate a roller door open and the player still walks into an invisible
wall.

## What Rockstar does

The abattoir door brain runs a two-object trick:

1. On activation it requests a **collision-only prop** — a model whose name ends in
   `_col`, here `p_abat_roller_1_col` — and creates it at the door's own coordinates
   and rotation, captured once at startup before anything moves.
2. When the door should open, it plays the door animation on the *visual* map object.
3. In the next state it **manually moves the collision prop** toward a target offset
   `3.45m` along local X, stepping it each frame by direction × `GET_FRAME_TIME()` ×
   `0.35`, until it arrives within `0.1m`.
4. On arrival it sets a global flag so the rest of the mission knows the door is
   open, and drops into a dead state.
5. Cleanup deletes the collision prop and releases the model.

So the animation and the collision are two separate objects moved by two separate
mechanisms, hand-synchronised by tuning the lerp speed to match the clip.

## Why it is worth knowing

The technique generalises to anything animated that the player must be able to walk
through or stand on: gates, shutters, lifts, drawbridges, ramps.

The speed constant is the fragile part. `0.35` is not derived from the animation —
it is tuned so the collision arrives at roughly the same time the clip finishes.
Change the animation and the two drift apart. If you port this, prefer driving the
collision position from the animation phase rather than a fixed rate, so the two
cannot desynchronise.

## FiveM notes

The `_col` variants are shipped game models, so a collision proxy needs no custom
assets. Worth checking whether a `_col` model exists for the prop you are animating
before building anything.

The frame-time stepping is already the right shape for a client-side loop. The part
needing thought is ownership: this runs as a single-player brain with one authority.
Networked, either the object needs a designated owner or every client needs to run
the same deterministic lerp from a shared start time.

## Related

- [object-brain-pattern](object-brain-pattern.md) — the skeleton this sits in
- [../reference/doors](../reference/doors.md) — the door system, for doors that are
  actually registered as doors rather than animated props
