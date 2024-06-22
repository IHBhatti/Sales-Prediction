**##Sales Prediction Analysis**

## Introduction
This project analyzes the relationship between TV advertising expenditures and sales using a simple linear regression model.
## Dataset
The dataset contains the advertising budgets (in thousands of dollars) for TV, radio, and newspaper, along with the corresponding sales (in thousands of units) for a product.
## Source
The dataset is provided in the ISLR book and is available for download.[here](https://www.statlearning.com/s/Advertising.csv).
## Structure
- **TV**: Advertising budget for TV (in thousands of dollars).
- **Radio**: Advertising budget for radio (in thousands of dollars).
- **Newspaper**: Advertising budget for newspaper (in thousands of dollars).
- **Sales**: Sales of the product (in thousands of units).
## Objective
The primary objective of this project is to analyze the relationship between TV advertising expenditures and sales using a simple linear regression model.
## Analysis Process

### Data Cleaning
1. **Missing Values**: Checked for any missing values in the dataset.
2. **Data Types**: Ensured all columns have appropriate data types.

### Exploratory Data Analysis (EDA)

1. **Summary Statistics**: Calculated basic summary statistics for the dataset.
2. **Correlation Analysis**: Investigated correlations between TV advertising and sales.
### Simple Linear Regression
1. **Model Definition**: Defined the simple linear regression model with TV advertising as the predictor and sales as the response.
2. **Model Training**: Trained the linear regression model on the dataset.
3. **Model Summary**: Generated and interpreted the summary statistics for the model.
### Model Evaluation
1. **Residual Analysis**: Examined residuals to check for any patterns.
2. **Goodness-of-Fit**: Evaluated the model using R-squared and Adjusted R-squared values.
3. **Significance Testing**: Conducted t-tests to determine the significance of the model coefficients.

### Results

1. **Regression Equation**: Derived the regression equation from the model.
2. **Coefficient Interpretation**: Interpreted the coefficients of the regression model.
3. **Predictions**: Made predictions of sales based on TV advertising budgets.
4. **Visualization**: Plotted the regression line along with the data points.

### Conclusion
The analysis revealed a significant positive relationship between TV advertising expenditures and sales. The model indicates that increasing TV advertising budgets is associated with higher sales.

## Tools and Technologies

- **Python**: Programming language used for analysis and modeling.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical operations.
- **Matplotlib & Seaborn**: Data visualization.
- **Statsmodels**: Statistical modeling.

