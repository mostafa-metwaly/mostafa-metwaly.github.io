# Academic site — mostafa-metwaly.github.io

GitHub Pages site (Jekyll / Minimal Mistakes) for **research, publications, and thesis projects**.

- **Live:** https://mostafa-metwaly.github.io/
- **Career portfolio:** https://mostafa-metwaly.netlify.app/

## Local preview

```bash
cd sites/mostafa-metwaly.github.io
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000

## What to edit

| Content | Path |
|--------|------|
| Homepage / about | `_pages/about.md` |
| Research statement | `_pages/research.md` |
| Industry experience (short) | `_pages/experience.md` |
| Publications | `_publications/*.md` |
| Projects | `_portfolio/*` |
| CV embed + text summary | `_pages/cv.md` + `files/MostafaOthman_CV.pdf` |
| Site title, bio, social links | `_config.yml` |
| Navigation | `_data/navigation.yml` |

## Deploy

Commit and push to `main` on `mostafa-metwaly/mostafa-metwaly.github.io`. GitHub Pages rebuilds automatically.

Based on [academicpages](https://github.com/academicpages/academicpages.github.io) (Minimal Mistakes).

## Upstream sync

This repo was forked from academicpages and has diverged heavily (personal content + old theme layout). To check for upstream updates:

```bash
git fetch https://github.com/academicpages/academicpages.github.io.git master:upstream/master
git log HEAD..upstream/master --oneline -20   # what you're missing
git rev-list --count HEAD..upstream/master    # commit count behind
```

**As of May 2026:** upstream is **~400 commits ahead** with a major rewrite (built-in light/dark themes via `site_theme`, reorganized `_sass/`, footer overlap fixes). A blind merge will conflict with local customizations. Prefer:

1. **Custom SCSS** in `_sass/_custom.scss` (current approach), or  
2. **Re-fork** upstream and re-copy only `_pages/`, `_portfolio/`, `_publications/`, `_config.yml` author block, and `files/`.

Add upstream permanently: `git remote add upstream https://github.com/academicpages/academicpages.github.io.git`
