# Animation alignment and interrupt points

Two natives that solve problems normally solved by hand-tuning. Both were found by
reading `ob_mp_bed_low.c` and `ob_mr_raspberry_jam.c`. Neither is visible to a
string search, because the interesting part is how they are used, not what they are
called.

## Where should the ped stand?

The usual approach to an interaction animation is to pick an offset from the prop by
trial and error, walk the ped there, and nudge the number until the animation stops
clipping. The vending machine port in this repo uses `0.0, -0.97, 0.05`, arrived at
by testing.

The beds do not guess. They ask the animation:

    GET_ANIM_INITIAL_OFFSET_POSITION(dict, anim, sceneOrigin, sceneRot, 0f, 2)
    GET_ANIM_INITIAL_OFFSET_ROTATION(dict, anim, sceneOrigin, sceneRot, 0f, 2)

Given the scene origin and rotation an animation will play at, these return the
exact position and heading the ped must already be at for the first frame to line
up. `ob_mp_bed_low.c` takes the returned position, takes the Z rotation as the
heading, and feeds both straight into the walk:

    TASK_GO_STRAIGHT_TO_COORD(ped, alignedPos, 1f, 5000, alignedHeading, 0.05f)

Then it waits for the task to end and starts the synchronised scene. No offsets are
hardcoded anywhere in the approach.

**Why this matters for a port.** Any animation you place by hand has to be retuned
for every variant — every bed side, every machine model, every character. Asking the
animation removes that entirely, and it is correct the first time.

## When may the player break out?

Rockstar's animations carry embedded event tags. `ob_mr_raspberry_jam.c` reads one:

    FIND_ANIM_EVENT_PHASE(dict, anim, "WalkInterruptible", &start, &end)

That returns the phase window, as two floats between 0 and 1, during which the
authored animation says it is safe to walk away. The script polls the scene phase
each frame and only allows an interrupt while the phase falls inside that window.

Compare with the vending machine, where the stop point was found by putting a debug
readout on screen and testing values until one looked right — five rounds to settle
on `0.55`. The event tag would have given the answer directly, and would stay
correct across every clip that carries the tag.

`WalkInterruptible` is the tag used by the safehouse activities. Other clips carry
other tags; the native takes any tag name and reports whether it exists.

## The interrupt itself

Worth copying as well. The safehouse activities do not watch for a keypress to break
out — they watch the movement stick, and treat any deflection past a threshold of
about 64 on either axis as intent to leave. Once tripped, a flag latches and the
script exits at the next interruptible window rather than immediately, so the break
always lands on an authored transition.

That combination — latch the intent, act on it only inside the tagged window — is
why the exits look clean in game and why a naive "clear tasks on input" port looks
janky.

## Related

- [sync-scenes](sync-scenes.md) — the scene system these run on
- [../features/beds](../features/beds.md) — full worked example
- [../features/vending-machine](../features/vending-machine.md) — the hand-tuned
  version, and what it cost
