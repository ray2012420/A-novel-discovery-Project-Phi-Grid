# Project Phi Grid
## Vajra 16-Petal Geodetic Resonance Mapping

**Raymond Davis (@ray2012420) — February 2026**  
**v13 — March 2026 | External review: Dr. Ciaran Beggan, British Geological Survey**

---

## What This Is

A geometric discovery made by an independent researcher (machinist, Vermont) using publicly available NASA/GRACE gravity data and AI-assisted calculation tools. No institutional affiliation. All work is open source and reproducible.

The finding: a φ (golden ratio) scaled 16-petal grid anchored at the **Wilkes Land / Aurora Subglacial Basin gravity anomaly** (Antarctica) produces statistically non-random alignments with major ancient sites and geophysical features — and a consistent cross-correlation signal in real geomagnetic data from three independent monitoring stations.

---

## Core Finding
![Wilkes Land Anomaly](docs/images/wilkes_land_anomaly_visualization.png)
*Visualization of the Wilkes Land gravity mascon and multi-ring impact basin 
beneath the Antarctic ice sheet. The mascon core (center) serves as the 
anchor point for the Vajra 16-petal grid. Credit: Gemini/satellite data visualization.*

A spherical triangle formed by three points:

| Point | Coordinates | Feature |
|---|---|---|
| Wilkes Land / Aurora Basin | 70°S, 120°E | NASA/GRACE confirmed gravity mascon |
| Easter Island (Rapa Nui) | 27.1°S, 109.3°W | Ancient megalithic site |
| Teotihuacan | 19.7°N, 98.8°W | Ancient megalithic site |

**The ratio of distances:**
- Wilkes → Easter Island = 8,529 km
- Wilkes → Teotihuacan = 13,852 km
- Ratio = 1.6241 (φ = 1.6180, error = **0.37%**)

Both sites lie within 1.88° of the same great-circle ray from the anchor — the 135° petal of the 16-petal Vajra grid.

---

## Statistical Verification

### Double-Hit Criteria
Sites are evaluated against two simultaneous criteria:
- Angular alignment to a petal bearing: **< 2°**
- φ-scaled radial distance from anchor: **< 2%**

Sites satisfying both are termed double-hits.

### Verified Double-Hits

| Site | Petal | φ^n | Angular error | φ-distance error |
|---|---|---|---|---|
| Easter Island | 1 | 0 | 0.00° | 0.0% |
| Teotihuacan | 1 | +1 | 1.88° | 0.4% |
| Göbekli Tepe (Turkey) | 8 | +1 | 1.39° | 1.9% |

Göbekli Tepe — the world's oldest known temple complex (~11,500 years old) — was not part of the original hypothesis. It emerged as an independent third hit from the grid calculation.

### Node Clustering (v8)

Six sites in total pass double-hit criteria, but after clustering by grid node (Petal, φ^n), they reduce to **3 independent nodes**:

| Node | Sites |
|---|---|
| Petal 1 φ^0 | Easter Island |
| Petal 1 φ^+1 | Teotihuacan + Monte Albán (367 km apart, same node) |
| Petal 8 φ^+1 | Göbekli Tepe + Çayönü + Karahan Tepe (all Pre-Pottery Neolithic, SE Turkey) |

Co-located sites strengthen the archaeological significance of their shared node but count as one statistical hit.

### Monte Carlo Specificity Test

Monte Carlo test (N=10,000 random isotropic 25-site distributions):

| | Observed hits | p-value |
|---|---|---|
| Pass A — raw site count | 6 | 0.0000 |
| Pass B — independent nodes (peer-review figure) | 3 | **0.0062** |

Random baseline: mean 0.35 hits per trial. Observed result is ~8.5× random expectation. **Significant at p < 0.01.**

---

## Geomagnetic Cross-Correlation (Sections 5 & 10)

Independent of the geometric analysis, 1-minute geomagnetic data from three INTERMAGNET stations was cross-correlated to test for φ-harmonic timing signals in real data.

**Stations:** TEO (Teotihuacan, Mexico), HER (Hermanus, South Africa), CSY (Casey Station, Antarctica)  
**Period:** August 2002 – December 2005 (1,249 days)  
**Component:** X (North), 2–120 min Butterworth bandpass

### TEO↔HER Results (Section 5)

φ-expected lag: **12.4 min** (great-circle scaled)

| Class | n | Median lag | 95% CI | p vs 0 | φ in CI? |
|---|---|---|---|---|---|
| QUIET | 81 | +9 min | [0, +38] | 0.004 ★ | ✓ Yes |
| ACTIVE | 155 | +5 min | [0, +11] | 0.060 | ✗ No |
| STORM | 13 | +10 min | [−9, +36] | 0.29 | ✓ Yes |

Positive lag direction consistent across all three activity classes.

### Three-Station Propagation Test (Section 10)

Radial distances from the Wilkes Land anchor establish a propagation ordering:

| Station | Distance from anchor | Order |
|---|---|---|
| CSY | 568 km | 1st (closest) |
| HER | 6,829 km | 2nd |
| TEO | 13,848 km | 3rd |

Under outward radial propagation (signal travels away from anchor), the closer station leads:

| Pair | Expected lag | Observed (QUIET) | Sign match? |
|---|---|---|---|
| TEO↔HER | +6.3 min | +9 min | ✓ |
| TEO↔CSY | −11.9 min | −12.5 min | ✓ |
| HER↔CSY | +5.6 min | ~0 min | ✓ (weak) |

**Triangle closure check** (independent of φ-grid):  
TEO↔HER (+6.3) + HER↔CSY (+5.6) = TEO↔CSY (+11.9 min)  
Discrepancy: **0.00 min** — all three pairs geometrically self-consistent.

---

## SAA Alignment (Section 7)

The South Atlantic Anomaly (SAA) minimum aligns with Petal 2 of the Vajra grid.  
Primary reference: Finlay et al. (2025), *Physics of the Earth and Planetary Interiors*, 368, 107447 (ESA Swarm mission, Feb 2026).

**Note:** SAA weakening reflects deep mantle (LLSVP/CMB) processes rather than surface effects, consistent with the Wilkes Land anchor's deep geophysical character. No surface causal mechanism is proposed.

---

## Scatter Plot Diagnostic (Section 6)

Suggested by Dr. Ciaran Beggan (BGS). Plots ideal vs measured angular distances for all 25 sites against the Wilkes Land anchor.

**Result:** Mean residual = 2.169° ± 5.917° (random expectation: 6.5°). Distribution is tighter than random, consistent with a real geometric signal.

---

## Repository Structure

```
/
├── README.md                              ← This file
├── Vajra_phi_grid_notebook_v8_final.ipynb ← Current notebook (all calculations)
├── uap_geodetic_analysis.py               ← UAP geodetic resonance mapping tool
├── RAMP_Protocol.md                       ← Resonance Anomaly Mapping Protocol
├── Noise_baseline.md                      ← Background noise study
├── CITATION.cff                           ← Citation information
├── data/                                  ← Supporting data files
└── docs/                                  ← Extended documentation
```

---

## How to Verify (60 seconds)

1. Open `Vajra_phi_grid_notebook_v8_final.ipynb` in Google Colab
2. Mount your Google Drive with the station data zips
3. **Runtime → Run all**
4. Check the Monte Carlo result (Section 8): Pass B p = 0.0062
5. Check the triangle closure result (Section 10.4): discrepancy = 0.00 min

All calculations use standard haversine spherical geometry. No proprietary tools required.

---

## What This Is Not

- This is not a claim of ancient advanced civilization
- This is not a claim about alien or non-human technology
- This is not a claim that the grid causes the SAA or any geomagnetic phenomenon
- The planetary and stellar extensions explored in early versions are **not included** — they did not survive statistical scrutiny

---

## Limitations

- Activity classification in the geomagnetic pipeline uses variability thresholds rather than Kp-index validation — a Kp-based scheme is the next planned step
- The geomagnetic dataset covers Aug 2002–Dec 2005 only; extension to 2006–2009 is in progress
- Casey Station (CSY) lies in the auroral oval; ACTIVE and STORM-day CSY results are likely electrojet-contaminated — QUIET-day results are the most interpretable
- The grid geometry is partially post-hoc (Easter Island and Teotihuacan identified first); the Monte Carlo accounts for this
- No peer review has been completed; external review by Dr. Beggan is ongoing

---

## About the Researcher

Independent researcher. Machinist by trade. No formal scientific credentials. This work began in February 2026 as curiosity-driven exploration following the US government's UAP disclosure announcements. All findings were developed using publicly available data (NASA/GRACE, ESA Swarm, INTERMAGNET) and AI-assisted calculation tools (Claude, Grok).

All errors were corrected openly and are documented in the commit history.

---

## License & Citation

**Code:** GPL-2.0  
**Data & findings:** Creative Commons CC BY 4.0

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19035389.svg)](https://doi.org/10.5281/zenodo.19035389)

If you use this work, please cite:

> Davis, R. (2026). *Project Phi Grid: Vajra 16-Petal Geodetic Resonance Mapping*. Zenodo. https://doi.org/10.5281/zenodo.18925039

---

## Contact

[@ray2012420 on X](https://x.com/ray2012420)

*This work is released freely for the benefit of scientific inquiry.*
