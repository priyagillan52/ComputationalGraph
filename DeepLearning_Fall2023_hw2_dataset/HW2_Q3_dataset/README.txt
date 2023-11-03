##### FALL 2023 Deep Learning HW2 Problem 3 Dataset #####

Apply your code on the toy dataset, which has 100 points.

The data points are in 2-D. 

The dataset have 4 classes in total, which are denoted by 0, 1, 2, 3 in Y for each class.

# The following Python code can be used to load the data for each data set specified by the "dataind". You may also use "Visualization_data.py" to visualize the distribution of the data.

import numpy as np

svpath = './Q3_data.npz'
data = np.load(svpath)

# X, array of shape [n_samples, n_features]
# Y, array of shape [n_samples]
X = data['X']
Y = data['Y']

