# TASK-3
Linear Regression Model on Housing Data 
Dataset: A housing dataset with features like area, bedrooms, bathrooms, etc., and a target column price.
Objective: Predict house price using Linear Regression.
Steps:
Load the dataset using pandas.
Separate features (X) and target (y).
Encode categorical variables using one-hot encoding (pd.get_dummies).
Split the data into training and test sets (80/20 split).
Train a Linear Regression model using sklearn.linear_model.LinearRegression.
Predict prices on the test data.
Evaluate the model using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R-squared (R²)
Print model coefficients to understand the impact of each feature.
Plot Actual vs Predicted prices to visualize model performance.
