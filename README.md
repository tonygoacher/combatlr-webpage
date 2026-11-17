# CombatLR Website

The public-facing home of the CombatLR open-source project.

The site presents CombatLR as a real-world Battle Royale laser tag system, highlighting dynamic safe zones, pickups and weapons; outdoor play without venue-installed infrastructure; self-contained ESP32 player units; and open hardware and software.

## Structure
- `index.html` — responsive project homepage
- `css/style.css` — layout, typography and visual styling
- `js/main.js` — mobile navigation and small page enhancements
- `assets/images/` — image assets and favicon
- `guides/` — Getting Started guides for maps, game plans, file transfer and game management
- `map-builder/` — experimental browser-based map calibration and site-package exporter
- `downloads/` — future downloadable application and firmware releases
- `documentation/` — future technical documentation

## Running locally
No build tools or framework are required. Open `index.html` in a browser, or serve the repository root with any static HTTP server.

The stylesheet loads Barlow Condensed, DM Mono and Inter from Google Fonts, with system fallbacks.

## Project links
- Source: https://github.com/tonygoacher/CombatLR
- Releases: https://github.com/tonygoacher/CombatLR/releases
- PCBWay: https://www.pcbway.com/

The PCBWay link currently points to the general PCBWay website, not to a published CombatLR board listing.

## Releases
The releases card links to GitHub Releases. Do not advertise a download until the corresponding binary and release notes have been published and verified.

## Getting Started guides

The website includes four practical user guides in `guides/`:

1. [Create maps](guides/create-maps.html) — prepare an image, calibrate four GPS reference points and export the site package.
2. [Create gameplans](guides/create-gameplans.html) — configure players, teams, zones, pickups and game settings.
3. [Transfer files](guides/transfer-files.html) — discover player units and transfer project files using the mobile app.
4. [Manage games](guides/manage-games.html) — verify players, start a match and monitor game progress.

The guides are text-first at this stage. Screenshots and photographs can be added later without changing the guide structure. Review operational details against the current app and firmware when workflows change.
