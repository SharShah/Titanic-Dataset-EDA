# Titanic Dataset Analysis

## Project Overview
This project explores the Titanic dataset to analyze survival patterns based on demographic and ticket-related factors. The analysis involves exploratory data analysis (EDA), data preprocessing, and visualization to uncover insights into survival rates

## Objectives
- Investigate survival rates across different passenger classes
- Examine the relationship between age and survival
- Analyze gender disparities in survival rates
- Explore how ticket fare and embarkation points influenced survival

## Dataset
- **Source:** [HackerNoon: 15 Excel Datasets for Data Analytics Beginners](https://hackernoon.com/15-excel-datasets-for-data-analytics-beginners)
- The dataset contains information on **891 passengers**, including their age, gender, ticket class, fare, and survival status

## Technologies Used
- **Python**
- **Libraries:** pandas, NumPy, matplotlib, seaborn

## Exploratory Data Analysis (EDA)
- **Data Preprocessing:**
  - Checked for missing values and handled them (filled missing `Age` values with the mean, removed rows with missing `Embarked` values)
  - Identified and removed outliers using the **Interquartile Range (IQR)** method
  - Encoded categorical variables (e.g., `Sex` converted to numerical representation)

- **Data Visualization:**
  - Heatmaps to show correlations between variables
  - Histograms to analyze survival distributions based on age
  - Boxplots to detect and visualize outliers
  - Scatter plots to analyze the relationship between age, fare, and survival
  - Bar plots to explore survival rates across passenger classes and embarkation points
  - Pie charts to analyze gender-based survival distribution

## Key Findings
- **Passenger Class:** First-class passengers had the highest survival rate (~62.6%), while third-class passengers had the lowest (~24.2%)
- **Age Distribution:** Children (0-10 years) had the highest survival rate (~61.3%), while older passengers (70-80 years) had the lowest (0%)
- **Gender Disparity:** Women had a much higher survival rate (~74.2%) compared to men (~18.9%)
- **Ticket Fare:** Higher ticket fares generally corresponded to higher survival rates, indicating socioeconomic bias

## Future Work
- Apply machine learning models to predict survival probabilities
- Extend the analysis to other disaster datasets (aviation, natural disasters)
- Use similar survival analysis techniques for medical research (e.g., cancer survival rates)

## References

1. [Matplotlib Documentation](https://matplotlib.org/stable/plot_types/index)
2. [Seaborn](https://seaborn.pydata.org/api.html)
3. [Pandas](https://pandas.pydata.org/docs/user_guide/index.html)
4. [NumPy Documentation](https://numpy.org/doc/2.2/user/index.html)  

