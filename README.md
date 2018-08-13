# ML-Assignment-11-1
1. What are the three stages to build the hypotheses or model in machine learning?
2. What is the standard approach to supervised learning?
3. What is Training set and Test set?
4. What is the general principle of an ensemble method and what is bagging and
boosting in ensemble method?
5. How can you avoid overfitting ?

Assignment-11.2
Build the linear regression model using scikit learn in boston data to predict 'Price'
based on other dependent variable.
Here is the code to load the data
import numpy as np
import pandas as pd
import scipy.stats as stats
import matplotlib.pyplot as plt
import sklearn
from sklearn.datasets import load_boston
boston = load_boston()
bos = pd.DataFrame(boston.data)
