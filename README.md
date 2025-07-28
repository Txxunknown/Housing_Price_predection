# Housing_Price_predection
using linear regression

California Housing Price Prediction 📈
This project focuses on analyzing and predicting California housing prices using the California Housing Dataset provided by scikit-learn. The aim is to understand the key factors affecting house prices and build a regression model that can accurately predict median home values.

OBJECTIVE:
-Perform Exploratory Data Analysis (EDA) on real-world housing data.
-Visualize relationships between features and target variable (MedHouseVal).
-Build and evaluate regression models to predict housing prices.

DATASET INFORMATION:
Source: fetch_california_housing() from sklearn.datasets
📍 Region: California, U.S.
Size: ~20,640 samples with 8 features
Target: Median House Value (price) in 100,000s USD

🛠️ TOOLS & LIBRARIES:
.Python 🐍
.Pandas & NumPy
.Matplotlib & Seaborn
.Scikit-learn (Linear Regression, R², MSE)

📊 STEPS PERFORMED:
-Data Loading & Cleaning
-Loaded dataset from sklearn
-Converted it into a DataFrame
-Renamed target column to price
-Exploratory Data Analysis (EDA)
-Distribution plots of features
-Correlation heatmap
-Scatter plots vs. target variable
-Preprocessing
-Feature-target separation
-Train-test-split (80/20)

MODELING
.Linear Regression

MODEL EVALUATION USING(ACCURACY):
-R² Score
-Mean Squared Error (MSE)
-Root Mean Squared Error (RMSE)
-Visual: Actual vs Predicted Plot
