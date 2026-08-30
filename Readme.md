
# 22% Green, 34% Coal: Türkiye's Energy Transition vs. Europe

This repository contains the curated datasets, Python analytical pipelines, and visual assets supporting the data story** ** **"22% Green, 34% Coal: Where Does Türkiye Stand in Europe?"** .

It evaluates the structural decarbonization of European power systems, contrasting the continent's direct displacement of coal through wind expansion with Türkiye's dual reality of rapid renewable growth, persistent imported coal reliance, and an unprecedented 33 GW battery storage (BESS) pipeline.

- **Author:** Selçuk Çelik
- **Blog Post:** https://dataparadox.medium.com

## 📌 Research Overview & Key Findings

This study analyzes generation time series and cross-sectional grid metrics to evaluate how policy, market structures, and grid flexibility shape the pace of decarbonization:

* **Fossil Fuel Displacement Dynamics:** Quantifying the strong inverse relationship between expanding wind generation and coal output in Europe (**r**=**−**0.96), demonstrating systematic baseload displacement.
* **National Power Mix Heterogeneity:** Evaluating comparative renewable shares across European nations, isolating baseload hydro maturity (e.g., Norway, Austria) from variable wind and solar integration leaders (e.g., Denmark, Germany).
* **Regional Wind & Solar Penetration:** Spatial mapping of combined variable renewable generation shares across Europe and neighboring regions to reveal transition disparities.
* **Capacity Additions & Trajectory (Türkiye Case Study):** Assessing annual installed capacity additions (2015–2025), capturing the post-2021 surge in solar deployments relative to wind additions.
* **Longitudinal Grid Shifts (2000–2025):** Heatmap tracking of the historical generation mix, documenting shifts in fossil gas/coal baseloads alongside the rise of solar and wind shares.
* **Grid-Scale Battery Storage Archetypes (BESS):** Hierarchical clustering of European battery storage pipelines, identifying Türkiye's unique 33 GW pipeline as a significant scale outlier relative to EU markets.

---

## 📁 Repository Structure

```notion
├── data/
│   ├── raw/             # Raw source datasets
│   └── processed/       # Standardized CSV datasets (proc_01 to proc_06)
├── visuals/             # High-resolution dendrograms, maps, and cluster plots
├── workflows/           # Orange Data Mining workflows (.ows) and data pipelines
└── LICENSE
```

---

## 📚 Data Source & Attribution

Primary datasets are compiled and harmonized from the   **Ember Electricity Data Explorer** and official energy market reporting frameworks. Data curation, metric standardization, and statistical modeling were structured to ensure reproducible computational research.

- **Primary Data Provider:** Ember
- **Curation & Analytical Modeling:** Selçuk Çelik

* **Analytical Engine:** [Orange Data Mining](https://orangedatamining.com/) (Statistical workflows & hierarchical clustering)
* **Visualization Tooling:** [Flourish Studio](https://flourish.studio/) (Interactive charts & spatial mapping)

---

## 📜 License

This project is licensed under the MIT License.
