# Digit_Recognition

A deep learning CNN model that recognizes the digit present in an image using Keras , TensorFlow as backend

# Requirments

MNIST Dataset is used to train the model.

Intel i5 processor is used for training the model.

Python 3.3+ , Keras 2+ , Tensorflow 1.15+

# Contents

digit_recognition.ipynb:  This file contains the CNN deep learning model used in the project, code to generate  the data and train the model.

Weights.h5:  Contains the weights associated with the Trained Model.

# Training and Test Data

The Images are 28*28 size black and white Images

![image](https://user-images.githubusercontent.com/41421032/90872613-87345f00-e3ba-11ea-95e7-6f90143d2a74.png)

# Reading Data from Directory and Class Mapping

![image](https://user-images.githubusercontent.com/41421032/90876936-f1e89900-e3c0-11ea-95c1-691ce58d4d81.png)

![image](https://user-images.githubusercontent.com/41421032/90877085-20ff0a80-e3c1-11ea-9e0c-b8def1d685c2.png)

# Model

The model contains 3 CNN layers and 3 Hidden Layers.

![image](https://user-images.githubusercontent.com/41421032/90873377-b8615f00-e3bb-11ea-9218-5b5a7494ef77.png)

# Training the Model

![image](https://user-images.githubusercontent.com/41421032/90880802-b4870a00-e3c6-11ea-818e-349e8c7f1c29.png)

# Training and Test Result Visualization

![accuracy](https://user-images.githubusercontent.com/41421032/90880840-c49ee980-e3c6-11ea-8e54-93307c346cac.png)

![loss](https://user-images.githubusercontent.com/41421032/90880992-0039b380-e3c7-11ea-91f1-cb7d6f7e3dd3.png)

# Observation

1. The Model performs with an accuracy of > 90%.

2. As Due to complete absence of GPU I wasn't able to fine tune the Hyperparameters  but I am sure better results can be expected by tinkering around with the number of neurons and number of layers.
