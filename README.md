# Global rainfall erosivity calculating tool based on IMERG V06 and Machine Learning correction

This repository provides a workflow to calculate corrected rainfall erosivity derived from IMERG V06 precipitation data.

---

## Authors:

<ul style="line-height:1.5;">
<li>Ameng Zou <a href="mailto:amengzou@arizona.edu">(amengzou@arizona.edu)</a></li>
<li>Shang Gao <a href="mailto:shanggao@arizona.edu">(shanggao@arizona.edu)</a></li>
</ul>

---

## Affiliation:

School of Natural Resources and the Environment, University of Arizona, Tucson, AZ, USA

---

## Purpose:

This notebook provides workflow for calculating rainfall erosivity derived from IMERG precipittation data which makes it available to acquire rainfall erosivity value (R-factor) anywhere globally. For getting more accurate rainfall eorsivity, this notebook also applies a machine learning algorithm to reliably correct the rainfall erosivity value from IMERG V06 precipitation data which helps user to collect high-accuracy rainfall erosivity data. 

---

## Target Audience:

This tool is intended for researchers and practitioners who require high-resolution global rainfall erosivity data and have a working knowledge of Jupyter Notebooks, Python, and basic hydrologic data analysis.

---

## Description:

The notebook takes latitude and longitude coordinates as input and performs the following steps:
1. Extracts baseline rainfall erosivity derived from IMERG V06 precipitation (Emberson's dataset)  
2. Retrieves auxiliary predictors from Google Earth Engine (GEE) assets  
3. Applies a trained machine learning model to estimate the error between satellite-derived and reference (gauge-based) erosivity  
4. Generates bias-corrected rainfall erosivity estimates  
5. Exports results as a CSV file and provides visualization outputs  

---

## Data Description:

Original rainfall erosivity data is from Erosivity_IMERGV06B_30min_2001_2021.tif.

---

## Software Requirements:

Please refer to `requirements.txt` for configuring the Python environment and dependencies.

---

## Project Structure

```text
Rainfall-Erosivity-Tool/
├── Rainfall_erosivity_tool_IMERG_V06.ipynb   # Main notebook
├── README.md
├── requirements.txt
├── Erosivity_IMERGV06B_30min_2001_2021.tif
├── IMERGV06_Erosivity_Error_Prediction_Model.pkl
├── Inputs.csv
├── ...
```
---

## Acknowledgement

If you find this tool useful, please consider citing or starring the repository.

