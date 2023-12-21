# Overview
In the rapidly evolving automotive market, the ability to accurately predict used car prices is crucial for both sellers and buyers. This project aims to develop a machine learning model to predict the sale prices of used cars. Using a rich dataset and advanced analytical techniques, we strive to provide precise predictions that cater to the needs of individual sellers, dealerships, and other stakeholders in the used car market.
Data Description

The project utilizes a comprehensive dataset, encompassing various attributes of used cars such as:

S.No. : Serial Number
Name : Name of the car which includes Brand name and Model name \
Location : The location in which the car is being sold or is available for purchase (Cities) \
Year : Manufacturing year of the car \
Kilometers_driven : The total kilometers driven in the car by the previous owner(s) in KM \
Fuel_Type : The type of fuel used by the car (Petrol, Diesel, Electric, CNG, LPG) \
Transmission : The type of transmission used by the car (Automatic / Manual) \
Owner : Type of ownership \
Mileage : The standard mileage offered by the car company in kmpl or km/kg \
Engine : The displacement volume of the engine in CC \
Power : The maximum power of the engine in bhp \
Seats : The number of seats in the car \
New_Price : The price of a new car of the same model in INR 100,000 \
Price : The price of the used car in INR 100,000 (**Target Variable**)

This dataset provides a holistic view of factors influencing used car prices.

# Methodology
The methodology includes several key stages:

Data Preprocessing: Cleaning and preparing the data for analysis. \
Exploratory Data Analysis: Understanding data distributions and relationships. \
Feature Engineering: Creating new features to improve model performance. \
Model Development: Employing various machine learning algorithms for regression. \
Model Evaluation: Using metrics like R-squared and MSE to assess model performance.

# Results
Analysis showed Ridge Regularization and Linear Regression as top performers, improving test set performance by around 12%. KNN model excelled in training but dropped by 5.5% in testing. Ridge Regularization, adept at handling multicollinearity and numerous features, demonstrated robust performance with 58% accuracy in training and 70% in testing.

# Conclusion
Hyperparameter tuning improved Decision Tree and Random Forest models, achieving 68.5% and 68.7% accuracy respectively. This tuning made models simpler and more transparent, beneficial for stakeholder explanation. Future work includes expanding the dataset for enhanced predictive accuracy and market representation.

# Acknowledgments
This project was a part of the MIT - Applied Data Science Program. Special thanks to MIT Professional Education for their support and resources, which were instrumental in the successful completion of this project.
