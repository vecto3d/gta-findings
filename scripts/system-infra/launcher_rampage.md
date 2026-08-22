# launcher_rampage.c

System and infrastructure script. 10 models; 1 scaleforms.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 26,263 |
| Functions | 377 (40 unique, 337 shared) |
| Unique lines | 5,291 (20.1% of file) |

## Assets

**Animations** (13) - `hipster_idle`, `hipster_post_post_irony`, `hipster_self_hating_hipster`, `misstrvram_2`, `hipster_cunts_in_america`, `marines_idle_a`, `marines_idle_b`, `thugs_idle_b`, `thugs_idle_a`, `mexicans_idle_a`, `mexicans_idle_b`, `redneck_idle_a`, `redneck_idle_b`

**Models and props** (10) - `prop_table_03b_chr`, `prop_chair_01a`, `prop_npc_phone`, `s_m_y_marine_03`, `ig_ramp_gang`, `ig_ramp_mex`, `ig_ramp_hipster`, `prop_table_01`, `ig_ramp_hic`, `prop_beer_bottle`

**Scaleform movies** (1) - `DISPLAY_VIEW`

**Text labels** (2) - `RAMP2AU`, `NULL`

**Scenarios** (1) - `Rampage1`

**Relationship groups** (1) - `player`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (97), `WAIT` (20), `CLEAR_PED_PROP` (18), `DOES_ENTITY_EXIST` (16), `PLAYER_PED_ID` (14), `NETWORK_IS_GAME_IN_PROGRESS` (13), `FREEZE_ENTITY_POSITION` (11), `REQUEST_MODEL` (11), `HAS_MODEL_LOADED` (11), `SET_MODEL_AS_NO_LONGER_NEEDED` (11), `SET_PED_NAME_DEBUG` (10), `TASK_SYNCHRONIZED_SCENE` (7), `CLEAR_HELP` (6), `GET_ENTITY_COORDS` (6), `REQUEST_ANIM_DICT` (6), `HAS_ANIM_DICT_LOADED` (6), `CREATE_SYNCHRONIZED_SCENE` (6), `TASK_PLAY_ANIM` (6), `SET_SYNCHRONIZED_SCENE_LOOPED` (5), `SET_GAMEPLAY_ENTITY_HINT` (5), `TASK_LOOK_AT_ENTITY` (5), `SET_GAMEPLAY_HINT_CAMERA_BLEND_TO_FOLLOW_PED_MEDIUM_VIEW_MODE` (5), `SET_GAMEPLAY_HINT_BASE_ORBIT_PITCH_OFFSET` (5), `SET_GAMEPLAY_HINT_CAMERA_RELATIVE_SIDE_OFFSET` (5), `SET_GAMEPLAY_HINT_CAMERA_RELATIVE_VERTICAL_OFFSET` (5), `SET_GAMEPLAY_HINT_FOLLOW_DISTANCE_SCALAR` (5), `SET_GAMEPLAY_HINT_FOV` (5), `REQUEST_WEAPON_ASSET` (5), `IS_ENTITY_ATTACHED_TO_ENTITY` (4), `SET_PED_TO_RAGDOLL` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x4 · `0.9f` x3 · `0.35f` x3 · `5.1f` x2 · `0.95f` x2 · `0.3f` x2 · `-0.9f` x2 · `-1297.84f` x2 · `2505.91f` x2 · `19.34f` x2 · `-0.5f` x2 · `-401.7374f` x2 · `1.5f` x1 · `-0.1f` x1 · `0.15f` x1 · `0.5f` x1 · `-177.0628f` x1 · `-1679.715f` x1 · `33.16263f` x1 · `-157.0628f` x1 · `-1659.715f` x1 · `37.16263f` x1 · `-1855.4f` x1 · `-0.85f` x1

## Other strings

Literals whose consuming native was not classified:

`gun_root`, `WAPClip`, `WAPSupp`, `WAPScop`, `WAPFlshLasr`, `WAPSupp_2`, `component_at_ar_flsh`, `component_gunrun_mk2_upgrade`, `WAPGrip`, `component_at_ar_afgrip`, `component_at_ar_supp`, `WAPScop_2`, `component_at_ar_supp_02`, `component_at_scope_medium`, `component_at_pi_flsh`, `WAPFlshLasr_2`, `component_at_pi_supp`, `component_at_sights`, `WAPGrip_2`, `component_at_muzzle_01`, `component_at_muzzle_02`, `component_at_muzzle_03`, `component_at_muzzle_04`, `component_at_muzzle_05`, `component_at_muzzle_06`, `component_at_muzzle_07`, `component_at_scope_macro`, `component_at_scope_max`, `component_at_ar_afgrip_02`, `RAMP_HELP_TRIG`

---

Source: `decompiled_scripts/launcher_rampage.c`
