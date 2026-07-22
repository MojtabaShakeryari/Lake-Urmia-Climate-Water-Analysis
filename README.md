# Research Workflow

![Lake Urmia Environmental Monitoring Workflow](./Figures/Lake_Urmia_Workflow.png)

The workflow integrates satellite remote sensing, climate datasets, statistical trend analysis, and machine learning modeling to evaluate Lake Urmia environmental dynamics during 2016–2025.

The workflow consists of the following main stages:

## 1. Satellite Data Acquisition and Pre-processing

- Sentinel-2 MSI image acquisition using Google Earth Engine
- Cloud filtering and image preprocessing
- Seasonal image compositing
- Preparation of analysis-ready satellite data

---

## 2. Surface Water Extraction and Validation

- Water extraction using MNDWI and NDVI spectral indices
- Threshold optimization for water classification
- Annual surface water area calculation
- Accuracy assessment using independent datasets:
  - JRC Global Surface Water
  - Dynamic World

---

## 3. Surface Water Dynamics Analysis

- Annual water area estimation (2016–2025)
- Temporal change detection
- Assessment of water loss patterns

---

## 4. Climate Data Integration

Environmental drivers were analyzed using:

- CHIRPS precipitation
- ERA5-Land temperature
- MOD16 evapotranspiration
- SPEI drought indicators

---

## 5. Statistical Trend Analysis

Temporal trends and environmental relationships were evaluated using:

- Correlation analysis
- Mann–Kendall trend test
- Sen's slope estimator
- Climate–water relationship assessment

---

## 6. Machine Learning Modeling and Prediction

Predictive models were developed using Python:

- Linear Regression
- Random Forest Regression

Model performance was evaluated using:

- R²
- RMSE
- MAE

The models were used to investigate the relationship between environmental variables and lake water area variations and to generate future water condition scenarios.

---

## 7. Visualization and Reporting

Final outputs include:

- Time-series analysis
- Scientific figures and maps
- Statistical results
- Model evaluation outputs
- Environmental monitoring framework
