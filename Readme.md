# European & Regional Energy Transition: Decarbonization Dynamics and Grid Structural Shifts

This repository contains curated datasets, analytical workflows, and visual assets examining the structural transformation of European and regional power grids (2000–2025). The research models the empirical shift from fossil-fuel reliance toward variable renewable energy (VRE), tracking coal phase-out trajectories, national generation mix topologies, and capacity addition dynamics.

- **Author:** Selçuk Çelik
- **Blog Post:** https://dataparadox.medium.com

## 📌 Research Overview & Key Findings

This study analyzes long-term generation time series and cross-sectional grid metrics to evaluate how policy, market structures, and geographical endowments shape the pace of decarbonization:

- **Fossil Fuel Displacement Dynamics:** Quantifying the inverse relationship between expanding wind generation and coal output in Europe (r=−0.96), demonstrating systematic baseline displacement.
- **National Power Mix Heterogeneity:** Evaluating comparative renewable shares across European nations, isolating base-load hydro maturity (e.g., Norway, Austria) from variable wind and solar integration leaders (e.g., Denmark, Germany).
- **Regional Wind & Solar Penetration:** Spatial mapping of combined variable renewable generation shares (2025) across Europe, the Middle East, and Central Asia to reveal regional transition disparities.
- **Capacity Additions & Trajectory (Türkiye Case Study):** Assessing annual installed capacity additions (2015–2025), capturing the post-2021 surge in solar deployments relative to wind additions.
- **Longitudinal Grid Shifts (2000–2025):** Longitudinal heat-map tracking of the historical generation mix, documenting the decline of fossil gas/coal baseloads and the progressive rise of solar and wind shares.

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
