# Auto_Price_Prediction

The objective of this project is to predict the price of automobiles based on a dataset of used cars. This problem is important as it can help individuals accurately estimate the value of used cars for buying or selling purposes.

This project involves the use of various regression-oriented machine learning algorithms such as CatBoost, LightGBM, XGBoost, along with RandomForest. A comparative analysis will be conducted on the performance of these algorithms. Additionally, each model will undergo hyperparameter optimization to ensure we extract the maximum performance potential from them.

# How it Works

* **Data Preprocessing**
<br>The missing values are handled, duplicates are removed, outliers are identified, and irrelevant features are eliminated. One-hot encoding is then applied to categorical features.
* **Data Splitting** <br> The data is divided into training, validation, and test sets.
* **Model Training**<br> Various models including CatBoostRegressor, LightGBM, XGBoost, and RandomForestRegressor are trained and their hyperparameters are tuned.
* **Model Evaluation** <br> Each model's performance is evaluated on the validation set based on the RMSE (Root Mean Squared Error) metric. The time taken for both training and prediction is also recorded.
* **Final Model Testing** <br> The best model, as determined by RMSE and computation time, is then employed to make predictions on the test set.
* **Comparison with a Baseline Model** <br> The results are compared to a baseline model generated using the DummyRegressor.

# Dependencies
To run the project, you will need to have the following libraries installed:

pandas: for data manipulation and analysis.
numpy: for numerical computations.
matplotlib and seaborn: for data visualization.
sklearn: for machine learning tasks and preprocessing.
catboost: for implementing CatBoostRegressor, a gradient boosting model.
lightgbm: for implementing LightGBM, a gradient boosting model.
xgboost: for implementing XGBoost, a gradient boosting model.
pandas_profiling: for generating profile reports from a pandas DataFrame.
ydata-profiling: for exploratory data analysis.
scipy: for scientific computations.

# Concslusions
This Auto Price Prediction project focuses on predicting the price of used cars. Multiple regression-oriented machine learning algorithms, including CatBoost, LightGBM, XGBoost, and RandomForest, were employed. The models underwent hyperparameter optimization, and their performance was evaluated using RMSE on the validation set. The best-performing model was selected for predictions on the test set. The project provides a valuable solution for accurately estimating automobile prices, aiding buyers and sellers in making informed decisions.
