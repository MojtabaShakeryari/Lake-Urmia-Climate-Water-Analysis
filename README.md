# Lake Urmia Environmental Monitoring (2016–2025)

## Overview

## Overview

Lake Urmia is one of the most important saline lakes in the Middle East and has experienced significant environmental changes during recent decades.

This repository presents a data-driven framework for monitoring and analyzing Lake Urmia environmental dynamics from 2016 to 2025 by integrating satellite remote sensing, climate datasets, statistical analysis, and machine learning approaches.

The workflow combines Google Earth Engine (GEE) and Python-based analysis to investigate surface water changes, climate–water interactions, drought impacts, and future environmental trends.

The main components of this research include:

- Satellite-based surface water extraction using Sentinel-2 imagery
- Climate data analysis using precipitation, temperature, and evapotranspiration datasets
- Drought assessment using SPEI indicators
- Statistical trend and correlation analysis
- Machine learning modeling for environmental prediction

The objective is to develop a reproducible and transferable workflow for long-term wetland monitoring and climate impact assessment.
---

## Objectives

The main objectives of this project are:

- Monitor annual surface water dynamics
- Analyze long-term environmental changes
- Investigate climate–water relationships
- Evaluate drought conditions using SPEI
- Develop predictive models for future lake conditions
- Build a reproducible workflow for environmental monitoring

---

## Study Area

Lake Urmia is one of the largest hypersaline lakes in the Middle East and has experienced dramatic shrinkage during recent decades due to climate variability and human activities.

---

## Data Sources

### Satellite Data

- Sentinel-2 Surface Reflectance
- Dynamic World
- JRC Global Surface Water

### Climate Data

- CHIRPS Precipitation
- ERA5-Land Temperature
- MOD16 Evapotranspiration

---

## Methodology

### Google Earth Engine

- Image preprocessing
- Cloud masking
- Water extraction using MNDWI
- NDVI masking
- Threshold optimization
- Annual water area calculation
- Change detection
- Validation using Dynamic World and JRC

### Python Analysis

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Correlation analysis
- Linear Regression
- Random Forest Regression
- Model evaluation
- Future prediction

---

## Repository Structure

```
Lake_Urmia_Project/
│
├── Code/
│   ├── GEE/
│   └── Python/
│
├── Data/
│
├── Figures/
│
├── Results/
│
└── README.md
```

---

## Main Results

The project successfully generated:

- Annual lake surface area (2016–2025)
- Climate indicators
- Correlation analysis
- Machine Learning models
- Future predictions
- Publication-quality figures

---

## Tools

- Google Earth Engine
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Future Improvements

Planned future developments include:

- Mann–Kendall Trend Analysis
- Sen's Slope Estimator
- Time-series forecasting
- XGBoost modeling
- SHAP feature importance
- Interactive visualization dashboard

---

## Author

**Mojtaba Shakeryari**

M.Sc. Environmental Science

Research Interests:

- Remote Sensing
- GIS
- Machine Learning
- Climate Change
- Wetland Monitoring

---

## License

This repository is intended for academic and research purposes.
