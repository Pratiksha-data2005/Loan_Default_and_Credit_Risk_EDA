#  Loan Default Prediction: Exploratory Data Analysis & Data Cleaning

##  Project Overview
This project is an Exploratory Data Analysis (EDA) focused on financial data and credit risk analytics. The primary objective is to inspect raw and messy financial data, handle errors and missing values, and use meaningful visualizations to understand the key factors driving loan defaults.

* **Note:** This repository represents the **First Phase (EDA & Data Cleaning)** of the project. Machine learning models will be built and integrated in a subsequent phase.



##  Data Cleaning & Preprocessing Steps
The initial raw dataset (`Loan_Total_RAW_Uncleaned.csv`) contained several data quality issues, which were resolved step-by-step:
* **Duplicate Removal:** Identified and removed duplicate rows from the dataset.
* **Handling Invalid Entries:** Corrected or filtered out unrealistic values such as negative ages.
* **Missing Value Imputation:** Handled missing values in columns like `Annual_Income`, `Employment_Length_Yrs`, and `Interest_Rate` using appropriate methods.
* **Data Type Standardization:** Ensured all column data types were correctly formatted for analysis.



##  Exploratory Data Analysis & Visualizations
Several charts and graphs were generated to explore patterns and distributions:
* **Univariate Analysis:** Used histograms and boxplots to examine individual distributions of variables like `Loan_Amount`, `Annual_Income`, and `Credit_Score`.
* **Bivariate Analysis:** Created scatter plots and bar charts to check the relationships between `Loan_Status` and other variables such as `Debt_To_Income_Ratio` and `Interest_Rate`.
* **Correlation Heatmap:** Generated a heatmap to analyze the correlation among numerical features.



##  Key Insights from EDA
1. **Debt-to-Income Ratio Impact:** Borrowers with a higher debt-to-income ratio have significantly higher chances of loan default.
2. **Credit Score & Defaults:** Customers with lower credit scores fall predominantly into the default category.
3. **Loan Grades:** Lower loan grades (such as D and E) come with substantially higher interest rates, clearly reflecting higher risk.



##  Future Scope
* Classification algorithms (such as Logistic Regression, Random Forest, etc.) will be trained on this cleaned and processed dataset later.
* Model evaluation metrics (such as Accuracy, Precision, Recall, and confusion matrix) will be used to select the best-performing model and update this repository.
