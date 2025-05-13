# flight_price_predection
Flight price prediction using linear regression
✈️ Flight Price Prediction Using Linear Regression
📌 Project Overview
This project focuses on building a predictive model to estimate flight prices based on various features such as the airline, source and destination cities, departure and arrival times, number of stops, and travel class. The goal is to understand the key factors influencing ticket prices and to build a model that can provide reasonably accurate predictions.

🔍 Dataset Highlights
The dataset contains information on:

Airline names

Source and destination cities

Flight class (Economy/Business)

Number of stops

Departure and arrival times

Flight ticket prices

The dataset was cleaned to remove irrelevant or redundant columns and encoded to handle categorical variables.

📊 Exploratory Data Analysis
Visualizations revealed variation in ticket prices across different airlines and routes.

Airlines like Air India and Vistara showed higher average ticket prices.

The number of stops and travel class significantly influenced the final ticket price.

🛠️ Data Preprocessing
Irrelevant columns such as flight numbers were dropped.

One-hot encoding was applied to categorical features.

The dataset was split into training and testing sets (70/30 ratio).

🤖 Model Building
A Linear Regression model was trained to predict flight prices. The model was evaluated using various metrics including:

Mean Absolute Error (MAE)

Mean Absolute Percentage Error (MAPE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

📈 Results
The model provides a decent baseline for flight price prediction.

Evaluation metrics suggest there's room for improvement using more advanced algorithms like Random Forest or Gradient Boosting.

Feature importance analysis shows that airline, class, and number of stops are among the top contributors to price prediction.

📌 Key Takeaways
Simple linear regression can be a useful starting point for understanding pricing trends.

Feature engineering and encoding play a crucial role in preparing the data for modeling.

Visualization helps uncover patterns that influence business decisions, such as pricing strategies.

🚀 Future Work
Experiment with advanced machine learning models (Random Forest, XGBoost).

Hyperparameter tuning for improved accuracy.

Integration into a web app for real-time predictions.
