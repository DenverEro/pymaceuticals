# Pymaceuticals Inc. Study Analysis
### Overview
Pymaceuticals, Inc. conducted a study to evaluate the effectiveness of various drug regimens in treating squamous cell carcinoma (SCC) in mice. This analysis provides a comprehensive overview of the data collected from the study, including summary statistics, visualizations, and statistical analyses to compare the performance of the drug regimens.

### Data Preparation
The dataset consists of two main files:

- Mouse_metadata.csv: Contains information about the mice, including their sex, age, and weight.
- Study_results.csv: Contains the tumor volume measurements and other data collected during the study.
These files were merged into a single dataset, and duplicate entries were removed to ensure data integrity.

### Summary Statistics
Summary statistics were calculated for each drug regimen, focusing on the tumor volume measurements. The statistics include the mean, median, variance, standard deviation, and standard error of the mean (SEM).

### Visualizations
#### Bar Charts
Two bar charts were generated to show the total number of mice per treatment regimen:

- One using Pandas' DataFrame.plot() method
- One using Matplotlib's pyplot methods
#### Pie Charts
Two pie charts were created to illustrate the distribution of female versus male mice in the study:

- One using Pandas' DataFrame.plot() method
- One using Matplotlib's pyplot methods
#### Box Plot
A box plot was generated to show the distribution of the final tumor volume for four treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. The analysis identified a potential outlier in the Infubinol treatment group.

#### Line Plot
A line plot was created for a single mouse treated with Capomulin, showing the tumor volume versus time point.

#### Scatter Plot
A scatter plot was generated to show the relationship between mouse weight and average tumor volume for the Capomulin treatment regimen.

### Statistical Analysis
A correlation and linear regression analysis were performed between mouse weight and average tumor volume for the Capomulin treatment regimen. The results indicated a strong positive correlation (correlation coefficient = 0.842) with the following regression parameters:

- Slope: 0.954
- Intercept: 21.552
- R-squared value: 0.842
- P-value: 
1.32
×
1
0
−
7
1.32×10 
−7
 
### Conclusion
The analysis provided valuable insights into the effectiveness of different drug regimens in treating SCC in mice. The Capomulin regimen, in particular, showed promising results with a strong correlation between mouse weight and tumor reduction.