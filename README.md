# libergot — app website

Static site published with GitHub Pages: <https://benjamingott.github.io/>.
Plain HTML and one stylesheet, no build step. The site is in English.

| Page | Path |
| --- | --- |
| Home | `/` |
| MyBookmark | `/mybookmark/` |
| MyBookmark — privacy policy | `/mybookmark/privacy/` |

Old paths redirect to the current ones: `/biblivre/…` (the app's first name)
and `/mybookmark/confidentialite/` (the French privacy URL).

## Adding an app

1. Copy the `mybookmark/` folder under the new app's name, then adapt the text
   and the icon (`assets/img/`).
2. Add its card to the `.apps` list in `index.html`.

## Custom domain

To move to your own domain: *Settings → Pages → Custom domain*, then add a
`CNAME` record pointing to `benjamingott.github.io` at your registrar. Links
are root-relative (`/mybookmark/…`) and keep working. Remember to update the
privacy policy URL in the Play Console and on Meta.
