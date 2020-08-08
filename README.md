# [New York City Taxi Fare Prediction](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction)
![alt text](https://miro.medium.com/max/2560/1*0Ov3bD5xNxszuJTBYJjX4w.jpeg)
This project aims to provide a solution for predicting the fare amount (inclusive of tolls) of a taxi ride in New York City given the pickup and dropoff locations. **The techniques utilized in this project include feature engineering with geological data, hyper-parameter tuning, and building LightGBM and CatBoost models based on 55M+ data.**

## Build status
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger) [![codecov](https://codecov.io/gh/yunglinchang/NYC_taxifare_prediction/branch/master/graph/badge.svg)](https://codecov.io/gh/yunglinchang/NYC_taxifare_prediction)

## Code style
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

## Data Science Pipeline
The contributing model consists of the following process:
* data preprocessing with NumPy and Pandas 
* feature engineering with geological data
* LightGBM and CatBoost model hyperparameter optimization with GridSearchCV
* RSME evaluation

Code files:
* nyctfp-catboost-model.ipynb
* nyctfp-lgb-model.ipynb

## Python Packages Used
* calendar
* CatBoost
* holidays
* LightGBM
* math
* Matplotlib
* NumPy
* os
* Pandas
* re
* reverse_geocoder
* scikit-learn

## Credits
This is the final project of the **Introduction to Machine Learning** course in 2018 Fall semester.

## License
MIT License

Copyright (c) [2019] [Yung-Lin Chang]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
