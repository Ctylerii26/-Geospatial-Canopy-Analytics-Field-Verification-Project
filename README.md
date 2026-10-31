# Geospatial Canopy Analytics & Field Verification Project

## 🌲 Project Overview
This repository bridges the gap between field-collected ecological data and cloud-based satellite data pipelines. Using **Python** and open-source **GIS software**, this workflow extracts, cleans, and models vegetation health indices across local forest canopy zones in Northwest Arkansas to create a reproducible framework for wildfire risk and habitat degradation modeling.

## 🛠️ The Tech Stack
*   **Languages:** Python (Core Pipeline)
*   **Geospatial Libraries:** `rasterio`, `geopandas`, `earthpy`, `numpy`
*   **Visualization:** `matplotlib`, `seaborn`
*   **Software & Hardware:** QGIS, Avenza Maps mobile logging

## 🚀 Data Pipeline Architecture
1. **Ground-Truthing Fieldwork:** Logged spatial coordinate vector layers (.KML) across varying canopy conditions using mobile GIS field protocols.
2. **Satellite Ingestion:** Automatically extracted multi-spectral Landsat 8 satellite imagery bands via Python.
3. **Matrix Calculations:** Processed raw bands to compute the **Normalized Difference Vegetation Index (NDVI)** to quantify live green vegetation.
4. **Statistical Validation:** Extracted exact raster pixel values underneath field GPS markers and plotted distributions to validate satellite accuracy against field observations.

## 📊 Results & Key Figures

| Zone | Observed Condition | Average NDVI | Risk Assessment |
| :--- | :--- | :--- | :--- |
| **Zone A** | Dense, Healthy Canopy | `0.72` | Low Risk |
| **Zone B** | Cleared/Dead Brush | `0.21` | High Fuel Load / Wildfire Hazard |

***

*Developed by Charles Tyler II as part of the M.S. Environmental Data Analytics curriculum at Unity Environmental University.*
