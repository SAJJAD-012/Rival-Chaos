# Rival Chaos — GitHub Pages site

This folder is ready to publish as a **GitHub Pages** landing page.

Live site (after you publish):

`https://YOUR_USERNAME.github.io/`

or (project site):

`https://YOUR_USERNAME.github.io/rival-chaos/`

## What’s inside

| File | Purpose |
|------|---------|
| `index.html` | Rival Chaos marketing landing page |
| `_config.yml` | Optional site title/description for Pages |
| `README.md` | This file |

## Publish in 10 minutes (GitHub website)

### A) User site — `username.github.io` (recommended for a main homepage)

1. On GitHub, click **+** → **New repository**.
2. Repository name: **`YOUR_USERNAME.github.io`** (must match your username exactly).
3. Visibility: **Public**.
4. Add README: **On** (or Off — we will upload files).
5. Click **Create repository**.
6. Click **Add file** → **Upload files**.
7. Upload everything from this `github-pages` folder (`index.html`, `_config.yml`, this README).
8. Commit.
9. Go to **Settings** → **Pages**.
10. Under **Build and deployment** → **Source**: **Deploy from a branch**.
11. Branch: **`main`** / folder **`/ (root)`** → **Save**.
12. Wait up to ~10 minutes, then open:  
    `https://YOUR_USERNAME.github.io/`

### B) Project site — keep game repo separate

1. Create a repo named e.g. `rival-chaos`.
2. Upload this folder’s files to the **root** of that repo (or put them in `/docs`).
3. **Settings** → **Pages** → Deploy from branch `main` / `/ (root)` or `/docs`.
4. Site URL becomes:  
   `https://YOUR_USERNAME.github.io/rival-chaos/`

## Optional: edit title in `_config.yml`

```yaml
title: Rival Chaos
description: Turnkey 3D card duel game — PC & Android
```

> Note: This landing page is **static HTML**. It does not require a Jekyll theme to work. `_config.yml` is only for Pages metadata if GitHub uses Jekyll processing.

## Before you publish

1. Open `index.html` and change the email in the Acquire button from `hello@rivalchaos.game` to your real address.
2. Drop real screenshots into the gallery later (replace placeholders).

## Local preview

Double-click `index.html`, or open it from Cursor / browser.
