**House Price Prediction using Linear Regression**

**📌 Overview**

This project implements a Linear Regression model to predict house prices based on features such as:

Square footage

Number of bedrooms

Number of bathrooms

The goal is to build a regression model that learns the relationship between these features and the house price, and can make accurate predictions on unseen data.

**Dataset**

**Source:** Kaggle - House Prices: Advanced Regression Techniques

**Files used:**

train.csv: Training dataset containing house features and sale prices.

test.csv: Test dataset used for evaluation.

**Key columns used in this project:**

GrLivArea: Above ground living area (square feet)

BedroomAbvGr: Number of bedrooms above ground

FullBath: Number of full bathrooms

SalePrice: Target variable (house price)


**🧠 Model Workflow**

Load and clean the data

Feature selection (GrLivArea, BedroomAbvGr, FullBath)

Split data into training and testing sets

Train a Linear Regression model

Evaluate the model using R² score and RMSE

Make predictions on the test data

**📊 Results**

Model evaluation metrics:

R² Score: e.g., 0.82

Root Mean Squared Error (RMSE): e.g., 30,000

Note: Actual performance depends on data preprocessing and parameter tuning.

**📌 Dependencies**

Python 3.8+

pandas

numpy

matplotlib

seaborn

scikit-learn

jupyter




