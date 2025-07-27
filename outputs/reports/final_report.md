# Uber Fare Data Analysis: Final Report

**Author:** 24613 Ngwije Ngabo Gerard  
**Date:** July 2025

---

## 1. Introduction

This report presents a comprehensive analysis of the Uber Fares Dataset, focusing on data cleaning, exploratory data analysis (EDA), feature engineering, and key insights. The goal is to uncover fare patterns, operational metrics, and actionable business recommendations.

---

## 2. Data Overview

- **Source:** Uber Fares Dataset (`data/raw/uber.csv`)
- **Initial Records:** [Refer to notebook for exact count]
- **Key Variables:**
  - `fare_amount`, `pickup_datetime`, `pickup_longitude`, `pickup_latitude`, `dropoff_longitude`, `dropoff_latitude`, `passenger_count`

---

## 3. Data Cleaning Summary

- Removed records with invalid coordinates (0.0, 0.0)
- Filtered out unrealistic fare amounts (<$1 or >$200)
- Dropped rows with missing values
- Kept only valid passenger counts (1-6)
- Standardized datetime format
- Removed duplicates
- **Final Cleaned Records:** [Refer to notebook for exact count]

**Before/After Comparison:**
- Significant reduction in outliers and invalid data
- Improved reliability for downstream analysis

---

## 4. Exploratory Data Analysis (EDA)

### 4.1 Descriptive Statistics
- Fare amount: [mean, median, std, min, max — see notebook]
- Passenger count: [distribution — see notebook]

### 4.2 Fare Distribution
- Box plot and violin plot reveal right-skewed distribution with some outliers.

### 4.3 Fare vs. Distance
- Positive correlation between fare and trip distance (scatter plot).

### 4.4 Fare vs. Time of Day
- Higher fares observed during peak hours (morning and evening).

### 4.5 Correlation Analysis
- Heatmap shows strong correlation between fare and distance; weak correlation with passenger count.

---

## 5. Feature Engineering

- Extracted time-based features: hour, day of week, month, year, is_weekend, time_period, is_peak_hour
- Added season, holiday, and day_type indicators
- Clustered pickup/dropoff locations into zones
- Added airport trip and manhattan distance features
- Created fare_per_km and fare category (Low/Medium/High)
- One-hot encoded categorical variables
- **Enhanced dataset saved to:** `data/enhanced/uber_enhanced.csv`

---

## 6. Power BI Dashboard (Summary)

- Imported enhanced dataset into Power BI
- Created interactive dashboard with:
  - Fare distribution by time, distance, and location
  - Heatmaps, bar charts, and line plots
  - Filters for time period, passenger count, and zones
- **Screenshots and details in README.md**

---

## 7. Key Insights & Recommendations

- **Fare Patterns:** Most fares are under $30; outliers exist but are rare after cleaning.
- **Distance Impact:** Fare increases with distance, as expected.
- **Temporal Trends:** Peak hours and weekends/holidays see higher fares and demand.
- **Geographic Trends:** Certain zones (e.g., airport trips) have distinct fare patterns.
- **Business Recommendations:**
  - Optimize driver allocation during peak times and in high-demand zones
  - Consider dynamic pricing for airport and long-distance trips
  - Monitor outliers for potential fraud or data entry errors

---

## 8. Appendix

- See `notebooks/uber_fare_analysis.ipynb` for all code, plots, and step-by-step analysis.
- See `outputs/plots/` for all generated visualizations.
- See `README.md` for submission checklist and screenshot mapping.
