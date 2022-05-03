# Customer-Churn-Prediction
## In this project, I use bank customer data to predict customer bahavior (whether churn or not)
## It includes 4 parts: Data Exploration, Frature Preprocessing, Model Training and Evaluation and Model Extra Funcationality

### Part1: Data Exploration
By employing Exploratory Data Analysis, we can better understand the raw data.It also helps us to bring up some hypothsis, which can be tested after training the model

### Part2: Feature Preprocessing
I used one-hot encoding and ordinal encoding on data, and performed stratify sampling to do train-test split since data is highly imbalanced.

### Part3: Model Training and Result Evaluation
I used 3 models to train: Logistic Regression, Random Forest and KNN. Grid Search is helpful to find the optimal hyperparameters for each model.

After training the model with best hyperparameters, I chose Confusion Matrix and ROC curve to evaluate model performance.

### Part4: Model Extra Functionality
Apart from having a decent model performance score, it's vital to know how to imterprete model and bring up recommendation for real business case.
