# Nightclub

**Source:** `am_mp_nightclub.c` (14M), `am_mp_casino_nightclub.c` (14M),
`nightclubpeds.c`, `sclub_front_bouncer.c`

Scaleforms `DANCER`, `SECURITY_CAM`.

## The standout: player bartender

`anim@amb@nightclub@mini@drinking@bar@player_bartender@base` with `@one`, `@two`,
`@three`, `@four` and `@idle_a` — **numbered by how many drinks are being
carried**. A complete serve-drinks-behind-the-bar mechanic.

## Other dicts

- Crowd: `anim@amb@nightclub@dancers@crowddance_groups@low_intensity`
- Drinking at the bar: `...@bar@drink@base`, `@beer`, `@one` through `@four`,
  `@idle_a`, plus a `drink_v2` variant
- Shots with drunk states:
  `anim@amb@nightclub@mini@drinking@drinking_shots@ped_a@drunk@`
- Champagne: `ANIM@AMB@NIGHTCLUB@MINI@DRINKING@CHAMPAGNE_DRINKING@BASE@`

## Bouncer

`sclub_front_bouncer.c` holds the door behaviour, and the speech context
`BOUNCER_EJECT_GENERIC` is the most-used speech line in the entire repo at 745
call sites.

Related: `si_dancing_activity.c`, `music_studio_smoking.c`,
`mansion_club_bar.c`, `stripperhome.c`.
