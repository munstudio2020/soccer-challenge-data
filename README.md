# Soccer Challenge data packs

Public host for the Soccer Challenge app's player dataset, served via GitHub Pages.

The app reads one file to find the rest: `dataset/index.json`, which points at the per-difficulty packs under `dataset/packs/`. Each pack carries its own version and SHA-256 digest, verified by the app before it trusts a download.

Player careers come from Wikidata (CC0). Club names and dates only; no crests, kits or photographs.
