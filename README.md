# covid-19-survey-analysis
This project analyzes publicly available COVID-19 Case Surveillance data from the CDC and demographic data from the US Census Bureau. The aim is to understand the impact of demographics on COVID-19 outcomes (hospitalizations, ICU admissions, and deaths) and predict the likelihood of death due to COVID-19 using machine learning techniques.
# Key Objectives
1. Data Analysis and Visualization:

* Analyze the total number of COVID-19 hospitalizations versus deaths across the US on a monthly basis.
* Investigate COVID-19 death rates relative to patient demographics (age, gender, race/ethnicity).
* Explore the relationship between age, pre-existing medical conditions, and COVID-19 outcomes (hospitalization, ICU admission, death).
* Assess the impact of COVID-19 on employment loss by demographic and sector.
2. Hypothesis Testing:

* Test the association between COVID-19 death probability and patient demographics.
* Formulate and test additional hypotheses based on the data.
3. Regression Analysis:

* Fit regression models to predict the proportion of deaths out of all COVID-19 cases based on gender, age distribution, ICU admissions, and hospitalizations.
4. Machine Learning Prediction:

* Train and evaluate machine learning classifiers to predict the likelihood of death due to COVID-19 using relevant attributes.
# Methodology
* Data Preparation: Cleaning and preprocessing the dataset, handling missing values, and encoding categorical variables.
* Exploratory Data Analysis (EDA): Using statistical analysis and visualizations to uncover patterns and insights.
* Hypothesis Testing: Conducting Chi-Square tests to explore associations between categorical variables.
* Regression Analysis: Using linear regression to identify significant predictors of COVID-19 death rates.
* Machine Learning: Implementing models like Logistic Regression, Random Forest, and Gradient Boosting, and performing hyperparameter tuning to improve predictive performance.
# Tools and Libraries
* Programming Language: Python
* Data Processing: Pandas, NumPy
* Data Visualization: Matplotlib, Seaborn
* Statistical Analysis: SciPy, Statsmodels
* Machine Learning: Scikit-learn, XGBoost
* Model Evaluation: Classification metrics, ROC-AUC score
# Results and Insights
* Detailed analysis of COVID-19 hospitalizations and deaths by month, age group, gender, and state.
* Identification of key demographic factors influencing COVID-19 outcomes.
* Significant predictors of COVID-19 mortality rates and their relative importance.
* Predictive models for estimating the likelihood of death due to COVID-19, demonstrating the efficacy of Gradient Boosting with hyperparameter tuning.
# Conclusion
This project provides a comprehensive analysis of COVID-19 surveillance data, offering valuable insights into the demographic factors influencing COVID-19 outcomes. The predictive models developed can assist in identifying high-risk individuals and informing public health strategies.
