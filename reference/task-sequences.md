# Task sequences

**Source:** `re_yetarian.c` (read in full, 1,028 unique lines), plus the sequence use
visible across all 38 random events.

`TASK_PERFORM_SEQUENCE` is the most-used AI idiom in the game — 3,239 call sites, more
than any task except leaving a vehicle. Every survey in this repo kept surfacing it.
Reading `re_yetarian.c` shows how the sequences are actually built.

## The building API

A sequence is assembled between two calls and then handed over as a unit:

    OPEN_SEQUENCE_TASK(&sequenceId)
        TASK_LOOK_AT_ENTITY(0, target, ...)      // ped arg is 0 inside a sequence
        TASK_PLAY_ANIM(0, dict, clip, ...)
        TASK_PAUSE(0, 2500)
        TASK_FOLLOW_NAV_MESH_TO_COORD(0, ...)
    CLOSE_SEQUENCE_TASK(sequenceId)

    TASK_PERFORM_SEQUENCE(ped, sequenceId)
    CLEAR_SEQUENCE_TASK(&sequenceId)

Three details that are easy to get wrong:

1. **The ped argument is `0` inside the sequence.** Tasks added between open and close
   take `0` where a ped handle would normally go — they are recorded, not executed, and
   bound to whichever ped later performs them.
2. **`CLEAR_SEQUENCE_TASK` releases the slot,** and it is called right after handing the
   sequence to the ped, not when the ped finishes. The sequence has been copied by then.
   Sequence slots are a limited resource and leaking them is a real bug.
3. **One sequence can be given to several peds.** `re_yetarian.c` builds nine sequences
   across its run and reuses them.

## Why R* prefers sequences

A sequence runs to completion without the script touching it each frame. The script
polls once:

    GET_SCRIPT_TASK_STATUS(ped, joaat("script_task_perform_sequence")) == 7

That is why the random events look like state machines with very few states — most of
the behaviour is inside sequences, not in script branching. Copying that shape makes a
FiveM AI script dramatically smaller than the usual per-frame task juggling.

## Related

- [task-vocabulary](task-vocabulary.md)
- [../features/random-events](../features/random-events.md)
