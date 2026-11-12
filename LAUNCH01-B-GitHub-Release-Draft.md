# LAUNCH01-B — GitHub Release draft

Locally prepared release content only. No GitHub Release object, tag, upload, visibility change or new repository has been created. Continue in the existing private `hyp36rmax/project-ot`; the separate landing-page proposal is not executed.

## Release settings for later approval

- Title: **PROJECT OT v0.5.0-rc.1**.
- Version/tag proposal: `v0.5.0-rc.1` — tag does not exist and is not created here.
- Repository: existing private `hyp36rmax/project-ot`.
- Proposed target: approved main checkpoint `166721ebd170a8d6bb57d9c59541568eb0dcdfbb`; if documentation is later merged, record the specifically approved final target rather than silently moving it.
- Release classification: prerelease, subject to final approval.
- Current attachments: **none**.
- Current public release-file decision: **none approved**; keep the qualified ZIP unchanged and local.

The description below links existing documentation at the approved private checkpoint for review. Those links are not asserted to be publicly accessible. It contains no link claiming public corresponding-source access. Repository publication requires its separate current/history/media review; this task does not clear a visibility change.

## Conditional attachment list

1. `ProjectOT_v0.5.0-rc.1_Win64_PRIVATE_UAT.zip` only if its exact name/bytes, effective recipient terms, rights and release-file decision are approved. SHA-256: `6B0779C70258E88BF0078E13F84AB6D4A97966F78B91738CFE0BEDBCC4F03484`.
2. Complete approved source delivery for both variants: the nine existing handoff files with dependencies/build instructions and any legally required interface/relink/install additions. Hosting, layout, final hashes and actual recipient access remain pending.
3. Final applicable license/notice/recipient-terms materials and checksum manifest, after approval. The review notice tree alone is not clearance.

Full file/source/notice identities are in [the release inventory](LAUNCH01-B-Release-File-Inventory.txt). No binary/source file is committed or attached by this branch.

## Mandatory gates

- CDI/GPL compatibility for both frozen runtimes (B01).
- Experience/runtime licensing scope and recipient terms (B05).
- Asset rights, generated resources, apphost/component requirements and final notices (B02–B04, B06–B08).
- Actual complete recipient corresponding-source access and final documented references (B09–B10).
- Exact release-file selection, final publication approval and any separate repository-visibility authorization.

Optional enhancements and extended physical UAT remain deferred. Physical RC UAT is not marked passed. No automatic merge, public binary release, package rename or GitHub attachment is authorized here.

## Prepared Release description

# PROJECT OT v0.5.0-rc.1

**Virtual-On Oratorio Tangram Experience**

Our first Release Candidate brings the original NAOMI 5.66 experience to modern Windows hardware through our customized Flycast Lean runtime and Project OT Experience framework.

**Private release preparation: no public RC download is available or authorized yet.** Redistribution and complete recipient source access remain mandatory gates. These notes describe the candidate scope, not a cleared public offering.

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
- The existing LAN runtime and transport remain unchanged. Sustained cross-PC reliability and the reported `NETWORK ERROR` / `0xB002` remain unresolved; a successful discovery or Ready state is not a completed-match reliability qualification.

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

Once a public package is approved:

1. Use a Windows x64 PC with a compatible graphics/input environment for the DX11 runtime. These notes do not introduce a new minimum CPU, GPU or Windows-version certification.
2. Install the official [Microsoft .NET 10 Runtime x64](https://dotnet.microsoft.com/en-us/download/dotnet/10.0). The native Experience does not require the SDK or Desktop Runtime.
3. Install the official [Microsoft Visual C++ v14 Redistributable x64](https://aka.ms/vc14/vc_redist.x64.exe). The recorded checked baseline is 14.51.36247.0 or later.
4. Verify the approved ZIP checksum and extract the complete application into a new ordinary local folder. Do not run from the ZIP or overwrite an older installation or Golden Reference. Existing path-safety checks can reject linked/reparse-backed folders.
5. Keep the complete directory structure together. Put your compatible, legally obtained `vonot.zip` and required `naomi.zip` in root `data/`, not inside either runtime directory.
6. Launch `ProjectOT.exe`, claim and test controllers, and choose the appropriate session's Display and Audio settings before play.

No ROM or BIOS archives are included. Shared .NET and app-local VC++ runtime DLLs are not bundled. Do not launch internal runtime executables directly or edit integrity records to bypass an error.

See [Getting Started](https://github.com/hyp36rmax/project-ot/blob/166721ebd170a8d6bb57d9c59541568eb0dcdfbb/docs/getting-started.md), [Controllers](https://github.com/hyp36rmax/project-ot/blob/166721ebd170a8d6bb57d9c59541568eb0dcdfbb/docs/controllers.md), [Display](https://github.com/hyp36rmax/project-ot/blob/166721ebd170a8d6bb57d9c59541568eb0dcdfbb/docs/display.md) and [Audio](https://github.com/hyp36rmax/project-ot/blob/166721ebd170a8d6bb57d9c59541568eb0dcdfbb/docs/audio.md) for the existing candidate guidance.

## Release Candidate notes

This is an initial Release Candidate. Some hardware combinations, display configurations and network environments require additional validation. **Physical RC UAT is deferred by maintainer decision; it is not recorded as passed.**

Known limitations retained from the qualified reports:

- Sustained cross-PC gameplay, completed-match reliability and the reported LAN `0xB002` remain open.
- Physical first-frame aspect checks, controller reconnection/return-to-Title combinations, monitor/DPI recovery and Alt+Tab still need qualification. The earlier Solo-to-Title navigation report was not reproduced on a recorded physical retest; these notes do not claim a new input correction.
- Horizontal damage-flash coverage at higher render heights still has remaining physical checks.
- Named Audio endpoint and Separate Audio settings do not qualify independent live-cabinet routing. Audible RC routing checks remain deferred.
- Actual Windows security prompt timing, authorization reuse and denial recovery remain unqualified; the reported Local VS firewall-dialog trigger is unresolved. Never disable protection or create broad exceptions as a workaround.
- Linked gameplay may continue behind the Experience menu. Physical cleanup and device/display recovery combinations remain under qualification.
- Long endurance, monitor sleep/disconnect and power-loss testing remain later qualification.

These are recorded limitations and deferred checks, not newly reproduced defects or new physical PASS results. See [Known Issues](https://github.com/hyp36rmax/project-ot/blob/166721ebd170a8d6bb57d9c59541568eb0dcdfbb/docs/known-issues.md). Optional enhancements remain deferred.

## Feedback

Press F12 at Title, Settings or gameplay for **Feedback & Diagnostics**. Select context and Working / Issue Found / Not Tested, add optional details or tester alias, then use **Export Report + Diagnostics**.

Reports are exported locally; nothing is uploaded automatically. Review diagnostic data before sharing. Include version, play mode, controller setup, aspect/quality and a short reproduction sequence. Do not attach game/BIOS archives or unnecessary personal information. ESC closes the form and restores its prior context.

## Credits and source

SEGA and the original Virtual-On creators made the game this project preserves. [Flycast](https://github.com/flyinghead/flycast), flyinghead and its contributors provide the runtime foundation, building on [reicast](https://github.com/skmp/reicast-emulator) and other contributors. See [Credits](https://github.com/hyp36rmax/project-ot/blob/166721ebd170a8d6bb57d9c59541568eb0dcdfbb/CREDITS.md) for the existing acknowledgments.

The required corresponding-source recipient mechanism for both modified runtimes is not yet verified. No working public corresponding-source link is asserted here. Complete exact variant source, dependency/build materials and any required covered interface/install material must be delivered under the applicable terms before binary publication. Adding an upstream link alone does not satisfy that gate.

CDI/GPL compatibility, Experience/runtime licensing, asset rights, final notices, recipient source access and final release approval remain mandatory. The existing private-only package terms also need an approved recipient-facing resolution. Prepared notices and source hashes are evidence, not distribution permission.

PROJECT OT is an unofficial fan project, not affiliated with or endorsed by SEGA. Original game content, artwork and trademarks remain with their respective owners. No game or BIOS material is supplied, and no additional rights are granted by these release notes.
