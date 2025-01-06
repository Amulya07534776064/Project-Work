# E-Commerce Churn Prediction
PROJECT OVERVIEW:
This project will use machine learning models to predict whether or not customers in the e-commerce commodity will experience a churn. Customer churn occurs when a customer stops engaging with the business. By knowing the reasons for churn and predicting them beforehand, e-commerce businesses could then offer their customers better retention strategies.

PURPOSE:
Predicting customer churn through machine learning models is a key strategy for e-commerce businesses. Most major strategies revolve around customer retention, and a high churn rate significantly affects revenue. Therefore, machine learning models are used to predict customer churn through various features.

DATASET:
"E-Commerce Customer Churn" dataset contains customer churn information against various attributes. The dataset can be found using the link: Kaggle Dataset. This dataset includes:
•	Gender
•	Mode of Payment
•	Satisfaction Score
•	Cashback Rate
•	And a lot more

TECHNOLOGIES USED:
•	Python: Programming language.
•	Jupyter Notebook: For code development and testing.
•	Pandas, NumPy: For data manipulation.
•	Matplotlib, Seaborn: For data visualization.
•	Scikit-learn: For building and evaluating machine learning models.

EXPLORATORY DATA ANALYSIS(EDA):
1. Customer Churn: 
•	16.7% of all customers leave the platform.
2. Payment Mode: 
•	Cash on Delivery customers have a higher churn rate. 
•	Debit cardholders have the least churn. 
3. Gender: 
•	Males are more in numbers and have a greater churn rate compared to females. 
4. Preferred Order Category:
•	A greater churn rate is noticed in customers who buy mobile phones. 
•	There is no churn in the grocery segment. 
5. City Impact: 
•	People from City Tier 2 churn at a greater rate. 
•	Cities in Tier 1 demonstrate minimum churn. 
6. Satisfaction Score: 
•	The customers with 1 and 2 levels of satisfaction exhibit the highest churn rates. 
7. Number of Registered Devices: 
•	Customers with more than 5 registered devices show a higher churn rate. 

MACHINE LEARNING MODELS APPLIED:
1.	Logistic Regression
2.	Decision Tree
3.	Random Forest
4.	Gradient Boosting
MODELING PHASES:
1.	Models applied to imbalanced data.
2.	Models applied to balanced data using Random Oversampling.
3.	Models applied to balanced data using SMOTE.
FEATURE SELECTION:
Feature selection methods were used to save time and space by removing unnecessary columns:
1.	Correlation-based selection.
2.	Chi-Square-based selection.
POST-FEATURE SELECTION:
1.	Models were reapplied three times as above (imbalanced, balanced with Random Oversampling, balanced with SMOTE).
2.	Hyperparameter tuning was performed on Logistic Regression.
RESULTS:
1.	In imbalanced data after feature selection, the performance of the Decision Tree was affected the most, while other algorithms performed well. Selected features were effective.
2.	For balanced data (Random Oversampling and SMOTE), no major accuracy changes were observed.
3.	Feature removal led to no significant accuracy drop, confirming that the removed features were unnecessary.
4.	Hyperparameter tuning improved Logistic Regression performance.
5.	Accuracy of all models was checked after removing one feature at a time.
