
## Overview
This project aims to predict the maximum selling prices of HDB BTO flats based on features such as flat type, location, and year. Using a linear regression model, I achieved an R² score of 74.6% and a root mean squared error (RMSE) of 68,975 SGD.
## Features
- Data cleaning - removed missing values, NaN, and duplicate data.
- Employed a Linear Regression Model using Scikit-learn.
- Used one-hot encoding for categorical data. 

## Data
Data retrieved from https://data.gov.sg
## Setup
- Clone this repository 
``` 
git clone https://github.com/Beefsteakk/BTO-price-prediction.git
cd BTO-price-prediction
```
```
pip install -r requirements.txt
```
```
jupyter notebook BTOprediction.ipynb
```

## Disclaimer
This project is for personal learning and exploration only. Predictions made by this model are not guaranteed to be accurate and should not be used for financial or invesment decisions. Thank you.
