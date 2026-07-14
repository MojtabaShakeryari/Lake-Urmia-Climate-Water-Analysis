# Lake Urmia Environmental Monitoring (2016–2025)

## Overview

This repository presents a comprehensive environmental monitoring and data analysis workflow for Lake Urmia (Iran) using Google Earth Engine (GEE), Python, and Machine Learning techniques.

The project integrates satellite remote sensing, climate data, statistical analysis, and predictive modeling to investigate long-term environmental changes affecting Lake Urmia between 2016 and 2025.

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
