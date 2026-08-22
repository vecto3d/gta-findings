# nigel1d.c

SP strangers and freaks script. 2 anim dicts; 13 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 50,872 |
| Functions | 568 (88 unique, 480 shared) |
| Unique lines | 5,136 (10.1% of file) |

## Assets

**Animation dictionaries** (2) - `mini@golf`, `rcmnigel1d`

**Animations** (14) - `rcmnigel1d`, `mini@golf`, `swing_a_mark`, `swing_b_mark`, `thanks_male_03`, `iron_idle_high_b`, `iron_swing_intro_high`, `iron_swing_action_high`, `swing_outro`, `swing_react_bad_02`, `idle_c`, `thanks_male_05`, `idle_a`, `idle_a_friend_watching`

**Models and props** (13) - `a_m_y_golfer_01`, `prop_golf_wood_01`, `s_m_m_highsec_01`, `s_m_y_valet_01`, `s_m_m_security_01`, `prop_golf_putter_01`, `u_m_m_markfost`, `prop_golf_bag_01`, `s_m_y_doorman_01`, `s_m_m_bouncer_01`, `u_m_m_aldinapoli`, `caddy`, `prop_golf_iron_01`

**Sounds** (4) - `NIGEL_1D_SCENE`, `NIGEL_1D_SOUNDSET`, `COLLECT_IN_BAG`, `COLLECT_OUT_BAG`

**Text labels** (11) - `NIG1DAU`, `FOSTENBURG`, `TREVOR`, `THUNDER`, `NIGEL`, `MRSTHORNHILL`, `CONCIERGE`, `COP`, `NULL`, `OVERCAST`, `NIGEL1D`

**Scenarios** (3) - `WORLD_HUMAN_GUARD_STAND`, `WORLD_HUMAN_CLIPBOARD`, `WORLD_VEHICLE_DRIVE_SOLO`

**Waypoint recordings** (4) - `NIGEL1DGOLF`, `NIGEL1DGOLF2`, `NIGEL1DTRANS`, `NIGEL1DCRASH`

**Relationship groups** (1) - `SecurityGroup`

**Vehicle mods** (1) - `gauntlet`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (193), `IS_ENTITY_AT_ENTITY` (43), `GET_GAME_TIMER` (42), `HAS_MODEL_LOADED` (28), `IS_PED_IN_VEHICLE` (26), `ATTACH_ENTITY_TO_ENTITY` (25), `TASK_PLAY_ANIM` (20), `PLAYER_ID` (18), `TASK_TURN_PED_TO_FACE_ENTITY` (17), `WAIT` (16), `GET_IS_WAYPOINT_RECORDING_LOADED` (16), `GET_PED_BONE_INDEX` (16), `DOES_ENTITY_EXIST` (16), `SET_MODEL_AS_NO_LONGER_NEEDED` (16), `IS_ENTITY_ATTACHED` (15), `DETACH_ENTITY` (15), `OPEN_SEQUENCE_TASK` (15), `CLOSE_SEQUENCE_TASK` (15), `TASK_PERFORM_SEQUENCE` (15), `CLEAR_SEQUENCE_TASK` (15), `GET_ENTITY_COORDS` (14), `REQUEST_MODEL` (14), `CLEAR_PRINTS` (14), `IS_MESSAGE_BEING_DISPLAYED` (14), `SET_PED_COMBAT_ATTRIBUTES` (13), `SET_PED_FLEE_ATTRIBUTES` (13), `REMOVE_WAYPOINT_RECORDING` (10), `SET_PED_CAN_BE_TARGETTED` (10), `IS_PED_IN_ANY_VEHICLE` (10), `CLEAR_PED_TASKS` (9)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.06f` x6 · `0.04f` x6 · `0.5f` x6 · `0.8f` x6 · `-1073.19f` x6 · `342.05f` x6 · `63.32832f` x6 · `-966.24f` x6 · `411.05f` x6 · `84.82043f` x6 · `0.1f` x5 · `-0.25f` x5 · `-577.274f` x5 · `270.6505f` x5 · `-543.1793f` x5 · `315.2973f` x5 · `0.2f` x4 · `-1.3f` x4 · `-1122.202f` x3 · `48.5724f` x3 · `51.4652f` x3 · `-1076.233f` x3 · `92.1041f` x3 · `60.0617f` x3

## Other strings

Literals whose consuming native was not classified:

`Nigel1DCelebSecurity`, `NIG1D_SECUR`, `caddy`, `NIG1D_SECUR_4`, `NIG1D_HIT`, `NIG1D_SECUR_6`, `N1D_TAKE`, `NIG1D_FLEE`, `N1D_COLLECT`, `player`, `Replay skipping to stage `, `NIGEL1DAMBIENTGOLFER1`, `GENERIC_CURSE_MED`, `NIG1D_SECUR_3`, `GENERIC_SHOCKED_HIGH`, `NIG1D_SECUR_5`, `NIG1D_BUMPF`, `NIG1D_BANK`, `NIG1D_SECUR_1`, `NIG1D_OUTFIT`, `Reattaching bag to buggy!?`, `Reattaching club to bag!?`, `Glen still holding club, reattach to bag`, `Celeb dead - returning true`, `VEHICLE HEALTH IS `, `GENERIC_FUCK_YOU`, `MS_GET_THE_CLUB`, `NIGEL_1D_GOLF_CART_A`, `premier`, `Force cleanup [TERMINATING]`

---

Source: `decompiled_scripts/nigel1d.c`
