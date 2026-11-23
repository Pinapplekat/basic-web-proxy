# basic-web-proxy

A simple web proxy from June 2022, built with Express.

Request `/?url=example.com` and the server fetches the page and rewrites its links (with `absolutify`) so clicks route back through the proxy. It also forwards POST requests. An earlier version rendered pages with Puppeteer before switching to plain fetches.

*Archived early project. Some dependencies used in `index.js` (`node-fetch`, `cheerio`, `cors`, `mock-browser`) are missing from `package.json`.*
