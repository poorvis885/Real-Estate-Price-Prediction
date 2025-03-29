🏡 **House Price Prediction**


📌 **Overview**
This project predicts house prices using Linear Regression, Decision Trees, and XGBoost. The dataset used is California Housing Prices (alternative to Boston Housing Dataset).

📊 **Dataset**
The dataset consists of various features like:

Median Income

House Age

Total Rooms & Bedrooms

Population & Households

Latitude & Longitude

🔗 **Download the dataset using KaggleHub:**
import kagglehub
dataset_path = kagglehub.dataset_download("camnugent/california-housing-prices")


🚀 **Workflow**


**Data Preprocessing:**

Handling missing values

Encoding categorical variables

Feature scaling

**Model Training & Selection:**

Linear Regression

Decision Tree Regressor

XGBoost Regressor

**Performance Evaluation:**

RMSE (Root Mean Squared Error) is used to compare models

A visualization is generated to showcase performance


📈 **Results**
A bar plot compares RMSE values across models to determine the best-performing algorithm.

🔧 **Installation**
Install dependencies using:
pip install pandas numpy matplotlib seaborn scikit-learn xgboost kagglehub
🏃‍♂️ **Run the Project**
python house_price_prediction.py


💡 **Want to contribute? Feel free to fork, star ⭐, and raise issues!** 
🔗 **Connect with me:** https://www.linkedin.com/in/poorvi-shrivastava-4a34a9256/
