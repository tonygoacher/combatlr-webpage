# CombatLR Website

The source for the CombatLR website.

The site uses the established CombatLR visual identity: black, white and tactical green, with a technical, field-oriented visual style.

## Structure

- `index.html` — responsive landing page
- `css/style.css` — layout, typography and visual styling
- `js/main.js` — mobile navigation and small page enhancements
- `assets/images/` — image assets and favicon
- `assets/logos/` — approved brand logo assets
- `downloads/` — downloadable application and firmware releases
- `documentation/` — user guides and technical documentation
- `pages/` — additional website pages

## Running locally

No build tools or framework are required. Open `index.html` in a browser, or serve the repository root with any static HTTP server.

The stylesheet currently loads Barlow Condensed, DM Mono and Inter from Google Fonts. System font fallbacks are included.

## Binary downloads

Every published binary must include its file name, version, file size and MD5 checksum. Generate checksums from the final release files; do not enter them manually. A `checksums.txt` file should accompany each release batch.

MD5 is useful for detecting accidental corruption, but it is not a cryptographic authenticity guarantee. Consider publishing SHA-256 alongside it for stronger verification.

## Content status

The downloads area is intentionally a placeholder until release packages are ready. Do not advertise a download until the corresponding binary and checksum have been published and verified.
