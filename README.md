# 🌍 Flood Risk & Ecosystem-Based Adaptation (EBA) – Python + GEE Workflow

This repository demonstrates an end-to-end workflow linking **Google Earth Engine (GEE)** and **Python** for flood-risk and ecosystem-based adaptation analysis in Lao PDR.

## 🧭 Workflow Overview

| Step | Description |
|------|--------------|
| 1–3 | Data preprocessing in GEE (DEM, LULC, NDVI/NDWI export) |
| 4–10 | Python workflow for reprojection, flood mask, EBA scenario, runoff, and cost–benefit analysis |

## ⚙️ Requirements

Install dependencies:

```bash
pip install -r requirements.txt
```

## 📂 Folder Structure

```
flood-eba-tutorial/
├── notebooks/
│   └── Flood_EBA_Runoff_LPB.ipynb
├── data/
├── outputs/
│   ├── rasters/
│   ├── maps/
│   └── tables/
├── README.md
├── requirements.txt
└── .gitignore
```

## 🚀 Run the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/flood-eba-tutorial.git
   cd flood-eba-tutorial
   ```
2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `Flood_EBA_Runoff_LPB.ipynb` and run all cells.

## 📊 Outputs
- `LPB_runoff_reduction_EBA.png` – Runoff reduction map  
- `LPB_BCR_bar.png` – Benefit–Cost Ratio chart  
- `LPB_EBA_CBA_admin_results.csv` – Summary of hydrological & economic results

## 🧠 Author
**Your Name**  
GIS & Climate Resilience Analyst – Vientiane, Lao PDR  
[BANDIT](https://bandit15.github.io/Portfolio/)
