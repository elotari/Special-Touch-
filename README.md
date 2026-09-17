# Special Touch Co. — Website Prototype

Prototype by Tamo Haus.

| File | View |
| --- | --- |
| `index.html` | Start here — choose a view |
| `desktop.html` | Desktop website prototype |
| `mobile.html` | Mobile web prototype |
| `timeline.html` | Delivery timeline |

## Deploy

Upload **everything in this folder** to the repository root, then:

**Railway** — New Project → Deploy from GitHub repo → pick this repo. It detects
`package.json` and runs `node server.js`, which sets a Content-Security-Policy
allowing `'unsafe-eval'`. The prototype compiles its logic in the browser, so
without that header the page reports
"'unsafe-eval' is not an allowed source of script" and stays blank.

**GitHub Pages** — repository must be Public. Settings → Pages → Deploy from a
branch → `main` / `/ (root)`. `server.js` and `package.json` are ignored there.

Both can run at the same time from the same repository.
