# Project Phi Grid v14
### Dual-Anchor Geometric Framework: Wilkes Land & Hiawatha Crustal Gravity Anomalies

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19119306.svg)](https://doi.org/10.5281/zenodo.19119306)

---

## Overview

Project Phi Grid is an independent research investigation into whether a 16-petal geometric framework anchored at two crustal gravity anomalies produces statistically significant alignments with globally distributed archaeological, geophysical, and geomagnetic features.

The two anchors are:
- **Wilkes Land crustal gravity anomaly** — 70.0°S, 120.0°E (Antarctica)
- **Hiawatha impact structure** — 78.72°N, 67.0°W (Greenland)

---

## Core Finding — The Primary Triangle

The distances from the Wilkes Land anchor to Easter Island and Teotihuacan form a ratio of **1.6159**, against φ = 1.6180 — an error of **0.37%**. Both sites lie on the same 135° bearing petal, forming the foundational geometric relationship of the framework.

---

## Key Results

| Result | Value |
|---|---|
| Primary phi-ratio error (Easter → Teotihuacan) | 0.37% |
| Monte Carlo p-value (10,000 trials) | p = 0.0102 |
| IOGL angular alignment (Petal 15) | 1.00° |
| SAA western cell alignment (Petal 3) | 1.06° |
| Wilkes–Hiawatha antipodal offset | ~990 km |
| Antipodal chance probability | ~1 in 800 |

### Verified Double-Hits
Sites satisfying **both** angular error < 2° **and** φ-distance error < 2%:
- Easter Island
- Teotihuacan
- Göbekli Tepe

### Partial Hits
Mnajdra Malta · Knossos · Çatalhöyük · Great Pyramid · Stonehenge · Angkor Wat · Machu Picchu · Nazca Lines

### Geophysical Alignments
- **IOGL** (Indian Ocean Geoid Low) — tightest geophysical alignment in the dataset at 1.00° from Petal 15
- **SAA** (South Atlantic Anomaly) western cell — 1.06° from Petal 3
- **Chicxulub, Vredefort, Popigai** impact craters tested in Section 16 six-anchor survey

---

## Dual-Anchor Geometry

The Wilkes Land and Hiawatha anomalies are near-mutually antipodal with an offset of ~990 km. The probability of two crustal anomalies falling this close to mutual antipodal positions by chance is approximately 1 in 800. Paleomagnetic pole wander data (CALS7k) shows both the north and south geomagnetic poles have historically wandered around their respective anchors while the grid geometry remains stationary.

![Dual-Anchor Visualization](phi_grid_v14_dual_anchor.png)
*16-petal grids from both anchors overlaid on a global map, with pole wander paths, verified sites, SAA, IOGL, and impact craters.*

---

## Notebook Structure

| Section | Content |
|---|---|
| 0 | Core constants, haversine & bearing functions |
| 2 | Primary phi triangle — Wilkes → Easter → Teotihuacan |
| 3 | Full 16-petal grid — verified and partial hits |
| 4 | SAA alignment — corrected petal assignment |
| 5 | Multi-year pipeline results (Aug 2002–Dec 2005) |
| 6 | Scatter plot diagnostic |
| 7 | SAA alignment — 2026 verified data |
| 8 | Monte Carlo specificity test |
| 9 | Intersection point search & node clustering |
| 10 | CSY pair pipeline (TEO↔CSY, HER↔CSY) |
| 11 | DRV replication pipeline (2006–2008) |
| 12 | Physical mechanism hypothesis |
| 15 | Hiawatha crustal anomaly — northern hemisphere boundary condition |
| 16 | Six-anchor geometric survey — global gravity anomalies & impact structures |
| 17 | Dual-anchor geometric framework visualization |

---

## Reproducibility

The notebook is fully self-contained and Google Colab compatible. All coordinate data, functions, and Monte Carlo logic are documented inline. Results are reproducible by running cells sequentially after mounting Google Drive and extracting the provided data archive.

**Requirements:** Python 3, NumPy, SciPy, Pandas, Matplotlib, Plotly

---

## Files

| File | Description |
|---|---|
| `phi_grid_v14_Section16_SixAnchor.ipynb` | Full documented Python notebook |
| `phi_grid_v14_dual_anchor.png` | Dual-anchor visualization (dark) |

---

## Citation

If referencing this work please cite the Zenodo record:

> Davis, R. (2026). *Project Phi Grid v14 — Dual-Anchor Geometric Framework: Wilkes Land & Hiawatha Crustal Gravity Anomalies*. Zenodo. https://doi.org/10.5281/zenodo.19119306

---

## Status

This is an independent, open research project. All statistical results are computed transparently within the notebook. Feedback and independent verification are welcome.
