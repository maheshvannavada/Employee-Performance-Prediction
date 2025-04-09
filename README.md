Project Overview: Employee Performace prediction.

Business Requirement
INX Future Inc. is a well-established data analytics and automation solutions provider with over 15 years of global business experience. Recently, the company has seen a decline in employee performance indices, raising concerns among senior leadership. In response, CEO Mr. Brian initiated a data science project to analyze current employee data and uncover the root causes of low performance.

The objective of this project is to:

Analyze department-wise performance

Identify the top three factors affecting employee performance

Develop a predictive model to estimate employee performance

Provide data-driven recommendations to improve performance

Data Analysis and Preprocessing
The dataset is supervised and contains mostly categorical variables. The target variable, 'Performance Rating', is ordinal. The predictor variables include both ordinal and nominal data types.

The following steps were performed during preprocessing:

Label encoding for categorical features

Standardization of numerical features

Correlation analysis to understand the relationships between variables

Feature selection based on correlation and relevance to the business problem

Key features selected for modeling include: Department, Job Role, Environment Satisfaction, Last Salary Hike Percent, Work Life Balance, Experience Years at Company, Experience Years in Current Role, Years Since Last Promotion, and Years With Current Manager.

Machine Learning Models Used
Several classification algorithms were implemented to train the model and predict performance ratings:

Logistic Regression

Support Vector Machine

Decision Tree (with GridSearchCV)

Random Forest (with GridSearchCV)

Naïve Bayes

K-Nearest Neighbors

XGBoost Classifier

Artificial Neural Network (MLP Classifier)

Summary of Workflow
Imported the dataset and identified predictors and the target variable

Analyzed department-wise performance

Encoded categorical variables and standardized features

Performed correlation analysis to identify significant predictors

Split the dataset into training and test sets

Trained multiple models and evaluated their performance

Exported the best-performing model using joblib

Results
The Random Forest model with GridSearchCV achieved the highest accuracy of 93%

The XGBoost Classifier performed similarly, with an accuracy of 92.8%

Top three features influencing employee performance:

Environment Satisfaction (39.5%)

Last Salary Hike Percent (33.3%)

Years Since Last Promotion (16.7%)

Positively correlated factors:

Environment Satisfaction

Last Salary Hike Percent

Work-Life Balance

Negatively correlated factors:

Years Since Last Promotion

Years at Company

Years in Current Role

Years With Current Manager

Insights and Conclusion
The analysis suggests that improving work environment, offering timely salary hikes, and promoting a healthy work-life balance can significantly enhance employee performance. Conversely, lack of promotions and static roles or management over extended periods can lower performance.

Recommendations
Based on the findings, the following recommendations are made:

Improve the overall work environment to enhance employee satisfaction

Ensure timely salary hikes and reward systems are in place

Support work-life balance initiatives

Review employee roles regularly and provide opportunities for advancement

Consider rotating managers or team leads to prevent stagnation and improve engagement
