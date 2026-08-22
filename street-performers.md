# Street performers

**Source:** `pb_busker.c` (20K), `pb_preacher.c` (16K), `pb_homeless.c` (24K),
`pb_prostitute.c`

Tiny scripts, one per character, all the same shape: spawn a ped, run a looping
performance, react to the player.

| Script | Dict | Ped | Speech |
|---|---|---|---|
| `pb_busker` | `amb@BUSKER` | `a_f_m_bevhills_02` | |
| `pb_preacher` | `amb@PREACHER` | `s_m_m_strpreach_01` | `PREACH` |
| `pb_homeless` | `amb@drug_dealer` | `a_m_o_tramp_01`, `g_m_y_strpunk_01` | |

All reference `player_timetable_scene`.

Together with [pole-dancer.md](pole-dancer.md) these are the cleanest ambient-NPC
templates in the repo.
