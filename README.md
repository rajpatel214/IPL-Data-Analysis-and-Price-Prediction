# IPL-Data-Analysis-and-Price-Prediction

This project aims to analyze IPL auction data, understand key factors influencing sold prices, and build predictive models to estimate player auction prices.

### **Project Overview**
- Exploratory Data Analysis (EDA) with visualizations.
- Feature selection to identify important predictors.
- Regression models to predict player sold price.
- Comparison of different models' performances.

### **Dataset**
- The dataset contains IPL auction player details like name, age, country, team, playing role, base price, sold price, and various performance metrics.

### **Installation**
```bash
pip install -r requirements.txt
```

### **How to Run**
1. Open `EDA.ipynb` to explore data.
2. Run `Feature_Selection.ipynb` to identify key features.
3. Train models using `Model_Training.ipynb`.

### **Technologies Used**
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Machine Learning (Scikit-learn, StatsModels)
- Data Visualization (Seaborn, Matplotlib)



### Explanation of Code and Human-Generated Content**  

#### **Exploratory Data Analysis (EDA)**
- **Dataset Overview**: Check missing values, column types, and summary statistics.
- **Visualizations**:
  - Count plots for different categories (Teams, Playing Roles, Countries).
  - Heatmap to check feature correlations.
  - Boxplots and violin plots to analyze Sold Price distribution.

#### **Feature Selection**
- Checking correlations of features with Sold Price.
- Evaluating Variance Inflation Factor (VIF) to remove multicollinear features.
- Identifying statistically significant predictors using OLS regression.

#### **Model Training & Evaluation**
- Regression models:
  - Ridge Regression (R^2 = 0.36, RMSE ≈ 293,780)
  - Decision Tree (R^2 = 0.22, RMSE ≈ 326,596)
- Comparison of models based on RMSE and R² scores.
