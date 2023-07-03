### Import library
```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
```
### Load data
```
dataset = pd.read_csv('name_of_dataset')
dataset.head()
```
### Split the dataset into the Training set and Test set
```
from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size = 1/3, random_state = 0)
```
### Create and fit the regression model
from sklearn.linear_model import LinearRegression
regressor = LinearRegression()
regressor.fit(X_train, y_train)
### View parameters
### Make predictions
### Plot Results





- Learn from being given "right answers"
- Regression: predict a number from many possible numbers
- Terminology: training set, (x,y): single training example, function f = model

- training set -> learning algorithm -> model
- feature + model -> prediction
