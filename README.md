# binker.app

Static site for https://binker.app, served by GitHub Pages.

- `index.html`: landing page.
- `privacy/`: privacy policy. Source of truth is `apps/privacy/site/index.html` in the main repo; copy it here to publish.
- `.well-known/apple-app-site-association`: lets the iOS app (team `VRNRQG4239`, bundle `app.binker.mobile`) use passkeys for binker.app. Must stay at this path, served over HTTPS with no redirect.
- `.nojekyll`: publish dot-folders such as `.well-known` as-is.
