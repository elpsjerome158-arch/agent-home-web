# Third-party sources — Agent Home v3

| Source | URL | License | What we use |
|---|---|---|---|
| three.js (incl. examples/jsm GLTFLoader) | https://github.com/mrdoob/three.js | MIT | Isometric war-room renderer (OrthographicCamera), Signal Loft radar, glTF loading (npm `three`) |
| Kenney Furniture Kit 2.0 | https://kenney.nl/assets/furniture-kit | CC0 1.0 | pottedPlant.glb in the war room (procedural cone fallback); other kit files remain in `public/models/`, license copy `KENNEY-LICENSE.txt` |
| spaceship-dashboard (DC INFOSEC) | /workspace/ref/spaceship-dashboard | MIT | Design ideas only: department rooms with accent colors, status-lamp colors, data-flow lines between linked agents. No code copied; `src/services` not used. |
| Rajdhani (Indian Type Foundry) via @fontsource/rajdhani | https://fonts.google.com/specimen/Rajdhani | SIL OFL 1.1 | Headers, panel titles and numbers (latin 600/700, bundled) |
| JetBrains Mono via @fontsource/jetbrains-mono | https://github.com/JetBrains/JetBrainsMono | SIL OFL 1.1 | Monospace data across the app (latin 400/800, bundled) |
| Coinbase Exchange public market data API | https://docs.cdp.coinbase.com/exchange/reference | Public API terms (no key, CORS *) | SOL/BTC/ETH-USD ticker, 24h stats and hourly candles, fetched live in the browser |
| Kraken public REST Ticker | https://docs.kraken.com/api/ | Public API terms (no key) | Fallback ticker when Coinbase is unreachable |
| Vite / TypeScript | https://github.com/vitejs/vite · https://github.com/microsoft/TypeScript | MIT · Apache-2.0 | Build tooling (dev only) |


Look inspired by eastenray1's "GROKBOT + JEV" X demo and a CrawlHive narrative-radar video breakdown (style only; no code or assets copied). War-room desks, monitors, ghost mascots, rocket, radar dish, network graph, charts and the Signal Loft spider are hand-written procedural Three.js / SVG / Canvas2D. The MARKET chart only plots public scout prices sampled in this browser; the site never shows balances, P&L or account digits.
