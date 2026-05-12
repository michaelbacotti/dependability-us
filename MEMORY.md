# Dependability Site — Operational Lessons

## Critical Hugo Rules

### Section Index Pages
**Hugo section index pages MUST be `content/[section]/_index.md`** — not `[section].md`, not `[section]/index.md`.
Only `_index.md` inside the section folder generates the section's index URL (`/[section]/`).

### CSS/Asset Paths
CSS paths in Hugo base templates must use **root-relative absolute paths starting with `/static/`** — never relative paths like `../../`.
Hugo puts static files in `/static/`. Use `/static/css/style.css`, not `../static/css/style.css` or `./static/css/style.css`.

### Before Any Deploy
1. Run `hugo --gc --minify` locally — check for build errors
2. Check `public/[section]/index.html` exists for any section you're linking to
3. Do NOT commit if Hugo reports errors

### After Every Deploy
Visually verify the homepage, `/learn/`, and one article page load with the dark navy theme.
A 200 status code is NOT sufficient — curl the page and confirm `var(--navy)` CSS is present.

## The Workflow Bug (2026-05-12)

**Never use `rm -rf public && rsync . public/` in a Hugo GitHub Actions workflow.**
This deletes Hugo's build output (which contains all the generated HTML) and replaces it with Hugo SOURCE files.
Hugo SOURCE files are markdown and layouts — not HTML. The deploy artifact ends up being the source, not the build.

**The correct workflow:**
```yaml
- name: Build Hugo site
  run: hugo --gc --minify

# Do NOT add a copy/rsync step here

- name: Upload artifact
  uses: actions/upload-pages-artifact@v3
  with:
    path: ./public
```

The `public/` directory is Hugo's build output. Upload it directly.

## Git Rollback History (2026-05-12)
- Commit `1fd8c5e` was the last "visually correct" state — but it had the workflow bug
- Multiple deploys of buggy commits erased Hugo's generated pages from the live site
- Fix: commit `d441f3e` created `content/learn/_index.md` and the workflow was fixed
- All 4 pages verified: homepage, /learn/, /cash-secured-puts/, /dependability-forecast/ — CSS working on all

## Key File Locations
- Hugo content: `content/options/`, `content/research/`, `content/risk/`, `content/learn/`
- Hugo layouts: `layouts/_default/baseof.html`, `layouts/_default/single.html`
- Hugo static: `static/css/style.css`, `static/js/main.js`
- Hugo config: `hugo.toml`
- GitHub Actions: `.github/workflows/hugo.yml`
