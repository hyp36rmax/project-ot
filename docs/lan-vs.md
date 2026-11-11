# LAN VS between PROJECT OT stations

LAN VS connects compatible PROJECT OT stations on a local network. The transport, local discovery/binding and interface have different evidence scopes. Retained transport and earlier discovery tests do not establish final acceptance of the current Match Board build. Cross-PC discovery, the complete Challenge/Accept/Ready flow and finished matches still require release-specific acceptance.

## Before connecting

Use the same approved package and matching authorized game/firmware data on both PCs. Each station needs a supported local controller, a working local-network connection and the correct active network interface. A trusted local network is the intended setting; multi-adapter routing and wireless behavior have additional validation limits.

Claim the locally connected controller as **Player 1 on each station**. The second PC is not the same-PC Player 2 assignment. Configure the local display/audio before opening LAN VS.

## Match Board workflow — interface qualification pending

Open **Multiplayer → LAN VS**. The Match Board lists available stations when discovery is operating. In current development interfaces, **Join** makes the station available; an entry or outgoing challenge alone does not mean a match is ready.

The intended sequence is to choose an available station, issue a challenge, have the other player accept, and confirm readiness on both sides. Follow the displayed **Challenge**, **Accept** and **Ready** states, including any compatibility or preparation messages, before expecting gameplay. Exact final button behavior still needs RC acceptance; these steps are not a claim that the current public-release workflow is frozen.

## Player and station identity

Use **Network Settings** for Player Name and Station Name where the build exposes it. The approved access points are LAN VS → Network Settings and Title → Settings → Network, sharing the same values. Final integration of those entry points remains to be checked in the offered build.

Choose an appropriate display name rather than personal information. A station name identifies the local installation in the board; it does not prove game-data or runtime compatibility.

## Direct Connect fallback

If discovery is unavailable, use **Direct Connect** where enabled. One PC selects **Host**. On the other, enter the host's local address, save it and select **Join**, following that build's prompts. Both PCs still need matching package/data and compatible network access; Direct Connect does not bypass those checks or Windows permissions.

An empty board can result from missing game data, a local listener failure, the wrong interface, compatibility rejection or network permissions. It does not by itself prove a firewall fault. Use **Retry** if the build provides it, and retain the exact visible message.

## During and after a match

Do not assume the Experience menu pauses linked gameplay. Follow **Gameplay Continues**. Use the offered **Return to Title** action to end the session, then reopen LAN VS to return to the Match Board. In-match return directly to the board is not assumed unless the release documents it.

A successful listener, handshake or two independent games is not a completed LAN match. Verify that both players share the same linked match, with independent local input, match completion and clean departure. Do not relabel an untested combination as accepted.

## Basic connection checks

Check package/data identity, the selected adapter and the host's local address. Review Windows permission requests yourself for the exact installed application on the appropriate trusted network. Do not disable firewall protection or assume that an exception for an older installation applies to the new folder. This guide does not create or change firewall rules.

Internet NETPLAY, rollback networking and spectators are not part of this player guide or the current LAN feature claim. [Known issues](known-issues.md) and [troubleshooting](troubleshooting.md) identify the remaining gates.
