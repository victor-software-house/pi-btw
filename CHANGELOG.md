# Changelog

## 0.2.4 — 2026-05-18

### Changed

- Peer range for `@earendil-works/*` bumped from `>=0.74.0` to `>=0.75.0` to match Pi 0.75.x. No API surface changes were required; the imports used by this package are unchanged across the 0.74 → 0.75 upgrade.

## 0.2.3 — 2026-05-12
- Renamed package to @victor-software-house/pi-btw.
- Moved to pnpm 11.1.1 and Node 24 LTS.
- Kept Pi runtime deps as optional peers only, with @earendil-works/* imports.
- Added private GitHub Packages publish metadata plus CI/release workflow.
- Cleaned transitive Pi runtime devDependency pull-in.
