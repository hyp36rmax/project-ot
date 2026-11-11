# Known issues and support limits

The software baseline is `v0.5.0-dev`. Final installation instructions and package-specific release notes remain pending. These limits identify unfinished checks without treating established Solo, Local VS or controller/display support as experimental.

## Current limits

| Area | Limit |
| --- | --- |
| Controllers | Known profiles do not certify every hardware revision, adapter or connection. See the [profile table](controllers.md#known-profiles-and-physical-coverage). |
| Display | Not every aspect, quality, monitor and Windows-scaling combination has been tested. Keep/Revert confirms a settings plan; use a new session for saved launch changes. Newer stacked Hor+ layouts need active-match acceptance. |
| Audio | See the [current routing limitation](audio.md) for endpoint choices, Shared/Separate preferences and live sound. Physical output checks remain open. |
| Pause | Linked gameplay may continue while the menu is open. Current Solo/cabinet pause-presentation changes need final physical checks. |
| LAN VS | Wired Ethernet is recommended and wireless LAN is supported. Automatic discovery depends on Windows, adapter and router settings; use [Direct Connect](lan-vs.md#direct-connect-fallback) where available. The latest complete-match and simultaneous Ethernet/Wi-Fi acceptance remain open. |
| Recovery | Device/display reconnect and invalid-configuration recovery have not been qualified for every setup. Do not delete a complete settings directory as a reset. |
| Rendering effects | A reported missing-side impact effect at higher internal resolutions remains unresolved in live testing. Include aspect, quality and affected player/side in reports. |
| Menu presentation | Recent Title/Pause visual changes still need physical acceptance in the integrated build. |
| Exit | In current development packages, confirmed Title Exit can close other recognized PROJECT OT copies in the same Windows session. Save work in those copies first. Interactive acceptance of that cross-copy behavior remains open. |

## Outside the current feature set

Vertical expansion, internet NETPLAY, rollback, spectators and experimental haptics are not supported player features. These Windows guides do not establish macOS, Linux or SteamOS parity.

[Report a problem](troubleshooting.md#reporting-a-problem) with a small, redacted reproduction record. A discovered LAN station or successful connection is separate from a completed linked match.

## Documentation still pending

The approved [development-history narrative](development-history.md), final public installation steps, complete third-party notices and distribution/source-access review remain open. The approved project introduction is preserved in the [README](../README.md).
