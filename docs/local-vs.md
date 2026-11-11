# Local VS multiplayer on one PC

Local VS brings the original linked-cabinet game to one PC, with independent controls for Player 1 and Player 2. Set up both players before starting a match.

## Set up two players

1. Open **Settings → Controllers** and claim a different supported device for each player.
2. Use Test Controls for both players. Check that one player's inputs do not light the other player's contacts.
3. Choose a supported **Single Display** or **Dual Display VS** arrangement in [Display](display.md).
4. Review [Audio](audio.md). Shared/Separate configuration and speaker-test controls do not establish independent live routing.
5. Return to Title, open **Multiplayer → Local VS**, and follow the original game prompts on both views.

Player 1 can use the documented keyboard fallback, but Player 2 still needs a physical assigned controller. Do not assign one physical device to both players or rely on remembered XInput connection slots after reconnecting.

## Display and audio choices

Single Display places both views on one monitor; Dual Display VS gives each player a separate physical display. See [Display](display.md) for aspect/layout choices and the remaining checks on newer stacked Hor+ arrangements.

Shared Audio refers to the common-output configuration. Separate Audio describes player-specific choices where supported; it is not yet a guarantee that the current endpoint-settings page routes live game audio independently. A stereo speaker test is separate from actual linked gameplay sound.

## During a linked match

Opening the Experience menu does **not** establish safe synchronized pause. Linked gameplay can continue while the menu is open. Follow the **Gameplay Continues** status and do not expect the other cabinet to stop while one player changes controls.

Resume keeps the current session. After a disconnect or reassignment, confirm the correct player and release inputs to neutral. A missing player device must not be replaced by silently taking the other player's device.

## End the session

Use **Return to Title** and its confirmation to end the paired session, then **Exit** when finished. Wait for cleanup before starting another mode. A successful launch or two visible game views does not prove a complete linked match; report match completion and both players' control behavior separately.

Related: [controllers](controllers.md), [known issues](known-issues.md), [troubleshooting](troubleshooting.md).
