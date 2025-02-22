## Project Overview
This project explores the relationship between road traffic volume and economic indicators such as GDP, employment rates, and consumer spending. By analyzing traffic data across different regions and performing time series analysis, we aim to determine whether traffic volume can serve as a reliable indicator of economic activity and future trends.

## Project Goals
We aim to answer the following research questions:

- How does road traffic volume vary across different regions and cities, and what factors contribute to these variations?
- Is there a correlation between road traffic volume and economic indicators such as GDP, employment rates, and consumer spending?
- Are there significant events or change points in traffic volumes?

## Implementation Details
- ## 1. Data Collection & Preprocessing
  - Merged traffic volume datasets from multiple states.
  - Standardized the data to ensure consistency.
  - Cleaned missing values and transformed time-related variables for time series analysis.

- ## 2. Exploratory Data Analysis (EDA)
  - Analyzed correlations between traffic volume and economic indicators.
  - Identified key trends across regions.
  - Performed statistical tests and visualizations to support our hypotheses.

- ## 3. Time Series Analysis
  - Identified patterns and trends in traffic data over time.
  - Investigated change points and potential external influences (e.g., COVID-19).
  - Conducted regression analysis to determine relationships between traffic volume and economic factors.

## Findings & Insights
### Correlation Between Traffic Volume and Economic Indicators:
  - Traffic volume showed weak to moderate correlations with market hotness (-0.32), unemployment rate (-0.22), and annual population (0.11).
  - Linear regression models showed that unemployment rate and market hotness had statistically significant relationships with traffic volume, though the explanatory power varied.

## Key Trends in Time Series Analysis:
  - Traffic volume displayed seasonal and cyclical patterns.
  - There was a sharp decline in 2020, likely due to COVID-19, followed by a gradual recovery.
  - Changes in unemployment and traffic volume trends appeared to be linked in some regions.
