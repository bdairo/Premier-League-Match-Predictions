# European Premier League (EPL) Match Outcome Prediction

The European Premier League is the biggest soccer league in the world with an audience of approximately 4.7 billion viewers. In this project, we attempt to utilize various machine learning models to predict EPL match outcomes. The models use EPL data (2017/2018 to 2022/2023) scraped from https://fbref.com/en/comps/9/schedule/Premier-League-Scores-and-Fixtures

Features from the dataset were chosen based on how they may affect the results of the game

We also performed feature engineering to create new features, specifically creating features based on rolling averages tpo track the form of a team in the last five games

## Objectives

- Predict match outcomes: win or loss.
- Use a variety of machine learning techniques: 
        - AdaBoost with Naive Bayes and Decision Tree Base classifier
        - SVM with plynomial, rbf, linear, and sigmoid kernels
        - Random Forest
        - Multilayer Perceptron
- Hyperparameter optimization to enhance model performance.
- Analysis of feature importance to understand what factors most affect match outcomes.

## Getting Started

### Dependencies

- Python 3.8+
- Beautiful Soup
- Pandas, NumPy
- Scikit-Learn, PyTorch
- Optuna for hyperparameter tuning

## Running the Code

- Ensure that all the dependencies are installed
- The code is written in Jupyter notebooks. Each notebook is nameds appropruiately reflecting the models built in them. 