# Changelog — Helix Stax Brand Kit

All notable changes to the brand asset kit.

## [1.0.5] - 2026-03-15

### Fixed
- Remove cursor glow trail (annoying, not premium)
- Fix double scrollbar on desktop
- Remove parallax hero (caused janky scroll)
- Clean single scroll context

## [1.0.4] - 2026-03-15

### Fixed
- Mobile overflow — prevent horizontal scroll
- Logo grid responsive (auto-fill instead of fixed columns)
- Color swatch grid responsive

### Added
- Hero landing section with stats (13 platforms, 24 assets, 14 logo variants)
- Micro-interactions (scroll reveal, card hover, section dividers, progress bar, tooltips, copy-to-clipboard, badge pulse, Konami confetti)
- Logo Assets section with all SVG variants on dark/light backgrounds
- Color palette reference with Pantone assignments

## [1.0.3] - 2026-03-14

### Fixed
- Headshot alignment in cover photos (cx ratio bug — used svg_w instead of 851)
- YouTube and Pinterest cover text clipping (aspect ratio detection + font scaling cap)
- All cover photos re-rendered with cairocffi pipeline (text as paths, no font dependency)
- "HELIX STAX" wordmark centered under logo mark (x=768)

### Added
- All 5 visual effects on cover photos (text shadow, gradient text, accent underline, headshot glow, ambient glow)
- 8K supersample → downscale pipeline for sharp rendering
- Upload-ready folder organized by platform (24 files)

## [1.0.2] - 2026-03-14

### Changed
- Cover photo hook changed from "$3.6M" to "6 missed calls today." (gut punch version)
- Trades language: "Dead calls. Double-booked jobs. Software your crew won't touch."
- Open loop: "We know where it breaks. Do you?"
- Reduced to 3 lines (cut redundant sub-punch line)

### Fixed
- Top-anchored headshot crop (was center-cropping, cut off locs)
- Profile photos regenerated at platform-recommended upload sizes per metadata doc

## [1.0.1] - 2026-03-14

### Added
- Social media image sizes reference (all 11 platforms)
- Facebook SEO research (33 findings)
- Facebook content strategy (7 content pillars, 6 hook formulas)
- Facebook 90-day growth strategy with 29 group links
- Headshot SEO metadata (EXIF, schema, OG tags, alt text)

## [1.0.0] - 2026-03-14

### Added
- Initial brand asset kit
- Profile photos for 13 platforms (supersampled from 4096x4096)
- Cover photos for 7 platforms
- Logo SVGs (mark, lockup stacked, lockup horizontal, favicons)
- Platform assets HTML gallery
- EXIF metadata on all JPEG headshots
