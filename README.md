# California-Housing-Price-Prediction
This project focuses on predicting house prices using the California Housing dataset. By leveraging the XGBoost regressor and performing systematic hyperparameter tuning, the model achieves high accuracy in estimating median house values based on various geographic and demographic features.

🚀 Project Overview
The goal of this project is to build a robust regression pipeline to predict housing prices. The workflow includes data preprocessing, an initial model baseline, and optimization using GridSearchCV to maximize predictive power.

Key Features:
Dataset: 20,640 samples with 8 features.  

Model: XGBoost Regressor.  

Optimization: 5-fold Cross-Validation with GridSearchCV.  

Environment: Python 3 (Kaggle/VS Code/Jupyter).

Best Parameters Found:
learning_rate: 0.1  

max_depth: 7  

n_estimators: 300

🛠️ Tech Stack
Language: Python  

Libraries:

xgboost (Gradient Boosting)  

scikit-learn (Model Evaluation & Tuning)  

pandas & numpy (Data Manipulation)  

matplotlib (Visualization)
