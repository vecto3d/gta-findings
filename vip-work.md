# VIP work

**Source:** `gb_sightseer.c` (1.7M), `gb_headhunter.c` (1.6M)

The two smallest and most readable `gb_*` scripts, and the best entry point into
that family.

- **Sightseer** — checkpoint collection loop
- **Headhunter** — targets with bodyguard AI

Both use only the shared matchmaking and spectator scaleforms
(`MP_SPECTATOR_CARD`, `mp_matchmaking_card`, `mp_mm_card_freemode`), so their
value is the job *structure* — objective spawning, timers, blips, rival players —
not assets.

See [business-work.md](business-work.md) for the rest of the family.
