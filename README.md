# 🚲 Ford GoBike — Exploratory Data Analysis

Exploratory analysis of a bike-sharing dataset from the San Francisco Bay Area as part of the Udacity Digital Egypt Cubs Data Science program (Level 4). Comprehensive investigation of usage patterns, rider demographics, and trip characteristics.

## 🎯 Objective
Explore usage patterns across user types, trip durations, age groups, and days of the week to understand how people use bike-sharing services and identify key trends in rider behavior.

## 🛠️ Tools Used
- Python, pandas, numpy
- seaborn, matplotlib

## 📊 Key Findings
- **Trip Duration Patterns**: The majority of trips are short (~16 minutes or under 1,000 seconds), but outliers extending beyond 80,000 seconds suggest system errors or unique use cases requiring further investigation.
- **Age Demographics Dominate Usage**: Riders aged 20-39 dominate bike usage, with the 30-39 age group having the highest participation, while ridership drops sharply after age 60, indicating bike-sharing appeals primarily to younger adults.
- **User Type Behavior Diverges**: Subscribers take significantly shorter and more consistent trips (likely for commuting), while customers exhibit longer and more variable trip durations (likely for leisure), with subscribers vastly outnumbering customers across all age groups.

## 📁 Files
- `exploratory data analysis.ipynb` — Data cleaning, assessment, and univariate/bivariate/multivariate exploration
- `explanatory data analysis.ipynb` — Comprehensive analysis with visualizations and insights
- `201902-fordgobike-tripdata.csv` — Original raw dataset
- `fordgobike-tripdata-clean.csv` — Cleaned and processed dataset

## ▶️ How to Run
```bash
pip install pandas numpy seaborn matplotlib
jupyter notebook exploratory\ data\ analysis.ipynb
