# Retail Sales Forecasting for German Drugstores

This project was to analyze historical sales data from a major German drugstore chain and build a predictive model to forecast daily sales across 1,115 stores. The focus was on data cleaning, feature engineering, exploratory data analysis, and implementing a robust Gradient Boosting model for accurate forecasting.

## Project Structure

- `store.csv`: Metadata of stores (store type, assortment, competition, promotion details)
- `train.csv`: Historical sales data (01/01/2013 to 31/07/2015)
- `test.csv`: Future period data for prediction (01/08/2015 to 17/09/2015)
- `Part1_Part2.ipynb`: Data loading, cleaning, merging, and exploratory data analysis
- `Part3A.ipynb`: Feature engineering and transformation
- `Part3B.ipynb`: Encoding, handling holidays/promotions, variable interaction
- `Part4_Part5.ipynb`: Model training (Gradient Boosting) and evaluation
- `StudentID11585796.pdf`: Final report detailing methodology, visualizations, findings, and conclusions

## Key Highlights

- Addressed missing values in key variables using rule-based imputation
- Created new features such as `CompetitionDurationInMonths` and `Promo2DurationInWeeks`
- Applied MinMax scaling for standardization and Label/One-Hot encoding for categorical data
- Identified key sales drivers (e.g., promotions, holidays, store types) through EDA and Gradient Boosting
- Achieved R² = 0.76 with a Gradient Boosting model, indicating a strong predictive performance
