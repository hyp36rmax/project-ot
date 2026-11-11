# Troubleshooting PROJECT OT

Check the version and [known issues](known-issues.md) first. A private development candidate can contain enabled settings, gated controls and unqualified combinations; an unavailable option is not automatically a hardware fault.

## The application does not start

Use the complete package for that version. Check its documented Windows x64 prerequisites and retain the exact error text. The current development packaging uses external Microsoft runtimes; final installation steps and dependency versions must come from the approved [release guide](release-guide.md).

Do not mix files from older packages, rename a runtime to evade validation, or copy system DLLs from unrelated installations. Keep the previous installation intact for rollback.

## The game will not prepare or start

Confirm the expected, authorized game/firmware files and their revision for the delivered build. Missing data, incompatible data and a failed integrity check are separate conditions. Follow the visible message; do not download replacement ROMs from issue comments or attach archives to a report.

## A controller is missing, cross-controls or stays active

Return to the Controllers page, identify the intended player/device and release inputs. Reclaim a reconnected ambiguous XInput device and test all contacts to neutral. One device cannot belong to both players. Check the exact adapter/profile before changing mappings. See [Controllers](controllers.md).

## The image is on the wrong display or looks cropped

At Title, confirm the session, monitor assignment, aspect and quality. Check the requested arrangement against [Display](display.md); a settings preview does not qualify actual game framing. Use Revert or allow a supported preview to time out if the change is wrong. Preserve errors if recovery fails; do not delete a complete settings directory as an undocumented reset.

## Audio or speaker tests are silent

Check application volume/mute and the Windows output used by the build, then review the [Audio guide](audio.md) for its current routing limit. Report speaker-test failure separately from gameplay silence and identify the output type without publishing private device identifiers.

## LAN stations cannot connect

Use matching packages and game/firmware data, then check discovery separately from the connection and match itself:

1. Confirm both stations are connected to the intended local network.
2. Check the active Windows network adapter, especially if the PC has both Ethernet and Wi-Fi or a VPN.
3. Confirm the network allows connected devices to communicate with each other. Guest networks may restrict this even when both PCs can access the internet.
4. If using wireless, check whether the router isolates wireless clients. A setting may be called **client isolation** or **AP isolation**; names and availability vary. Ask the network owner if you cannot review it yourself.
5. Confirm Windows firewall permissions for the application in its current installation folder. An exception for an older copy may not apply. Keep Windows security protections enabled.
6. Use **Direct Connect** where available if the other station is not discovered automatically. Check the host's local address and follow the [LAN VS steps](lan-vs.md#direct-connect-fallback).
7. If wireless behavior is inconsistent, try wired Ethernet on both PCs. Ethernet is the recommended connection; wireless LAN is also supported.

An empty board does not by itself prove a firewall or wireless fault. Retain the visible message for missing data, incompatible packages or other preparation failures. A successful connection is not proof of a completed linked match.

## A session will not end or another copy is running

Let the session-ending action finish before starting another mode. If cleanup fails, retain the visible message rather than repeatedly launching more copies. Save work in any other PROJECT OT copy before confirming Title Exit; see [known issues](known-issues.md) for the current cross-copy exit behavior.

## Reporting a problem

Use the appropriate repository issue form: general bug, controller, display or LAN. Include the app/package version, Windows version, mode, steps, expected result, actual result and whether it repeats. For a display problem, include selected aspect/quality and the affected player's view; for a controller problem, include the model and connection/profile.

Share only a short relevant error excerpt or an approved redacted image. Remove usernames, personal station names, private filesystem paths, IP/MAC addresses and credentials. Do not attach ROMs, BIOS files, save data, entire configuration directories or unfiltered diagnostic ZIPs. Do not use issue comments to request game files.

If an installation offers a local feedback/export feature, review its contents before sharing anything. This documentation does not establish a public upload destination or permission to send a private export automatically.
