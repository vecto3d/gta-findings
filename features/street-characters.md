# Street characters and performers

**Source:** all 18 `gpb_*` and `pb_*` scripts, surveyed from their unique code.
12,234 unique lines total.

Two distinct families that the shared prefix hides.

## `gpb_*` — the strangers, one template fourteen times

`andymoon`, `baygor`, `billbinder`, `clinton`, `griff`, `jane`, `jerome`, `jesse`,
`mani`, `mime`, `pameladrake`, `superhero`, `tonya`, `zombie`.

These are the shouting oddballs scattered around the map. The extraction settles
that they are **one template with the serial numbers filed off** — `gpb_clinton.c`
and `gpb_superhero.c` produce byte-identical mechanical call sets, and most of the
rest have almost no unique calls at all.

The template:

- `CREATE_PED(25, ...)` — ped type 25 for these ambient characters
- `SET_PED_COMBAT_ATTRIBUTES(ped, 17, true)`
- an `idle_intro` clip, then a looping idle from the character's own dictionary
- `PLAY_PED_AMBIENT_SPEECH_NATIVE(ped, "GENERIC_CURSE_MED", "SPEECH_PARAMS_FORCE", 1)`
  when the player crowds them
- `TASK_FOLLOW_NAV_MESH_TO_COORD` back to their spawn point if displaced
- `TASK_SMART_FLEE_PED(ped, player, 100.0, ...)` if actually threatened

The return-to-post behaviour is confirmed by a debug string R* left in:
`WAIT_MOVE_BACK_TO_INITIAL_POSITION TASK_PLAY_ANIM`. These characters own a spot and
walk back to it. That single behaviour is most of what makes them read as residents
rather than spawned props.

**Blend values are the tell.** The idle intro blends at `4.0 / -4.0`, the loop at
`2.0 / -2.0`, and the forced snap uses `1000.0 / -1000.0` — an instant cut used when
the transition must not be seen.

### Props they carry

All attached to bone `28422`, the right hand:

| Script | Prop |
|---|---|
| `gpb_baygor.c` | `prop_cs_pamphlet_01` |
| `gpb_griff.c` | `prop_cs_protest_sign_01` |
| `gpb_zombie.c` | `prop_npc_phone` |

`gpb_griff.c` also calls `SET_PED_COMPONENT_VARIATION` on slots `1` and `11` to
force a specific outfit, and `gpb_zombie.c` disables evasive dive so the character
stands its ground in traffic.

### The exception worth reading

`gpb_pameladrake.c` is the only one that does something structurally different. It
builds a walking route at runtime:

    TASK_FLUSH_ROUTE()
    TASK_EXTEND_ROUTE(x, y, z)      // repeated per waypoint
    TASK_FOLLOW_POINT_ROUTE(ped, 1.0, 0)

A complete patrol path in a handful of calls, with no state machine and no distance
polling. Most FiveM patrol implementations rebuild this by hand with a table of
coordinates and a per-frame check. It already exists.

It also spawns a companion `a_m_m_business_01` who walks the route alongside.

## `pb_*` — the performers

Smaller, and each genuinely distinct. All follow a spawn-performer, spawn-audience
shape.

**`pb_busker.c`** — dictionary `amb@BUSKER`, alternating between `SAX_loop_A` and
`SAX_loop_B` chosen at random so repeat visits differ. Spawns an audience ped
(`a_f_m_bevhills_02`) and turns it to face the performer with
`TASK_TURN_PED_TO_FACE_COORD`. Blend `8.0 / -8.0` throughout, which is the standard
for a loop that must not pop.

**`pb_preacher.c`** — dictionary `amb@PREACHER`, clip `PREACH`, performer model
`s_m_m_strpreach_01`. The simplest of the set at three unique functions.

**`pb_homeless.c`** — the most useful of the three. Dictionary `amb@drug_dealer`
with three beckon variants, `beckon_01` through `beckon_03`, picked at random. It
creates its own relationship group:

    ADD_RELATIONSHIP_GROUP("homeless", &group)
    SET_PED_RELATIONSHIP_GROUP_HASH(ped, group)

so the tramp (`a_m_o_tramp_01`) and a nearby punk (`g_m_y_strpunk_01`) relate to each
other and to the player independently of the ambient population. It falls back to
`TASK_WANDER_STANDARD` when the player leaves.

**`pb_prostitute.c`** — by far the largest at 8,246 unique lines and 261 unique
functions, more than every other street character combined. It is a full
solicit-to-vehicle flow: scenario idle via `WORLD_HUMAN_PROSTITUTE_HIGH_CLASS`,
approach, enter the player vehicle, drive to a quiet spot with
`TASK_VEHICLE_DRIVE_TO_COORD` at 65% of the vehicle's estimated max speed, then
leave. Animation selection runs through a helper that picks clips by index, so the
clip names never appear as literals.

That speed detail is worth copying on its own — driving at a fraction of
`GET_VEHICLE_ESTIMATED_MAX_SPEED` rather than a fixed number keeps behaviour sane
across every vehicle class.

## Porting

The `gpb_*` template is a good starting point for any "character who lives at this
spot": idle loop, react when crowded, return to post, flee if threatened. It is
about forty lines of real logic.

`TASK_FOLLOW_POINT_ROUTE` is the single most reusable find here — reach for it
before writing another waypoint loop.

## Related

- [../reference/scenario-index](../reference/scenario-index.md)
- [../reference/speech-index](../reference/speech-index.md)
- [random-events](random-events.md)
- [street-performers](street-performers.md)
