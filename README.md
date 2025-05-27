# Impact of Different Diet Plans on Weight Change After Six Weeks


### Analysis Overview
This analysis aims to evaluate how three distinct diet plans (Diet 1, Diet 2, and Diet 3) influence individuals' weight outcomes after six weeks. By comparing the weight measurements at the six-week mark across these diet groups, the study seeks to identify which diet is most effective for weight loss or maintenance. Additionally, detecting and understanding any outliers in the data will help ensure the robustness of the results and provide insights into individual variations.

### Data Source
The data used in this analysis was sourced from a CSV file named 'Diet.csv', which contains information on individuals' weight changes over six weeks under three different diet plans.

### Tools
- SQL- Data Cleaning
- Python- Data Analysis

### Data Preparation
During the initial data preparation stage, we carried out the following tasks:
- Data loading and inspection
- Handling missing values
- Data formatting

### Exploratory Data Analysis
An exploratory analysis of the "Diet" dataset was carried out to answer essential questions like:
- Are there any outliers in baseline weight within each diet category?
- Was normal distribution observed within each group?
- Is there equality of variance between the groups?
- Are there significant differences in baseline body weight between participants following different diets

### Data Analysis
A Python script has been attached to this documentation.

### Result
A one-way Anova was conducted to determine if the types of diet have an impact on weight change after six weeks of dieting.
   Participants were classified into three groups:1,2 and 3
   There is an outlier, as assessed by boxplot; data was normally distributed for each group, as assessed by Shapiro-Wilk test (p>0.05); and there was homogeneity of variances (p=0.64).
   Data is presented as mean ± standard deviation.
   There is no statistically significant difference between the impact of the types of diet on weight change after six weeks of dieting,
F(2, 75) = 0.260, p = 0.772, ω² = -0.0194 ≈ 0

This result implies that all three diets produced similar outcomes in terms of weight change, within the sample and timeframe studied.

### Recommendation
Since the data met all assumptions for valid ANOVA analysis—including normality, homogeneity of variances, and limited outlier influence, this conclusion is considered robust within the study’s scope.
Therefore, dietary recommendations should focus on individual sustainability, nutritional adequacy, and personal preference rather than assuming one diet is more effective for short-term weight reduction.

 
### Limitations
- Presence of an Outlier
- Small Effect Size (ω² ≈ 0)
- Sample Size Considerations
- Lack of Control for Confounding Variables
- Only One Time Point Assessed
- Assumption of Homogeneity May Be Affected by Outlier

   








