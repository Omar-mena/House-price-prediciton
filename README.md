# House-prediciton

## Overview
This code uses several machine learning techniques to predict the change in median home prices in the United States based on several economic indicators. The indicators used in the analysis include the 30-year mortgage rate, the rental vacancy rate, and the Consumer Price Index. Additionally, the data is analyzed by using the Zillow Home Value Index (ZHVI) and the median sale price of homes.

## Data
The data used in this analysis is sourced from two different sources, the Federal Reserve Economic Data (FRED) and Zillow Research Data. The FRED data includes the 30-year mortgage rate, the rental vacancy rate, and the Consumer Price Index. The Zillow data includes the Zillow Home Value Index (ZHVI) and the median sale price of homes. The data is in csv format and is loaded into the script using the Pandas library. The data is then cleaned and preprocessed to ensure that it is in the correct format for analysis.

## Analysis
The script uses a Random Forest Classifier to predict the change in median home prices. The classifier is trained on a subset of the data and then used to make predictions on the remaining data. The script uses the scikit-learn library to perform the analysis. The script also includes functions to backtest the model and to evaluate the importance of each predictor variable.

## Results
The script is able to predict the change in median home prices with an accuracy of 65.37%. The permutation importance analysis shows that the Consumer Price Index, the 30-year mortgage rate, and the Zillow Home Value Index (ZHVI) are the most important predictor variables.

## Conclusion
The analysis shows that the Consumer Price Index, the 30-year mortgage rate, and the Zillow Home Value Index (ZHVI) are the most important predictor variables in determining the change in median home prices. However, the accuracy of the predictions is not very high, indicating that other factors may also be important in determining the change in median home prices.
