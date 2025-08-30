# Titanic-survival
**Aim** : This project aims to build a predictive model to determine the likelihood of a passenger surviving the Titanic disaster based on the provided features.

**Summary** : 
1. Data loading: Dataset downloaded from kaggle.
2. Exploratory data analysis (EDA): Visualized the distributions and explored the relationship between "Pclass" and "Fare".
3. Preprocessing: Used Label encoding for "Embarked" and "Sex", filled the mean and mode for missing values, deleted irrelevant columns ("Name", "Cabin", "Ticket"), applied log transformation for "Fare" column for more uniform distribution.
4. Model Training and Evaluation: Splitting the data into training and testing sets, and training several classification models including Logistic Regression, Decision Tree, Random Forest, Extra Trees, XGBoost, and CatBoost. The accuracy of each model was evaluated on the test set, and cross-validation was used for Logistic Regression.
5. Prediction and Submission: Using the trained CatBoost model (which showed the highest accuracy on the test set) to make predictions on the unseen test dataset and preparing a submission file.

## Tech Stack
**Languages**
![Python](https://img.shields.io/badge/python-3.9-blue.svg)

**Data Analytics**
![Pandas](https://img.shields.io/badge/pandas-1.3.4-blue.svg)
![Numpy](https://img.shields.io/badge/numpy-1.21.4-blue.svg)

**Data Visualization**
![Matplotlib](https://img.shields.io/badge/matplotlib-3.5.0-blue.svg)
![Seaborn](https://img.shields.io/badge/seaborn-0.11.2-blue.svg)

**Machine Learning & Modeling**
![Scikit-learn](https://img.shields.io/badge/scikit--learn-1.0.1-blue.svg)
![Random Forest](https://img.shields.io/badge/Random%20Forest-5882FA.svg?style=flat&logo=random-forest&logoColor=white)
![XGBoost](https://img.shields.io/badge/xgboost-1.5.0-blue.svg)
![LightGBM](https://img.shields.io/badge/lightgbm-3.3.1-blue.svg)
![CatBoost](https://img.shields.io/badge/catboost-1.0.1-blue.svg)

**Tools & Platform**
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Git](https://img.shields.io/badge/Git-F05032.svg?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
