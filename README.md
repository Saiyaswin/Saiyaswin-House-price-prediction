# Saiyaswin-House-price-prediction
House price prediction using machine learning, feature engineering, and Gradient Boosting.
# House Price Prediction Using Machine Learning

## Project Overview
This project predicts residential house sale prices using machine learning techniques. It analyses property features such as overall quality, living area, garage capacity, bathrooms, construction year, and neighborhood.

## Objectives
- Perform exploratory data analysis (EDA) and clean the dataset.
- Analyse relationships between house features and sale prices.
- Build and compare Random Forest and Gradient Boosting regression models.
- Use feature engineering and hyperparameter tuning to improve predictions.
- Recommend suitable houses based on a buyer's budget, neighborhood, and minimum quality requirements.
- Provide an interactive interface for house price estimation.

## Dataset
The project uses the Ames Housing dataset, containing historical residential property sales information.

**Target variable:** `SalePrice`

**Note:** The dataset contains historical sales from 2006–2010. Predictions are estimates based on this data and are not current market valuations.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook
- ipywidgets

## Machine Learning Models
- Random Forest Regressor
- Gradient Boosting Regressor
- Tuned Gradient Boosting Regressor

## Reported Results
The current notebook reports the following results for the tuned Gradient Boosting model:

- **Test R²:** 91.37%
- **Mean Absolute Error (MAE):** $15,449.79
- **Root Mean Squared Error (RMSE):** $25,735.02
- **Mean cross-validation R²:** 87.18%

These results are based on the project's current train/test split and cross-validation procedure. Performance may differ on other datasets.

## Project Files
- `House_Price_Prediction_Final.ipynb` — analysis, model training, evaluation, reports, recommendations, and interactive prediction interface.
- `Data/data.csv` — input dataset.
- `top10_price_correlations.png` — supporting correlation chart.

## How to Run
1. Clone or download this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

   `pip install pandas numpy matplotlib seaborn scikit-learn ipywidgets jupyter`

4. Open `House_Price_Prediction_Final.ipynb` in Jupyter Notebook or VS Code.
5. Run the notebook cells in order.

Ensure the dataset path matches the notebook's expected location.

## Limitations
The model was trained on historical Ames, Iowa housing data. It should not be used as a guaranteed estimate of present-day prices in other locations. The buyer recommendation system filters historical records and does not identify currently available listings.

## Author
Saiyaswin
