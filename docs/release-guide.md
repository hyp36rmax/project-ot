# Release candidate readiness and installation

**[v0.5.0-rc.1 is available as a public Release Candidate](https://github.com/hyp36rmax/project-ot/releases/tag/v0.5.0-rc.1).** Solo, Local VS and LAN VS have extensive physical development acceptance. The published ROM-free ZIP and matching corrected runtime source have verified identities. The final corrected RC full physical cycle was not repeated; selected recovery/hardware checks and the separate Experience licensing review remain open. Publication does not establish full compliance clearance.

## Installation and prerequisites

Install the official [Microsoft .NET 10 Runtime x64](https://dotnet.microsoft.com/download/dotnet/10.0) and [Microsoft Visual C++ v14 Redistributable x64](https://aka.ms/vc14/vc_redist.x64.exe). The checked VC++ baseline is 14.51.36247.0 or later. The native host does not require the .NET SDK or Desktop Runtime. Shared Microsoft runtimes are not bundled.

Extract the public RC ZIP into a new folder, add your legally obtained compatible archives to root `data/`, and launch `ProjectOT.exe`. Follow [Getting Started](getting-started.md).

## Package layout and rollback

`ProjectOT.exe` remains the entry point. Keep its application dependencies and `runtime/`, `assets/`, `themes/`, `config/`, `data/`, `docs/` and `diagnostics/` together. Runtime variants remain separate under `runtime/Solo-Local/` and `runtime/LAN/`; do not swap them or edit integrity records to bypass a failure.

No game or BIOS content, private logs, saved development preferences, shared .NET runtime, app-local VC++ redistributable or debug symbols belong in the release ZIP. Keep the empty data location available for user-supplied files.

Keep previous installations separate. To roll back, exit this candidate normally and launch the earlier installation. This package does not authorize migration by overwriting another build or Golden Reference.

## Validation history

| Area | Validated status |
| --- | --- |
| Solo gameplay | Physically validated |
| Local VS gameplay | Physically validated |
| LAN VS gameplay | Physically validated |
| Consolidated gameplay UAT | 38/38 PASS |
| Extended endurance | Four physical sessions exceeding 60 minutes |
| Controller configurations | Xbox, HORI and Tanita tested in documented combinations |
| Display configurations | Physical and automated testing completed within documented scope |
| LAN station discovery | Physically validated across 7 different PC setups |
| Cross-PC LAN gameplay | Completed matches over Ethernet and Wi-Fi, including extended sessions |
| Final CDI-corrected runtime builds | Build/focused checks PASS |
| Additional RC recovery and hardware coverage | Continuing |
| Final corrected RC full physical retest | Not repeated |

Seven is the discovery setup count, not simultaneous PCs or every test on every setup. These development acceptances retain their historical scope; see [validation history](validation-history.md) for controller/display evidence, provenance and final-RC limits. The four hour-plus sessions do not replace future 12-hour and monitor/power-recovery targets.

## Release gates

| Gate | Current status |
| --- | --- |
| RC version and corrected runtime hashes | Verified against the public RC ZIP; see [matching hashes](../README.md#runtime-source--licensing) |
| Focused automated qualification | Qualified RC source: 1,189 reported passing checks; initial private package: 466 focused PASS |
| ROM/BIOS-free inventory | Verified for the published RC ZIP |
| Final corrected RC full physical cycle | Not repeated; accepted development gameplay is retained above |
| Intermittent LAN 0xB002 and selected role/recovery cases | Open; completed Ethernet/Wi-Fi matches and extended sessions are retained |
| Remaining impact-flash and Windows-dialog checks | Pending |
| Native-runtime source, dependencies, build materials, notices and hosted interfaces | [Published for both corrected variants](https://github.com/hyp36rmax/flycast-lean-voot/releases/tag/source-v0.5.0-rc.1-corrected) |
| Recipient access to native-runtime source | Anonymous download and checksums verified |
| Additional Experience source-scope, installation obligations and recipient terms | Unresolved; proposed terms remain subject to approval |
| Public media and asset rights | Pending where not already approved |
| Public availability | RC download available; full compliance clearance not claimed |

A passing runtime parity test or public native-runtime source delivery does not settle the Experience integration boundary or waive obligations to recipients. Independent bit-for-bit reproducibility has not been established. See [Legal](../LEGAL.md) and [Credits](../CREDITS.md).

The two older configuration failures are retained as [historical results](validation-history.md#historical-configuration-results), not established current corrected-RC failures or proven fixes. The later focused PASS totals do not show that both assertions were rerun.

## Feedback and final approval

Use [F12 Feedback & Diagnostics](feedback.md) for local reports. Additional final-RC recovery/hardware checks and the remaining Experience licensing decisions are pending; completed development acceptance remains established. These maintained documentation corrections do not change the published release description, ZIP, assets or tag. See the [RC release notes](release-notes-v0.5.0-rc.1.md).
