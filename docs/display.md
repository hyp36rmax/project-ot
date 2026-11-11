# Displays, aspect ratios and rendering quality

Open **Settings → Display** from the Title menu to choose the session, display arrangement, monitors and rendering quality before playing.

## Original 4:3 and Hor+ widescreen rendering

Original **4:3** is the reference presentation. **16:9** is the primary modern presentation, with expanded **21:9-class** and **32:9** rendering in supported configurations.

Hor+ widescreen rendering preserves the original vertical framing while showing more world horizontally. It does not stretch the 4:3 picture. See the [Flycast Lean VOOT rendering documentation](https://github.com/hyp36rmax/flycast-lean-voot) for the runtime's projection and visibility work.

Support does not mean every stage, aspect, quality and monitor combination has been tested. Check [known issues](known-issues.md) for configuration-specific limits. Vertical expansion is not a supported display mode.

## Rendering Quality

Rendering Quality settings use internal render heights of **480, 720, 1080, 1440 and 2160** pixels; **High** uses 1080p. Internal resolution is separate from the monitor's desktop resolution and the arrangement preview.

Higher quality increases graphics work. Choose a setting that runs consistently on your PC; performance at 1440p or 2160p is not guaranteed. Return to Title and start a new session when a quality change requires it.

## Single Display and Dual Display VS

| Arrangement | Player presentation |
| --- | --- |
| Single Display | The default for Solo and Local VS. Solo uses one view; Local VS places both player views on one monitor. |
| Dual Display VS | Local VS with independent player views on separate physical displays. |

The established 32:9 Single Display Local VS layout uses fitted side-by-side views. Newer stacked Hor+ arrangements for 4:3, 16:9 and 21:9 still need active-match acceptance in the final package; use the layout supported by your build.

## Monitor selection and placement

Select the intended monitor for Single Display. For Dual Display VS, assign a separate physical display to each player and check the arrangement preview. Use **Identify** when enabled to locate a monitor, and **Swap Screens** where offered to exchange player placement. Windows display duplication does not provide two independent player views.

Monitor layout, Windows scaling and reconnect behavior can vary. Confirm both views are visible and assigned correctly before starting a match.

## Safe display-setting recovery

Live geometry previews provide **Keep/Revert** with a 15-second confirmation deadline. Choose Keep only when the image and assignments are correct. Otherwise choose Revert or let the preview time out.

Return to Title before changing cabling, Windows display topology or settings that require a new session. If a monitor is lost or a change cannot be recovered, close normally and retain the displayed error for [troubleshooting](troubleshooting.md). Do not delete preferences as an undocumented reset.

Related: [Local VS](local-vs.md), [known issues](known-issues.md), [release guide](release-guide.md).
