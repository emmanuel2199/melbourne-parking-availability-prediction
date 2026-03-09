# Predicting On-Street Parking Availability in Melbourne

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikit-learn)
![Geospatial](https://img.shields.io/badge/Geospatial-Analysis-green)

---

## Project Overview

This project applies predictive analytics to forecast **on-street parking availability in Melbourne** using real-time parking sensor data and parking restriction information from the **City of Melbourne Open Data platform**.

Urban drivers often struggle to find legal parking spaces due to time-based restrictions and limited availability. This project explores patterns in parking usage and builds a machine learning model to predict whether a parking bay is likely to be available at a given time.

---

## Project Objectives

The objectives of this project are to:

- Analyse parking availability patterns across Melbourne
- Identify parking violations based on restriction rules
- Perform exploratory data analysis on parking sensor data
- Build a predictive model to forecast parking availability
- Provide insights that could support smarter urban mobility planning

---

## Data Sources

Data used in this project was obtained from the **City of Melbourne Open Data Portal**.

Datasets include:

- On-Street Parking Bay Sensors dataset
- Sign Plates Located in Each Parking Zone dataset

These datasets provide information about:

- Parking sensor status
- Parking zones
- Parking restrictions
- Time limits
- Geographic coordinates

---

## Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Folium

### Tools

- Jupyter Notebook
- Git
- GitHub

---

## Methodology

### Data Integration

Parking sensor data was combined with parking restriction signage data to determine whether parking was legally allowed at specific times.

### Data Cleaning

The datasets were cleaned and preprocessed to remove inconsistencies and missing values.

### Feature Engineering

Time-based features were created including:

- Hour of day
- Day of week
- Parking zone
- Restriction type

### Exploratory Data Analysis (EDA)

EDA was performed to analyse:

- Parking violations by weekday
- Violations by hour
- Violation patterns by parking zone
- Distribution of parking restriction types

### Predictive Modelling

A **Random Forest Classifier** was trained to predict whether parking would be legally available.

Model features included:

- Hour
- Weekday
- Parking zone
- Restriction type

### Model Evaluation

The model achieved approximately:

**75% accuracy** in predicting legal parking availability.

---

## Key Insights

- Parking violations are most common during peak daytime hours.
- Some parking zones consistently show higher violation rates.
- Time-based parking restrictions strongly influence parking availability.

---

## Project Report

The full analysis including visualisations and results can be viewed here:

📄 **[View Project Report](melbourne-parking-availability-prediction-report.pdf)**

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
