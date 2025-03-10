Import required Libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
Load the dataset
from sklearn.datasets import load_breast_cancer
Explore the dataset variables
cancer.keys()
Read the breast cancer dataset
Standardize the data by scaling into Mean of eaual to 0 and variance of eaqual to 1
from sklearn.preprocessing import StandardScaler
#Decompose the feature names by applying the Principal Component Analysis Techniques from 30 to 2 dimensional components
from sklearn.decomposition import PCA
Check the shape of the dataset
scaled_data.shape
Check the shape of the dataset after decomposition
x_pca.shape
perform data visualization
