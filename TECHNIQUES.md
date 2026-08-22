# Techniques index

Every non-obvious technique recovered from the decompile, in one place. These are the
findings a string search cannot produce — each came from reading a script, or from
surveying the shape of its calls.

Ordered within each group by how much work it saves.

## Animation

| Technique | What it replaces | Where |
|---|---|---|
| `GET_ANIM_INITIAL_OFFSET_POSITION` / `_ROTATION` | Hand-tuned approach offsets. Ask the animation where the ped must stand | [animation-alignment](reference/animation-alignment.md) |
| `FIND_ANIM_EVENT_PHASE(dict, clip, "WalkInterruptible", ...)` | Guessed phase cutoffs for breaking out | [animation-alignment](reference/animation-alignment.md) |
| MoVE networks | Sync scenes, when the animation must respond to input | [move-networks](reference/move-networks.md) |
| `TASK_PLAY_ANIM_ADVANCED` | A sync scene, when you only need one clip placed exactly | [minigames-toolkit](features/minigames-toolkit.md) |
| `PLAY_FACIAL_ANIM` on its own track | Blank-faced peds | [jukebox](features/jukebox.md) |
| `PLAY_SYNCHRONIZED_ENTITY_ANIM` | Bone-attaching a prop that should move with a scene | [safehouse-drinking](features/safehouse-drinking.md) |
| Chaining scenes at phase `0.9`, not `1.0` | Visible seams between enter, loop and exit | [beds](features/beds.md) |

## Tasks and AI

| Technique | What it replaces | Where |
|---|---|---|
| `OPEN_SEQUENCE_TASK` / `CLOSE_SEQUENCE_TASK` | Per-frame task juggling | [task-sequences](reference/task-sequences.md) |
| `TASK_FLUSH_ROUTE` / `TASK_EXTEND_ROUTE` / `TASK_FOLLOW_POINT_ROUTE` | Hand-rolled patrol loops | [street-characters](features/street-characters.md) |
| `TASK_FOLLOW_WAYPOINT_RECORDING` | Authoring a patrol path at all — 184 ship with the game | [waypoint index](reference/waypoint-recording-index.md) |
| The three driver flags | Hired drivers who bail at the first gunshot | [npc-drivers](features/npc-drivers.md) |
| `SET_PED_KEEP_TASK` | Peds stopping dead when your script releases them | [scripted-scene-hygiene](features/scripted-scene-hygiene.md) |
| `IS_VEHICLE_STUCK_TIMER_UP` | Polling positions to detect a stuck vehicle | [random-events](features/random-events.md) |
| `GET_CLOSEST_VEHICLE_NODE` before a drop-off | Vehicles stranded on kerbs | [npc-drivers](features/npc-drivers.md) |
| Ambient, gesture and evasive-dive flags | "My animation keeps getting interrupted" | [ped-control-flags](features/ped-control-flags.md) |

## Cameras and world

| Technique | What it replaces | Where |
|---|---|---|
| `USE_SCRIPT_CAM_FOR_AMBIENT_POPULATION_ORIGIN_THIS_FRAME` | Empty streets under a drone or scope | [telescope](features/telescope.md) |
| `SET_CAM_CONTROLS_MINI_MAP_HEADING` | A minimap that ignores where you are looking | [telescope](features/telescope.md) |
| `SET_CAM_ACTIVE_WITH_INTERP` | Repositioning one camera per frame | [minigames-toolkit](features/minigames-toolkit.md) |
| Cutscene exit state plus a drifting camera | A visible jump out of a cutscene | [cutscenes-and-streaming](reference/cutscenes-and-streaming.md) |
| `NEW_LOAD_SCENE_START` | Pop-in after any teleport or spawn | [cutscenes-and-streaming](reference/cutscenes-and-streaming.md) |
| `GET_OFFSET_FROM_ENTITY_GIVEN_WORLD_COORDS` | Manual rotation maths | [coordinate-transforms](reference/coordinate-transforms.md) |
| `SUPRESS_RANDOM_EVENT_THIS_FRAME` | Muggings interrupting your scripted scene | [scripted-scene-hygiene](features/scripted-scene-hygiene.md) |
| Attach, do not chase | Jittering passengers on moving platforms | [coordinate-transforms](reference/coordinate-transforms.md) |
| Swap the prop for an off-state model | Faking "off" with a black texture | [tv-and-channels](features/tv-and-channels.md) |
| A collision proxy lerped alongside an animated prop | Invisible walls at animated doors | [animated-door-collision](features/animated-door-collision.md) |

## UI

| Technique | What it replaces | Where |
|---|---|---|
| Named render targets | NUI for an in-world screen | [tv-and-channels](features/tv-and-channels.md) |
| `MIDSIZED_MESSAGE` with `HUD_AWARDS` | A custom achievement popup | [notifications](reference/notifications.md) |
| `mission_complete` as a parameterised service | A results screen per minigame | [results-screen](features/results-screen.md) |
| `BEGIN_SCALEFORM_MOVIE_METHOD_ON_FRONTEND` | Building your own pause menu | [pause-menu-and-buttons](features/pause-menu-and-buttons.md) |
| `CALL_SCALEFORM_MOVIE_METHOD_WITH_*` | BEGIN, push, END boilerplate | [results-screen](features/results-screen.md) |
| `BEGIN_TEXT_COMMAND_SCALEFORM_STRING` | Getting formatted times and names into a movie | [results-screen](features/results-screen.md) |
| `DRAW_SCALEFORM_MOVIE_3D` | A render target, when the surface is not a linkable model | [minigames-toolkit](features/minigames-toolkit.md) |
| Sprite-drawn minigames | A scaleform or NUI overlay | [hotwire-minigame](features/hotwire-minigame.md) |
| `DOES_TEXT_LABEL_EXIST` | Raw text keys appearing on screen | [scripted-scene-hygiene](features/scripted-scene-hygiene.md) |

## Audio

| Technique | What it replaces | Where |
|---|---|---|
| Audio scene variables written per frame | Fading a sound on a timer | [audio](reference/audio.md) |
| `SET_VARIABLE_ON_SOUND` | Discrete beeps for a continuous state | [hotwire-minigame](features/hotwire-minigame.md) |
| `CB_RADIO_SFX` squelch | Authoring radio audio | [world-state-and-comms](features/world-state-and-comms.md) |
| `HIDDEN_RADIO_*` stations | Streaming your own ambient music | [jukebox](features/jukebox.md) |
| `HUD_FRONTEND_DEFAULT_SOUNDSET` | Inventing menu sounds players will not recognise | [jukebox](features/jukebox.md) |
| `PLAY_SYNCHRONIZED_AUDIO_EVENT` | Timer-started audio that drifts from the animation | [random-events](features/random-events.md) |
| `GET_SOUND_ID_FROM_NETWORK_ID` | Local sound ids that do not survive the network | [scripted-scene-hygiene](features/scripted-scene-hygiene.md) |

## Entities and state

| Technique | What it replaces | Where |
|---|---|---|
| Bone `28422` versus `57005` | Props sitting wrong in a ped hand | [random-events](features/random-events.md) |
| `CREATE_PICKUP_ROTATE` with a custom model | Faking a pickup with a prop and a distance check | [random-events](features/random-events.md) |
| `ADD_PICKUP_TO_INTERIOR_ROOM_BY_NAME` | Pickups silently invisible indoors | [collectible-hunts](features/collectible-hunts.md) |
| Decorators keyed by player hash | A server-side ownership table for vehicles | [vehicle-huds-and-cameras](features/vehicle-huds-and-cameras.md) |
| `SET_VEHICLE_MODEL_IS_SUPPRESSED` | A scripted car lost among identical traffic | [random-events](features/random-events.md) |
| `APPLY_PED_DAMAGE_DECAL` | Tracking injury only in variables | [cutscenes-and-streaming](reference/cutscenes-and-streaming.md) |
| `GET_RANDOM_VEHICLE_IN_SPHERE` | Spawning when the world already has one | [random-events](features/random-events.md) |
| `TIMESTEP` scaling | Minigames that are easier at high frame rates | [hotwire-minigame](features/hotwire-minigame.md) |
| `GET_NETWORK_TIME` | Local clocks in anything timed | [hotwire-minigame](features/hotwire-minigame.md) |
| Detach before delete | Attached entities that will not delete | [vending-machine](features/vending-machine.md) |

## Structure

| Technique | What it replaces | Where |
|---|---|---|
| The object brain skeleton | A per-frame distance loop that never terminates | [object-brain-pattern](features/object-brain-pattern.md) |
| Host and participant split | Ad-hoc "who owns this" logic | [random-events](features/random-events.md) |
| One engine, many props, branch on model | Nine copies of the same interaction | [safehouse-drinking](features/safehouse-drinking.md) |
| A numbered stat series for collectibles | Bespoke storage per hunt | [collectible-hunts](features/collectible-hunts.md) |
| Bit flags over a struct of bools | State that is awkward to sync | [hotwire-minigame](features/hotwire-minigame.md) |
| Cycle a variant index instead of re-rolling | The same clip twice in a row | [safehouse-drinking](features/safehouse-drinking.md) |

## Three that cost us time

1. **An attached entity will not delete.** Detach first, always.
2. **Model does not imply identity.** The soda machines share models, so a machine
   cannot tell you which brand it dispenses.
3. **Animations are authored data.** Only `PLYR_BUY_DRINK_PT1/2/3` exist game-wide;
   there is no alternate button-press clip to swap in.
