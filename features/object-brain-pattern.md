# The object brain pattern

**Read in full:** `ob_airdancer.c`, `ob_abattoircut.c`, `ob_foundry_cauldron.c`,
`ob_abatdoor.c`, `ob_poledancer.c`, `ob_cashregister.c`, `ob_mp_bed_low.c`,
`ob_mr_raspberry_jam.c`

Every one of the 26 `ob_*` scripts is the same skeleton with a different middle.
Learn it once and all 26 become readable. This is the highest-value structure in
the corpus for FiveM work, because it is small, self-contained, and prop-triggered.

## The skeleton

Every brain does this, in this order:

1. **Bail if force-cleaned.** `HAS_FORCE_CLEANUP_OCCURRED(n)` at the top, jump
   straight to the terminate function. The flag differs per script (2 for simple
   world props, 16 and 19 for the safehouse activities).
2. **Freeze the prop.** `FREEZE_ENTITY_POSITION(obj, true)` so physics cannot drift
   it while the brain owns it.
3. **Loop forever** on `WAIT(0)`.
4. **Two guards, every frame.** `DOES_ENTITY_EXIST(obj)` and
   `IS_OBJECT_WITHIN_BRAIN_ACTIVATION_RANGE(obj)`. Failing either terminates the
   thread — brains do not idle, they die and get respawned by the brain system.
5. **A `switch` on one state integer.** States run 0..N, each advancing by assigning
   the next value.
6. **A single terminate function.** Deletes created objects, stops looped particles,
   `REMOVE_ANIM_DICT`, releases audio banks, then `TERMINATE_THIS_THREAD()`.

The object the brain is attached to arrives as **script parameter 0**. That is the
whole binding mechanism.

## What changes between them

Only the middle. Three families:

**Play a looping animation on the prop.** The simplest form. `ob_airdancer.c` is
about 50 lines of real code: request `map_objects`, play `airdancer_test` on the
entity with the loop flag set, move to a dead state and idle forever. Nothing else.
`ob_abattoircut.c` is identical with `MISSMIC2` / `beefsplitter_loop`.

**Run a looped particle effect.** `ob_foundry_cauldron.c` waits for a valid, ready
interior and an active interior scene, finds its target prop by
`GET_CLOSEST_OBJECT_OF_TYPE` around a hardcoded point, then starts
`scr_obfoundry_cauldron_steam` looped on it.

**Run a player interaction.** The beds and the safehouse activities. These are much
larger and use synchronised scenes; see [beds](beds.md) and
[safehouse-drinking](safehouse-drinking.md).

## Gating on other scripts

Brains coordinate with missions by counting threads:

    GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH(joaat("michael2")) > 0

`ob_abattoircut.c` and `ob_abatdoor.c` only run while `michael2` is active.
`ob_foundry_cauldron.c` inverts it — it runs only while `finalec1` is **not**
running, so the steam stops during the finale.

For FiveM this maps cleanly onto checking whether your own state resource says an
event is active, and it is a better pattern than the usual global flag because the
brain terminates rather than idling.

## The guard that matters

`DOES_ENTITY_HAVE_DRAWABLE(obj)` is checked before animating in every brain that
animates a map prop. A map object can exist as a handle before its model is
streamed in; animating it in that window silently does nothing. This is the kind of
detail that costs an afternoon if you do not know it.

## Porting notes

The activation-range check is the part with no direct FiveM equivalent. The usual
substitutes:

- a distance check in a throttled loop, cheapest and closest in spirit
- `od_interact` / `ox_target` model registration, which gets you the prompt for free

The terminate-on-leave behaviour is worth keeping either way. It is why these
scripts cost nothing when the player is elsewhere.

## Reading order

If you want to learn this, read them smallest first:

| Script | Unique lines | What it teaches |
|---|---:|---|
| `ob_airdancer.c` | 54 | The bare skeleton |
| `ob_abattoircut.c` | 55 | Skeleton plus mission gating |
| `ob_foundry_cauldron.c` | 93 | Looped particles, interior guards |
| `ob_abatdoor.c` | 117 | [Animated collision](animated-door-collision.md) |
| `ob_cashregister.c` | 111 | Breakable prop, cash spawning |
| `ob_poledancer.c` | 151 | Ambient performer, de-synced loops |
| `ob_mp_bed_low.c` | 332 | Full synchronised-scene interaction |

All seven together are under 900 lines.
