# Task 5: Advertising Sales Prediction

## Objective
Predict sales based on advertising budgets for TV, Radio, and Newspaper using machine learning models: Linear Regression, Random Forest Regressor, and XGBoost Regressor.

## Steps Performed
1. Loaded the "Advertising.csv" dataset and cleaned column names.
2. Selected relevant columns: `TV`, `Radio`, `Newspaper`, and `Sales`.
3. Visualized data using **boxplots** to detect outliers.
4. Removed duplicates and outliers from the `Newspaper` column using the IQR method.
5. Split the dataset into features (`X`) and target (`y`), with `Sales` as the target.
6. Performed an 80-20 train-test split.
7. Trained and evaluated three models:
   - **Linear Regression**
   - **Random Forest Regressor**
   - **XGBoost Regressor**
8. Evaluated models using **R² score** and **Mean Absolute Error (MAE)**.

## Tools / Technologies Used
- Python 3.12 
- Pandas, NumPy, Seaborn, Matplotlib  
- scikit-learn (`LinearRegression`, `RandomForestRegressor`, `train_test_split`, `r2_score`, `mean_absolute_error`)  
- XGBoost (`XGBRegressor`)  
- Jupyter Notebook or Google Colab  

## Outcome / Results
- **Linear Regression**
  - R² Score: [89.89%]  
  - MAE: [1.24]  
- **Random Forest Regressor**
  - R² Score: [98.45%]  
  - MAE: [0.45]  
- **XGBoost Regressor**
  - R² Score: [98.16%]  
  - MAE: [0.62]  
- Random Forest and XGBoost provide more accurate predictions compared to Linear Regression.

