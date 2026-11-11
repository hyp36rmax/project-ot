# Gamepads and arcade Twin-Sticks

Open **Settings → Controllers**. Choose **Gamepad** for Xbox, compatible PlayStation/XInput and other compatible dual-analog gamepads. Gamepads share one control type; there are no manufacturer-specific Gamepad choices.

Arcade profiles include **HORI Twin Stick EX**, **Tanita**, **Custom / Brook**, **Raphnet Dreamcast v1** and **Raphnet Saturn v2**. HORI has one visible selection. Use the matching adapter/profile and check your hardware in Test Controls; see [Known Issues](known-issues.md#controllers) for variant coverage.

## Assign a player

1. Connect from Title or Controllers. On Controllers, select Player 1 or Player 2 first.
2. Release the controls to neutral, then hold **Start for 750 ms**.
3. Release Start and **tap it again to confirm**. This tap assigns the device without activating a menu item. Another long hold does not confirm.
4. Check the connected-player message and open **Test Controls**.

Each player needs a different device. Keyboard fallback belongs to P1; Local VS needs a physical P2 controller. On each LAN station, claim the local controller as P1. Reclaim an ambiguous reconnected XInput device rather than trusting its old connection slot.

<!-- POT-MEDIA03:tanita -->
<p><a href="../assets/screenshots/controllers/tanita-player-one.png"><img src="../assets/screenshots/controllers/tanita-player-one.webp" alt="Detected Tanita Twin-Stick assigned to Player 1 with its matching profile" width="960"></a></p>

*Player 1: detected Tanita Twin-Stick and selected Tanita profile.*
<!-- /POT-MEDIA03:tanita -->

## Test and customize

Test both levers' Up, Down, Left, Right, Weapon and Dash contacts, including simultaneous inputs and release to neutral.

Use enabled binding prompts to customize controls. Fixed Twin-Stick mappings are read-only. Resolve conflicts with **Swap** or **Cancel**. Calibrate gamepad sticks one at a time; adjust dead zones and X/Y inversion separately.

Accepted binding edits auto-save. Cancel stops the active capture, not earlier edits. Where an assignment screen offers Save/Cancel, they apply to that pending selection. **Restore Defaults** affects the current control type and offers **Undo**.

<!-- POT-MEDIA03:test -->
<p><a href="../assets/screenshots/controllers/test-controls-player-two.png"><img src="../assets/screenshots/controllers/test-controls-player-two.webp" alt="Player 2 Test Controls showing active left-lever Up and right-weapon contacts" width="960"></a></p>

*Live input indication during the physical Player 2 test.*
<!-- /POT-MEDIA03:test -->

<!-- POT-MEDIA03:details -->
<details>
<summary>Hardware profiles and gamepad configuration</summary>

<p><a href="../assets/screenshots/controllers/hori-player-two.png"><img src="../assets/screenshots/controllers/hori-player-two.webp" alt="Player 2 detected as HORI Twin Stick EX with its matching hardware profile" width="960"></a></p>

*Player 2: detected HORI Twin Stick EX and selected HORI profile.*

<p><a href="../assets/screenshots/controllers/twin-stick-profile-list.png"><img src="../assets/screenshots/controllers/twin-stick-profile-list.webp" alt="Hardware profile list with HORI, Tanita, Custom Brook and both Raphnet options" width="960"></a></p>

*Available profiles; this menu does not establish physical testing of every listed adapter.*

<p><a href="../assets/screenshots/controllers/gamepad-mapping.png"><img src="../assets/screenshots/controllers/gamepad-mapping.webp" alt="Gamepad mapping configuration with the gamepad control type selected" width="960"></a></p>

*Gamepad mapping view; the selected control type is distinct from the detected hardware.*

<p><a href="../assets/screenshots/controllers/analog-calibration-controls.png"><img src="../assets/screenshots/controllers/analog-calibration-controls.webp" alt="Expanded analog controls showing dead zone, inversion and calibration actions" width="960"></a></p>

*Calibration controls shown; no completed calibration is claimed.*

</details>
<!-- /POT-MEDIA03:details -->

A short gameplay Start press is the arcade Start input; the longer menu gesture has a different purpose.
