# 2D Auto Battler

A web-based 2D auto-battler game built with Godot and exported to WebAssembly.

## Play Online

The game is published as a GitHub Pages site and can be played at:
**https://quadfade.github.io/2dAutoBattlerWeb/**

## About

2D Auto Battler is a turn-based strategy game featuring automated combat mechanics. Deploy your units and watch them engage in strategic battles. The game is built using the Godot game engine and runs directly in modern web browsers.

## Project Structure

- `docs/` — Godot web export files (HTML, WebAssembly, assets) published to GitHub Pages
  - `index.html` — Main entry point
  - `2d-autobattler.wasm` — WebAssembly binary
  - `2d-autobattler.pck` — Godot resource pack
  - `2d-autobattler.js` — Godot engine loader
  - Image and audio assets

## Browser Requirements

- Modern browser with WebAssembly support (Chrome, Firefox, Safari, Edge)
- 4+ MB available memory
- JavaScript enabled

## Building

If you want to rebuild the game from source, you'll need:
- Godot 4.x
- Export templates for HTML5/WebAssembly

Simply export the Godot project as HTML5 and replace the assets in the `docs/` folder.

## License

See repository for license details.
