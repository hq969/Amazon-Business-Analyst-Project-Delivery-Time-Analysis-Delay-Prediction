# 📦 Amazon Business Research Analyst Project: Delivery Time Analysis & Delay Prediction

## 📌 Overview

This project aims to analyze and predict delivery times for Amazon's logistics network using the Amazon Business Research Analyst Dataset. The goal is to identify key factors affecting delivery delays and build a predictive model to estimate delivery times more accurately.

By using Python, SQL, and Tableau, this project focuses on data-driven decision-making and process optimization.

## 🎯 Objectives

- Analyze the impact of factors such as traffic, weather, and vehicle type on delivery times.

- Predict expected delivery times based on historical data.

- Visualize delivery trends to help optimize logistics operations.

- Provide business insights for reducing delivery inefficiencies.

## 🗂 Dataset

The dataset contains order details, delivery personnel information, location coordinates, timestamps, weather conditions, and traffic density.

### Key Columns

```bash 
 - ID                          
 - Delivery_person_ID           
 - Delivery_person_Age          
 - Delivery_person_Ratings      
 - Restaurant_latitude          
 - Restaurant_longitude         
 - Delivery_location_latitude   
 - Delivery_location_longitude  
 - Time_Orderd                  
 - Time_Order_picked             
 - Weatherconditions            
 - Road_traffic_density         
 - Vehicle_condition           
 - Type_of_order                 
 - Type_of_vehicle               
 - multiple_deliveries          
 - Festival                      
 - City                          
 - Time_taken(min)
```

## 🛠 Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook (for analysis and modeling)

## 📊 Exploratory Data Analysis (EDA)

- Handle missing values and correct data types.
- Calculate Order Processing Time and Delivery Distance.
- Identify patterns in delivery delays across different factors (weather, traffic, vehicle type, etc.).

## 🔮 Predictive Modeling

- Feature Engineering: Extract meaningful insights from timestamps and geospatial data.
- Model Selection: Compare Linear Regression, Decision Trees, and XGBoost.
- Evaluate performance using RMSE and R-squared metrics.

## 📈 Insights & Recommendations

- Traffic Impact: Orders in 'Jam' conditions take 43.81% longer than normal.
- Weather Impact: 'Cloudy' and 'Foggy' conditions cause the highest delay.
- Vehicle Type: The fastest vehicle is: Motorcycle with an average delivery time of 24.03 minutes. The slowest vehicle is: Scooter with an average delivery time of 27.85 minutes.

## 🚀 How to Use This Project

```bash
# Clone the repo:

git clone https://github.com/yourusername/amazon-business-analyst-project.git

# Install dependencies:
pip install -r requirements.txt

# Run the Jupyter notebook:
jupyter notebook
```

## 📌 Future Improvements

- Enhance the predictive model using deep learning techniques.
- Optimize delivery routes using geospatial clustering.
- Develop a real-time dashboard with interactive insights.

## 👨‍💻 Author

Cassie GU

## 📜 License

This project is licensed under the MIT License.
