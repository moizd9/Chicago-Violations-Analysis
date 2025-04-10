# Chicago Building Violations Data Mining Project

## 📋 Project Overview
This project involves an exploratory data analysis and data mining exercise on the City of Chicago’s building violations dataset using **Python** on **Google Colab**. The analysis focuses on Ward 4 data, examining missing values, date handling, seasonal trends, fines, and violations, ultimately providing insights into violation patterns and administrative delays.

## 🧠 Key Objectives
- Perform descriptive and exploratory data analysis on Chicago building violations data.
- Analyze missing values, complete cases, and blank entries.
- Handle date fields and calculate delay metrics between violation and hearing dates.
- Segment and filter data by top case dispositions and violation types.
- Visualize administrative costs, fines, and violation patterns.
- Provide actionable insights on fines, seasonal violation patterns, and system delays.

## 🛠️ Tools Used
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** for data cleaning, manipulation, and visualization.
- **Google Colab** for interactive coding and analysis.

## 📈 Analysis Highlights
- **Dataset Overview:**  
  - 784,225 records and 22 columns initially.  
  - Focused analysis on **Ward 4** with 10,105 records.
  
- **Data Cleaning:**  
  - Identified and handled 278 missing values.  
  - Converted date fields to datetime format and created a new `CityDelay` variable.  
  - 97.33% of cases were complete (no missing values).
  
- **Seasonality Analysis:**  
  - Created a `Season` variable from violation dates.  
  - Highest violations occurred during **Winter**, lowest in **Fall**.

- **Violation and Fine Analysis:**  
  - Top 5 case dispositions identified (`Non-Suit`, `Liable`, `Not Liable`, `Default`, `Continuance`).  
  - Cases with "Default" disposition had the highest average fines.  
  - Most common street type was **AVE**, appearing 4,968 times.

- **Visualizations:**  
  - Bar charts and histograms for CityDelay, administrative costs, imposed fines, and seasonal trends.  
  - Heatmap and histograms highlighted violation patterns across different case types.

- **Violation Type Simplification:**  
  - Shortened the top 5 violation descriptions into categories like `Porch Repair`, `Elevator Compliance`, and `Exterior Wall Repair`.

- **Insights:**  
  - Structural safety violations like porch and wall repairs incurred the highest fines.  
  - Minor violations like inspection or documentation lapses had lower fines.  
  - Administrative delays peaked around 100 days, indicating typical processing times.
