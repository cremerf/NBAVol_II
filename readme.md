### NBA Vol. II

The purpose of this project is to demonstrate the application of various predictive models on a given dataset. This project have a bunch of csv files already preprocessed in [NBA Vol. I](https://github.com/cremerf/NBAVol_I) to use as input datasets. The project uses Jupyter Notebook for exploratory data analysis, feature engineering, and model development.

This project utilizes [scikit-learn 1.2.2](https://scikit-learn.org/stable/) a widely used and popular Python library, as the core framework for implementing various machine learning models and algorithms.


#### Goals

The goals of this project are:

1) Define a prediction task
2) Select evaluation metrics and baseline models
3) Perform feature engineering and standardization
4) Train and use predictive models: Univariable and Multivariate Linear Regression, Classification
5) Understand how Gradient Descent works by implementing a Linear Regressor in Python

#### Data

NBA Season 21/22. You will find everything you need here [NBA Vol. I](https://github.com/cremerf/NBAVol_I).

#### Methods

The following methods were used in this project:

1) Exploratory Data Analysis
2) Feature Engineering
3) Standardization
4) Univariable Linear Regression
5) Multivariate Linear Regression
6) Classification
7) Gradient Descent

#### Results

1) Salary prediction (continuous variable): the MAE dropped almost by 50% between Baseline and Decision Tree. 
    * MAE Baseline: $ 6.948.493
    * MAE Decision Tree: $ 3.780.848

2) All Star selection (discrete variable / Logistic regression):
    * Baseline metrics: 
        a) F1: 0.724
        b) Recall: 0.669
        c) Precision: 0.788
        d) Accuracy: 0.984
    * After fine-tuning and feature engineering:
        a) F1: 0.769 (↑ 6%)
        b) Recall: 1 (↑ 49.47%)
        c) Precision: 0.625 (↓ 26%)


#### How to Use

1) Remember, **before** installing all the dependencies with **!pip install -r requirements.txt**, build a virtual/working env to avoid conflict between your local installations and the packages used in this project. 


#### Conclusion

To summarize, this project showcases the successful implementation of several predictive models on a specific dataset, achieving the predefined objectives and generating valuable insights. The project's outcomes can serve as a useful reference for similar predictive modeling tasks and highlight the practical application of machine learning in data analysis and decision-making


