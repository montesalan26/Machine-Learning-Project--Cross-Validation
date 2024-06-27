# Machine-Learning-Project--Cross-Validation
In this project,, i analyzed 3 different datasets. Afer analyzing the datasets, i created two different target columns. After creating the target columns, I used cross validation to determine what machine learning model worked best for this project, between, Random Forest Regressor, Decision Tree Regressor and Linear Regression.

Required Python Libraries for project:

import pandas as pd  
from matplotlib import pyplot as plt  
import numpy as np  
from sklearn.linear_model import LinearRegression  
from sklearn.metrics import mean_absolute_error, mean_absolute_percentage_error, make_scorer, mean_squared_error  
from sklearn.model_selection import cross_val_score, train_test_split, KFold  
from sklearn.tree import DecisionTreeRegressor  
from sklearn.ensemble import RandomForestRegressor  
from sklearn.dummy import DummyRegressor  
