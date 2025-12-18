# Mental Health and Social Media Usage Analysis Report
## Executive Summary
This report presents findings from an analysis of the Mental Health and Social Media Balance Dataset, examining the relationship between social media usage patterns and mental health outcomes. Our analysis reveals significant correlations between digital habits and mental well-being, with machine learning models successfully predicting stress levels based on behavioral factors. Key insights indicate that screen time, exercise frequency, and social media dependency are the strongest predictors of mental health outcomes, providing a foundation for targeted interventions and digital wellness tools.

 ## 1. Introduction
With social media's growing influence on daily life, understanding its impact on mental health has become a priority for organizations and mental health practitioners. This analysis aims to:

i. Examine how social media usage patterns affect mental health
1i. Identify behavioral factors that predict stress, anxiety, and sleep issues
iii. Develop machine learning models to predict mental health levels based on lifestyle and online habits
## 2. Data Overview
The analysis utilized a dataset of 500 users with the following key variables:

Demographics:Age, Gender
Digital Habits: Daily screen time, days without social media, social media dependency
Lifestyle Factors: Exercise frequency, screen-to-exercise ratio
Mental Health Metrics: Stress level (1-10), sleep quality (1-10), happiness index (1-10)
# 3. Methodology
3.1 Analytical Approach
Exploratory data analysis to identify correlations and patterns
Feature engineering to create meaningful metrics (screen-to-exercise ratio, social media dependency)
Predictive modeling using Linear Regression and Random Forest algorithms
Statistical analysis to determine significant predictors
3.2 Model Development
We developed several predictive models to assess mental health outcomes:

Linear Regression: With and without regularization (Ridge, Lasso)
Random Forest: With optimized hyperparameters (n_estimators=100, max_depth=10, min_samples_leaf=4)
Models were evaluated using R² and RMSE metrics, with cross-validation to ensure robustness.

4. Key Findings
4.1 How Social Media Usage Patterns Affect Mental Health
Screen Time Impact

Strong positive correlation between daily screen time and stress levels (r=0.42)
Users with >6.5 hours of daily screen time showed 32% higher stress levels (7.2/10) compared to the overall average
Screen time showed negative correlation with sleep quality (r=-0.38) and happiness index (r=-0.35)
Social Media Dependency

Users with high social media dependency (top quartile) reported stress levels of 7.5/10
Taking 2+ days off social media per week was associated with 18% lower stress levels
Digital Balance

Screen-to-exercise ratio emerged as a critical factor, with high ratios (>2.5) correlating with stress levels of 7.3/10
Users who maintained balanced digital and physical activities showed significantly better mental health outcomes
4.2 Behavioral Factors That Predict Mental Health Outcomes
Strongest Predictors of Stress

Screen-to-Exercise Ratio (Importance: 0.24)
Daily Screen Time (Importance: 0.21)
Social Media Dependency (Importance: 0.18)
Exercise Frequency (Importance: 0.15)
Days Without Social Media (Importance: 0.12)
Impact of Exercise

Users exercising <2 times per week showed stress levels of 7.1/10 (vs. 6.2 for those exercising 3+ times)
Exercise frequency showed negative correlation with stress (r=-0.31) and positive correlation with sleep quality (r=0.28)
Age and Gender Differences

Younger users (18-25) showed stronger correlation between screen time and stress
Gender analysis revealed slight variations, with males showing marginally higher stress levels (6.8/10) compared to females (6.5/10)
4.3 Machine Learning Model Performance
Predictive Accuracy

Random Forest Model: Achieved R² of 0.60-0.68, explaining up to 68% of variance in stress levels
Linear Regression Models: Achieved R² of 0.55-0.63 after scaling and regularization
Key Model Features: Screen-to-exercise ratio, daily screen time, and social media dependency were consistently identified as top predictors
