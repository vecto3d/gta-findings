# animal_controller.c

Ambient world script. 26 anim dicts; 35 models; 3 scaleforms.

| | |
|---|---|
| Category | Ambient world |
| Total lines | 107,933 |
| Functions | 662 (79 unique, 583 shared) |
| Unique lines | 4,816 (4.5% of file) |

## Assets

**Animation dictionaries** (26) - `random@peyote@dog`, `random@peyote@fish`, `random@peyote@bird`, `random@peyote@deer`, `creatures@pug@amb@peyote@enter`, `facials@creatures@retriever@bark`, `facials@creatures@pug@bark`, `random@peyote@generic`, `creatures@retriever@amb@peyote@enter`, `creatures@rottweiler@amb@peyote@enter`, `random@peyote@eat`, `random@peyote@cat`, `creatures@boar@amb@peyote@enter`, `creatures@cat@amb@peyote@enter`, `creatures@cow@amb@peyote@enter`, `creatures@coyote@amb@peyote@enter`, `creatures@deer@amb@peyote@enter`, `creatures@cougar@amb@peyote@enter`, `creatures@pig@amb@peyote@enter`, `creatures@rabbit@amb@peyote@enter`, `creatures@hen@amb@peyote@enter`, `facials@creatures@rottweile@bark`, `random@peyote@eatswimming`, `random@peyote@rabbit`, `random@peyote@chicken`, `SWIMMING@BASE`

**Models and props** (35) - `ig_orleans`, `a_c_hen`, `a_c_fish`, `a_c_sharkhammer`, `a_c_sharktiger`, `a_c_stingray`, `a_c_pigeon`, `a_c_cormorant`, `prop_peyote_lowland_01`, `prop_peyote_highland_02`, `a_c_dolphin`, `a_c_mtlion`, `a_c_boar`, `a_c_cow`, `a_c_coyote`, `a_c_killerwhale`, `a_c_crow`, `a_c_seagull`, `a_c_chickenhawk`, `prop_peyote_lowland_02`, `prop_peyote_highland_01`, `prop_peyote_water_01`, `prop_peyote_gold_01`, `a_c_rabbit_01`, `a_c_rottweiler`, `a_c_cat_01`, `a_c_deer`, `a_c_husky`, `a_c_pig`, `a_c_poodle`, `a_c_pug`, `a_c_retriever`, `a_c_shepherd`, `a_c_westy`, `prop_peyote_chunk_01`

**Audio banks** (1) - `Taxi_Vomit`

**Sounds** (10) - `PEYOTE_TRANSITION_OUT_SCENE`, `PLAYER_AS_ANIMAL_LAND_SCENE`, `PEYOTE_TRANSITION_IN_SCENE`, `PLAYER_AS_ANIMAL_AIR_SCENE`, `PLAYER_AS_ANIMAL_WATER_SCENE`, `PLAYER_AS_SASQUATCH_SCENE`, `HUD_AWARDS`, `PEYOTE_ATTRACT_SOUNDSET`, `PEYOTE_COMPLETED`, `COLLECTED`

**Speech contexts** (5) - `DROWNING`, `SPEECH_PARAMS_FORCE_FRONTEND`, `WAVELOAD_PAIN_MICHAEL`, `WAVELOAD_PAIN_FRANKLIN`, `WAVELOAD_PAIN_TREVOR`

**Scaleform movies** (3) - `SHOW_SHARD_MIDSIZED_MESSAGE`, `SHARD_ANIM_OUT`, `MIDSIZED_MESSAGE`

**Text labels** (34) - `BARK`, `NONE`, `CALL`, `EXCITED`, `HEN`, `PIG`, `SQUAWK`, `PIGEON`, `COO`, `ANIMLAU`, `SEAGULL`, `CORMORANT`, `NULL`, `RABBIT`, `DOLPHIN`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `ROTTWEILER`, `HUSKY`, `CROW`, `RETRIEVER`, `FLIGHT`, `BOAR`, `CAT`, `COW`, `COYOTE`, `DEER`, `MTLION`, `ROAR`, `SASQUATCH`, `CHICKENHAWK`, `SCREECH`, `SHEPHERD`

**Scenarios** (2) - `WORLD_MOUNTAIN_LION_REST`, `WORLD_MOUNTAIN_LION_WANDER`

**Stats** (1) - `num_hidden_packages_5`

**Hashed names** (4) - `interrupt`, `Create_Peyote`, `Destroy_Peyote`, `Ragdoll`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (125), `GET_GAME_TIMER` (39), `DISABLE_CONTROL_ACTION` (37), `SET_BIT` (35), `CLEAR_BIT` (32), `PLAYER_ID` (27), `IS_STRING_NULL_OR_EMPTY` (21), `SET_MODEL_AS_NO_LONGER_NEEDED` (20), `DOES_ENTITY_EXIST` (12), `IS_ENTITY_DEAD` (11), `GET_ENTITY_COORDS` (10), `ARE_STRINGS_EQUAL` (9), `REMOVE_ANIM_DICT` (9), `IS_AUDIO_SCENE_ACTIVE` (8), `START_AUDIO_SCENE` (8), `REQUEST_MODEL` (7), `GET_ENTITY_MODEL` (7), `GET_RANDOM_INT_IN_RANGE` (7), `IS_CONTROL_PRESSED` (7), `VDIST2` (6), `HAS_MODEL_LOADED` (6), `SET_ENTITY_COORDS` (6), `SET_ENTITY_HEADING` (6), `SET_ENTITY_INVINCIBLE` (6), `ANIMPOSTFX_IS_RUNNING` (6), `IS_PLAYER_PLAYING` (6), `HAS_ANIM_DICT_LOADED` (6), `SET_PLAYER_CONTROL` (6), `STOP_SOUND` (5), `RELEASE_SOUND_ID` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x6 · `-0.5f` x2 · `0.1f` x2 · `1.5f` x2 · `0.33f` x1 · `0.4f` x1 · `-1031.02f` x1 · `-399.0387f` x1 · `37.4325f` x1 · `-1027.634f` x1 · `-397.8321f` x1 · `38.1158f` x1 · `-1026.092f` x1 · `-397.068f` x1 · `37.5389f` x1 · `-1033.187f` x1 · `-400.7195f` x1 · `38.1248f` x1 · `-1034.797f` x1 · `-401.579f` x1 · `37.6024f` x1

## Other strings

Literals whose consuming native was not classified:

`PeyoteEndIn`, `PEYOTE_ATTRACT_SEA_CREATURE`, `PeyoteIn`, `SEA_CREATURE`, `eat_peyote_cam1`, `eat_peyote_cam2`, `PEYOTE_TRANSITION_OUT`, `PEYOTE_ATTRACT_SMALL_DOG`, `PEY_L_A`, `SMALL_DOG`, `foggy`, `DisableReplayScriptStreamRecording`, `PEY_L`, `PEYOTE_TRANSITION_IN`, `ANIML_FWST`, `ANIML_FWST2`, `ANIML_TWST2`, `eat_peyote`, `eat_peyote_plantpot_cam1`, `PEYOTE_ATTRACT_HEN`, `SAS_BANK_01`, `PEYOTE_ATTRACT_HUSKY`, `PEY_TITLE`, `PEY_COLLECT`, `His quarry seemed familiar.`, `CM_ANIBOAR`, `CM_ANICAT`, `CM_ANICOW`, `CM_ANICOY`, `CM_ANIDEE`

---

Source: `decompiled_scripts/animal_controller.c`
