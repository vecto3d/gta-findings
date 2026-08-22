# Sync scenes

**The most-used mechanic in the entire repo.**

| Native | Call sites |
|---|---|
| `TASK_SYNCHRONIZED_SCENE` | 7998 |
| `CREATE_SYNCHRONIZED_SCENE` | 4747 |
| `NETWORK_CREATE_SYNCHRONISED_SCENE` | 1991 |

R* coordinates almost every multi-ped animation this way rather than with
separate `TASK_PLAY_ANIM` calls. Anything where two entities must move together —
the CPR pair, a ped opening a door for you, any cutscene-like set piece — is a
sync scene. The networked variant keeps it consistent for other players.

**This is the single most transferable technique in the codebase.** If you are
porting anything involving two peds, or a ped and a prop moving together, this is
how the original does it.
