# GTA V Decompiled Scripts — FiveM Port Findings

Notes from mining a full decompile of GTA V build **1.73-3889.0** (1156 scripts)
for mechanics worth porting to FiveM. One file per feature. Everything quoted —
anim dictionaries, props, scaleform names, timing values, offsets — is taken
verbatim from the decompiled source.

## Start here

Strongest build candidates found, roughly easiest first:

- [beds.md](beds.md) — enter, loop, exit. Reuses the vending skeleton verbatim
- [cash-register.md](cash-register.md) — ~170 lines, no animation at all
- [atm.md](atm.md) — dedicated `ATM` scaleform, easiest UI-bearing system
- [collectible-hunts.md](collectible-hunts.md) — two complete implementations
- [cpr-revive.md](cpr-revive.md) — paired medic/patient anims for EMS
- [safe-cracking.md](safe-cracking.md) — full dial-turning set, nothing missing
- [chop-companion-dog.md](chop-companion-dog.md) — complete K9 including scent pose
- [taxi.md](taxi.md) — two scaleforms, no UI to write
- [arcade-cabinets.md](arcade-cabinets.md) — sprite-drawn, smallest is 60K

## Object interactions

Prop-triggered, the `ob_*` family. All follow one pattern.

[vending-machine.md](vending-machine.md) · [beds.md](beds.md) ·
[shower.md](shower.md) · [telescope.md](telescope.md) ·
[jukebox.md](jukebox.md) · [cash-register.md](cash-register.md) ·
[tv-and-channels.md](tv-and-channels.md) · [pole-dancer.md](pole-dancer.md) ·
[safehouse-drinking.md](safehouse-drinking.md) ·
[drunk-system.md](drunk-system.md)

## Minigames and games

[darts.md](darts.md) · [golf.md](golf.md) · [tennis.md](tennis.md) ·
[arm-wrestling.md](arm-wrestling.md) ·
[shooting-range.md](shooting-range.md) · [yoga.md](yoga.md) ·
[pilot-school.md](pilot-school.md) ·
[arcade-cabinets.md](arcade-cabinets.md) · [slot-machine.md](slot-machine.md) ·
[three-card-poker.md](three-card-poker.md) ·
[casino-table-games.md](casino-table-games.md)

## Hacking and heists

[word-hack.md](word-hack.md) ·
[circuit-block-hack.md](circuit-block-hack.md) ·
[safe-cracking.md](safe-cracking.md) ·
[heist-minigames.md](heist-minigames.md) ·
[heist-planning-boards.md](heist-planning-boards.md)

## Jobs and work

[taxi.md](taxi.md) · [towing.md](towing.md) · [car-wash.md](car-wash.md) ·
[hunting.md](hunting.md) · [bail-bonds.md](bail-bonds.md) ·
[vip-work.md](vip-work.md) · [business-work.md](business-work.md)

## Activities and races

[races.md](races.md) · [rides.md](rides.md) ·
[freemode-activities.md](freemode-activities.md)

## World and ambient life

[chop-companion-dog.md](chop-companion-dog.md) ·
[street-characters.md](street-characters.md) ·
[street-performers.md](street-performers.md) ·
[random-events.md](random-events.md) ·
[collectible-hunts.md](collectible-hunts.md) ·
[nightclub.md](nightclub.md) · [cinema.md](cinema.md) · [atm.md](atm.md) ·
[laptop-and-terminals.md](laptop-and-terminals.md) ·
[world-systems.md](world-systems.md)

## Animation

[sync-scenes.md](sync-scenes.md) — start here, it is the most-used mechanic in
the repo · [cpr-revive.md](cpr-revive.md) ·
[vehicle-repair.md](vehicle-repair.md) ·
[activity-anim-dicts.md](activity-anim-dicts.md) ·
[scenarios.md](scenarios.md) · [camera-shakes.md](camera-shakes.md)

## UI and screens

[render-targets.md](render-targets.md) ·
[scaleform-catalogue.md](scaleform-catalogue.md) · [phone.md](phone.md) ·
[notifications.md](notifications.md) · [shops.md](shops.md) ·
[properties.md](properties.md)

## Reference

[audio.md](audio.md) · [decorators.md](decorators.md) · [doors.md](doors.md) ·
[interior-entity-sets.md](interior-entity-sets.md) ·
[pickups.md](pickups.md) ·
[relationship-groups.md](relationship-groups.md) ·
[timecycles.md](timecycles.md) ·
[task-vocabulary.md](task-vocabulary.md) ·
[waypoint-recordings.md](waypoint-recordings.md) ·
[native-call-counts.md](native-call-counts.md)

## Mining the repo

[repo-guide.md](repo-guide.md) — what to avoid, duplication warnings, and the
search techniques that actually surface features ·
[script-inventory.md](script-inventory.md) — all 1156 scripts, categorised

## Three things that cost time

Learned building the vending machine, and worth knowing before you start:

1. **An attached entity will not delete.** Detach first, always.
2. **Model does not imply identity.** The soda machines share models, so the
   brand a machine displays cannot be derived from what it is.
3. **Animations are authored data.** Only `PLYR_BUY_DRINK_PT1/2/3` exist in the
   entire game; there is no alternate button-press clip to swap in.
