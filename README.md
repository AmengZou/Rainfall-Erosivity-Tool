# Rainfall-Erosivity-Tool
## 🚀 Run this project in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AmengZou/Rainfall-Erosivity-Tool/blob/main/Rainfall_erosivity_tool_IMERG_V06.ipynb)

---

# Rainfall Erosivity Tool (IMERG V06)

This repository provides a workflow to calculate and analyze rainfall erosivity using IMERG precipitation data.

## 📌 Features

* Process IMERG precipitation data
* Calculate rainfall erosivity (R-factor)
* Generate spatial maps and figures
* Export results for GIS applications (e.g., ArcGIS Pro)

---

## ⚙️ How to Use

### Option 1 (Recommended): Run in Google Colab

1. Click the **"Open in Colab"** button above
2. Run all cells
3. Upload your input data when prompted
4. Download outputs

👉 No installation required

---

### Option 2: Run Locally

Requirements:

* Python 3.10+
* rasterio
* geopandas
* cartopy
* numpy
* pandas
* matplotlib

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 📂 Project Structure

```text
Rainfall-Erosivity-Tool/
│
├── Rainfall_erosivity_tool_IMERG_V06.ipynb   # Main notebook
├── README.md
├── requirements.txt
```

---

## 📊 Outputs

The tool can generate:

* Rainfall erosivity maps
* Error maps
* GeoTIFF files for GIS
* Figures for publication

---

## 📎 Notes

* Colab version is recommended to avoid dependency issues (GDAL, rasterio, cartopy)
* Local execution may require additional system configuration

---

## 📧 Contact

For questions or collaboration:

Ameng Zou
PhD Student, University of Arizona

---

## ⭐ Acknowledgement

If you find this tool useful, please consider citing or starring the repository.

