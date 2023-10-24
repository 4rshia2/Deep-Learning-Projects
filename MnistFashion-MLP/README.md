# MLP Neural Network Project
This project implements a Multi-Layer Perceptron (MLP) neural network using Python and the NumPy library. It is used for classifying data from the MNIST Fashion dataset. The project includes the following steps:

1. Reading the Data: Initially, we read the training data (images) and their corresponding labels from the 'train.npy' file.

2. Displaying the Data: We visualize the training images, displaying a few sample images within the README.

3. Data Normalization: The project normalizes the data values by scaling them between 0 and 1.

4. Neural Network Layers: The neural network architecture consists of custom layers, and it includes feedforward and backpropagation methods for each layer.

5. Activation Function: The network uses a ReLU activation function, as an alternative to ELU, to avoid overflow issues.

6. Model Architecture: The neural network is designed with one hidden layer containing 32 neurons. The softmax activation function is used for classification.

7. Training the Model: Training is performed using stochastic gradient descent. The model is trained for a specified number of epochs, and the cross-entropy loss is used as the cost function.

8. Making Predictions: The model is capable of making predictions on input data.

Please note that this implementation is for educational purposes and may not be optimized for production use. Further improvements and optimizations can be made based on specific requirements and datasets.

### Usage
To use this MLP neural network, you can add additional layers, adjust hyperparameters, and provide your dataset for training.

### Dataset Folder

In this project, we utilize a dataset folder to store the necessary data for training and testing our MLP (Multi-Layer Perceptron) neural network. The dataset includes images from the Fashion MNIST dataset.

You can find the dataset folder [here](https://drive.google.com/drive/folders/1cCOnr9r4zGCV1Ihj6LGQYMaLfDfxs2jN?usp=drive_link), which contains the following files:
- `train.npy`: The training dataset with preprocessed image data.
- `labels.npy`: The corresponding labels for the training dataset.

Please ensure that you have downloaded these datasets and placed them in the appropriate directories before running the project.
