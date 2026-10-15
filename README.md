# expressed.app redirect

This repo only forwards visitors from expressed.app to the Expressed page on
east73studio.com. It's hosted on GitHub Pages so expressed.app gets HTTPS
(required: every .app domain is HTTPS-only in browsers).

- expressed.app, www.expressed.app → https://east73studio.com/expressed/
- expressed.app/privacy, /terms, /support → the matching page on east73studio.com
- `404.html` is a copy of `index.html`, so every path is caught.

Email for expressed.app (hello@expressed.app forwarding) is handled by
Namecheap Email Forwarding and is unaffected by this repo.
