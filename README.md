# U.S. Drilling Efficiency & Production Trends — Exploratory Data Analysis

## Overview

An exploratory data analysis examining the relationship between drilling activity and crude oil production across major U.S. basins, with a focus on the Permian Basin. The central question: **How is the U.S. producing more oil with fewer active rigs?**

## Data Source

- **Source:** U.S. Energy Information Administration (EIA) — Drilling Productivity Report
- **Access:** Publicly available at [eia.gov](https://www.eia.gov/)
- **Scope:** U.S. onshore drilling and production data, ~2023–2025

## Objective

The goal was to explore publicly available drilling data and uncover trends in operational efficiency across U.S. shale basins. Specifically:

- Is there a measurable shift in drilling efficiency over recent years?
- How does rig count relate to production output?
- What do DUC (Drilled but Uncompleted) well inventories tell us about the pace of drilling vs. completions?
- Are completion activity levels changing over time?

## Methodology

1. **Data Collection** — Downloaded drilling productivity data from the EIA's public database covering rig counts, production volumes, DUC inventories, and completion activity by region.
2. **Data Cleaning & Preparation** — Organized and structured the data in Excel, handling date formatting and aligning regional breakdowns for comparison.
3. **Trend Analysis** — Built time-series views to track rig count, production, DUC inventory, and pad completions over the analysis period.
4. **Regional Comparison** — Isolated Permian Basin data to examine whether national-level trends held at the basin level.

## Key Findings

- **Rigs are getting more efficient.** Between 2023 and 2025, the active rig count has been dropping consistently, yet crude oil production continues to rise — particularly in the Permian Basin. Operators are doing more with less.
- **DUC inventory is steadily declining.** Across U.S. land, wells are being completed faster than new wells are being drilled, drawing down the backlog of drilled but uncompleted wells.
- **Pad completions per month have slowed.** Completion activity has decreased over the analysis period, reinforcing the trend that operators are prioritizing efficiency and capital discipline over volume.

## Tools

| Tool | Use |
|------|-----|
| Microsoft Excel | Data cleaning, analysis, and visualization |
| EIA Public Database | Primary data source |

## What I Learned

This project reinforced the value of letting the data tell the story. The disconnect between falling rig counts and rising production is counterintuitive at first glance, but the supporting metrics (DUC drawdown, slowing completions) paint a clear picture of an industry shifting toward efficiency. It was also a good exercise in working entirely within Excel for a full EDA workflow — from raw data to insight.

---

*This project was completed independently using only publicly available data from the EIA.*
