# Predicting-Hospital-Readmission-of-Diabetic-Patient
**Project Overview**
Diabetes is a chronic disease requiring ongoing medical attention. Hospital readmissions for diabetic patients often signal complications that can lead to higher costs and adverse health outcomes. By predicting which patients are likely to be readmitted, healthcare providers can intervene earlier and reduce readmission rates.

In this project, we use the Diabetes 130-US hospitals dataset, containing records of diabetic patients' hospitalizations, to build predictive models that classify patients based on the likelihood of being readmitted within 30 days of discharge.

**Dataset**
The dataset includes over 100,000 instances of patient encounters across 130 hospitals. Each record includes 55 attributes such as patient demographics, lab results, medications, and previous encounters. Key features include:

Patient demographics (age, gender, race)
Medical information (number of lab tests, medications, diagnoses)
Hospitalization history (previous visits, length of stay, discharge status)
The dataset can be downloaded from the UCI Machine Learning Repository.

**Modeling Approach**
We explored several machine learning algorithms to predict hospital readmission, including:

Logistic Regression
Decision Trees
Random Forest
Gradient Boosting
Support Vector Machines

We performed feature engineering to extract the most relevant features and used techniques such as one-hot encoding for categorical variables. Hyperparameter tuning was conducted using grid search and cross-validation.

**Key Steps:**
1. Data Preprocessing: Handling missing values, scaling, and encoding categorical variables.
2. Feature Engineering: Creating additional features based on domain knowledge.
3. Model Training: Training various models to compare performance.
4. Evaluation: Using metrics like accuracy, precision, recall, and AUC-ROC to evaluate models.

**Results**
The best-performing model was the Random Forest, which achieved the following performance on the test set:

Accuracy: 82%
AUC-ROC: 0.76
Precision: 0.68
Recall: 0.62
These results indicate a strong ability to predict readmission, though further improvements could be made with more advanced feature engineering and deep learning techniques.



