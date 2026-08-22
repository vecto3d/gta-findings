# Render targets — drawing to an in-world screen

`REGISTER_NAMED_RENDERTARGET` names. This is how anything appears on a screen
prop, and the name must match the model.

| Target | Uses | What it is |
|---|---|---|
| `blimp_text` | 14 | The blimp sign |
| `tvscreen` | 8 | TVs |
| `npcphone` | 7 | NPC phone display |
| `Prop_x17DLC_Monitor_Wall_01a` | 4 | Facility monitor wall |
| `Big_Disp` | 4 | Large display |
| `digiscanner` | 3 | Scanner |
| `W_AM_HackDevice_M32` | 3 | Hacking device |
| `taxi` | 2 | Taxi screen |
| `safe_01a`, `xm3_safe_01a` | 2, 1 | Safe displays |
| `club_computer`, `prop_clubhouse_laptop_01a` | 2 | Club laptop |
| `osp_panel`, `prop_ex_office_text`, `prop_ex_computer_screen` | 2 | Office screens |
| `PBus_Screen` | 2 | Party bus |
| `submarine_table`, `prop_x17_p_01` | 1 | Planning tables |

Pair a render target with one of the terminal scaleforms in
[laptop-and-terminals.md](laptop-and-terminals.md) for a working in-world
computer with no NUI.
