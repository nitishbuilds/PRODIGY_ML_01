Delhi NCR House Price Prediction using Machine Learning

This project predicts house prices in the Delhi NCR region using machine learning algorithms and structured data.

Dataset:
- Target variable: price
- Features include:
  - Area
  - Latitude, Longitude
  - Bedrooms, Bathrooms, Balcony
  - Status (new/old), Type of building
  - Furnished status, Lift, Parking, Landmarks

Tools & Libraries:
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

Workflow:
1. Data Cleaning
   - Dropped unnecessary columns like desc, Price_sqft
   - Imputed missing values with SimpleImputer

2. Feature Engineering
   - One-hot encoding for categorical features
   - Numeric and categorical preprocessing with ColumnTransformer

3. Model Training
   - Used LinearRegression
   - Train-test split (80-20)

4. Evaluation
   - Metrics: R² Score, MAE, RMSE
   - Visualizations: heatmap, predictions vs actual plot, feature importance

Results:
- Model performs decently with acceptable error range
- Interpretability maintained
- Dataset properly cleaned and handled with industry practices

Future Improvements:
- Try ensemble models (Random Forest, XGBoost)
- Hyperparameter tuning
- Deployment using Flask or Streamlit

Author:
Nitish Kumar Kushwaha
BCA Data Science Student
Machine Learning Intern
