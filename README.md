# car_price_prediction
This project aims to predict the price of a car based on its features such as brand, model, year, mileage, fuel type, transmission, and engine capacity. The model leverages machine learning algorithms to analyze historical car data and estimate accurate prices for used cars.It's a simple yet brilliant project for beginners

📘 Overview

The goal of this project is to build a machine learning model that predicts the selling price of a car using multiple features. This can help car owners, buyers, and dealers understand pricing trends and make better decisions.

🧠 Approach
✅ Data Cleaning & Preprocessing

Converted string fields like year and kms_driven into numeric values

Replaced invalid values (e.g., “Ask for Price”)

Standardized fuel type, transmission, and car model names

Extracted first three words of the car name for meaningful categorization

✅ Feature Engineering

Encoded categorical variables

Removed unnecessary columns

Prepared clean structured dataset for modeling

✅ Model Training

Algorithms used:

Linear Regression

Lasso Regression

Random Forest Regressor (performed the best)

Evaluation metrics:

✅ R² Score

✅ Mean Absolute Error (MAE)

✅ Root Mean Squared Error (RMSE)

🛠️ Tech Stack
Category	Tools
Language	Python
Core Libraries	pandas, numpy, scikit-learn
Visualization	matplotlib, seaborn
Notebook	Jupyter / Google Colab
🎯 Key Outcome

Achieved a strong prediction performance, with Random Forest providing the most accurate results — making it ideal for real-world car price evaluation scenarios.

🚀 Future Enhancements

Add more attributes (engine size, mileage, owner count, location, etc.)

Hyperparameter tuning for improved accuracy

Deploy using Flask / Streamlit for live predictions
