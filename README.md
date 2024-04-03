# Machine-learning-finance-classes Project
This is an obligatory project created for "machine learning" classes taught at the UEP.

## Classes file

- [MLF_class_classification.ipynb](https://github.com/a-smaruj/Machine-learning-finance-classes/blob/main/MLF_class_classification.ipynb)

## Homeworks file

### [Use Case 1](https://github.com/a-smaruj/Machine-learning-finance-classes/blob/main/Use_case_1.ipynb)

- Data Cleaning

The 'fraud' data needed data cleaning. It was necessary to remove null values and redundant columns. There were too many outliers, therefore they remained in the set. The categorical variables had too many options, so only the top 10 were left in the set, others were named 'other'. 

- Data Processing

Column transformation, like standardisation for numeric variables and One Hot Encoding for categorical variables, were implemented. Then PCA was used for dimensional reductions. To create models, data split was needed, so data was split between train and test sets. Unfortunately, there was a huge difference between the size of the two target groups, therefore oversampling was deployed.

- Models

Three models were used: the KNeighbors model, SVM, and Balanced Logistic Regression. Additionally, they were applied to two datasets (only numerical and all data).

- Results

It turned out that the dataset including categorical variables had better scores. Two models (Logistic Regression and SVM) have perfect predictions.

