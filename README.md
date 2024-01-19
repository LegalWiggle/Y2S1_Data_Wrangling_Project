# Data Wrangling on F1 Dataset

In this project, I tried and learned many data wrangling techniques such as cleaning and transformation. I also applied my transformed datasets into simple machine learning models to gauge and understand the effects of the wrangling process. 

Going through this project taught me a lot about how data transformations can affect the distribution and correlation of features, which subsequently affects the performance of machine learning models and its interpretability.

### Project Overview

Analyse and transform F1 dataset to be implemented in a machine learning model. Model looks to predict top F1 teams to allow for sponsorship evaluation.

### Data Cleaning 

Missing values and Outliers

- Detection of missing values and imputation methods. Missing date values were dropped and alt missing values were median imputed
- Detection of outlier values. Methods such as trimming, windsorization and capping were evaluated using Quartile-Quartile plots and model metrics

### Data Transformation

- Categorical data encoding, utilised Target Mean encoding.
- Numerical data transformation for feature distribution, used Yeo-Johnson transformer
- Used binning and discretization for skewed distributions

### Feature Engineering

- Feature standardization with Robust Scaling
- Polynomial expansion
- Dimensionality reduction with Principal Component Analysis
  
### Machine Models

- Naive Baseline and Logistic Regression
  
### Improvements

- Use more datasets and utilise more models
