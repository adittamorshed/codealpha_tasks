# CodeAlpha Data Science Internship — Car Price Prediction

# 1. Project Overview:
This project is developed as part of the CodeAlpha Data Science Internship .  
The goal is to predict the selling price of used cars using machine learning techniques based on various features such as brand, year, fuel type, mileage, and transmission.


# 2. Objective:
To build a regression model that can accurately predict a car’s resale price using real-world used-car data.


# 3. Dataset:
Source: given in the instruction manual from codealpha (car data.csv)

Features:
 Column   - Description 

 a. name  -   Full name of the car (Brand + Model) 
 b. year  -   Manufacturing year 
 c. selling_price - Car’s resale price (Target variable) 
 d. km_driven     - Total distance driven 
 e. fuel  -   Type of fuel (Petrol, Diesl, etc.) 
 f. seller_type   - Dealer or Individual 
 g. transmission  - Manual or Automatic 
 h. owner - First, Second, or Third owner 


# 4. Tools & Libraries:
   - Python.
   - Pandas.
   - NumPy.
   - Scikit-learn.
   - Matplotlib.
   - Seaborn.


# 5. Project Workflow:

1. Data Loading & Cleaning: Removed duplicates and missing values, extracted car brand and calculated car age.
2. Feature Engineering: Converted text (categorical) data into numeric using One-Hot Encoding.
3. Model Building: Trained multiple regression models:
     - Linear Regression  
     - Random Forest Regressor  
     - Gradient Boosting Regressor
4. Model Evaluation: Evaluated using R² Score and Mean Absolute Error (MAE).
5. Results Comparison: Compared model performances and selected the best one.


# 6. Model Performance:

Linear Regression: r2 score- 0.55, mae- 1.81 
Random Forest Regressor:  r2 score- 0.60, mae-  1.34 
Gradient Boosting Regressor: r2 score- 0.70, mae-  1.18 

Best Model: Gradient Boosting Regressor  
Achieved ~70% accuracy with average prediction error of 1.18 lakh rupees.


# 7. Insights:
- Car price strongly depends on brand, car age, and fuel type.  
- Automatic transmission and Diesel cars tend to have higher prices.  


# 8. Key Learnings:
- Data preprocessing and cleaning for real-world datasets  
- Feature encoding (converting text to numbers)  
- Regression modeling and evaluation
- model tuning and feature selection


# 9. Internship Information:
Internship: Data Science Internship at CodeAlpha
Task: Car Price Prediction  
