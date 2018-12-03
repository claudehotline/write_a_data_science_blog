# Seattle Airbnb Data Analysis
A Udacity DSND project using CRISP-DM to Analyze Seattle Airbnb Dataset.

# Installation
The development tool of this project is Jupyter notebook and the Anaconda distribution of Python 3.7. Other necessary python libraries are * listed below:
* pandas 0.23.4
* nmupy 1.15.4
* matplotlib 3.0.1
* seaborn 0.9.0
* scikit-learn 0.20.1

# Project Motivation
**CRISP-DM** standards for Cross-Industry Standard Process for Data Mining and the whole includes 6 steps — business understanding, data understanding, data preparation, modeling, evaluation, and deployment. With the respect of the main business of Airbnb, we are interested in solving the following questions:
* What is the distribution of the listings price?
* Which neighborhood has the most listings?
* Can we predict the price of a new listing based on some of its attributes?

# Technique
**Missing value:** for columns with missing value proportion greater than 30%, drop those columns from the dataset; for numerical columns, fill in missing values with the column mean value.

**Categorical column:** for each categorical column, create dummy columns for the column.

**Value prediction:** for predicting the price of a new listing, this project uses the linear regression model provided by scikit_learn.

# File Descriptions
**data:** contains the Seattle Airbnb dataset CSV files.

**Airbnb Seattle dataset.ipynb:** Jupyter notebook with python code performing the dataset analysis.

# How to Interact
Medium post: https://medium.com/@claudehotline/seattle-airbnb-data-analysis-401b46203590. 
