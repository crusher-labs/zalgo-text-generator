# Zalgo Text Generator

Turn any text into cursed Zalgo glitch text with stacked Unicode combining marks: adjustable intensity, above/through/below toggles, one-click copy.

Live: <https://crusher-labs.github.io/zalgo-text-generator/>

## Privacy

This tool runs entirely in your browser. There is no server. No data is uploaded, no telemetry, no analytics.

## Framework / hosting

- Static HTML / CSS / JS deployed via GitHub Pages from this repo's `main` branch.
- UI chrome is the published `crusher-ui-kit` static contract; the pinned version and its SRI hashes are managed fleet-wide by `tools-hub/scripts/bump-kit.mjs`.

## Development

- Open `index.html` directly in a browser. No build, no dependencies.
- Or serve the parent workspace via the hub's preview server: `cd ../../tools-hub && npm run preview` then visit `http://127.0.0.1:8723/utility-tools/zalgo-text-generator/`.

## License

MIT.
