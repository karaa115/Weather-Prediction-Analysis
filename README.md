# Weather Prediction Analysis

A machine learning project built in Python to analyze historical weather data and predict air temperature using regression models.


## Project Overview

This project explores weather measurements collected over multiple years and investigates how atmospheric variables influence air temperature.

The workflow includes:

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Correlation Analysis
- Linear Regression
- Random Forest Regression
- Model Evaluation
- Feature Importance Analysis

---

## Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Dataset

Historical weather observations containing:

- Temperature
- Apparent Temperature
- Humidity
- Wind Speed
- Wind Bearing
- Visibility
- Pressure
- Date and Time

---

## Machine Learning Models

### Linear Regression

Performance:

- MAE: **5.56°C**
- RMSE: **6.92°C**
- R² Score: **0.48**

---

### Random Forest Regression

Performance:

- MAE: **1.31°C**
- RMSE: **1.81°C**
- R² Score: **0.97**

Random Forest significantly outperformed Linear Regression and captured non-linear relationships between weather variables.

---

## Feature Importance

The Random Forest model identified the following variables as the most important:

1. Month
2. Humidity
3. Pressure
4. Day
5. Year

---

## Repository Structure

```
Weather-Forecasting/
│
├── data/
│   └── weatherHistory.csv
│
├── notebooks/
│   └── Weather_Analysis.ipynb
│
├── images/
│
└── README.md
```

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/karaa115/Weather-Prediction-Analysis.git
```

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Run:

```
jupyter notebook
```

Open:

```
notebooks/Weather_Analysis.ipynb
```

---

## Results

The project demonstrates a complete machine learning workflow:

- Data preprocessing
- Feature engineering
- Exploratory analysis
- Model training
- Model evaluation
- Feature importance interpretation

---
