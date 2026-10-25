# Piston Punch V2 — Robot sprites

- `piston-punch-sprite-atlas.svg`: transparent vector atlas committed to the repository.
- 288×288 viewBox; 6 columns × 6 rows; each frame is 48×48.
- Animation rows: idle, walk, run, attack, jump, hurt/KO.

The Canvas renderer loads this file locally and selects frames for idle, walking, running, punching and taking damage. If SVG loading fails, the game retains its procedural fallback robot.

The SVG is a lightweight vector adaptation of the concept art's visual cues (dark armor, orange plating, cyan optics/core), not a pixel-perfect extraction of the provided raster concept sheet.