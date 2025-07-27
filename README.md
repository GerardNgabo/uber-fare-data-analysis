# Uber Fare Analysis Project

**Course:** Introduction to Big Data Analytics (INSY 8413)  
**Project:** Uber Fares Dataset Analysis using Power BI  
**Author:** 24613 Ngwije Ngabo Gerard
**Deadline:** July 27, 2025

## Project Overview

This project analyzes the Uber Fares Dataset to gain comprehensive insights into fare patterns, ride durations, and key operational metrics. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, and an interactive Power BI dashboard.


## Project Structure

```
├── README.md                           # Project documentation
├── notebooks/
│   └── uber_fare_analysis.ipynb       # Main analysis notebook
├── data/
│   ├── raw/                           # Original dataset
│   ├── cleaned/                       # Cleaned dataset
│   ├── enhanced/                      # Feature-engineered dataset
│   └── final/                         # Power BI ready dataset
└── powerbi/
    └── Uber-fare-analysis-powerbi.pbix   # Power BI dashboard
```

## Setup Instructions

### 1. Environment Setup

```bash
source uber-analysis-env/bin/activate

pip install -r requirements.txt

```

###
### 3. Analysis Workflow

1. **Data Acquisition:** Load and inspect the raw dataset
2. **Data Exploration:** Understand data structure and quality
3. **Data Cleaning:** Handle missing values and outliers
4. **Exploratory Analysis:** Generate insights and statistics
5. **Feature Engineering:** Create temporal and derived features
6. **Power BI Development:** Create interactive dashboard

## Key Features

- **Comprehensive EDA:** Statistical analysis and visualizations
- **Temporal Analysis:** Time-based patterns and trends
- **Feature Engineering:** Enhanced dataset with derived metrics
- **Interactive Dashboard:** Professional Power BI visualization
- **Documentation:** Complete process documentation

## Technology Stack

- **Python:** Data analysis and processing
- **Pandas:** Data manipulation
- **Matplotlib/Seaborn:** Static visualizations
- **Plotly:** Interactive visualizations
- **Jupyter Notebook:** Analysis environment
- **Power BI:** Dashboard creation


## Project Deliverables & Submission Requirements

1. **Power BI Dashboard File (.pbix)**
   - Interactive dashboard with all required visualizations
   - Professional formatting and user-friendly design

2. **GitHub Repository (Public Access Required)**
   - Cleaned datasets (CSV files)
   - README file explaining your project structure (this file)
   - **Screenshots documenting your analysis process:**
     - Data loading process
     - Data cleaning steps
     - DAX formulas (if used)
     - Dashboard development stages
     - **Chart screenshots:**
       - For each major chart/visual in Power BI, take a screenshot and save it in `outputs/plots/` or `outputs/reports/`.
       - Name files descriptively, e.g., `hourly_ride_count.png`, `fare_by_time_period.png`, `heatmap_busiest_periods.png`.
       - Reference these screenshots in your final report and optionally in this README under a new section (see below).

3. **Documentation Screenshots**
   - Include screenshots for all key steps and visuals as described above.

4. **Final Report**
   - Option A: Comprehensive GitHub report (Markdown format, e.g., `outputs/reports/final_report.md`)
   - Option B: PowerPoint presentation (if required)

---

## Where to Add Chart Screenshots

1. **outputs/plots/**
   - Save all chart and dashboard screenshots here.
   - Use clear, descriptive filenames for each chart.

2. **outputs/reports/**
   - Place your final report and any additional documentation here.
   - You may also include screenshots in the Markdown report using image links, e.g.:
     ```markdown
     ![Hourly Ride Count](../outputs/plots/hourly_ride_count.png)
     ```

3. **README.md**
   - Optionally, add a section below summarizing your key charts with embedded screenshots for quick reference.

---

## Usage

1. Open `notebooks/uber_fare_analysis.ipynb`
2. Run cells step by step from top to bottom
3. Follow the analysis workflow sections
4. Export final dataset for Power BI
5. Create dashboard in Power BI Desktop



## Results & Insights

Below are key results and where to find the corresponding screenshots for each step of the analysis:

- **Data Loading & Initial Exploration**
  
  ![Data Loading](outputs/plots/data_loading.png)

- **Initial Data Quality Assessment**
  
  ![Data Quality Check](outputs/plots/data_quality_check.png)

- **Data Cleaning Process**
  
  ![Data Cleaning](outputs/plots/data_cleaning.png)

- **Data Quality Report & Before/After Comparison**
  
  ![Before After Comparison](outputs/plots/before_after_comparison.png)

- **Descriptive Statistics**
  
  ![Descriptive Statistics](outputs/plots/descriptive_statistics.png)

- **Fare Distribution Visualizations**
  
  ![Fare Distribution Histogram](outputs/plots/fare_distribution_histogram.png)
  ![Fare Boxplot](outputs/plots/fare_boxplot.png)
  ![Fare Violinplot](outputs/plots/fare_violinplot.png)

- **Fare Amount vs. Distance Traveled**
  
  ![Fare vs Distance](outputs/plots/fare_vs_distance.png)

- **Fare Amount vs. Time of Day**
  
  ![Fare vs Hour](outputs/plots/fare_vs_hour.png)

- **Correlation Analysis**
  
  ![Correlation Heatmap](outputs/plots/correlation_heatmap.png)

- **Feature Engineering**
  
  ![Feature Engineering](outputs/plots/feature_engineering.png)

- **Power BI Dashboard**
  
  ![Power BI Dashboard](outputs/plots/powerbi_dashboard.png)

- **Peak Hours:** [Add summary and optionally embed screenshot]
- **Seasonal Patterns:** [Add summary and optionally embed screenshot]
- **Fare Distribution:** [Add summary and optionally embed screenshot]
- **Business Recommendations:** [Add summary]

## Contact

**Email:** [Your Email]  
**Instructor:** eric.maniraguha@auca.ac.rw

---
