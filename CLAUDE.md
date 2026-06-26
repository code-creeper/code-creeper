# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is a **GitHub profile README repository** — the special `code-creeper/code-creeper` repo whose `README.md` renders at the top of the user's GitHub profile page (https://github.com/code-creeper).

It contains no application code, build system, or tests. The entire deliverable is `README.md`.

## Working in this repo

- The only file that matters is `README.md`. Edits are content/markup changes, not code changes.
- `README.md` is GitHub-Flavored Markdown with embedded HTML comments used as section dividers (e.g. `<!-- ── ABOUT ── -->`). Preserve this sectioning when editing.
- Visuals come from external services rendered as images:
  - **Shields.io badges** (`img.shields.io`) for the tech-stack chips — keep the `style=for-the-badge` and brand color/logo params consistent when adding new ones.
  - **github-readme-stats** (`github-readme-stats.vercel.app`) for the stats and top-languages cards — these are pinned to `username=code-creeper` and a `github_dark` theme.
- There is no way to "build" or "run" this. To preview changes, view the rendered Markdown (GitHub, or any Markdown previewer). The accurate final render is the GitHub profile page itself.

## Conventions

- Keep the green accent palette consistent (e.g. `2ED06E` / `00DC82` title colors) when adding badges or stats cards.
- Contact links point to the user's Upwork profile and `abdulhaseebkhan407@gmail.com`.
