# PROJECT OT
### Virtual On Experience

**Preserving Virtual-On: Oratorio Tangram M.S.B.S. Ver. 5.66 for modern PC hardware.**

## About PROJECT OT

*Virtual-On: Oratorio Tangram* has always been one of those arcade games that deserves to be experienced properly.

The fast-paced combat, precise Twin-Stick controls, and competition between linked cabinets are what made the original arcade experience special. Everything worked together, from how the game played to how players interacted with the machines.

Over the years, SEGA brought *Oratorio Tangram* to different platforms, each offering another way to enjoy the game. But recreating the original NAOMI arcade experience on modern PC hardware still presents its own challenges.

That's where PROJECT OT began.

Rather than rebuilding the game, changing its mechanics, or combining features from different releases, I wanted to preserve the original NAOMI 5.66 experience while improving everything around it.

Modern controllers. Expanded displays. Local multiplayer. LAN play. A unified interface that makes the original game easier to access and enjoy.

The goal isn't to reinvent *Oratorio Tangram*.

It's to make the original arcade experience feel at home on modern hardware.

## The Experience

PROJECT OT brings the original NAOMI 5.66 game together with a purpose-built Windows experience.

Instead of managing emulator settings, multiple windows, controller assignments, and separate runtime configurations, players interact with one application.

Choose how to play, configure your controllers and displays, and enter the game.

The underlying software remains the original arcade release, executed through a specialized Flycast-derived runtime.

PROJECT OT manages the surrounding experience without replacing the game's original mechanics.

### Ways to Play

**SOLO**

Play the original arcade game through a modern interface, with supported controller, display, and audio settings.

**LOCAL VS**

Bring the original linked-cabinet experience to one PC. Two players, independent controls, and flexible display arrangements managed through a single application.

**LAN VS**

Connect compatible PROJECT OT stations across a local network. Discover available players, issue challenges, and enter linked matches through the Match Board.

## Modern Controls

The original Twin-Stick control system remains central to how *Oratorio Tangram* plays.

PROJECT OT makes that experience accessible through modern dual-analog gamepads while retaining support for compatible arcade-style Twin-Stick hardware.

Controller discovery, player assignment, input mapping, calibration, and testing are brought together in one interface.

The intention is straightforward: connect your controller, configure it when necessary, and play without having to understand the underlying arcade input system.

## Modern Displays

The original NAOMI release was designed around a 4:3 display.

PROJECT OT preserves that original presentation while introducing expanded rendering for modern widescreen and ultrawide monitors.

This goes beyond stretching the picture or cropping the original camera.

Our Flycast Lean development involved investigating PowerVR rendering, projection, clipping, and the game's original visibility behavior to support a wider field of view without changing the underlying gameplay.

The Experience also manages single-display and supported dual-display configurations, allowing players to choose how the game is presented.

Original 4:3 behavior remains the reference against which expanded presentation is evaluated.

## Built Around the Original Game

Preservation has guided the project from the beginning.

The original NAOMI 5.66 release remains our reference for gameplay, movement, weapons, timing, camera behavior, and linked competition.

Improving the experience doesn't mean changing the game itself.

Some challenges have required modifications to the runtime. Others have been addressed through the surrounding Windows application.

Every change needs to respect that distinction.

When something doesn't behave like the original arcade release, we investigate it rather than automatically treating the difference as an improvement.

## Development and Open-Source Foundations

PROJECT OT builds upon years of emulator development, community research, and preservation work.

The execution runtime is based on Flycast, with dedicated improvements developed for *Oratorio Tangram*.

Our Flycast Lean VOOT source, technical investigations, and corresponding open-source modifications are maintained separately:

**[Flycast Lean VOOT](https://github.com/hyp36rmax/flycast-lean-voot)**

The PROJECT OT Experience provides the player-facing framework around that runtime, including controller management, display presentation, audio configuration, multiplayer coordination, and session management.

Keeping these responsibilities distinct helps preserve the original software while making the surrounding experience easier to maintain and improve.

## Where the Project Stands

PROJECT OT remains in active development and release qualification.

Solo, Local VS, modern controller support, expanded rendering, and LAN multiplayer have progressed through implementation and physical testing.

The remaining work focuses on completing acceptance testing, refining the player experience, documenting known limitations, and preparing a responsible distribution.

Features and compatibility will be documented according to their actual validation status.

Downloads and installation instructions will be published when the release package is ready.

## A Fan-Created Project

PROJECT OT is an unofficial, fan-created preservation and modernization project.

*Virtual-On*, *Oratorio Tangram*, SEGA, and related trademarks and game assets belong to their respective owners.

PROJECT OT is not affiliated with or endorsed by SEGA.

No commercial game ROMs or proprietary NAOMI BIOS files are provided.

---

**Preserve the game. Improve the experience.**

## Player guides and release information

**Documentation foundation — November 11, 2026.** The current development baseline is `v0.5.0-dev`. No public download or qualified release candidate is offered here. The player guides explain supported workflows and identify specific configuration limits in [known issues](docs/known-issues.md).

- [Getting started on Windows](docs/getting-started.md)
- [Modern dual-analog gamepads and Twin-Sticks](docs/controllers.md)
- [Displays, aspect ratios and rendering quality](docs/display.md)
- [Audio output, volume and speaker tests](docs/audio.md)
- [Solo](docs/solo.md), [Local VS on one PC](docs/local-vs.md) and [LAN VS between stations](docs/lan-vs.md)
- [Troubleshooting](docs/troubleshooting.md) and [known issues](docs/known-issues.md)
- [First-session walkthrough and all player guides](docs/README.md#first-session)

## Releases and project history

Installation and download instructions remain pending until an approved distribution package exists. The [release guide](docs/release-guide.md) records what must accompany that package; it contains no speculative download links. [Changelog](CHANGELOG.md) tracks this documentation foundation separately from software releases.

The [development history](docs/development-history.md) is a draft structure awaiting the approved narrative. [Credits](CREDITS.md) recognize the original game and open-source foundations. [Legal and distribution notes](LEGAL.md) describe ownership, user-supplied game data and the remaining release review.
