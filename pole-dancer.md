# Pole dancer — ambient performer template

**Source:** `ob_poledancer.c` (4K, ~170 lines)

Dict `MISSSTRIP_CLUB`, anim `Poledance_01`, ped `a_f_y_beach_01`.

The cleanest ambient-performer template in the repo:

1. Freeze the prop, read its coords and heading, disable its collision.
2. Spawn the ped there with `SET_PED_RANDOM_COMPONENT_VARIATION`,
   `SET_PED_CAN_BE_TARGETTED(false)`, `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS`.
3. Loop the anim, and call `SET_ENTITY_ANIM_CURRENT_TIME` with a random 0–1
   float so multiple performers do not move in lockstep.
4. Watch for the player getting close, shooting, or touching, then bail into
   `TASK_COWER` and `SET_ALL_RANDOM_PEDS_FLEE`.

Step 3 is the detail worth copying — it is what stops a room of dancers looking
like clones.
