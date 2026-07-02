House Price Prediction using Supervised Learning
Project Overview

This project focuses on predicting house prices using various Supervised Learning Regression algorithms. The dataset contains information about residential properties such as area, bedrooms, bathrooms, location score, age of the property, distance from the city, and other important features. The goal is to build predictive models, compare their performance, and identify the best algorithm for accurate house price prediction.

Objectives
Understand the concepts of Supervised Learning.
Perform data preprocessing and exploratory data analysis (EDA).
Build a Simple Linear Regression model.
Build a Multiple Linear Regression model.
Apply Polynomial Regression.
Implement Gradient Descent techniques.
Evaluate model performance using different evaluation metrics.
Analyze Bias-Variance Trade-off.
Compare different regression models.
Dataset Information

Dataset Name: RealEstate_HousePrice_Dataset_4200.csv

Number of Records: 4200

Number of Features: 12

Features
Feature	Description
house_id	Unique House ID
area_sqft	Area of the house (Square Feet)
bedrooms	Number of Bedrooms
bathrooms	Number of Bathrooms
location_score	Location Rating
age_years	Age of Property
distance_city_km	Distance from City Center
lot_size_sqft	Land Area
has_garage	Garage Availability (0/1)
has_pool	Swimming Pool Availability (0/1)
renovation_years_ago	Years Since Last Renovation
house_price_inr	House Price (Target Variable)
Technologies Used
Python
Google Colab
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Machine Learning Algorithms
Simple Linear Regression
Multiple Linear Regression
Polynomial Regression
Batch Gradient Descent
Stochastic Gradient Descent
Mini-Batch Gradient Descent
Project Workflow
Import Libraries
Load Dataset
Data Exploration
Data Cleaning
Exploratory Data Analysis (EDA)
Feature Selection
Train-Test Split
Simple Linear Regression
Multiple Linear Regression
Polynomial Regression
Gradient Descent Implementation
Model Evaluation
Bias-Variance Analysis
Conclusion
Evaluation Metrics

The following evaluation metrics are used to measure model performance:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
Adjusted R² Score
Data Visualization

The following visualizations are included in this project:

Histogram
Correlation Heatmap
Scatter Plot
Pair Plot
Regression Line
Residual Plot
Actual vs Predicted Plot
Polynomial Regression Curve
Folder Structure
House-Price-Prediction/
│
├── RealEstate_HousePrice_Dataset_4200.csv
├── House_Price_Prediction.ipynb
├── README.md
├── requirements.txt
├── images/
│   ├── heatmap.png
│   ├── scatter_plot.png
│   ├── regression_line.png
│   └── polynomial_curve.png
└── report.pdf
Installation

Clone the repository:

git clone https://github.com/your-username/House-Price-Prediction.git

Go to the project folder:

cd House-Price-Prediction

Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn
Running the Project

Open the notebook in Google Colab or Jupyter Notebook.

Run all cells in sequence to:

Load the dataset
Explore the data
Train regression models
Evaluate model performance
Compare different algorithms
Results

The project compares different regression models based on their prediction accuracy. Performance is evaluated using MAE, MSE, RMSE, R² Score, and Adjusted R². The best-performing model is selected after comparing all evaluation metrics.

Learning Outcomes

After completing this project, you will understand:

Fundamentals of Supervised Learning
Regression techniques
Data preprocessing
Exploratory Data Analysis
Model training and testing
Performance evaluation
Bias-Variance Trade-off
Overfitting and Underfitting
Future Improvements
Apply Decision Tree Regression
Random Forest Regression
XGBoost Regression
Hyperparameter Tuning
Cross Validation
Model Deployment using Flask or Streamlit
Author

Yagna Patel

Diploma in Information Technology

Machine Learning Project
