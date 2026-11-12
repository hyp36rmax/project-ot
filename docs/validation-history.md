# Physical validation history and final RC scope

PROJECT OT's Solo, linked Local VS and cross-PC LAN VS gameplay were physically validated during development. Controller, display and session-lifecycle acceptance in the tested configurations remains part of that history.

The consolidated gameplay UAT recorded **38/38 PASS**, with **four extended physical endurance sessions exceeding 60 minutes each**. These accepted development results do not mean the complete physical UAT was repeated on the exact final CDI-corrected `v0.5.0-rc.1` public ZIP. No new gameplay tests were run for this documentation correction.

## Completed physical validation

| Area | Accepted development scope |
| --- | --- |
| Solo | Physical gameplay, controls and session lifecycle |
| Local VS | Actual linked gameplay with independent players; Single Display and Dual Display testing |
| Consolidated gameplay UAT | 38/38 PASS |
| Extended endurance | Four physical sessions exceeding 60 minutes each across tested configurations |
| Xbox dual-analog Solo | 10/10 physical PASS |
| Mixed Local VS controllers | Xbox P1 / HORI Twin-Stick EX P2; Tanita Twin-Stick P1 / HORI Twin-Stick EX P2 |
| LAN controller ownership and focus | 9/9 physical PASS |
| Displays | Original 4:3 and Hor+ 16:9 physical acceptance; independent player views and monitor placement; borderless/fullscreen behavior and scoped Alt+Tab tests |
| LAN discovery | Automatic station discovery physically validated across **seven different PC setups** |
| LAN gameplay | Multiple completed cross-PC matches over Ethernet and Wi-Fi, including extended linked sessions; Match Board discovery, challenge, acceptance and readiness |

The seven-setup count is the maintainer's corrected discovery scope. It does not mean seven simultaneously connected PCs, seven-player matches, every pairing or role reversal, or that every setup completed every gameplay test. Tested Xbox/HORI/Tanita combinations do not certify every PlayStation, Brook, Raphnet, adapter or hardware revision.

These physical acceptances are preserved in development records and the maintainer's RC-VALIDATION01 reconciliation. Some historical totals are maintained as reported acceptance without an individual run-to-package hash for every result. They are not reassigned to the final corrected public ZIP. The corrected discovery count and endurance duration are recorded from the maintainer's authoritative reconciliation, not inferred from older preparation reports.

## Automated and native evidence

| Evidence | Recorded result and scope |
| --- | --- |
| Controller-module integration regression | 101/101 automated PASS: 20 Coordinator + 15 presentation + 49 controller + 17 shell checks; not 101 controller-only unit tests |
| DISPLAY-REG01 layout regression | 173 automated PASS: 129 explicit-layout + 44 Automatic-equivalence checks |
| HITFX replay | 295 checks PASS across 20 aspect/render-height combinations |
| Native visual comparisons | 68 unchanged |
| Qualified RC source | 1,189 reported passing focused checks |
| Initial private RC package | 466 focused checks PASS |
| Corrected CDI-excluded runtimes | Release builds and focused engineering checks PASS |
| Corrected runtime source and dependencies | [Public delivery and anonymous access verified](../README.md#runtime-source--licensing) |

These results belong to their recorded stages and are not added together as a new test total. HITFX uses native replay of captured primitives at five render heights and four aspects; it is not physical gameplay acceptance of every preset/aspect. The 173 layout checks do not by themselves prove first-frame GPU output. Native captures and engineering checks supplement, rather than replace, physical acceptance.

### Historical configuration results

Two older assertions, `configuration-unit / shared-space-dash-default-preserved` and `configuration-native / corrupt-config-host-and-workers-exit-zero`, failed on earlier baselines. The later RC readiness record retains them separately and does not count them in its 1,189 passing focused checks. It does not establish that both were rerun or fixed.

Their present corrected-RC impact remains unqualified. Describing them as confirmed current failures is too broad; describing them as resolved would also be unsupported. Historical evidence remains retained for maintainer disposition, without suppressing the failures or changing working behavior to satisfy them.

## Remaining final-RC qualification

- The complete physical UAT was **not repeated** on the exact final corrected public ZIP.
- Specific controller reconnection, reassignment, ambiguous-device and return-to-Title combinations remain to be qualified on that package.
- Selected first-frame aspect checks, monitor/DPI recovery and additional Alt+Tab/device-topology cases remain open. Prior accepted display and Alt+Tab tests are not erased.
- Higher-resolution live HITFX coverage remains open, including the reported missing sides at 1440p/4K. The passing replay does not establish a live correction.
- Intermittent `NETWORK ERROR` / `0xB002`, a previously observed Wi-Fi dropout, reversed network roles and repeated reconnect/failure recovery remain under investigation. Development match completion does not promise universal reliability.
- Twelve-hour Solo/Local VS, monitor sleep/disconnection and sudden-power-loss qualification remain future work; the four completed hour-plus endurance sessions are distinct from those longer targets.
- Audible final-RC routing and actual Windows authorization/reuse/denial observations remain separate scoped checks.

The accepted LANNET-08 Ethernet session that ended intentionally is not a confirmed transport failure. Keep deliberate session exit separate from unexpected link loss when reporting a problem.

Gameplay validation is separate from the Experience source-scope, installation and recipient-terms review. Neither physical acceptance nor public runtime-source delivery establishes full legal compliance. See [Known Issues](known-issues.md), [release status](release-guide.md#release-gates) and [legal notes](../LEGAL.md).
