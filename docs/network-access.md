# Windows network access

Project OT does not create firewall exceptions, approve Windows dialogs, change network profiles or disable protection.

## LAN VS authorization

LAN networking starts when you enter LAN VS. A legitimate first-time Windows authorization prompt may appear. Inspect the executable details and authorize only the access you intend on a trusted Private network. If access fails, retain the actual error and use Retry; a successful socket bind does not prove firewall permission.

Use the normal Windows Security firewall settings to review application access. Do not add broad rules or turn the firewall off to make a test pass.

## Solo and same-PC Local VS

Solo should not need network permission. Local VS uses loopback communication, but a reported physical firewall-dialog trigger is still unidentified. If Windows prompts during Solo or Local VS, record the displayed application, full executable path, mode and time. That observation is separate from LAN authorization.

Different extracted installation roots have different executable paths. Authorization reuse and denial recovery still need physical qualification. See [Known Issues](known-issues.md#windows-network-authorization).
