# Random events

**Source:** all 38 `re_*.c` scripts, surveyed by extracting every distinct
mechanical call from their unique code. 81,050 unique lines total.

These are the world encounters — muggings, car thefts, shootouts, hitchhikers,
accidents. As a group they are the best available reference for **spawning a small
scripted encounter and cleaning it up again**, which is most of what an ambient job
or dynamic event resource does.

## The shared template

Every one of the 38 follows the same shape:

1. Pick a spawn point and wait for the player to come near
2. Create a relationship group and set how it feels about the player
3. Spawn peds and vehicles, dress them, arm them
4. Give them a task sequence
5. Poll task status; branch on player behaviour
6. Release everything and terminate

### Relationships are the switch

`SET_RELATIONSHIP_BETWEEN_GROUPS(level, groupA, groupB)` is what decides whether an
encounter is hostile, and the levels used are consistent across all 38:

| Level | Meaning in practice |
|---|---|
| `1` | Like — used between allied groups |
| `2` | Dislike |
| `3` | Neutral-ish, used for wary encounters |
| `5` | Hate — the standard for anything that attacks |
| `255` | Special / no relationship |

`re_armybase.c` sets a full matrix rather than a single line: army hates player both
ways, army likes army, and cop and army like each other. Relationships are
directional — nearly every script sets both directions explicitly, and forgetting
one is a classic source of one-sided aggression.

### Task status polling

The universal idiom for "is this ped done yet":

    GET_SCRIPT_TASK_STATUS(ped, joaat("script_task_perform_sequence")) == 7

`7` means finished, `1` means active, `0` means not yet started. Scripts check `!= 1
&& != 0` when they want "finished or never ran". Task names are the hashed
`script_task_*` form.

`TASK_PERFORM_SEQUENCE` is the dominant idiom — R* builds a sequence of tasks and
hands it over as a unit rather than driving each step from script state.

### Flee distances

`TASK_SMART_FLEE_PED(ped, player, radius, -1, false, false)` with radius varying by
severity: `150` for a startled bystander, `250` for someone who has just been
threatened, `1000` for a witness escaping a killing.

`SET_PED_COMBAT_ATTRIBUTES(ped, 17, true)` appears in almost every hostile event.

## Techniques worth stealing

**Two different attach bones.** Held items divide cleanly:

- **`28422`** — right hand grip, for carried objects. Wallets, spray cans,
  pamphlets, protest signs, phones.
- **`57005`** — used for weapon-like held items with rotation offsets, such as the
  golf club in `re_domestic.c` and the shotgun in `re_shoprobbery.c`.

Using `28422` for everything is why hand-attached props often sit wrong.

**Custom pickup models.** `re_prisonvanbreak.c` creates a pickup that looks like
whatever you want:

    CREATE_PICKUP_ROTATE(joaat("pickup_money_case"), pos, rotation, ..., 5000, 2, true, joaat("prop_security_case_01"))

The final argument overrides the display model, so a money pickup can render as a
security case. This is the clean way to make custom lootables without faking the
pickup with a prop and a distance check.

**Reuse the world instead of spawning.** `re_rescuehostage.c` calls
`GET_RANDOM_VEHICLE_IN_SPHERE` and `GET_RANDOM_PED_AT_COORD` to grab entities that
already exist rather than creating new ones. Cheaper, and the scene blends into
traffic instead of appearing.

**Audio baked into a synchronised scene.** `re_mountdance.c` starts a scene and calls
`PLAY_SYNCHRONIZED_AUDIO_EVENT`, so the audio is locked to the animation phase
rather than started on a timer.

**Paired rescue animation.** `re_crashrescue.c` runs one scene containing two roles,
`helping_friend_inside_victim` and `helping_friend_inside_friend`, plus a matching
`HELPING_FRIEND_INSIDE_CAM` camera track. The template for any two-person
interaction — carrying, reviving, arresting.

**Patrols come free.** `re_armybase.c` uses
`TASK_FOLLOW_WAYPOINT_RECORDING(ped, "OfficerMarch01", ...)` — a shipped, named
patrol route. See the [waypoint recording index](../reference/waypoint-recording-index.md)
for all 184.

**Built-in point routes.** Separately, `gpb_pameladrake.c` builds a route at runtime
with `TASK_FLUSH_ROUTE`, repeated `TASK_EXTEND_ROUTE(x, y, z)` calls, then
`TASK_FOLLOW_POINT_ROUTE`. A patrol path in four calls, no state machine needed.
Most FiveM patrol scripts reimplement this by hand.

**Dynamic string building.** `re_paparazzi.c` concatenates a random integer onto a
base string to pick one of thirteen variants. Worth knowing because it is exactly
the case a literal-scanning tool cannot see — the names never appear in the file.

## Named animation sets

- `random@drunk_driver_1` — `drunk_argument_dd1` / `dd2`, a two-hander
- `random@homelandsecurity` — `idle_to_knees_girl`, `knees_loop_girl`
- `random@robbery` — `exit_flee`
- `random@paparazzi@pap_anims` — `base_pap`, `pap_idle_a`, `pap_idle_b`
- `amb@world_human_guard_patrol@male@idle_b` — `idle_e`
- Agitation loops `agitated_loop_a` / `_b` / `_c` in `re_muggings.c`

## Vehicle behaviour

- `TASK_VEHICLE_MISSION_PED_TARGET` — chase or ram a ped, mission type `8` is the
  common aggressive pursuit
- `TASK_VEHICLE_DRIVE_WANDER` — ambient driving after a theft
- `TASK_DRIVE_BY` with a firing pattern hash
- `TASK_VEHICLE_TEMP_ACTION(ped, veh, 30, 1000)` — a brief scripted manoeuvre
- `SET_DRIVE_TASK_CRUISE_SPEED(veh, 3.0)` in `re_bus_tours.c` for a slow tour
- `TASK_PLANE_MISSION` in `re_lossantosintl.c`, scrambling jets

`re_cartheft.c` triggers `scr_wheel_burnout` as a non-looped effect on the wheels
when the thief pulls away.

## Porting

The whole family is single-player, so ownership and cleanup need rethinking for a
networked server. What transfers directly is the vocabulary: relationship levels,
task sequences, status polling, flee radii and the attach bones. Those are the parts
that make a spawned encounter behave like the game's own rather than like a scripted
set piece.

## Related

- [../reference/relationship-group-index](../reference/relationship-group-index.md)
- [../reference/waypoint-recording-index](../reference/waypoint-recording-index.md)
- [street-characters](street-characters.md)
- [../reference/task-vocabulary](../reference/task-vocabulary.md)
