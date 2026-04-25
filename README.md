# AI-Powered Urban Flood Risk Mapping for Nairobi

This repository contains a **reproducible GeoAI workflow** for high-resolution **urban flood susceptibility mapping** and **early impact assessment** in Nairobi.

The project leverages the **Google Earth Engine (GEE) Python API**, multi-sensor satellite data, and machine learning to generate **actionable flood risk intelligence** for urban planners, emergency responders, and policy makers.

---

## 🌍 Project Objectives

- Map urban flood susceptibility at high spatial resolution  
- Fuse multi-source Earth observation data (optical, SAR, terrain, climate)  
- Apply machine learning for risk classification and prediction  
- Support early warning and urban resilience planning  

---

## 🛰️ Data Sources

- Sentinel-1 SAR (flood dynamics & surface water)
- Sentinel-2 Optical (land cover & impervious surfaces)
- SRTM / DEM (topography & slope)
- CHIRPS / ERA5 (precipitation & climate variables)
- OpenStreetMap (urban infrastructure)

All satellite data are accessed via **Google Earth Engine**.

---

## 🧠 Methodology

1. Data preprocessing & feature engineering in GEE  
2. Flood proxy extraction (water indices & SAR backscatter)  
3. Training dataset generation  
4. Machine learning modeling (Random Forest / Gradient Boosting)  
5. Flood susceptibility classification  
6. Spatial risk visualization & export  

---

## 🛠️ Tech Stack

- Python 3.x  
- Google Earth Engine (Python API)  
- NumPy, Pandas, GeoPandas  
- Scikit-learn  
- Matplotlib / Folium  

---

## 🚀 Getting Started

### Prerequisites
- Google Earth Engine account  
- Python 3.9+  
- GEE Python API installed  

```bash
pip install earthengine-api geemap scikit-learn geopandas
````

Authenticate GEE:

```bash
earthengine authenticate
```

---

## 📂 Repository Structure

```text
ai-urban-flood-risk/
│
├── data/               # Sample / exported datasets
├── notebooks/          # Jupyter notebooks
├── src/                # Core Python scripts
├── models/             # Trained ML models
├── outputs/            # Maps & results
├── requirements.txt
└── README.md
```

---

## 🎓 Capstone Context

This project is developed as part of the **2026 GEE Capstone Project**, focusing on **GeoAI for climate resilience and disaster risk reduction** in urban environments.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Stephen Karitu Wambui**
GeoAI & AI Systems Architect
