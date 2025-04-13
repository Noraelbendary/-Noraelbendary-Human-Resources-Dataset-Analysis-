https://drive.google.com/drive/folders/1jNAdz5DigEthu8tELwiBp9akQH5Hoam-?usp=drive_link
    <h2> Human Resources Datset Analysis </h2><br>
</div>


<div align= "center">
    <img src="https://github.com/Noraelbendary/-Noraelbendary-Human-Resources-Dataset-Analysis-/blob/main/12643932_5031659.jpg">
</div>



### :writing_hand: HR ANALYTICS
Human Resource Data Analysis is the process of collecting and analyzing employee data to improve organizational performance. This analysis links HR data with the organization's strategic objectives, allowing for the measurement of how HR initiatives contribute to achieving those goals. Over the years, this analysis has become a critical tool for data-driven decision-making in workforce management.

Historically, interest in HR data analytics began in the 1970s, when companies used simple statistics to analyze resignation rates and absenteeism. Over time, tools and techniques have evolved significantly, and companies now rely on more complex data analysis to identify factors affecting employee satisfaction and retention. 


<a><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>


### :round_pushpin: OBJECTIVE

Employee attrition is the rate at which employees leave a company. The goal of this analysis is to model employee attrition and determine the most dominant contributing factors that govern this turnover. Through this kind of analysis, we can understand how many employees are likely to leave, while also determining which employees are at the highest risk and for what reasons.


<a><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>



#### Methodology:-
```
- Load the Dataset: 
HR Analytics Attrition Dataset is loaded using the pd.read_csv() function. The head() and info() methods are used to display the first few rows and get information about the dataset, respectively.

- Knowing the Dataset: 
Basic Information about the dataset is generated; numerical and categorical attributes are enlisted.

- Data Cleaning:
Managing missing and Duplicates values, handling outliers, Merging the employee and performance rating CSV files to analyze trends throughout the employee lifecycle, and ensuring proper date formatting.

- Data Visualization: 
Matplotlib and Seaborn libraries are used to visualize the data. 

- Statistical Analysis: 
The T-Test is performed to analyze the Numerical Features' Importance in Employee Attrition, while the Chi-Square Test to Analyze the Categorical Feature Importance in Employee Attrition.

```

<a><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :file_folder: DATASET
### Data Set Content and Dimensions:  
### Total of 5 datasets:
```
- Employee csv: Contains employee information with 1,470 records and 23 columns.

- Performance Rating csv: Historical data of employee’s personal metrics and manager’s rating, consisting 6709 rows and 11 columns.

- Education level csv: Ordinal Categorical labels converted from numerical figures (1 being the lowest and 5 being the highest).

- Satisfied level csv: Ordinal Categorical labels converted from numerical figures (1 being the lowest and 5 being the highest).

- Rating level csv: Ordinal Categorical labels converted from numerical figures (1 being the lowest and 5 being the highest) on self and managerial ratings.


```


<a><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :memo: LIBRARIES USED:
```
- Pandas
- NumPy
- Matplotlib
- Seaborn
- chi2_contingency
- ttest_ind
```

<a><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :warning: PREREQUISITES

```
- Python Programming
- Data Analysis
- Data Pre-processing
- Data Visualization
- Statistical Analysis
```

<a><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :key: CONCLUSION
```
- The company's attrition rate stands at 16.12%, meaning that one in every six employees leaves, indicating challenges in employee retention.

- The most influential factors affecting attrition include:  Age, Job Role, Department, Marital Status, Education Field, Stock Option Level, Salary, Overtime, and 
  Tenure-related variables.

- Younger, single employees, those working in Sales, frequent travelers, and those with low salaries or required to work overtime are more likely to leave the 
  organization.

- Employees who haven’t been promoted for a long time or have limited time with their current manager also show higher attrition rates.

- Factors such as Gender, Distance from Home, Environment Satisfaction, Job Satisfaction, and Work-Life Balance showed no statistically significant relationship, 
  but may still contribute indirectly.

- Employees with higher salaries, longer tenure, and higher job levels tend to have a lower likelihood of leaving.

- There was a data inconsistency observed in some performance ratings, where the Review Date preceded the Hire Date.

- The dataset contains no missing or erroneous values, and all features are in the correct data type.

- There are strong positive correlations between attrition and: Performance Rating, Monthly Income, Number of Companies Worked, and Distance from Home.

```
<a><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :globe_with_meridians: RECOMMENDATIONS
```
- Provide targeted support and incentives for younger and newly hired employees, especially in high-turnover departments like Sales and Tech.

- Reassess overtime policies and reduce excessive workload to promote healthier work-life balance.

- Establish clear career development and promotion paths, particularly for long-term employees with limited advancement.

- Enhance salary structures and stock option accessibility, especially for lower-paid employees.

- Consider the impact of marital status  and offer flexible policies or support programs for single employees, who are more likely to leave.

- Implement mentorship and onboarding programs to support employees with less tenure or limited interaction with their managers.

- Review and validate performance rating data, addressing anomalies like review dates that precede hire dates.

- Develop tailored retention strategies for roles with high attrition, such as Sales Representatives and frequent travelers.

- Explore indirect influences of non-significant factors, like job satisfaction or environment satisfaction, as they may still affect engagement.

- Maintain continuous data monitoring and analysis to detect emerging patterns and make evidence-based HR decisions.


```



 
<a><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>
