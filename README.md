# HR Attrition Analysis and Modelling

This project aims to analyze and predict employee attrition within an organization. By leveraging a variety of features related to employee demographics, job roles, and work conditions, the goal is to identify factors contributing to employee turnover and build a predictive model to forecast attrition.

## Project Overview

The project involves the following steps:

1. **Data Collection**: The dataset contains various features such as employee ID, age, gender, job role, marital status, remote work status, leadership opportunities, innovation opportunities, and other relevant factors that may influence employee attrition.

2. **Data Preprocessing**: 
   - Handling missing values and removing irrelevant columns like `Employee ID`.
   - Encoding categorical variables, including one-hot encoding for non-ordinal features and label encoding for ordinal features.
   - Creating a balanced dataset for training by understanding the distribution of the target variable `Attrition`.

3. **Exploratory Data Analysis (EDA)**:
   - Visualizing relationships between different features and attrition rates using histograms, count plots, KDE plots, and box plots.
   - Identifying key patterns such as the impact of promotions, performance ratings, remote work, leadership opportunities, and tenure on attrition.

4. **Modeling**:
   - Using a RandomForestClassifier to build a predictive model.
   - Analyzing feature importance to understand which factors most strongly influence employee attrition.

5. **Evaluation**:
   - Splitting the data into training and testing sets.
   - Evaluating model performance using appropriate metrics.
   - Interpreting the results to provide actionable insights.

## Key Insights

- Employees with leadership and innovation opportunities are less likely to leave, highlighting the importance of growth and development in retention.
- Higher attrition rates are observed among entry-level employees and those with fewer years at the company, suggesting challenges in retaining new hires.
- Single employees are more likely to leave compared to married employees.
- Employees with 3 to 4 promotions tend to stay with the company, indicating that career advancement is a critical factor in employee retention.

## File Structure

- `HR_attrition_prediction.ipynb`: The Jupyter Notebook containing all the code, visualizations, and analysis for the project.
- 'test.csv': The dataset used for analysis and modeling.
- `README.md`: This file provides an overview of the project, including the objectives, methodology, and key insights.

## How to Run the Project

1. Clone the repository to your local machine.
2. Ensure you have the necessary libraries installed, including `pandas`, `numpy`, `seaborn`, `matplotlib`, and `scikit-learn`.
3. Open the `HR_attrition_prediction.ipynb` notebook in Jupyter Notebook or JupyterLab.
4. Run the cells in sequence to reproduce the analysis and results.

## Conclusion

This project demonstrates how data-driven approaches can provide valuable insights into employee attrition, enabling organizations to take proactive steps to improve employee retention. The predictive model developed here can be further refined and integrated into HR analytics systems for real-time decision-making.



