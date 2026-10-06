# libergot — app website

Static site published with GitHub Pages: <https://benjamingott.github.io/>.
Plain HTML and one stylesheet, no build step. The site is in English, with
French versions of the MyBookmark pages.

| Page | Path |
| --- | --- |
| Home | `/` |
| MyBookmark | `/mybookmark/` |
| MyBookmark — privacy policy | `/mybookmark/privacy/` |
| MyBookmark, in French | `/mybookmark/fr/` |
| MyBookmark — privacy policy, in French | `/mybookmark/fr/privacy/` |
| Matcha Rush | `/matcha-rush/` |
| Matcha Rush — privacy policy | `/matcha-rush/privacy/` |
| Matcha Rush, in French | `/matcha-rush/fr/` |
| Matcha Rush — privacy policy, in French | `/matcha-rush/fr/privacy/` |

The MyBookmark and Matcha Rush pages have an EN | FR switch in the header.
Screenshots live in `assets/img/<app>-screens/` (English) and `…/fr/`
(French). MyBookmark's come from `tool/screenshots` in its repository; Matcha
Rush's are landscape captures of the web build (854 × 480 at ×2, WebP), shown
with the `.gallery-track.landscape` variant.

Matcha Rush, unlike MyBookmark, shows rewarded ads (AdMob), sends anonymous
statistics (Firebase) and has in-app purchases: its privacy policy says so,
and the home page no longer promises "no ads" for every app.

Old paths redirect to the current ones: `/biblivre/…` (the app's first name)
and `/mybookmark/confidentialite/` (the French privacy URL).
`/matcha-rush/confidentialite/` forwards to the French privacy policy.

## Adding an app

1. Copy the `mybookmark/` folder under the new app's name, then adapt the text
   and the icon (`assets/img/`).
2. Add its card to the `.apps` list in `index.html`.

## Custom domain

To move to your own domain: *Settings → Pages → Custom domain*, then add a
`CNAME` record pointing to `benjamingott.github.io` at your registrar. Links
are root-relative (`/mybookmark/…`) and keep working. Remember to update the
privacy policy URL in the Play Console and on Meta.
