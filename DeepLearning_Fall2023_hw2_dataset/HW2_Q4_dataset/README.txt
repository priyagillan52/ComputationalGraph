##### FALL 2023 Deep Learning HW2 Problem 4 Dataset #####

The data points are in 2D, so you can easily visualize them in a 2D plane to help you understand
the distribution of those data points. We have 4 classes in total, which are denoted by 0, 1, 2, 3 in Y for each class.

# Use the following reference code to load the training and testing data. You may also use "Visualization_data.py" to visualize the distribution of the data.

import numpy as np

svpath = './Q4_data.npz'
data = np.load(svpath)

# X, array of shape [n_samples, n_features]
# Y, array of shape [n_samples]
X = data['X']
Y = data['Y']
