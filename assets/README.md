# Sprite atlas integration

The game renderer now supports `assets/piston-punch-sprite-atlas.png`.

Expected layout: 6 columns × 6 rows, 48×48 pixels per frame. Rows: idle, walk, run, attack, jump, hurt/KO. Until that PNG exists at the path above, the game deliberately falls back to its procedural robot so the page remains playable.

The extracted atlas from the provided concept sheet still needs to be copied into this repository at the expected path to activate the animated sprites.
