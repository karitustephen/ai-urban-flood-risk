# AI-Powered Urban Flood Risk Mapping for Nairobi

## 🌊 Project Overview
This repository contains a reproducible GeoAI workflow for high-resolution flood susceptibility mapping and early impact assessment. By leveraging the **Google Earth Engine (GEE) Python API**, we fuse multi-sensor satellite data with machine learning to provide actionable risk intelligence for urban stakeholders.

## 🚀 Key Features
- **Multi-Sensor Fusion:** Sentinel-1 (SAR) for flood extents, Sentinel-2 for land cover, and CHIRPS for rainfall dynamics.
- **Terrain Analysis:** Hydrological modeling using SRTM/Copernicus DEMs.
- **Machine Learning:** Random Forest and Gradient Boosting models for susceptibility classification.
- **Impact Metrics:** Decision-ready indicators for administrative units (Wards/Sub-locations).

## 🛠️ Technical Stack
- **Engine:** Google Earth Engine (Python API)
- **Languages:** Python 3.9+
- **Libraries:** `geemap`, `geopandas`, `scikit-learn`, `xarray`
- **Deployment:** Google Colab / Jupyter Notebooks

## 📂 Workflow
1. **Preprocessing:** Cloud-masking, temporal aggregation, and SAR thresholding.
2. **Feature Engineering:** Slope, aspect, distance to rivers, and impervious surface density.
3. **Modeling:** Training supervised models on historical flood proxies.
4. **Validation:** Cross-temporal consistency and historical event correlation.

## 📋 Installation
```bash
pip install -r requirements.txt
earthengine authenticate
```

## 👤 Author
**Stephen Karitu Wambui**  
Geospatial Solutions Architect
