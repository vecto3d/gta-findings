# World state, blips and comms

**Source:** all 89 `system-infra` and 67 `mp-ambient` scripts, surveyed from unique
code. Mostly plumbing, but three things in here are worth taking.

## CB radio audio, ready made

`comms_controller.c` drives radio chatter with a shipped soundset, `CB_RADIO_SFX`:

| Sound | Use |
|---|---|
| `Start_Squelch` | Key up, before speech |
| `End_Squelch` | Key down, after speech |
| `Background_Loop` | Carrier hiss while the channel is open |

Any FiveM radio resource can have correct-sounding squelch with three calls and no
audio files. Bracketing transmissions with start and end squelch, with the loop
underneath, is what separates a radio that sounds like a radio from one that just
plays voice.

## Changing the world permanently

`building_controller.c` is how the map reflects story progress. It creates props at
fixed coordinates with `CREATE_OBJECT_NO_OFFSET` and freezes them — repair signs,
cabinet doors, and similar — so a location looks different after an event.

The pattern generalises to any persistent world change on a server: keep a list of
state-dependent props in one controller, create and freeze the set that matches
current state, rather than scattering the logic across the scripts that cause the
change.

The [TV brains](tv-and-channels.md) use the same swap-the-prop idea for on and off
states, and `carsteal2.c` does it for a garage door. Swapping models is the game's
standard answer to "this object needs to look different now".

## Centralised blips

`blip_controller.c` owns a table of blips rather than letting each script manage its
own. Radius blips are added with `ADD_BLIP_FOR_RADIUS` and dimmed to alpha `128`, the
convention for an area you can see through.

The blip vocabulary across the whole corpus:

`SET_BLIP_SPRITE` · `SET_BLIP_COLOUR` · `SET_BLIP_SCALE` · `SET_BLIP_ALPHA` ·
`SET_BLIP_PRIORITY` · `SET_BLIP_FLASHES` · `SET_BLIP_FLASH_INTERVAL` ·
`SET_BLIP_FLASH_TIMER` · `SET_BLIP_ROUTE` · `SET_BLIP_AS_FRIENDLY` ·
`SET_BLIP_HIDDEN_ON_LEGEND` · `SET_BLIP_NAME_FROM_TEXT_FILE` ·
`SET_BLIP_EXTENDED_HEIGHT_THRESHOLD`

Two worth knowing: `SET_BLIP_FLASH_TIMER(blip, 7000)` flashes then stops by itself,
so attention-grabbing blips do not flash forever; and `SET_BLIP_HIDDEN_ON_LEGEND`
keeps a marker off the map legend while still showing it on the minimap.

## Freemode event enemies

The `am_*` freemode events share a way of tuning hostiles beyond relationship groups:

    SET_PED_ACCURACY(ped, value)
    SET_PED_COMBAT_ABILITY(ped, 1)
    SET_PED_COMBAT_MOVEMENT(ped, 2)

Accuracy is per-ped and read from a difficulty table rather than fixed, which is how
the same event scales. Combat ability and movement are small enums — ability roughly
poor to professional, movement roughly stationary to aggressive advance.

Relationship groups for these events come from globals rather than named hashes, so
the group names never appear as literals. That is one of the places string extraction
genuinely cannot follow.

## Event audio

`GTAO_FM_Events_Soundset` and `GTAO_Biker_Modes_Soundset` carry `Event_Start_Text`,
`Enter_1st`, `Object_Collect_Player` and `Object_Collect_Remote`.

The player and remote collect variants are the detail worth copying — the game plays
a different sound depending on whether you or someone else picked the thing up.

## What is not worth reading

- **`dev-test`** — 88 scripts, 65 with no unique code at all, averaging one distinct
  asset each. The only category where emptiness is real.
- **`creators`** — 543,353 unique lines of mission-editor UI. Five of the seventeen
  have no unique code.
- **`mp-freemode`** — 3.68M unique lines, 30% of everything, almost entirely session
  plumbing, matchmaking and transaction validation.

## Related

- [../reference/audio](../reference/audio.md)
- [ped-control-flags](ped-control-flags.md)
