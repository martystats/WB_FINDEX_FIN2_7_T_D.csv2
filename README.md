# WB_FINDEX_FIN2_7_T_D.csv2 – Health Condition Prediction Project

This project demonstrates a complete machine learning workflow, using the World Bank dataset `WB_FINDEX_FIN2_7_T_D.csv2` to predict health conditions in children under age 18.

## Project Structure

- **Jupyter Notebook (`Clearworkflows004.ipynb`)**  
  Includes the full pipeline: data loading, cleaning, feature engineering, model training, evaluation, and exporting results.

- **Model File (`best_random_forest_model.pkl`)**  
  Trained Random Forest model saved using `joblib` for future reuse without retraining.

- **Prediction Results (`model_predictions.csv`)**  
  CSV file comparing actual vs predicted values for model performance inspection.

## Key Steps Performed

1. **Data Cleaning & Preparation**  
   - Handled missing values, outliers, and inconsistent formats  
   - Encoded categorical variables  
   - Created new features (ratios, flags)

2. **Exploratory Data Analysis (EDA)**  
   - Visualized patterns and correlations  
   - Identified feature importance

3. **Model Training**  
   - Trained Linear Regression, Decision Tree, Random Forest, and Gradient Boosting  
   - Evaluated using MSE and R² scores  
   - Selected best model based on performance

4. **Model Export & Deployment**  
   - Saved the best model (`RandomForestRegressor`)  
   - Generated CSV with actual vs predicted values  
   - Uploaded all assets to GitHub for sharing and reuse

## Model Performance

- **Best Model**: Random Forest Regressor  
- **R² Score**: ~0.9999  
- **MSE**: ~0.03 (Very low)

## Author

**Martin Ude**  
GitHub: [martystats](https://github.com/martystats)

---

**Note:** All work was executed using Jupyter Notebook and Git Bash for version control and GitHub integration.
