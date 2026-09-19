# thecoven.github.io
The Coven API Wiki docs.

The MkDocs site itself is built from source in
[`whoamimi/tarot-ai-backend`](https://github.com/whoamimi/tarot-ai-backend)
(`docs/`) and auto-published here by that repo's `.github/workflows/docs.yml`
on every push to its `main` branch. The `gh-pages` branch of this repo is
generated output — don't edit it by hand, edit the docs source instead. See
[`docs/README.md`](https://github.com/whoamimi/tarot-ai-backend/blob/main/docs/README.md)
in that repo for the build/deploy details.

GitHub Pages must be enabled once on this repo (Settings → Pages → Deploy
from a branch → `gh-pages`), and because this repo isn't named after the
account that owns it (`whoamimi`), the live site is served at
<https://whoamimi.github.io/thecoven.github.io/>, not at a bare
`thecoven.github.io` domain.
