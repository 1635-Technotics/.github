# Team 1635 — Org Profile Package

Drop-in package for the Newtown Technotics (FRC 1635) GitHub org front page.

## Contents
- `README.md` — the org profile front page
- `assets/img/` — logo, favicon, CAD renders, sponsor logos (12 files)
- `assets/photos/` — robot + team-life photography (19 files)

## How to publish (GitHub org profile)
1. Create a **public** repo in your org named **`.github`**
2. Put `README.md` inside a **`profile/`** folder → `profile/README.md`
3. Copy the `assets/` folder in next to it → `profile/assets/...`
4. Commit. It renders automatically at `github.com/<your-org>`

> Paths in the README are relative (`assets/...`), so keep `assets/` alongside `README.md`.
> For a single-repo front page instead, put `README.md` + `assets/` at the repo root.

## Asset source
Curated set the live site actually references. The raw camera-original
duplicates from the site's `/uploads` folder were intentionally excluded
(they're 8–10 MB each; these are the web-sized versions).
