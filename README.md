# ML_Linear-Regression-Project

# Overview-
This project applies linear regression to analyze the King County House Sales dataset. The primary goal is to predict house prices based on various features such as square footage, number of bedrooms, bathrooms, and other characteristics of the homes. By utilizing linear regression, we aim to understand the relationship between these features and the price of the house, and build a model that can accurately estimate house prices.

# Dataset-
The dataset contains house sale prices for King County, which includes Seattle. It has over 20,000 records and includes features such as:

price: The price of the house (target variable)

bedrooms: Number of bedrooms

bathrooms: Number of bathrooms

sqft_living: Square footage of the house's interior

sqft_lot: Square footage of the lot

floors: Number of floors

waterfront: Whether the house is by a waterfront

view: Quality of the house’s view

condition: Overall condition rating of the house

grade: Construction grade of the house

yr_built: Year the house was built

zipcode: Location of the house

Data Source
The dataset was provided by the King County, USA and is publicly available for use in predictive modeling and analysis.

# Linear Regression

# Objective-
The primary objective of this project is to build a linear regression model that predicts the price of a house based on the available features. Linear regression helps in determining the weight (coefficient) each feature contributes towards predicting the target variable (house price).

# Methodology-
Data Preprocessing: Handling missing values
Outlier detection and treatment
Feature engineering (e.g., transforming categorical variables, feature scaling)

Exploratory Data Analysis (EDA): Visualizing relationships between the features and target variable (price)
Correlation analysis between numeric features

Model Building: Implementing linear regression using scikit-learn
Splitting the dataset into training and testing sets
Training the model on the training data and evaluating performance on test data

Model Evaluation: Metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²) were used to evaluate the model's performance.
Visualizations like residual plots were used to inspect the model’s fit and identify potential areas for improvement.

# Results-
The linear regression model was able to capture the general trends in the data and provided a reasonable prediction of house prices. Key insights include:

sqft_living showed a strong positive correlation with the price, indicating that larger homes tend to be priced higher.
Other features like the number of bathrooms and grade also had significant impacts on the price.
The model performance was as follows:

MAE: 448749.8980515179 (average error in predicting house prices)

MSE:452914712798.46497 (measure of average squared difference between actual and predicted values)

R² Score: 0.09256855509161599 (indicating how well the model explains variance in house prices).
