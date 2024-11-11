# Stock Price Prediction using Fundamental Analysis

## Summary
With the use of machine learning algorithms, we want to predict the next quarter's average stock price which ultimately indicates whether the stock will perform well in the future or not. We want to analyse the financial indicators and fundamental parameters of stock to predict the future price. As part of this project, we would be
- cleaning and merging the datasets into one
- analysing the corelation between the features and the target variable
- performing feature engineering
- training and testing different models
- evaluating and comparing the performance metrics of different models

## Dataset
1. [Fundamentals](https://www.kaggle.com/datasets/dgawlik/nyse?select=fundamentals.csv) - Fundamental parameters and financial indicators of different stocks in NYSE.
2. [Prices](https://www.kaggle.com/datasets/dgawlik/nyse?select=prices-split-adjusted.csv) - Daily prices of different stocks in NYSE.
3. [Securities](https://www.kaggle.com/datasets/dgawlik/nyse?select=securities.csv) - Sector information of different stocks in NYSE.

## Project Structure
1. `data` - contains the `raw` datasets and `clean` (or merged) datasets in their respective folders.
2. `data_cleaning`
    - `outputs` - contains intermediate results data
    - `.ipynb`file - code that cleans and merges the data.
3. `data_exploration`
    - `outputs` - contains intermediate results data
    - `.ipynb`file - code that explores the data, corelation between the features and target variable, feature engineering
4. `model_development`
    - `outputs` - contains intermediate results data
    - `.ipynb`file - code that builds, trains and tests different models
5. `model_analysis`
    - `outputs` - contains intermediate results data
    - `.ipynb`file - code that analyses the performance of all the developed models
6. `final.ipynb` - Model selection and conclusion about the project

## Contributors
1. [Aishwarya Prakash Bannimatti](mailto:abannima@uwo.ca)
2. [Owen David Roseborough](orosebor@uwo.ca)
3. [Eric Hout](ehout@uwo.ca)
4. [Arianna Song](asong43@uwo.ca)
5. [Andrew Scott Pitblado](mailto:apitblad@uwo.ca)
