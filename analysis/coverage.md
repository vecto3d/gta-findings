# Coverage

What was actually processed, and to what depth. Read this before trusting anything
in the script documents.

## Three depths

Not everything here is known to the same standard. Three distinct levels:

| Depth | Meaning | Scripts |
|---|---|---:|
| **Parsed** | Every function split out, deduped, every string typed by its consuming native | 1,156 |
| **Read** | Source opened and followed line by line | 3 |
| **Verified** | Behaviour confirmed by building it and running it | 1 |

Every script in this repo is **parsed**. Almost none are **read**.

## Parsed: all 1,156

Every line of all 168.6M was passed through the extractor. Nothing was sampled and
nothing was skipped. For each script this yields, restricted to code unique to it:

- typed assets (anim dicts, animations, models, sounds, scaleforms, particles, and more)
- native call counts
- float tuning constants
- developer state labels where they survive

This is exhaustive for **identifiers**. It is silent on **logic**.

## Read: 3

- `ob_cashregister.c` — 625 lines, read fully
- `ob_poledancer.c` — 170 lines, read fully
- `ob_vend1.c` — several hundred lines of ~80,000, read in the regions that mattered

That is roughly **1,200 lines out of 168,668,190**, or 0.0007%.

## Verified: 1

The vending machine, ported to a working FiveM resource. Everything in
[vending-machine](../features/vending-machine.md) was confirmed against a running
game. It is the only document in this repo at that standard, and the only one where
the timing values and the ordering of the flow can be trusted.

## Why not read the rest

After removing the 93% that is duplicated library code, 12.4M unique lines remain.
The distribution is the problem:

| Unique lines | Scripts | Total unique lines |
|---|---:|---:|
| under 300 | 175 | 19,598 |
| 300 - 1k | 149 | 96,670 |
| 1k - 3k | 171 | 320,291 |
| 3k - 10k | 222 | 1,289,587 |
| 10k - 30k | 232 | 3,960,586 |
| 30k+ | 78 | 6,739,303 |

78 scripts hold 6.7M unique lines between them. `freemode.c` alone has 573,248
unique lines across 11,179 unique functions. No context window holds that, so those
scripts will only ever be indexed, never read.

The opposite end is tractable. **495 scripts have under 3,000 unique lines each**,
436,559 lines in total. Those can genuinely be read, and they are where the
portable mechanics live.

## Where the value is concentrated

Unique lines per category, smallest first:

| Category | Scripts | Unique lines |
|---|---:|---:|
| Collectibles | 8 | 5,582 |
| Street characters | 18 | 12,234 |
| **Object brains** | 26 | **22,145** |
| Random events | 38 | 81,050 |
| Ambient world | 41 | 112,665 |
| Vehicles | 25 | 230,128 |
| Jobs | 52 | 270,951 |
| Minigames | 75 | 1,166,312 |
| MP freemode | 122 | 3,684,117 |

The inversion is the useful finding. **Object brains are the most portable thing in
the corpus and the smallest** — all 26 of them together are 22,145 lines, less than
4% of `freemode.c` alone. The vending machine came from there.

`mp-freemode` is 30% of all unique code and is almost entirely session plumbing,
matchmaking and transaction validation. It is the least portable category and the
largest.

## Known blind spots

- **Logic is not recovered.** Scoring rules, state transitions and payout formulas
  are invisible except where a debug label names them.
- **Numbers are listed, not explained.** Constants appear without meaning attached.
- **Reference is not usage.** A model listed against a script proves the name appears
  in its code, not what it does with it.
- **Descriptions are inferred.** Each script document opens with a one-line summary
  derived from category and assets. The tables under it are extracted fact; that
  opening line is a guess.
- **SP story missions and the creator tools were parsed but not investigated.**

## The failure mode this guards against

Two errors during the vending machine port came from inferring instead of reading.
The eCola/Sprunk mapping was guessed from a filename pattern and was wrong twice,
until the actual code settled it. `VAULT_DRILL` looked like a drilling minigame
until call counts showed it is boilerplate present in nearly every script.

Both were caught by reading. Neither would have been caught by extraction, however
thorough. When a mechanic matters, open the file.
