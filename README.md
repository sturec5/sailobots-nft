# Sailobots

Sail-o-Bots a.k.a. SeaHams is a collection of 750 unique digital art pieces created on Art Blocks. This repository is a clean mirror of the project source and supporting notes, not a per-token dump.

<img width="1455" alt="sailobots-seahams-nft" src="https://user-images.githubusercontent.com/120736771/210150824-e62bb083-7704-4d85-b4e4-3487ef14065b.png">

## Repository Layout

- `src/sailobots.js` - the project-level p5.js generator script
- `preview/index.html` - local preview entrypoint
- `docs/license.md` - the Art Blocks project license note
- `docs/provenance.md` - contract, project, token hash, and attribution notes
- `README.md` - overview and quick links

## What Belongs Where

Keep the shared generator code in `src/sailobots.js`.
Do not make separate files for each minted token unless you specifically want examples or screenshots.
Each token only contributes its own `tokenData.hash` and metadata at render time; the artwork logic lives in the shared project script.

## Project Link

Art Blocks project page: https://www.artblocks.io/collections/presents/projects/0xa7d8d9ef8d8ce8992df33d8b8cf4aebabd5bd270/98

## Notes

The source mirrors the on-chain Art Blocks project script and includes provenance details in `docs/provenance.md`.
Open `preview/index.html` in a browser to render the project locally with a sample token hash.
