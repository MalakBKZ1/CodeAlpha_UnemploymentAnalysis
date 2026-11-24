# 📊 Unemployment Analysis with Python — CodeAlpha Internship (Task 2)

Analysis of unemployment in India (May 2019 – June 2020), including data cleaning, exploratory analysis, visualization, and assessment of the **impact of COVID-19**.

![Dashboard](figures/final/07_dashboard_synthese.png)

## 🎯 Objectives
- Clean and explore unemployment data.
- Visualize trends over time and across regions.
- Measure the impact of COVID-19.
- Investigate seasonal patterns.
- Provide recommendations for economic and social policies.

## 📁 Dataset
- **Source:** Unemployment in India (Kaggle) / Link provided by CodeAlpha.
- **740 observations**, covering 28 regions with monthly data.
- **Features:** Region, date, unemployment rate, estimated employment, labor force participation rate, and area (urban/rural).

## 🛠️ Methodology
1. Data inspection and cleaning (missing values, duplicates, data types, column names).
2. Exploratory Data Analysis (regions, areas, and correlations).
3. Time series analysis and trend visualization.
4. COVID-19 impact analysis (pre-shock, shock, and recovery phases; paired Wilcoxon test).
5. Seasonality analysis.
6. Final visualizations.
7. Insights and recommendations.

## 🔑 Key Results
- Average unemployment increased from **9.6% to 24.3%** during the shock (2.5×), peaking at **24.9% in May 2020**.
- Most affected regions: **Puducherry, Jharkhand, and Tamil Nadu**.
- Urban areas were more affected than rural areas: **+16.0 vs. +13.3 percentage points**.
- Estimated employment fell from **399 million to 285 million** (−28.7%), while labor force participation dropped by **7 percentage points**.
- **Partial recovery** in June 2020, with employment reaching 369 million.

![Overall Trend](figures/final/01_tendance_globale.png)
![Most Affected Regions](figures/final/02_regions_les_plus_touchees.png)
![Regional Heatmap](figures/final/04_heatmap_region_mois.png)

## 💡 Recommendations
- Target assistance toward the most affected regions.
- Protect urban service-sector and informal workers.
- Support the reintegration of people who have left the labor force.
- Monitor employment and labor force participation, not just unemployment.

## ⚠️ Limitations
- Short time series (~14 months), limiting seasonal and long-term conclusions.
- Regional averages are not weighted by labor force population.
- The timing is consistent with lockdown measures but does not prove causality.

## ▶️ Run the Project
```bash
git clone https://github.com/[YOUR_USERNAME]/CodeAlpha_UnemploymentAnalysis.git
cd CodeAlpha_UnemploymentAnalysis
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```
Open `notebooks/unemployment_analysis.ipynb` to explore the analysis.

## 🗂️ Project Structure
```text
├── data/            # Raw and cleaned datasets
├── notebooks/       # Analysis notebook
├── figures/         # Exported visualizations
├── requirements.txt
└── README.md
```

## 👩‍💻 Author
**Malak**

*Data Science Internship Project — [CodeAlpha](https://www.codealpha.tech)*