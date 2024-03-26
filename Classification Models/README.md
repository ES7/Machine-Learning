# Classification Models
**Data Exploration and Preprocessing:** The Iris dataset was loaded and explored to understand its structure and features. The target variable was identified as the "Species" column, which contains three classes: "Iris-setosa," "Iris-versicolor," and "Iris-virginica." No missing values were found in the dataset.<br>

**Data Visualization:** Various visualizations were created to understand the relationships between different features and the target variable. This included box plots, violin plots, and area plots.<br>

**Data Splitting:** The dataset was split into training and validation sets using a 90-10 split (90% for training, 10% for validation) with a random state of 2 for reproducibility.<br>

**Model Selection:** Several classifiers were selected for the task, including Logistic Regression, Support Vector Machine, K-Nearest Neighbors, Decision Tree, Random Forest, Gaussian Naive Bayes, XGBoost, etc.<br>

**Model Training and Evaluation:** Each classifier was trained on the training set and evaluated on the validation set using accuracy as the evaluation metric. Most classifiers performed well, except for the XGBoost Classifier, which encountered an issue with the target variable classes.<br>

**Issue Resolution:** The issue with the XGBoost Classifier was identified as an incorrect target variable format (string classes instead of numeric classes). Label encoding was used to convert the target variable to numeric classes before training the XGBoost Classifier.<br>

**Final Model Evaluation:** After resolving the issue with the XGBoost Classifier, all classifiers were retrained, and their accuracies were evaluated on the validation set. The accuracies ranged from approximately 90% to 100% for most classifiers, indicating good performance on the Iris dataset.<br>
