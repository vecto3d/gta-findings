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
