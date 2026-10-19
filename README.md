Evidence for the tangency-labs/solidcraft pull request "STEP import: read the micro edges and tiny knot spans Siemens NX writes".

- `block-bezier-1e-7-knots.step`: a 30 × 20 × 10 mm block exported by SolidCraft, with each of its 12 straight edges rewritten as a straight cubic Bézier over the knot span (0, 1.020781457822E-07), the way Siemens NX writes edges.
- `before-main.png`: SolidCraft 0.16.2 (main) opens it as an empty design: "STEP import: no bodies (solid 'Bloco': not imported: no face could be imported)".
- `after-branch.png`: the pull request's branch opens it whole (one body, 6 faces).
