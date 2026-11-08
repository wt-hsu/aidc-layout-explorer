# AIDC Layout Explorer · AIDC 配置圖解

An isometric, layer-by-layer explorer of an illustrative 80 MW AI data center: how power, cooling, water and network run from the point of interconnection to the rack.

- Live: https://aidc-explorer.wantinghsu.com/ (also https://wt-hsu.github.io/aidc-layout-explorer/)
- Study page: https://wantinghsu.com/lab/aidc-layout/

## What's in it
- Five zoom levels: campus, building, space zones, rooms and systems, rack.
- Six system layers: power, cooling, water, network, fire and security, structure.
- Component cards with upstream and downstream links, due-diligence questions and public sources.
- Design options: utility outage sequence, N+1 or 2N, legacy air or AI liquid hall, 415 V AC or 800 VDC, cooling tower or dry cooler, phasing.
- Exploded NVL72-class rack with tray pull-out, NVLink spine and scale-out fibre.
- English and Chinese, following the browser's language.

## Files
- `index.html`: the whole explorer in one file (HTML, CSS and JavaScript).
- `vendor/three.min.js`: three.js r128, served locally.

No build step. GitHub Pages serves the repo root as-is.

Illustrative reference design; not based on any specific facility. Figures come from public sources cited on each component.
