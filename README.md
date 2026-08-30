# Endless Summer Grass Tournament — schedule page

`index.html` is served by GitHub Pages and embedded in the tournament page on
surfandturfvolleyball.net.

It lives here rather than being served from the Wix site's own `_functions`
route because Wix puts `default-src 'self'; script-src 'nonce-<uuid>'` on every
`_functions` response, which blocks the page's inline script and styles outright.

**Do not edit `index.html` here.** It is generated. The source of truth is
`tools/schedule-source.html` in the site repo; run `npm run deploy:page` there.
