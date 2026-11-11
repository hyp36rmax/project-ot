# Screenshot placement recommendations — POT-MEDIA02-R1

Private maintainer review only. These are proposed insertions, not edits to the frozen README V2.4 or Development Narrative V1.0. Captions, alt text, original dimensions, capture times and SHA-256 values are in [capture-inventory.json](capture-inventory.json). Menu availability does not establish physical compatibility or completed feature qualification.

| Document and existing section | Suggested image | Review guidance |
| --- | --- | --- |
| README.md — Screenshots & Gameplay | title/title-menu.png; gameplay/solo-combat-hud.png | Use a small representative selection after media acceptance. Preserve all approved prose. |
| docs/getting-started.md — Download, set up and play | title/title-menu.png | Show the actual entry menu; describe this as a private development capture. |
| docs/controllers.md — Assign a player | controllers/tanita-player-one.png; controllers/hori-player-two.png | Identify the detected device and selected profile separately. The earlier XInput-labelled capture is historical within this session. |
| docs/controllers.md — Test and customize | controllers/twin-stick-profile-list.png; controllers/gamepad-mapping.png; controllers/analog-calibration-controls.png; controllers/test-controls-player-two.png | Profiles include HORI, Tanita, Custom/Brook and both Raphnet variants. Do not claim every listed adapter was physically tested. Gamepad view and calibration controls are menu demonstrations. |
| docs/display.md — Aspect ratio and quality | display/solo-armada-1080p.png; display/rendering-presets.png; functions/f7-display-information.png | Distinguish native 2560×1440 desktop from configured 1920×1080 internal rendering. Presets are configuration options, not performance claims. |
| docs/display.md — Single Display and Dual Display VS | display/local-vs-single-display-plan.png; display/dual-display-configuration.png | Both are actual configuration screens; neither alone proves a live match. |
| docs/display.md — Aspect ratio and quality | functions/f6-live-21x9.png | Optional detailed demonstration only: native 2560×1080 application window, 2560×1080 configured internal at 21:9, on unchanged 2560×1440 desktop. The changed width is intrinsic to the live aspect demonstration. |
| docs/audio.md — Speaker Test | audio/audio-speaker-test.png | Speaker test invoked; physical audibility not independently confirmed. The UI explicitly says game-instance routing is not connected. |
| docs/solo.md — Start playing | gameplay/solo-combat-hud.png | Real user-controlled Solo combat with guest HUD. Do not describe this as F5 HUD toggling. |
| docs/local-vs.md — Set up a match | display/local-vs-single-display-plan.png; live match capture when verified | Keep actual configuration and simultaneous gameplay evidence distinct. Never substitute a contact sheet for the live dual view. |
| docs/local-vs.md — Arcade Cabinet Mode | Cabinet settings and persistent session captures when verified | Keep distinct from ordinary Local VS. Mode configuration alone does not demonstrate persistent operation. |
| docs/lan-vs.md — Match Board / Direct Connect | Actual board and empty Direct Connect screenshots when privacy-reviewed | No second physical PC is available. Do not illustrate Challenge/Accept/Ready with invented stations. |
| docs/development-history.md — relevant existing controller, cabinet, display and experience sections | Optional links to the corresponding verified images | Preserve Narrative V1.0 text and order verbatim. Present DEV-UAT04 captures as current development illustrations, not historical screenshots from earlier milestones. |

## F-function evidence limits

- F5 is intentionally consumed without an action in the current source because guest HUD separation remains unqualified. No HUD-disabled image may be claimed.
- F6 live cycling was observed in Solo. The source gates it out of Local VS and LAN VS. The 21:9 capture is an explicitly labelled rendering-width exception.
- F7 display information was observed during real Solo combat.
- F8 added the runtime FPS line. The saved F8 frame is the game's automatic match replay, not active player combat. It is not a benchmark measurement.
- No obsolete development cover/reveal/menu/stop shortcuts were used.

## Original-pixel policy

The original PNG files are retained byte-for-byte. A thin yellow Windows capture indicator is visible in several images. It has not been cropped, painted out or retouched. Maintainer media acceptance remains pending. Any contact sheet is explicitly a review composite of independent captures and cannot prove simultaneous multiplayer presentation.
