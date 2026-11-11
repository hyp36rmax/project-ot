# Troubleshooting PROJECT OT

Check the package version and [Known Issues](known-issues.md), then try the relevant steps below.

## The application does not start

Use the complete package and its [Microsoft prerequisites](getting-started.md#microsoft-prerequisites). Keep the exact error message. Do not mix files from older installations or copy unrelated system DLLs.

## The game will not start

Check the required game/firmware revision and placement against the package instructions. Missing files, incompatible data and integrity errors need different fixes. Do not post game archives in issues.

## Controller inputs are missing or cross players

Open Controllers, confirm the player/profile, release inputs and reclaim a reconnected ambiguous device. Use Test Controls for both players. One physical device cannot belong to both. See [Controller Setup](controllers.md).

## Display or audio looks wrong

At Title, check monitor, aspect, quality and arrangement. Revert a wrong display plan and use a new session for saved launch changes. For silence, check application mute/volume and the Windows output; distinguish gameplay from the speaker test. See [Display](display.md) and [Audio](audio.md).

## LAN stations cannot connect

1. Confirm matching packages/data and the intended local network.
2. Check the active Windows adapter, especially with Ethernet, Wi-Fi or a VPN together.
3. Confirm devices may communicate. Guest networks or wireless client/AP isolation can prevent it; router controls vary.
4. Review permissions for this installed application while keeping Windows security enabled.
5. Try [Direct Connect](lan-vs.md#direct-connect), or Ethernet on both PCs if Wi-Fi is inconsistent.

## Reporting a problem

Use the matching issue form with version, Windows version, mode, hardware, steps, expected/actual result and a short redacted error. Remove personal paths, station names, addresses and credentials. Never attach ROMs, BIOS, saves or complete private diagnostics/configuration folders. If cleanup stalls, retain the message before launching another copy.
