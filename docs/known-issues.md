# Known issues and support limits

The software baseline is `v0.5.0-dev`. Final installation instructions and package-specific release notes remain pending. These limits identify unfinished checks without treating established Solo, Local VS or controller/display support as experimental.

## Current limits

| Area | Limit |
| --- | --- |
| Controllers | Known profiles do not certify every hardware revision, adapter or connection. See the [profile table](controllers.md#known-profiles-and-physical-coverage). |
| Display | Not every aspect, quality, monitor and Windows-scaling combination has been tested. Newer stacked Hor+ layouts still need active-match acceptance. |
| Audio endpoints | Saved output choices and speaker tests do not route live game audio. Separate outputs, shared-mix behavior and physical channels need end-to-end acceptance. |
| Pause | Linked gameplay may continue while the menu is open. Current Solo/cabinet pause-presentation changes need final physical checks. |
| LAN VS | Wired Ethernet is recommended and wireless LAN is supported. Automatic discovery depends on Windows, adapter and router settings; use [Direct Connect](lan-vs.md#direct-connect-fallback) where available. The current Match Board and full cross-PC workflow still need final release acceptance. |
| Recovery | Device/display reconnect and invalid-configuration recovery have not been qualified for every setup. Do not delete a complete settings directory as a reset. |
| Rendering effects | A reported missing-side impact effect at higher internal resolutions remains unresolved in live testing. Include aspect, quality and affected player/side in reports. |
| Menu presentation | Recent Title/Pause visual changes still need physical acceptance in the integrated build. |

## Outside the current feature set

Vertical expansion, internet NETPLAY, rollback, spectators and experimental haptics are not supported player features. These Windows guides do not establish macOS, Linux or SteamOS parity.

[Report a problem](troubleshooting.md#reporting-a-problem) with a small, redacted reproduction record. A discovered LAN station or successful connection is separate from a completed linked match.

## Documentation still pending

The approved [development-history narrative](development-history.md), final public installation steps, complete third-party notices and distribution/source-access review remain open. The approved project introduction is preserved in the [README](../README.md).
