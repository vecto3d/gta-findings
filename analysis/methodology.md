# Methodology

How the corpus was processed, and what each number means.

## The problem

The decompile is 1,156 scripts, 3.58 GB, **168,668,190 lines**. Reading it linearly
is not possible for any person or tool. Earlier passes over this repo used string
grep, which finds quoted literals but is blind to everything else.

## The insight: 15:1 duplication

Every script is compiled with the shared script libraries linked in. `ob_wheatgrass.c`
contains 441 functions; the vending machine brain contains 428. Almost none of that
is about wheatgrass or vending machines.

Function *names* are not stable across files. The decompiler numbers them per file,
so the same library routine is `func_88` in one script and `func_291` in another.
Comparing names finds nothing.

So compare **bodies**. Normalising every identifier index (`func_12` → `func_`,
`iLocal_88` → `iLocal_`, `Global_2621568` → `Global_`, `iParam0` → `iParam`) makes
the same library routine hash identically everywhere it appears.

Result:

| | |
|---|---|
| Function instances | 2,830,909 |
| Distinct function bodies | 190,106 |
| Duplication ratio | **14.9 : 1** |
| Lines inside functions | 162,511,371 |
| Distinct lines | 12,426,035 |

Roughly **93% of the corpus is copies.**

## What counts as unique

A function body is treated as belonging to a script when it appears in **3 or fewer**
files. The threshold is not 1, because genuine variants exist in pairs and triples:
`ob_vend1.c` / `ob_vend2.c`, the two bed brains, the mission-controller family.

| Bodies appear in | Distinct bodies | Distinct lines |
|---|---:|---:|
| 1 file | 133,204 | 9,479,105 |
| 2-3 files | 25,009 | 1,253,733 |
| 4-10 files | 14,371 | 996,296 |
| 11+ files (library) | 17,522 | 1,208,124 |

129 of the 1,156 scripts have **no** unique function at all. They are stubs,
registration shims, or exact duplicates. Each is marked as such in its document.

## Typing the strings

The earlier grep passes could tell you `"PLYR_BUY_DRINK_PT1"` existed somewhere.
They could not tell you it was an animation rather than a model or a text label.

This pass parses each line with a paren-depth stack and attributes every string
literal to the **native call that encloses it**. So in

    TASK_PLAY_ANIM(PLAYER::PLAYER_PED_ID(), sLocal, "PLYR_BUY_DRINK_PT1", ...)

the string is attributed to `TASK_PLAY_ANIM`, not to the nearer `PLAYER_PED_ID`.
That single fix is what turns a flat word list into a typed asset inventory.

A shape-based fallback catches assets passed through variables, where no native
directly encloses the literal: anything containing `@` is an animation dictionary,
anything starting with `prop_`/`v_`/`a_c_`/`mt_` is a model, and so on. This is how
`MINI@SPRUNK@FIRST_PERSON` and the vending machine prop list were recovered.

## Developer state labels

27 scripts still contain `DRAW_DEBUG_TEXT_2D` calls with the developers' own state
names. `ob_vend1.c` names its states `runVendingMachine`, `waitForPlayer`,
`grabPlayer`, `playerOutOfRange`, `resetVend`.

These are the single most valuable thing in the corpus, because they describe
*structure* rather than assets. They are collected in
[developer-state-labels](../reference/developer-state-labels.md).

## Validation

The vending machine was reverse-engineered by hand earlier by reading `ob_vend1.c`
directly. The extracted profile reproduces every fact found that way: the three
animation clips, the `VENDING_MACHINE` audio bank, the `0.98f` release threshold and
the `-1.5f` blend-out. Nothing was invented and nothing known was missed.

That is the only end-to-end check that exists. It passed for one script.

## What this cannot do

Extraction recovers **names, counts and constants**. It does not recover **logic**.

- Control flow, state machines and scoring rules are invisible unless a debug label
  happens to name them.
- Numbers are listed but not interpreted. `0.98f` appears in the vending machine
  profile; that it is the point where the can detaches was learned by reading.
- A listed asset is proof the script *references* the name, not proof of how.

Treat every script document as a verified index and an unverified description.
