# Loan Default Prediction
Student project using SBA loan data to predict whether a loan will default.

## About this project
This notebook explores Small Business Administration loan data and builds machine learning models to predict whether a loan will be paid back or default.
In this project, I cleaned the data, explored the relationships between variables, prepared the dataset for modelling and trained models to predict loan default.

## Summary of the work done
- Cleaned and prepared the loan data.
- Checked for missing values and unusual entries.
- Converted columns into a usable format.
- Used visualizations to better understand the data.
- Created a target variable for loan default.
- Trained and evaluated models.

## Dataset
The dataset includes information about SBA loans such as loan amounts, business information, approval information and repayment outcomes.
The target variable created for this project was:
- default = 0 for loans that were fully paid
- default = 1 for loans that defaulted

## Models
- Logistic Regression
- Random Forest

## Results
The models were evaluated using accuracy, confusion matrix and ROC AUC

| Model | Accuracy | AUC |
|-------|----------:|----:|
|Logistic Regression | 87.3% | 0.902|
|Random Forest | 94.5% | 0.974|

- Logistic Regression gave a solid result.
- Random Forest performed better overall and gave the stronger result.

## Key Findings
- The dataset is imbalanced because most of the loans were paid back.
- Multiple numerical values were highly right skewed.
- Loan and business related variables were useful for predicting default.
- Random Forest captured the patterns better than Logistic Regression.

## Interpretation
These results seem to be consistent because loan default is influenced by a combination of multiple factors and not just one variable.
Logistic Regression mainly captures linear relationships between variables.
Random Forest performed better because it was able to capture more complex patterns than Logistic Regression.
The fact that Random Forest performed better suggests that the relationship between variables and default is not linear.

## Tools used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## My motivation for choosing this project
Throughout my studies, I learned about machine learning and working with datasets. I wanted to apply that knowledge by practising data cleaning, analysis and machine learning techniques using a real world financial dataset.

## File
- `Loan-Default.ipynb` - main notebook


