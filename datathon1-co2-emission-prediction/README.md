This folder contains my solution for one of the hackathon projects completed as part of the CSE 5045 Machine Learning course during my graduate studies. In this project, the goal was to predict CO2 emissions of vehicles using classical machine learning techniques — without relying on pre-built modeling libraries (e.g., sklearn.linear_model).

📌 Competition Link: [Kaggle Challenge](https://www.kaggle.com/competitions/ml-course-project-1)

📊 Problem Statement
Given a dataset of vehicle specifications and their fuel consumption details, the goal is to predict carbon emissions (g/km) using a regression model built from scratch using algorithms like Gradient Descent or Least Squares Estimation (LSE).

🛠️ Techniques & Workflow
The project follows a classical ML pipeline:

🔍 Exploratory Data Analysis (EDA)
Checked missing values.

Visualized target distribution and feature correlations.

Identified and handled highly null-rated features.

🧹 Data Cleaning
Dropped non-informative and high-missing columns: Make, Model, Vehicle class, CO2 rating, Smog rating.

Removed outliers using Z-score thresholding.

Filtered rare categorical values in Transmission and Fuel type.

🔢 Feature Engineering
Applied Target Encoding to handle high-cardinality categorical features like Transmission.

Used Polynomial Features and Standard Scaling for numerical features to improve model learning.

📈 Modeling (To be included in full notebook)
Linear regression model created from scratch using Gradient Descent or Least Squares Estimation.

Evaluation metric: Mean Squared Error (MSE).

🚫 Note: As per competition rules, no high-level ML libraries (like sklearn.linear_model) are used for modeling. All models are implemented manually.
