# Car Price Prediction with Machine Learning

## Project Overview

This project focuses on predicting the selling price of used cars using supervised machine learning techniques. Given features such as car age, fuel type, seller type, and kilometers driven, the goal was to build regression models that estimate the selling price.

## Dataset

The dataset used (`car data.csv`) contains information about second-hand cars, including the following columns:
- Car_Name
- Year
- Selling_Price
- Present_Price
- Kms_Driven
- Fuel_Type
- Seller_Type
- Transmission
- Owner

## Key Tasks Performed

- Loaded and explored the dataset
- Encoded categorical variables like fuel type, seller type, and transmission
- Split the data into features (`X`) and target (`Y`)
- Trained and evaluated two regression models:
  - Linear Regression
  - Lasso Regression
- Visualized predicted vs actual prices using scatter plots
- Measured performance using R² (R-squared score)

## Tools and Libraries Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- scikit-learn

## Results

- Both models performed reasonably well on training and test sets
- Visualizations helped confirm the alignment between predicted and actual prices
- R² score provided a quantitative measure of model accuracy

## Conclusion

This project demonstrates how regression models can be used to estimate used car prices. It involved standard data preprocessing, model building, evaluation, and visualization, making it a practical application of machine learning for pricing and valuation problems.
