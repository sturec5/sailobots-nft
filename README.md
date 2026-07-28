# Sailobots

Sail-o-Bots is a collection of 750 unique digital art pieces created on Art Blocks. This repository is a clean mirror of the project source and supporting notes, not a per-token dump.

<img width="1455" alt="Sail-o-Bots project preview" src="https://user-images.githubusercontent.com/120736771/210150824-e62bb083-7704-4d85-b4e4-3487ef14065b.png">

## Repository Layout

- `index.html` - portfolio-style landing page
- `src/sailobots.js` - the project-level p5.js generator script
- `preview/index.html` - local preview entrypoint
- `docs/auction-history.md` - verified Sotheby's auction history
- `docs/public-record.md` - selected external references and coverage
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
Open `index.html` for the visual landing page, or `preview/index.html` to render the project locally with a sample token hash.

## Auction History

The project has a verified public Sotheby's record across at least nine lot listings in eight sales between June 1, 2023 and April 16, 2025.
See `docs/auction-history.md` for the official lot links and dates.

## Public Record

For a compact set of official pages, editorial mentions, and artist-level exhibition or interview references, see `docs/public-record.md`.

## Artist Links

- Website: https://sturec.art
- Twitter: https://twitter.com/sturec5
