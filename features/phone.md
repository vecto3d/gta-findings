# Phone and apps

**Source:** `cellphone_controller.c`, `cellphone_flashhand.c`, ~40 `app*.c`

**The phone is scaleform on a render target, not NUI.** The controller makes
**108 `SCALEFORM_MOVIE_METHOD` calls**, with `SET_MOBILE_PHONE_POSITION` for
placement. Render target `npcphone` for the NPC-side display.

Phone scaleforms: `cellphone_ifruit`, `cellphone_alert_popup`,
`cellphone_prologue`.

GXT label prefix for phone strings is `CELL_*`: `CELL_SIGHTS`, `CELL_SECHACK`,
`CELL_HACKER_ROB`, `CELL_EXTRACT`, `CELL_BOSSAGE`, `CELL_CIRCBREAK`,
`CELL_BENWEB`, `CELL_COMIC_P`, `CELL_CONDFON`, `CELL_CL*`.

## App sizes

Tiny, worth reading as templates: `appextraction.c` (8K), `appbroadcast.c` (16K),
`appchecklist.c` (28K), `apphs_sleep.c` (20K), `appmedia.c` (20K),
`appemail.c` (108K), `appcamera.c` (272K, selfie mode).

Enormous, avoid: `appinternet.c` (12M, the whole in-game web),
`appbusinesshub.c` (7.6M), `apparcadebusiness.c` (7.5M).

Terminal-style apps are listed in
[laptop-and-terminals.md](laptop-and-terminals.md).


## Survey of all 40 app scripts

Read from the unique code of every `app*.c` and `cellphone*.c`.

### The phone is one movie, not forty

The core apps — contacts, email, checklist, camera, extraction — all drive the
**same scaleform handle**, held in a shared global, rather than each owning a movie.
An app is not a screen; it is a set of calls that push rows into the one phone movie
and read the selection back.

The shared vocabulary is small:

| Method | Purpose |
|---|---|
| `SET_DATA_SLOT` | Write one row into the current list |
| `GET_CURRENT_SELECTION` | Read which row is highlighted |
| `GET_CURRENT_ROLLOVER` | Read which row is hovered |
| `SET_INPUT_EVENT` | Forward a control input into the movie |
| `DISPLAY_VIEW` | Switch which view the movie shows |

If you are building a phone in FiveM, that is the whole contract: fill slots, read
selection back, forward inputs. Everything else is data.

Phone audio comes from a soundset held alongside the movie handle, with
`Dial_and_Remote_Ring`, `Remote_Ring`, `Menu_Navigate` and `Hang_Up`.

### Business and laptop apps own their movies

The management apps are different — each requests its own movie, such as
`BIKER_BUSINESSES`, and drives a richer method set:

`SHOW_SCREEN` · `SHOW_OVERLAY` · `HIDE_OVERLAY` · `ADD_BUSINESS` · `ADD_JOB` ·
`SET_PLAYER` · `ENABLE_TABS` · `UPDATE_TAB_DATA` · `UPDATE_START_BUTTON` ·
`UPDATE_SELL_COOLDOWN` · `UPDATE_MANAGEMENT_COOLDOWN` · `SET_AUDIO_BUTTON` ·
`RESET_AUDIO_BUTTONS` · `SET_MOUSE_INPUT`

`SET_MOUSE_INPUT` is worth noting — the hacker den and fixer apps accept a cursor,
not just d-pad navigation.

The camera app uses `camera_gallery` plus an `instructional_buttons` instance, and
`appcamera.c` steadies the shot from a vehicle with
`TASK_VEHICLE_TEMP_ACTION(ped, veh, 6, 4000)`.

### Every computer has its own soundset

Reusable as-is, no audio authoring required:

| Soundset | Notable sounds |
|---|---|
| `DLC_H3_Arcade_Laptop_Sounds` | `Click_Link`, `Click_Fail` |
| `DLC_GR_MOC_Computer_Sounds` | `Log_In`, `Select_Mission_Cancel`, `Select_Mission_Unavailable`, `Select_Mission_Are_You_Sure` |
| `DLC_GR_Disruption_Logistics_Sounds` | `Click_Link`, `Click_Fail` |
| `Bounty_Office_Computer_Sounds` | rollover and select |
| `DLC_Fixer_Agency_Computer_Soundset` | rollover and select |

Paired with an audio scene while the screen is open, for example
`dlc_ch_arcade_laptop_use_scene`.
