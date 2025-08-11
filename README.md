# yulu--shared-bike-data-analysis
yulu - data analysis and hypothesis testing
Yulu E-Cycle Demand Analysis
This project involves a comprehensive exploratory data analysis (EDA) of a shared electric cycle rental dataset, focusing on understanding the demand drivers in the Indian market. The dataset contains hourly rental data spanning multiple seasons, weather conditions, holidays, and working days.

Key Highlights
Data Overview: 10,886 rows and 12 columns including date/time, season, holiday indicator, weather, temperature, humidity, windspeed, casual & registered rentals, and total count.

Data Cleaning & Preparation:

Converted date/time to appropriate formats.

Removed irrelevant or redundant columns like ‘casual’ and ‘registered’ to focus on total rentals.

Handled outliers after understanding distribution with histograms and boxplots.

Transformed the target variable (count) using logarithmic scale to meet normality assumptions for certain tests.

Statistical Testing:

Conducted t-tests to compare bike rentals on holidays vs. regular days, finding no significant difference.

Applied ANOVA to assess variation in bike rentals across seasons, confirming significant differences.

Tested effects of weather conditions on rentals, using ANOVA and Levene’s test to check normality and homogeneity of variance assumptions.

Used Shapiro-Wilk test, QQ plots, and Levene’s test to validate distribution assumptions before tests.

Visualizations:

Created boxplots and distribution charts to visualize how rentals vary with factors like season, weather, holiday, and working day.

Used seaborn and matplotlib libraries for clear and insightful visual representation.

Findings:

Rentals vary significantly by season, with summer and monsoon showing higher demand.

Working days and holidays do not show significant differences in demand.

Weather conditions influence rentals, with clearer conditions having higher usage.

Dealt with non-normality and heteroscedasticity issues before drawing statistical conclusions.

Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn)

SciPy for statistical tests

Jupyter Notebook on Google Colab for interactive analysis
