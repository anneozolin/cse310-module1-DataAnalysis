# Overview

As a software engineer, my goal is to expand my skills in data analysis and learn how to derive meaningful insights from real-world datasets. This project focuses on analyzing house pricing data to explore factors that influence property values. By conducting this analysis, I aim to deepen my understanding of exploratory data analysis (EDA), data visualization, and regression modeling, which are crucial skills for developing data-driven software solutions.

The dataset analyzed in this project was obtained from Kaggle. It contains information on various properties, including features such as area, garage spaces, bathrooms, fireplaces, marble finishing, and whether the house has multiple floors. These variables were explored to understand their impact on house prices.

The purpose of writing this software was to conduct a thorough analysis of the dataset, answer specific questions about the factors influencing house prices, and build a linear regression model to predict property values based on selected features. This project also serves as a practical exercise in data manipulation, visualization, and predictive modeling.

[Software Demo Video](http://youtube.link.goes.here)

# Data Analysis Results

The main questions explored and the answers derived through this analysis are:

1. Do categorical features like garage spaces, bathrooms, fireplaces, marble finishing, and multiple floors significantly impact house prices?

    Yes, the box plots revealed that certain features, such as having more garage spaces or multiple floors, were associated with higher prices. However, the effect of features like marble finishing was less significant.

2. What is the distribution of house prices in the dataset?
    The distribution of house prices was found to be right-skewed, indicating that most properties are priced in the lower range, with a few high-priced outliers.

3. Is there a linear relationship between house prices and other continuous variables?
    A positive linear correlation was identified between house prices and features like area and garage spaces. However, the relationships with other variables were weaker, indicating that not all features contribute equally to price predictions.

# Development Environment

The project was developed using the following tools:

* Jupyter Notebook: for interactive coding and data visualization.
* Python: the programming language used for data analysis.
* Libraries:
    * pandas for data manipulation.
    * seaborn and matplotlib for data visualization.
    * scikit-learn for building and evaluating the regression model.

# Useful Websites

{Make a list of websites that you found helpful in this project}
* [Seaborn Documentation](https://seaborn.pydata.org/)
* [Scikit-Learn Documentation](https://scikit-learn.org/stable/)

# Future Work

In the future, I plan to:

* Refine the model by experimenting with feature engineering and selecting more relevant variables to improve the R² score.
* Expand the analysis by incorporating non-linear models like decision trees or random forests for better predictions.
* Automate the process by creating a user-friendly interface that allows users to input property features and get price estimates directly.