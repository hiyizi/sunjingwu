# CLAUDE.md

This file provides context for AI assistants working in this repository.

## Repository Overview

This is the **GitHub profile README repository** for the user `sunjingwu` (GitHub: [@sunjingwu](https://github.com/sunjingwu)). GitHub treats the repository `sunjingwu/sunjingwu` as special: its `README.md` is displayed directly on the owner's GitHub profile page.

**Purpose**: Personal introduction and profile page on GitHub.
**Language**: Markdown only.
**Framework**: None — this is a static documentation repository.

## Repository Structure

```
sunjingwu/
├── README.md    # GitHub profile page content (rendered on github.com/sunjingwu)
└── CLAUDE.md    # This file
```

## Development Workflow

There is no build, test, or deployment pipeline. Changes take effect when `README.md` is updated on the `main` branch — GitHub automatically renders the latest version on the profile page.

### Making Changes

1. Edit `README.md` with the desired profile content.
2. Commit and push to `main` (or open a PR from a feature branch).
3. Verify the result at `https://github.com/sunjingwu`.

### Branches

- `main` — production branch; its `README.md` is live on the GitHub profile.
- Feature branches (e.g. `claude/...`) — used for drafting changes before merging.

## README.md Conventions

- The file uses GitHub Flavored Markdown (GFM).
- Emoji shortcodes (`:wave:`) and Unicode emoji are both supported.
- GitHub renders the file without a wrapping page chrome, so the content should read well as a standalone introduction.
- Keep the profile concise and human-readable — this is a public-facing page.

## Key Notes for AI Assistants

- There is no source code, tests, linting, or CI in this repository.
- Do not add configuration files (`package.json`, `.gitignore`, workflows, etc.) unless explicitly requested.
- The only meaningful file to edit is `README.md`.
- When updating the profile, preserve existing content unless specifically asked to replace it.
- Do not commit directly to `main` without user confirmation — open a PR or ask first.
