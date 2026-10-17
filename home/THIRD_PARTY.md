# Third-party sources — Agent Home v3

| Source | URL | License | What we use |
|---|---|---|---|
| three.js (incl. examples/jsm OrbitControls, GLTFLoader, EffectComposer, UnrealBloomPass, OutputPass) | https://github.com/mrdoob/three.js | MIT | 3D renderer, touch orbit/zoom, glTF loading, bloom post-processing (npm `three`) |
| augmented-ui | https://github.com/propjockey/augmented-ui | BSD-2-Clause | Cyberpunk clipped-corner/border CSS on agent cards (npm `augmented-ui`) |
| Kenney Furniture Kit 2.0 | https://kenney.nl/assets/furniture-kit | CC0 1.0 | desk, chairDesk, pottedPlant, loungeSofa .glb (recolored at runtime, ~100 KB total; files in `public/models/`, license copy `KENNEY-LICENSE.txt`) |
| spaceship-dashboard (DC INFOSEC) | /workspace/ref/spaceship-dashboard | MIT | Design ideas only: department rooms with accent colors, status-lamp colors, data-flow lines between linked agents. No code copied; `src/services` not used. |
| Syncopate (Andrew Paglinawan) via @fontsource/syncopate | https://fonts.google.com/specimen/Syncopate | SIL OFL 1.1 | Extended heavy uppercase headers in Signal Loft (latin 700, bundled) |
| JetBrains Mono via @fontsource/jetbrains-mono | https://github.com/JetBrains/JetBrainsMono | SIL OFL 1.1 | Monospace data in Signal Loft (latin 400/800, bundled) |
| Vite / TypeScript | https://github.com/vitejs/vite · https://github.com/microsoft/TypeScript | MIT · Apache-2.0 | Build tooling (dev only) |

Bottom sheet and swipe cards are small hand-written CSS scroll-snap + touch handlers: the GitHub components found were React/Vue-bound and would add a framework.

Signal Loft spider mascot, radar and lock lines are hand-written procedural SVG/Three.js (no external asset). Look inspired by a CrawlHive narrative-radar video breakdown (style only, no code/assets copied).
