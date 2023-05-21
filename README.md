# Auto_Price_Prediction

The objective of this project is to predict the price of automobiles based on a dataset of used cars. This problem is important as it can help individuals accurately estimate the value of used cars for buying or selling purposes.

This project involves the use of various regression-oriented machine learning algorithms such as CatBoost, LightGBM, XGBoost, along with RandomForest. A comparative analysis will be conducted on the performance of these algorithms. Additionally, each model will undergo hyperparameter optimization to ensure we extract the maximum performance potential from them.

# How it Works

The approach taken in this project involves several steps:
* Data Preprocessing: The missing values are handled, duplicates are removed, outliers are identified, and irrelevant features are eliminated. One-hot encoding is then applied to categorical features.
* Data Splitting: The data is divided into training, validation, and test sets.
* Model Training: Various models including CatBoostRegressor, LightGBM, XGBoost, and RandomForestRegressor are trained and their hyperparameters are tuned.
* Model Evaluation: Each model's performance is evaluated on the validation set based on the RMSE (Root Mean Squared Error) metric. The time taken for both training and prediction is also recorded.
* Final Model Testing: The best model, as determined by RMSE and computation time, is then employed to make predictions on the test set.
* Comparison with a Baseline Model: The results are compared to a baseline model generated using the DummyRegressor.

# Dependencies:
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
