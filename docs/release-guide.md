# Release preparation and installation guide

**No public download or approved installation package is available through this foundation.** Installation steps are pending the final distribution layout. The current software baseline remains `v0.5.0-dev`; documentation V1.0 is not a software RC promotion.

## What an approved release must identify

| Item | Required release information |
| --- | --- |
| Version | Product version, channel and package identity shown by the offered application |
| Download | Approved repository/release destination and exact package filename; no speculative links |
| Windows support | Tested Windows x64 environment and verified prerequisites for that package |
| Installation | Full extraction/layout, writable-location requirements, launch and upgrade/rollback steps |
| Player-owned data | Required game/firmware revision, filenames/checksums and where the user supplies them |
| Runtime dependencies | Exact verified Microsoft/other runtime requirements and approved installation routes |
| Release notes | Actual changes and limitations of the offered build |
| Integrity | SHA-256 for the final offered artifact; checksum instructions tied to that file |
| Source and notices | Applicable licenses, attribution, complete corresponding-source route and checked recipient access |
| Support | Issue-reporting instructions and privacy/redaction guidance |

## Installation section — pending

The final guide must tell players which package to use, how to check it, which prerequisites to install, where authorized data belongs and how to start `ProjectOT.exe`. It must also explain how to retain existing settings/saves during upgrades. Those paths and migration steps are not frozen by this draft.

Current development packaging has external .NET/Visual C++ prerequisites recorded in [Getting Started](getting-started.md). Verify them against the final artifact rather than assuming that every future package has the same dependency layout. Do not distribute a private development ZIP as a public substitute.

## Release acceptance

Confirm the actual Solo, Local VS and LAN VS scope; device/display/audio combinations; permission and recovery behavior; known issues; and complete-match/cleanup checks. Settings screenshots and automated fixtures do not establish physical acceptance.

Complete the separate licensing, corresponding-source, dependency-notice and asset-rights review for the actual package. Verify that recipients can reach the required source and supporting materials. Exclude unauthorized game/BIOS archives, private diagnostics and machine-specific preferences.

## Player reporting and future notes

Publish the final [known issues](known-issues.md) with each approved package. Ask players to report the version, mode, configuration and smallest reproducible problem through the relevant issue form, following [privacy guidance](troubleshooting.md#reporting-a-problem).

No release binary, tag, public visibility change or download is created by this documentation branch. See [legal notes](../LEGAL.md) and [credits](../CREDITS.md).
