# Keeping a scripted scene intact

**Source:** `re_bus_tours.c` (2,120 unique lines), `apptextmessage.c`, `am_ammo_drop.c`,
`launcher_hunting.c`, read from unique code.

A scattered set of calls that solve the same problem: the game interfering with
something your script is in the middle of.

## Stop other events firing

    SUPRESS_RANDOM_EVENT_THIS_FRAME()

Called every frame of the bus tour, nine times across the script. It stops the ambient
random-event system starting a mugging or a car theft in the middle of a scripted
sequence.

The spelling is the game's own — one `p`. Grepping for the correct spelling finds
nothing, which is a small example of why native names should be copied, not typed.

Any FiveM scene that must not be interrupted — a cutscene, a job hand-off, a tour —
wants this on a per-frame loop.

## Let a ped finish after you let go

    SET_PED_KEEP_TASK(ped, true)

Normally a ped reverts to default behaviour when the script that tasked it stops
caring. This makes the current task survive, which is what you want when releasing a
driver mid-route or a ped mid-walk rather than having them stop dead.

## Check the vehicle is still usable

    IS_VEHICLE_DRIVEABLE(veh, false)

Used 21 times in the bus tour. A destroyed or upside-down vehicle still exists, so
`DOES_ENTITY_EXIST` is not enough before continuing a driving sequence. The tour also
locks doors with `SET_VEHICLE_DOORS_LOCKED` so passengers cannot wander out mid-route.

The tour bus itself is the `tourbus` model with `BUSTOAU` audio.

## Text that might not exist

    DOES_TEXT_LABEL_EXIST(label)

`apptextmessage.c` guards every label lookup with this. Missing text keys render as
the raw key on screen rather than failing loudly, so the check is the only way to catch
them.

The same script shows the correct split for putting text into a scaleform:

- `ADD_TEXT_COMPONENT_SUBSTRING_TEXT_LABEL` for a **localised label key**
- `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME` for **arbitrary or user-supplied text**

The second name is misleading — it is used for any literal string, not just player
names. Passing user text through the label path would try to resolve it as a key.
This is the same mechanism described in [the results screen](results-screen.md).

`SET_SOFT_KEYS` appears 27 times: the phone's context-sensitive button labels are
re-pushed constantly rather than set once.

## Networked sound handles

    GET_SOUND_ID_FROM_NETWORK_ID(netId)

From `am_ammo_drop.c`. A looping sound attached to a networked object needs a sound id
derived from the network id, so every client refers to the same sound. Local sound ids
do not survive the network boundary.

The same script guards every entity use with both
`NETWORK_DOES_NETWORK_ID_EXIST` and `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` before
converting with `NET_TO_OBJ` — 61 conversions, every one guarded. Worth copying as a
habit.

The ammo drop uses a `cuban800` for the plane and `p_cargo_chute_s` for the parachute.

## Related

- [random-events](random-events.md)
- [ped-control-flags](ped-control-flags.md)
- [../reference/cutscenes-and-streaming](../reference/cutscenes-and-streaming.md)
