# EV-Recommendation-Analysis-Python
Python project for Electric Vehicle (EV) Recommendation System &amp; Analysis — includes data exploration, filtering, outlier detection, correlation analysis, class-based recommender, and statistical testing.
This Python project builds an **EV Recommendation System** and performs various exploratory and statistical analyses on an EV dataset.  
The goal is to help users select suitable EVs based on their preferences and provide insights into EV trends.

## Project Workflow

1. **Data Exploration**
    - Load `fev_data.csv`
    - View columns and basic stats

2. **Filtering & Grouping**
    - EVs within budget and range criteria
    - Grouped by manufacturer
    - Calculate average battery capacity

3. **Outlier Detection**
    - Identify outliers in energy consumption using IQR

4. **Correlation Analysis**
    - Battery capacity vs. range
    - Pearson correlation coefficient

5. **EV Recommendation Class**
    - Class `EV_data` built to recommend top 3 EVs based on:
      - Budget
      - Minimum range
      - Minimum battery capacity

6. **Hypothesis Testing**
    - Compare average engine power between Tesla and Audi
    - Two-sample t-test
    - Actionable insights & recommendations

## Library Used

- Python 
- pandas, numpy
- matplotlib
- scipy
- Jupyter Notebook

## Insights

- Strong correlation (r = 0.81) between battery capacity and range.
- No significant difference in average engine power between Tesla and Audi (p > 0.05).
- Buyers should focus more on range, battery capacity, and other features.
