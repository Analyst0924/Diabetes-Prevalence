
# Analyzing Demographic and Health Factors Influencing Diabetes Prevalence

## Project Overview

This project investigates the key demographic and health factors that contribute to the prevalence of diabetes. Using a large dataset, this analysis employs statistical modeling and data visualization to understand the relationships between variables like race, gender, BMI, hypertension, and heart disease, and their impact on diabetes risk. The primary goal is to derive actionable insights that can inform public health strategies and interventions.


## Business Problem

To identify the primary factors contributing to diabetes across different racial and gender groups. The success of this project is measured by the ability to understand the relationship between diabetes and risk factors such as BMI, HbA1c level, blood glucose level, smoking history, and hypertension to derive insights for public health interventions.

## Data Source

The dataset for this analysis was sourced from Kaggle: [Diabetes Prediction 99% Recall Rate](https://www.kaggle.com/code/ailenenunez/diabetes-prediction-99-recall-rate/input).

**Data Preparation:**
- Consolidated race columns for clarity.
- Standardized gender labels.
- Excluded rows with missing or "No Info" smoking history.
- Created BMI categories to facilitate analysis across different weight groups.

## Methodology

A variety of statistical methods were employed to analyze the data:

1.  **Descriptive Statistics:** To summarize and understand the data distributions.
2.  **Pivot Tables:** To calculate marginal probabilities of diabetes for specific demographic groups.
3.  **Logistic Regression:** To model the likelihood of diabetes based on risk factors and determine the significance of each variable.
4.  **Chi-Square Test:** To evaluate the dependency of diabetes on race and gender.
5.  **Correlation Analysis:** To identify relationships between diabetes status, gender, race, and various predictors.

## Key Findings

-   **High-Risk Groups:**
    -   **Age:** Older populations ("45-64" and "Over 65") are at a significantly higher risk.
    -   **BMI:** Individuals in the "Obesity" and "Overweight" categories show a higher prevalence of diabetes.
    -   **Health Conditions:** Hypertension and a history of heart disease are strong predictors of diabetes.

-   **Gender and Race:**
    -   Males generally have a higher prevalence of diabetes across all racial groups.
    -   Among males, Asians (10.39%) and African Americans (9.96%) have the highest prevalence.
    -   Among females, African Americans (7.88%) and Hispanics (7.61%) have the highest prevalence.

## Model Results

The logistic regression models provided the following odds ratios for key predictors:

| Factor | Odds Ratio | Interpretation |
| :--- | :--- | :--- |
| **Heart Disease** | ~4.33 | Individuals with heart disease are over 4 times more likely to have diabetes. |
| **HbA1c Level** | ~7.11 | Higher HbA1c levels are one of the strongest predictors of diabetes. |
| **Hypertension** | ~2.99 | Individuals with hypertension are nearly 3 times more likely to have diabetes. |
| **Ever Smoked** | ~2.82 | Those who have smoked in the past are nearly 3 times as likely to have diabetes. |
| **BMI** | ~1.09 | For every unit increase in BMI, the odds of being diabetic increase by about 9%. |

## Conclusion

The analysis reveals that while diabetes prevalence is relatively similar across racial groups, specific health factors significantly increase the risk. Older age, high BMI, hypertension, and a history of heart disease are primary drivers. Public health initiatives should focus on preventative care and management strategies targeting individuals with these high-risk profiles.

## Team

- Ashraf Afana
- Anu Girija
- Amanjot Kandhola
- Alan Mathews
- April Uy
