# Regression Models
**Objective:** The project aims to build and evaluate multiple regression models to predict `housing prices`. The dataset contains various features related to housing properties, and the goal is to train models that can accurately predict the prices of houses based on these features.

**Data Preprocessing:** The dataset is first loaded and split into training and validation sets.<br>
Missing values in numerical columns are filled using appropriate strategies, such as using the median or mean value.<br>
Categorical columns are encoded using one-hot encoding or custom mapping to convert them into numerical values.<br>

**Model Selection:** Several regression models are selected for evaluation, including Gradient Boosting, Bagging, AdaBoost, K Nearest Neighbors, Decision Tree, Random Forest, Gaussian Process, XGBoost, and LightGBM regressors.<br>
Each model is initialized with specific hyperparameters that are chosen based on prior knowledge or experimentation.<br>

**Model Evaluation:** A function called regressor_comparator is used to compare the performance of these models on the validation set.<br>
The function iterates over each model, trains it on the training set, and evaluates its performance using root mean square error (RMSE).<br>
The RMSE values for each model are printed, providing insights into how well each model performs in predicting housing prices.<br>

**Result Analysis:** The RMSE values obtained from the regressor_comparator function help in identifying the best-performing model.<br>
The model with the lowest RMSE is selected as the final model for predicting housing prices.<br>
