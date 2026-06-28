# Wind_Energy_Efficiency_Project

# 📌 Project Overview
--
Wind energy is one of the fastest-growing renewable energy sources. Monitoring turbine efficiency helps improve power generation, reduce maintenance costs, and optimize turbine performance.

This project uses Machine Learning algorithms to predict the efficiency of wind turbines based on real-world sensor measurements such as wind speed, ambient temperature, grid power, reactive power, turbine ID, month, hour, and other operational parameters.

Three regression models were implemented and compared to identify the best-performing algorithm.

# 🎯 Problem Statement

A wind farm operator wants to predict the efficiency of wind turbines using sensor data collected from turbines. Accurate prediction enables proactive maintenance, improved energy generation, and better operational planning.

# 📂 Dataset

The dataset contains 909,604 observations and multiple sensor features collected from wind turbines.

1. Features
2. Ambient Temperature
3. Grid Power (10 min Average)
3. NC1 Inside Temperature
4. Reactive Power
5. Wind Direction
6. Wind Speed Turbulence
7. Turbine ID
8. Hour
9. Month
10. Target Variable
11. Wind Energy Efficiency (Target)

# 🛠 Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Google Colab

# 📊 Exploratory Data Analysis (EDA)

The dataset was explored using:

Dataset overview
Missing value checking
Correlation heatmap
Feature selection
Data visualization

# 🤖 Machine Learning Models

The following regression algorithms were implemented:

1️⃣ Linear Regression  
R² Score: 23.86%
2️⃣ Decision Tree Regressor
R² Score: 87.18%
3️⃣ Random Forest Regressor ⭐
Best Performing Model
R² Score: 93.68%
MAE: 0.3997
RMSE: 0.6996

# 📈 Model Evaluation

Evaluation metrics used:

R² Score
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)

The Random Forest Regressor achieved the highest prediction accuracy and lowest prediction error among all tested models.

# 📉 Visualizations

The project includes:

Correlation Heatmap
Model Comparison Graph
Feature Importance Plot
Residual Plot
Actual vs Predicted Values
Performance Comparison

# 🏆 Results
Model	R² Score
Linear Regression	23.86%
Decision Tree	87.18%
Random Forest	93.68%
Best Model

# ✅ Random Forest Regressor

It demonstrated the highest predictive accuracy while maintaining the lowest prediction error.

# 📁 Project Structure
Wind_Energy_Efficiency/

│
├── data/
│   └── train.csv

│
├── notebooks/
│   └── Wind_Energy_Efficiency_Project.ipynb

│
├── images/
│   ├── Heatmap.png
│   ├── Model_Comparison.png
│   ├── Residual_Plot.png
│   ├── Feature_Importance.png
│   └── Actual_vs_Predicted.png

│
├── requirements.txt

├── README.md

└── LICENSE

# 🚀 Future Improvements

Hyperparameter Tuning (GridSearchCV/RandomizedSearchCV)
Cross Validation
XGBoost Regressor
LightGBM
CatBoost Regressor
Model Deployment using Streamlit or Flask
Real-time Prediction Dashboard
SHAP Explainability for feature interpretation

# 💻 Installation
git clone https://github.com/vaishnavipokhriyal083-sudo/Wind_Energy_Efficiency_Project/tree/main

cd Wind_Energy_Efficiency

pip install -r requirements.txt

jupyter notebook

# ▶️ Run the Project

Open Wind_Energy_Efficiency_Project.ipynb

Run all cells

View the results and visualizations

# 📌 Key Highlights
1. Large dataset with 909K+ records
2. Complete data preprocessing pipeline
3. Multiple regression models
4. Comprehensive model comparison
5. Performance evaluation using MAE, RMSE, and R² Score
6. Feature importance analysis
7. Residual analysis
8. High prediction accuracy using Random Forest
   
# 📚 Learning Outcomes

Through this project, I gained practical experience in:

1. Data Cleaning
2. Feature Engineering
3. Exploratory Data Analysis
4. Regression Modeling
5. Model Evaluation
6. Machine Learning Workflow
7. Data Visualization
8. Performance Comparison
9. Wind Energy Analytics

# 👩‍💻 Author

**Vaishnavi Pokhriyal**

Second-Year B.Tech Student | Machine Learning Enthusiast | Python Developer

# ⭐ If you found this project helpful, don't forget to star the repository!

**One suggestion to make your GitHub repository stand out even more:**

Create an images/ folder in your repository and add screenshots of:

📊 Correlation Heatmap
📈 Model Comparison Chart
🎯 Actual vs Predicted Plot
📉 Residual Plot
📌 Feature Importance Chart
