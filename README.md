# Lake Urmia Environmental Monitoring and Climate Analysis (2016–2025)

## Overview

This project investigates Lake Urmia surface water dynamics and its relationship with climate variability during 2016–2025 using Python-based environmental data analysis.

The workflow integrates satellite-derived surface water observations with climate variables to evaluate temporal changes, environmental drivers, and future surface water trends.

---

## Objectives

The main objectives of this project are:

- Monitoring Lake Urmia surface water changes during 2016–2025
- Evaluating relationships between water area and climate variables
- Quantifying long-term surface water trends
- Developing a baseline regression model
- Forecasting future surface water area (2026–2030)

---

## Study Area

Lake Urmia is one of the largest hypersaline lakes in the Middle East and has experienced significant environmental changes during recent decades.

This project focuses on annual surface water variations during 2016–2025 and investigates the influence of climatic factors on lake surface dynamics.

---

## Dataset

The dataset contains annual environmental variables:

| Variable | Description |
|---|---|
| Year | Study year (2016–2025) |
| Water_Area_km² | Satellite-derived surface water area |
| Rainfall_mm | Annual precipitation |
| Temperature_C | Mean annual temperature |
| SPEI_Summer | Summer Standardized Precipitation Evapotranspiration Index |

Study period:

**2016–2025**

---

## Workflow

The analysis workflow includes:

1. Data loading and quality inspection
2. Statistical summary analysis
3. Surface water temporal trend analysis
4. Climate variable visualization
5. Correlation analysis
6. Surface water trend estimation using Linear Regression
7. Model evaluation using statistical metrics
8. Future surface water forecasting (2026–2030)

---

## Tools and Technologies

The project was developed using:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Results

## Surface Water Trend Analysis

Lake Urmia surface water area showed an overall declining trend during the study period.

The estimated annual surface water change rate was:

```
-48.72 km²/year
```

---

## Climate–Water Relationship

Correlation analysis indicated:

- Positive relationship between rainfall and surface water area
- Negative relationship between temperature and surface water area
- Climate variables influence lake surface water variability

---

## Regression Model Performance

A baseline Linear Regression model was developed to estimate surface water area.

Model performance:

| Metric | Value |
|---|---:|
| R² | 0.44 |
| RMSE | 157.36 km² |
| MAE | 141.61 km² |

The model explains approximately 44% of the observed variability in surface water area.

---

## Future Surface Water Forecast (2026–2030)

The baseline model estimated future surface water area:

| Year | Forecasted Water Area (km²) |
|---|---:|
| 2026 | 3100.90 |
| 2027 | 3052.17 |
| 2028 | 3003.45 |
| 2029 | 2954.72 |
| 2030 | 2906.00 |

These predictions represent a baseline estimation due to the limited number of annual observations.

---

## Project Structure

```
Lake_Urmia_Project1/

├── Data/
│   └── Lake_Urmia_Climate_Water_Dataset_2016_2025.xlsx
│
├── Figures/
│   ├── Surface Water Dynamics
│   ├── Climate Variables
│   ├── Correlation Heatmap
│   ├── Trend Analysis
│   └── Surface Water Forecast
│
├── Results/
│   ├── statistical_summary.csv
│   ├── correlation_matrix.csv
│   ├── Observed_vs_Predicted_Water_Area.csv
│   ├── Model_Performance_Metrics.csv
│   └── Future_Water_Area_Forecast_2026_2030.csv
│
└── Lake_Urmia_Climate_Water_Analysis.ipynb
```

---

## Limitations

Due to the limited number of annual observations (10 years), forecasting results should be considered as a baseline estimation rather than a final predictive model.

---

## Future Work

Future improvements include:

- Integration of longer satellite time series
- Sentinel-2 and Google Earth Engine workflow development
- Monthly and seasonal climate analysis
- Hydrological variables integration
- Advanced machine learning and deep learning approaches

---

## Conclusion

This project demonstrates an integrated workflow for monitoring Lake Urmia surface water changes and evaluating climate impacts using remote sensing-derived observations, environmental data analysis, and Python-based modeling techniques.

The project provides a foundation for future research using advanced remote sensing, machine learning, and environmental prediction methods.

---

## Author

Environmental Science & Remote Sensing Research Portfolio Project