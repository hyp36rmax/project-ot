# Audio output, volume and speaker tests

Open **Settings → Audio** and choose Solo or Local VS. The page offers System Default or named outputs, Master Volume, Mute and speaker tests.

**Current limitation:** output selection and Shared/Separate choices configure preferences and tests; they do not route live game audio. Existing gameplay sound uses the build's established output path. Applying the current page's volume/mute settings to gameplay also needs end-to-end acceptance. This is the audio-routing limit referenced by the other guides.

## Choose an output and level

**System Default** follows the Windows default render output for configuration and tests. A named output selects that device for the test path. Start at a comfortable listening level, then adjust **Master Volume** or **Mute**. These preferences do not change the Windows system master volume.

Use the mouse or keyboard to adjust the slider. With a controller, Confirm enters volume editing, Up/Down adjusts the level, and Confirm or Back finishes editing.

## Speaker Test

Choose an enabled left or right speaker test. The short chime is a separate sound and can run without a game. A test-only mute bypass does not unmute the game or Windows.

Listen for the expected physical speaker; a completed digital test alone cannot confirm it. If the output is unavailable or incompatible, retain the displayed error. When reporting silence, distinguish the speaker test from gameplay sound.

## Local VS Shared and Separate Audio

| Choice | Configuration |
| --- | --- |
| Shared Audio | Common output and volume preferences for Local VS. |
| Separate Audio | Player-specific output and volume preferences where enabled. |

These choices have the routing limitation above. A shared stereo mix and independent player outputs still require physical acceptance for the actual package. Music, announcer and weapon-effect routing are not separate supported controls.

## Saved settings and unavailable devices

Valid changes save automatically for the selected session mode; wait for the saved status before closing. Solo and Local VS retain their own preferences. If a named device disappears, the page reports a System Default fallback. Check the selected output after reconnecting rather than assuming the saved device is available.

Use Restore Defaults only for the current Audio settings when offered. If saving or loading reports an error, retain the message and existing files; do not delete the complete configuration directory.

Related: [Local VS](local-vs.md), [troubleshooting](troubleshooting.md#audio-or-speaker-tests-are-silent), [known issues](known-issues.md).
