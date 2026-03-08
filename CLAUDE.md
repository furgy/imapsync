# CLAUDE.md - Project Guidance for AI Assistants

## Project Overview
This is the imapsync project - a Perl-based email synchronization tool with Python components for OAuth2 authentication.

## Versioning
This project uses semantic versioning. See [VERSIONING.md](VERSIONING.md) for details.

## Key Files
- `VERSION` - Contains current version (format: X.Y.Z)
- `imapsync` - Main Perl script
- `oauth2/oauth2_google.py` - Python OAuth2 module for Google
- `.github/workflows/` - CI workflows

## Important Notes
- This is primarily a Perl project
- The main branch is `master`
- Always bump the version in VERSION file when making changes that warrant a new release
