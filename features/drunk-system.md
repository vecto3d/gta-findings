# Drunk system

**Source:** `drunk_controller.c` (16K), `drunk.c`

A complete sober-to-drunk progression already exists in the game.

- **Controller:** `drunk_controller.c` — the state machine, using the
  `DRUNK_SHAKE` camera shake (72 uses repo-wide) and a `drunk` clipset. Also
  references `SAFEHOUSE_STONED_MICHAEL`.
- **Movement clipsets:** `MOVE_M@DRUNK@SLIGHTLYDRUNK`,
  `MOVE_M@DRUNK@MODERATEDRUNK_HEAD_UP`
- **Exit animations per state:** see [safehouse-drinking.md](safehouse-drinking.md)
- **Nightclub shots with drunk states:**
  `anim@amb@nightclub@mini@drinking@drinking_shots@ped_a@drunk@`
- `re_drunkdriver.c` uses the same clipsets for its NPC

Everything needed for a drinking system that visibly degrades the player, with
no custom animation work.
