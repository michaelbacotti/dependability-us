# Dependability.us Hugo Migration — Project Status

**Last updated:** 2026-05-02 19:23 EDT
**Agent:** Dependability
**Status:** ✅ Hugo live on Cloudflare Pages preview — manual steps remain for production

---

## What Was Done ✅

| Item | Status |
|------|--------|
| Hugo project at repo root | ✅ — `hugo.toml`, `content/`, `layouts/`, `static/`, `data/` at root |
| Legacy HTML → `legacy/` | ✅ — all 54 files moved, git-tracked |
| Hugo builds cleanly | ✅ — 60 pages, 0 errors |
| GitHub main pushed | ✅ — 5 commits pushed |
| `_redirects` created | ✅ — 57 redirect rules for backward compatibility |
| Cloudflare Pages preview deployed | ✅ — `https://00854b7b.dependability-us.pages.dev` |
| Pages HTTPS verified | ✅ |
| CSS/JS/assets loading | ✅ |
| Redirects working (302 → new URLs) | ✅ |
| Forecast page | ✅ — live data |
| AdSense / Analytics | ✅ — all pages |

---

## Current Deploy URLs

| Environment | URL | Notes |
|---|---|---|
| **Preview (latest)** | https://00854b7b.dependability-us.pages.dev | Wrangler direct upload, no Git integration |
| Preview (prior) | https://c41c5674.dependability-us.pages.dev | _redirects fix deploy |
| Preview (initial) | https://06a8acfd.dependability-us.pages.dev | Hugo-only upload |

**Production:** https://www.dependability.us/ (still serving legacy HTML from existing host)

---

## GitHub Commits (migration)

```
38f7f9c .gitignore: add .wrangler/
bd63207 Fix _redirects: correct case-study slugs, add missing term redirects
efce6cf Move _redirects to static/ so Hugo copies it to public/
f6de1e6 Hugo migration: move project to repo root
```

---

## ⚠️ Remaining Manual Steps (Require Mike)

### 1. Connect GitHub to Cloudflare Pages (for auto-deploy)
Currently the preview is a **manual wrangler upload**. To get automatic deploys on every push:

1. Go to https://dash.cloudflare.com/56d1b3ebac9ac0438cab8077a1e9a993/pages/view/dependability-us
2. Click **Settings → Builds and Deployments**
3. Set **Build command:** `hugo`
4. Set **Build output directory:** `public`
5. Under **GitHub** tab, connect the `michaelbacotti/dependability-us` repo
6. Set production branch to `main`

This replaces the manual wrangler upload with proper CI/CD.

### 2. DNS Cutover (final step after GitHub integration verified)
Once the auto-deploy is working from GitHub:

1. In Cloudflare Pages dashboard → custom domains → add `dependability.us`
2. Update DNS at your registrar to point CNAME to Cloudflare Pages
3. The existing `CNAME` file in the repo already has `www.dependability.us` — Cloudflare will handle the apex via their DNS

### 3. Cron Job Update
The existing cron job (`747eaa63`) runs a script that rebuilds `hugo/public/` and deploys. The script path may need updating since Hugo moved from `hugo/` subdirectory to repo root.

---

## Key Paths (Local Workspace)

| Path | Purpose |
|------|---------|
| `/Users/mike/.openclaw/workspace-bacottibot/dependability/` | Repo root |
| `hugo.toml` | Hugo site config |
| `content/` | All markdown content |
| `layouts/` | Hugo templates |
| `static/` | Static assets + `_redirects` |
| `legacy/` | Backup of all original `.html` files |
| `public/` | Hugo build output (gitignored) |

---

## Blockers (resolved/prevented)

- ~~Hugo not in GitHub repo~~ → ✅ Done
- ~~_redirects not in public/~~ → ✅ Fixed
- ~~Legacy HTML still live~~ → ✅ Moved to legacy/ (not served)
- ~~Backward-compat redirects wrong~~ → ✅ Fixed slugs

---

## Site Identity

- **URL:** https://www.dependability.us/
- **GitHub repo:** `michaelbacotti/dependability-us`
- **AdSense:** `ca-pub-9312870448453345`
- **Analytics:** `G-CR7TV6QRSN`
- **Cron job:** `747eaa63-02b4-41a2-b26c-c7b9216bbc82`
