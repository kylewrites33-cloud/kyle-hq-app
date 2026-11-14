# Kyle HQ app

Kyle's dashboard as a web app for the iPad and phone home screen. This repo holds no data.
The app reads `hq/app-data.json` from Kyle's private personal-data repo with a GitHub key pasted into the app (kept on that device only), and saves his ticks and check-in answers as files in personal-data `hq/inbox/`.
The Chief of Staff's evening run writes the data file and applies the inbox.

`index.html` is built from the Kyle HQ claude.ai page by personal-data `hq/build_app.py` with `hq/shim.js`; rebuild rather than editing it by hand.
