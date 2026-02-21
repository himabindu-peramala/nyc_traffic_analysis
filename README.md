# NYC Motor Vehicle Collision Analysis

A data science project exploring motor vehicle collisions in New York City. This analysis identifies temporal patterns, geographic hotspots, and key risk factors using NYPD incident data.

## Project Overview
This project performs an in-depth exploratory data analysis (EDA) and statistical investigation into NYC's motor vehicle collisions. It utilizes Python for data cleaning, feature engineering, and visualization, supported by statistical models to validate safety insights.

## Key Features
- **Data Preprocessing**: Robust cleaning pipeline including geospatial validation and record de-duplication.
- **Feature Engineering**: Creation of indicators for peak traffic periods, weekend trends, and vehicle classifications.
- **Exploratory Data Analysis**:
  - Temporal risk heatmaps identifying peak incident windows.
  - Geospatial density mapping using hexagonal binning.
  - Analysis of injury distributions across road user categories.
- **Statistical Modeling**:
  - **Poisson Distribution**: Modeling daily incident arrival rates.
  - **ANOVA**: Testing geographic variance in incident severity.
  - **Chi-Squared**: Evaluating relationships between traffic periods and risk.

## Tech Stack
- **Language**: Python
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`
- **Tooling**: Jupyter Notebook

## Key Findings
- **High-Risk Periods**: Verified significant correlation between weekday afternoon rush hours and collision density.
- **Regional Disparity**: Confirmed statistically significant variance in injury profiles across the five boroughs.
- **Causal Factors**: Identified "Aggressive Driving" as a primary factor with a high conditional probability of injury.

## Setup Instructions
1. Clone the repository: `git clone <your-repo-url>`
2. Create and activate a virtual environment.
3. Install requirements: `pip install pandas matplotlib seaborn scipy`
4. Run the notebook: `jupyter notebook NYC_Collision_Analysis.ipynb`

## Data Source
Dataset provided by the [NYC Open Data Portal](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95).
