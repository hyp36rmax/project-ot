# PROJECT OT v0.5.0-rc.1

**Virtual-On Oratorio Tangram Experience**

Our first Release Candidate brings the original NAOMI 5.66 experience to modern Windows hardware through our customized Flycast Lean runtime and Project OT Experience framework.

**[v0.5.0-rc.1 is available as a public Release Candidate](https://github.com/hyp36rmax/project-ot/releases/tag/v0.5.0-rc.1).** Core gameplay has extensive accepted physical development testing. Matching corrected native-runtime source is public, with anonymous retrieval verified. The complete physical cycle was not repeated on the exact final corrected RC. Experience source-scope, installation obligations and proposed recipient terms remain separate open decisions; availability is not a claim of full compliance clearance.

## What's included

### Solo

- Single-player NAOMI 5.66 gameplay.
- Modern controller support.
- Expanded display configurations.

### Local VS

- Two-player linked gameplay on one Windows PC.
- Single Display and Dual Display VS options, with independent player views and controls.
- Approved stacked layouts at effective 4:3, 16:9 and 21:9, and side-by-side at effective 32:9 for Single Display.

### LAN VS

- Linked gameplay across two Windows systems using the retained LAN implementation.
- Match Board discovery, challenge, acceptance and readiness, plus Direct Connect configuration.
- The existing LAN implementation has completed physical Ethernet/Wi-Fi cross-PC matches and extended sessions. Intermittent `NETWORK ERROR` / `0xB002`, a previously observed Wi-Fi dropout and selected role/recovery cases remain open; this RC does not claim a networking fix or universal reliability.

Wired Ethernet is recommended. Discovery depends on Windows, adapters and router settings. Internet NETPLAY VS, rollback and spectators are not offered features.

### Controllers

- Compatible Xbox/XInput and PlayStation-style gamepads; PlayStation devices need an appropriate compatible XInput setup.
- Twin-Stick configuration and mapping through the established hardware profiles.
- Analog calibration, player assignment, controller settings and Test Controls.

Available profiles do not certify every hardware revision, adapter or wiring arrangement. Claim a controller by holding Start for 750 ms, releasing, then tapping Start to confirm. Check both players before linked play.

### Display

- 4:3, 16:9, 21:9 and 32:9 options in supported configurations.
- Existing approved Hor+ rendering corrections, preserving original vertical framing while expanding horizontal visibility.
- F6 Aspect Ratio in eligible Solo Single Display sessions only.
- F7 Display Information for the focused cabinet.
- F8 FPS.

Rendering quality includes Original 480p, Performance 720p, High 1080p, Ultra 1440p and 4K 2160p. These presets are distinct from Windows desktop resolution. No FPS, latency or new performance improvement is claimed by this release preparation.

### Experience

- Project OT Title and Pause menus.
- Controller, Display, Audio and Gameplay settings, including Arcade Cabinet Mode settings.
- F12 Feedback & Diagnostics.
- Hidden Settings module-version labels in RC while retaining the main application version and diagnostic metadata.
- Framework-dependent Windows x64 packaging, separate Solo/Local and LAN runtimes, integrity verification and coordinated session cleanup.

Fresh audio defaults are 100% Master Volume and Mute Off. Explicit saved preferences remain respected. Gameplay-triggered rumble is not an offered feature.

## Installation

For the [public RC download](https://github.com/hyp36rmax/project-ot/releases/tag/v0.5.0-rc.1):

1. Use a Windows x64 PC with a compatible graphics/input environment for the DX11 runtime. These notes do not introduce a new minimum CPU, GPU or Windows-version certification.
2. Install the official [Microsoft .NET 10 Runtime x64](https://dotnet.microsoft.com/en-us/download/dotnet/10.0). The native Experience does not require the SDK or Desktop Runtime.
3. Install the official [Microsoft Visual C++ v14 Redistributable x64](https://aka.ms/vc14/vc_redist.x64.exe). The recorded checked baseline is 14.51.36247.0 or later.
4. Verify the approved ZIP checksum and extract the complete application into a new ordinary local folder. Do not run from the ZIP or overwrite an older installation or Golden Reference. Existing path-safety checks can reject linked/reparse-backed folders.
5. Keep the complete directory structure together. Put your compatible, legally obtained `vonot.zip` and required `naomi.zip` in root `data/`, not inside either runtime directory.
6. Launch `ProjectOT.exe`, claim and test controllers, and choose the appropriate session's Display and Audio settings before play.

No ROM or BIOS archives are included. Shared .NET and app-local VC++ runtime DLLs are not bundled. Do not launch internal runtime executables directly or edit integrity records to bypass an error.

See [Getting Started](docs/getting-started.md), [Controllers](docs/controllers.md), [Display](docs/display.md) and [Audio](docs/audio.md) for the existing candidate guidance.

## Completed development validation

- Consolidated gameplay UAT: **38/38 PASS**, including accepted Solo, linked Local VS and cross-PC LAN VS gameplay.
- Four recorded extended physical endurance sessions exceeding 60 minutes each.
- Xbox dual-analog Solo: **10/10 physical PASS**; Xbox P1 / HORI Twin-Stick EX P2 and Tanita P1 / HORI Twin-Stick EX P2 Local VS physically verified.
- LAN controller ownership and focus: **9/9 physical PASS**.
- Original 4:3, Hor+ 16:9, Single Display and Dual Display VS, independent monitor placement, borderless/fullscreen behavior and scoped Alt+Tab testing.
- Automatic station discovery across **seven different PC setups**. This is discovery coverage across development, not seven simultaneous PCs or every gameplay test on all seven.
- Multiple completed cross-PC matches over Ethernet and Wi-Fi, extended linked sessions, and Match Board discovery/challenge/acceptance/readiness.

Engineering evidence includes the 101/101 combined controller-integration regression, 173 display checks, 295 native HITFX replay checks across 20 aspect/render-height targets, and 68 unchanged native visual comparisons. Qualified RC source recorded 1,189 reported passing checks; the initial private RC package passed 466 focused checks. Corrected CDI-excluded runtime builds and focused checks passed. These are stage-specific results, not a new aggregate or physical test count. See [validation history and evidence scope](docs/validation-history.md).

## Release Candidate notes

This is an initial Release Candidate with accepted development gameplay history. Some hardware combinations, display configurations and recovery paths require additional validation. **The complete physical UAT was not repeated on the exact final CDI-corrected public ZIP.** Historical acceptance is retained without treating it as that additional cycle.

### Remaining RC qualification

Known limitations retained from the qualified reports:

- Intermittent LAN `0xB002`, a previously observed Wi-Fi dropout, reversed-role tests and repeated failure/reconnect recovery remain open. The accepted Ethernet session that ended intentionally is not classified as a confirmed transport failure.
- Selected final-RC first-frame aspect checks, controller reconnection/reassignment/return-to-Title combinations, monitor/DPI recovery and additional Alt+Tab cases remain open. Earlier accepted gameplay, display and Alt+Tab tests are retained. The earlier Solo-to-Title navigation report was not reproduced on a recorded physical retest; these notes do not claim a new input correction.
- Horizontal damage-flash coverage at higher render heights still has remaining physical checks.
- Named Audio endpoint and Separate Audio settings do not qualify independent live-cabinet routing. Audible RC routing checks remain deferred.
- Actual Windows security prompt timing, authorization reuse and denial recovery remain unqualified; the reported Local VS firewall-dialog trigger is unresolved. Never disable protection or create broad exceptions as a workaround.
- Linked gameplay may continue behind the Experience menu. Selected final-RC cleanup and device/display recovery combinations remain under qualification; prior session-lifecycle acceptance is retained.
- Separate 12-hour Solo/Local VS, monitor sleep/disconnect and sudden-power-loss targets remain future qualification, distinct from the four accepted hour-plus endurance sessions.

These are recorded limitations and deferred checks, not newly reproduced defects or new physical PASS results. See [Known Issues](docs/known-issues.md). Optional enhancements remain deferred.

## Feedback

Press F12 at Title, Settings or gameplay for **Feedback & Diagnostics**. Select context and Working / Issue Found / Not Tested, add optional details or tester alias, then use **Export Report + Diagnostics**.

Reports are exported locally; nothing is uploaded automatically. Review diagnostic data before sharing. Include version, play mode, controller setup, aspect/quality and a short reproduction sequence. Do not attach game/BIOS archives or unnecessary personal information. ESC closes the form and restores its prior context.

## Credits and source

SEGA and the original Virtual-On creators made the game this project preserves. [Flycast](https://github.com/flyinghead/flycast), flyinghead and its contributors provide the runtime foundation, building on [reicast](https://github.com/skmp/reicast-emulator) and other contributors. See [Credits](CREDITS.md) for the existing acknowledgments.

The [corrected runtime source release](https://github.com/hyp36rmax/flycast-lean-voot/releases/tag/source-v0.5.0-rc.1-corrected) supplies both matching runtime variants, dependencies, build materials, notices and hosted protocol documentation. Anonymous access and checksums were verified. See [Runtime Source & Licensing](README.md#runtime-source--licensing) for the executable and source-bundle hashes. Independent bit-for-bit build reproducibility is not established.

The published native-runtime source includes the CDI-exclusion correction. Any additional Experience host/interface/build/install source obligations remain unresolved, and the proposed Experience recipient terms still require maintainer approval and a supported licensing determination. Public runtime source delivery does not establish full distribution clearance or grant rights to third-party material.

PROJECT OT is an unofficial fan project, not affiliated with or endorsed by SEGA. Original game content, artwork and trademarks remain with their respective owners. No game or BIOS material is supplied, and no additional rights are granted by these release notes.
