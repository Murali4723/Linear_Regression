# Linear_Regression
1.Taxi_Price _prediction_ model building using Linear Regression


🚖 Taxi Fare Prediction Using Machine Learning

📌 Objective:
This project aims to predict taxi fares based on factors like trip distance, passenger count, time of day, and weather conditions using Linear Regression.
📂 Project Overview

Predicting taxi fares is crucial for both passengers and drivers to estimate ride costs. In this project, we preprocess data, apply feature engineering, train a Linear Regression model, and evaluate its performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.

🔍 Dataset Description

The dataset contains the following features:
Feature Name	Description
Trip_Distance_km_median	Distance of the trip in kilometers
Passenger_Count_median	Number of passengers
Base_Fare_median	Base fare charged for the trip
Per_Km_Rate_median	Fare charged per kilometer
Per_Minute_Rate_median	Fare charged per minute
Trip_Duration_Minutes_median	Duration of the trip in minutes
Time_of_Day_mode	Time of the trip (Morning, Afternoon, Evening, Night)
Day_of_Week_mode	Day of the trip (Weekday, Weekend)
Weather_mode	Weather conditions during the trip (Clear, Rain, Snow)
Trip_Price_median	Target variable - Total trip price
🛠 Technologies Used

    Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)

    Machine Learning: Linear Regression

    Data Preprocessing: One-Hot Encoding, Standard Scaling

    Evaluation Metrics: MAE, MSE, R² Score

🚀 Implementation Steps
✅ 1. Data Preprocessing

🔹 Handled missing values (if any)
🔹 One-Hot Encoding for categorical features
🔹 Feature Scaling using StandardScaler
✅ 2. Model Training & Evaluation

🔹 Trained a Multiple Linear Regression model
🔹 Performance Metrics:

    📉 Mean Absolute Error (MAE): 7.72
    📉 Mean Squared Error (MSE): 116.37
    📈 R-squared (R²): 0.814 (81.4% variance explained!)
✅ 3. Model Interpretation

🔹 Correlation Analysis → Checked feature relationships
🔹 VIF Analysis → Identified multicollinearity issues
📊 Key Visualizations

📌 Feature Distributions (Histograms)
📌 Correlation Heatmap (Feature relationships)
📌 Trip Distance vs. Fare (Scatter Plot)
📌 Residual Plot (Model Errors)


 ![download](https://github.com/user-attachments/assets/ac125f7d-410d-4e3f-964f-a80146b34b3c)
 ![download (1)](https://github.com/user-attachments/assets/12d3d110-3915-4a60-9237-b853810836bf)


📌 How to Run the Project Locally

1️⃣ Clone the Repository:

    git clone https://github.com/Murali4723/Linear_Regression.git
    cd taxi-fare-prediction

2️⃣ Install Dependencies:

    pip install -r requirements.txt

3️⃣ Run Jupyter Notebook:

    jupyter notebook

4️⃣ Open Taxi_Fare_Prediction.ipynb and execute the cells!


🔮 Next Steps & Improvements

    🔹 Experiment with advanced models (Random Forest, XGBoost)
    🔹 Integrate real-world factors like traffic & surge pricing
    🔹 Deploy the model as a real-time fare prediction API
📢 Feedback & Contributions

Feel free to fork the repository, open issues, or submit PRs! Let’s collaborate and make this even better. 🚀

🔗 Connect with me on LinkedIn: https://www.linkedin.com/in/seeram-murali-ganesh-9a6b62258/

📌 #DataScience #MachineLearning #TaxiFarePrediction #LinearRegression #Python #AI #PredictiveModeling
