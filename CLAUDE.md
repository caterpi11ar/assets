# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **static assets repository** for the caterpi11ar organization — no build system, no dependencies, no tests. It serves as a centralized store for brand and organizational assets consumed by other projects via Git submodule or direct file copy.

## Directory Structure

| Folder | Contents |
|--------|----------|
| `logo/` | Brand logos in various formats (SVG, PNG, dark/light variants) |
| `icon/` | App icons, favicons, platform-specific icon sets |
| `copyright/` | Copyright statement templates, license notice snippets |
| `contact/` | Contact info templates (email, social handles, etc.) |

## Usage by Other Projects

**As a Git submodule:**
```bash
git submodule add https://github.com/caterpi11ar/assets.git assets
```

**Direct copy:** Copy required files and note the source version in the commit message.

## Conventions

- Documentation is bilingual (Chinese first, then English), following the pattern in README.md.
- `.gitkeep` files mark intentionally empty directories that are reserved for future assets.
- Copyright: © 2026 caterpi11ar. Contents are for internal caterpi11ar projects only.
