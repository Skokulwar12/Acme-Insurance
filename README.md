📊 Acme Insurance - Exploratory Data Analysis & Linear Regression Modeling
This project focuses on analyzing the Acme Insurance dataset, with the objective of understanding customer patterns and building a predictive model to estimate insurance charges based on key demographic and health features.

🔍 Project Overview
This notebook walks through the complete data science workflow:

Exploratory Data Analysis (EDA)
Data Preprocessing (Encoding, Scaling)
Model Building (Linear Regression)
Model Evaluation
Through interactive visualizations and statistical techniques, the goal is to derive business insights and create a simple yet interpretable model for insurance cost prediction.

🧪 Key Components
📌 1. Exploratory Data Analysis (EDA)
Univariate Analysis using histograms, box plots, and distribution plots to understand the spread and shape of:
Age
BMI (Body Mass Index)
Charges
Bivariate Analysis using:
Scatter plots to understand correlations between numerical variables (e.g., age vs. charges)
Box plots to explore categorical-numerical relationships (e.g., smoker status vs. charges)
Correlation Heatmap (via Seaborn) to highlight strong relationships among variables

🧹 2. Data Preprocessing
Label Encoding for binary categorical variables such as sex and smoker
One-Hot Encoding for multi-class categorical variables like region
Feature Scaling using StandardScaler to normalize numerical variables, improving model performance and interpretability

📈 3. Linear Regression Modeling
Applied Linear Regression to predict charges (insurance premiums) based on encoded and scaled features
Model interpretation includes:
Coefficients and intercept
R² Score and Mean Absolute Error (MAE)
Residual analysis to check model fit

📊 4. Visual Insights
Interactive Plotly Histograms with marginal box plots for better visual understanding of distributions
Seaborn Heatmaps and Scatter Plots for statistical correlation analysis and trend spotting

🧰 Tech Stack
Python: Data handling and modeling
Pandas & NumPy: Data manipulation
Seaborn & Matplotlib: Static data visualization
Plotly Express: Interactive plots
Scikit-learn: Preprocessing, model building, and evaluation


📈 Future Work
Include additional models (e.g., Ridge, Lasso, Decision Tree)
Hyperparameter tuning
Feature importance ranking
Deployment using Flask or Streamlit
