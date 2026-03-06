# Project Phi Grid
## Vajra 16-Petal Geodetic Resonance Mapping

**Raymond Davis (@ray2012420) — February 2026**  
**v2 corrections verified with Claude (Anthropic) — March 2026**

---

## What This Is

A geometric discovery made by an independent researcher (machinist, Vermont) using publicly available NASA/GRACE gravity data and AI-assisted calculation tools. No institutional affiliation. All work is open source and reproducible.

The finding: a φ (golden ratio) scaled 16-petal grid anchored at the **Wilkes Land / Aurora Subglacial Basin gravity anomaly** (Antarctica) produces statistically non-random alignments with major ancient sites and geophysical features.

---

## Core Finding

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

A Monte Carlo test (n=10,000 random anchors) asked: how often does a random anchor point produce this many simultaneous hits (angular error <2° AND φ-distance error <2%) against a database of 24 major ancient sites?

**Result: p ≈ 0.01**

Wilkes Land produces more double-hits than 99% of random anchor points tested. This is statistically significant by conventional standards (p < 0.05).

### Verified Double-Hits (angle <2° AND φ-distance <2%)

| Site | Angular error | φ-distance error |
|---|---|---|
| Easter Island | 0.00° | 0.0% |
| Teotihuacan | 1.88° | 0.4% |
| Göbekli Tepe (Turkey) | 1.39° | 1.9% |

Göbekli Tepe — the world's oldest known temple complex (~11,500 years old) — was not part of the original hypothesis. It emerged as an independent third hit from the grid calculation.

---

## SAA Alignment (Corrected from v1)

The South Atlantic Anomaly (SAA) — a well-documented weakness in Earth's magnetic field — has been drifting westward at approximately 0.3°/year for decades.

**Finding:** The SAA's western cell aligns with **Petal 3** of the Vajra grid to within **1.06°** of bearing from the Wilkes Land anchor.

More significantly, tracking the SAA's historical center positions shows it has been **converging toward Petal 3** for 55 years:

| Year | Angular error from Petal 3 |
|---|---|
| 1970 | 17.20° |
| 1980 | 14.30° |
| 1990 | 10.62° |
| 2000 | 7.85° |
| 2010 | 5.09° |
| 2020 | 2.35° |
| 2025 | 0.07° |

The SAA has drifted onto Petal 3 in real time. This is an observed trajectory, not a static alignment.

**Note:** A full physical simulation of the SAA using spherical harmonic field modeling has not yet been completed. The angular alignment is verified; the causal mechanism is not proposed.

**Correction from v1:** The original notebook incorrectly labeled this alignment as the "11th petal." With Easter Island as Petal 1 (bearing 136.06°), the 11th petal points near-north (~1°), not toward the South Atlantic. The correct petal is Petal 3. This has been corrected in the v2 notebook.

---

## AMOC Corridor Hypothesis

The Atlantic Meridional Overturning Circulation (AMOC) transports heat from the Southern Ocean to the North Atlantic. Its abyssal limb originates from Antarctic Bottom Water formation in the Southern Ocean — geographically near the Wilkes Land anchor.

Preliminary geometric analysis suggests Petal 3 of the grid traces the Atlantic corridor connecting:
- Antarctic Bottom Water source region (~60°S, Atlantic sector)
- SAA center (~25°S, 55°W)  
- RAPID array monitoring line (26.5°N)
- OSNAP monitoring arrays (41°N, 53°N)

Two AMOC monitoring arrays (OSNAP East and OSNAP West) show angular alignment with grid petals to within 1°.

**This is an exploratory hypothesis only.** It has not been peer reviewed and no causal mechanism is proposed. It is presented as a direction for future investigation by qualified researchers.

---

## Repository Structure

```
/
├── README.md                          ← This file
├── Vajra_Phi_grid_notebook.ipynb      ← v2 corrected notebook (all calculations)
├── uap_geodetic_analysis.py           ← UAP geodetic resonance mapping tool
├── RAMP_Protocol.md                   ← Resonance Anomaly Mapping Protocol
├── Noise_baseline.md                  ← Background noise study
├── CITATION.cff                       ← Citation information
├── data/                              ← Supporting data files
└── docs/                              ← Extended documentation
```

---

## How to Verify (60 seconds)

1. Open `Vajra_Phi_grid_notebook.ipynb` in Google Colab
2. Run all cells
3. Check the φ ratio output (should be 1.6241, error 0.370%)
4. Check the Monte Carlo result (should return p ≈ 0.01)

All calculations use standard haversine spherical geometry. No proprietary tools required.

---

## What This Is Not

- This is not a claim of ancient advanced civilization
- This is not a claim about alien or non-human technology
- This is not a claim that the grid causes the SAA or influences the AMOC
- The planetary and stellar extensions explored in early versions of this work are **not included here** as they did not survive statistical scrutiny

---

## About the Researcher

Independent researcher. Machinist by trade. No formal scientific credentials. This work began in February 2026 as curiosity-driven exploration following the US government's UAP disclosure announcements. All findings were developed using publicly available data (NASA/GRACE, ESA Swarm) and AI-assisted calculation tools (Grok, Claude).

All errors were corrected openly and are documented in the commit history.

---

## Limitations

- Statistical significance (p=0.01) is interesting but not proof of a physical relationship
- The choice of which ancient sites to include affects the statistical outcome
- The Aurora Basin anchor (66.5°S, 110°E) produces a cleaner full grid than the confirmed mascon center (70°S, 120°E) — the reason for this discrepancy is not yet understood
- No peer review has been conducted

---

## License & Citation

**Code:** GPL-2.0  
**Data & findings:** Creative Commons CC BY 4.0 (public domain)

If you use this work, please cite:

> Davis, R. (2026). *Project Phi Grid: Vajra 16-Petal Geodetic Resonance Mapping*. GitHub. https://github.com/ray2012420/A-novel-discovery-Project-Phi-Grid

---

## Contact

[@ray2012420 on X](https://x.com/ray2012420)

*This work is released freely for the benefit of scientific inquiry.*
