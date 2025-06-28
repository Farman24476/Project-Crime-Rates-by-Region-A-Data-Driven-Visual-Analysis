# Project-Crime-Rates-by-Region-A-Data-Driven-Visual-Analysis


This repository accompanies the paper **“Crime Rates by Region: A Data-Driven Visual Analysis.”**  
It contains the cleaned dataset, Jupyter notebooks, Python scripts, and figures that reproduce every result—bar plots, heatmaps, choropleth maps, radar charts, and K-Means clustering—for violent-crime patterns across the 50 U.S. states.

---

## 🗂 Project Structure

```text
.
├── data/
│   └── us_violent_crime_by_state_1973.csv
├── notebooks/
│   ├── 01_data_cleaning_and_eda.ipynb
│   ├── 02_visualisation.ipynb
│   └── 03_kmeans_clustering.ipynb
├── src/
│   ├── __init__.py
│   ├── prepare_data.py        # feature engineering helpers
│   ├── visualise.py           # reusable plotting utilities
│   └── clustering.py          # K-Means wrapper + silhouette score
├── figures/                   # auto-generated when notebooks run
│   ├── bar_total_crime.png
│   ├── heatmap_crime_types.png
│   └── ...
├── requirements.txt
└── README.md
