# Hunting

**Source:** `hunting2.c` (1008K), `hunting_ambient.c`

The animal AI is the valuable part:

- `creatures@deer@amb@world_deer_grazing@base` with `@enter`, `@exit`, `@idle_a`
- `oddjobs@hunter` — the hunter animations
- `facials@p_m_one@variations@elkcall` — the elk call facial
- `amb@world_human_guard_patrol@male@idle_a`, `gestures@m@standing@casual`
- `rcmhunting2` — mission-specific

Scenario `WORLD_DOG_SITTING_RETRIEVER` exists for the dog.

See also [chop-companion-dog.md](chop-companion-dog.md) for a much richer animal
animation set.
