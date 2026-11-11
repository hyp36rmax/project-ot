# Displays, aspect ratios and rendering quality

Open **Settings → Display** from the Title menu. Choose the session type, arrangement, monitor assignment and rendering quality before starting play. Enabled options depend on the build and its capability checks.

## Original 4:3 and Hor+ widescreen rendering

Original **4:3** remains the reference presentation. **16:9** is the primary modern widescreen target; **21:9-class** and **32:9** modes use expanded horizontal presentation where the specific configuration is qualified.

Hor+ widescreen rendering keeps the original vertical framing while showing more world horizontally. It is not a stretched 4:3 picture. Flycast Lean VOOT's rendering and guest-visibility work is documented in the [runtime repository](https://github.com/hyp36rmax/flycast-lean-voot). A matched runtime scene or a selectable aspect option does not establish acceptance of every stage, HUD behavior or Local VS layout.

Historical original-aspect and selected widescreen checks exist. The full combination of aspect, quality, session mode and physical monitor still needs a release-specific qualification matrix. Genuine vertical-expansion layouts remain research, not a supported player option.

## Rendering Quality

Retained quality settings use internal render heights of **480, 720, 1080, 1440 and 2160** pixels. The documented High setting is 1080p. Internal rendering quality is separate from the physical monitor size and the arrangement preview.

Start with a qualified setting for your build. Higher internal resolution can increase graphics work; these guides do not establish a minimum GPU or guarantee performance at 1440p/2160p. Quality changes may require returning to Title and starting a new session.

## Single Display, Mirror and Dual Display VS

| Arrangement | What it means | Qualification |
| --- | --- | --- |
| Single Display | Solo uses one view; Local VS places both player views on one monitor | Accepted retained configurations exist. Layout depends on aspect and build; broader stacked Hor+ variants still require active-match acceptance. |
| Dual Display Mirror | The same presentation on two outputs | Gated/unavailable in the retained qualified backend. A preview or visible option does not establish working mirroring. |
| Dual Display VS | Independent Local VS player views on separate displays | Retained implementation and historical gameplay checks exist. Monitor/DPI/reconnect combinations still need final package acceptance. |

The retained 32:9 Single Display Local VS path uses fitted side-by-side views. Later 4:3/16:9/21:9 stacked Hor+ arrangements have separate validation limits; use them only where the delivered build enables and qualifies them. Do not infer layout from a monitor's marketing aspect label alone.

## Monitor assignment and safe recovery

Select the intended primary and, where applicable, secondary monitor. Use **Identify** when enabled, inspect the arrangement preview, and use **Swap Screens** if the build offers it. Independent Local VS outputs require independent displays; duplicated Windows outputs are not equivalent to two player surfaces.

Supported live geometry previews offer **Keep/Revert** with a 15-second confirmation deadline. Keep only when the image and assignments are correct. Otherwise choose Revert or let the preview time out. An arrangement preview confirms the requested layout, not final gameplay rendering.

Return to Title before changing cabling, desktop topology or a setting that requires a new session. Monitor loss and reconnect recovery still have qualification limits; seamless live migration is not promised. If recovery fails, close normally, preserve the error message and consult [troubleshooting](troubleshooting.md). Do not delete preferences as an undocumented reset procedure.

Related: [Local VS](local-vs.md), [known issues](known-issues.md), [release guide](release-guide.md).
