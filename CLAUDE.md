# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is the **GitHub profile repository** for `VincentXII`. GitHub automatically renders `README.md` from this repository on the user's public profile page at `github.com/VincentXII`. There is no application code here — the primary artifact is the profile README.

## Repository Structure

```
VincentXII/VincentXII (profile repo)
├── README.md       # Displayed on github.com/VincentXII — the profile showcase
└── CLAUDE.md       # This file
```

## Working with the Profile README

The `README.md` supports full GitHub-Flavored Markdown (GFM) including:
- GitHub stats cards (via third-party badge services)
- Shields.io badges
- Mermaid diagrams (rendered natively by GitHub)
- HTML `<img>` tags for layout control (e.g. centering, sizing)
- Emoji via `:emoji_name:` syntax

Keep edits to `README.md` focused on profile presentation. GitHub renders the file at a fixed width, so prefer relative sizing and centered layouts.

## Development Workflow

Since this repo has no build system or tests, the only workflow is editing and committing Markdown:

```bash
# Stage and commit changes
git add README.md
git commit -m "update profile README"

# Push to main
git push -u origin main
```

## Conventions

- Branch `main` is the default and the one GitHub reads for profile display.
- Commit messages should be short and descriptive of what changed visually.
- Do not add build tooling, CI pipelines, or dependencies unless the repo expands beyond a profile page.
