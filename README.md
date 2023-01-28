# Waste_Classification_using_CNN

## Problem Statement

Despite the fact that garbage is accumulated and is difficult to manage, it is obvious that the environment's continual pollution has a negative influence on human health. This necessitates reform and the development of superior procedures through the classification of biodegradable and non-biodegradable waste.

## Datasets

22,564 photos in total are provided for the model to be trained, and 2513 images are accessible for testing.
 - Dataset link:https://www.kaggle.com/datasets/techsash/waste-classification-data
 
## Dependencies:
- Keras.
- Tensorflow.
- Python.
- Scikit-Learn.
- Numpy.
- Matplotlib.
- Seaborn.

## Data Augmentation

For additional data and better results, certain data augmentation techniques are used.

- Rescale.
- Rotation.
- Width_shift.
- Height_shift.
- Horizontal_flip.
- Fill_mode.

## Network Parameter:

- Rectifier Linear Unit (ReLU)
- MaxPooling.
- Dropout layers.
- Hidden Layers.
- Softmax(output layers).
- Optimizer:'Nadam'.
- Loss:'Categorical_Crossentropy'.
- Metrics:'Accuracy'.
