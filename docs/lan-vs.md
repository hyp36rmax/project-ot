# LAN VS between PROJECT OT stations

LAN VS connects two compatible PROJECT OT stations over a local network. Use matching packages and authorized game/firmware data, then claim the local controller as **Player 1 on each station**. Configure each PC's display and audio before opening LAN VS.

## Recommended LAN Connection

**Wired Ethernet is recommended for the best PROJECT OT LAN VS experience.**

PROJECT OT also supports wireless LAN connections, although device discovery and connection reliability may vary depending on the network environment.

Wireless discovery can be affected by Windows network settings, the capabilities of the wireless adapter, router configuration, and how connected devices are allowed to communicate across the local network.

Some PROJECT OT stations may not appear automatically on the Match Board, even when connected to the same network.

If a station isn't discovered, check the local network configuration or use **Direct Connect** to connect to the other station manually, where available.

For the most consistent multiplayer experience, we recommend connecting both PCs through wired Ethernet.

## Match Board

Open **Multiplayer → LAN VS**. The Match Board lists stations found through automatic discovery. **Join** makes your station available to other players.

Choose an available station, issue a challenge, have the other player accept, and confirm readiness on both sides. Follow the displayed **Challenge**, **Accept** and **Ready** states and any compatibility messages before starting play.

The current Match Board's complete cross-PC workflow still needs final release acceptance. Existing LAN transport and discovery checks do not establish that every current interface step or network configuration has passed a complete linked match.

## Player and station identity

**Network Settings** contains Player Name and Station Name. The approved access points are LAN VS → Network Settings and Title → Settings → Network, sharing the same values; final integration of both entry points remains to be confirmed in the release package.

Choose a display name that does not reveal personal information. A station name helps identify the other PC; it does not establish package or game-data compatibility.

## Direct Connect fallback

When automatic discovery does not find the other station, use **Direct Connect** where available. One PC selects **Host**. On the other, enter the host's local address, save it and select **Join**, following the on-screen prompts.

Direct Connect still requires compatible packages/data and a network that permits the PCs to communicate. It does not bypass Windows permissions or guarantee a completed match.

## During and after a match

Linked gameplay can continue while the Experience menu is open; follow **Gameplay Continues**. Use **Return to Title** to end the session, then reopen LAN VS to return to the Match Board.

A discovered station or successful connection is separate from completed linked gameplay. Both players should reach the same match, retain independent local control and be able to finish and leave cleanly.

## Connection help

Check the selected network adapter, package/data compatibility and Windows permissions for the installed application. An empty board alone does not identify the cause. Do not disable Windows security protections. For wireless client isolation and other discovery checks, see [LAN troubleshooting](troubleshooting.md#lan-stations-cannot-connect).

Internet NETPLAY, rollback networking and spectators are outside the current LAN feature set. See [known issues](known-issues.md) for remaining release-specific checks.
