# House_Cost_Prediction

Here's an overview of House price prediction using linear regression:

Dataset: The California housing dataset contains information about housing in California collected from the 1990 census. It includes features like median income, housing median age, average rooms, population, and median house value.

Linear Regression: A linear regression model attempts to find a linear relationship between the input features and the target variable (in this case, median house value). It assumes the relationship can be modeled as a linear combination of the input features.

Process:

a) Data preprocessing:
Load the dataset
Handle missing values if any
Split the data into features (X) and target variable (y)
Split into training and testing sets

b) Feature scaling:
Normalize or standardize features to ensure they're on similar scales

c) Model training:
Create a linear regression model
Fit the model to the training data

d) Prediction:
Use the trained model to make predictions on the test set

e) Evaluation:
Calculate metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared score
Interpretation:
Examine coefficients to understand feature importance
Analyze residuals to check model assumptions
