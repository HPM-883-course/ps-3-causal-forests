# Problem Set 3: Causal Forests & Heterogeneous Treatment Effects

**Course:** HPM 883 — Advanced Quantitative Methods (Spring 2026)
**Due:** April 8, 2026

## Getting Started

1. Clone this repository locally: `git clone <your-repo-url>`
2. Open `hpm883-lab.Rproj` in RStudio or Positron
3. Run `renv::restore()` to install packages
4. Open `analysis.qmd` and complete the tasks

## Data

The dataset `data/ps-3-app-rct.csv` contains simulated RCT data from the Patient Engagement App trial (n=5,000).

## Packages

- `grf` — Causal forests and CATE estimation
- `policytree` — Policy tree learning
- `ranger` — Random forests (for meta-learners)
- `ggplot2` — Visualization
- `data.table` — Data manipulation
- `sandwich` + `lmtest` — Robust inference

All packages install automatically via `renv::restore()`.

## Submission

Push your completed `analysis.qmd` and rendered HTML to this repository by the deadline.
