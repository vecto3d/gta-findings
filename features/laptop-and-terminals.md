# Laptops, computers and terminals

**Source:** `laptop_trigger.c` (128K), plus phone app scripts

Ready-made computer interfaces — no NUI needed for a laptop or terminal prop.

| Scaleform | Script |
|---|---|
| `ROBBERY_COMPUTER` | `apphackerden.c` |
| `hacker_truck_desktop` | `apphackertruck.c` |
| `securoserv` | `appsecuroserv.c` |
| `BOUNTY_COMPUTER` | `appbailoffice.c` |
| `AVENGER_OPERATIONS_TERMINAL` | |
| `JHPB_02_Laptop` | |
| `FIXER_APP`, `COVERT_OPS` | |

Combine one of these with a matching render target — `club_computer`,
`prop_clubhouse_laptop_01a`, `prop_ex_computer_screen`, `osp_panel` — and you
have a working in-world computer. See [render-targets.md](../reference/render-targets.md).


## They are object brains without the prefix

`atm_trigger.c` (3,078 unique lines) and `laptop_trigger.c` (1,125) do not start with
`ob_`, but both run the [object brain pattern](object-brain-pattern.md) exactly,
including the `IS_OBJECT_WITHIN_BRAIN_ACTIVATION_RANGE` guard and terminate-on-leave.
Prefix sweeps miss them. There are more prop interactions in the game than the 26
files named for it.

Both share one approach sequence, and it is the cleanest example of it anywhere:

    TASK_GO_STRAIGHT_TO_COORD(ped, pos, 1.0, 5000, GET_ENTITY_HEADING(prop), 0.25)

The heading comes straight from the prop, so the player always ends up square to it
without a hardcoded angle. They wait for task status `7`, confirm the anim dict is
loaded, then start a `NETWORK_CREATE_SYNCHRONISED_SCENE` at the prop position and
rotation.

**Exit is on phase, not on completion.** `laptop_trigger.c` breaks out at
`GET_SYNCHRONIZED_SCENE_PHASE(scene) >= 0.93`, leaving the tail of the clip to blend
into whatever comes next rather than running to `1.0` and snapping.

`atm_trigger.c` additionally requests the `ATM` scaleform plus an
`INSTRUCTIONAL_BUTTONS` instance and runs the `ATM_PLAYER_SCENE` audio scene while
active. `laptop_trigger.c` spawns its own `prop_laptop_lester2` rather than using a
map prop.

For a FiveM port these two are better starting points than the vending machine: they
already use the networked scene natives, and they take their alignment from the prop
instead of from tuned constants.
