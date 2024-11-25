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


### Exploratory Data Analysis
1. Data Cleaning:
   - Removed missing values using Pandas. 11 countries were removed due to NaN MMR values for all years.
   -  split 'Year' and 'MMR' into separate columns, and created an 'HDI Average' column.
   -  Change the datatype of Human Development Groups to category in order of lowest rank to highest rank
3. Data Analysis: Explored correlations and performed an ANOVA test.
4. Visualizations: Created line charts, bar charts, and boxplots to highlight key trends.
5. Tools Used: Jupyter Notebook. Libraries such as; Pandas, Numpy, Matplotlib, Seaborn, Scipy.stats
6. Questions asked:
   - What Human Development Group has the highest Maternal Mortality Ratio?
   - What is the average Maternal Mortality Rate per HDI
   - 

### Visualizations 
![line graph ](https://github.com/user-attachments/assets/18428bbd-462c-47fe-b97b-e1b68812001c)

**Figure 1:** *Line graph showing the maternal mortality rates from 1990 to 2021 for each Human Development group.*

![Bar Chart](https://github.com/user-attachments/assets/ddeec64a-8934-4862-90f7-3f06bc0340b6)

**Figure 2:** *bar graph gives us a snapshot of the Maternal Mortality Rates per Human Development group in the year 2021.*

![Box Plot](https://github.com/user-attachments/assets/54aa824b-07b6-4d5f-b3e1-22eaa5414dd4)

**FIgure 3:** *Boxplot that shows the distribution of maternal mortality rates (MMR) for each HDI category in the year 2021.*

### Results









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


