# UI, scaleforms and screens

Part of the [GTA V decompiled script findings](README.md).

## Phone (`cellphone_controller.c` + ~40 `app*.c`)

The controller is driven almost entirely through scaleform: **108
`SCALEFORM_MOVIE_METHOD` calls**, with `SET_MOBILE_PHONE_POSITION` for placement.
The phone is a scaleform rendered to a render target, not NUI.

App scripts range from tiny to enormous — `appextraction.c` is 8K,
`appinternet.c` is 12M (the whole in-game web), `appbusinesshub.c` and
`apparcadebusiness.c` ~7.5M each. Small ones worth reading as templates:
`appbroadcast.c` (16K), `appchecklist.c` (28K), `apphs_sleep.c` (20K),
`appmedia.c` (20K), `appemail.c` (108K), `appcamera.c` (272K, selfie mode).

GXT label prefix for phone strings is `CELL_*` (`CELL_SIGHTS`, `CELL_SECHACK`,
`CELL_HACKER_ROB`, `CELL_EXTRACT`, `CELL_BOSSAGE`, `CELL_CIRCBREAK`, …).

## Shops — camera and component work, not animation

`shop_controller.c` (9.2M), `clothes_shop_sp.c` (7.6M), `carmod_shop.c` (8.3M),
`tattoo_shop.c` (2.8M), `hairdo_shop_sp.c` (3.4M), `gunclub_shop.c` (3.9M).

Almost no anim dicts. The mechanics are native-driven:

- **Clothing** — `SET_PED_COMPONENT_VARIATION` (101), `SET_PED_PROP_INDEX`,
  `GET_NUMBER_OF_PED_TEXTURE_VARIATIONS`, `SET_PED_MICRO_MORPH`.
- **Car mods** — `GET_NUM_VEHICLE_MODS` (145), `SET_VEHICLE_MOD` (107),
  `SET_VEHICLE_MOD_COLOR_` (45), with 39 `SET_CAM_ACTIVE` / 28 `SET_CAM_PARAMS`
  driving the browsing camera. This is the best reference for a mod-shop camera.
- `ADD_PED_DECORATION_FROM_HASHES` appears ~200 times in *all* shop scripts —
  shared boilerplate, not tattoo-specific.

`gunclub_shop.c` is the only one with a real anim dict:
`ANIM@SCRIPTED@FREEMODE_NPC@FIX_AGY_IG2_REQUISITIONS@`.

## Properties — mostly boilerplate, but named render scaleforms

`am_mp_property_int.c` (18M), `am_mp_car_meet_property.c` (14M),
`am_mp_auto_shop.c` (14M), `am_mp_submarine.c` (13M), `am_mp_arcade.c` (9.7M).

Low yield overall, but the custom sign/board scaleforms are worth knowing:
`CLUBHOUSE_NAME`, `ORGANISATION_NAME`, `AUTO_SHOP_CREW_NAME`,
`BIKER_MISSION_WALL`, and `SECURITY_CAM` (used across nightclub, submarine,
auto shop and property interiors).

`am_mp_car_meet_property.c` carries `SC_LEADERBOARD` for the test-track times.

## Creators

`creator.c` (4.7M), `fm_race_creator.c` (21M), `fm_deathmatch_creator.c` (14M),
`public_mission_creator.c` (13M), plus capture/LTS/survival variants.

Editor UIs rather than mechanics. Their one reusable asset is `camera_gallery`,
and they are the best reference for prop-placement tooling if a server ever
needs an in-game editor.

## Render targets — drawing to an in-world screen

`REGISTER_NAMED_RENDERTARGET` names. This is how anything appears on a screen
prop, and the name must match the model:

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

Pair a render target with one of the terminal scaleforms already catalogued and
you have a working in-world computer with no NUI.

## Notifications

`BEGIN_TEXT_COMMAND_THEFEED_POST` (2650), ended by: `..._TICKER` (1314),
`..._MESSAGETEXT` (868), `..._UNLOCK_TU` (536),
`..._CREWTAG_WITH_GAME_NAME` (292), `..._CREWTAG` (167),
`..._MESSAGETEXT_SUBTITLE_LABEL` (89), `..._UNLOCK` (28), `..._STATS` (17),
`..._AWARD` (13).

The award and unlock variants are the achievement-earned popups.
