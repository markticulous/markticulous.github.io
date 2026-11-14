# markticulous.github.io

Home page of markticulous.com. It shows the same Markticulous apps page as
https://markticulous.com/support/ (repo markticulous/support), at the root address.

`index.html` is generated from `markticulous/support`'s `index.html` by `kit/root-copy.mjs`
in the Support Markticulous Apps folder, with its links pointed at `/support/`. Do not edit it here.

`measured.html`, `site-terms.html` and `site-privacy.html` live here and are edited here. Their old
addresses under `/support/` are redirect pages in markticulous/support. Assets and `measured.json`
stay in markticulous/support and are loaded from `/support/assets/`.

This repo also holds the Google Search Console verification file for the site.
Keep that file: removing it cancels the verification.
