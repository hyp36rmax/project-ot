# Configuring modern gamepads and Twin-Sticks

Open **Settings → Controllers** to choose Player 1 or Player 2, identify the connected device and test its inputs. A detected name or selectable profile is not proof that every hardware revision has completed physical qualification.

## Modern dual-analog gamepads and arcade controls

The Gamepad control type uses a common dual-analog layout for the supported Xbox and PlayStation families. The two sticks represent the original left and right Twin-Stick lever contacts; weapon and dash contacts remain independently available on each side. The original game interprets combined inputs. Controller support does not add new movement, weapon or timing rules.

Support depends on the actual device and connection, not simply the presence of two sticks. Check both lever directions, both weapon inputs, dash inputs, Start and simultaneous actions in **Test Controls** before playing.

## Known profiles and physical coverage

| Profile or hardware family | Current evidence and limits |
| --- | --- |
| Xbox dual-analog gamepads | Historical Solo and mixed-controller gameplay acceptance exists for the recorded devices. Other models/transports still need their own checks. |
| PlayStation dual-analog gamepads | Known translation profiles and controller tests exist. A complete release hardware matrix is not yet approved. |
| HORI Twin Stick EX | One player-facing selection covers the supported hardware variants. Historical recorded HORI gameplay does not qualify every revision or establish that all variants are equivalent. |
| Tanita Twin-Stick | A known device/profile is implemented. Full revision-specific physical acceptance and some physical button-label correspondence remain to be confirmed. |
| Custom Brook / XInput Twin-Sticks | Explicit profile selection and reviewed remapping are available. Custom wiring and board revisions require individual testing. |
| Raphnet Dreamcast v1 adapter | Known Twin-Stick translation profile; Project OT physical compatibility remains to be qualified for the exact adapter/setup. |
| Raphnet Saturn v2 adapter | Known Twin-Stick translation profile; Project OT physical compatibility remains to be qualified for the exact adapter/setup. |

This is a profile inventory, not a universal compatibility certification. The [release guide](release-guide.md) must identify accepted device/model/transport combinations before public support claims are made.

## Claiming and assigning players

Release the controls to neutral before claiming. The retained controller workflow uses a **750 ms Hold Start** gesture; releasing early cancels the claim. On the Controllers page, select the intended player before following the claim prompt. A device already owned by the other player cannot be assigned again.

Use the read-only detected-device information and Test Controls to confirm ownership. After reconnecting an ambiguous XInput device, make a fresh claim rather than relying on a remembered connection slot. Do not assume that two identical display names identify the same physical controller.

Keyboard fallback belongs to Player 1. Local VS still requires a separate physical Player 2 device. In LAN VS, claim the local controller as Player 1 on each station; being the second PC does not make its local controller P2.

## Mapping, calibration and dead zones

Choose the control type before editing. Fixed Twin-Stick profiles are read-only; supported Gamepad and Custom/Brook edits use the page's capture prompts. When a binding conflicts, review **Swap** or **Cancel** instead of silently replacing another action.

For supported gamepads, calibrate one stick at a time: release it at center, then follow the full-travel prompt. Dead zones and X/Y inversion are separate settings. Incomplete travel is rejected; disconnecting during capture/calibration cancels that operation and retains saved values. Confirm that returning to center releases every contact.

## Test Controls, Save, Cancel and Restore Defaults

**Test Controls** highlights the twelve left/right dashboard contacts: Up, Down, Left, Right, Weapon and Dash for each lever. Test individual inputs, simultaneous inputs and release to neutral. Input testing/capture temporarily isolates normal gameplay/menu confirmation.

Where an assignment page offers **Save** and **Cancel**, Save applies the pending selection and Cancel leaves that selection uncommitted. Accepted binding edits in the V1.3 workflow can save immediately; Cancel cancels the active capture/conflict operation and is not a promise to undo all earlier edits. Follow the on-screen confirmation for the build you are testing.

**Restore Defaults** affects the current control type and offers **Undo** in the retained mapping workflow. It is not a global reset of both players or all configuration. Recheck Test Controls afterward.

Final physical acceptance of the current Settings page and all supported devices remains open. Report problems through the controller issue form with the model, adapter/connection, selected profile, affected player and the smallest reproducible input sequence. Do not attach full private configuration folders.

Related: [Solo](solo.md), [Local VS](local-vs.md), [LAN VS](lan-vs.md), [known issues](known-issues.md).
