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

Check application volume/mute and the Windows output actually used by the build. A selected test endpoint is not proof that live game audio uses it. Report a speaker-test failure separately from game sound, and identify the selected output type without publishing private device identifiers. See [Audio](audio.md).

## LAN stations cannot connect

Use matching packages/data, a reachable local-network interface and the intended host address. Distinguish missing data, occupied ports, explicit socket denial and an empty station list. Review the exact installation's Windows permissions; do not disable firewall protection or automatically reuse old-path exceptions. Direct Connect still needs compatible peers and permitted traffic. See [LAN VS](lan-vs.md).

## Reporting a problem

Use the appropriate repository issue form: general bug, controller, display or LAN. Include the app/package version, Windows version, mode, steps, expected result, actual result and whether it repeats. For a display problem, include selected aspect/quality and the affected player's view; for a controller problem, include the model and connection/profile.

Share only a short relevant error excerpt or an approved redacted image. Remove usernames, personal station names, private filesystem paths, IP/MAC addresses and credentials. Do not attach ROMs, BIOS files, save data, entire configuration directories or unfiltered diagnostic ZIPs. Do not use issue comments to request game files.

If an installation offers a local feedback/export feature, review its contents before sharing anything. This documentation does not establish a public upload destination or permission to send a private export automatically.
