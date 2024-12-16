# 📍 Linear Regression and Ridge Regression Models


In this project, two different regression models were used to make predictions on datasets.


## 📌 Datasets

### ✅ Advertising.csv:
This dataset examines the effect of investments in TV, Radio, and Newspaper advertisements on sales.
  
- Independent variables: TV, Radio, Newspaper
- Dependent variable: Sales

  
### ✅ Hitters.csv: 
This dataset predicts the salary of baseball players based on their independent variables.

- Independent variables: League, Division, New League
- Dependent variable: Salary

 
## 📌 Methods Used
  
### ✅ Simple Linear Regression:

- In the "Advertising.csv" dataset, we modeled the relationship between TV, Radio, and Newspaper ads and sales.
- The model’s accuracy was evaluated using R² score and Root Mean Squared Error (RMSE).
- Prediction results and the model equation were shown in a graph.
  
### ✅ Ridge Regression:

- In the "Hitters.csv" dataset, we used Ridge regression to predict players' salaries.
- L2 regularization was applied to prevent overfitting.
- Different alpha values (regularization coefficients) were tested to optimize the model.
- The best alpha value was chosen to obtain the final model results.

### ✅ Lasso Regression:
- In the "Hitters.csv" dataset, Lasso regression was applied to predict players' salaries.
- L1 regularization was used, which shrinks coefficients and sets some to zero.
- This method performs feature selection by eliminating less relevant variables.
- The best alpha value was found using cross-validation to optimize the model.

### ✅ ElasticNet Regression:
- In the "Hitters.csv" dataset, ElasticNet regression combined L1 (Lasso) and L2 (Ridge) penalties.
- It balances feature selection (Lasso) with stability (Ridge) when predictors are highly correlated.
- Cross-validation was used to determine the best alpha value and l1_ratio, ensuring an optimal model.

  
## 📌 Model Performance
For all models, performance was measured using:

- Root Mean Squared Error (RMSE): To evaluate prediction accuracy.
- R² Score: To determine how much of the variance in the dependent variable was explained by the model.
### Key Insights:
- Ridge regression improved prediction performance by controlling overfitting through L2 regularization.
- Lasso regression added the ability to select important features by reducing irrelevant ones to zero.
- ElasticNet regression combined the benefits of Ridge and Lasso, making it robust in datasets with correlated predictors.

This project demonstrates how advanced regression techniques like Lasso and ElasticNet enhance model performance through regularization and feature selection.
