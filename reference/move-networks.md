# MoVE networks

Found in `am_armwrestling.c`, `am_armwrestling_apartment.c` and
`am_mp_arcade_love_meter.c`, surveyed from their unique code.

The third animation system in the game, after `TASK_PLAY_ANIM` and
[synchronised scenes](sync-scenes.md) — and the only one that reacts to input while
it plays. It is barely used in the FiveM community, mostly because nothing names it
in a way you would search for.

## What it is

A MoVE network is a **named animation state machine** shipped with the game. The
script starts one on a ped, then reads and writes its state by name while it runs.
The animation blending inside is handled by the engine.

Use it when the animation has to respond continuously — a tug of war, a drill
biting, a struggle. A synchronised scene plays a fixed clip on a timeline; a MoVE
network holds a state and transitions.

## The calls

    TASK_MOVE_NETWORK_ADVANCED_BY_NAME_WITH_INIT_PARAMS(
        ped, "Heist3_minigame_drill_vault", initParams,
        x, y, z, rx, ry, rz, blend, flags, ...)

    IS_TASK_MOVE_NETWORK_ACTIVE(ped)
    GET_TASK_MOVE_NETWORK_STATE(ped)        // returns a state name as a string
    SET_TASK_MOVE_NETWORK_ENABLE_COLLISION_ON_NETWORK_CLONE_WHEN_FIXED(ped, true)

The state readback is the important part. `am_armwrestling_apartment.c` waits for
both competitors to reach the same state before starting:

    ARE_STRINGS_EQUAL(GET_TASK_MOVE_NETWORK_STATE(pedA), "Running")
    && ARE_STRINGS_EQUAL(GET_TASK_MOVE_NETWORK_STATE(pedB), "Running")

So a MoVE network reports where it is as a plain string, and script logic branches on
that. No phase arithmetic, no guessing at thresholds.

## Networks are reused across unrelated features

The single most useful observation here. `am_mp_arcade_love_meter.c` — the arcade
love-tester cabinet — runs the network named **`Heist3_minigame_drill_vault`**.

That is the vault drilling network from the casino heist, driving a completely
unrelated novelty machine. The networks are generic input-driven animation state
machines, not tied to the feature they were authored for.

For a FiveM server this means the drilling, cutting and struggle animations already
exist as ready-made interactive systems, and can be repurposed for anything with the
same shape: a lockpick, a winch, a valve, a tug of war.

## Positioning

The advanced variant takes an explicit world position and rotation, so the network
plays at a fixed spot rather than wherever the ped happens to stand — the same
problem [animation alignment](animation-alignment.md) solves for ordinary clips.

`am_armwrestling.c` runs two peds on their own networks simultaneously and treats the
pair as one contest, which is the template for any two-player physical struggle.

## Caution

These are the least verified findings in this repo. The native names, the state
string comparison and the network name reuse are all quoted directly from the
scripts. What is **not** known is the full list of valid network names, the init
parameter layout, or the state names each network exposes. Those never appear as
literals except where a script happens to compare against one.

Discovering the rest means experimenting in game, not reading further.

## Related

- [sync-scenes](sync-scenes.md) — the fixed-timeline alternative
- [animation-alignment](animation-alignment.md)
- [../features/heist-minigames](../features/heist-minigames.md)
