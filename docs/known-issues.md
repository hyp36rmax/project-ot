# Known issues and qualification limits

This is the documentation baseline as of November 11, 2026. The software remains `v0.5.0-dev`. A final public RC package, installation procedure and release-specific compatibility matrix have not been established here.

## Current limits

| Area | Evidence and limit |
| --- | --- |
| Controllers | Historical accepted devices and known profiles exist. The complete current UI/device/adapter/transport matrix still needs physical acceptance; one profile does not certify every hardware revision. |
| Display | Original and selected expanded configurations have scoped evidence. Not every aspect/quality/session/monitor combination is qualified. Later stacked Hor+ arrangements have separate active-match gates. |
| Dual Display Mirror | Gated/unavailable in the retained qualified backend. |
| Vertical expansion | Research remains unqualified; it is not a supported player-facing display mode. |
| Audio endpoints | Configuration and speaker tests exist; the current page does not establish connected live game-audio routing. Separate outputs, shared-mix behavior and physical channels require acceptance. |
| Pause | An Experience menu is not proof of a stopped game. Linked gameplay may continue; current Solo/cabinet presentation changes need their own physical checks. |
| LAN VS | Transport/discovery engineering and earlier physical observations have different scopes. Final Match Board, multi-interface discovery, permissions, Direct Connect and full-match acceptance remain open for the current release candidate work. |
| Recovery | Device/display reconnect and end-to-end invalid-configuration recovery still need qualification. No blanket delete-and-recreate recovery procedure is approved. |
| Rendering effects | A reported missing-side impact-effect issue at higher internal resolutions remains unresolved in live testing; replay tests alone do not close it. Report aspect, quality and affected player/side. |
| New menu presentation | Later Title/Pause cleanup has engineering evidence but still needs final physical visual acceptance in the integrated build. |

## What is not a current feature claim

Internet NETPLAY, rollback and spectators are not included in the current LAN guide. Experimental haptics and unqualified rendering experiments are not player features. Windows development evidence does not establish equivalent macOS, Linux or SteamOS functionality.

Use only the enabled, qualified options described for the package you receive. Successful startup, a native settings capture or a loopback network test cannot replace a completed physical gameplay test. [Report a problem](troubleshooting.md#reporting-a-problem) with a small, redacted reproduction record.

## Documentation still pending

The full approved [development-history narrative](development-history.md), final public installation steps, complete third-party notices and distribution/source-access review remain open. The approved project introduction is preserved in the [README](../README.md).
