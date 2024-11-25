# The Impact of Human Development Index (HDI) on Maternal Mortality Rates

## Brief Overview
This project investigates the relationship between the Human Development Index (HDI) and maternal mortality rates worldwide. Using a comprehensive dataset spanning decades, the analysis uncovers trends, visualizations, and insights that can inform policy-making and healthcare interventions.

### Dataset Information
Data source is from Kaggle https://www.kaggle.com/datasets/iamsouravbanerjee/maternal-mortality-dataset/data

The dataset includes maternal mortality rates from 1990 to 2021 across various countries. 
Key columns include:

`HDI Rank`: Rank based on the Human Development Index.

`MMR`: Maternal Mortality Ratio (deaths per 100,000 live births).

`Human Development Groups`: Classification of countries into 'Low', 'Medium', 'High', or 'Very High' HDI.

### Analysis
1. Data Cleaning:
   - Removed missing values using Pandas. 11 countries were removed due to NaN MMR values for all years.
   -  split 'Year' and 'MMR' into separate columns, and created an 'HDI Average' column.
3. Data Analysis: Explored correlations and performed an ANOVA test.
4. Visualizations: Created line charts, bar charts, and boxplots to highlight key trends.

### Visualizations 


```python
print(head(5))```
-data source
- tools used
- data cleaning/prep
- eda questions you asked
- data analysis
''' pytho
summary of findings

-recommendations
-limitations
upload files
save screenshot n upload


