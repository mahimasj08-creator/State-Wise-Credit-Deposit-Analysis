# State-Wise Credit-Deposit Pattern Analysis

## Overview
This project analyzes state-wise Credit-Deposit (CD) ratios across India using data from the Reserve Bank of India's *Handbook of Statistics on Indian States*, covering 2004–2025.

The project combines MongoDB-based data management with Python-based statistical analysis to investigate changes in credit deployment across states and regions over time.

## Objectives
- Analyze state-wise and region-wise credit-deposit ratio patterns.
- Clean and restructure RBI data for analysis.
- Examine long-term trends and year-over-year changes.
- Compare regional distributions using statistical hypothesis tests.
- Identify states with significant upward or downward trends.

## Tools and Technologies
- **Database:** MongoDB
- **Programming:** Python
- **Libraries:** pandas, NumPy, Matplotlib, Seaborn, SciPy
- **Analysis:** Exploratory Data Analysis, correlation, linear regression, hypothesis testing

## Key Analyses
- Descriptive statistics and missing-value analysis
- National and regional trend visualization
- State-wise comparisons and heatmaps
- Year-over-year and long-term change analysis
- Paired t-test and Wilcoxon signed-rank test
- Correlation and regression analysis
- Kruskal–Wallis and pairwise Mann–Whitney U tests

## Key Findings
- The Southern Region maintained the highest regional CD ratio over the study period.
- The North-Eastern Region generally recorded the lowest regional CD ratio.
- The national CD ratio showed a statistically significant upward trend in the report's regression analysis.
- Regional differences were statistically significant in the reported comparisons.

## Repository Structure
- `notebooks/` — Python analysis notebook
- `mongodb/` — MongoDB commands and scripts
- `data/` — Dataset documentation or shareable sample data
- `report/` — Project report
- `images/` — Selected charts and visualizations

## Data Source
Reserve Bank of India, *Handbook of Statistics on Indian States*, Table 154: State-wise Credit-Deposit Ratio of Scheduled Commercial Banks According to Place of Utilisation.

## Notes
This project was completed as an academic NoSQL project. Refer to the project report for the methodology, detailed statistical results, and limitations.
