# Housing Price Prediction - Regression Analysis  

## 📌 Overview  
This project analyzes a housing dataset to predict prices using various regression techniques. It includes:  
- **Exploratory Data Analysis (EDA)** with visualizations (box plots, bar charts, pair plots)  
- **Outlier Handling** using IQR method  
- **Feature Selection** (Forward/Backward Selection with Linear Regression)  
- **Model Comparison**:  
  - Linear Regression (with SequentialFeatureSelector)  
  - Random Forest Regressor  
  - Gradient Boosting Regressor  
- **Evaluation Metrics**: MSE and R² scores  

## 🔍 Key Steps  
1. **Data Preprocessing**:  
   - Binary encoding for categorical features (`yes/no` → `1/0`).  
   - Outlier clipping using IQR.  
2. **Feature Selection**:  
   - Forward/Backward selection to identify significant predictors.  
3. **Model Training & Evaluation**:  
   - Compared Linear Regression (with cross-validation), Random Forest, and Gradient Boosting.  
   - Visualized MSE and R² across methods.  

## 📊 Results  
- **Best Performing Model**: Gradient Boosting (lowest MSE, highest R²).  
- **Feature Importance**: `area`, `bathrooms`, and `furnishingstatus` were key predictors.  

## 🛠️ Tools Used  
- Python (Pandas, NumPy, Seaborn, Plotly)  
- Scikit-learn (Regression models, metrics, feature selection)  

## 🚀 How to Run  
1. Clone the repo.  
2. Install dependencies:  
   ```bash
   pip install pandas numpy scikit-learn plotly seaborn matplotlib  
