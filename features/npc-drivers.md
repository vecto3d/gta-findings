# NPC drivers and passenger jobs

**Source:** `am_taxi.c` (6,617 unique lines), `am_boat_taxi.c`, `am_heli_taxi.c`,
`fm_content_taxi_driver.c` (13,178), `controller_taxi.c`, surveyed from unique code.

Six scripts drive NPC-chauffeur behaviour and they agree on one small recipe that is
worth copying exactly.

## The driver recipe

Every hired driver in the game gets the same three flags:

    SET_PED_CAN_BE_DRAGGED_OUT(ped, false)
    SET_PED_COMBAT_ATTRIBUTES(ped, 17, true)
    SET_PED_COMBAT_ATTRIBUTES(ped, 5, false)

Together these mean: cannot be yanked out of the seat, will not panic and abandon
the vehicle, will not flee on gunfire. Without them a hired driver bails the moment
anything goes wrong nearby, which is the single most common complaint about
home-made taxi resources.

Drivers are dressed with four `SET_PED_COMPONENT_VARIATION` calls on slots `0`, `2`,
`3` and `4` rather than left on a random outfit.

## Finding somewhere to stop

Both the taxi and the emergency-call scripts refuse to use a raw coordinate as a
destination. They snap to the road network first:

    GET_CLOSEST_VEHICLE_NODE(coords, &node, 1, 3.0, 0.0)
    GET_CLOSEST_ROAD(coords, 1.0, 1, ...)         // emergencycall.c

A drop-off derived from a node lands on drivable road. A raw coordinate strands the
vehicle on a kerb or inside geometry.

`fm_content_taxi_driver.c` marks each fare with `ADD_BLIP_FOR_RADIUS` rather than a
point blip, so the pickup reads as an area.

## Structure of the larger job scripts

`fm_content_*` delivery and taxi scripts share a **data-driven ped behaviour
system**. Assert strings left in the shipped code name its shape:

    "sPedLocal.sBehaviour[iLoop].Task[iLoop2].iNumTransitions"
    "MAX_NUM_PED_TASK_TRANSITIONS"

So each ped carries a behaviour record holding an array of tasks, each with a
transition count. The job scripts are not hand-written state machines — they are
interpreters over a table. That is why they run to thousands of unique functions
while doing conceptually simple work, and it is why reading one teaches you little
about the others.

For a FiveM port the table-driven approach is the right idea at scale, but a plain
state machine is far less code for a single job.

## Related

- [taxi](taxi.md) - the scaleform meter UI
- [../reference/task-vocabulary](../reference/task-vocabulary.md)
