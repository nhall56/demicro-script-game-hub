# de_micro v1.0 - Browser FPS Game Script 2026

> A Counter-Strike-style FPS utility that runs directly on the web. The entire experience is contained in one HTML file and is intended for local matches, LAN play, and lightweight browser-based sessions.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nhall56/demicro-script-game-hub?style=flat-square)](https://github.com/nhall56/demicro-script-game-hub)

---

<p align="center">
  <a href="https://nhall56.github.io/demicro-script-game-hub/">
    <img src="https://img.shields.io/badge/Download-de_micro%20Script-brightgreen?style=for-the-badge" alt="Download de_micro Script">
  </a>
</p>

> **[Download de_micro](https://nhall56.github.io/demicro-script-game-hub/)**

---

[Download Latest Build](https://nhall56.github.io/demicro-script-game-hub/)

---

## What is de_micro?

de_micro packages a small browser FPS inspired by Counter-Strike into one standalone HTML document. It opens without a build pipeline, external asset collection, or dedicated server, allowing it to be launched and shared easily in lightweight environments.

The design centers on quick startup and self-contained matches. Players can create or join LAN sessions with a four-letter code, fight AI bots that use line-of-sight logic, and play through rounds containing buying, bomb planting, and defusing. Three.js, WebGL, JavaScript, and HTML generate the maps and visual geometry in code.

## Core Capabilities

- Runs as a single HTML file with no compilation or build step
- Works without a separate external asset pack
- Supports local use without server installation
- Provides LAN sessions through a 4-letter join code
- Includes line-of-sight AI combat bots
- Implements buy, plant, and defuse phases within the round cycle
- Offers several playable maps
- Includes a scoreboard, kill feed, and lifetime statistics
- Creates textures and geometry procedurally in code
- Uses host-authoritative peer-to-peer networking

## Getting Started

1. Download or clone the repository files.
2. Launch the main HTML file in a modern browser.
3. Create or enter a multiplayer session with the supplied 4-letter code.
4. For local multiplayer tests, place every player on the same network.

A basic session can be started as follows:

- Open the HTML file
- Host a game
- Give the join code to the other players
- Have them connect from another browser window or instance on the same LAN

## Available Options

Because de_micro is distributed as a self-contained browser file, its primary controls are available in the game interface or within the embedded settings instead of a separate installer configuration.

| Setting | Purpose | Notes |
| --- | --- | --- |
| Host session | Creates a LAN match | Follows the 4-letter join code process |
| Join session | Enters an existing hosted match | Designed for players on the same network |
| Bot match | Brings AI opponents into the game | Bots rely on line-of-sight combat behavior |
| Map selection | Chooses a playable map | The available selection can vary by build |
| Round flow | Manages match stages | Covers buying, planting, and defusing |
| Stats display | Presents the scoreboard and kill feed | Lifetime statistics are tracked during play |

## Browser Compatibility

The project requires a web browser with support for HTML, JavaScript, three.js, and WebGL. Modern desktop browsers are the intended environment, particularly those capable of real-time graphics rendering and browser networking.

Keep the following constraints in mind:

- Desktop browsers are preferred over mobile layouts
- LAN connectivity requires suitable network visibility and browser permissions
- Rendering performance differs across devices and graphics hardware
- Multiplayer operation is tied to the host-authoritative peer-to-peer model

## Frequently Asked Questions

### How can I launch a match?
Open the HTML file in a browser, then choose the host or join controls provided by the game.

### Is installation required?
No. The project is delivered as a single HTML file and does not require a separate installation.

### Is LAN multiplayer available?
Yes. Players on the same network can connect with the short 4-letter join code.

### Are computer-controlled opponents included?
Yes. AI bots are available and use line-of-sight behavior when engaging in combat.

### How can I change the game?
Use the available in-game settings, or edit the HTML and JavaScript source directly for further customization.

### Does the project depend on stored assets or save folders?
No external asset collection is required. Most of the game content is produced procedurally in code rather than read from separate directories.

### What can I try if performance is poor?
Use a modern desktop browser with WebGL enabled. If rendering or networking remains unreliable, test the project in another desktop browser.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
