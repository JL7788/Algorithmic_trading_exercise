# Algorithmic_trading_exercise
This code will allow you to implement algorithmic trading strategies with machine learning in order to automate trading decisions. In this exercise, data is used to help a financial advisory firm improve their existing trading signals with machine learning algoriths that will be able to adapt to newly generated data. 

<br />

## Technologies

This project leverages python 3.7 with Jupyter Notebook.

<br />

## Installation Guide

Before running the application first import the following. <br />

import pandas as pd<br />
import numpy as np<br />
from pathlib import Path<br />
import hvplot.pandas<br />
import matplotlib.pyplot as plt<br />
from sklearn import svm<br />
from sklearn.preprocessing import StandardScaler<br />
from pandas.tseries.offsets import DateOffset<br />
from sklearn.metrics import classification_report<br />
<br />

## Findings/Analysis 

The provided data was first loaded into a data frame and the rest of the provided data was ran in order to find the signals dataframe and generate the SMA_Fast and SMA_Slow columns. The first graph that was created was used to visualize the firms existing strategy returns, shown below.
<br />![](./Resources/graph1.png)<br />

I then used the SVC classifier model in order to run a new model with different predictions, shown below.
<br />![](./Resources/graph2.png)<br />

A third model was also created. Instead of using the SVC classfier, I opted to use the Decision Tree Classifier, shown below.
<br />![](./Resources/graph3.png)<br />

In conclusion, the SVC classifier is definitely the most accurate in terms of modeling predictions compared to that of the Decision Tree Classifier. Using the Decision Tree method, the data was extremely volatile compared to the strategy line and seems like a bad classifier to use as a testing method. I would stick to using the SVC classifier or test other classifiers instead of using DTC. 

## Contributors

Jeffrey Liu : Dev
UCB Fintech - Provided initial resources

<br />
## License
Trilogy Technology 
UCB Fintech Extension Program



