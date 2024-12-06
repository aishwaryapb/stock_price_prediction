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
1. `data` - contains the `raw` datasets and `clean` datasets in their respective folders and the final `merged_data.csv`.
2. `data_cleaning`
    - `outputs` - contains intermediate results data
    - `.ipynb`file - code that cleans and merges the data.
3. `data_exploration`
    - `outputs` - contains intermediate results data
    - `.ipynb`file - code that explores the data, corelation between the features and target variable, feature engineering
4. `model_development`
    - `outputs` - contains intermediate results data
    - Multiple `.ipynb`files - Each file corresponds to a different model and contains code for training, testing and evaluating a model.

## How to run the project
1. Open `data_cleaning/data_cleaning.ipynb` and run all the cells. This will generated the final `merged_data.csv` and `merged_scaled_data.csv`.
2. Open `data_exploration/data_exploration.ipynb` and run all the cells. This will generate all the plots to help analyse the final dataset. It also creates `data/clean/lr_data.csv` which will be used by the Linear Regression Model.
3. Run all the cells in the following files in the folder `model_development` to build, train, test and evaluate the respective models.
    - Linear Regression Model - `linear_model.ipynb`
    - Logistic Regression Model - `logistic_model.ipynb`
    - LSTM Model - `lstm_model.ipynb`
    - Random Forest Model - `random_forest_model.ipynb`


## Contributors
1. [Aishwarya Prakash Bannimatti](mailto:abannima@uwo.ca)
2. [Owen David Roseborough](orosebor@uwo.ca)
3. [Eric Hout](ehout@uwo.ca)
4. [Arianna Song](asong43@uwo.ca)
5. [Andrew Scott Pitblado](mailto:apitblad@uwo.ca)
