# boxmode-legal

Static legal pages for the Boxmode iOS app, served with GitHub Pages at
https://soloranez21.github.io/boxmode-legal/ (the App Store Support URL).

| Page | English | German |
|---|---|---|
| Help and legal (hub) | `/` | `/de/` |
| Privacy Policy | `/privacy/` | `/de/privacy/` |
| Terms of Use (EULA) | `/terms/` | `/de/terms/` |
| Consumer Health Data Privacy Policy | `/health-data/` | `/de/health-data/` |
| Impressum | | `/de/impressum/` |

**Don't edit these files here.** The source of truth is the Markdown in the app repository
(`docs/legal/*.md` and `docs/legal/de/*.md`). Edit there, run `python3 docs/legal/build.py`,
then publish with `docs/legal/publish.sh --yes`, which copies `docs/legal/site/` into this repository.

These URLs are linked from the app (paywall, "Unlock Boxmode", Settings), from App Store Connect
(Privacy Policy URL, Support URL, the license agreement and the description), so keep them working.
