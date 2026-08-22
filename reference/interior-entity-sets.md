# Interior entity sets

`ENABLE_INTERIOR_PROP` names, used to swap interior contents at runtime. This is
how property upgrades and decorations are toggled **without loading a different
interior**.

| Entity set | Uses |
|---|---|
| `shutter_closed` | 126 |
| `SET_ACCESS_BLOCKER` | 30 |
| `SET_VAULT_DOOR_OPEN` / `SET_VAULT_DOOR_CLOSED` | 26 each |
| `SET_MOD_BLOCKER` | 26 |
| `SET_GAR_PODIUM_BLOCKER` | 26 |
| `SET_GAR_MOD_BLOCKER` | 26 |
| `SET_ARMORY_BLOCKER` | 26 |
| `VIP_XMAS_DECS` | 20 |
| `SET_PET_DOG` / `SET_PET_CAT` | 18 each |
| `entity_set_tint_options` | 15 |
| `entity_set_office` | 15 |
| `SET_ELEV_STD` | 13 |
| `entity_set_light_option_1` | 12 |
| `SET_GAR_AI_TABLETS_01`–`03` | 12 each |
| `SET_BASE_AI_TABLETS_01`–`03` | 12 each |

`SET_PET_DOG` and `SET_PET_CAT` are worth noting — apartments can have a pet
placed by entity set.

## IPLs

For map pieces not loaded by default, `REQUEST_IPL` / `REMOVE_IPL`. Most-toggled:
`ch_cutscene_casino` (496), `smboat` (146), `hei_carrier` and
`hei_carrier_LODLights` (140), `farmint` / `farmint_cap` (140),
`CS1_02_cf_onmission1`–`4` (140 each), `facelobby` / `facelobbyfake` (138),
`hei_bi_hw1_13_door` (137), `gr_Heist_Yacht2_enginrm` (137).
