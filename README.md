# basedecreditoregrelinear

Credit Analysis - Linear Regression
This repository contains a Jupyter notebook that performs a linear regression analysis on the "Credit Limit" dataset. The goal is to predict the overdraft limit based on various customer characteristics.

Notebook Contents
Importing Libraries
Imported necessary libraries, including pandas, numpy, seaborn, and scikit-learn.

Data Loading
Loaded data from the file "Cópia de Limite_Credito_Dummy.xlsx" using the pandas library.

Preprocessing
Used LabelEncoder to transform the 'Escolaridade' (Education), 'Gênero' (Gender), and 'Região' (Region) columns into numerical values. Applied MinMaxScaler to normalize the DataFrame's data.

Exploratory Analysis
Generated histograms to visualize the distribution of the target variable 'LimitedoChequeEspecial' (Overdraft Limit). Calculated descriptive statistics for the DataFrame.

Regression Modeling
Used the statsmodels library to perform linear regression with different configurations of independent variables. Printed regression results for each fitted model.

Linear Regression Model with scikit-learn
Split the data into training and testing sets. Fitted a linear regression model using the training set. Evaluated the model's performance on both training and test sets using metrics such as MAE, MSE, and RMSE.

Results
Various linear regression models were fitted using different sets of independent variables. Model performance metrics were calculated and evaluated to determine which variables have the greatest impact on predicting the overdraft limit.

How to Run
Install the required libraries listed in the requirements.txt file.
Open the Jupyter notebook.
Execute each cell of the notebook in order to reproduce the analyses and results.




