# Neural Networks

This is a set of code used to demonstrate basic neural network concepts.

## Notebooks

The notebooks contain code to demonstrate the concepts and how they are 
applied in code and data.

### 01_Gradient_Descent.ipynb

This shows the concept of optimization with gradient descent. 

**Main Concepts:**

*   Computation of the parameter gradients
*   Computation of the gradient steps
*   Optimizing the parameters using the gradients

### 02_Keras.ipynb

This shows the usage of Keras and the usage of activation functions with
stack of linear functions.

**Main Concepts:**

*   How keras makes model creation simpler
*   How activation functions allow learning non-linearity
*   Dense network introduction

### 03_Dense_Networks.ipynb

This shows some preprocessing steps on real world data and practical things
to set up before training a network.

**Main Concepts:**

*   Basic imputation
*   Training, Validation, and Test splits
*   Numerical encoding
*   Dense networks
*   Training checkpoints
*   Early stopping

### 04_Convolutional_Network.ipynb

This shows how to train a convolutional network. Loading images from numeric
data format, displaying images on the notebook, and model training are the
concepts shown in this notebook.

**Main Concepts:**

*   Image from numeric formats
*   Convolutional networks

### 05_Transfer_Learning.ipynb

This shows how to leverage pretrained models on use cases with low amount of
data.

**Main Concepts:**

*   Loading images from image formats
*   Loading pretrained models
*   Adding layers on pretrained models
*   Setting trainable layers on pretrained models

### 06_Recurrent_Network.ipynb

This notebook shows how to generate models that consumes sequences of data 
with recurrent networks.

**Main Concepts:**

*   Fixed value outputs from sequences
*   Masking on variable length sequences
*   Recurrent networks

## Data

The `data` folder contains the example datasets used to run the code in the
`notebook` directory. Most of them are smaller versions of the datasets for
the sake of reasonable run times.
