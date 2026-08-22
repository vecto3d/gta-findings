# Boss and business work

**Source:** 70 `gb_*` scripts

**Mostly low yield.** The large ones (9–16M: `gb_deathmatch`, `gb_casino_heist`,
`gb_casino`, and every `gb_biker_*`) share an identical shell — spectator cards,
`anim@amb@facility@hanger_doors`, `SOCIAL_CLUB_TV`, `BREAKING_NEWS` — with the
mission logic buried deep inside.

Read one to learn the shell, then ignore the rest.

The exceptions worth opening:

- `gb_sightseer.c`, `gb_headhunter.c` — see [vip-work.md](vip-work.md)
- `gb_biker_safecracker.c` — see [safe-cracking.md](safe-cracking.md)
- `gb_data_hack.c` — see [heist-minigames.md](heist-minigames.md)
- `gb_casino_heist_planning.c` — see
  [heist-planning-boards.md](heist-planning-boards.md)

## Business management UIs

Named scaleforms, each a ready-made management interface: `NIGHTCLUB`,
`BIKER_BUSINESSES`, `ARCADE_MANAGEMENT`, `ARCADE_BUSINESS_HUB`, `warehouse`,
`IMPORT_EXPORT_WAREHOUSE`, `HANGAR_CARGO`, `DISRUPTION_LOGISTICS`,
`SALVAGE_PLANNING`, `SALVAGE_VEHICLE_TARGETS`, `STARTER_PACK_BROWSER`,
`AVENGER_OPERATIONS_TERMINAL`, `FIXER_APP`, `COVERT_OPS`.
