# Versioning System

## Overview
This project uses semantic versioning with a simple VERSION file approach.

## Version File
- **Location**: `VERSION`
- **Format**: `X.Y.Z` (e.g., `2.229`)
- The VERSION file contains the current version string as the single line of content.

## Version Bumping
- Version bumps are performed manually by updating the VERSION file
- Follow semantic versioning: MAJOR.MINOR.PATCH
  - MAJOR: Incompatible API changes
  - MINOR: New backward-compatible functionality
  - PATCH: Backward-compatible bug fixes

## CI Requirements
- On push to the main branch (master), the CI must verify that the version was bumped
- The version check is performed in `.github/workflows/version-check.yml`

## Version Source
The authoritative version is stored in the `VERSION` file in the project root.
