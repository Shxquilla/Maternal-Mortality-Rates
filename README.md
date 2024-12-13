# The Impact of Human Development Index (HDI) on Maternal Mortality Rates

## Brief Overview
This project investigates the relationship between the Human Development Index (HDI) and maternal mortality rates worldwide. Using a comprehensive dataset spanning decades, the analysis uncovers trends, visualizations, and insights that can inform policy-making and healthcare interventions.

---

### Dataset Information
Data sourced from Kaggle https://www.kaggle.com/datasets/iamsouravbanerjee/maternal-mortality-dataset/data

The dataset includes maternal mortality rates from 1990 to 2021 across various countries. 
Key columns include:

`HDI Rank`: Rank based on the Human Development Index.

`MMR`: Maternal Mortality Ratio (deaths per 100,000 live births).

`Human Development Groups`: Classification of countries into 'Low', 'Medium', 'High', or 'Very High' HDI.

---

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
   - What is the average Maternal Mortality Rate per HDI?
     
---
### Visualizations 
![line graph ](https://github.com/user-attachments/assets/18428bbd-462c-47fe-b97b-e1b68812001c)

**Figure 1:** *Line graph showing the maternal mortality rates from 1990 to 2021 for each Human Development group.*

![Bar Chart](https://github.com/user-attachments/assets/ddeec64a-8934-4862-90f7-3f06bc0340b6)

**Figure 2:** *bar graph gives us a snapshot of the Maternal Mortality Rates per Human Development group in the year 2021.*

![Box Plot](https://github.com/user-attachments/assets/54aa824b-07b6-4d5f-b3e1-22eaa5414dd4)

**FIgure 3:** *Boxplot that shows the distribution of maternal mortality rates (MMR) for each HDI category in the year 2021.*

---

### Results
Pearson Correlation: 0.703

P-value: 0.0

ANOVA:  2777.26

P-value: 0.0

Pearson Correlation: 0.7036: This indicates a moderate to strong positive correlation between the Human Development Index (HDI) Rank and Maternal Mortality Rate (MMR). A positive correlation means that as the HDI increases 

F-statistic: This value measures how much the means of the different groups (in this case, the HDI categories) differ relative to the variation within each group.

The boxplots reveal a wide spread of maternal mortality rates for countries classified under the 'Low' and 'Medium' HDI groups, particularly in earlier years. This indicates significant variability in outcomes within these groups, suggesting disparities in maternal healthcare and socio-economic conditions.

High maternal mortality rates in these groups, even if considered statistical outliers, are reflective of structural neglect and underscore the critical need for targeted interventions to reduce maternal deaths.

---
### Recommendations 
1. Policy and Advocacy
 - Strengthen Health Infrastructure: Advocate for increased investments in maternal health infrastructure in low- and medium-HDI countries, particularly in rural and underserved areas.
 - Global Collaboration: Encourage partnerships between high-HDI nations and those with lower HDI rankings to share expertise, resources, and technology.
Targeted Maternal Health Programs: Develop region-specific maternal health programs that address cultural, economic, and logistical barriers to healthcare access.
2. Resource Allocation
 - Prioritize Funding: Allocate funding toward maternal health programs in regions with high mortality rates, particularly in Africa and South Asia, as suggested by data trends.
3. Capacity Building and Education
 - Train Healthcare Providers: Enhance training programs for midwives, nurses, and doctors in low-resource settings to improve maternal healthcare delivery.
 - Community Awareness: Implement educational campaigns about maternal health, emphasizing the importance of timely healthcare access during pregnancy.
4. Equity and Inclusivity
- Focus on Vulnerable Populations: Pay special attention to indigenous and marginalized communities within 'Low' and 'Medium' HDI countries, as they are often disproportionately affected.
---
### Limitations
Quality of Data:

- Maternal Mortality Rates (MMR) in low-HDI countries may be underreported or misclassified due to weak health information systems.
- HDI scores are composite indices that may oversimplify a country's socio-economic dynamics, which could affect their relevance to maternal mortality.
  
Temporal Trends:

- The dataset spans multiple decades, but the HDI categories or rankings might not account for significant fluctuations or reforms in specific years.
- Historical biases or policy shifts during the time frame might not have been controlled for.
  
Correlation vs. Causation:

- While the correlation analysis shows a strong relationship between HDI and MMR, it does not imply causation. Other unexamined factors (e.g., cultural practices, political stability) could influence maternal mortality.

Outliers:

- The spread in the boxplot, especially for the 'Low' and 'Medium' HDI groups, suggests the presence of extreme values. While these outliers are significant, they may disproportionately influence statistical results.

Aggregation Bias:

- Grouping countries into broad HDI categories (e.g., 'Low,' 'Medium') might mask within-group heterogeneity. For example, countries with 'Medium' HDI scores might experience vastly different MMRs due to regional or policy-specific factors.

Use of Averages:

- Averaging MMR for HDI groups could oversimplify the data and fail to account for the diverse realities within each group.














