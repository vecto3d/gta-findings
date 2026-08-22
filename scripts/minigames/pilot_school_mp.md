# pilot_school_mp.c

Minigames script. 2 anim dicts; 10 models; 14 scaleforms; 3 particle effects.

| | |
|---|---|
| Category | Minigames |
| Total lines | 170,658 |
| Functions | 2,119 (450 unique, 1,669 shared) |
| Unique lines | 25,819 (15.1% of file) |

## Assets

**Animation dictionaries** (2) - `oddjobs@bailbond_mountain`, `oddjobs@basejump@ig_15`

**Models and props** (10) - `s_m_m_pilot_02`, `p_parachute_s`, `s_m_m_marine_01`, `barracks`, `ambulance`, `firetruk`, `rhino`, `lazer`, `freighttrailer`, `phantom`

**Audio banks** (5) - `DLC_PILOTSCHOOL/CITY_LANDING`, `Alarms`, `TARGET_PRACTICE`, `HUD_321_GO`, `SCRIPT\DRUG_TRAFFIC_AIR`

**Sounds** (33) - `DLC_PILOT_Shooting_Range_Sounds`, `move`, `stop`, `HUD_MINI_GAME_SOUNDSET`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `HUD_AWARDS`, `DLC_Pilot_Chase_Parachute_Sounds`, `DLC_PILOT_ENGINE_FAILURE_SOUNDS`, `NO`, `MP_CELEB_SCREEN_SCENE`, `Destroyed`, `NAV_UP_DOWN`, `YES`, `DEATH_SCENE`, `TIMER_STOP`, `10_SEC_WARNING`, `Spawn`, `Jump`, `Grab_Chute_Foley`, `Plane_Wind`, `DLC_PILOT_CITY_LANDING_END_TRANSITION_SCENE`, `engineexplosion`, `DLC_PILOT_CITY_LANDING`, `Generic_Alarm_Fire_Electronic`, `Engine_fail`, `Warning_Tones`, `Landing_Tone`, `DLC_PILOT_CITY_LANDING_MENU_FADE_SCENE`, `MEDAL_GOLD`, `MEDAL_SILVER`, `MEDAL_BRONZE`, `FLIGHT_SCHOOL_LESSON_PASSED`, `QUIT_WHOOSH`

**Scaleform movies** (14) - `SET_SLOT`, `TV_FRAME`, `mission_quit`, `COUNTDOWN`, `RESET_MOVIE`, `STRING`, `TRANSITION_OUT`, `SET_CLEAR_SPACE`, `SET_MAX_WIDTH`, `SET_DATA_SLOT_EMPTY`, `TOGGLE_MOUSE_BUTTONS`, `SET_DATA_SLOT`, `DRAW_INSTRUCTIONAL_BUTTONS`, `SET_BACKGROUND_COLOUR`

**Particle effects** (3) - `scr_veh_plane_gen_damage`, `damage_smoke`, `damage_fire`

**Texture dicts** (6) - `PS_Menu`, `PS_MenuDLC`, `pilotSchool`, `MPMedals_FEED`, `Shared`, `FlightSchool_Logo_256`

**Text labels** (14) - `PS_BLPMTARG`, `PSDAUD`, `NUMBER`, `PS_BLIP_PARA`, `PERCENTAGE`, `PSCHOOL`, `DSCHOOL`, `PS_BLIP_TARGET`, `PS_sFINISH`, `NULL`, `STRING`, `FM_JIP_WAITO`, `OFF`, `PSER_SUCCESS`

**Scenarios** (2) - `WORLD_VEHICLE_DRIVE_SOLO`, `DRIVE`

**Vehicle recordings** (2) - `PilotSchool`, `pilotSchool`

**Timecycle modifiers** (1) - `scanline_cam`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (299), `PLAYER_ID` (131), `DISABLE_CONTROL_ACTION` (100), `NETWORK_DOES_NETWORK_ID_EXIST` (98), `IS_VEHICLE_DRIVEABLE` (97), `GET_ENTITY_COORDS` (88), `IS_ENTITY_DEAD` (76), `DOES_ENTITY_EXIST` (67), `GET_GAME_TIMER` (63), `FLOOR` (58), `GET_TIME_POSITION_IN_RECORDING` (57), `DOES_SHOP_PED_APPAREL_HAVE_RESTRICTION_TAG` (57), `DOES_BLIP_EXIST` (55), `ABSF` (54), `IS_PED_INJURED` (53), `TIMESTEP` (47), `PLAY_SOUND_FROM_ENTITY` (46), `REMOVE_BLIP` (40), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (38), `CLEAR_HELP` (34), `FREEZE_ENTITY_POSITION` (33), `ROUND` (33), `GET_DISTANCE_BETWEEN_COORDS` (31), `HAS_SOUND_FINISHED` (30), `DOES_CAM_EXIST` (30), `GET_SOUND_ID` (29), `RENDER_SCRIPT_CAMS` (27), `SET_ENTITY_ROTATION` (27), `SET_PED_COMPONENT_VARIATION` (27), `NET_TO_VEH` (27)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.4f` x26 · `1.2f` x18 · `0.3f` x13 · `-1744.8f` x9 · `170.5f` x9 · `0.5f` x9 · `64.4f` x7 · `299.2812f` x6 · `-0.5f` x5 · `0.342f` x5 · `0.1f` x4 · `1.5f` x4 · `328.5558f` x3 · `0.2f` x3 · `0.15f` x3 · `0.07f` x3 · `-0.01f` x3 · `-2684.475f` x3 · `2409.234f` x3 · `15.6944f` x3 · `-2857.977f` x3 · `2171.132f` x3 · `33.4674f` x3 · `2.5f` x3

## Other strings

Literals whose consuming native was not classified:

`mp_f_freemode_01`, `pilotSchool`, `PS_METRE`, `mp_m_freemode_01`, `besra`, `PS_SRa`, `SC_LB_EMPTY`, `PS_CITY`, `FlightSchool_Bronze_128`, `HUD_INPUT68`, `PS_BLPKNIFE`, `PS_HUDTARG_B`, `PS_HUDTARG_S`, `PS_HUDTARG_G`, `PS_CP`, `MinigameTransitionIn`, `HAND_SHAKE`, `FlightSchool_Gold_128`, `FlightSchool_Silver_128`, `barracks`, `firetruk`, `PSM_AWARDS_SUB`, `IB_QUIT`, `morph_suit`, `FS_TARGS`, `ambulance`, `lazer`, `PS_ML`, `PS_FLbad`, `PSBARREL_E`

---

Source: `decompiled_scripts/pilot_school_mp.c`
