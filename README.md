# Predicting Median Income in Los Angeles County 

## Overview
This project explores the socioeconomic factors influencing median household income across various communities in Los Angeles County. By leveraging demographic data and applying predictive modeling, we aim to provide insights that can guide policies addressing income inequality.

## Objectives
1. **Understand income inequality:** Analyze factors contributing to median household income disparities.
2. **Predictive modeling:** Develop and compare models (Lasso and Ridge regression) to identify significant predictors of income.
3. **Geographic trends:** Highlight spatial patterns using k-Nearest Neighbors (kNN) clustering.

## Data Sources
The data used in this study were sourced from:
- The American Community Survey (2018–2022)
- Los Angeles Almanac (demographics, education, crime rates, etc.)

## Methods
- **Web Scraping:** Extracted data from online sources using Python and BeautifulSoup4.
- **Exploratory Data Analysis:** Evaluated linearity, multicollinearity, and correlation using tools like Spearman coefficients and Breusch-Pagan tests.
- **Modeling Techniques:**
  - **Lasso Regression:** Emphasized feature selection by shrinking less impactful coefficients to zero.
  - **Ridge Regression:** Stabilized coefficients in the presence of multicollinearity.
  - **k-Nearest Neighbors (kNN):** Clustered communities based on similarities to uncover spatial trends.

## Results
- **Significant Predictors:** Education level, household size, and the proportion of elderly residents were the strongest predictors of income.
- **Geographic Insights:** Perimeter communities in LA County exhibited higher median incomes compared to inland areas.
- **Model Performance:** Lasso regression outperformed Ridge regression in prediction accuracy, providing clearer insights into variable importance.

## Limitations
- The findings may not generalize beyond Los Angeles County due to regional-specific socioeconomic dynamics.
- Statistical challenges, such as heteroscedasticity and multicollinearity, may affect interpretation.

## Future Directions
- Expand the analysis to include additional counties or the entire state of California.
- Incorporate advanced machine learning techniques (e.g., Random Forest, Gradient Boosting Machines).
- Explore additional variables, such as race, housing prices, and health data, for a more comprehensive analysis.

## Repository Contents
- **`data/`**: Processed data and analysis-ready files.
- **`notebooks/`**: Jupyter notebooks for data preprocessing, EDA, and modeling.

