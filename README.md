# basedecreditoregrelinear

Credit Analysis - Linear Regression
This GitHub repository hosts a Jupyter notebook conducting a comprehensive linear regression analysis on the "Credit Limit" dataset. The primary objective is to forecast the overdraft limit based on diverse customer attributes.

Notebook Overview
Libraries Utilized
Essential libraries, including pandas, numpy, seaborn, and scikit-learn, have been imported to facilitate the analysis.

Data Loading
The notebook seamlessly loads data from the file "Cópia de Limite_Credito_Dummy.xlsx" utilizing the pandas library.

Preprocessing
To prepare the dataset for analysis, LabelEncoder was employed to transform categorical columns like 'Escolaridade' (Education), 'Gênero' (Gender), and 'Região' (Region) into numerical values. Furthermore, MinMaxScaler was applied to normalize the entire DataFrame.

Exploratory Analysis
Visualizations, specifically histograms, were generated to intuitively comprehend the distribution of the target variable 'LimitedoChequeEspecial' (Overdraft Limit). Descriptive statistics for the DataFrame were also calculated.

Regression Modeling
Leveraging the statsmodels library, the notebook conducts linear regression with various configurations of independent variables, providing detailed results for each fitted model.

Linear Regression Model with scikit-learn
The data was partitioned into training and testing sets, and a linear regression model was trained on the former. The model's performance on both training and test sets was evaluated using crucial metrics like MAE, MSE, and RMSE.

Key Insights
Multiple linear regression models were fitted using diverse sets of independent variables. Model performance metrics were meticulously computed and scrutinized to discern the variables with the most substantial impact on predicting the overdraft limit.

Running the Notebook
Install the required libraries listed in the requirements.txt file.
Open the Jupyter notebook.
Execute each cell of the notebook sequentially to replicate the analyses and outcomes.
Feel free to explore, contribute, and engage in discussions!
