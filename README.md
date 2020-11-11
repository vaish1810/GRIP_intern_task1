# GRIP_intern_task1
This repository contains the task1 of a "DataScience & Business Analyst Internship" by Team #GRIP@THE SPARKS FOUNDATION.

The task was to "predict the percentage of students on the basis of number of study hours",using "SUPERVISED MACHINE LEARNING".

To execute this I have used a "LINEAR REGRESSION" approach.

LINEAR REGRESSION-> It is a kind of regression algorithm that aims at predicting a relationship between an Independant Variable(X) & a Dependant Variable(Y).When an unseen data is passed to the algorithm it make use of a function then calculates & maps input value for a continuous output value.

IMPORTANT LIBRARIES:
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline
from sklearn.model_selection import train_test_split 
from sklearn.linear_model import LinearRegression 
from sklearn import metrics
from sklearn.metrics import r2_score

CONCLUSION:
After applying The Simple Linear Regression algorithm on my dataset of 25 records to obtain "a relationship between no of study hours of student & their percentage scored",I found that "if a student studies for 9.25 hours"then the most probable percentage scored is approximately equal to 93.7 %,however this may not be always true "since the data is very small"
Upon Modle Evaluation I observed the Mean Absolute Error to be 4.18 & the Root Mean Squared Error 21.6
The Accuracy of our Model is 94.5%

