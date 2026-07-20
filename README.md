# Lake Urmia Environmental Monitoring (2016–2025)

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Google Earth Engine](https://img.shields.io/badge/Google%20Earth%20Engine-Remote%20Sensing-green)
![Remote Sensing](https://img.shields.io/badge/Remote%20Sensing-Satellite%20Data-orange)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-red)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626)
![GIS](https://img.shields.io/badge/GIS-Environmental%20Analysis-yellow)

---

# Overview

Lake Urmia is one of the most important hypersaline lakes in the Middle East and has experienced significant environmental changes during recent decades.

This repository presents a data-driven framework for monitoring and analyzing Lake Urmia environmental dynamics during 2016–2025 by integrating satellite remote sensing, climate datasets, statistical analysis, and machine learning approaches.

The workflow combines Google Earth Engine (GEE) and Python-based analysis to investigate:

- Surface water dynamics
- Climate–water interactions
- Drought impacts
- Environmental trends
- Future water condition scenarios

The main components of this research include:

- Satellite-based surface water extraction using Sentinel-2 MSI imagery
- Climate analysis using precipitation, temperature, evapotranspiration, and drought indicators
- Statistical analysis of environmental relationships
- Machine learning modeling for water area prediction

The objective is to develop a reproducible and transferable framework for long-term wetland monitoring and climate impact assessment.

---

# Objectives

The main objectives of this project are:

- Monitor annual surface water dynamics of Lake Urmia
- Analyze environmental changes during 2016–2025
- Investigate climate impacts on lake surface variations
- Evaluate drought conditions using SPEI indicators
- Develop machine learning models for environmental prediction
- Create a reproducible remote sensing workflow for wetland monitoring

---

# Study Area

Lake Urmia is one of the largest hypersaline lakes in the Middle East and an important ecological system in Iran.

During recent decades, the lake has experienced substantial surface water reduction due to the combined effects of climate variability, drought conditions, and anthropogenic pressures.

The study area map was generated using Sentinel-2 MSI imagery and represents the geographical location and environmental characteristics of Lake Urmia.

![Study Area Map](./Figures/Lake_Urmia_Study_Area_Map.png)

---

# Data Sources

## Satellite Data

- Sentinel-2 Surface Reflectance
- Dynamic World Land Cover
- JRC Global Surface Water Dataset

## Climate Data

- CHIRPS Precipitation
- ERA5-Land Temperature
- MOD16 Evapotranspiration
- SPEI drought indicators

---

# Methodology

## Google Earth Engine Workflow

The Google Earth Engine platform was used for satellite-based processing:

- Sentinel-2 image acquisition
- Cloud masking and preprocessing
- MNDWI calculation
- NDVI-based masking
- Threshold optimization
- Annual surface water estimation
- Change detection analysis
- Validation using independent datasets

---

## Python-Based Analysis

Python was used for data analysis and modeling:

- Data preprocessing
- Climate data integration
- Exploratory Data Analysis (EDA)
- Correlation analysis
- Statistical evaluation
- Linear Regression modeling
- Random Forest Regression
- Model evaluation
- Future prediction

---

# Research Workflow

![Lake Urmia Environmental Monitoring Workflow](./Figures/Lake_Urmia_Workflow.png)

The complete workflow integrates satellite remote sensing, climate datasets, statistical analysis, and machine learning approaches to evaluate Lake Urmia environmental dynamics during 2016–2025.

The workflow consists of five main stages:

## 1. Satellite Data Processing

- Sentinel-2 MSI image acquisition using Google Earth Engine
- Cloud filtering and preprocessing
- Spectral index calculation (MNDWI and NDVI)
- Water extraction threshold optimization
- Annual surface water estimation

---

## 2. Surface Water Dynamics Analysis

- Annual water area estimation (2016–2025)
- Surface water change detection
- Water loss assessment
- Validation using independent datasets:
  - JRC Global Surface Water
  - Dynamic World

---

## 3. Climate Data Integration

Environmental drivers were analyzed using:

- CHIRPS precipitation
- ERA5-Land temperature
- MOD16 evapotranspiration
- SPEI drought indicators

---

## 4. Statistical Trend Analysis

The environmental variables were evaluated using:

- Correlation analysis
- Climate–water relationship assessment
- Mann–Kendall trend test
- Sen's slope estimation

---

## 5. Machine Learning Modeling and Prediction

Predictive models were developed using Python:

- Linear Regression
- Random Forest Regression

Model performance was evaluated using:

- R²
- RMSE
- MAE

The final outputs include environmental trend assessment, water area prediction, and future water condition scenarios.

# Repository Structure

| Folder | Description |
|--------|-------------|
| `Data` | Climate datasets, water area datasets, and processed tables |
| `Figures` | Scientific figures, maps, and visualization outputs |
| `Results` | Model performance metrics, prediction outputs, and statistical analysis results |
| `Notebook` | Jupyter notebooks for reproducible analysis |
| `README.md` | Project documentation |

---

# Code Availability

This repository provides workflow documentation, processed datasets, scientific figures, and analysis outputs.

The complete processing pipeline will be progressively released as the research framework is further developed.

---
