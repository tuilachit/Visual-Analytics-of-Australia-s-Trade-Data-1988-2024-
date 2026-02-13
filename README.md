# Visual Analytics of Australia's Trade Data (1988–2024)

I built this project to investigate Australia's international trade dynamics over three decades, with a focused lens on **mineral fuels**—particularly **Liquefied Natural Gas (LNG)**. Using Tableau for visualisation and Excel for data preparation, I employed statistical and analytical pattern modelling to uncover long-term shifts, major change points, and structural evolutions in Australia's export landscape.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## What I Did

I analysed trade data across ten main categories from 1988 to 2024 and chose to focus in-depth on **Category 3: Mineral Fuels** and its subcategories (coal, petroleum, gas). I prepared the data in three ways to support different analytical views:

| Approach | Purpose |
|----------|---------|
| **Raw Dollar** | Absolute value trends to understand scale and magnitude |
| **Statistical Pattern** | Ratio analysis — % share of each category vs total for proportional comparison |
| **Analytical Pattern** | Year-over-year change to surface volatility, growth surges, and shock points |

**Data sources:** [ABS](https://www.abs.gov.au/statistics/economy/international-trade), [DFAT Trade Statistics](https://www.dfat.gov.au/trade/trade-and-investment-data-information-and-publications/trade-statistics)

---

## Tools & Deliverables

I used **Excel** for data transformation (statistical and analytical patterns) and **Tableau** for visualisation. I created:

- **3 dashboards** — Australia's Trade Landscape; Mineral Fuels deep-dive; Gas vs Coal comparison
- **1 storyboard** — 4-point narrative guiding the viewer from macro trends to the gas subcategory
- **Product focus report** — 10-year trend (2015–2024), gain/loss summary, and 5-year forecast (2025–2029)

---

## My Approach

**Data preparation (Excel):**
- **Statistical pattern:** `Percentage = sub-total / total` — I normalised values so I could compare categories and subcategories across years despite different magnitudes.
- **Analytical pattern:** `Ratio_Change(t) = d(t) / d(t-1)` — I calculated year-over-year change to detect volatility and turning points.

**Tableau:** I connected the three prepared sheets using relationships (Time, Trade fields) so I could layer raw, proportional, and change views without duplicating data. This let me build dashboards that combined trends with scale and dynamics.

---

## Key Findings

- **Coal → Gas transition:** Coal dominated mineral fuel exports in early years (>60% share) but declined below 30% by 2024. Gas surged from &lt;5% to ~30%, overtaking coal as the key growth driver—the most significant structural shift I observed.
- **Turning points:** I identified clear correlations with major disruptions—2008 (GFC), 2020 (COVID-19), 2022 (Ukraine energy crisis). These events drove volatility and sharp spikes in gas demand, reinforcing Australia's role as a critical LNG supplier.
- **Export reorientation:** Australia's export profile shifted from diversified to resource-centric. Mineral fuels grew from &lt;10% to &gt;25% of total exports, while machinery and manufactured goods declined in share.
- **Gas outlook:** I projected gas to maintain strong performance in the $85–95K range through 2029, supported by Asian demand, with strategic emphasis on infrastructure modernisation, sustainability, and diversification.

---

## Project Structure

```
├── data/              # Raw and processed datasets (Excel)
│   └── raw/           # Raw trade data
├── tableau/           # Tableau workbooks (.twbx / .twb)
├── output/            # Exported charts and assets
├── docs/              # Report, screenshots
│   └── screenshots/   # Dashboard snapshots
└── README.md
```

---

## Screenshots

*Dashboard and storyboard screenshots go in `docs/screenshots/`.*

---

## License

MIT License — see [LICENSE](LICENSE).

---

**Author:** [@tuilachit](https://github.com/tuilachit) · [LinkedIn](https://linkedin.com/in/your-profile)
