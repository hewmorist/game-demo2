# Daily Gallery

A browser art-identification game accompanying Hewmorist’s [A Work Of Art](https://on.soundcloud.com/d9Fq7yY1TEDhRxWE5p).

Deployment-ready package: compiled WebAssembly, minified JavaScript, artwork and published exhibition data. Serve this branch’s root directory over HTTP(S); no build is required. For GitHub Pages select `daily-gallery` and `/ (root)`.

A scheduled publisher reads the master spreadsheet and starts at midnight America/Los_Angeles, beginning October 24, 2026. A complete dated Ready exhibition takes precedence; otherwise it selects from prepared artworks and credits AlanAi. Published daily data and exact previous-day answers are saved in this branch. Updates become available after preparation and Pages deployment. No player progress is stored.

Artwork JPEGs are under 50,000 bytes each. Image sources and rights notes are recorded in the exhibition JSON files. The Miniquad browser loader’s MIT notice is retained in `vendor/LICENSE-MIT`. No license is granted for the original project code or other original content by publishing this repository.

Runtime revision: daily-trial-r1. Packaged from development revision 6955308.
