# Changelog

All notable changes to this project will be documented in this file.

## [Unreleased]
- Ongoing minor documentation updates.

## [1.0.0] - 2026-05-06
### Added
- **Official Dataset Release:** The ClimateGen dataset (Version 1.0.0) has been formally published at the GESIS Data Archive (DOI: [10.7802/3038](https://doi.org/10.7802/3038)).
- Added formal citation, DOI link, and license information to the README.

### Changed
- Removed data embargo warnings from the documentation.
- Completed repository cleanup (paths/secrets removed) and finalized documentation improvements for the public release.

## [0.1.0] - 2026-01-18
### Added
- Initial repository skeleton with `classification/`, `processing/`, and `descriptive replication/`.
- Minimal documentation (`README.md`) and repo hygiene files (`.gitignore`, `CHANGELOG.md`).

### Changed
- Removed hard-coded local paths and secrets from notebooks (R/Python chunks now rely on repo-relative paths and env vars).
