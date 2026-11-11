# Playing Virtual-On: Oratorio Tangram 5.66 on Windows

PROJECT OT: Virtual On Experience brings the original SEGA NAOMI arcade game together with controller, display, audio and multiplayer controls in one Windows application. Flycast Lean VOOT executes the original software; players use PROJECT OT to set up and manage the experience.

## Availability and Windows environment

**Installation instructions: pending the final distribution package.** The current baseline is `v0.5.0-dev`; no downloadable RC is offered here.

Development and qualification records cover Windows x64 with DX11 rendering. They do not establish a minimum Windows edition/build, CPU, GPU, memory or free-storage requirement for a public release. macOS, Linux and SteamOS parity is not established by these Windows guides.

The current framework-dependent development packaging was checked with Microsoft .NET 10 Runtime x64 and Microsoft Visual C++ v14 x64 Redistributable 14.51.36247.0 or later. The final package must publish its own verified prerequisite list before installation instructions become actionable. Do not infer different package requirements from this development record.

## Game and firmware requirements

The target game is *Virtual-On: Oratorio Tangram M.S.B.S. Ver. 5.66* for SEGA NAOMI. You must supply the game and required firmware through an authorized source. The current private preparation records refer to `vonot.zip`, `naomi.zip`, `jvs13551.zip` and `mie.zip`; the exact required archive revisions and checksums must be confirmed for the final package.

No game or BIOS files are provided here. Do not rename a different game revision to match a filename, post archives in issues, or copy an entire private development installation as a substitute for an approved release. See [legal notes](../LEGAL.md).

## Initial launch — workflow draft

Once an approved package and installation guide are available:

1. Follow that version's extraction, prerequisite and game-data instructions. Keep the whole package together in its documented writable location.
2. Open `ProjectOT.exe` and check the version shown by the application.
3. Open **Settings** from the Title menu. Configure [Controllers](controllers.md), [Display](display.md) and [Audio](audio.md) using the options enabled in that build.
4. Choose **Solo**, or open **Multiplayer** for **Local VS** or **LAN VS**.
5. When finished, use **Return to Title**, then **Exit**. Keep earlier installations and saves separate until upgrade/migration instructions are published.

If data or runtime validation fails, read the displayed message and follow [troubleshooting](troubleshooting.md). A successful application launch does not by itself qualify gameplay or LAN connectivity.

## Choose how to play

- [Solo](solo.md): one player, with a supported controller or the documented P1 keyboard fallback.
- [Local VS](local-vs.md): two players on one PC; each needs independent input ownership, with a physical P2 controller.
- [LAN VS](lan-vs.md): compatible PROJECT OT stations on a local network. Final Match Board acceptance remains pending.

See [known issues](known-issues.md) for specific display and audio limits. [Release information](release-guide.md) will identify the supported configurations for each package.
