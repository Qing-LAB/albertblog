# Wowchemy Hugo Starter (minimal scaffold)

This is a minimal **Hugo** site scaffold configured to use **Wowchemy** as a Hugo Module.
It includes example content and a working `config.toml` that will fetch Wowchemy when you build the site.

## Quick start (recommended)

1. Install Hugo (Extended) — see https://gohugo.io/getting-started/installing/
   * You'll need a recent Hugo version that supports modules (Hugo 0.74+; Wowchemy recommends a modern version).
2. Open a terminal in this folder.
3. Initialize and fetch modules:
   ```bash
   hugo mod get
   ```
4. Run the dev server:
   ```bash
   hugo server -D
   ```
   Then open http://localhost:1313

## What this package contains
- `config/` — Hugo config that imports Wowchemy as a module.
- `content/` — Example content (Home, About, Posts).
- `data/` — Small site data for menus.
- `static/` — Example static assets (logo).
- `archetypes/` — Post archetype for new posts.
- `themes/` — (empty) — Wowchemy will be pulled as a Hugo module automatically when you run `hugo mod get`.

## Notes & next steps
- This is a minimal starting point. Wowchemy provides many modules, shortcodes, and front matter options.
- To customize your theme and modules, consult Wowchemy docs: https://wowchemy.com
- If you want, I can expand this package with more sections (projects, publications, gallery), demo data, and Netlify/Cloudflare deploy configs.
