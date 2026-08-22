# Jukeboxes and hidden radio stations

**Source:** `ob_jukebox.c` (read in full, 2,107 unique lines, 65 unique functions)

The largest object brain by unique function count, and the one with the most
immediately reusable payload: **the list of radio stations that exist in the game
but never appear in a vehicle radio wheel.**

## Hidden radio stations

Jukeboxes tune to stations the normal radio does not expose. The script maps a menu
index to a station name:

`HIDDEN_RADIO_BIKER_CLASSIC_ROCK` · `HIDDEN_RADIO_BIKER_MODERN_ROCK` ·
`HIDDEN_RADIO_BIKER_HIP_HOP` · `HIDDEN_RADIO_BIKER_PUNK` ·
`HIDDEN_RADIO_ARCADE_POP` · `HIDDEN_RADIO_ARCADE_DANCE` ·
`HIDDEN_RADIO_ARCADE_EDM` · `HIDDEN_RADIO_ARCADE_MIRROR_PARK` ·
`HIDDEN_RADIO_ARCADE_WWFM` · `HIDDEN_RADIO_37_MOTOMAMI` ·
`HIDDEN_RADIO_34_DLC_HEI4_KULT` · `HIDDEN_RADIO_THE_LAB` · `HIDDEN_RADIO_FLYLO` ·
`HIDDEN_RADIO_IFRUIT` · `HIDDEN_RADIO_MLR` · `HIDDEN_RADIO_12_REGGAE` ·
`HIDDEN_RADIO_17_FUNK` · `HIDDEN_RADIO_06_COUNTRY` · `HIDDEN_RADIO_15_MOTOWN` ·
`RADIO_36_AUDIOPLAYER`

These are station identifiers usable with the standard radio natives. For a FiveM
server this is a ready-made source of ambient music for bars, clubhouses and
interiors that does not need a single streamed audio file, because the content
already ships with the game.

`RADIO_36_AUDIOPLAYER` is the self-radio slot and behaves differently from the rest.

## Volume ducking

The part most implementations miss. The script runs an audio scene and drives a
named variable on it:

    START_AUDIO_SCENE("dlc_ch_arcade_music_volume")
    SET_AUDIO_SCENE_VARIABLE("dlc_ch_arcade_music_volume", "ArcadeRadioVolumeDucking", value)

So the music level is a continuous value pushed into a scene variable, not a
toggle. That is how the volume falls off with distance and ducks under dialogue
instead of cutting out.

Audio scene variables are a general mechanism worth knowing — any scene can expose
named floats the script drives per frame.

## Menu feel

The selection UI uses the standard frontend soundset, and it is worth copying the
mapping exactly because players recognise it:

| Action | Sound | Soundset |
|---|---|---|
| Move selection | `NAV_UP_DOWN` | `HUD_FRONTEND_DEFAULT_SOUNDSET` |
| Confirm | `SELECT` | `HUD_FRONTEND_DEFAULT_SOUNDSET` |
| Rejected | `ERROR` | `HUD_FRONTEND_DEFAULT_SOUNDSET` |
| Back out | `BACK` | `HUD_FRONTEND_DEFAULT_SOUNDSET` |

Payment goes through the `service_spend_jukebox` transaction.

## Models

Three, each looked up with `GET_CLOSEST_OBJECT_OF_TYPE` within 2m:

- `ch_prop_arcade_jukebox_01a` — arcade
- `xm3_prop_xm3_jukebox_01a` — agency
- `bkr_prop_clubhouse_jukebox_01a` — biker clubhouse

## Also here: paired facial animation

Not from the jukebox but worth recording alongside it. `ob_mp_stripper.c` plays a
**facial animation on its own track** next to the body animation, via
`PLAY_FACIAL_ANIM(ped, facialClip, facialDict)`, for every stage of its routine.

Facial clips are a separate dictionary and a separate call. Skipping them is why
custom animated peds tend to look blank-faced while the body moves correctly. The
same script positions the player with `TASK_PED_SLIDE_TO_COORD` rather than a walk,
and drives its peds through network ids so the animation is shared.

## Related

- [../reference/audio](../reference/audio.md)
- [nightclub](nightclub.md)
- [object-brain-pattern](object-brain-pattern.md)
