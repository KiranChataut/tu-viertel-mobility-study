# TU Viertel: Parking Survey & Travel Demand Management Analysis

**Group Project — TDM Seminar, Chair of Urban Structure and Transport Planning, Technical University of Munich (2023)**

This project investigates mobility, parking, and recreational space challenges in the **TU Viertel**, a campus neighborhood near TUM's main campus in Munich. As part of a team project, the study combined field observations (tracing, activity mapping, counting) with **on-street parking occupancy surveys** to identify problems and propose concrete recommendations for a more car-independent, livable neighborhood.

**My contribution:** I led the **parking occupancy survey design and data analysis** — covering 9 street sections across 2 survey rounds (April & June 2023), each with weekday and weekend observations.

---

## Project Goals

- Identify urban mobility issues in TU Viertel: lack of recreational space, green infrastructure, bike infrastructure, and safety concerns
- Quantify on-street parking demand and utilization across the neighborhood
- Propose actionable, data-backed recommendations to reduce car dependency

---

## Methodology (Parking Survey Analysis)

- **9 street sections** surveyed (e.g. Steinheilstraße, Arcisstraße, Zieblandstraße, Luisenstraße, Schellingstraße)
- **2 survey rounds**: Round 1 (April 2023) and Round 2 (June 2023), each covering a weekday and a weekend
- For each section and time slot (morning / midday-afternoon / evening), recorded:
  - Overall **occupancy rate (%)**
  - **User group breakdown**: Day parking (D), Overnight parking (ON), Overnight+Day parking (ON/D), Permanent parking (P)
  - License plates (for residency/permit checks), illegal parking flags
- Data was originally collected in structured Excel survey forms, then consolidated and analyzed in Python (`pandas`, `matplotlib`)

---

## Key Findings

- Average parking occupancy across all sections and time slots ranged from **~18% to ~65%**
- **Zieblandstraße (Section 7)** consistently had the highest occupancy (50–65%) — high parking pressure
- **Luisenstraße (Section 8)** consistently had the lowest occupancy (~19%) — significant underused capacity
- Most sections showed **decreased occupancy in Round 2 (June)** vs Round 1 (April) — likely due to a seasonal modal shift toward walking/cycling in warmer weather
- An average of **8 vacant parking spots** were consistently observed on Schellingstraße — a strong candidate for road-space reallocation

---

## Recommendations (Team Output)

- **Road-space reallocation**: convert underused parking into bike lanes, trees, and green corridors (e.g. Schellingstraße, Luisenstraße)
- **Transform unused green space** into community gardens
- **Introduce open streets / green access corridors**
- **Park & Ride incentives**: rebalance pricing (lower P+R fees, raise resident parking fees) with direct tram/U-Bahn connections
- **Super blocks** (Barcelona-style) for the TU district
- Gradual parking reduction (e.g. ~3%/year, following Copenhagen's model)

---

## Repository Structure

```
├── README.md
├── notebooks/
│   └── parking_occupancy_analysis.ipynb     # Data consolidation + occupancy analysis & charts
├── data/
│   ├── 23_04_23_Parking_Survey_round1_weekend.xlsm
│   ├── 26_04_23_Parking_Survey_round1_weekday.xlsm
│   ├── 18_06_23_Parking_Survey_round2_weekend.xlsm
│   ├── 21_06_23_Parking_Survey_round2_weekday.xlsm
│   └── parking_occupancy_data.csv           # Cleaned/consolidated dataset
├── images/
│   ├── occupancy_comparison_rounds.png
│   ├── occupancy_comparison_daytype.png
│   └── study_area_map.png
└── TU_Viertel_Final_Presentation.pdf         # Full team presentation
```

---

## Team

This was a collaborative project involving team members across multiple workstreams (parking survey, activity mapping/tracing, green space analysis, bike infrastructure, GIS mapping). This repository focuses on the parking survey data collection and analysis component, contributed by **Kiran Chataut**.

Supervised by the Chair of Urban Structure and Transport Planning, TUM.
