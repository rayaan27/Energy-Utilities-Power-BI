# ⚡ Global Energy & Utilities Intelligence Dashboard
### Power BI Analytics Project

---

## 📌 Overview

This project presents a multi-page interactive Power BI dashboard analyzing global energy production, renewable energy adoption, carbon intensity trends, and electricity generation efficiency across **130+ countries** spanning **2000–2022**.

The central research question driving this project is:

> **"Is the Global Energy Transition Real? Analyzing the Shift from Fossil Fuels to Renewables Across Nations"**

---

## 👥 Team

Collaborative group project — 3 members, each responsible for distinct dashboard pages, integrated into a single cohesive report.

---

## 📂 Dataset

| Detail | Info |
|---|---|
| **Source** | [Our World in Data — Energy Dataset](https://github.com/owid/energy-data) |
| **File** | `owid-energy-data.csv` |
| **Size** | 130+ countries · 120+ years · 129 variables |
| **Key Columns Used** | `carbon_intensity_elec`, `renewable_share_elec`, `solar_electricity`, `wind_electricity`, `coal_electricity`, `gdp`, `population`, `year`, `country` |

---

## 📊 Dashboard Pages

### Page 1 — Overview
High-level summary of global energy landscape with key KPI cards and intro visuals.

### Page 2 — Energy Mix
Compares energy sources (coal, gas, oil, solar, wind) across top countries using stacked bar charts and pie charts.

> **Insight:** Fossil fuels dominate globally but renewables are a growing presence in developed nations.

### Page 3 — Renewable Growth
Tracks how solar and wind consumption have grown over time using line charts.

> **Insight:** Solar and wind are growing rapidly, especially post-2015 following the Paris Agreement.

### Page 4 — Environmental Impact *(Carbon Intensity)*
Analyzes electricity cleanliness across nations using bar charts and area charts.

> **Insight:** Turkmenistan leads with a carbon intensity of 817 gCO₂/kWh. Global average has declined consistently from ~450 in 2000 to ~300 by 2022 — proving electricity is getting cleaner.

### Page 5 — Global Renewable Landscape
Maps renewable energy share leaders using a treemap visual across 15 top-performing countries.

> **Insight:** Countries with highest renewable % are concentrated in Europe and South America. Norway leads at 67%, Iceland at 66%, Sweden at 41%. Global average is just 8% — the transition is real but far from complete.

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| **Power BI Desktop** | Dashboard design, visuals, interactions |
| **DAX** | Calculated measures, aggregations, Top N filters |
| **CSV / Excel** | Raw dataset handling |
| **Our World in Data** | Primary data source |
| **GitHub** | Version control and project sharing |

---

## 📈 Visuals Used

- KPI Cards
- Bar Chart (Top N filtered)
- Area Chart
- Line Chart
- Treemap
- Slicers (Year range, Country, Region)
- Text Box Insight Annotations

---

## 🔍 Key Insights

1. **Carbon intensity is declining** — global average dropped from ~450 to ~300 gCO₂/kWh between 2000–2022
2. **Renewable share is only 8% globally** — despite significant growth, fossil fuels still dominate
3. **Europe & South America lead renewables** — Norway (67%), Iceland (66%), Brazil (37%)
4. **Fossil fuel dependency is regional** — Central Asia and Eastern Europe have the dirtiest electricity grids
5. **The energy transition is real but unequal** — wealthy nations decarbonize while developing nations still scale up fossil infrastructure

---

## 🎨 Design Choices

- **Orange/Red theme** on carbon intensity pages — reflects environmental danger
- **Green/Colorful theme** on renewable pages — reflects clean energy positivity
- **Edit Interactions** used to lock bar charts from slicer influence for fixed comparisons
- **Top N filters** applied to focus on most meaningful countries

---

## 📁 Repository Structure

```
├── Proj.pbix                  # Main Power BI dashboard file
├── owid-energy-data.csv       # Source dataset
├── README.md                  # Project documentation
└── screenshots/               # Dashboard page previews
```

---

## 🚀 How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop) (free)
2. Clone or download this repository
3. Open `Proj.pbix` in Power BI Desktop
4. Interact with slicers and visuals freely

---

## 📜 License

Dataset sourced from Our World in Data under [Creative Commons BY 4.0](https://creativecommons.org/licenses/by/4.0/).
