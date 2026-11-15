# Template provenance

- Starter: https://github.com/alshedivat/al-folio
- Starter commit: 8158dd07b40eda745da47a55a8a711332286dbf5
- Core theme: al_folio_core 1.0.15 (Gemfile.lock)
- Original MIT license retained in LICENSE.
- Uses the real gem-owned al-folio styles, scripts, and theme palette.
- Local overrides: default layout for per-page language; header for language-only navigation; head include to attach a small site stylesheet and alternate-language links.
- Deployment uses GitHub Pages artifacts rather than the starter gh-pages branch workflow. Pages source must be GitHub Actions.
- Before upgrading core theme, review the three overrides against upstream and run `bundle exec al-folio upgrade overrides audit`.
