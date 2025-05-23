# Pre-Intervention-Weight-Differences-Across-Various-Diet-Types
This study investigates whether different types of diet have a measurable effect on participants' body weight before starting a dietary intervention, aiming to understand if pre-existing dietary patterns influence baseline body composition and help tailor more effective nutrition strategies.

### Project Overview
This study investigates whether different types of diet have a measurable effect on participants' body weight before starting a dietary intervention, aiming to understand if pre-existing dietary patterns influence baseline body composition and help tailor more effective nutrition strategies.

### Data Source
The data is sourced from a CSV file titled "Diet".

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
This study aimed to investigate whether different types of diet have a measurable effect on participants' body weight before starting a dietary intervention, with the goal of understanding if pre-existing dietary patterns influence baseline body composition and can guide more effective nutrition strategies.

A one-way ANOVA was conducted to compare the pre-intervention body weights of participants grouped into three dietary categories. Although one outlier was identified (via boxplot), the assumption of normality was met for groups 1 and 3, but not for group 2, as assessed by the Shapiro-Wilk test (p = 0.05). Homogeneity of variances was confirmed using Levene’s test (p = 0.30). Data were reported as mean ± standard deviation.

The ANOVA results showed no statistically significant difference in pre-intervention body weight across the three diet groups, F(2, 49.1) = 0.532, p = 0.591, ω² ≈ 0. This suggests that the type of diet participants were following prior to the intervention did not have a measurable impact on their baseline body weight. Therefore, pre-existing dietary patterns may not significantly influence initial body composition, and tailoring nutrition strategies based solely on baseline diet type may have limited benefit in this context.

### Recommendation
Given that no statistically significant difference was found in baseline body weight across different pre-existing dietary groups, it is recommended that future nutrition strategies focus less on prior diet type when designing interventions and instead consider other individual factors such as metabolic markers, lifestyle habits, physical activity levels, and psychological readiness for behavior change.

Additionally, further research with larger sample sizes and more diverse dietary profiles is encouraged to explore whether other dimensions of dietary history—such as nutrient quality, portion control, or meal timing—may play a more meaningful role in influencing baseline body composition and the effectiveness of personalized interventions.

### Limitations

   








