# Safehouse drinking and smoking

**Source:** `ob_mr_raspberry_jam.c` (read in full), `ob_drinking_shots.c`,
`ob_franklin_beer.c`, `ob_franklin_wine.c`, `ob_wheatgrass.c`, `ob_bong.c`,
`ob_huffing_gas.c`, `ob_sofa_michael.c`, `ob_sofa_franklin.c`

## They are one script, not nine

Reading `ob_mr_raspberry_jam.c` settles something the file listing hides. These are
not nine separate implementations — they are **one activity engine** compiled into
several brains, which branches on the model of the prop it was attached to.

A single lookup inside it maps prop model to camera:

| Prop model | Camera |
|---|---|
| `prop_bong_01` | `bong_cam`, or `short_cam` |
| `prop_cs_beer_bot_01` | `enter_cam` |
| `prop_rolled_sock_02` | `ig_8_huff_gas_cam` |
| `prop_mr_raspberry_01` | four `ig_7_*` variants |
| `p_w_grass_gls_s` | `ig_2_wheatgrassdrink_cam` |
| `p_wine_glass_s` | resolved by a further lookup |

So porting one gets you all of them. Pick the prop, everything else follows.

## Dictionaries

`MP_SAFEHOUSEBEER@`, `MP_SAFEHOUSEWINE@`, `MP_SAFEHOUSEWHISKEY@`,
`mp_safehousewheatgrass@`, `mp_safehousebong@`, plus character-specific
`safe@michael@ig_1`–`ig_5`, `safe@franklin@ig_9`–`ig_14`, `safe@trevor@ig_5`–`ig_8`.

## The useful part: drunk-state exits

Each activity has enter and idle clips plus **separate exits per drunk state**:

- `exit_sober_bot`, `exit_slightly_drunk_bot`, `exit_moderately_drunk_bot`,
  `exit_drunk_bot`
- Glass variants: `exit_sober_glass`, `exit_drunk_glass`, `exit_shotglass`
- Bottle counts: `exit_1_bottle` through `exit_4_bottle`, `exit_1_beer`,
  `exit_2_beer`
- Matching facial anims, e.g. `exit_sober_trevor_facial`,
  `exit_moderately_drunk_trevor_facial`

## How a run works

The state machine is short. Approach and face the prop, and it starts the
`TREVOR_SAFEHOUSE_ACTIVITIES_SCENE` audio scene and shows a prompt. Hold the input
and it clears nearby projectiles, holsters to `weapon_unarmed`, takes player control
and unfreezes the prop.

Then one synchronised scene drives three things at once:

- the **player**, via `TASK_SYNCHRONIZED_SCENE`
- the **prop**, via `PLAY_SYNCHRONIZED_ENTITY_ANIM` — the glass moves with the hand
  because it is in the same scene, not attached to a bone
- the **camera**, via a `DEFAULT_ANIMATED_CAMERA` and `PLAY_SYNCHRONIZED_CAM_ANIM`

That third one is the trick worth taking. The camera move is baked into the
animation rather than scripted. It is skipped entirely when the player is in first
person, where the script destroys all cams instead.

**Variety is a counter, not a roll.** One of four variants is picked at random on
startup, then **cycles** on each use rather than re-rolling, so the player never
sees the same clip twice running. Each variant has its own duration — roughly 3.0s,
3.6s, 4.0s and 5.5s — and its own spoken line, `SHRJ_0` through `SHRJ_3`, fired
partway through on a timer.

On completion it heals the player by 10, capped at max health, and increments a
usage stat.

## Breaking out cleanly

The exit is the part most ports get wrong. This one watches the movement stick for
deflection past a threshold, latches that as intent, and then leaves **only** when
the scene phase reaches a window the animation itself declares, found with
`FIND_ANIM_EVENT_PHASE` against the `WalkInterruptible` tag.

Clearing tasks the moment input arrives is what makes a port look janky. Details in
[animation-alignment](../reference/animation-alignment.md).

## Related

- [drunk-system](drunk-system.md) — the drunkenness the exit clips read from
- [object-brain-pattern](object-brain-pattern.md)
- [../reference/sync-scenes](../reference/sync-scenes.md)
