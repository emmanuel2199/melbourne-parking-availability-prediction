# Predicting On-Street Parking Availability in Melbourne

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikit-learn)
![Geospatial](https://img.shields.io/badge/Geospatial-Analysis-green)

---

## Project Overview

This project applies predictive analytics to forecast on-street parking availability in Melbourne using real-time parking sensor data and parking restriction information from the City of Melbourne Open Data platform.

The goal is to identify patterns in parking availability and predict whether a parking bay is likely to be legally available at a given time.

---

## Problem Statement

Urban drivers often struggle to find legal parking spaces due to time-based restrictions and limited availability.

This project aims to:

- Predict parking availability
- Identify violation patterns
- Analyse temporal parking behaviour
- Provide insights for smarter urban mobility planning

---

## Data Sources

City of Melbourne Open Data Portal:

- On-Street Parking Bay Sensors dataset
- Parking Sign Plates dataset

These datasets include information about:

- Parking sensor status
- Parking zones
- Parking restrictions
- Time limits
- Geographic coordinates

---

## Methodology

### Data Integration
Parking sensor data was combined with parking restriction signage data.

### Data Cleaning
Missing values and inconsistent records were handled to ensure accurate modelling.

### Feature Engineering
Time-based features were created including:

- Hour of day
- Day of week
- Parking zone
- Restriction type

### Exploratory Data Analysis (EDA)

Analysis was performed to identify patterns such as:

- Violations by weekday
- Violations by hour
- Violations by zone
- Restriction type patterns

### Predictive Modelling

A **Random Forest Classifier** was trained to predict parking availability.

Model features included:

- Hour
- Weekday
- Parking zone
- Restriction type

### Model Evaluation

The predictive model achieved approximately:

**75% classification accuracy**

for predicting legal parking availability.

---

## Key Insights

- Parking violations occur most frequently during peak daytime hours.
- Some zones consistently show higher violation rates.
- Time-based restrictions significantly influence parking availability.

---

## Technologies Used

Python Libraries:

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Folium

Tools:

- Jupyter Notebook
- Git
- GitHub

---

## Repository Structure

```
melbourne-parking-availability-prediction
│
├── README.md
├── parking_prediction_report.pdf
│
└── notebooks
    └── parking_prediction_model.ipynb
```

---

## Author

**Emmanuel Clement Anthony**  
Master of Data Science  
Melbourne, Australia

GitHub: https://github.com/emmanuel2199
