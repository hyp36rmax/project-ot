# Release candidate readiness and installation

**v0.5.0-rc.1 is a privately staged candidate, not an approved public release.** The existing ROM-free ZIP has passed its file audit, but physical and compliance gates remain open. No public download is offered by this proposal.

## Installation and prerequisites

Install the official [Microsoft .NET 10 Runtime x64](https://dotnet.microsoft.com/download/dotnet/10.0) and [Microsoft Visual C++ v14 Redistributable x64](https://aka.ms/vc14/vc_redist.x64.exe). The checked VC++ baseline is 14.51.36247.0 or later. The native host does not require the .NET SDK or Desktop Runtime. Shared Microsoft runtimes are not bundled.

After an approved package is supplied, extract it into a new folder, add your legally obtained compatible archives to root `data/`, and launch `ProjectOT.exe`. Follow [Getting Started](getting-started.md).

## Package layout and rollback

`ProjectOT.exe` remains the entry point. Keep its application dependencies and `runtime/`, `assets/`, `themes/`, `config/`, `data/`, `docs/` and `diagnostics/` together. Runtime variants remain separate under `runtime/Solo-Local/` and `runtime/LAN/`; do not swap them or edit integrity records to bypass a failure.

No game or BIOS content, private logs, saved development preferences, shared .NET runtime, app-local VC++ redistributable or debug symbols belong in the release ZIP. Keep the empty data location available for user-supplied files.

Keep previous installations separate. To roll back, exit this candidate normally and launch the earlier installation. This package does not authorize migration by overwriting another build or Golden Reference.

## Release gates

| Gate | Current status |
| --- | --- |
| RC source/version and frozen runtime hashes | Verified for the private candidate |
| Focused automated qualification | Passed targeted checks; two historical configuration assertions still fail |
| ROM/BIOS-free inventory | Verified for the existing private RC ZIP and current clean staging |
| Physical RC gameplay and recovery | Pending |
| Sustained cross-PC LAN and reported 0xB002 | Unresolved |
| Remaining impact-flash and Windows-dialog checks | Pending |
| Exact runtime corresponding source and complete build/install handoff | Not cleared |
| Recipient source access | Not cleared; repositories remain private |
| Complete third-party notices, applicable relinking material and Experience integration review | Not cleared |
| Public media and asset rights | Pending where not already approved |
| Public distribution | **NO-GO** |

A passing runtime parity test or a repository link does not replace the source and licensing review. Private staging does not waive obligations to recipients. See [Legal](../LEGAL.md) and [Credits](../CREDITS.md).

## Feedback and final approval

Use [F12 Feedback & Diagnostics](feedback.md) for local reports. Complete physical acceptance and all distribution gates before publication. This documentation proposal creates no GitHub Release, tag or visibility change. See the [RC release notes](release-notes-v0.5.0-rc.1.md).
