# Z Academy website

The public pages for Z Academy apps: home, privacy policy, terms of use and account deletion. Served by GitHub Pages from `main`.

One privacy policy, one set of terms and one account-deletion page cover every Z Academy app.

## Adding an app

Before the app's first release:

1. Add it to the "Apps covered" list in `privacy/index.html`, `terms/index.html` and `delete-account/index.html` (same line in each: store name, Android package id, who it is for), and to "Our apps" in `index.html`.
2. Change the "last updated" date (header and first section) of the privacy policy and terms.
3. If the app collects anything the others do not, or sells something they do not, add it to the privacy policy or terms first: the pages say every app handles information in the same way.
4. In Play Console, use `https://ziyadmansy.github.io/zacademy-site/privacy/` as the privacy policy and `https://ziyadmansy.github.io/zacademy-site/delete-account/` as the account-deletion URL.

The logo files are exported from `packages/zacademy_ui/brand/` in the Z Academy app repository; the brand rules live there too (`docs/BRAND.md`).
