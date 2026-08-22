# am_mp_hotwire.c

MP ambient script. 1 scaleforms.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 5,740 |
| Functions | 157 (19 unique, 138 shared) |
| Unique lines | 934 (16.3% of file) |

## Assets

**Sounds** (17) - `DLC_XM17_IAA_Hack_Minigame_Scene`, `Output_Highlight`, `Input_Highlight`, `Damage`, `Background_Loop`, `Hack_Success`, `Hack_Success_Remote`, `Test_Circuit`, `Wire_01`, `Wire_02`, `Wire_03`, `Wire_04`, `Hack_Fail`, `Hack_Fail_Remote`, `Grab_Wire`, `Attach_Wire`, `Error`

**Scaleform movies** (1) - `HACKING_MESSAGE`

**Texture dicts** (12) - `MPHotwire`, `leftnode_roll`, `rightnode_roll`, `leftnode`, `rightnode`, `lifelight`, `correctlight`, `wronglight`, `failed`, `passed`, `load_bar`, `Cursor_0`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DRAW_SPRITE` (13), `IS_USING_KEYBOARD_AND_MOUSE` (11), `SET_BIT` (9), `PLAY_SOUND_FRONTEND` (9), `CLEAR_BIT` (8), `PLAYER_PED_ID` (7), `PLAYER_ID` (6), `IS_CONTROL_JUST_PRESSED` (6), `ROUND` (5), `TO_FLOAT` (5), `DISABLE_CONTROL_ACTION` (5), `SET_VARIABLE_ON_SOUND` (5), `TIMESTEP` (5), `GET_CONTROL_NORMAL` (4), `NETWORK_IS_GAME_IN_PROGRESS` (3), `ABSI` (3), `GET_TIME_DIFFERENCE` (3), `GET_NETWORK_TIME` (3), `SIN` (3), `ADD_TEXT_COMPONENT_INTEGER` (2), `HAS_SCALEFORM_MOVIE_LOADED` (2), `SET_PLAYER_CONTROL` (2), `GET_SOUND_ID` (2), `SET_INPUT_EXCLUSIVE` (2), `IS_AUDIO_SCENE_ACTIVE` (2), `SET_PED_CONFIG_FLAG` (2), `PLAY_SOUND_FROM_ENTITY` (2), `SET_STREAMED_TEXTURE_DICT_AS_NO_LONGER_NEEDED` (1), `COPY_SCRIPT_STRUCT` (1), `NETWORK_REGISTER_HOST_BROADCAST_VARIABLES` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x8 · `0.17f` x5 · `1.01f` x4 · `0.062f` x4 · `0.35f` x2 · `0.164f` x2 · `0.056f` x2 · `0.344f` x2 · `0.127f` x2 · `0.612f` x2 · `1.5f` x2 · `0.019f` x2 · `0.001f` x2 · `0.4f` x1 · `0.1f` x1 · `0.455f` x1 · `0.456f` x1

## Other strings

Literals whose consuming native was not classified:

`HWSF_QT`, `HWSF_CONN`, `HWSF_MWRE`, `HWSF_SEL`, `HWSF_MCUR`, `BEAM_TR`, `HWSF_TST`, `HTWR_PSY`, `HTWR_HLP2_PC`, `HTWR_HLP2`, `HTWR_HLP_PC`, `HTWR_HLP`, `BEAM_F`, `MC_PLAY`, `BEAM_P`, `HWTUT_SEL_PC`, `HWTUT_SEL`, `HWTUT_WIRE`, `HWTUT_SELR_PC`, `HWTUT_SELR`, `HWTUT_TEST`, `HWTUT_FINAL`, `HWTUT_LIVES`, `DLC_XM17_IAA_SF_Hack`

---

Source: `decompiled_scripts/am_mp_hotwire.c`
