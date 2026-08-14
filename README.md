# Pipewick — Privacy & Terms

Hosted privacy policy and terms of use for the **Pipewick** mobile game,
in the ten languages the app itself ships with.

**These pages are generated, not hand-edited.** The source of truth is the
app's own `lib/core/legal_texts.dart` (English + Turkish originals) plus
`tools/legal_i18n.json` (the eight translations). To update:

```bash
# in the pipewick repo
python3 tools/build_legal_pages.py /path/to/pipeflow-pages
```

then commit here. Editing the HTML directly would let the public policy drift
away from the one shown inside the app, which is the one thing this setup
exists to prevent.

## Store listing URLs

After enabling GitHub Pages (Settings → Pages → Deploy from `main`, root):

- Privacy policy: `https://mnpekdemirapps.github.io/pipeflow-pages/en/privacy.html`
- Terms of use: `https://mnpekdemirapps.github.io/pipeflow-pages/en/terms.html`
- Language index: `https://mnpekdemirapps.github.io/pipeflow-pages/`

Swap `en` for `tr`, `de`, `es`, `fr`, `it`, `ja`, `ko`, `pt` or `ru`.
