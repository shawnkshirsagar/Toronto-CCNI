Toronto-CCNI

This repository contains the applied project for JPG2151: GIS & Society.

The project develops a Toronto-specific Climate Canopy Need Index (CCNI) that combines tree canopy deficit, building density, population density, income vulnerability, and racialized population indicators to identify broad areas where urban greening may be most needed in Toronto.

Live links

- Interactive web map: https://shawnkshirsagar.github.io/Toronto-CCNI/
- GitHub repository: https://github.com/shawnkshirsagar/Toronto-CCNI

Repository contents

- `index.html` — interactive web map
- `TorontoCCNI.pdf` — final written report
- `scripts/` — simplified workflow scripts
- `data/` — processed non-spatial outputs and source notes
- `resources/` — project notes and workflow context

Workflow summary

The project combined tract-level tree canopy coverage, socio-demographic vulnerability indicators from the 2021 census, and building density to construct a normalized Climate Canopy Need Index (CCNI). The workflow moved through data preparation, alignment, normalization, index construction, and interactive mapping using R, Leaflet, and GitHub Pages.

Project purpose

The CCNI was designed as a transparent and reproducible GIS workflow that translates tract-level environmental and socio-demographic indicators into an interpretable planning tool for discussing urban heat equity in Toronto.
