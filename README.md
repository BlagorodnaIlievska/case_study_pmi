# PMI Case Study 
This is a repository that covers the source code for predicting product success on a hypothetical set of products 
It goes under the following order:
  - data_exploration.ipynb for general overview of the data
  - baseline_classifier.ipynb as a starting point
  - categorical_feature_engineering_exploration.ipynb for binning the categorical features 
  - improved_classifiers_using_binned_features.ipynb for bulding additional models using the binned features
  - encode_test_set.ipynb for mapping the encoding in the train set to the test set
  - new_score_data.xlsx a test set for checking the model performances 
  
  
  Used packages
  import itertools

# Data Science
pandas as pd
import numpy as np
import math

# ML
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.linear_model import LogisticRegression
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import accuracy_score, confusion_matrix, recall_score, precision_score
from sklearn.ensemble import RandomForestClassifier
from sklearn.model_selection import GridSearchCV
from sklearn.metrics import roc_curve, auc, f1_score

# Plotting
import seaborn as sns
import matplotlib.pyplot as plt
 
