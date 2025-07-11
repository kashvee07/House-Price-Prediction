# House-Price-Prediction🏠 House Price Prediction using Regression
This project uses a real-world dataset from Kaggle to build a machine learning model that predicts house sale prices based on various features like square footage, number of rooms, quality, and neighborhood.

📁 Dataset
Source: Kaggle - House Prices: Advanced Regression Techniques

train.csv contains data on 1,460 houses and 80+ features

Target variable: SalePrice

🎯 Objective
To accurately predict SalePrice (continuous variable) using numerical and categorical house attributes. Also to understand which features are most important in determining the price.

🧪 Models Used
Model	Scaled	RMSE (Test)	R² Score	Notes
Linear Regression	✅	xxx	xxx	Baseline model
Ridge Regression	✅	xxx	xxx	Better generalization with α
Lasso Regression	✅	xxx	xxx	Feature selection benefit

Replace xxx with your actual results.

🧰 Tools & Technologies
Python, pandas, numpy

Seaborn, matplotlib

Scikit-learn

Google Colab

🔍 Key Steps
📊 EDA (Exploratory Data Analysis)
Checked feature correlations with SalePrice

Identified top numeric predictors: GrLivArea, OverallQual, GarageCars, TotalBsmtSF

Visualized distributions and relationships using scatterplots, boxplots, and heatmaps

🧹 Data Preprocessing
Filled missing values (e.g., GarageYrBlt, MasVnrArea)

Removed high-missing or non-informative columns

One-hot encoded categorical features

🤖 Model Building
Used LinearRegression, Ridge, and Lasso
Evaluated using RMSE and R² Score

📈 Results
Model explains a significant portion of variance in SalePrice (~80–90% R²).

📌 Future Improvements
Feature selection using SelectKBest or PCA

Hyperparameter tuning using GridSearchCV can further improve performance 

Deployment using Streamlit

Include test set predictions for leaderboard submission (if doing Kaggle comp)

