# Big-Mart-Sales-Regression-model
A machine learning model built to predict the sales of bigmart dataset

Here I have cleaned the dataset by filling up numeric null values with their respective mean and categorical values with their mode, and removed some irrelavent columns and combined some.

Then I explored the distribution components of numeric columns, and contributional part of categorical columns.

Hence the EDA is completed, so I encoded the data using OneHot encoding and Label Encoding for Categoircal and numeric columns respectievly

Towards the Model development, I have used Linear Regression, Lasso Model, Decision Tree, Random Forest, Extra Trees, Ridge and Gradient Boosting Regressor. From the results Linear regression has lowest CV score, so the efficiency for linear regression is high. Hence Linear Regression is suited for the above dataset
