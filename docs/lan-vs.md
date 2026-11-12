# LAN VS over Ethernet or Wi-Fi

Use matching PROJECT OT packages and authorized game/firmware data on both stations. Claim the local controller as **Player 1 on each PC**, then configure its display and audio.

**Wired Ethernet is recommended. Wi-Fi is supported.** Automatic discovery depends on Windows settings, active adapters, wireless capabilities, router settings and whether connected devices may communicate. Stations can be on the same network without appearing automatically.

## Candidate qualification

Discovery, compatibility, challenge and readiness are implemented. A reported `NETWORK ERROR` / `0xB002` and sustained cross-PC gameplay remain unresolved for the candidate. Do not infer match reliability from a successful discovery or Ready state.

## Match Board

1. Open **Multiplayer → Link Play → LAN VS**. Discovery starts on entry.
2. Select **Join** to make your station available for invitations.
3. Select an available opponent. A mouse click highlights; double-click, keyboard Enter or controller Confirm challenges. Selecting an opponent also joins the board if needed.
4. The other player chooses **Accept**, then both choose **Ready**.

Busy or incompatible stations cannot be challenged. Expired entries disappear. Set neutral **Player Name** and **Station Name** through Network Settings, available from the board and **Title → Settings → Network**. Both routes edit the same saved values.

## Direct Connect

If discovery misses the other station, use Direct Connect where available. One PC selects **Host** and leaves the waiting screen open. On the other, choose **IP**, enter the host's local address, **Save**, then **Join**. The host still accepts and both players choose Ready.

## Finish a session

Linked gameplay can continue while the Experience menu is open. Confirm **Return to Title** to stop the match; the Match Board workflow returns there after cleanup. Use Back to leave the board, then confirm Exit at Title.

For an empty board or inconsistent wireless connection, follow [Troubleshooting](troubleshooting.md#lan-stations-cannot-connect). Direct Connect does not bypass compatibility or Windows permissions. See [Windows network access](network-access.md). Current package limits are in [Known Issues](known-issues.md#lan-vs).

![LAN VS Match Board showing three available stations and Direct Connect](../assets/screenshots/lan-vs.png)

The Match Board shows available stations and the Direct Connect action. Discovery visibility is not proof of completed matches, sustained LAN reliability or public internet matchmaking.
