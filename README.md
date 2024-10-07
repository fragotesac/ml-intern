# Machine Learning Intern
## Scenario

A private educational institution is experiencing an increase in students defaulting on their tuition fee payments. The administration wants to identify key factors that contribute to this issue and develop a predictive model to anticipate which students are at risk of defaulting. This will enable the school to implement proactive measures such as financial counseling, flexible payment plans, or scholarships to support at-risk students and improve overall financial stability.

## Dataset:

You will use the “Student Financial Default Dataset”, which contains anonymized data on students’ demographics, academic performance, financial background, and payment history. A sample dataset can be found [here](https://github.com/fragotesac/ml-intern/blob/main/student_default_dataset.csv). (Note: Since a specific student default dataset may not be readily available, you can adapt a financial default dataset or simulate one with relevant features.)

Key Features May Include:

	•	Student ID
	•	Age
	•	Gender
	•	Program of Study
	•	Year of Study
	•	Grade Point Average (GPA)
	•	Attendance Rate
	•	Scholarship Recipient (Yes/No)
	•	Parental Income
	•	Employment Status (Part-time/Full-time/Unemployed)
	•	Previous Payment History (On-time/Late)
	•	Outstanding Loan Amount
	•	Extracurricular Involvement (Yes/No)
	•	Default Status (Target Variable: Defaulted/Not Defaulted)

## Tasks Overview:

### 1. Data Exploration and Preprocessing (20%)

	•	Data Loading and Initial Exploration:
	•	Load the dataset and display the first few rows.
	•	Understand the data types and summary statistics of each feature.
	•	Handling Missing Values and Outliers:
	•	Identify missing values and decide on appropriate imputation methods.
	•	Detect outliers using statistical methods and decide whether to remove or adjust them.
	•	Feature Encoding and Transformation:
	•	Encode categorical variables using techniques like One-Hot Encoding or Label Encoding.
	•	Normalize or standardize numerical features if necessary.
	•	Exploratory Data Analysis (EDA):
	•	Visualize the distribution of each feature and the target variable.
	•	Analyze correlations between features and with the target variable using correlation matrices and heatmaps.
	•	Identify any patterns or anomalies that could impact the model.

### 2. Logistic Regression Analysis (25%)

	•	Model Training:
	•	Split the data into training and testing sets (e.g., 70% training, 30% testing).
	•	Train a Logistic Regression model using relevant predictor variables.
	•	Assumption Checks:
	•	Check for multicollinearity among independent variables using Variance Inflation Factor (VIF).
	•	Model Evaluation:
	•	Use metrics such as Accuracy, Precision, Recall, F1 Score, and ROC-AUC to evaluate model performance.
	•	Generate a Confusion Matrix to visualize true vs. predicted classifications.
	•	Interpretation:
	•	Interpret the coefficients to understand the impact of each variable on the likelihood of default.
	•	Identify significant predictors and discuss their practical implications.

### 3. Multivariate Techniques (Principal Component Analysis - PCA) (20%)

	•	Dimensionality Reduction:
	•	Apply PCA to reduce the number of features while retaining most of the variance.
	•	Determine the number of principal components to keep based on the explained variance ratio.
	•	Visualization:
	•	Plot the principal components to visualize data structure.
	•	Modeling with PCA Components:
	•	Retrain the Logistic Regression model using the principal components.
	•	Evaluation and Comparison:
	•	Compare the performance of the PCA-based model with the original model.
	•	Discuss the advantages and disadvantages of using PCA in this context.

### 4. Alternative Classification Models (20%)

	•	Decision Tree Classifier:
	•	Train a Decision Tree model and visualize the tree structure.
	•	Random Forest Classifier:
	•	Train a Random Forest model to enhance prediction accuracy.
	•	Determine feature importance scores and identify key predictors.
	•	Model Evaluation:
	•	Evaluate these models using the same metrics as before.
	•	Use Cross-Validation to ensure model robustness.
	•	Comparison:
	•	Compare the performance of all models (Logistic Regression, PCA-based Logistic Regression, Decision Tree, Random Forest).
	•	Discuss which model performs best and why.

### 5. Regularization Techniques (Lasso and Ridge Regression) (10%)

	•	Applying Regularization:
	•	Implement Lasso (L1) and Ridge (L2) regularization with Logistic Regression to address overfitting and feature selection.
	•	Hyperparameter Tuning:
	•	Use techniques like Grid Search or Random Search with Cross-Validation to find optimal regularization parameters.
	•	Evaluation:
	•	Assess the impact of regularization on model performance and interpretability.
	•	Discuss how regularization affects the coefficients and model simplicity.

### 6. Final Model Selection and Recommendations (5%)

	•	Model Selection:
	•	Choose the best-performing model based on evaluation metrics and business considerations.
	•	Actionable Insights:
	•	Provide recommendations to the school’s administration on strategies to mitigate default risks.
	•	Highlight the most influential factors contributing to student defaults.
	•	Intervention Strategies:
	•	Suggest potential interventions (e.g., financial counseling, payment plans, scholarships).

### Submission Requirements:

	1.	Code:
	•	Submit a well-documented google colab.
	•	Use comments and markdown cells to explain each step clearly.
	•	Include all data preprocessing, analysis, and modeling steps.
	2.	Presentation:
	•	Prepare a brief presentation (5 slides) highlighting:
	•	Project objectives
	•	Data overview
	•	Key findings
	•	Model comparisons
	•	Recommendations

# Grading Criteria:

	•	Data Preprocessing and EDA (20%)
	•	Model Implementation and Evaluation (55%)
	•	Logistic Regression Analysis (25%)
	•	Multivariate Techniques (PCA) (20%)
	•	Regularization and Alternative Models (10%)
	•	Interpretation and Insights (15%)
	•	Report and Presentation Quality (10%)

