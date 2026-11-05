# curvesNshapes

Field and shop calculator, single-file PWA.

- **H-Curve** — horizontal curve solver from any two of Δ, R, D, T, L, LC, E, M; stakeout deflections (ft/m) or shop offsets from chord or tangent (in/mm).
- **V-Curve** — symmetric parabolic vertical curve, high/low point, elevation table.
- **Area / Volume** — common shapes, imperial and metric units, adjustable waste %.
- **Triangle** — solve from any three values (at least one side), live sketch, SSA ambiguous case.

Inputs, theme and colours are saved in the browser (localStorage). Works offline after the first visit.

## Files
```
index.html
manifest.json
sw.js
icons/
  icon.svg
  icon-maskable.svg
  icon-192.png
  icon-512.png
  icon-maskable-512.png
  apple-touch-icon.png
  favicon-32.png
```

## Updating
Edit `index.html`, then bump `VERSION` in `sw.js` (e.g. `cns-v2`) so installed copies refresh their offline cache.
