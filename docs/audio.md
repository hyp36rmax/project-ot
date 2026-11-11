# Audio output, volume and speaker tests

Open **Settings → Audio** to choose outputs and run speaker tests for the selected session. These endpoint controls currently configure preferences and tests; they do not route live game audio. Existing gameplay audio continues through the build's established output path.

## System Default, Volume and Mute

**System Default** follows the available Windows default render output for configuration and tests. A named output selects that endpoint for the supported test path. If a saved output disappears, the page reports the default fallback rather than treating the missing device as available.

**Volume** and **Mute** are session preferences; player-specific configuration is shown for the Separate layout. Gameplay volume/mute handling is retained, but applying the current Audio-page settings to live gameplay still needs end-to-end acceptance. Check the page's status and release notes rather than assuming a saved choice changed the game output.

The application does not use these settings to change the Windows system master volume. Begin at a comfortable listening level before running a test.

## Speaker Test

Where enabled, choose the left or right speaker test for an available compatible output. The short chime is a separate diagnostic sound. A test-only mute bypass does not mean the game or Windows has been unmuted.

A completed digital test is not proof that the expected physical speaker was audible. Confirm the selected output and channel yourself. If the endpoint is unavailable or incompatible, retain the displayed error instead of assuming a successful route.

## Local VS Shared and Separate Audio

| Choice | Intended use | Current limit |
| --- | --- | --- |
| Shared Audio | A common Local VS output/configuration | Retained gameplay audio is preserved; the current settings/test page is not qualification of a guaranteed new stereo mix. |
| Separate Audio | Player-specific output and volume choices | Per-player endpoint choices and tests exist as configuration. Independent live game routing is not established by those controls. |

Follow only the supported options in the delivered build. Headphones, HDMI outputs, USB devices and mixed hardware need their own physical routing checks. Independent music, announcer or weapon-effect routing is not a verified feature.

If gameplay is silent, check application mute/volume and the Windows output used by that build before changing cabling. Speaker-test success and game-audio success are separate observations. Include both in an [issue report](troubleshooting.md#reporting-a-problem).

Related: [Local VS](local-vs.md), [known issues](known-issues.md), [release guide](release-guide.md).
