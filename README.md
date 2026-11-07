# IronRoot Consulting

Static site for IronRoot Consulting. Publish it with GitHub Pages from the `main` branch at the repository root (`/`). No CNAME file is in this repo, and no custom domain should be configured.

Page copy, prices, booking links, and layout match the current preview site. Production-only additions in this repository:

- Google Analytics 4 measurement ID `G-VJBLDFXN01` (gtag.js on `index.html` and `privacy.html`)
- `sitemap.xml` lists only `https://ironrootstrategy.com/` and `https://ironrootstrategy.com/privacy.html`
- `robots.txt` allows indexing (`Allow: /`) and points to `https://ironrootstrategy.com/sitemap.xml`
- `og:image` and `twitter:image` use `https://ironrootstrategy.com/assets/og-share.png`
- The hostname-gated script still injects `noindex` only on `ironrootconsulting.github.io` and other `*.github.io` hosts
- Search Console HTML verification meta tag on `index.html` and `privacy.html`
