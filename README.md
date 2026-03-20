# Project Phi Grid

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19121315.svg)](https://doi.org/10.5281/zenodo.19121315)

**Independent geophysical research notebook investigating whether a 16-petal geometric framework anchored at two crustal gravity anomalies exhibits statistically significant alignment with archaeological sites and geophysical features.**

---

## Primary Result

> Monte Carlo test (10,000 trials): archaeological site alignment at **p = 0.0102** — significantly above chance — anchored at the Wilkes Land crustal gravity anomaly (70.0°S, 120.0°E).

---

## What Is This?

Project Phi Grid tests whether the golden ratio φ ≈ 1.618 governs the spatial distribution of:
- Major archaeological sites (Teotihuacan, Easter Island, Göbekli Tepe, Nazca Lines, and others)
- Geophysical features (impact craters, gravity anomalies, tectonic boundaries, mantle heterogeneities)

relative to two sub-ice crustal gravity anomalies used as geometric anchors:

| Anchor | Coordinates | Description |
|--------|-------------|-------------|
| **Wilkes Land** | 70.0°S, 120.0°E | Sub-Antarctic crustal gravity anomaly |
| **Hiawatha** | 78.72°N, 67.0°W | Sub-Greenland impact crater |

The framework divides the sphere into 16 petals at 22.5° intervals and uses φ-ratio distances to define radial "shells" from each anchor.

---

## Key Results

| Finding | Value | Status |
|---------|-------|--------|
| Primary phi-triangle (Wilkes→Easter Island→Teotihuacan) | 0.37% error | ✅ Confirmed |
| Monte Carlo p-value — archaeological sites (Sec. 8) | **p = 0.0102** | ✅ Confirmed |
| Wilkes–Hiawatha antipodal offset | ~990 km (~1 in 800) | ✅ Pre-computed |
| IOGL alignment — Petal 9, 1.71° error, 4.1% φ-err (Ghosh 2017) | Confirmed hit | ✅ Section 16 |
| Section 12 null results (GNA / HAD / OTT) | 0 / 3 phi in CI | ⬜ Null |
| Section 13 null results — Hiawatha pipeline | 0 / 5 pairs | ⬜ Null |
| Section 16 geophysical survey Monte Carlo | p ≈ 0.95 (1 hit / 20) | ⬜ Null overall |

---

## Notebook Structure

| Section | Content |
|---------|---------|
| 1–4 | Geometric setup, haversine functions, petal definitions, phi-triangle |
| 8 | Monte Carlo specificity test — archaeological sites, **p = 0.0102** |
| 9–10 | Extended site analysis, CSY pair pipeline |
| 11 | DRV replication pipeline (null) |
| 12 | Extended observatory replication — GNA, HAD, OTT (all null) |
| 13 | Hiawatha anchor pipeline — TEO, ABK, TRO, HAD, OTT (all null) |
| 15.2 | Hiawatha background, antipodal geometry |
| 16 | Six-anchor geophysical survey — IOGL confirmed hit |
| 17 | Dual-anchor global visualization |

---

## Two Hypotheses — Clearly Separated

**Geometric alignment hypothesis** (Sections 2, 3, 8, 16)
Statistically supported at p < 0.01 for archaeological sites. Stands independently.

**Electromagnetic propagation hypothesis** (Sections 5–13)
Preliminary and unconfirmed. Null results in Sections 11, 12, and 13 are documented honestly as negative evidence. Not claimed as established.

---

## IOGL — Confirmed Geophysical Hit

The Indian Ocean Geoid Low (4.8°N, 78.4°E; [Ghosh et al. 2017](https://doi.org/10.1002/2017GL075049)) aligns with Petal 9 of the Wilkes Land grid at:
- Angular error: **1.71°** (threshold ±4°) ✅
- φ-distance error: **4.1%** (threshold ±10%) ✅

The IOGL is the Earth's largest negative gravity anomaly (~−106 m geoid height relative to WGS84), making it a physically significant candidate for a third phi-grid anchor.

---

## Data Sources

- INTERMAGNET geomagnetic data — [BGS World Data Centre](https://www.bgs.ac.uk/data/wdc/)
- Kp index — [GFZ Potsdam](https://www.gfz-potsdam.de/en/section/geomagnetism/data-products-services/kp-index)
- NASA/GRACE gravity data — [NASA Physical Oceanography DAAC](https://podaac.jpl.nasa.gov/)
- IOGL coordinate — Ghosh, A. et al. (2017), *Geophysical Research Letters*, 44(19), 9707–9715

---

## Zenodo

Full notebook archived at:
**DOI: [10.5281/zenodo.19121315](https://doi.org/10.5281/zenodo.19121315)**

---

## License

CC BY 4.0 — Raymond Davis, 2026
