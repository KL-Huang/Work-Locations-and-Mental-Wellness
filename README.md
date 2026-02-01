# Project Description: Analysis of Remote Work Impact on Mental Health

## Files
- **IS630_G2_3_Group_3_Statistical_Thinking_for_Data_Science_Mental_Wellness.ipynb**: The main Jupyter Notebook containing the analysis code.
- **Impact_of_Remote_Work_On_Mental_Health.xlsx**: The raw dataset used.

## Analysis Workflow
This notebook performs the following analysis steps:

1. **Data Loading & Exploration**:
   - Loads the Excel dataset for initial observation and descriptive statistical analysis.
   - Plots a Correlation Matrix Heatmap to visualize relationships between variables.

2. **Statistical Hypothesis Testing**:
   - Analyzes differences between "Remote" and "Non-Remote" work in terms of **Hours Worked Per Week** and **Number of Virtual Meetings** (using Z-test).
   - Analyzes differences in working hours between groups "With Mental Health Conditions" and "Without Mental Health Conditions".
   - Calculates the Spearman correlation coefficient between Stress Level and Hours Worked Per Week.

3. **Predictive Modeling (Logistic Regression)**:
   - **Objective**: Predict whether an employee has a mental health issue (e.g., Burnout, Depression, Anxiety).
   - **Feature Engineering**: Performs One-hot encoding on categorical variables like Work Location and Stress Level.
   - **Data Preprocessing**: Uses **SMOTE** (Synthetic Minority Over-sampling Technique) to address data imbalance.
   - **Model**: Builds a Logistic Regression classification model.
   - **Evaluation**: Evaluates model performance using Cross-validation, Confusion Matrix, ROC Curve, and Feature Importance.

## Conclusion
This analysis aims to explore the relationship between various remote work factors (such as working hours and meeting frequency) and employee mental health using statistical methods and machine learning models.
